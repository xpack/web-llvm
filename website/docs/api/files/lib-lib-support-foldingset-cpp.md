---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/foldingset-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `FoldingSet.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">llvm/ADT/FoldingSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">llvm/Support/Allocator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/swapbyteorder-h">llvm/Support/SwapByteOrder.h</a>"
#include &lt;cassert&gt;
#include &lt;cstring&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node">FoldingSetBase::Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f8ba1b9a42df5cb5d980ebf3748925">GetNextPtr</a> (void *NextInBucketPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper functions for <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase">FoldingSetBase</a>. <a href="#a99f8ba1b9a42df5cb5d980ebf3748925">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a353da8c5013043b9425e9cc07012bd3e">GetBucketPtr</a> (void *NextInBucketPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>testing. <a href="#a353da8c5013043b9425e9cc07012bd3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85e4a0c73ad7a5e3e3527f2ce8ae2f51">GetBucketFor</a> (unsigned Hash, void **Buckets, unsigned NumBuckets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetBucketFor - Hash the specified node <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and return the hash bucket for the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a85e4a0c73ad7a5e3e3527f2ce8ae2f51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97273c4c8ad6de0f710e32e23c665b9b">AllocateBuckets</a> (unsigned NumBuckets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AllocateBuckets - Allocated initialized bucket memory. <a href="#a97273c4c8ad6de0f710e32e23c665b9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### AllocateBuckets() {#a97273c4c8ad6de0f710e32e23c665b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ** AllocateBuckets (unsigned NumBuckets)</td>
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

<p>AllocateBuckets - Allocated initialized bucket memory.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp">FoldingSet.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a53b2f25342c49b78f06fbec9cf7fe644">llvm::safe_calloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/#a0b9bf8b05bd0406a5336cb542bc8144a">llvm::FoldingSetBase::FoldingSetBase</a>.</p>

</div>
</div>

### GetBucketFor() {#a85e4a0c73ad7a5e3e3527f2ce8ae2f51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ** GetBucketFor (unsigned Hash, void ** Buckets, unsigned NumBuckets)</td>
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

<p>GetBucketFor - Hash the specified node <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and return the hash bucket for the specified <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp">FoldingSet.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/#af117101241977258f5cebbec909651dc">llvm::FoldingSetBase::FindNodeOrInsertPos</a> and <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/#abad18f0235458f866663a2a78062c855">llvm::FoldingSetBase::InsertNode</a>.</p>

</div>
</div>

### GetBucketPtr() {#a353da8c5013043b9425e9cc07012bd3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ** GetBucketPtr (void * NextInBucketPtr)</td>
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

<p>testing.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp">FoldingSet.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/foldingsetiteratorimpl/#acb6151b8ecc444658e152761887bab9a">llvm::FoldingSetIteratorImpl::advance</a> and <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/#a50648616eadb2b7b9dcf36c9bd685ccc">llvm::FoldingSetBase::RemoveNode</a>.</p>

</div>
</div>

### GetNextPtr() {#a99f8ba1b9a42df5cb5d980ebf3748925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSetBase::Node * GetNextPtr (void * NextInBucketPtr)</td>
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

<p>Helper functions for <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase">FoldingSetBase</a>.</p>


<p>GetNextPtr - In order to save space, each bucket is a singly-linked-list. In order to make deletion more efficient, we make the list circular, so we can delete a node without computing its hash. The problem with this is that the start of the hash buckets are not Nodes. If NextInBucketPtr is a bucket pointer, this method returns null: use GetBucketPtr when this happens.</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/support/foldingset-cpp">FoldingSet.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/foldingsetiteratorimpl/#acb6151b8ecc444658e152761887bab9a">llvm::FoldingSetIteratorImpl::advance</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/#af117101241977258f5cebbec909651dc">llvm::FoldingSetBase::FindNodeOrInsertPos</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbucketiteratorimpl/#a90952c33551c531abe5416e86b9280ba">llvm::FoldingSetBucketIteratorImpl::FoldingSetBucketIteratorImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetiteratorimpl/#a3297d4b587880e46293a51d51fe09db7">llvm::FoldingSetIteratorImpl::FoldingSetIteratorImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/#a50648616eadb2b7b9dcf36c9bd685ccc">llvm::FoldingSetBase::RemoveNode</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
