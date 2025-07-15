---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coverage/functionrecorditerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FunctionRecordIterator` Class Reference

<p>Iterator over Functions, optionally filtered to a single file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::coverage::FunctionRecordIterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">llvm/ProfileData/Coverage/CoverageMapping.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-facade-base">iterator_facade_base&lt;DerivedT, IteratorCategoryT, T, DifferenceTypeT, PointerT, ReferenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP base class which implements the entire standard iterator facade in terms of a minimal subset of the interface. <a href="/web-llvm/docs/api/classes/llvm/iterator-facade-base/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72e5e423cf145f633dd0ee5a9694ddc">FunctionRecordIterator</a> (ArrayRef&lt; FunctionRecord &gt; Records_, StringRef Filename="", ArrayRef&lt; unsigned &gt; RecordIndices_={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af045297fa65a9cb9fc542f5b15c6b7d9">FunctionRecordIterator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ab6b8a5aeaca1ba5fdfbfdc4043914">operator==</a> (const FunctionRecordIterator &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/functionrecord">FunctionRecord</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9fb5622b6d292b68b5573d4a1e6d95e">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coverage/functionrecorditerator">FunctionRecordIterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac123c720178c9b5927b582296a6002bc">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a13719755155224e2660d5bb4c8d160">skipOtherFiles</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip records whose primary file is not <span class="doxyComputerOutput">Filename</span>. <a href="#a2a13719755155224e2660d5bb4c8d160">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04ad0a171e3ec958ee6a4222396ae876">advanceOne</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/functionrecord">FunctionRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72acb08019df559d34ff560f450861b">Records</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4342385aa9f86fb7731028a9297173ae">RecordIndices</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab971c5a3df4ae4ae524c7787e18d2fa8">CurrentIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/functionrecord">FunctionRecord</a> &gt;::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a856d273fb44236907a1bd65af342b0db">Current</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2725de7bc407b1435fdd81db2596be76">Filename</a></td>
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

<p>Iterator over Functions, optionally filtered to a single file.</p>


<p>When filtering to a single file, the iterator requires a list of potential indices where to find the desired records to avoid quadratic behavior when repeatedly iterating over functions from different files.</p>


<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionRecordIterator() {#aa72e5e423cf145f633dd0ee5a9694ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::FunctionRecordIterator::FunctionRecordIterator (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/functionrecord">FunctionRecord</a> &gt; Records_, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename="", <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; RecordIndices_={})</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Referenced by <a href="#ac123c720178c9b5927b582296a6002bc">operator++</a> and <a href="#ac7ab6b8a5aeaca1ba5fdfbfdc4043914">operator==</a>.</p>

</div>
</div>

### FunctionRecordIterator() {#af045297fa65a9cb9fc542f5b15c6b7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::FunctionRecordIterator::FunctionRecordIterator ()</td>
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



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#af9fb5622b6d292b68b5573d4a1e6d95e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionRecord &amp; llvm::coverage::FunctionRecordIterator::operator* ()</td>
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



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### operator++() {#ac123c720178c9b5927b582296a6002bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionRecordIterator &amp; llvm::coverage::FunctionRecordIterator::operator++ ()</td>
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



<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Reference <a href="#aa72e5e423cf145f633dd0ee5a9694ddc">FunctionRecordIterator</a>.</p>

</div>
</div>

### operator==() {#ac7ab6b8a5aeaca1ba5fdfbfdc4043914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::coverage::FunctionRecordIterator::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coverage/functionrecorditerator">FunctionRecordIterator</a> &amp; RHS)</td>
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



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#aa72e5e423cf145f633dd0ee5a9694ddc">FunctionRecordIterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### advanceOne() {#a04ad0a171e3ec958ee6a4222396ae876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::coverage::FunctionRecordIterator::advanceOne ()</td>
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



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### skipOtherFiles() {#a2a13719755155224e2660d5bb4c8d160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionRecordIterator::skipOtherFiles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Skip records whose primary file is not <span class="doxyComputerOutput">Filename</span>.</p>

<p>Declaration at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Current {#a856d273fb44236907a1bd65af342b0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;FunctionRecord&gt;::iterator llvm::coverage::FunctionRecordIterator::Current</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### CurrentIndex {#ab971c5a3df4ae4ae524c7787e18d2fa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;unsigned&gt;::iterator llvm::coverage::FunctionRecordIterator::CurrentIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Filename {#a2725de7bc407b1435fdd81db2596be76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::coverage::FunctionRecordIterator::Filename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### RecordIndices {#a4342385aa9f86fb7731028a9297173ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;unsigned&gt; llvm::coverage::FunctionRecordIterator::RecordIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Records {#af72acb08019df559d34ff560f450861b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;FunctionRecord&gt; llvm::coverage::FunctionRecordIterator::Records</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
