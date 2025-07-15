---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/elfsectionref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ELFSectionRef` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::ELFSectionRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">llvm/Object/ELFObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a value type class that represents a single section in the list of sections in the object file. <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4adc966e00d57fb68b91ea203d8c119">ELFSectionRef</a> (const SectionRef &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase">ELFObjectFileBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781194b172ea38248b42801f65e3f071">getObject</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50a33a2b9a8bb4f0308ac8ae8e614d3">getType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65cfa3f4710cddbc95dc790ffe80a658">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89effab364d0a163ab419a879c6bbe9e">getOffset</a> () const</td>
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


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ELFSectionRef() {#ab4adc966e00d57fb68b91ea203d8c119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::ELFSectionRef::ELFSectionRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; B)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#af325f1df60eef3a8a8a47e22a1f43c5e">llvm::object::SectionRef::getObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a92bedaaa222dbfcf63f2219d872291d3">llvm::object::SectionRef::SectionRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFlags() {#a65cfa3f4710cddbc95dc790ffe80a658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFSectionRef::getFlags ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a781194b172ea38248b42801f65e3f071">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a1f7697438cbf778f7d1b051e97204606">llvm::object::SectionRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a5a43e2c5f7caa16cb7ee5313abd829f9">llvm::object::ELFObjectFileBase::getSectionFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a1b2e1cb1c6d2d1f8a038916a90f993a9">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::fillSectionInformation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92107a34e05220d72ef61d8416be486e">llvm::isReadOnlyData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af84608c14d72c4d634360ce6a536e4a4">llvm::isRequiredForExecution</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3c9c204f9d38e82b1f67b87df65bcab0">llvm::isTLS</a>.</p>

</div>
</div>

### getObject() {#a781194b172ea38248b42801f65e3f071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ELFObjectFileBase * llvm::object::ELFSectionRef::getObject ()</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#af325f1df60eef3a8a8a47e22a1f43c5e">llvm::object::SectionRef::getObject</a>.</p>


<p>Referenced by <a href="#a65cfa3f4710cddbc95dc790ffe80a658">getFlags</a>, <a href="#a89effab364d0a163ab419a879c6bbe9e">getOffset</a> and <a href="#ab50a33a2b9a8bb4f0308ac8ae8e614d3">getType</a>.</p>

</div>
</div>

### getOffset() {#a89effab364d0a163ab419a879c6bbe9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::ELFSectionRef::getOffset ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a781194b172ea38248b42801f65e3f071">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a1f7697438cbf778f7d1b051e97204606">llvm::object::SectionRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#af07b10fb70f0c6b9c0e27a032019fab7">llvm::object::ELFObjectFileBase::getSectionOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a1b2e1cb1c6d2d1f8a038916a90f993a9">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::fillSectionInformation</a>.</p>

</div>
</div>

### getType() {#ab50a33a2b9a8bb4f0308ac8ae8e614d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::ELFSectionRef::getType ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a>.</p>


<p>References <a href="#a781194b172ea38248b42801f65e3f071">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a1f7697438cbf778f7d1b051e97204606">llvm::object::SectionRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a8146832410779867e8d49382ce55add8">llvm::object::ELFObjectFileBase::getSectionType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a426a48f358aaf6be7a95428dae0d4f31">anonymous{OffloadBinary.cpp}::extractFromObject</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac0bcf1406ba361ae499b251f7cd33ac9">llvm::isZeroInit</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elfobjectfile-h">ELFObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
