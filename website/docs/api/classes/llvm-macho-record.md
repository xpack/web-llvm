---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/record
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Record` Class

<p>Define <a href="/web-llvm/docs/api/classes/llvm/macho/record">Record</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachO::Record { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">llvm/TextAPI/Record.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord">GlobalRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord">ObjCContainerRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord">ObjCIVarRecord</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab278f1a89b32d95df4ed5ef7dbafc892">RecordsSlice</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26fd2afadedd7a56637f81fad0725470">Record</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a829b3d0e548c498383702df2368b7">Record</a> (StringRef Name, RecordLinkage Linkage, SymbolFlags Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2faaddd759c2c6aad86466b697354a">isWeakDefined</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3f7c6f7b11a738c421391707a88ef7">isWeakReferenced</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f46eeca206af39f6539258e31e33d4c">isThreadLocalValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a986ed20ca0aa9ba9b7cb690fe57e75cc">isData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe12f8f753ee1908c244c2ec5daf0f36">isText</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f8339d96c4b97a11d8b65e5b2c9d77">isInternal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a172b785813d0cf80daf3936777ced74a">isUndefined</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d8c8eb5e266ee7fe20838b3d4dd920">isExported</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac34f3ecda3a5a0214766f86130930f1d">isRexported</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da118e468e332e780b403591881e52b">isVerified</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35cd698765763e43ab57a81c803f0fd">setVerify</a> (bool V=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a275e8a5b9303c59fe00b7eecd1066f6b">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a671acbd063953da6403ccbd2fa35c349">getFlags</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a693fd723e699552c81b2751391a872ba">mergeFlags</a> (SymbolFlags Flags, RecordLinkage Linkage)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1da3190ebbff030b4f205be49606ec6">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac617292ffd14e2658362629e552ac3a8">Linkage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaaf6d0b389985f5d39ae6cbb6bb3968">Flags</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe5fc0e2c20106f21c45b212e9026d5">Verified</a></td>
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

<p>Define <a href="/web-llvm/docs/api/classes/llvm/macho/record">Record</a>.</p>


<p>They represent API's in binaries that could be linkable symbols.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Friends

### RecordsSlice {#ab278f1a89b32d95df4ed5ef7dbafc892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/macho/recordsslice">RecordsSlice</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Reference <a href="#ab278f1a89b32d95df4ed5ef7dbafc892">RecordsSlice</a>.</p>


<p>Referenced by <a href="#ab278f1a89b32d95df4ed5ef7dbafc892">RecordsSlice</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Record() {#a26fd2afadedd7a56637f81fad0725470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::Record::Record ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#ae884774726774b58b46eef58effa5ac1">llvm::MachO::ObjCContainerRecord::getObjCIVars</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#a0e224eeea061497db8c1de4e465bebb6">llvm::MachO::GlobalRecord::GlobalRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#a97c5d891019f0f22072bf593df1545c0">llvm::MachO::ObjCContainerRecord::ObjCContainerRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord/#a48af4fe3e956ac6c22704700e64d0941">llvm::MachO::ObjCIVarRecord::ObjCIVarRecord</a>.</p>

</div>
</div>

### Record() {#a63a829b3d0e548c498383702df2368b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::Record::Record (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Linkage, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> Flags)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="#afaaf6d0b389985f5d39ae6cbb6bb3968">Flags</a>, <a href="#ac617292ffd14e2658362629e552ac3a8">Linkage</a>, <a href="#ae1da3190ebbff030b4f205be49606ec6">Name</a> and <a href="#aebe5fc0e2c20106f21c45b212e9026d5">Verified</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFlags() {#a671acbd063953da6403ccbd2fa35c349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolFlags llvm::MachO::Record::getFlags ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Reference <a href="#afaaf6d0b389985f5d39ae6cbb6bb3968">Flags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#ab3e40f86314ef9875bfd12cd2eab9b5e">llvm::MachO::SymbolConverter::visitGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#a212640fcd49c76726374251900489631">llvm::MachO::SymbolConverter::visitObjCInterface</a>.</p>

</div>
</div>

### getName() {#a275e8a5b9303c59fe00b7eecd1066f6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachO::Record::getName ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Reference <a href="#ae1da3190ebbff030b4f205be49606ec6">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#ab3e40f86314ef9875bfd12cd2eab9b5e">llvm::MachO::SymbolConverter::visitGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/symbolconverter/#a212640fcd49c76726374251900489631">llvm::MachO::SymbolConverter::visitObjCInterface</a>.</p>

</div>
</div>

### isData() {#a986ed20ca0aa9ba9b7cb690fe57e75cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isData ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4af6068daa29dbb05a7ead1e3b5a48bbee">llvm::MachO::Data</a> and <a href="#afaaf6d0b389985f5d39ae6cbb6bb3968">Flags</a>.</p>

</div>
</div>

### isExported() {#ad0d8c8eb5e266ee7fe20838b3d4dd920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isExported ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="#ac617292ffd14e2658362629e552ac3a8">Linkage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa6994917dfcfb9ef55fc6bce4b454f9a4">llvm::MachO::Rexported</a>.</p>

</div>
</div>

### isInternal() {#a24f8339d96c4b97a11d8b65e5b2c9d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isInternal ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffaafbf0897a5a83fdd873dfb032ec695d3">llvm::MachO::Internal</a> and <a href="#ac617292ffd14e2658362629e552ac3a8">Linkage</a>.</p>

</div>
</div>

### isRexported() {#ac34f3ecda3a5a0214766f86130930f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isRexported ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="#ac617292ffd14e2658362629e552ac3a8">Linkage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffa6994917dfcfb9ef55fc6bce4b454f9a4">llvm::MachO::Rexported</a>.</p>

</div>
</div>

### isText() {#afe12f8f753ee1908c244c2ec5daf0f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isText ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="#afaaf6d0b389985f5d39ae6cbb6bb3968">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a9dffbf69ffba8bc38bc4e01abf4b1675">llvm::MachO::Text</a>.</p>

</div>
</div>

### isThreadLocalValue() {#a2f46eeca206af39f6539258e31e33d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isThreadLocalValue ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="#afaaf6d0b389985f5d39ae6cbb6bb3968">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a4514e0ecc0bca43f5fa805abf7d7f1da">llvm::MachO::ThreadLocalValue</a>.</p>

</div>
</div>

### isUndefined() {#a172b785813d0cf80daf3936777ced74a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isUndefined ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="#ac617292ffd14e2658362629e552ac3a8">Linkage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ffaec0fc0100c4fc1ce4eea230c3dc10360">llvm::MachO::Undefined</a>.</p>

</div>
</div>

### isVerified() {#a6da118e468e332e780b403591881e52b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isVerified ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Reference <a href="#aebe5fc0e2c20106f21c45b212e9026d5">Verified</a>.</p>

</div>
</div>

### isWeakDefined() {#a8a2faaddd759c2c6aad86466b697354a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isWeakDefined ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="#afaaf6d0b389985f5d39ae6cbb6bb3968">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a97a89195303306e8a5bacadf960312a9">llvm::MachO::WeakDefined</a>.</p>

</div>
</div>

### isWeakReferenced() {#aef3f7c6f7b11a738c421391707a88ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::isWeakReferenced ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>References <a href="#afaaf6d0b389985f5d39ae6cbb6bb3968">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4a7c73b1797e3f46eb2dcb9d8d2d75805b">llvm::MachO::WeakReferenced</a>.</p>

</div>
</div>

### setVerify() {#ad35cd698765763e43ab57a81c803f0fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::Record::setVerify (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Reference <a href="#aebe5fc0e2c20106f21c45b212e9026d5">Verified</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### mergeFlags() {#a693fd723e699552c81b2751391a872ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolFlags Record::mergeFlags (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#abf69d7d02356968b4f36bc37bcbfe5b4">SymbolFlags</a> Flags, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a234dd862de758d2c88dc4876656cf8ff">RecordLinkage</a> Linkage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/recordsslice-cpp">RecordsSlice.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Flags {#afaaf6d0b389985f5d39ae6cbb6bb3968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolFlags llvm::MachO::Record::Flags</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#a671acbd063953da6403ccbd2fa35c349">getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#a0e224eeea061497db8c1de4e465bebb6">llvm::MachO::GlobalRecord::GlobalRecord</a>, <a href="#a986ed20ca0aa9ba9b7cb690fe57e75cc">isData</a>, <a href="#afe12f8f753ee1908c244c2ec5daf0f36">isText</a>, <a href="#a2f46eeca206af39f6539258e31e33d4c">isThreadLocalValue</a>, <a href="#a8a2faaddd759c2c6aad86466b697354a">isWeakDefined</a>, <a href="#aef3f7c6f7b11a738c421391707a88ef7">isWeakReferenced</a> and <a href="#a63a829b3d0e548c498383702df2368b7">Record</a>.</p>

</div>
</div>

### Linkage {#ac617292ffd14e2658362629e552ac3a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordLinkage llvm::MachO::Record::Linkage</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#a85376daae5640f771d4da0beeac835e9">llvm::MachO::ObjCContainerRecord::addObjCIVar</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#ab2e6927d7418fa3873dd778f5db6dd2b">llvm::MachO::ObjCContainerRecord::getLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#a0e224eeea061497db8c1de4e465bebb6">llvm::MachO::GlobalRecord::GlobalRecord</a>, <a href="#ad0d8c8eb5e266ee7fe20838b3d4dd920">isExported</a>, <a href="#a24f8339d96c4b97a11d8b65e5b2c9d77">isInternal</a>, <a href="#ac34f3ecda3a5a0214766f86130930f1d">isRexported</a>, <a href="#a172b785813d0cf80daf3936777ced74a">isUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#a97c5d891019f0f22072bf593df1545c0">llvm::MachO::ObjCContainerRecord::ObjCContainerRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord/#a1befb918686e43e4e912988cdecf2dcb">llvm::MachO::ObjCInterfaceRecord::ObjCInterfaceRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord/#a48af4fe3e956ac6c22704700e64d0941">llvm::MachO::ObjCIVarRecord::ObjCIVarRecord</a>, <a href="#a63a829b3d0e548c498383702df2368b7">Record</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord/#a7b7e231ea214423c70c04c3e7ef46237">llvm::MachO::ObjCInterfaceRecord::updateLinkageForSymbols</a>.</p>

</div>
</div>

### Name {#ae1da3190ebbff030b4f205be49606ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachO::Record::Name</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord/#a6fa88d10d21b4df676199e49177e4b88">llvm::MachO::ObjCInterfaceRecord::addObjCCategory</a>, <a href="#a275e8a5b9303c59fe00b7eecd1066f6b">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/globalrecord/#a0e224eeea061497db8c1de4e465bebb6">llvm::MachO::GlobalRecord::GlobalRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objccategoryrecord/#aaca0ca74b7c3089e4c81252e8b4d75c8">llvm::MachO::ObjCCategoryRecord::ObjCCategoryRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objccontainerrecord/#a97c5d891019f0f22072bf593df1545c0">llvm::MachO::ObjCContainerRecord::ObjCContainerRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objcinterfacerecord/#a1befb918686e43e4e912988cdecf2dcb">llvm::MachO::ObjCInterfaceRecord::ObjCInterfaceRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/objcivarrecord/#a48af4fe3e956ac6c22704700e64d0941">llvm::MachO::ObjCIVarRecord::ObjCIVarRecord</a> and <a href="#a63a829b3d0e548c498383702df2368b7">Record</a>.</p>

</div>
</div>

### Verified {#aebe5fc0e2c20106f21c45b212e9026d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::Record::Verified</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#a6da118e468e332e780b403591881e52b">isVerified</a>, <a href="#a63a829b3d0e548c498383702df2368b7">Record</a> and <a href="#ad35cd698765763e43ab57a81c803f0fd">setVerify</a>.</p>

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
