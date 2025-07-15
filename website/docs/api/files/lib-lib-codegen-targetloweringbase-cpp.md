---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/targetloweringbase-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `TargetLoweringBase.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">llvm/ADT/BitVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loads-h">llvm/Analysis/Loads.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/analysis-h">llvm/CodeGen/Analysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">llvm/CodeGen/ISDOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">llvm/CodeGen/RuntimeLibcallUtil.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">llvm/CodeGen/StackMaps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetopcodes-h">llvm/CodeGen/TargetOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/machinevaluetype-h">llvm/CodeGenTypes/MachineValueType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">llvm/IR/CallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sizeopts-h">llvm/Transforms/Utils/SizeOpts.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;cstring&gt;
#include &lt;iterator&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
#include "llvm/IR/ConstrainedOps.def"
#include "llvm/IR/VPIntrinsics.def"
#include "llvm/IR/Instruction.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8fb06bafca9d7d42e44c4f22669947">getVectorTypeBreakdownMVT</a> (MVT VT, MVT &amp;IntermediateVT, unsigned &amp;NumIntermediates, MVT &amp;RegisterVT, TargetLoweringBase *TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae094ad83b6971354f25c2bd55a210e30">getRecipEstimateForFunc</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the reciprocal estimate attribute string for a function that will override the target defaults. <a href="#ae094ad83b6971354f25c2bd55a210e30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e999991e3aeb3052927df01099bf4c">getReciprocalOpName</a> (bool IsSqrt, EVT VT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a string for the given reciprocal operation of the given type. <a href="#a70e999991e3aeb3052927df01099bf4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461ad47a3815838631b7aec404b99d21">parseRefinementStep</a> (StringRef In, size_t &amp;Position, uint8_t &amp;Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the character position and value (a single numeric character) of a customized refinement operation in the input string if it exists. <a href="#a461ad47a3815838631b7aec404b99d21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4c0f9a1193f368bbea577f429a3050c">getOpEnabled</a> (bool IsSqrt, EVT VT, StringRef Override)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the input attribute string, return one of the ReciprocalEstimate enum status values (enabled, disabled, or not specified) for this operation on the specified data type. <a href="#ad4c0f9a1193f368bbea577f429a3050c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9d92f0d78ae680c0eb2a43573b93ff">getOpRefinementSteps</a> (bool IsSqrt, EVT VT, StringRef Override)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the input attribute string, return the customized refinement step count for this operation on the specified data type. <a href="#acd9d92f0d78ae680c0eb2a43573b93ff">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f09c87e9827e71e1a8e9ca52520568">JumpIsExpensiveOverride</a>("jump-is-expensive", cl::init(false), cl::desc("Do not create extra branches to split comparison logic."), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1f1f1de803ec2f116902f215fe7a24">MinimumJumpTableEntries</a>("min-jump-table-entries", cl::init(4), cl::Hidden, cl::desc("Set minimum number of entries to use a jump table."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51120216af25ff57a3f94d59a9df0254">MaximumJumpTableSize</a>("max-jump-table-size", cl::init(UINT_MAX), cl::Hidden, cl::desc("Set maximum size of jump tables."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a691ffceb013ddad3b7b8348c412f5614">JumpTableDensity</a>("jump-table-density", cl::init(10), cl::Hidden, cl::desc("Minimum density for building a jump table in " "a normal function"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Minimum jump table density for normal functions. <a href="#a691ffceb013ddad3b7b8348c412f5614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af52fcf2321bdb6c2514d6854c8a416ef">OptsizeJumpTableDensity</a>("optsize-jump-table-density", cl::init(40), cl::Hidden, cl::desc("Minimum density for building a jump table in " "an optsize function"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Minimum jump table density for -Os or -Oz functions. <a href="#af52fcf2321bdb6c2514d6854c8a416ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fdf63539dd7c3babf700e32a706af80">DisableStrictNodeMutation</a>("disable-strictnode-mutation", cl::desc("Don't mutate strict-float node to a legalize node"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(A, B)&nbsp;&nbsp;&nbsp;  { <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_RELAX, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_ACQ, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_REL, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_ACQ_REL }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7caf1b72b68025eb17420cc4663ad64d">LCALL5</a>(A)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 1), <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 2), <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 4), <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 8), <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a245c76edc10bd7711d8afdd278d4ae68">OP_TO_LIBCALL</a>(Name, Enum)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf72c4cc7b3c53cbf1f02dd1f6c3c46b">DAG_INSTRUCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)&nbsp;&nbsp;&nbsp;    setOperationAction(ISD::STRICT_##DAGN, VT, Expand);</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2304230a51f7c268b7bdaa0bfc8e3f">BEGIN_REGISTER_VP_SDNODE</a>(SDOPC, ...)&nbsp;&nbsp;&nbsp;    setOperationAction(ISD::SDOPC, VT, Expand);</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acec6f7e3c8f55141a25830332307d3ea">HANDLE_INST</a>(NUM, OPCODE, CLASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6c9b5dc65aa7364c6e3ed632c9e9f02e">OPCODE</a> = NUM,</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab95ece372796414ceffc1c32fdce130a">LAST_OTHER_INST</a>(NUM)&nbsp;&nbsp;&nbsp;InstructionOpcodesCount = NUM</td>
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

### getOpEnabled() {#ad4c0f9a1193f368bbea577f429a3050c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getOpEnabled (bool IsSqrt, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Override)</td>
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

<p>For the input attribute string, return one of the ReciprocalEstimate enum status values (enabled, disabled, or not specified) for this operation on the specified data type.</p>

<p>Definition at line 2095 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33fabe65751dd4c96666d211802141105b27">llvm::TargetLoweringBase::Disabled</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33fa8e243db2e3806dcf4997c408a355ddfc">llvm::TargetLoweringBase::Enabled</a>, <a href="#a70e999991e3aeb3052927df01099bf4c">getReciprocalOpName</a>, <a href="#a461ad47a3815838631b7aec404b99d21">parseRefinementStep</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33faef4d83ea802e3b855bf36ea9689414b9">llvm::TargetLoweringBase::Unspecified</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a81db7ad778042035155d0e5052ca7b0f">llvm::TargetLoweringBase::getRecipEstimateDivEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a26e6cef786083fa5be5eed33adb16e13">llvm::TargetLoweringBase::getRecipEstimateSqrtEnabled</a>.</p>

</div>
</div>

### getOpRefinementSteps() {#acd9d92f0d78ae680c0eb2a43573b93ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getOpRefinementSteps (bool IsSqrt, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Override)</td>
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

<p>For the input attribute string, return the customized refinement step count for this operation on the specified data type.</p>


<p>If the step count does not exist, return the ReciprocalEstimate enum value for unspecified.</p>


<p>Definition at line 2155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a70e999991e3aeb3052927df01099bf4c">getReciprocalOpName</a>, <a href="#a461ad47a3815838631b7aec404b99d21">parseRefinementStep</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0cbb26a6b04c9a328e0e0966881da33faef4d83ea802e3b855bf36ea9689414b9">llvm::TargetLoweringBase::Unspecified</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6e5892228edb2677bf26969df95ac9e3">llvm::TargetLoweringBase::getDivRefinementSteps</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad86e2242dfd2adddc99fc4409aad112d">llvm::TargetLoweringBase::getSqrtRefinementSteps</a>.</p>

</div>
</div>

### getRecipEstimateForFunc() {#ae094ad83b6971354f25c2bd55a210e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getRecipEstimateForFunc (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Get the reciprocal estimate attribute string for a function that will override the target defaults.</p>

<p>Definition at line 2041 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6e5892228edb2677bf26969df95ac9e3">llvm::TargetLoweringBase::getDivRefinementSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a81db7ad778042035155d0e5052ca7b0f">llvm::TargetLoweringBase::getRecipEstimateDivEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a26e6cef786083fa5be5eed33adb16e13">llvm::TargetLoweringBase::getRecipEstimateSqrtEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad86e2242dfd2adddc99fc4409aad112d">llvm::TargetLoweringBase::getSqrtRefinementSteps</a>.</p>

</div>
</div>

### getReciprocalOpName() {#a70e999991e3aeb3052927df01099bf4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getReciprocalOpName (bool IsSqrt, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Construct a string for the given reciprocal operation of the given type.</p>


<p>This string should match the corresponding option to the front-end's "-mrecip" flag assuming those strings have been passed through in an attribute string. For example, "vec-divf" for a division of a vXf32.</p>


<p>Definition at line 2050 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>


<p>Referenced by <a href="#ad4c0f9a1193f368bbea577f429a3050c">getOpEnabled</a> and <a href="#acd9d92f0d78ae680c0eb2a43573b93ff">getOpRefinementSteps</a>.</p>

</div>
</div>

### getVectorTypeBreakdownMVT() {#a6c8fb06bafca9d7d42e44c4f22669947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getVectorTypeBreakdownMVT (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; IntermediateVT, unsigned &amp; NumIntermediates, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; RegisterVT, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase">TargetLoweringBase</a> * TLI)</td>
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



<p>Definition at line 1087 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4cc11b26432f9343b3c532f06171ad04">llvm::bit_ceil</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af344c6bd2d070c999525df85be7688cf">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aa1abe2e0d36a43d780ce54ea3b197217">llvm::MVT::getVectorElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a447ebcc5de7a1d9bc163862bf2c78e41">llvm::MVT::isScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>.</p>

</div>
</div>

### parseRefinementStep() {#a461ad47a3815838631b7aec404b99d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseRefinementStep (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> In, size_t &amp; Position, uint8_t &amp; Value)</td>
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

<p>Return the character position and value (a single numeric character) of a customized refinement operation in the input string if it exists.</p>


<p>Return false if there is no customized refinement step count.</p>


<p>Definition at line 2072 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a82c27bc751f7669f9c2a79de96e2d0fd">llvm::isDigit</a>, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#ad4c0f9a1193f368bbea577f429a3050c">getOpEnabled</a> and <a href="#acd9d92f0d78ae680c0eb2a43573b93ff">getOpRefinementSteps</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableStrictNodeMutation {#a3fdf63539dd7c3babf700e32a706af80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableStrictNodeMutation("disable-strictnode-mutation", cl::desc("Don't mutate strict-float node to a legalize node"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac5c03f3e796f76a1a81cdf3f41e24493">llvm::TargetLoweringBase::TargetLoweringBase</a>.</p>

</div>
</div>

### JumpIsExpensiveOverride {#a18f09c87e9827e71e1a8e9ca52520568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; JumpIsExpensiveOverride("jump-is-expensive", cl::init(false), cl::desc("Do not create extra branches to split comparison logic."), cl::Hidden)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af7666cad940e6ca0f5c37b9e7b23157d">llvm::TargetLoweringBase::setJumpIsExpensive</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac5c03f3e796f76a1a81cdf3f41e24493">llvm::TargetLoweringBase::TargetLoweringBase</a>.</p>

</div>
</div>

### JumpTableDensity {#a691ffceb013ddad3b7b8348c412f5614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; JumpTableDensity("jump-table-density", cl::init(10), cl::Hidden, cl::desc("Minimum density for building a jump table in " "a normal function"))</td>
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

<p>Minimum jump table density for normal functions.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab95e4ba1a5ed4d2f1256065a393042f2">llvm::TargetLoweringBase::getMinimumJumpTableDensity</a>.</p>

</div>
</div>

### MaximumJumpTableSize {#a51120216af25ff57a3f94d59a9df0254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaximumJumpTableSize("max-jump-table-size", cl::init(UINT_MAX), cl::Hidden, cl::desc("Set maximum size of jump tables."))</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a4b7d8d1b98f160a4b807187194b99d96">llvm::TargetLoweringBase::getMaximumJumpTableSize</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a2daba03291ed357d731e42824d8ba4b1">llvm::TargetLoweringBase::setMaximumJumpTableSize</a>.</p>

</div>
</div>

### MinimumJumpTableEntries {#a2d1f1f1de803ec2f116902f215fe7a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MinimumJumpTableEntries("min-jump-table-entries", cl::init(4), cl::Hidden, cl::desc("Set minimum number of entries to use a jump table."))</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3008612893c2c2095a2263367952a798">llvm::TargetLoweringBase::getMinimumJumpTableEntries</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9cc71effed4a85d71b1e556d266f0d3b">llvm::TargetLoweringBase::setMinimumJumpTableEntries</a>.</p>

</div>
</div>

### OptsizeJumpTableDensity {#af52fcf2321bdb6c2514d6854c8a416ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; OptsizeJumpTableDensity("optsize-jump-table-density", cl::init(40), cl::Hidden, cl::desc("Minimum density for building a jump table in " "an optsize function"))</td>
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

<p>Minimum jump table density for -Os or -Oz functions.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab95e4ba1a5ed4d2f1256065a393042f2">llvm::TargetLoweringBase::getMinimumJumpTableDensity</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### BEGIN\_REGISTER\_VP\_SDNODE {#a3f2304230a51f7c268b7bdaa0bfc8e3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BEGIN_REGISTER_VP_SDNODE(SDOPC, ...)&nbsp;&nbsp;&nbsp;    setOperationAction(ISD::SDOPC, VT, Expand);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>

</div>
</div>

### DAG\_INSTRUCTION {#abf72c4cc7b3c53cbf1f02dd1f6c3c46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DAG_INSTRUCTION(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)&nbsp;&nbsp;&nbsp;    setOperationAction(ISD::STRICT_##DAGN, VT, Expand);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>

</div>
</div>

### HANDLE\_INST {#acec6f7e3c8f55141a25830332307d3ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_INST(NUM, OPCODE, CLASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6c9b5dc65aa7364c6e3ed632c9e9f02e">OPCODE</a> = NUM,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1767 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>

</div>
</div>

### LAST\_OTHER\_INST {#ab95ece372796414ceffc1c32fdce130a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LAST_OTHER_INST(NUM)&nbsp;&nbsp;&nbsp;InstructionOpcodesCount = NUM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1768 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>

</div>
</div>

### LCALL5 {#a7caf1b72b68025eb17420cc4663ad64d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LCALL5(A)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 1), <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 2), <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 4), <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 8), <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 16)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#ab0d3dcfdec97d221021bfc9430beaba1">llvm::RTLIB::getOUTLINE_ATOMIC</a>.</p>

</div>
</div>

### LCALLS {#a170d2ae878fd8d8d7d558956f1dd6510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LCALLS(A, B)&nbsp;&nbsp;&nbsp;  { <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_RELAX, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_ACQ, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_REL, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_ACQ_REL }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>

</div>
</div>

### OP\_TO\_LIBCALL {#a245c76edc10bd7711d8afdd278d4ae68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OP_TO_LIBCALL(Name, Enum)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Name:                                                                   \
    switch (VT.SimpleTy) {                                                     \
    default:                                                                   \
      return UNKNOWN_LIBCALL;                                                  \
    case MVT::i8:                                                              \
      return Enum##_1;                                                         \
    case MVT::i16:                                                             \
      return Enum##_2;                                                         \
    case MVT::i32:                                                             \
      return Enum##_4;                                                         \
    case MVT::i64:                                                             \
      return Enum##_8;                                                         \
    case MVT::i128:                                                            \
      return Enum##_16;                                                        \
    }
</div>
</dd>
</dl>

<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp">TargetLoweringBase.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a3a9c838f40a37e66a425b537704a9acd">llvm::RTLIB::getSYNC</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
