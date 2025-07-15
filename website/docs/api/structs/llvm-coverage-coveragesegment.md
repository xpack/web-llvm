---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/coverage/coveragesegment
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CoverageSegment` Struct Reference

<p>The execution count information starting at a point in a file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::coverage::CoverageSegment { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">llvm/ProfileData/Coverage/CoverageMapping.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835140dc443783f083fe32dfb8693af0">operator==</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048c0b739395f48c23ed43a5a8725569">CoverageSegment</a> (unsigned Line, unsigned Col, bool IsRegionEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f5383042b75067f97e1ca42e89df98e">CoverageSegment</a> (unsigned Line, unsigned Col, uint64_t Count, bool IsRegionEntry, bool IsGapRegion=false, bool IsBranchRegion=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dba8c4bdd89f6ad3c70c1a326ed7c9a">Line</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The line where this segment begins. <a href="#a8dba8c4bdd89f6ad3c70c1a326ed7c9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a553303ac03c9e71d4d791f8007cd6d5b">Col</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The column where this segment begins. <a href="#a553303ac03c9e71d4d791f8007cd6d5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8674dd0786fdaeaa1b981e244927687a">Count</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The execution count, or zero if no count was recorded. <a href="#a8674dd0786fdaeaa1b981e244927687a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd16fbd5d317d00fea6242ce082ae41">HasCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When false, the segment was uninstrumented or skipped. <a href="#a3fd16fbd5d317d00fea6242ce082ae41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ead9925ccadb2ba2386f68f69ba0d1">IsRegionEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this enters a new region or returns to a previous count. <a href="#a83ead9925ccadb2ba2386f68f69ba0d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd3d929497ff2d88b67c0638464aaca">IsGapRegion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this enters a gap region. <a href="#abcd3d929497ff2d88b67c0638464aaca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The execution count information starting at a point in a file.</p>


<p>A sequence of CoverageSegments gives execution counts for a file in format that's simple to iterate through for processing.</p>


<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator== {#a835140dc443783f083fe32dfb8693af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/coveragesegment">CoverageSegment</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/coveragesegment">CoverageSegment</a> &amp; R</td>
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


<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Reference <a href="#a048c0b739395f48c23ed43a5a8725569">CoverageSegment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CoverageSegment() {#a048c0b739395f48c23ed43a5a8725569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CoverageSegment::CoverageSegment (unsigned Line, unsigned Col, bool IsRegionEntry)</td>
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



<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a553303ac03c9e71d4d791f8007cd6d5b">Col</a>, <a href="#a8674dd0786fdaeaa1b981e244927687a">Count</a>, <a href="#a3fd16fbd5d317d00fea6242ce082ae41">HasCount</a>, <a href="#abcd3d929497ff2d88b67c0638464aaca">IsGapRegion</a>, <a href="#a83ead9925ccadb2ba2386f68f69ba0d1">IsRegionEntry</a> and <a href="#a8dba8c4bdd89f6ad3c70c1a326ed7c9a">Line</a>.</p>


<p>Referenced by <a href="#a835140dc443783f083fe32dfb8693af0">operator==</a>.</p>

</div>
</div>

### CoverageSegment() {#a9f5383042b75067f97e1ca42e89df98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CoverageSegment::CoverageSegment (unsigned Line, unsigned Col, uint64_t Count, bool IsRegionEntry, bool IsGapRegion=false, bool IsBranchRegion=false)</td>
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



<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a553303ac03c9e71d4d791f8007cd6d5b">Col</a>, <a href="#a8674dd0786fdaeaa1b981e244927687a">Count</a>, <a href="#a3fd16fbd5d317d00fea6242ce082ae41">HasCount</a>, <a href="#abcd3d929497ff2d88b67c0638464aaca">IsGapRegion</a>, <a href="#a83ead9925ccadb2ba2386f68f69ba0d1">IsRegionEntry</a>, <a href="#a8dba8c4bdd89f6ad3c70c1a326ed7c9a">Line</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Col {#a553303ac03c9e71d4d791f8007cd6d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::coverage::CoverageSegment::Col</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The column where this segment begins.</p>

<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a048c0b739395f48c23ed43a5a8725569">CoverageSegment</a> and <a href="#a9f5383042b75067f97e1ca42e89df98e">CoverageSegment</a>.</p>

</div>
</div>

### Count {#a8674dd0786fdaeaa1b981e244927687a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::CoverageSegment::Count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The execution count, or zero if no count was recorded.</p>

<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a048c0b739395f48c23ed43a5a8725569">CoverageSegment</a> and <a href="#a9f5383042b75067f97e1ca42e89df98e">CoverageSegment</a>.</p>

</div>
</div>

### HasCount {#a3fd16fbd5d317d00fea6242ce082ae41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::coverage::CoverageSegment::HasCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When false, the segment was uninstrumented or skipped.</p>

<p>Definition at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a048c0b739395f48c23ed43a5a8725569">CoverageSegment</a> and <a href="#a9f5383042b75067f97e1ca42e89df98e">CoverageSegment</a>.</p>

</div>
</div>

### IsGapRegion {#abcd3d929497ff2d88b67c0638464aaca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::coverage::CoverageSegment::IsGapRegion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this enters a gap region.</p>

<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a048c0b739395f48c23ed43a5a8725569">CoverageSegment</a> and <a href="#a9f5383042b75067f97e1ca42e89df98e">CoverageSegment</a>.</p>

</div>
</div>

### IsRegionEntry {#a83ead9925ccadb2ba2386f68f69ba0d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::coverage::CoverageSegment::IsRegionEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this enters a new region or returns to a previous count.</p>

<p>Definition at line 848 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a048c0b739395f48c23ed43a5a8725569">CoverageSegment</a> and <a href="#a9f5383042b75067f97e1ca42e89df98e">CoverageSegment</a>.</p>

</div>
</div>

### Line {#a8dba8c4bdd89f6ad3c70c1a326ed7c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::coverage::CoverageSegment::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The line where this segment begins.</p>

<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#a048c0b739395f48c23ed43a5a8725569">CoverageSegment</a> and <a href="#a9f5383042b75067f97e1ca42e89df98e">CoverageSegment</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
