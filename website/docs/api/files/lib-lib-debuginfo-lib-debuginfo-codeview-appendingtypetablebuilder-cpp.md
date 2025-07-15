---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/codeview/appendingtypetablebuilder-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AppendingTypeTableBuilder.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/appendingtypetablebuilder-h">llvm/DebugInfo/CodeView/AppendingTypeTableBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/continuationrecordbuilder-h">llvm/DebugInfo/CodeView/ContinuationRecordBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typeindex-h">llvm/DebugInfo/CodeView/TypeIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">llvm/Support/Allocator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;cstring&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69f6dc0f79ddc38844c8585a439c2b1">stabilize</a> (BumpPtrAllocator &amp;RecordStorage, ArrayRef&lt; uint8_t &gt; Record)</td>
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


<div class="doxySectionDef">

## Functions

### stabilize() {#aa69f6dc0f79ddc38844c8585a439c2b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; stabilize (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; RecordStorage, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Record)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/appendingtypetablebuilder-cpp">AppendingTypeTableBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#a4054c3eefe873caf49c2290808d409ac">llvm::BumpPtrAllocatorImpl&lt; AllocatorT, SlabSize, SizeThreshold, GrowthDelay &gt;::Allocate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/mergingtypetablebuilder/#a9bf65e7f391ff7849881f3b4ffcef70a">llvm::codeview::MergingTypeTableBuilder::insertRecordAs</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/appendingtypetablebuilder/#a921cbd2a45ece4531141d3fc8aca6bd6">llvm::codeview::AppendingTypeTableBuilder::insertRecordBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/appendingtypetablebuilder/#a96695461914608b976f949ec2fd55c73">llvm::codeview::AppendingTypeTableBuilder::replaceType</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder/#aa8b7c684352cfa5cebef256df3df6955">llvm::codeview::GlobalTypeTableBuilder::replaceType</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/mergingtypetablebuilder/#aa948dfdffdb254c7b98e5457cb8e7798">llvm::codeview::MergingTypeTableBuilder::replaceType</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
