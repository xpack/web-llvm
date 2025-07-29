---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-lowermatrixintrinsics-cpp-/anonymous-lowermatrixintrinsics-cpp-/shapeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ShapeInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9234995de8f41a501e91be7d5c1a0c3b">ShapeInfo</a> (unsigned NumRows=0, unsigned NumColumns=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b6a8356b7604712cf8c80d4dffd1ed">ShapeInfo</a> (Value *NumRows, Value *NumColumns)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8a5460689af5ec9797bc64f63a092f">operator==</a> (const ShapeInfo &amp;other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa893a0d803da53dfab83c9248f1ca0ed">operator!=</a> (const ShapeInfo &amp;other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76fc8a2aaebff968abeed0ad6ad46e6d">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if shape-information is defined, meaning both dimensions are != 0. <a href="#a76fc8a2aaebff968abeed0ad6ad46e6d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef785b83f386a4bfcc5ab30a981a80f7">getStride</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec954156d2fd29de4f171ec9af0b73d">getNumVectors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/anonymous-lowermatrixintrinsics-cpp-/shapeinfo">ShapeInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc9b46906eb90767d9ec428bacb30d4">t</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the transposed shape. <a href="#a4dc9b46906eb90767d9ec428bacb30d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceadf5aacd5332ef600b9fe1af594405">NumRows</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18a04a957c0769d9ead65b88f1718e7d">NumColumns</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9cd3edba0a9371f5018c4beebefa46e">IsColumnMajor</a></td>
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


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ShapeInfo() {#a9234995de8f41a501e91be7d5c1a0c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::ShapeInfo (unsigned NumRows=0, unsigned NumColumns=0)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#abf221949fc61d1494af06b50731bdc90af695e73139b1c1d06d77655104370f00">ColumnMajor</a>, <a href="#ac9cd3edba0a9371f5018c4beebefa46e">IsColumnMajor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af65c97118cdb2629b72d9eeb2f218372">MatrixLayout</a>, <a href="#a18a04a957c0769d9ead65b88f1718e7d">NumColumns</a> and <a href="#aceadf5aacd5332ef600b9fe1af594405">NumRows</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-lowermatrixintrinsics-cpp-/#abb6c70c6f3c205d6a0b73be4534c0de5">anonymous{LowerMatrixIntrinsics.cpp}::computeShapeInfoForInst</a>, <a href="#aa893a0d803da53dfab83c9248f1ca0ed">operator!=</a>, <a href="#abb8a5460689af5ec9797bc64f63a092f">operator==</a>, <a href="#a85b6a8356b7604712cf8c80d4dffd1ed">ShapeInfo</a> and <a href="#a4dc9b46906eb90767d9ec428bacb30d4">t</a>.</p>

</div>
</div>

### ShapeInfo() {#a85b6a8356b7604712cf8c80d4dffd1ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::ShapeInfo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumRows, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumColumns)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a18a04a957c0769d9ead65b88f1718e7d">NumColumns</a>, <a href="#aceadf5aacd5332ef600b9fe1af594405">NumRows</a> and <a href="#a9234995de8f41a501e91be7d5c1a0c3b">ShapeInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a76fc8a2aaebff968abeed0ad6ad46e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::operator bool ()</td>
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

<p>Returns true if shape-information is defined, meaning both dimensions are != 0.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a18a04a957c0769d9ead65b88f1718e7d">NumColumns</a> and <a href="#aceadf5aacd5332ef600b9fe1af594405">NumRows</a>.</p>

</div>
</div>

### operator!=() {#aa893a0d803da53dfab83c9248f1ca0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/anonymous-lowermatrixintrinsics-cpp-/shapeinfo">ShapeInfo</a> &amp; other)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Reference <a href="#a9234995de8f41a501e91be7d5c1a0c3b">ShapeInfo</a>.</p>

</div>
</div>

### operator==() {#abb8a5460689af5ec9797bc64f63a092f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/anonymous-lowermatrixintrinsics-cpp-/shapeinfo">ShapeInfo</a> &amp; other)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="#a18a04a957c0769d9ead65b88f1718e7d">NumColumns</a>, <a href="#aceadf5aacd5332ef600b9fe1af594405">NumRows</a> and <a href="#a9234995de8f41a501e91be7d5c1a0c3b">ShapeInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNumVectors() {#a9ec954156d2fd29de4f171ec9af0b73d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::getNumVectors ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="#ac9cd3edba0a9371f5018c4beebefa46e">IsColumnMajor</a>, <a href="#a18a04a957c0769d9ead65b88f1718e7d">NumColumns</a> and <a href="#aceadf5aacd5332ef600b9fe1af594405">NumRows</a>.</p>

</div>
</div>

### getStride() {#aef785b83f386a4bfcc5ab30a981a80f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::getStride ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="#ac9cd3edba0a9371f5018c4beebefa46e">IsColumnMajor</a>, <a href="#a18a04a957c0769d9ead65b88f1718e7d">NumColumns</a> and <a href="#aceadf5aacd5332ef600b9fe1af594405">NumRows</a>.</p>

</div>
</div>

### t() {#a4dc9b46906eb90767d9ec428bacb30d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShapeInfo anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::t ()</td>
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

<p>Returns the transposed shape.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>References <a href="#a18a04a957c0769d9ead65b88f1718e7d">NumColumns</a>, <a href="#aceadf5aacd5332ef600b9fe1af594405">NumRows</a> and <a href="#a9234995de8f41a501e91be7d5c1a0c3b">ShapeInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsColumnMajor {#ac9cd3edba0a9371f5018c4beebefa46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::IsColumnMajor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="#a9ec954156d2fd29de4f171ec9af0b73d">getNumVectors</a>, <a href="#aef785b83f386a4bfcc5ab30a981a80f7">getStride</a> and <a href="#a9234995de8f41a501e91be7d5c1a0c3b">ShapeInfo</a>.</p>

</div>
</div>

### NumColumns {#a18a04a957c0769d9ead65b88f1718e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::NumColumns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="#a9ec954156d2fd29de4f171ec9af0b73d">getNumVectors</a>, <a href="#aef785b83f386a4bfcc5ab30a981a80f7">getStride</a>, <a href="#a76fc8a2aaebff968abeed0ad6ad46e6d">operator bool</a>, <a href="#abb8a5460689af5ec9797bc64f63a092f">operator==</a>, <a href="#a9234995de8f41a501e91be7d5c1a0c3b">ShapeInfo</a>, <a href="#a85b6a8356b7604712cf8c80d4dffd1ed">ShapeInfo</a> and <a href="#a4dc9b46906eb90767d9ec428bacb30d4">t</a>.</p>

</div>
</div>

### NumRows {#aceadf5aacd5332ef600b9fe1af594405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LowerMatrixIntrinsics.cpp}::anonymous{LowerMatrixIntrinsics.cpp}::ShapeInfo::NumRows</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a>.</p>


<p>Referenced by <a href="#a9ec954156d2fd29de4f171ec9af0b73d">getNumVectors</a>, <a href="#aef785b83f386a4bfcc5ab30a981a80f7">getStride</a>, <a href="#a76fc8a2aaebff968abeed0ad6ad46e6d">operator bool</a>, <a href="#abb8a5460689af5ec9797bc64f63a092f">operator==</a>, <a href="#a9234995de8f41a501e91be7d5c1a0c3b">ShapeInfo</a>, <a href="#a85b6a8356b7604712cf8c80d4dffd1ed">ShapeInfo</a> and <a href="#a4dc9b46906eb90767d9ec428bacb30d4">t</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp">LowerMatrixIntrinsics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
