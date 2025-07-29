---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scalablevectortype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ScalableVectorType` Class

<p>Class to represent scalable SIMD vectors. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ScalableVectorType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class of all SIMD vector types. <a href="/web-llvm/docs/api/classes/llvm/vectortype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad291d76727438314ed23080b0eb88422">ScalableVectorType</a> (Type *ElTy, unsigned MinNumElts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7473a4e5eb5a49846c0c161a5e56d2a">getMinNumElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the minimum number of elements in this vector. <a href="#aa7473a4e5eb5a49846c0c161a5e56d2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6c82789f78714f2dfea41f443b99b7">get</a> (Type *ElementType, unsigned MinNumElts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238505bbc8fb213c2293630fc82ee9dc">get</a> (Type *ElementType, const ScalableVectorType *SVTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28794e2f573f76d9171a5cf18b085517">getInteger</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b2237c400e18061b981fd7bcf5bec4">getExtendedElementVectorType</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae179f1902b29144930348846cad0f777">getTruncatedElementVectorType</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8df4ed4f44d9dfc2fd7e064590f5ec5e">getSubdividedVectorType</a> (ScalableVectorType *VTy, int NumSubdivs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af250057bed5c4bc6124d0b00687a22">getHalfElementsVectorType</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e081f3e98a10acbda6534411db933f1">getDoubleElementsVectorType</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689fb94f9a641097e5f1ee309cfec4ac">classof</a> (const Type *T)</td>
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

<p>Class to represent scalable SIMD vectors.</p>

<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### ScalableVectorType() {#ad291d76727438314ed23080b0eb88422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScalableVectorType::ScalableVectorType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElTy, unsigned MinNumElts)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">llvm::VectorType::VectorType</a>.</p>


<p>Referenced by <a href="#a238505bbc8fb213c2293630fc82ee9dc">get</a>, <a href="#a8e081f3e98a10acbda6534411db933f1">getDoubleElementsVectorType</a>, <a href="#a69b2237c400e18061b981fd7bcf5bec4">getExtendedElementVectorType</a>, <a href="#a6af250057bed5c4bc6124d0b00687a22">getHalfElementsVectorType</a>, <a href="#a28794e2f573f76d9171a5cf18b085517">getInteger</a>, <a href="#a8df4ed4f44d9dfc2fd7e064590f5ec5e">getSubdividedVectorType</a> and <a href="#ae179f1902b29144930348846cad0f777">getTruncatedElementVectorType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMinNumElements() {#aa7473a4e5eb5a49846c0c161a5e56d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScalableVectorType::getMinNumElements ()</td>
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

<p>Get the minimum number of elements in this vector.</p>


<p>The actual number of elements in the vector is an integer multiple of this value.</p>


<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a9531bece2eddd17e21a9fd250fcbe50a">llvm::VectorType::ElementQuantity</a>.</p>


<p>Referenced by <a href="#a238505bbc8fb213c2293630fc82ee9dc">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a689fb94f9a641097e5f1ee309cfec4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScalableVectorType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### get() {#a5f6c82789f78714f2dfea41f443b99b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * ScalableVectorType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, unsigned MinNumElts)</td>
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



<p>Declaration at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 812 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="#a238505bbc8fb213c2293630fc82ee9dc">get</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a031124353d199e69bbc9101bde19b023">llvm::AArch64TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7915bab3089583402f61b46f7baea356">instCombineSVECmpNE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#afdcb3be103dc32527286d0352eeacdd6">instCombineSVEDupqLane</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypesequential/#gac3f357b97efc36f5eb74643e5bbe44b9">LLVMScalableVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a22c6a7a1925a0177519e33d49ba91cea">llvm::RISCVTargetLowering::lowerInterleaveIntrinsicToStore</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>.</p>

</div>
</div>

### get() {#a238505bbc8fb213c2293630fc82ee9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::ScalableVectorType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> * SVTy)</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="#a5f6c82789f78714f2dfea41f443b99b7">get</a>, <a href="#aa7473a4e5eb5a49846c0c161a5e56d2a">getMinNumElements</a> and <a href="#ad291d76727438314ed23080b0eb88422">ScalableVectorType</a>.</p>

</div>
</div>

### getDoubleElementsVectorType() {#a8e081f3e98a10acbda6534411db933f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::ScalableVectorType::getDoubleElementsVectorType (<a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#ac423a4165a8f57cd2865ef33dd9be484">llvm::VectorType::getDoubleElementsVectorType</a> and <a href="#ad291d76727438314ed23080b0eb88422">ScalableVectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aac6aaf36d8c34dfd27b90fc04ea3c08f">instCombineSVEUzp1</a>.</p>

</div>
</div>

### getExtendedElementVectorType() {#a69b2237c400e18061b981fd7bcf5bec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::ScalableVectorType::getExtendedElementVectorType (<a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a3b1f5f847d812d85eaaa8a19bd01bcf4">llvm::VectorType::getExtendedElementVectorType</a> and <a href="#ad291d76727438314ed23080b0eb88422">ScalableVectorType</a>.</p>

</div>
</div>

### getHalfElementsVectorType() {#a6af250057bed5c4bc6124d0b00687a22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::ScalableVectorType::getHalfElementsVectorType (<a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a12589d52afe7ea72485b0a431327a6e6">llvm::VectorType::getHalfElementsVectorType</a> and <a href="#ad291d76727438314ed23080b0eb88422">ScalableVectorType</a>.</p>

</div>
</div>

### getInteger() {#a28794e2f573f76d9171a5cf18b085517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::ScalableVectorType::getInteger (<a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a781c723920fb1d098c4d959f3218d9aa">llvm::VectorType::getInteger</a> and <a href="#ad291d76727438314ed23080b0eb88422">ScalableVectorType</a>.</p>

</div>
</div>

### getSubdividedVectorType() {#a8df4ed4f44d9dfc2fd7e064590f5ec5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::ScalableVectorType::getSubdividedVectorType (<a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> * VTy, int NumSubdivs)</td>
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



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a62425c077bf32e483e2e041e26bce530">llvm::VectorType::getSubdividedVectorType</a> and <a href="#ad291d76727438314ed23080b0eb88422">ScalableVectorType</a>.</p>

</div>
</div>

### getTruncatedElementVectorType() {#ae179f1902b29144930348846cad0f777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::ScalableVectorType::getTruncatedElementVectorType (<a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a> and <a href="#ad291d76727438314ed23080b0eb88422">ScalableVectorType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
