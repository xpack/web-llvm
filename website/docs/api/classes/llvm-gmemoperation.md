---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gmemoperation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GMemOperation` Class

<p>Provides common memory operand functionality. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GMemOperation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">llvm/CodeGen/GlobalISel/GenericMachineInstrs.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr">GenericMachineInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for all GenericMachineInstrs. <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gindexedload">GIndexedLoad</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents indexed loads. <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gindexedstore">GIndexedStore</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents indexed stores. <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gloadstore">GLoadStore</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents any type of generic load or store. <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a130e12a0a8b3fe8149fe7b5eecfa603e">getMMO</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> on this instruction. <a href="#a130e12a0a8b3fe8149fe7b5eecfa603e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c309120c87f6a16704169f193bfc711">isAtomic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the attached <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> has the atomic flag set. <a href="#a9c309120c87f6a16704169f193bfc711">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabaa8933d3413bda663f85d8bc2086db">isVolatile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the attached MachineMemOpeand as the volatile flag set. <a href="#aabaa8933d3413bda663f85d8bc2086db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c1a69379306b47f0302688d3427b60">isSimple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the memory operation is neither atomic or volatile. <a href="#ae8c1a69379306b47f0302688d3427b60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de9f33a91663caa0f07d6f873514b65">isUnordered</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this memory operation doesn't have any ordering constraints other than normal aliasing. <a href="#a5de9f33a91663caa0f07d6f873514b65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515116c40bd191aee04f328b504d5692">getMemSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size in bytes of the memory access. <a href="#a515116c40bd191aee04f328b504d5692">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac815a03646b3fcf26176feb2c669fb9e">getMemSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size in bits of the memory access. <a href="#ac815a03646b3fcf26176feb2c669fb9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaa5db930b7885b643e3bb36a0cdfc43">classof</a> (const MachineInstr *MI)</td>
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

<p>Provides common memory operand functionality.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getMemSize() {#a515116c40bd191aee04f328b504d5692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::GMemOperation::getMemSize ()</td>
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

<p>Returns the size in bytes of the memory access.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>References <a href="#a130e12a0a8b3fe8149fe7b5eecfa603e">getMMO</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>.</p>

</div>
</div>

### getMemSizeInBits() {#ac815a03646b3fcf26176feb2c669fb9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::GMemOperation::getMemSizeInBits ()</td>
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

<p>Returns the size in bits of the memory access.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>References <a href="#a130e12a0a8b3fe8149fe7b5eecfa603e">getMMO</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abcceb535a4bb1e23c320e7628476bd5d">llvm::MachineMemOperand::getSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a0f3bc0c5478dd84e0831b5d78a274b47">llvm::CombinerHelper::matchEqualDefs</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcinstructionselector-cpp-/ppcinstructionselector/#a051c8a2638fc5f95b9ccd5e82a7a8559">anonymous{PPCInstructionSelector.cpp}::PPCInstructionSelector::select</a>.</p>

</div>
</div>

### getMMO() {#a130e12a0a8b3fe8149fe7b5eecfa603e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineMemOperand &amp; llvm::GMemOperation::getMMO ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> on this instruction.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa5ff177bc1498508696aaf27235db3fc">llvm::MachineInstr::memoperands_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a75ae99f242b3954f52d12c85e53d5f41">llvm::CombinerHelper::applySextInRegOfLoad</a>, <a href="#a515116c40bd191aee04f328b504d5692">getMemSize</a>, <a href="#ac815a03646b3fcf26176feb2c669fb9e">getMemSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/ganyload/#af79e3c82a97791f6e46aecd8bbdcf6ac">llvm::GAnyLoad::getRanges</a>, <a href="#a9c309120c87f6a16704169f193bfc711">isAtomic</a>, <a href="#a5de9f33a91663caa0f07d6f873514b65">isUnordered</a>, <a href="#aabaa8933d3413bda663f85d8bc2086db">isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab5ece2e19fefdc8f1112b05d6274e649">llvm::CombinerHelper::matchCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a070e7ae88917971c8b99b3bb7f3d5942">llvm::CombinerHelper::matchLoadOrCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>.</p>

</div>
</div>

### isAtomic() {#a9c309120c87f6a16704169f193bfc711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GMemOperation::isAtomic ()</td>
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

<p>Returns true if the attached <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> has the atomic flag set.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>References <a href="#a130e12a0a8b3fe8149fe7b5eecfa603e">getMMO</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a6829ff090c767b553f2390e0785adf4a">llvm::MachineMemOperand::isAtomic</a>.</p>


<p>Referenced by <a href="#ae8c1a69379306b47f0302688d3427b60">isSimple</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a2591ea6476cd4c80dd7f0fc9be1d3d74">llvm::CombinerHelper::matchCombineIndexedLoadStore</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a>.</p>

</div>
</div>

### isSimple() {#ae8c1a69379306b47f0302688d3427b60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GMemOperation::isSimple ()</td>
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

<p>Returns true if the memory operation is neither atomic or volatile.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>References <a href="#a9c309120c87f6a16704169f193bfc711">isAtomic</a> and <a href="#aabaa8933d3413bda663f85d8bc2086db">isVolatile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>.</p>

</div>
</div>

### isUnordered() {#a5de9f33a91663caa0f07d6f873514b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GMemOperation::isUnordered ()</td>
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

<p>Returns true if this memory operation doesn't have any ordering constraints other than normal aliasing.</p>


<p>Volatile and (ordered) atomic memory operations can't be reordered.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>References <a href="#a130e12a0a8b3fe8149fe7b5eecfa603e">getMMO</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a55d6f8587efdb9efb8cb374f11fe4408">llvm::MachineMemOperand::isUnordered</a>.</p>

</div>
</div>

### isVolatile() {#aabaa8933d3413bda663f85d8bc2086db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GMemOperation::isVolatile ()</td>
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

<p>Returns true if the attached MachineMemOpeand as the volatile flag set.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>References <a href="#a130e12a0a8b3fe8149fe7b5eecfa603e">getMMO</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a1d07cda64e7150bb7f330057c41a2965">llvm::MachineMemOperand::isVolatile</a>.</p>


<p>Referenced by <a href="#ae8c1a69379306b47f0302688d3427b60">isSimple</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#abaa5db930b7885b643e3bb36a0cdfc43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GMemOperation::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a0acacca59ced382e438ce720b92affd5">llvm::GenericMachineInstr::classof</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
