---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/superregclassiterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SuperRegClassIterator` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SuperRegClassIterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75cd8d7ef877408dace338c8c57b67da">SuperRegClassIterator</a> (const TargetRegisterClass *RC, const TargetRegisterInfo *TRI, bool IncludeSelf=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/superregclassiterator">SuperRegClassIterator</a> that visits all the super-register classes of RC. <a href="#a75cd8d7ef877408dace338c8c57b67da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c807ec80af5f31096a4e9e5d2b7beb">operator++</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance iterator to the next entry. <a href="#a10c807ec80af5f31096a4e9e5d2b7beb">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01d3f3f418cd90ef87272b9459403d8">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this iterator is still pointing at a valid entry. <a href="#ab01d3f3f418cd90ef87272b9459403d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dcb80f8a022e0531621cecea3d469db">getSubReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the current sub-register index. <a href="#a4dcb80f8a022e0531621cecea3d469db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f920552b93c493f12da5ad41af45f8">getMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the bit mask of register classes that <a href="#a4dcb80f8a022e0531621cecea3d469db">getSubReg()</a> projects into RC. <a href="#a66f920552b93c493f12da5ad41af45f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac88ac164824d2dd6e8fe77c034c2708">RCMaskWords</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a450774f589407ab7352ffd166230a47f">SubReg</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9a7ef3e70562ed22068ecf33f6bf0d">Idx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a575be86fccccda72c7c1e33a5ad70">Mask</a></td>
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


<p>Definition at line 1254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SuperRegClassIterator() {#a75cd8d7ef877408dace338c8c57b67da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SuperRegClassIterator::SuperRegClassIterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, bool IncludeSelf=false)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/superregclassiterator">SuperRegClassIterator</a> that visits all the super-register classes of RC.</p>


<p>When IncludeSelf is set, also include the (0, sub-classes) entry.</p>


<p>Definition at line 1263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator++() {#a10c807ec80af5f31096a4e9e5d2b7beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SuperRegClassIterator::operator++ ()</td>
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

<p>Advance iterator to the next entry.</p>

<p>Definition at line 1284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab01d3f3f418cd90ef87272b9459403d8">isValid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMask() {#a66f920552b93c493f12da5ad41af45f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * llvm::SuperRegClassIterator::getMask ()</td>
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

<p>Returns the bit mask of register classes that <a href="#a4dcb80f8a022e0531621cecea3d469db">getSubReg()</a> projects into RC.</p>


<p>See <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#acf5c67f9a17117f6971d4341ef5018bf">TargetRegisterClass::getSubClassMask()</a> for how to use it.</p>


<p>Definition at line 1281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

### getSubReg() {#a4dcb80f8a022e0531621cecea3d469db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuperRegClassIterator::getSubReg ()</td>
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

<p>Returns the current sub-register index.</p>

<p>Definition at line 1276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

### isValid() {#ab01d3f3f418cd90ef87272b9459403d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SuperRegClassIterator::isValid ()</td>
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

<p>Returns true if this iterator is still pointing at a valid entry.</p>

<p>Definition at line 1273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac1cbaebc2a18476b73105d6916a56664">llvm::TargetLoweringBase::findRepresentativeClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#af14d27fb00fd2058e8da7eec1489df19">llvm::TargetRegisterInfo::getMatchingSuperRegClass</a> and <a href="#a10c807ec80af5f31096a4e9e5d2b7beb">operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Idx {#a3d9a7ef3e70562ed22068ecf33f6bf0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t* llvm::SuperRegClassIterator::Idx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

### Mask {#a71a575be86fccccda72c7c1e33a5ad70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t* llvm::SuperRegClassIterator::Mask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

### RCMaskWords {#aac88ac164824d2dd6e8fe77c034c2708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SuperRegClassIterator::RCMaskWords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

### SubReg {#a450774f589407ab7352ffd166230a47f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuperRegClassIterator::SubReg = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
