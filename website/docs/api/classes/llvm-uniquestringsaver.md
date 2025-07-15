---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/uniquestringsaver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UniqueStringSaver` Class Reference

<p>Saves strings in the provided stable storage and returns a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> with a stable character pointer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::UniqueStringSaver { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">llvm/Support/StringSaver.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c2d4981873c0d420f8a5a022767bdb">UniqueStringSaver</a> (BumpPtrAllocator &amp;Alloc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa37b5fdb34477a1eb3361f7ee9717f3">save</a> (const char *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d86fb475892004ac3de09ea43c1485">save</a> (StringRef S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1d26a0bd554591bd9d67412671c24dd">save</a> (const Twine &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9319bb0d86788ba24f2013dd572c42">save</a> (const std::string &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1c59977b3fca42a63c6f6f75e1d083">Strings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">llvm::DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae956e865a294853a265a0bc1e814f0b6">Unique</a></td>
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

<p>Saves strings in the provided stable storage and returns a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> with a stable character pointer.</p>


<p>Saving the same string yields the same <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>Compared to <a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a>, it does more work but avoids saving the same string multiple times.</p>


<p>Compared to <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/stringpool">StringPool</a>, it performs fewer allocations but doesn't support refcounting/deletion.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">StringSaver.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UniqueStringSaver() {#a00c2d4981873c0d420f8a5a022767bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::UniqueStringSaver::UniqueStringSaver (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">StringSaver.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### save() {#aaa37b5fdb34477a1eb3361f7ee9717f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::UniqueStringSaver::save (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * S)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">StringSaver.h</a>.</p>


<p>Reference <a href="#aaa37b5fdb34477a1eb3361f7ee9717f3">save</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxregisterinfo/#a11f68a471f467af9babb2ba236bcf1d9">llvm::NVPTXRegisterInfo::getName</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-229898081ab1ae62ec808414e8cc9435/#a10ab4f820b351ea57b6fa5079aef8042">llvm::yaml::MappingTraits&lt; ModuleSummaryIndex &gt;::mapping</a>, <a href="#aaa37b5fdb34477a1eb3361f7ee9717f3">save</a>, <a href="#ab1d26a0bd554591bd9d67412671c24dd">save</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aff8740863a5ee2650339400236b6224b">llvm::GlobalValue::setPartition</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a959c99adbdc7f8375cf866916c6b60f2">llvm::GlobalObject::setSection</a>.</p>

</div>
</div>

### save() {#a92d86fb475892004ac3de09ea43c1485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef UniqueStringSaver::save (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">StringSaver.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringsaver-cpp">StringSaver.cpp</a>.</p>

</div>
</div>

### save() {#ab1d26a0bd554591bd9d67412671c24dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef UniqueStringSaver::save (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">StringSaver.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringsaver-cpp">StringSaver.cpp</a>.</p>


<p>References <a href="#aaa37b5fdb34477a1eb3361f7ee9717f3">save</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ac521760e9a45f304a4cbe46ed4fff845">llvm::Twine::toStringRef</a>.</p>

</div>
</div>

### save() {#a4c9319bb0d86788ba24f2013dd572c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::UniqueStringSaver::save (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; S)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">StringSaver.h</a>.</p>


<p>Reference <a href="#a4c9319bb0d86788ba24f2013dd572c42">save</a>.</p>


<p>Referenced by <a href="#a4c9319bb0d86788ba24f2013dd572c42">save</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Strings {#a4a1c59977b3fca42a63c6f6f75e1d083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSaver llvm::UniqueStringSaver::Strings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">StringSaver.h</a>.</p>

</div>
</div>

### Unique {#ae956e865a294853a265a0bc1e814f0b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenseSet&lt;llvm::StringRef&gt; llvm::UniqueStringSaver::Unique</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">StringSaver.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">StringSaver.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/stringsaver-cpp">StringSaver.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
