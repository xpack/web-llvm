---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/x86selectiondaginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86SelectionDAGInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::X86SelectionDAGInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-h">Target/X86/X86SelectionDAGInfo.h</a>"
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa586666fb99ba82adfd949fcb5df375e">X86SelectionDAGInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415f8b8d924531b36b682943b5f55a79">isTargetMemoryOpcode</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a node with the given target-specific opcode has a memory operand. <a href="#a415f8b8d924531b36b682943b5f55a79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d13fb026b38446469f2a27bb7519d06">isTargetStrictFPOpcode</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a node with the given target-specific opcode has strict floating-point semantics. <a href="#a6d13fb026b38446469f2a27bb7519d06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0597706526940b36ec2a6e5fb1e41d7">EmitTargetCodeForMemset</a> (SelectionDAG &amp;DAG, const SDLoc &amp;dl, SDValue Chain, SDValue Dst, SDValue Src, SDValue Size, Align Alignment, bool isVolatile, bool AlwaysInline, MachinePointerInfo DstPtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memset. <a href="#aa0597706526940b36ec2a6e5fb1e41d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96fa506e62ed4b22ab4e9eaac0edaf61">EmitTargetCodeForMemcpy</a> (SelectionDAG &amp;DAG, const SDLoc &amp;dl, SDValue Chain, SDValue Dst, SDValue Src, SDValue Size, Align Alignment, bool isVolatile, bool AlwaysInline, MachinePointerInfo DstPtrInfo, MachinePointerInfo SrcPtrInfo) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit target-specific code that performs a memcpy. <a href="#a96fa506e62ed4b22ab4e9eaac0edaf61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7587932a0d75f622c99bef8e52cc1a4a">isBaseRegConflictPossible</a> (SelectionDAG &amp;DAG, ArrayRef&lt; MCPhysReg &gt; ClobberSet) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is possible for the base register to conflict with the given set of clobbers for a memory intrinsic. <a href="#a7587932a0d75f622c99bef8e52cc1a4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-h">X86SelectionDAGInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86SelectionDAGInfo() {#aa586666fb99ba82adfd949fcb5df375e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::X86SelectionDAGInfo::X86SelectionDAGInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-h">X86SelectionDAGInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitTargetCodeForMemcpy() {#a96fa506e62ed4b22ab4e9eaac0edaf61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86SelectionDAGInfo::EmitTargetCodeForMemcpy (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op3, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool isVolatile, bool AlwaysInline, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> DstPtrInfo, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> SrcPtrInfo)</td>
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


<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-h">X86SelectionDAGInfo.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp">X86SelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#a6d50362e845dcbafcf632cb5b98b240f">emitConstantSizeRepmov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#acd303d58146a6b598490fa05692c1fb4">emitRepmovs</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a2788ec4ff3130471e24ab77dc08f7c50">llvm::MachinePointerInfo::getAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#aa97774432737736e15e395f3d24827db">UseFSRMForMemcpy</a>.</p>

</div>
</div>

### EmitTargetCodeForMemset() {#aa0597706526940b36ec2a6e5fb1e41d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86SelectionDAGInfo::EmitTargetCodeForMemset (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op3, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool isVolatile, bool AlwaysInline, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> DstPtrInfo)</td>
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


<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-h">X86SelectionDAGInfo.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp">X86SelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#ac6a86b853c0a0262731e7e8b084c0980">emitConstantSizeRepstos</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a2788ec4ff3130471e24ab77dc08f7c50">llvm::MachinePointerInfo::getAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a5cb49674ec65724b4d9aecb48588a13a">llvm::ConstantSDNode::getZExtValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### isTargetMemoryOpcode() {#a415f8b8d924531b36b682943b5f55a79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86SelectionDAGInfo::isTargetMemoryOpcode (unsigned Opcode)</td>
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


<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-h">X86SelectionDAGInfo.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp">X86SelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa88eab0f3f37b1ae95ccc40f69075f975">llvm::X86ISD::FIRST_MEMORY_OPCODE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8ae930c725ba632011e1ae7e1eecda5a">llvm::X86ISD::LAST_MEMORY_OPCODE</a>.</p>

</div>
</div>

### isTargetStrictFPOpcode() {#a6d13fb026b38446469f2a27bb7519d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86SelectionDAGInfo::isTargetStrictFPOpcode (unsigned Opcode)</td>
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

<p>Returns true if a node with the given target-specific opcode has strict floating-point semantics.</p>

<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-h">X86SelectionDAGInfo.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp">X86SelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aafb1d40d2d5be36b2802e39c46f42bcec">llvm::X86ISD::FIRST_STRICTFP_OPCODE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aade2bbda69cf12cb28e43fa4e4d056241">llvm::X86ISD::LAST_STRICTFP_OPCODE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isBaseRegConflictPossible() {#a7587932a0d75f622c99bef8e52cc1a4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86SelectionDAGInfo::isBaseRegConflictPossible (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; ClobberSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if it is possible for the base register to conflict with the given set of clobbers for a memory intrinsic.</p>

<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-h">X86SelectionDAGInfo.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp">X86SelectionDAGInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp">X86SelectionDAGInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-h">X86SelectionDAGInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
