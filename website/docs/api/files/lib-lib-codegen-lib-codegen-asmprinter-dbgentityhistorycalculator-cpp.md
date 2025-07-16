---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DbgEntityHistoryCalculator.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dbgentityhistorycalculator-h">llvm/CodeGen/DbgEntityHistoryCalculator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lexicalscopes-h">llvm/CodeGen/LexicalScopes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;map&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-dbgentityhistorycalculator-cpp-">anonymous{DbgEntityHistoryCalculator.cpp}</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a50e4c9f81d1b75e9f5706df4cdb3c489">InsnRange</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0250c150e720772b7e0feac3d2f43e82">intersects</a> (const MachineInstr *StartMI, const MachineInstr *EndMI, const ArrayRef&lt; InsnRange &gt; &amp;Ranges, const InstructionOrdering &amp;Ordering)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction range [StartMI, EndMI] intersects any instruction range in Ranges. <a href="#a0250c150e720772b7e0feac3d2f43e82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8c50334361138c028abb7a33ba65382">dropRegDescribedVar</a> (RegDescribedVarsMap &amp;RegVars, unsigned RegNo, InlinedEntity Var)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762ac984d093ef7fc39b2927266fb17d">addRegDescribedVar</a> (RegDescribedVarsMap &amp;RegVars, unsigned RegNo, InlinedEntity Var)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8380bda17afbeb9b1792136a17e55f74">clobberRegEntries</a> (InlinedEntity Var, unsigned RegNo, const MachineInstr &amp;ClobberingInstr, DbgValueEntriesMap &amp;LiveEntries, DbgValueHistoryMap &amp;HistMap, SmallVectorImpl&lt; Register &gt; &amp;FellowRegisters)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clobbering entry and end all open debug value entries for <span class="doxyComputerOutput">Var</span> that are described by <span class="doxyComputerOutput">RegNo</span> using that entry. <a href="#a8380bda17afbeb9b1792136a17e55f74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee24d91499bcb94c513e7db61664312">handleNewDebugValue</a> (InlinedEntity Var, const MachineInstr &amp;DV, RegDescribedVarsMap &amp;RegVars, DbgValueEntriesMap &amp;LiveEntries, DbgValueHistoryMap &amp;HistMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new debug value for <span class="doxyComputerOutput">Var</span>. Closes all overlapping debug values. <a href="#a9ee24d91499bcb94c513e7db61664312">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc54e01f7baa4967cf9f967fe2e59215">clobberRegisterUses</a> (RegDescribedVarsMap &amp;RegVars, RegDescribedVarsMap::iterator I, DbgValueHistoryMap &amp;HistMap, DbgValueEntriesMap &amp;LiveEntries, const MachineInstr &amp;ClobberingInstr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb7db0e98e12aff26d644d39ce1e947">clobberRegisterUses</a> (RegDescribedVarsMap &amp;RegVars, unsigned RegNo, DbgValueHistoryMap &amp;HistMap, DbgValueEntriesMap &amp;LiveEntries, const MachineInstr &amp;ClobberingInstr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"dwarfdebug"</td>
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


<div class="doxySectionDef">

## Functions

### addRegDescribedVar() {#a762ac984d093ef7fc39b2927266fb17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addRegDescribedVar (RegDescribedVarsMap &amp; RegVars, unsigned RegNo, InlinedEntity Var)</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#a9ee24d91499bcb94c513e7db61664312">handleNewDebugValue</a>.</p>

</div>
</div>

### clobberRegEntries() {#a8380bda17afbeb9b1792136a17e55f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void clobberRegEntries (InlinedEntity Var, unsigned RegNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; ClobberingInstr, DbgValueEntriesMap &amp; LiveEntries, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap">DbgValueHistoryMap</a> &amp; HistMap, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; FellowRegisters)</td>
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

<p>Create a clobbering entry and end all open debug value entries for <span class="doxyComputerOutput">Var</span> that are described by <span class="doxyComputerOutput">RegNo</span> using that entry.</p>


<p>Inserts into <span class="doxyComputerOutput">FellowRegisters</span> the set of Registers that were also used to describe <span class="doxyComputerOutput">Var</span> alongside <span class="doxyComputerOutput">RegNo</span>.</p>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#ae04ad615dfdd885e85cbddda146787c6">llvm::SmallSet&lt; T, N, C &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a7c92cf2698b8f135a0ae13fa7f9e4e5d">llvm::DbgValueHistoryMap::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a490f4bfbd523b5df0e484f26a6f7ef9a">llvm::DbgValueHistoryMap::startClobber</a>.</p>


