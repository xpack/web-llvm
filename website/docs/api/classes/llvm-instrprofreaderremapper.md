---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instrprofreaderremapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstrProfReaderRemapper` Class

<p>Name matcher supporting fuzzy matching of symbol names to names in profiles. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InstrProfReaderRemapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">llvm/ProfileData/InstrProfReader.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrprofreader-cpp-/instrprofreadernullremapper">InstrProfReaderNullRemapper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A remapper that does not apply any remappings. <a href="/web-llvm/docs/api/classes/anonymous-instrprofreader-cpp-/instrprofreadernullremapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper">InstrProfReaderItaniumRemapper&lt;HashTableImpl&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A remapper that applies remappings based on a symbol remapping file. <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd290f55b99643c4b2c0b5521b87f382">~InstrProfReaderRemapper</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed1ba031efeafd752d0336dba6d5de00">populateRemappings</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91de395f007322d92feedb65f73ee68d">getRecords</a> (StringRef FuncName, ArrayRef&lt; NamedInstrProfRecord &gt; &amp;Data)=0</td>
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

<p>Name matcher supporting fuzzy matching of symbol names to names in profiles.</p>

<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~InstrProfReaderRemapper() {#acd290f55b99643c4b2c0b5521b87f382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::InstrProfReaderRemapper::~InstrProfReaderRemapper ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRecords() {#a91de395f007322d92feedb65f73ee68d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::InstrProfReaderRemapper::getRecords (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/namedinstrprofrecord">NamedInstrProfRecord</a> &gt; &amp; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>

</div>
</div>

### populateRemappings() {#aed1ba031efeafd752d0336dba6d5de00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::InstrProfReaderRemapper::populateRemappings ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprofreader-h">InstrProfReader.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
