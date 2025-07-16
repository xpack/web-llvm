---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/memprof/callstack/callstackiterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CallStackIterator` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::memprof::CallStack::CallStackIterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">llvm/Analysis/MemoryProfileInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1eb8a8131d76d87c175640059ca21b3">CallStackIterator</a> (const NodeT *N, bool End)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d1e97095918f6f93df6be45a6557afe">CallStackIterator</a> (const MDNode *N, bool End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specializations for iterating through IR metadata stack contexts. <a href="#a8d1e97095918f6f93df6be45a6557afe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7889f786837688475dfe17af8b39e55">operator*</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaacedd8ec0ad6f90de8ee79b309ad5e">operator==</a> (const CallStackIterator &amp;rhs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268f1490d74fa9988335d2c0c29c3487">operator!=</a> (const CallStackIterator &amp;rhs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a906df1bd60ff7cb4c8b3273a6c3aa">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0c201e8ee704a7f52427ce5240e79e">operator*</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5d28319f8676510a6efdd4bf8d01ca">N</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">IteratorT</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae0f0d5ef648ccea30a6028c82c2b2a">Iter</a></td>
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


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallStackIterator() {#ad1eb8a8131d76d87c175640059ca21b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::CallStackIterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * N, bool End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<p>References <a href="#a5ae0f0d5ef648ccea30a6028c82c2b2a">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::Iter</a> and <a href="#a8e5d28319f8676510a6efdd4bf8d01ca">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::N</a>.</p>


<p>Referenced by <a href="#a268f1490d74fa9988335d2c0c29c3487">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator!=</a> and <a href="#abaacedd8ec0ad6f90de8ee79b309ad5e">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator==</a>.</p>

</div>
</div>

### CallStackIterator() {#a8d1e97095918f6f93df6be45a6557afe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::CallStack::CallStackIterator&lt; MDNode, MDNode::op_iterator &gt;::CallStackIterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N, bool End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specializations for iterating through IR metadata stack contexts.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<p>Reference <a href="#a8e5d28319f8676510a6efdd4bf8d01ca">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a268f1490d74fa9988335d2c0c29c3487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/callstack/callstackiterator">CallStackIterator</a> &amp; rhs)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<p>Reference <a href="#ad1eb8a8131d76d87c175640059ca21b3">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::CallStackIterator</a>.</p>

</div>
</div>

### operator\*() {#af7889f786837688475dfe17af8b39e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator* ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ae0f0d5ef648ccea30a6028c82c2b2a">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::Iter</a> and <a href="#a8e5d28319f8676510a6efdd4bf8d01ca">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::N</a>.</p>

</div>
</div>

### operator\*() {#a6b0c201e8ee704a7f52427ce5240e79e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::CallStack::CallStackIterator&lt; MDNode, MDNode::op_iterator &gt;::operator* ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>

</div>
</div>

### operator++() {#a50a906df1bd60ff7cb4c8b3273a6c3aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator++ ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<p>Reference <a href="#a5ae0f0d5ef648ccea30a6028c82c2b2a">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::Iter</a>.</p>

</div>
</div>

### operator==() {#abaacedd8ec0ad6f90de8ee79b309ad5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/callstack/callstackiterator">CallStackIterator</a> &amp; rhs)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<p>References <a href="#ad1eb8a8131d76d87c175640059ca21b3">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::CallStackIterator</a> and <a href="#a5ae0f0d5ef648ccea30a6028c82c2b2a">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::Iter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Iter {#a5ae0f0d5ef648ccea30a6028c82c2b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IteratorT llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::Iter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<p>Referenced by <a href="#ad1eb8a8131d76d87c175640059ca21b3">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::CallStackIterator</a>, <a href="#af7889f786837688475dfe17af8b39e55">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator*</a>, <a href="#a50a906df1bd60ff7cb4c8b3273a6c3aa">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator++</a> and <a href="#abaacedd8ec0ad6f90de8ee79b309ad5e">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator==</a>.</p>

</div>
</div>

### N {#a8e5d28319f8676510a6efdd4bf8d01ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeT* llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::N = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a>.</p>


<p>Referenced by <a href="#a8d1e97095918f6f93df6be45a6557afe">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::CallStackIterator</a>, <a href="#ad1eb8a8131d76d87c175640059ca21b3">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::CallStackIterator</a> and <a href="#af7889f786837688475dfe17af8b39e55">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::CallStackIterator::operator*</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">MemoryProfileInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
