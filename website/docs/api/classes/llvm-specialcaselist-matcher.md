---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/specialcaselist/matcher
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Matcher` Class

<p>Represents a set of globs and their line numbers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SpecialCaseList::Matcher { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">llvm/Support/SpecialCaseList.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeddf3282ade6b3f5d5bd98297ae8300a">insert</a> (StringRef Pattern, unsigned LineNumber, bool UseRegex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c112003d4b27780538553f72b0d7c0">match</a> (StringRef Query) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/globpattern">GlobPattern</a>, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f1a81bab8c7a1b33415bebad5a9d904">Globs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a> &gt;, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41662b43e15a55b4bf5b76108b30986d">RegExes</a></td>
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

<p>Represents a set of globs and their line numbers.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### insert() {#aeddf3282ade6b3f5d5bd98297ae8300a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::SpecialCaseList::Matcher::insert (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pattern, unsigned LineNumber, bool UseRegex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globpattern/#ad853cb6a2e5807ae5006c0f5ba1e7b49">llvm::GlobPattern::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a8f1a81bab8c7a1b33415bebad5a9d904">Globs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#ab0ec0a13edce115b90710387e246519f">llvm::Regex::isValid</a>, <a href="#a41662b43e15a55b4bf5b76108b30986d">RegExes</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### match() {#a95c112003d4b27780538553f72b0d7c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SpecialCaseList::Matcher::match (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Query)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a>.</p>


<p>References <a href="#a8f1a81bab8c7a1b33415bebad5a9d904">Globs</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#ae787b71e8d775a2b662d04e913489d8d">llvm::Regex::match</a> and <a href="#a41662b43e15a55b4bf5b76108b30986d">RegExes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Globs {#a8f1a81bab8c7a1b33415bebad5a9d904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::pair&lt;GlobPattern, unsigned&gt; &gt; llvm::SpecialCaseList::Matcher::Globs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>


<p>Referenced by <a href="#aeddf3282ade6b3f5d5bd98297ae8300a">insert</a> and <a href="#a95c112003d4b27780538553f72b0d7c0">match</a>.</p>

</div>
</div>

### RegExes {#a41662b43e15a55b4bf5b76108b30986d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;std::unique_ptr&lt;Regex&gt;, unsigned&gt; &gt; llvm::SpecialCaseList::Matcher::RegExes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a>.</p>


<p>Referenced by <a href="#aeddf3282ade6b3f5d5bd98297ae8300a">insert</a> and <a href="#a95c112003d4b27780538553f72b0d7c0">match</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">SpecialCaseList.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/specialcaselist-cpp">SpecialCaseList.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
