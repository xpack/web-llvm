---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/memprof/memprofrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MemProfRecord` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::memprof::MemProfRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">llvm/ProfileData/MemProf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3ed98e45283cea7a8ff1ae1d3b5915d">MemProfRecord</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5a539ee058b256071c731b50c18c2ca">print</a> (llvm::raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/memprof/allocationinfo">AllocationInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa477c9cea78a2286c0cfd54e36d2a15c">AllocSites</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/memprof/frame">Frame</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f7d5c18fd9744bf7d7f6181117c98f">CallSites</a></td>
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


<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemProfRecord() {#ac3ed98e45283cea7a8ff1ae1d3b5915d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::MemProfRecord::MemProfRecord ()</td>
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



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### print() {#aa5a539ee058b256071c731b50c18c2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::MemProfRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>References <a href="#aa477c9cea78a2286c0cfd54e36d2a15c">AllocSites</a>, <a href="#a33f7d5c18fd9744bf7d7f6181117c98f">CallSites</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllocSites {#aa477c9cea78a2286c0cfd54e36d2a15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;AllocationInfo&gt; llvm::memprof::MemProfRecord::AllocSites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ea7d45673a77363a3aeaba941797ff7e/#ae2e2ca8721dda0f1ee80a5811b55c326">llvm::yaml::MappingTraits&lt; memprof::GUIDMemProfRecordPair &gt;::mapping</a>, <a href="#aa5a539ee058b256071c731b50c18c2ca">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a58aa2ef50612b9678712ee8355036025">undriftMemProfRecord</a>.</p>

</div>
</div>

### CallSites {#a33f7d5c18fd9744bf7d7f6181117c98f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;std::vector&lt;Frame&gt; &gt; llvm::memprof::MemProfRecord::CallSites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ea7d45673a77363a3aeaba941797ff7e/#ae2e2ca8721dda0f1ee80a5811b55c326">llvm::yaml::MappingTraits&lt; memprof::GUIDMemProfRecordPair &gt;::mapping</a>, <a href="#aa5a539ee058b256071c731b50c18c2ca">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a58aa2ef50612b9678712ee8355036025">undriftMemProfRecord</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">MemProf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
