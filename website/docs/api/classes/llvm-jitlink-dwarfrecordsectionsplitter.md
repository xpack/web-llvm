---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/dwarfrecordsectionsplitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFRecordSectionSplitter` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> pass that splits blocks in a section that follows the DWARF <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> format into sub-blocks where each header gets its own block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::DWARFRecordSectionSplitter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/dwarfrecordsectionsplitter-h">llvm/ExecutionEngine/JITLink/DWARFRecordSectionSplitter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6152127d7c9f06400bbfdb9556678ad2">DWARFRecordSectionSplitter</a> (StringRef SectionName)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f2000bb8938fc279ffdff87d8136807">operator()</a> (LinkGraph &amp;G)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb3e3c1a61e77d3f30c3cd512380b1a4">processBlock</a> (LinkGraph &amp;G, Block &amp;B, LinkGraph::SplitBlockCache &amp;Cache)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe49fb3bcfe0f66155ccbdb0a55cb83e">SectionName</a></td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> pass that splits blocks in a section that follows the DWARF <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> format into sub-blocks where each header gets its own block.</p>


<p>When splitting EHFrames, <a href="/web-llvm/docs/api/classes/llvm/jitlink/dwarfrecordsectionsplitter">DWARFRecordSectionSplitter</a> should not be run without <a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframeedgefixer">EHFrameEdgeFixer</a>, which is responsible for adding FDE-to-CIE edges.</p>


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/dwarfrecordsectionsplitter-h">DWARFRecordSectionSplitter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFRecordSectionSplitter() {#a6152127d7c9f06400bbfdb9556678ad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::DWARFRecordSectionSplitter::DWARFRecordSectionSplitter (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/dwarfrecordsectionsplitter-h">DWARFRecordSectionSplitter.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/dwarfrecordsectionsplitter-cpp">DWARFRecordSectionSplitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a9f2000bb8938fc279ffdff87d8136807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::DWARFRecordSectionSplitter::operator() (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/dwarfrecordsectionsplitter-h">DWARFRecordSectionSplitter.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/dwarfrecordsectionsplitter-cpp">DWARFRecordSectionSplitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section/#a739ec54340b0cfa98110fc0ab250852c">llvm::jitlink::Section::blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/section/#a028aa065623fa3f89610548040ad0bfa">llvm::jitlink::Section::symbols</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### processBlock() {#aeb3e3c1a61e77d3f30c3cd512380b1a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::DWARFRecordSectionSplitter::processBlock (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#afc87be5343187a4cef74ac1a22d4a2b2">LinkGraph::SplitBlockCache</a> &amp; Cache)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/dwarfrecordsectionsplitter-h">DWARFRecordSectionSplitter.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/dwarfrecordsectionsplitter-cpp">DWARFRecordSectionSplitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SectionName {#afe49fb3bcfe0f66155ccbdb0a55cb83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::jitlink::DWARFRecordSectionSplitter::SectionName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/dwarfrecordsectionsplitter-h">DWARFRecordSectionSplitter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/dwarfrecordsectionsplitter-h">DWARFRecordSectionSplitter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/dwarfrecordsectionsplitter-cpp">DWARFRecordSectionSplitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