<p>Referenced by <a href="#acc54e01f7baa4967cf9f967fe2e59215">clobberRegisterUses</a>.</p>

</div>
</div>

### clobberRegisterUses() {#acc54e01f7baa4967cf9f967fe2e59215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void clobberRegisterUses (RegDescribedVarsMap &amp; RegVars, RegDescribedVarsMap::iterator I, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap">DbgValueHistoryMap</a> &amp; HistMap, DbgValueEntriesMap &amp; LiveEntries, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; ClobberingInstr)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a>.</p>


<p>References <a href="#a8380bda17afbeb9b1792136a17e55f74">clobberRegEntries</a>, <a href="#aa8c50334361138c028abb7a33ba65382">dropRegDescribedVar</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a> and <a href="#a0cb7db0e98e12aff26d644d39ce1e947">clobberRegisterUses</a>.</p>

</div>
</div>

### clobberRegisterUses() {#a0cb7db0e98e12aff26d644d39ce1e947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void clobberRegisterUses (RegDescribedVarsMap &amp; RegVars, unsigned RegNo, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap">DbgValueHistoryMap</a> &amp; HistMap, DbgValueEntriesMap &amp; LiveEntries, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; ClobberingInstr)</td>
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



<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a>.</p>


<p>References <a href="#acc54e01f7baa4967cf9f967fe2e59215">clobberRegisterUses</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### dropRegDescribedVar() {#aa8c50334361138c028abb7a33ba65382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dropRegDescribedVar (RegDescribedVarsMap &amp; RegVars, unsigned RegNo, InlinedEntity Var)</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#acc54e01f7baa4967cf9f967fe2e59215">clobberRegisterUses</a> and <a href="#a9ee24d91499bcb94c513e7db61664312">handleNewDebugValue</a>.</p>

</div>
</div>

### handleNewDebugValue() {#a9ee24d91499bcb94c513e7db61664312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleNewDebugValue (InlinedEntity Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DV, RegDescribedVarsMap &amp; RegVars, DbgValueEntriesMap &amp; LiveEntries, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap">DbgValueHistoryMap</a> &amp; HistMap)</td>
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

<p>Add a new debug value for <span class="doxyComputerOutput">Var</span>. Closes all overlapping debug values.</p>

<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a>.</p>


<p>References <a href="#a762ac984d093ef7fc39b2927266fb17d">addRegDescribedVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e2899f5dd649a9f82c32b99e5d77dcd">llvm::MachineInstr::debug_operands</a>, <a href="#aa8c50334361138c028abb7a33ba65382">dropRegDescribedVar</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a46d29699ee79b3a3d7359278f6bab01c">llvm::DIExpression::fragmentsOverlap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab367ba2f45afaba6e941bd54c9c95a9f">llvm::MachineInstr::getDebugExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a7c92cf2698b8f135a0ae13fa7f9e4e5d">llvm::DbgValueHistoryMap::getEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ae45a9559b6fd1578fb4d12f341cbed57">llvm::MachineInstr::isDebugEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a07197ab78c86a3f9dee5b443971873d3">llvm::DbgValueHistoryMap::startDbgValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>.</p>

</div>
</div>

### intersects() {#a0250c150e720772b7e0feac3d2f43e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ArrayRef&lt; InsnRange &gt;::iterator &gt; intersects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * StartMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * EndMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a50e4c9f81d1b75e9f5706df4cdb3c489">InsnRange</a> &gt; &amp; Ranges, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructionordering">InstructionOrdering</a> &amp; Ordering)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction range [StartMI, EndMI] intersects any instruction range in Ranges.</p>


<p>EndMI can be nullptr to indicate that the range is unbounded. Assumes Ranges is ordered and disjoint. Returns true and points to the first intersecting scope range if one exists.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/resourcesegments/#a173bcdd8f59b31a810aead1000274448">llvm::ResourceSegments::add</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a19a6a168a50b639280b51eada31cae76">llvm::DbgValueHistoryMap::trimLocationRanges</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"dwarfdebug"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp">DbgEntityHistoryCalculator.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
