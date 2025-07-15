---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/filecollector/pathcanonicalizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PathCanonicalizer` Class Reference

<p>Helper utility that encapsulates the logic for canonicalizing a virtual path and a path to copy from. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FileCollector::PathCanonicalizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">llvm/Support/FileCollector.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/filecollector/pathcanonicalizer/pathstorage">PathStorage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac656bc9e1653748650e52573708cdf20">canonicalize</a> (StringRef SrcPath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonicalize a pair of virtual and real paths. <a href="#ac656bc9e1653748650e52573708cdf20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af61f735fca52ae4d0bc670910d1a88bb">updateWithRealPath</a> (SmallVectorImpl&lt; char &gt; &amp;Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace with a (mostly) real path, or don't modify. <a href="#af61f735fca52ae4d0bc670910d1a88bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee7ddd42d9c6c4768d93067e39816c41">CachedDirs</a></td>
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

<p>Helper utility that encapsulates the logic for canonicalizing a virtual path and a path to copy from.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### canonicalize() {#ac656bc9e1653748650e52573708cdf20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCollector::PathCanonicalizer::PathStorage FileCollector::PathCanonicalizer::canonicalize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SrcPath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Canonicalize a pair of virtual and real paths.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp/#a20bab096e3719810afee546ab46997c3">makeAbsolute</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### updateWithRealPath() {#af61f735fca52ae4d0bc670910d1a88bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileCollector::PathCanonicalizer::updateWithRealPath (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace with a (mostly) real path, or don't modify.</p>


<p>Resolves symlinks in the directory, using <em>CachedDirs</em> to avoid redundant lookups, but leaves the filename as a possible symlink.</p>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CachedDirs {#aee7ddd42d9c6c4768d93067e39816c41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::string&gt; llvm::FileCollector::PathCanonicalizer::CachedDirs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
