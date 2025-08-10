---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `StatepointLowering.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-h">StatepointLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">llvm/ADT/SmallBitVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">llvm/CodeGen/FunctionLoweringInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">llvm/CodeGen/GCMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">llvm/CodeGen/ISDOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">llvm/CodeGen/SelectionDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">llvm/CodeGen/StackMaps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetopcodes-h">llvm/CodeGen/TargetOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/machinevaluetype-h">llvm/CodeGenTypes/MachineValueType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">llvm/IR/CallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gcstrategy-h">llvm/IR/GCStrategy.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">llvm/IR/Statepoint.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/statepointrelocationrecord">FunctionLoweringInfo::StatepointRelocationRecord</a> <a href="#ae5fbc6e1ce3fcbb7f185ed9e7beffec7">RecordType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac56a1eac8e1bf8bbe2530ba919e3542c">STATISTIC</a> (NumSlotsAllocatedForStatepoints, "Number of stack slots allocated for statepoints")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190019db36961a89ee7ac54d621812f9">STATISTIC</a> (NumOfStatepoints, "Number of statepoint nodes encountered")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832142292a9ea54449b2930dd109a131">STATISTIC</a> (StatepointMaxSlotsRequired, "Maximum number of stack slots required for a singe statepoint")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720a77a05d768dabfa739d154c11ddfd">pushStackMapConstant</a> (SmallVectorImpl&lt; SDValue &gt; &amp;Ops, SelectionDAGBuilder &amp;Builder, uint64_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac2c0f0b7439c31332c78cd1ca5c4fe">findPreviousSpillSlot</a> (const Value *Val, SelectionDAGBuilder &amp;Builder, int LookUpDepth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function for reservePreviousStackSlotForValue. <a href="#a6ac2c0f0b7439c31332c78cd1ca5c4fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8300a0e0276d27757963efa800126f14">willLowerDirectly</a> (SDValue Incoming)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if-and-only-if the given <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> can be lowered as either a constant argument or a stack reference. <a href="#a8300a0e0276d27757963efa800126f14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a> (const Value *IncomingValue, SelectionDAGBuilder &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to find existing copies of the incoming values in stack slots used for statepoint spilling. <a href="#adec63d991d7eb048d87fa3888099c848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8947d9c8165e82094241d319758e0c5">lowerCallFromStatepointLoweringInfo</a> (SelectionDAGBuilder::StatepointLoweringInfo &amp;SI, SelectionDAGBuilder &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract call from statepoint, lower it and return pointer to the call node. <a href="#af8947d9c8165e82094241d319758e0c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec1de11231135901271d92c7d90dae60">getMachineMemOperand</a> (MachineFunction &amp;MF, FrameIndexSDNode &amp;FI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a> (SDValue Incoming, SDValue Chain, SelectionDAGBuilder &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Spill a value incoming to the statepoint. <a href="#afb9b4b3ff97e290070f42849b51a13a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a> (SDValue Incoming, bool RequireSpillSlot, SmallVectorImpl&lt; SDValue &gt; &amp;Ops, SmallVectorImpl&lt; MachineMemOperand * &gt; &amp;MemRefs, SelectionDAGBuilder &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower a single value incoming to a statepoint node. <a href="#a1692829d8158767fe5ac1809c90a77a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720af7e7f23150174952da03d216341a">isGCValue</a> (const Value *V, SelectionDAGBuilder &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if value V represents the GC value. <a href="#a720af7e7f23150174952da03d216341a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a> (SmallVectorImpl&lt; SDValue &gt; &amp;Ops, SmallVectorImpl&lt; MachineMemOperand * &gt; &amp;MemRefs, SmallVectorImpl&lt; SDValue &gt; &amp;GCPtrs, DenseMap&lt; SDValue, int &gt; &amp;LowerAsVReg, SelectionDAGBuilder::StatepointLoweringInfo &amp;SI, SelectionDAGBuilder &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower deopt state and gc pointer arguments of the statepoint. <a href="#a9029ef3db44eac67782fd8ccb7796a0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcresultinst">GCResultInst</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcresultinst">GCResultInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1af1f498b4d814ee68810a03fbe28a7">getGCResultLocality</a> (const GCStatepointInst &amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return two gc.results if present. <a href="#ab1af1f498b4d814ee68810a03fbe28a7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9bf191372abad68cbfc02b4e33cebc6">UseRegistersForDeoptValues</a>("use-registers-for-deopt-values", cl::Hidden, cl::init(false), cl::desc("Allow using registers for non pointer deopt args"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e0d3f870d52149756ca3cec34ab6a0">UseRegistersForGCPointersInLandingPad</a>("use-registers-for-gc-values-in-landing-pad", cl::Hidden, cl::init(false), cl::desc("Allow using registers for gc pointer in landing pad"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc011fee2f0e40238d54aa2a8820c728">MaxRegistersForGCPointers</a>("max-registers-for-gc-values", cl::Hidden, cl::init(0), cl::desc("Max number of VRegs allowed to pass GC pointer meta args in"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"statepoint-lowering"</td>
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

## Typedefs

### RecordType {#ae5fbc6e1ce3fcbb7f185ed9e7beffec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef FunctionLoweringInfo::StatepointRelocationRecord RecordType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### findPreviousSpillSlot() {#a6ac2c0f0b7439c31332c78cd1ca5c4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int &gt; findPreviousSpillSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> &amp; Builder, int LookUpDepth)</td>
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

<p>Utility function for reservePreviousStackSlotForValue.</p>


<p>Tries to find stack slot index to which we have spilled value for previous statepoints. LookUpDepth specifies maximum DFS depth this function is allowed to look.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a6ac2c0f0b7439c31332c78cd1ca5c4fe">findPreviousSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ad10e64e191507974af84a4ea069a9e36">llvm::SelectionDAGBuilder::FuncInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/statepointrelocationrecord/#ae85ec708fd4e537d4b331ce7f94acb2ca4e2303faf0f163fb7a4af33f778884e8">llvm::FunctionLoweringInfo::StatepointRelocationRecord::Spill</a> and <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a460bac4fe51e0dcd08f1fb328005926d">llvm::FunctionLoweringInfo::StatepointRelocationMaps</a>.</p>


<p>Referenced by <a href="#a6ac2c0f0b7439c31332c78cd1ca5c4fe">findPreviousSpillSlot</a> and <a href="#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a>.</p>

</div>
</div>

### getGCResultLocality() {#ab1af1f498b4d814ee68810a03fbe28a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const GCResultInst *, const GCResultInst * &gt; getGCResultLocality (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst">GCStatepointInst</a> &amp; S)</td>
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

<p>Return two gc.results if present.</p>


<p>First result is a block local gc.result, second result is a non-block local gc.result. Corresponding entry will be nullptr if not present.</p>


<p>Definition at line 999 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a32cff45e4cfd323ecc3896adcb08c2a9">llvm::SelectionDAGBuilder::LowerStatepoint</a>.</p>

</div>
</div>

### getMachineMemOperand() {#aec1de11231135901271d92c7d90dae60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineMemOperand * getMachineMemOperand (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/frameindexsdnode">FrameIndexSDNode</a> &amp; FI)</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/frameindexsdnode/#a1cf719b8c945859e29131c892774b21c">llvm::FrameIndexSDNode::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">llvm::MachineMemOperand::MOVolatile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9a24d61ebbaf960b10d22de71b388be3">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#acbb662ad1799057d6bea1501cbaf5d46">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a697dec75b5e5a66bd8e0312542cd63b3">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#acf9d481ec021e4bbb5429f0f6d7fcba9">llvm::MachineFunction::getMachineMemOperand</a>, <a href="#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a>, <a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a> and <a href="#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a>.</p>

</div>
</div>

### isGCValue() {#a720af7e7f23150174952da03d216341a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isGCValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> &amp; Builder)</td>
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

<p>Return true if value V represents the GC value.</p>


<p>The behavior is conservative in case it is not sure that value is not GC the function returns true.</p>


<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a9b4db8b8082660004fda0c282da0ff0a">llvm::SelectionDAGBuilder::GFI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a32cff45e4cfd323ecc3896adcb08c2a9">llvm::SelectionDAGBuilder::LowerStatepoint</a> and <a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>.</p>

</div>
</div>

### lowerCallFromStatepointLoweringInfo() {#af8947d9c8165e82094241d319758e0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDNode * &gt; lowerCallFromStatepointLoweringInfo (<a href="/web-llvm/docs/api/structs/llvm/selectiondagbuilder/statepointloweringinfo">SelectionDAGBuilder::StatepointLoweringInfo</a> &amp; SI, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> &amp; Builder)</td>
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

<p>Extract call from statepoint, lower it and return pointer to the call node.</p>


<p>Also update NodeMap so that getValue(statepoint) will reference lowered call result</p>


<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6feb9a82882ea426db5b62f3f69f63a2">llvm::ISD::CALLSEQ_END</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a84c47705bcf7271413738ae8bf3871e6">llvm::ISD::CopyFromReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4c1f7e0dc3af92b9cfd0d5d11231ddc1">llvm::ISD::EH_LABEL</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ab29b69c993fbb9a4b9d28c3600df005d">llvm::SelectionDAGBuilder::lowerInvokable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>.</p>

</div>
</div>

### lowerIncomingStatepointValue() {#a1692829d8158767fe5ac1809c90a77a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lowerIncomingStatepointValue (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Incoming, bool RequireSpillSlot, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt; &amp; MemRefs, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> &amp; Builder)</td>
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

<p>Lower a single value incoming to a statepoint node.</p>


<p>This value can be either a deopt value or a gc value, the handling is the same. We special case constants and allocas, then fall back to spilling if required.</p>


<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ad997f08bfd4680a697130632badf740e">llvm::SelectionDAGBuilder::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2f4850c6b936e27186113935b002b36f">llvm::SelectionDAGBuilder::getFrameIndexTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="#aec1de11231135901271d92c7d90dae60">getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#aa3e946c1fc678a70e849244389bd929a">llvm::SelectionDAGBuilder::getRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6ececde40ed933c2dfb5af16cb002529">llvm::SelectionDAG::getTargetFrameIndex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a720a77a05d768dabfa739d154c11ddfd">pushStackMapConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae0fc3f54d06d2230bf93a19d45f51706">llvm::SelectionDAG::setRoot</a>, <a href="#afb9b4b3ff97e290070f42849b51a13a5">spillIncomingStatepointValue</a> and <a href="#a8300a0e0276d27757963efa800126f14">willLowerDirectly</a>.</p>


<p>Referenced by <a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>.</p>

</div>
</div>

### lowerStatepointMetaArgs() {#a9029ef3db44eac67782fd8ccb7796a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lowerStatepointMetaArgs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt; &amp; MemRefs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; GCPtrs, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, int &gt; &amp; LowerAsVReg, <a href="/web-llvm/docs/api/structs/llvm/selectiondagbuilder/statepointloweringinfo">SelectionDAGBuilder::StatepointLoweringInfo</a> &amp; SI, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> &amp; Builder)</td>
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

<p>Lower deopt state and gc pointer arguments of the statepoint.</p>


<p>The actual lowering is described in lowerIncomingStatepointValue. This function is responsible for lowering everything in the right position and playing some tricks to avoid redundant stack manipulation where possible. On completion, 'Ops' will contain ready to use operands for machine code statepoint. The chain nodes will have already been created and the DAG root will be set to the last value spilled (if any were).</p>


<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ad997f08bfd4680a697130632badf740e">llvm::SelectionDAGBuilder::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abba0f0474eb4e32d1ed7b6dfdb0d5140a8cf633e3cd4e8b21a16304c58495bfbc">llvm::DeoptLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a68cdc2666693dffb9173a9dffee11ab8">llvm::SDValue::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ad10e64e191507974af84a4ea069a9e36">llvm::SelectionDAGBuilder::FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a4adbd2ebdab9c844ce0443c43c3ee16d">llvm::FunctionLoweringInfo::getArgumentFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#abb661ad9d4e5fd0d8806106e9b4d7256">llvm::SelectionDAGBuilder::getCurSDLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2f4850c6b936e27186113935b002b36f">llvm::SelectionDAGBuilder::getFrameIndexTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="#aec1de11231135901271d92c7d90dae60">getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6ececde40ed933c2dfb5af16cb002529">llvm::SelectionDAG::getTargetFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a025adb087cac36e2cd504a33e8cb749d">llvm::SelectionDAGBuilder::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="#a720af7e7f23150174952da03d216341a">isGCValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a>, <a href="#adc011fee2f0e40238d54aa2a8820c728">MaxRegistersForGCPointers</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a720a77a05d768dabfa739d154c11ddfd">pushStackMapConstant</a>, <a href="#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a7c36580f905b274ca0a1ade46ba06ae0">llvm::SetVector&lt; T, Vector, Set, N &gt;::takeVector</a>, <a href="#ab9bf191372abad68cbfc02b4e33cebc6">UseRegistersForDeoptValues</a>, <a href="#a08e0d3f870d52149756ca3cec34ab6a0">UseRegistersForGCPointersInLandingPad</a> and <a href="#a8300a0e0276d27757963efa800126f14">willLowerDirectly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>.</p>

</div>
</div>

### pushStackMapConstant() {#a720a77a05d768dabfa739d154c11ddfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void pushStackMapConstant (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> &amp; Builder, uint64_t Value)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ad997f08bfd4680a697130632badf740e">llvm::SelectionDAGBuilder::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#abb661ad9d4e5fd0d8806106e9b4d7256">llvm::SelectionDAGBuilder::getCurSDLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>, <a href="#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a> and <a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>.</p>

</div>
</div>

### reservePreviousStackSlotForValue() {#adec63d991d7eb048d87fa3888099c848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reservePreviousStackSlotForValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IncomingValue, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> &amp; Builder)</td>
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

<p>Try to find existing copies of the incoming values in stack slots used for statepoint spilling.</p>


<p>If we can find a spill slot for the incoming value, mark that slot as allocated, and reuse the same slot for this safepoint. This helps to avoid series of loads and stores that only serve to reshuffle values on the stack between calls.</p>


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ad997f08bfd4680a697130632badf740e">llvm::SelectionDAGBuilder::DAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="#a6ac2c0f0b7439c31332c78cd1ca5c4fe">findPreviousSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ad10e64e191507974af84a4ea069a9e36">llvm::SelectionDAGBuilder::FuncInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2f4850c6b936e27186113935b002b36f">llvm::SelectionDAGBuilder::getFrameIndexTy</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a2e2d4007205a6b163daaf00e3aba04bd">llvm::StatepointLoweringState::getLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6ececde40ed933c2dfb5af16cb002529">llvm::SelectionDAG::getTargetFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a025adb087cac36e2cd504a33e8cb749d">llvm::SelectionDAGBuilder::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a6cdb26e5268cc05eb7f9726a140f1ae2">llvm::StatepointLoweringState::isStackSlotAllocated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#af93bbb466651e3e6abdf9e35c0a34b30">llvm::StatepointLoweringState::reserveStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a83f9edf0427d9c6d437318242326e331">llvm::StatepointLoweringState::setLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a77cbbcab1440ac5ef835e1a3d3f6c74e">llvm::SelectionDAGBuilder::StatepointLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a9691f14813e0540e6a1c90cfdad39df3">llvm::FunctionLoweringInfo::StatepointStackSlots</a> and <a href="#a8300a0e0276d27757963efa800126f14">willLowerDirectly</a>.</p>


<p>Referenced by <a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>.</p>

</div>
</div>

### spillIncomingStatepointValue() {#afb9b4b3ff97e290070f42849b51a13a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; SDValue, SDValue, MachineMemOperand * &gt; spillIncomingStatepointValue (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Incoming, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> &amp; Builder)</td>
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

<p>Spill a value incoming to the statepoint.</p>


<p>It might be either part of vmstate or gcstate. In both cases unconditionally spill it on the stack unless it is a null constant. Return pair with first element being frame index containing saved value and second element with outgoing chain from the emitted store</p>


<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a4841be2489ba10321338a1874b53f249">llvm::StatepointLoweringState::allocateStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ad997f08bfd4680a697130632badf740e">llvm::SelectionDAGBuilder::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#abb661ad9d4e5fd0d8806106e9b4d7256">llvm::SelectionDAGBuilder::getCurSDLoc</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2f4850c6b936e27186113935b002b36f">llvm::SelectionDAGBuilder::getFrameIndexTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a2e2d4007205a6b163daaf00e3aba04bd">llvm::StatepointLoweringState::getLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="#aec1de11231135901271d92c7d90dae60">getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6ececde40ed933c2dfb5af16cb002529">llvm::SelectionDAG::getTargetFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a83f9edf0427d9c6d437318242326e331">llvm::StatepointLoweringState::setLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a77cbbcab1440ac5ef835e1a3d3f6c74e">llvm::SelectionDAGBuilder::StatepointLowering</a>.</p>


<p>Referenced by <a href="#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a>.</p>

</div>
</div>

### STATISTIC() {#ac56a1eac8e1bf8bbe2530ba919e3542c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumSlotsAllocatedForStatepoints, "Number of stack <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp/#ad95860b0cf8da9d86f5683f19fafbb32">slots</a> allocated <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> statepoints")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a190019db36961a89ee7ac54d621812f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumOfStatepoints, "Number of statepoint <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifydivergentexitnodes-cpp/#aaa253dd3e56c37edd403113782c0ef94">nodes</a> encountered")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a832142292a9ea54449b2930dd109a131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (StatepointMaxSlotsRequired, "Maximum number of stack <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp/#ad95860b0cf8da9d86f5683f19fafbb32">slots</a> required <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> a singe statepoint")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>

</div>
</div>

### willLowerDirectly() {#a8300a0e0276d27757963efa800126f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool willLowerDirectly (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Incoming)</td>
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

<p>Return true if-and-only-if the given <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> can be lowered as either a constant argument or a stack reference.</p>


<p>The key point is that the value doesn't need to be spilled or tracked as a vreg use.</p>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2e392c596f41ac56b67f31c2e4b33dd1">llvm::isIntOrFPConstant</a>.</p>


<p>Referenced by <a href="#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a>, <a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a> and <a href="#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### MaxRegistersForGCPointers {#adc011fee2f0e40238d54aa2a8820c728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxRegistersForGCPointers("max-registers-for-gc-values", cl::Hidden, cl::init(0), cl::desc("Max number of VRegs allowed to pass GC pointer meta args in"))</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>Referenced by <a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>.</p>

</div>
</div>

### UseRegistersForDeoptValues {#ab9bf191372abad68cbfc02b4e33cebc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseRegistersForDeoptValues("use-registers-for-deopt-values", cl::Hidden, cl::init(false), cl::desc("Allow using registers for non pointer deopt args"))</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>Referenced by <a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>.</p>

</div>
</div>

### UseRegistersForGCPointersInLandingPad {#a08e0d3f870d52149756ca3cec34ab6a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseRegistersForGCPointersInLandingPad("use-registers-for-gc-values-in-landing-pad", cl::Hidden, cl::init(false), cl::desc("Allow using registers for gc pointer in landing pad"))</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>


<p>Referenced by <a href="#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"statepoint-lowering"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp">StatepointLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
