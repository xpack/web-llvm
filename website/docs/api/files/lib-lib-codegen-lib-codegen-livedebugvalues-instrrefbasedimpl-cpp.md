---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `InstrRefBasedImpl.cpp` File

<p>This is a separate implementation of <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a>, see <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/livedebugvalues-cpp">LiveDebugValues.cpp</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a> for more information. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">llvm/CodeGen/LexicalScopes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">llvm/CodeGen/MachineInstrBundle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevalue-h">llvm/CodeGen/PseudoSourceValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">llvm/CodeGen/TargetFrameLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">llvm/Support/GenericIteratedDominanceFrontier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">llvm/Support/TypeSize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">llvm/Transforms/Utils/SSAUpdaterImpl.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;climits&gt;
#include &lt;cstdint&gt;
#include &lt;functional&gt;
#include &lt;queue&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/livedebugvalues-h">LiveDebugValues.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-instrrefbasedimpl-cpp-">anonymous{InstrRefBasedImpl.cpp}</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/transfertracker">TransferTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracker for converting machine value locations and variable values into variable locations (the output of <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a>), recorded as DBG_VALUEs specifying block live-in locations and transfers within blocks. <a href="/web-llvm/docs/api/classes/transfertracker/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/transfertracker/transfer">Transfer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> of all changes in variable locations at a block position. <a href="/web-llvm/docs/api/structs/transfertracker/transfer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/transfertracker/resolveddbgvalue">ResolvedDbgValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores the resolved operands (machine locations and constants) and qualifying meta-information needed to construct a concrete DBG_VALUE-like instruction. <a href="/web-llvm/docs/api/structs/transfertracker/resolveddbgvalue/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/transfertracker/usebeforedef">UseBeforeDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> of a use-before-def: created when a value that's live-in to the current block isn't available in any machine location, but it will be defined in this block. <a href="/web-llvm/docs/api/structs/transfertracker/usebeforedef/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/transfertracker/locationandquality">LocationAndQuality</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaphi">LDVSSAPhi</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an SSA PHI node for the SSA updater class. <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaphi/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablockiterator">LDVSSABlockIterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Thin wrapper around a block predecessor iterator. <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablockiterator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock">LDVSSABlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Thin wrapper around a block for SSA Updater interface. <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssablock/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaupdater">LDVSSAUpdater</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility class for the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> interface: tracks blocks, PHIs and values while <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> is exploring the CFG. <a href="/web-llvm/docs/api/classes/anonymous-instrrefbasedimpl-cpp-/ldvssaupdater/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4">SSAUpdaterTraits&lt;LDVSSAUpdater&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Template specialization to give <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> access to CFG and value information. <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits/phi-iterator-6378c5910886d7a8595c30cf77f6df16">PHI_iterator&lt;LDVSSAUpdater &gt;::PHI_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator for PHI operands. <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits/phi-iterator-6378c5910886d7a8595c30cf77f6df16/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afba85f0d2bfd9c12500fa7c93a6e3f91">EmulateOldLDV</a>("emulate-old-livedebugvalues", cl::Hidden, cl::desc("Act like old LiveDebugValues did"), cl::init(false))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ba0b6b6e6515414554417edb06e073">StackWorkingSetLimit</a>("livedebugvalues-max-stack-slots", cl::Hidden, cl::desc("livedebugvalues-stack-ws-limit"), cl::init(250))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"livedebugvalues"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is a separate implementation of <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a>, see <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/livedebugvalues-cpp">LiveDebugValues.cpp</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a> for more information.</p>


<p>This pass propagates variable locations between basic blocks, resolving control flow conflicts between them. The problem is SSA construction, where each debug instruction assigns the <em>value</em> that a variable has, and every instruction where the variable is in scope uses that variable. The resulting map of instruction-to-value is then translated into a register (or spill) location for each variable over each instruction.</p>


<p>The primary difference from normal SSA construction is that we cannot <em>create</em> PHI values that contain variable values. CodeGen has already completed, and we can't alter it just to make debug-info complete. Thus: we can identify function positions where we would like a PHI value for a variable, but must search the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> to see whether such a PHI is available. If no such PHI exists, the variable location must be dropped.</p>


<p>To achieve this, we perform two kinds of analysis. First, we identify every value defined by every instruction (ignoring those that only move another value), then re-compute an SSA-form representation of the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>, using value propagation to eliminate any un-necessary PHI values. This gives us a map of every value computed in the function, and its location within the register file / stack.</p>


<p>Secondly, for each variable we perform the same analysis, where each debug instruction is considered a def, and every instruction where the variable is in lexical scope as a use. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> propagation is used again to eliminate any un-necessary PHIs. This gives us a map of each variable to the value it should have in a block.</p>


<p>Once both are complete, we have two maps for each block:</p>


<ul class="doxyList ">
<li>Variables to the values they should have,</li>
<li>Values to the register / spill slot they are located in. After which we can marry-up variable values with a location, and emit DBG_VALUE instructions specifying those locations. Variable locations may be dropped in this process due to the desired variable value not being resident in any machine location, or because there is no PHI value in any location that accurately represents the desired value. The building of location lists for each block is left to DbgEntityHistoryCalculator.</li>
</ul>

<p>This pass is kept efficient because the size of the first SSA problem is proportional to the working-set size of the function, which the compiler tries to keep small. (It's also proportional to the number of blocks). Additionally, we repeatedly perform the second SSA problem analysis with only the variables and blocks in a single lexical scope, exploiting their locality.</p>




#### Terminology {#autotoc_md62}


<p>A machine location is a register or spill slot, a value is something that's defined by an instruction or PHI node, while a variable value is the value assigned to a variable. A variable location is a machine location, that must contain the appropriate variable value. A value that is a PHI node is occasionally called an mphi.</p>


<p>The first SSA problem is the "machine value location" problem, because we're determining which machine locations contain which values. The "locations" are constant: what's unknown is what value they contain.</p>


<p>The second SSA problem (the one for variables) is the "variable value
problem", because it's determining what values a variable has, rather than what location those values are placed in.</p>


<p>TODO: Overlapping fragments Entry values Add back DEBUG statements for debugging this Collect statistics</p>


<div class="doxySectionDef">

## Variables

### EmulateOldLDV {#afba85f0d2bfd9c12500fa7c93a6e3f91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EmulateOldLDV("emulate-old-livedebugvalues", cl::Hidden, cl::desc("Act like old LiveDebugValues did"), cl::init(false))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/transfertracker/#a787205c8858064b56bad25b823faf3d0">TransferTracker::transferMlocs</a>.</p>

</div>
</div>

### StackWorkingSetLimit {#ad6ba0b6b6e6515414554417edb06e073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; StackWorkingSetLimit("livedebugvalues-max-stack-slots", cl::Hidden, cl::desc("livedebugvalues-stack-ws-limit"), cl::init(250))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a0ec8c44bc2b0efa41c2a6583f9d75f21">LiveDebugValues::MLocTracker::getOrTrackSpillLoc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"livedebugvalues"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
