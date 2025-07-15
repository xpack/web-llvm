---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/regsforvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegsForValue` Struct Reference

<p>This struct represents the registers (physical or virtual) that a particular set of values is assigned, and the type information about the value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RegsForValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">CodeGen/SelectionDAG/SelectionDAGBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a123209f777591b5401b745f330892d5c">RegsForValue</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc970ad3ae53c4651c93aea291dfb99e">RegsForValue</a> (const SmallVector&lt; Register, 4 &gt; &amp;regs, MVT regvt, EVT valuevt, std::optional&lt; CallingConv::ID &gt; CC=std::nullopt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8334b2e523b8d9fa1d57f399cc08921f">RegsForValue</a> (LLVMContext &amp;Context, const TargetLowering &amp;TLI, const DataLayout &amp;DL, Register Reg, Type *Ty, std::optional&lt; CallingConv::ID &gt; CC)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f8aefe8349b8f445625f678b051e16c">isABIMangled</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a03067151ceb16293bd64c1831c6dcb">append</a> (const RegsForValue &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the specified values to this one. <a href="#a6a03067151ceb16293bd64c1831c6dcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad782fe84b36a1c379ac9f1ac367706e1">getCopyFromRegs</a> (SelectionDAG &amp;DAG, FunctionLoweringInfo &amp;FuncInfo, const SDLoc &amp;dl, SDValue &amp;Chain, SDValue *Glue, const Value *V=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a series of CopyFromReg nodes that copies from this value and returns the result as a ValueVTs value. <a href="#ad782fe84b36a1c379ac9f1ac367706e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf93dd21d49c19700e980b15f19cb7d7">getCopyToRegs</a> (SDValue Val, SelectionDAG &amp;DAG, const SDLoc &amp;dl, SDValue &amp;Chain, SDValue *Glue, const Value *V=nullptr, ISD::NodeType PreferredExtendType=ISD::ANY_EXTEND) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a series of CopyToReg nodes that copies the specified value into the registers specified by this object. <a href="#adf93dd21d49c19700e980b15f19cb7d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e723a22ad556552ca99f7e7a90a780">AddInlineAsmOperands</a> (InlineAsm::Kind Code, bool HasMatching, unsigned MatchingIdx, const SDLoc &amp;dl, SelectionDAG &amp;DAG, std::vector&lt; SDValue &gt; &amp;Ops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add this value to the specified inlineasm node operand list. <a href="#a73e723a22ad556552ca99f7e7a90a780">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4c3ed13d5c82a825cb533010000347">occupiesMultipleRegs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the total RegCount is greater than one. <a href="#aed4c3ed13d5c82a825cb533010000347">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03813938f6c7ea6b7e94965a27491ddc">getRegsAndSizes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a list of registers and their sizes. <a href="#a03813938f6c7ea6b7e94965a27491ddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285fe7c1651ad46e272fbe0d4ef59189">ValueVTs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The value types of the values, which may not be legal, and may need be promoted or synthesized from one or more registers. <a href="#a285fe7c1651ad46e272fbe0d4ef59189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3cf865d5a653cfae070a5a64d2b3a9">RegVTs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The value types of the registers. <a href="#adc3cf865d5a653cfae070a5a64d2b3a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d3f48e8c5cf69454cd80e7a5224970">Regs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This list holds the registers assigned to the values. <a href="#a70d3f48e8c5cf69454cd80e7a5224970">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c16254f02fe53dec13cd46773ded1f3">RegCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This list holds the number of registers for each value. <a href="#a1c16254f02fe53dec13cd46773ded1f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0896c435305536fccf78b4fd263eae0">CallConv</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records if this value needs to be treated in an ABI dependant manner, different to normal type legalization. <a href="#ae0896c435305536fccf78b4fd263eae0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This struct represents the registers (physical or virtual) that a particular set of values is assigned, and the type information about the value.</p>


<p>The most common situation is to represent one value at a time, but struct or array values are handled element-wise as multiple values. The splitting of aggregates is performed recursively, so that we never have aggregate-typed registers. The values at this point do not necessarily have legal types, so each value may require one or more registers of some legal type.</p>


<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegsForValue() {#a123209f777591b5401b745f330892d5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegsForValue::RegsForValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a6a03067151ceb16293bd64c1831c6dcb">append</a>.</p>

</div>
</div>

### RegsForValue() {#acc970ad3ae53c4651c93aea291dfb99e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegsForValue::RegsForValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 4 &gt; &amp; regs, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> regvt, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> valuevt, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> &gt; CC=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#ae0896c435305536fccf78b4fd263eae0">CallConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a1c16254f02fe53dec13cd46773ded1f3">RegCount</a>, <a href="#a70d3f48e8c5cf69454cd80e7a5224970">Regs</a>, <a href="#adc3cf865d5a653cfae070a5a64d2b3a9">RegVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a> and <a href="#a285fe7c1651ad46e272fbe0d4ef59189">ValueVTs</a>.</p>

</div>
</div>

### RegsForValue() {#a8334b2e523b8d9fa1d57f399cc08921f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegsForValue::RegsForValue (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> &gt; CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="#ae0896c435305536fccf78b4fd263eae0">CallConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42bf7ed3daec395fe644414494888bc6">llvm::TargetLoweringBase::getNumRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a315b23c0819f55fa9e7473c21992fc12">llvm::TargetLoweringBase::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af344c6bd2d070c999525df85be7688cf">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a347d293012b5070f6833926f3d2e50d7">llvm::TargetLoweringBase::getRegisterTypeForCallingConv</a>, <a href="#a1f8aefe8349b8f445625f678b051e16c">isABIMangled</a>, <a href="#a1c16254f02fe53dec13cd46773ded1f3">RegCount</a>, <a href="#a70d3f48e8c5cf69454cd80e7a5224970">Regs</a>, <a href="#adc3cf865d5a653cfae070a5a64d2b3a9">RegVTs</a> and <a href="#a285fe7c1651ad46e272fbe0d4ef59189">ValueVTs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddInlineAsmOperands() {#a73e723a22ad556552ca99f7e7a90a780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegsForValue::AddInlineAsmOperands (<a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94">InlineAsm::Kind</a> Code, bool HasMatching, unsigned MatchingIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add this value to the specified inlineasm node operand list.</p>


<p>This adds the code marker, matching input operand index (if applicable), and includes the number of values added into it.</p>


<p>Declaration at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1018 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94ac50132234eb8c934e71b7f2f0fa5099c">llvm::InlineAsm::Clobber</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42bf7ed3daec395fe644414494888bc6">llvm::TargetLoweringBase::getNumRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5de0162fac7c57cab62e5bb81f0b5542">llvm::TargetLoweringBase::getStackPointerRegisterToSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a51773b6c05f392988bf6395ccd1788ce">llvm::MachineFrameInfo::hasOpaqueSPAdjustment</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ac6bf744f357352cde7578931007c0b6f">llvm::Register::isVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a70d3f48e8c5cf69454cd80e7a5224970">Regs</a>, <a href="#adc3cf865d5a653cfae070a5a64d2b3a9">RegVTs</a> and <a href="#a285fe7c1651ad46e272fbe0d4ef59189">ValueVTs</a>.</p>

</div>
</div>

### append() {#a6a03067151ceb16293bd64c1831c6dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegsForValue::append (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/regsforvalue">RegsForValue</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the specified values to this one.</p>

<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>References <a href="#a1c16254f02fe53dec13cd46773ded1f3">RegCount</a>, <a href="#a70d3f48e8c5cf69454cd80e7a5224970">Regs</a>, <a href="#a123209f777591b5401b745f330892d5c">RegsForValue</a>, <a href="#adc3cf865d5a653cfae070a5a64d2b3a9">RegVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a285fe7c1651ad46e272fbe0d4ef59189">ValueVTs</a>.</p>

</div>
</div>

### getCopyFromRegs() {#ad782fe84b36a1c379ac9f1ac367706e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue RegsForValue::getCopyFromRegs (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Glue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a series of CopyFromReg nodes that copies from this value and returns the result as a ValueVTs value.</p>


<p>This uses Chain/Flag as the input and updates them for the output Chain/Flag. If the Flag pointer is NULL, no flag is used.</p>


<p>Declaration at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 875 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee4f13218bdbb5c5697f7e786618ecb2">llvm::ISD::AssertSext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863">llvm::ISD::AssertZext</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#ae0896c435305536fccf78b4fd263eae0">CallConv</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a7f47812e8e75b0616a97d7004e5fb909">llvm::KnownBits::countMinLeadingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a752372e170e4e7c595bf8810bb52adf2">llvm::EVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a347d293012b5070f6833926f3d2e50d7">llvm::TargetLoweringBase::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="#a1f8aefe8349b8f445625f678b051e16c">isABIMangled</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a437cf7bc875369cbe0ea62f949626f0b">llvm::MVT::isInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ac6bf744f357352cde7578931007c0b6f">llvm::Register::isVirtualRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#ac49dfd777da8c8caee8f3d6370ef14ea">llvm::FunctionLoweringInfo::LiveOutInfo::Known</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a01c94937492f3ac3fb1e0be8eb0b9ef1">llvm::ISD::MERGE_VALUES</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#a651904591143e71c02a94dca2659fc8e">llvm::FunctionLoweringInfo::LiveOutInfo::NumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a1c16254f02fe53dec13cd46773ded1f3">RegCount</a>, <a href="#a70d3f48e8c5cf69454cd80e7a5224970">Regs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a9c374320ed4e895f9afa199987182bd2">RegSize</a>, <a href="#adc3cf865d5a653cfae070a5a64d2b3a9">RegVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a> and <a href="#a285fe7c1651ad46e272fbe0d4ef59189">ValueVTs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac0b87e85b015d15077a7d9432c500df3">llvm::SelectionDAGBuilder::getCopyFromRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe3b2bbac4396d088da5c91f77754843">llvm::SelectionDAGBuilder::getValueImpl</a>.</p>

</div>
</div>

### getCopyToRegs() {#adf93dd21d49c19700e980b15f19cb7d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegsForValue::getCopyToRegs (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> * Glue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V=nullptr, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a> PreferredExtendType=<a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">ISD::ANY_EXTEND</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a series of CopyToReg nodes that copies the specified value into the registers specified by this object.</p>


<p>This uses Chain/Flag as the input and updates them for the output Chain/Flag. If the Flag pointer is nullptr, no flag is used. If V is not nullptr, then it is used in printing better diagnostic messages on error.</p>


<p>Declaration at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="#ae0896c435305536fccf78b4fd263eae0">CallConv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8910923e28ba24c5abedb60c66c86cc5">getCopyToParts</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a347d293012b5070f6833926f3d2e50d7">llvm::TargetLoweringBase::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac476ca9c302b9ba8d47ea7b02f6149f5">llvm::SDValue::getResNo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="#a1f8aefe8349b8f445625f678b051e16c">isABIMangled</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a342be90695496b88a8854a775dfd030f">llvm::TargetLoweringBase::isZExtFree</a>, <a href="#a1c16254f02fe53dec13cd46773ded1f3">RegCount</a>, <a href="#a70d3f48e8c5cf69454cd80e7a5224970">Regs</a>, <a href="#adc3cf865d5a653cfae070a5a64d2b3a9">RegVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>, <a href="#a285fe7c1651ad46e272fbe0d4ef59189">ValueVTs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a5184df56e270750a839acad50a1b8501">llvm::SelectionDAGBuilder::CopyValueToVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a32cff45e4cfd323ecc3896adcb08c2a9">llvm::SelectionDAGBuilder::LowerStatepoint</a>.</p>

</div>
</div>

### getRegsAndSizes() {#a03813938f6c7ea6b7e94965a27491ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; std::pair&lt; Register, TypeSize &gt;, 4 &gt; RegsForValue::getRegsAndSizes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a list of registers and their sizes.</p>

<p>Declaration at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>, definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a1c16254f02fe53dec13cd46773ded1f3">RegCount</a>, <a href="#a70d3f48e8c5cf69454cd80e7a5224970">Regs</a>, <a href="#adc3cf865d5a653cfae070a5a64d2b3a9">RegVTs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a740d35e0d3e2f7601f845b641fe58971">llvm::zip_first</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>.</p>

</div>
</div>

### isABIMangled() {#a1f8aefe8349b8f445625f678b051e16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegsForValue::isABIMangled ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Reference <a href="#ae0896c435305536fccf78b4fd263eae0">CallConv</a>.</p>


<p>Referenced by <a href="#ad782fe84b36a1c379ac9f1ac367706e1">getCopyFromRegs</a>, <a href="#adf93dd21d49c19700e980b15f19cb7d7">getCopyToRegs</a> and <a href="#a8334b2e523b8d9fa1d57f399cc08921f">RegsForValue</a>.</p>

</div>
</div>

### occupiesMultipleRegs() {#aed4c3ed13d5c82a825cb533010000347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegsForValue::occupiesMultipleRegs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the total RegCount is greater than one.</p>

<p>Definition at line 795 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Reference <a href="#a1c16254f02fe53dec13cd46773ded1f3">RegCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CallConv {#ae0896c435305536fccf78b4fd263eae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;CallingConv::ID&gt; llvm::RegsForValue::CallConv</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records if this value needs to be treated in an ABI dependant manner, different to normal type legalization.</p>

<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#ad782fe84b36a1c379ac9f1ac367706e1">getCopyFromRegs</a>, <a href="#adf93dd21d49c19700e980b15f19cb7d7">getCopyToRegs</a>, <a href="#a1f8aefe8349b8f445625f678b051e16c">isABIMangled</a>, <a href="#acc970ad3ae53c4651c93aea291dfb99e">RegsForValue</a> and <a href="#a8334b2e523b8d9fa1d57f399cc08921f">RegsForValue</a>.</p>

</div>
</div>

### RegCount {#a1c16254f02fe53dec13cd46773ded1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 4&gt; llvm::RegsForValue::RegCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This list holds the number of registers for each value.</p>

<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a6a03067151ceb16293bd64c1831c6dcb">append</a>, <a href="#ad782fe84b36a1c379ac9f1ac367706e1">getCopyFromRegs</a>, <a href="#adf93dd21d49c19700e980b15f19cb7d7">getCopyToRegs</a>, <a href="#a03813938f6c7ea6b7e94965a27491ddc">getRegsAndSizes</a>, <a href="#aed4c3ed13d5c82a825cb533010000347">occupiesMultipleRegs</a>, <a href="#acc970ad3ae53c4651c93aea291dfb99e">RegsForValue</a> and <a href="#a8334b2e523b8d9fa1d57f399cc08921f">RegsForValue</a>.</p>

</div>
</div>

### Regs {#a70d3f48e8c5cf69454cd80e7a5224970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 4&gt; llvm::RegsForValue::Regs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This list holds the registers assigned to the values.</p>


<p>Each legal or promoted value requires one register, and each expanded value requires multiple registers.</p>


<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a73e723a22ad556552ca99f7e7a90a780">AddInlineAsmOperands</a>, <a href="#a6a03067151ceb16293bd64c1831c6dcb">append</a>, <a href="#ad782fe84b36a1c379ac9f1ac367706e1">getCopyFromRegs</a>, <a href="#adf93dd21d49c19700e980b15f19cb7d7">getCopyToRegs</a>, <a href="#a03813938f6c7ea6b7e94965a27491ddc">getRegsAndSizes</a>, <a href="#acc970ad3ae53c4651c93aea291dfb99e">RegsForValue</a> and <a href="#a8334b2e523b8d9fa1d57f399cc08921f">RegsForValue</a>.</p>

</div>
</div>

### RegVTs {#adc3cf865d5a653cfae070a5a64d2b3a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MVT, 4&gt; llvm::RegsForValue::RegVTs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The value types of the registers.</p>


<p>This is the same size as ValueVTs and it records, for each value, what the type of the assigned register or registers are. (Individual values are never synthesized from more than one type of register.)</p>


<p>With virtual registers, the contents of RegVTs is redundant with TLI's getRegisterType member function, however when with physical registers it is necessary to have a separate record of the types.</p>


<p>Definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a73e723a22ad556552ca99f7e7a90a780">AddInlineAsmOperands</a>, <a href="#a6a03067151ceb16293bd64c1831c6dcb">append</a>, <a href="#ad782fe84b36a1c379ac9f1ac367706e1">getCopyFromRegs</a>, <a href="#adf93dd21d49c19700e980b15f19cb7d7">getCopyToRegs</a>, <a href="#a03813938f6c7ea6b7e94965a27491ddc">getRegsAndSizes</a>, <a href="#acc970ad3ae53c4651c93aea291dfb99e">RegsForValue</a> and <a href="#a8334b2e523b8d9fa1d57f399cc08921f">RegsForValue</a>.</p>

</div>
</div>

### ValueVTs {#a285fe7c1651ad46e272fbe0d4ef59189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;EVT, 4&gt; llvm::RegsForValue::ValueVTs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The value types of the values, which may not be legal, and may need be promoted or synthesized from one or more registers.</p>

<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a>.</p>


<p>Referenced by <a href="#a73e723a22ad556552ca99f7e7a90a780">AddInlineAsmOperands</a>, <a href="#a6a03067151ceb16293bd64c1831c6dcb">append</a>, <a href="#ad782fe84b36a1c379ac9f1ac367706e1">getCopyFromRegs</a>, <a href="#adf93dd21d49c19700e980b15f19cb7d7">getCopyToRegs</a>, <a href="#acc970ad3ae53c4651c93aea291dfb99e">RegsForValue</a> and <a href="#a8334b2e523b8d9fa1d57f399cc08921f">RegsForValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp">SelectionDAGBuilder.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-h">SelectionDAGBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
