---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/webassemblyselectiondaginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WebAssemblySelectionDAGInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::WebAssemblySelectionDAGInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-h">Target/WebAssembly/WebAssemblySelectionDAGInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can subclass this to parameterize the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> lowering and instruction selection process. <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0397563bb09a2d4070efa1d8ed1fe3b6">~WebAssemblySelectionDAGInfo</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e0fe59c75c5881fbf9e853f1c5a8ae">isTargetMemoryOpcode</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a node with the given target-specific opcode has a memory operand. <a href="#ae7e0fe59c75c5881fbf9e853f1c5a8ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab4d3a4d8244caa1f031e2bba8089f9">EmitTargetCodeForMemcpy</a> (SelectionDAG &amp;DAG, const SDLoc &amp;dl, SDValue Chain, SDValue Op1, SDValue Op2, SDValue Op3, Align Alignment, bool isVolatile, bool AlwaysInline, MachinePointerInfo DstPtrInfo, MachinePointerInfo SrcPtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memcpy. <a href="#a2ab4d3a4d8244caa1f031e2bba8089f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b816955c5f4ac7b656e1b0e9f8b8d8d">EmitTargetCodeForMemmove</a> (SelectionDAG &amp;DAG, const SDLoc &amp;dl, SDValue Chain, SDValue Op1, SDValue Op2, SDValue Op3, Align Alignment, bool isVolatile, MachinePointerInfo DstPtrInfo, MachinePointerInfo SrcPtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memmove. <a href="#a9b816955c5f4ac7b656e1b0e9f8b8d8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3adcbeebb403a2dfff0ca610d0d746">EmitTargetCodeForMemset</a> (SelectionDAG &amp;DAG, const SDLoc &amp;DL, SDValue Chain, SDValue Op1, SDValue Op2, SDValue Op3, Align Alignment, bool IsVolatile, bool AlwaysInline, MachinePointerInfo DstPtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memset. <a href="#aac3adcbeebb403a2dfff0ca610d0d746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-h">WebAssemblySelectionDAGInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~WebAssemblySelectionDAGInfo() {#a0397563bb09a2d4070efa1d8ed1fe3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WebAssemblySelectionDAGInfo::~WebAssemblySelectionDAGInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-h">WebAssemblySelectionDAGInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitTargetCodeForMemcpy() {#a2ab4d3a4d8244caa1f031e2bba8089f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue WebAssemblySelectionDAGInfo::EmitTargetCodeForMemcpy (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op3, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool isVolatile, bool AlwaysInline, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> DstPtrInfo, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> SrcPtrInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit target-specific code that performs a memcpy.</p>


<p>This can be used by targets to provide code sequences for cases that don't fit the target's parameters for simple loads/stores and can be more efficient than using a library call. This function can return a null <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if the target declines to use custom code and a different lowering strategy should be used.</p>


<p>If AlwaysInline is true, the size is constant and the target should not emit any calls and is strongly encouraged to attempt to emit inline code even if it is beyond the usual threshold because this intrinsic is being expanded in a place where calls are not feasible (e.g. within the prologue for another call). If the target chooses to decline an AlwaysInline request here, legalize will resort to using simple loads and stores.</p>


<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-h">WebAssemblySelectionDAGInfo.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-cpp">WebAssemblySelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad0c6f059b29535f2c790d1c4f92b7a93">llvm::SelectionDAG::getZExtOrTrunc</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a9b816955c5f4ac7b656e1b0e9f8b8d8d">EmitTargetCodeForMemmove</a>.</p>

</div>
</div>

### EmitTargetCodeForMemmove() {#a9b816955c5f4ac7b656e1b0e9f8b8d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue WebAssemblySelectionDAGInfo::EmitTargetCodeForMemmove (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op3, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool isVolatile, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> DstPtrInfo, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> SrcPtrInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit target-specific code that performs a memmove.</p>


<p>This can be used by targets to provide code sequences for cases that don't fit the target's parameters for simple loads/stores and can be more efficient than using a library call. This function can return a null <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if the target declines to use custom code and a different lowering strategy should be used.</p>


<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-h">WebAssemblySelectionDAGInfo.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-cpp">WebAssemblySelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="#a2ab4d3a4d8244caa1f031e2bba8089f9">EmitTargetCodeForMemcpy</a>.</p>

</div>
</div>

### EmitTargetCodeForMemset() {#aac3adcbeebb403a2dfff0ca610d0d746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue WebAssemblySelectionDAGInfo::EmitTargetCodeForMemset (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op3, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool isVolatile, bool AlwaysInline, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> DstPtrInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit target-specific code that performs a memset.</p>


<p>This can be used by targets to provide code sequences for cases that don't fit the target's parameters for simple stores and can be more efficient than using a library call. This function can return a null <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> if the target declines to use custom code and a different lowering strategy should be used. Note that if AlwaysInline is true the function has to return a valid <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>.</p>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-h">WebAssemblySelectionDAGInfo.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-cpp">WebAssemblySelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aae7e97fa59261cc890aa2359971adfd4">llvm::SelectionDAG::getAnyExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad0c6f059b29535f2c790d1c4f92b7a93">llvm::SelectionDAG::getZExtOrTrunc</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### isTargetMemoryOpcode() {#ae7e0fe59c75c5881fbf9e853f1c5a8ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblySelectionDAGInfo::isTargetMemoryOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if a node with the given target-specific opcode has a memory operand.</p>


<p>Nodes with such opcodes can only be created with <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">SelectionDAG::getMemIntrinsicNode</a></span>.</p>


<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-h">WebAssemblySelectionDAGInfo.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-cpp">WebAssemblySelectionDAGInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-cpp">WebAssemblySelectionDAGInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyselectiondaginfo-h">WebAssemblySelectionDAGInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
