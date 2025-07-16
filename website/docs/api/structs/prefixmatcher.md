---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/prefixmatcher
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PrefixMatcher` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct PrefixMatcher { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d4f7a82f0d45796979a17a39fe7cfc">PrefixMatcher</a> (ArrayRef&lt; StringRef &gt; CheckPrefixes, ArrayRef&lt; StringRef &gt; CommentPrefixes, StringRef Input)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d7229c302f7f9a6e42ad1afdc957c9">match</a> (StringRef Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the next match of a prefix in Buffer. <a href="#a06d7229c302f7f9a6e42ad1afdc957c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, size_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a538f395992810f714b41a6a8b937211c">Prefixes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prefixes and their first occurrence past the current position. <a href="#a538f395992810f714b41a6a8b937211c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a37964705b058d38f423a47c96f703">Input</a></td>
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


<p>Definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PrefixMatcher() {#ac9d4f7a82f0d45796979a17a39fe7cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PrefixMatcher::PrefixMatcher (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; CheckPrefixes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; CommentPrefixes, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Input)</td>
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



<p>Definition at line 1658 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>, <a href="#a32a37964705b058d38f423a47c96f703">Input</a>, <a href="#a538f395992810f714b41a6a8b937211c">Prefixes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### match() {#a06d7229c302f7f9a6e42ad1afdc957c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef PrefixMatcher::match (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer)</td>
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

<p>Find the next match of a prefix in Buffer.</p>


<p>Returns empty <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> if not found.</p>


<p>Definition at line 1673 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="#a32a37964705b058d38f423a47c96f703">Input</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>, <a href="#a538f395992810f714b41a6a8b937211c">Prefixes</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Input {#a32a37964705b058d38f423a47c96f703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef PrefixMatcher::Input</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1656 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Referenced by <a href="#a06d7229c302f7f9a6e42ad1afdc957c9">match</a> and <a href="#ac9d4f7a82f0d45796979a17a39fe7cfc">PrefixMatcher</a>.</p>

</div>
</div>

### Prefixes {#a538f395992810f714b41a6a8b937211c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;StringRef, size_t&gt; &gt; PrefixMatcher::Prefixes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prefixes and their first occurrence past the current position.</p>

<p>Definition at line 1655 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>Referenced by <a href="#a06d7229c302f7f9a6e42ad1afdc957c9">match</a> and <a href="#ac9d4f7a82f0d45796979a17a39fe7cfc">PrefixMatcher</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
