---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/recordsentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RecordsEntry` Struct

<p><a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a> - Holds exactly one of a <a href="/web-llvm/docs/api/classes/llvm/record">Record</a>, <a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a>, or AssertionInfo. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RecordsEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TableGen/TGParser.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04f9bddc4be021deed958ca601d32b99">RecordsEntry</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0718a1736f1c23c8a03a2f8ae84eac9">RecordsEntry</a> (std::unique_ptr&lt; Record &gt; Rec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746b28681d6f50987fc33dcfe5d4b144">RecordsEntry</a> (std::unique_ptr&lt; ForeachLoop &gt; Loop)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeba6e96e2029cb848b8dff9e84c99eb">RecordsEntry</a> (std::unique_ptr&lt; Record::AssertionInfo &gt; Assertion)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a129f9ce7fbaf0b23389411187caa8a55">RecordsEntry</a> (std::unique_ptr&lt; Record::DumpInfo &gt; Dump)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b468e7c34a791c89904af7cc6325c2c">dump</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebee1c9bb9751a980883759cf8198154">Rec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77569fc8d274c91169bf1e9af483be78">Loop</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/record/assertioninfo">Record::AssertionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86ab3776ab3242644dadb2a90f80843e">Assertion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/record/dumpinfo">Record::DumpInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1dd81bff474746b63a1338d8b3976e8">Dump</a></td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/recordsentry">RecordsEntry</a> - Holds exactly one of a <a href="/web-llvm/docs/api/classes/llvm/record">Record</a>, <a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a>, or AssertionInfo.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RecordsEntry() {#a04f9bddc4be021deed958ca601d32b99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RecordsEntry::RecordsEntry ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>

</div>
</div>

### RecordsEntry() {#ad0718a1736f1c23c8a03a2f8ae84eac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RecordsEntry::RecordsEntry (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> &gt; Rec)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#aebee1c9bb9751a980883759cf8198154">Rec</a>.</p>

</div>
</div>

### RecordsEntry() {#a746b28681d6f50987fc33dcfe5d4b144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RecordsEntry::RecordsEntry (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/foreachloop">ForeachLoop</a> &gt; Loop)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="#a77569fc8d274c91169bf1e9af483be78">Loop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### RecordsEntry() {#afeba6e96e2029cb848b8dff9e84c99eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RecordsEntry::RecordsEntry (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/record/assertioninfo">Record::AssertionInfo</a> &gt; Assertion)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="#a86ab3776ab3242644dadb2a90f80843e">Assertion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### RecordsEntry() {#a129f9ce7fbaf0b23389411187caa8a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RecordsEntry::RecordsEntry (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/record/dumpinfo">Record::DumpInfo</a> &gt; Dump)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>References <a href="#ac1dd81bff474746b63a1338d8b3976e8">Dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a8b468e7c34a791c89904af7cc6325c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RecordsEntry::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>, definition at line 4463 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="#a77569fc8d274c91169bf1e9af483be78">Loop</a> and <a href="#aebee1c9bb9751a980883759cf8198154">Rec</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Assertion {#a86ab3776ab3242644dadb2a90f80843e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Record::AssertionInfo&gt; llvm::RecordsEntry::Assertion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="#afeba6e96e2029cb848b8dff9e84c99eb">RecordsEntry</a>.</p>

</div>
</div>

### Dump {#ac1dd81bff474746b63a1338d8b3976e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Record::DumpInfo&gt; llvm::RecordsEntry::Dump</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="#a129f9ce7fbaf0b23389411187caa8a55">RecordsEntry</a>.</p>

</div>
</div>

### Loop {#a77569fc8d274c91169bf1e9af483be78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ForeachLoop&gt; llvm::RecordsEntry::Loop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="#a8b468e7c34a791c89904af7cc6325c2c">dump</a> and <a href="#a746b28681d6f50987fc33dcfe5d4b144">RecordsEntry</a>.</p>

</div>
</div>

### Rec {#aebee1c9bb9751a980883759cf8198154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Record&gt; llvm::RecordsEntry::Rec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>.</p>


<p>Referenced by <a href="#a8b468e7c34a791c89904af7cc6325c2c">dump</a> and <a href="#ad0718a1736f1c23c8a03a2f8ae84eac9">RecordsEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp">TGParser.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
