---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/scalablevectortype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ScalableVectorType` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::ScalableVectorType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">llvm/SandboxIR/Type.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype">VectorType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa62f2685c4d8d61f8f6ea9f346af76e9">getMinNumElements</a> () const</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd09e63057e199c5f4d85dcc0c3cd019">get</a> (Type *ElementType, unsigned MinNumElts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb562486f4088cacf7fff39b41932fca">get</a> (Type *ElementType, const ScalableVectorType *SVTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24bd5a94b49b62681a5e927c4306b8b0">getInteger</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f3e279b225c90ca971420721997678">getExtendedElementVectorType</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46173614a721f3d48da7d7bd58cd5b5">getTruncatedElementVectorType</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc9963652d7605b965ae25d4ed102494">getSubdividedVectorType</a> (ScalableVectorType *VTy, int NumSubdivs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27fbe7053be44c5c2d953dbb34c4248c">getHalfElementsVectorType</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac42f0896e89aa3e4c5f0ea41bd617605">getDoubleElementsVectorType</a> (ScalableVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a79c9248c99972db1d81df0bafb7dd">classof</a> (const Type *T)</td>
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


<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getMinNumElements() {#aa62f2685c4d8d61f8f6ea9f346af76e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::ScalableVectorType::getMinNumElements ()</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a330bbaf89b90196df6960be4724513c6">llvm::sandboxir::Type::LLVMTy</a>.</p>


<p>Referenced by <a href="#acb562486f4088cacf7fff39b41932fca">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a06a79c9248c99972db1d81df0bafb7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ScalableVectorType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * T)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### get() {#abd09e63057e199c5f4d85dcc0c3cd019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::sandboxir::ScalableVectorType::get (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * ElementType, unsigned MinNumElts)</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>

</div>
</div>

### get() {#acb562486f4088cacf7fff39b41932fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::sandboxir::ScalableVectorType::get (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> * SVTy)</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#af2cdf7082ff42d000af895d5e3e6335d">llvm::sandboxir::get</a> and <a href="#aa62f2685c4d8d61f8f6ea9f346af76e9">getMinNumElements</a>.</p>

</div>
</div>

### getDoubleElementsVectorType() {#ac42f0896e89aa3e4c5f0ea41bd617605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::sandboxir::ScalableVectorType::getDoubleElementsVectorType (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a992f8e70b5847690ae8ddb8adadc3037">llvm::sandboxir::VectorType::getDoubleElementsVectorType</a>.</p>

</div>
</div>

### getExtendedElementVectorType() {#a02f3e279b225c90ca971420721997678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::sandboxir::ScalableVectorType::getExtendedElementVectorType (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ac96d755c768edd2cde7743330bbb6f5a">llvm::sandboxir::VectorType::getExtendedElementVectorType</a>.</p>

</div>
</div>

### getHalfElementsVectorType() {#a27fbe7053be44c5c2d953dbb34c4248c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::sandboxir::ScalableVectorType::getHalfElementsVectorType (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a9cd3c5065659bc840e36b5a96ec94d96">llvm::sandboxir::VectorType::getHalfElementsVectorType</a>.</p>

</div>
</div>

### getInteger() {#a24bd5a94b49b62681a5e927c4306b8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::sandboxir::ScalableVectorType::getInteger (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a78f34fdeeb7b2cc30adc895344d8df0f">llvm::sandboxir::VectorType::getInteger</a>.</p>

</div>
</div>

### getSubdividedVectorType() {#acc9963652d7605b965ae25d4ed102494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::sandboxir::ScalableVectorType::getSubdividedVectorType (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> * VTy, int NumSubdivs)</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a2b3fb17faf3c8e599183efe5cbeb41ce">llvm::sandboxir::VectorType::getSubdividedVectorType</a>.</p>

</div>
</div>

### getTruncatedElementVectorType() {#ad46173614a721f3d48da7d7bd58cd5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalableVectorType * llvm::sandboxir::ScalableVectorType::getTruncatedElementVectorType (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/scalablevectortype">ScalableVectorType</a> * VTy)</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a950c035ff5222db07c7cc70a8d755e40">llvm::sandboxir::VectorType::getTruncatedElementVectorType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
