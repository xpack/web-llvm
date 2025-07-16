---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/objccontainerrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ObjCContainerRecord` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachO::ObjCContainerRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">llvm/TextAPI/Record.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/record">Record</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define <a href="/web-llvm/docs/api/classes/llvm/macho/record">Record</a>. <a href="/web-llvm/docs/api/classes/llvm/macho/record/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord">ObjCCategoryRecord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord">ObjCInterfaceRecord</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c5d891019f0f22072bf593df1545c0">ObjCContainerRecord</a> (StringRef Name, RecordLinkage Linkage)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord">ObjCIVarRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85376daae5640f771d4da0beeac835e9">addObjCIVar</a> (StringRef IVar, RecordLinkage Linkage)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord">ObjCIVarRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9669b1c810efd98e1173f2b0ca56aa0d">findObjCIVar</a> (StringRef IVar) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord">ObjCIVarRecord</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae884774726774b58b46eef58effa5ac1">getObjCIVars</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e6927d7418fa3873dd778f5db6dd2b">getLinkage</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa27d6e08de741442bc5cd6affed0cfc6">RecordMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord">ObjCIVarRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70625cf1e37a8d4f032ab13253915901">IVars</a></td>
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


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ObjCContainerRecord() {#a97c5d891019f0f22072bf593df1545c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::ObjCContainerRecord::ObjCContainerRecord (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Linkage)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4af6068daa29dbb05a7ead1e3b5a48bbee">llvm::MachO::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/record/#ac617292ffd14e2658362629e552ac3a8">llvm::MachO::Record::Linkage</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/record/#ae1da3190ebbff030b4f205be49606ec6">llvm::MachO::Record::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/record/#a26fd2afadedd7a56637f81fad0725470">llvm::MachO::Record::Record</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord/#aaca0ca74b7c3089e4c81252e8b4d75c8">llvm::MachO::ObjCCategoryRecord::ObjCCategoryRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord/#a1befb918686e43e4e912988cdecf2dcb">llvm::MachO::ObjCInterfaceRecord::ObjCInterfaceRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addObjCIVar() {#a85376daae5640f771d4da0beeac835e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCIVarRecord * ObjCContainerRecord::addObjCIVar (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IVar, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Linkage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/macho/record/#ac617292ffd14e2658362629e552ac3a8">llvm::MachO::Record::Linkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/recordsslice/#a41a1ad036885f6571a0b968e30c2b52f">llvm::MachO::RecordsSlice::addObjCIVar</a>.</p>

</div>
</div>

### findObjCIVar() {#a9669b1c810efd98e1173f2b0ca56aa0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjCIVarRecord * ObjCContainerRecord::findObjCIVar (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IVar)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp/#af60cd1eab7adb7cd85da1dfb85cbcf6e">findRecord</a>.</p>

</div>
</div>

### getLinkage() {#ab2e6927d7418fa3873dd778f5db6dd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordLinkage llvm::MachO::ObjCContainerRecord::getLinkage ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/macho/record/#ac617292ffd14e2658362629e552ac3a8">llvm::MachO::Record::Linkage</a>.</p>

</div>
</div>

### getObjCIVars() {#ae884774726774b58b46eef58effa5ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; ObjCIVarRecord * &gt; ObjCContainerRecord::getObjCIVars ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/macho/record/#a26fd2afadedd7a56637f81fad0725470">llvm::MachO::Record::Record</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#a4821f93278208c868cd078fb8afc2746">llvm::MachO::SymbolConverter::visitObjCCategory</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#a212640fcd49c76726374251900489631">llvm::MachO::SymbolConverter::visitObjCInterface</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IVars {#a70625cf1e37a8d4f032ab13253915901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordMap&lt;ObjCIVarRecord&gt; llvm::MachO::ObjCContainerRecord::IVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
