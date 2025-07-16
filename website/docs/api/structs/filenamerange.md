---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/filenamerange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FilenameRange` Struct Reference

<p>A range of filename indices. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct FilenameRange { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b42b9cdef947587aca5d033dd7f94b0">FilenameRange</a> (unsigned StartingIndex, unsigned Length)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a47c0a9dcaef4e805c51df3d33920c">markInvalid</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b81ea49054f4d59b76e9627240b13a">isInvalid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26e5dea7580e45a5d1c881aa92f93972">StartingIndex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37475eae00e558a1d7ebc8c116234fc4">Length</a></td>
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

<p>A range of filename indices.</p>


<p>Used to specify the location of a batch of filenames in a vector-like container.</p>


<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FilenameRange() {#a3b42b9cdef947587aca5d033dd7f94b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FilenameRange::FilenameRange (unsigned StartingIndex, unsigned Length)</td>
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



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>References <a href="#a37475eae00e558a1d7ebc8c116234fc4">Length</a> and <a href="#a26e5dea7580e45a5d1c881aa92f93972">StartingIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isInvalid() {#a77b81ea49054f4d59b76e9627240b13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FilenameRange::isInvalid ()</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>Reference <a href="#a37475eae00e558a1d7ebc8c116234fc4">Length</a>.</p>

</div>
</div>

### markInvalid() {#a73a47c0a9dcaef4e805c51df3d33920c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FilenameRange::markInvalid ()</td>
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



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>Reference <a href="#a37475eae00e558a1d7ebc8c116234fc4">Length</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader/#a8c67cee70433798d45a0759d4fddad92">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readCoverageHeader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Length {#a37475eae00e558a1d7ebc8c116234fc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FilenameRange::Length</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>Referenced by <a href="#a3b42b9cdef947587aca5d033dd7f94b0">FilenameRange</a>, <a href="#a77b81ea49054f4d59b76e9627240b13a">isInvalid</a>, <a href="#a73a47c0a9dcaef4e805c51df3d33920c">markInvalid</a> and <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader/#a8c67cee70433798d45a0759d4fddad92">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readCoverageHeader</a>.</p>

</div>
</div>

### StartingIndex {#a26e5dea7580e45a5d1c881aa92f93972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FilenameRange::StartingIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a>.</p>


<p>Referenced by <a href="#a3b42b9cdef947587aca5d033dd7f94b0">FilenameRange</a> and <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader/#a8c67cee70433798d45a0759d4fddad92">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readCoverageHeader</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp">CoverageMappingReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
