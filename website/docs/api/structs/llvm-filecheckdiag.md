---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/filecheckdiag
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FileCheckDiag` Struct

<p>Summary of a <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> diagnostic. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::FileCheckDiag { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">llvm/FileCheck/FileCheck.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MatchType { <a href="#ab33e9e639814daad35bb1a9dc84190c0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>What type of match result does this diagnostic describe? <a href="#ab33e9e639814daad35bb1a9dc84190c0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b7d723c27bc645be803cb48a7f103f">FileCheckDiag</a> (const SourceMgr &amp;SM, const Check::FileCheckType &amp;CheckTy, SMLoc CheckLoc, MatchType MatchTy, SMRange InputRange, StringRef Note="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">Check::FileCheckType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86901e0196062903763ea40e149ae363">CheckTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>What is the <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> directive for this diagnostic? <a href="#a86901e0196062903763ea40e149ae363">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70d45da9cefd23e5f10aac0bf27b64b">CheckLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Where is the <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> directive for this diagnostic? <a href="#af70d45da9cefd23e5f10aac0bf27b64b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#ab33e9e639814daad35bb1a9dc84190c0">llvm::FileCheckDiag::MatchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da50048c6a2c815f6e4219f9c259386">MatchTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2ffb9989d232f1741d82d11901ee55">InputStartLine</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The search range if MatchTy starts with MatchNone, or the match range otherwise. <a href="#a3e2ffb9989d232f1741d82d11901ee55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2598d8229c3e2065b3ec2b99958876a4">InputStartCol</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a431375a72a3d181911379890869b6bf6">InputEndLine</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9be546d093e6ba646781b3947c7eceec">InputEndCol</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c0c1239a8b44a6ec3c83e9951c64af">Note</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A note to replace the one normally indicated by MatchTy, or the empty string if none. <a href="#a02c0c1239a8b44a6ec3c83e9951c64af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Summary of a <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> diagnostic.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### MatchType {#ab33e9e639814daad35bb1a9dc84190c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::FileCheckDiag::MatchType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>What type of match result does this diagnostic describe?</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchFoundAndExpected<a id="ab33e9e639814daad35bb1a9dc84190c0adcf3e4ffa0433fb40711377d53b4baf1"></a></td>
<td class="doxyEnumItemDescription">Indicates a good match for an expected pattern</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchFoundButExcluded<a id="ab33e9e639814daad35bb1a9dc84190c0a66b95270a54c88af1ba70b794aa836f8"></a></td>
<td class="doxyEnumItemDescription">Indicates a match for an excluded pattern</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchFoundButWrongLine<a id="ab33e9e639814daad35bb1a9dc84190c0a3f5c9c6115db2361e358de0c62d43bed"></a></td>
<td class="doxyEnumItemDescription">Indicates a match for an expected pattern, but the match is on the wrong line</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchFoundButDiscarded<a id="ab33e9e639814daad35bb1a9dc84190c0abf168517cbdcc053154c47b20986837b"></a></td>
<td class="doxyEnumItemDescription">Indicates a discarded match for an expected pattern</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchFoundErrorNote<a id="ab33e9e639814daad35bb1a9dc84190c0ab7e91555667e7182c229428b8f3a6302"></a></td>
<td class="doxyEnumItemDescription">Indicates an error while processing a match after the match was found for an expected or excluded pattern</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchNoneAndExcluded<a id="ab33e9e639814daad35bb1a9dc84190c0a4a92716c994d8a58dc2e6b158e2b2f3f"></a></td>
<td class="doxyEnumItemDescription">Indicates no match for an excluded pattern</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchNoneButExpected<a id="ab33e9e639814daad35bb1a9dc84190c0afc543db8ad6f068fab3eea06297e0ebc"></a></td>
<td class="doxyEnumItemDescription">Indicates no match for an expected pattern, but this might follow good matches when multiple matches are expected for the pattern, or it might follow discarded matches for the pattern</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchNoneForInvalidPattern<a id="ab33e9e639814daad35bb1a9dc84190c0ad139fc8ba0eace914c3d91f8c51c35b1"></a></td>
<td class="doxyEnumItemDescription">Indicates no match due to an expected or excluded pattern that has proven to be invalid at match time</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MatchFuzzy<a id="ab33e9e639814daad35bb1a9dc84190c0a6c8cff7a0ac871bde6a0e4e33a8e90d2"></a></td>
<td class="doxyEnumItemDescription">Indicates a fuzzy match that serves as a suggestion for the next intended match for an expected pattern with too few or no good matches</td>
</tr>

</table>
</dd>
</dl>


<p>A directive's supplied pattern is said to be either expected or excluded depending on whether the pattern must have or must not have a match in order for the directive to succeed. For example, a CHECK directive's pattern is expected, and a CHECK-NOT directive's pattern is excluded.</p>


<p>There might be more than one match result for a single pattern. For example, there might be several discarded matches (MatchFoundButDiscarded) before either a good match (MatchFoundAndExpected) or a failure to match (MatchNoneButExpected), and there might be a fuzzy match (MatchFuzzy) after the latter.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FileCheckDiag() {#a61b7d723c27bc645be803cb48a7f103f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCheckDiag::FileCheckDiag (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/check/filechecktype">Check::FileCheckType</a> &amp; CheckTy, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> CheckLoc, <a href="#ab33e9e639814daad35bb1a9dc84190c0">MatchType</a> MatchTy, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> InputRange, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Note="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>, definition at line 1457 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="#af70d45da9cefd23e5f10aac0bf27b64b">CheckLoc</a>, <a href="#a86901e0196062903763ea40e149ae363">CheckTy</a>, <a href="/web-llvm/docs/api/classes/llvm/smrange/#a971f74faff26ef837fb42b7b4b6e3066">llvm::SMRange::End</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a494d75fe0bc43f9c6b8821f983205649">llvm::SourceMgr::getLineAndColumn</a>, <a href="#a9be546d093e6ba646781b3947c7eceec">InputEndCol</a>, <a href="#a431375a72a3d181911379890869b6bf6">InputEndLine</a>, <a href="#a2598d8229c3e2065b3ec2b99958876a4">InputStartCol</a>, <a href="#a3e2ffb9989d232f1741d82d11901ee55">InputStartLine</a>, <a href="#a2da50048c6a2c815f6e4219f9c259386">MatchTy</a>, <a href="#a02c0c1239a8b44a6ec3c83e9951c64af">Note</a> and <a href="/web-llvm/docs/api/classes/llvm/smrange/#a95721f80bb5e9cfa8571695f8807881b">llvm::SMRange::Start</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CheckLoc {#af70d45da9cefd23e5f10aac0bf27b64b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::FileCheckDiag::CheckLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Where is the <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> directive for this diagnostic?</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Referenced by <a href="#a61b7d723c27bc645be803cb48a7f103f">FileCheckDiag</a>.</p>

</div>
</div>

### CheckTy {#a86901e0196062903763ea40e149ae363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Check::FileCheckType llvm::FileCheckDiag::CheckTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>What is the <a href="/web-llvm/docs/api/classes/llvm/filecheck">FileCheck</a> directive for this diagnostic?</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Referenced by <a href="#a61b7d723c27bc645be803cb48a7f103f">FileCheckDiag</a>.</p>

</div>
</div>

### InputEndCol {#a9be546d093e6ba646781b3947c7eceec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FileCheckDiag::InputEndCol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Referenced by <a href="#a61b7d723c27bc645be803cb48a7f103f">FileCheckDiag</a>.</p>

</div>
</div>

### InputEndLine {#a431375a72a3d181911379890869b6bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FileCheckDiag::InputEndLine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Referenced by <a href="#a61b7d723c27bc645be803cb48a7f103f">FileCheckDiag</a>.</p>

</div>
</div>

### InputStartCol {#a2598d8229c3e2065b3ec2b99958876a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FileCheckDiag::InputStartCol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Referenced by <a href="#a61b7d723c27bc645be803cb48a7f103f">FileCheckDiag</a>.</p>

</div>
</div>

### InputStartLine {#a3e2ffb9989d232f1741d82d11901ee55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FileCheckDiag::InputStartLine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The search range if MatchTy starts with MatchNone, or the match range otherwise.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Referenced by <a href="#a61b7d723c27bc645be803cb48a7f103f">FileCheckDiag</a>.</p>

</div>
</div>

### MatchTy {#a2da50048c6a2c815f6e4219f9c259386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::FileCheckDiag::MatchType llvm::FileCheckDiag::MatchTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Referenced by <a href="#a61b7d723c27bc645be803cb48a7f103f">FileCheckDiag</a>.</p>

</div>
</div>

### Note {#a02c0c1239a8b44a6ec3c83e9951c64af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::FileCheckDiag::Note</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A note to replace the one normally indicated by MatchTy, or the empty string if none.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a>.</p>


<p>Referenced by <a href="#a61b7d723c27bc645be803cb48a7f103f">FileCheckDiag</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/filecheck/filecheck-h">FileCheck.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
