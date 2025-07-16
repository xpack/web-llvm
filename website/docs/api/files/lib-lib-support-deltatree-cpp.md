---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/deltatree-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DeltaTree.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">llvm/ADT/DeltaTree.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include &lt;cassert&gt;
#include &lt;cstring&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-deltatree-cpp-">anonymous{DeltaTree.cpp}</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> class is a multiway search tree (BTree) structure with some fancy features. <a href="/web-llvm/docs/api/namespaces/anonymous-deltatree-cpp-/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> - As code in the original input buffer is added and deleted, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> records are used to keep track of how the input SourceLocation object is mapped into the output buffer. <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode">DeltaTreeNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode">DeltaTreeNode</a> - The common part of all nodes. <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/deltatreenode/insertresult">InsertResult</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode">DeltaTreeInteriorNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode">DeltaTreeInteriorNode</a> - When isLeaf = false, a node has child pointers. <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static DeltaTreeNode *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab590661425ca60ca82edfdb4cf22233d">getRoot</a> (void *Root)</td>
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

### getRoot() {#ab590661425ca60ca82edfdb4cf22233d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaTreeNode * getRoot (void * Root)</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode/#a9e297565b80638f97e409c2f6d579332">anonymous{DeltaTree.cpp}::DeltaTreeNode::DeltaTreeNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/deltatree/#a65b2200df7c029fc766e3486c6629ae5">llvm::DeltaTree::AddDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/ropepiecebtree/#ad2b31f7577575db9116286aa7eb9eb88">llvm::RopePieceBTree::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/deltatree/#a71158ee3b58ca404fbbe5c7e96d30c4b">llvm::DeltaTree::DeltaTree</a>, <a href="/web-llvm/docs/api/classes/llvm/ropepiecebtree/#a84b450bb9da39cb7e9a32b070be6e086">llvm::RopePieceBTree::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#abec5174f9edec79de20397f6b8e0ccdf">llvm::msgpack::Document::fromYAML</a>, <a href="/web-llvm/docs/api/classes/llvm/deltatree/#a9d2add1ca152069aa7cd796d3e7c552e">llvm::DeltaTree::getDeltaAt</a>, <a href="/web-llvm/docs/api/classes/llvm/ropepiecebtree/#a7df64d1d1750e8b24349731c8bd5d8a3">llvm::RopePieceBTree::insert</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a721c66ae31a226c5f4244f7827ddbba2">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::PromoteMem2Reg</a>, <a href="/web-llvm/docs/api/classes/threadsafetrierawhashmapbase/impltype/#a136e93a3da4f0b0ca10e261d94c76100">llvm::ThreadSafeTrieRawHashMapBase::ImplType::save</a>, <a href="/web-llvm/docs/api/classes/llvm/ropepiecebtree/#a650c344f216dd59d031913a242df9e39">llvm::RopePieceBTree::size</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a82205f2c71cb88331e554cb4fc8b8822">llvm::msgpack::Document::toYAML</a>, <a href="/web-llvm/docs/api/classes/llvm/deltatree/#abf2c383983f61525048221dc5218c8a0">llvm::DeltaTree::~DeltaTree</a> and <a href="/web-llvm/docs/api/classes/llvm/ropepiecebtree/#a2d57e33c075c95f38ebe02b23cd34aa7">llvm::RopePieceBTree::~RopePieceBTree</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
