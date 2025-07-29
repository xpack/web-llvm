---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-deltatree-cpp-/deltatreenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DeltaTreeNode` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode">DeltaTreeNode</a> - The common part of all nodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{DeltaTree.cpp}::DeltaTreeNode { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a455e5ebc3ad620af5cdb8adc76e6f24b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WidthFactor - This controls the number of K/V slots held in the BTree: how wide it is. <a href="#a455e5ebc3ad620af5cdb8adc76e6f24b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a214f196cfb002cb214c446017df4eaa6">DeltaTreeInteriorNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e297565b80638f97e409c2f6d579332">DeltaTreeNode</a> (bool isLeaf=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c3a4d52017fd2315e4e155e22ca4151">isLeaf</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3418845f80bce5764a81fc769cb0f2da">getFullDelta</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec965054fc8939e804b7afb1eec2147">isFull</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8651e474075cd4133edfffba3e08e6c">getNumValuesUsed</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e1b9e22a417698fa120f554ae9e48c">getValue</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27a756995c91d8eb05fe8d1fc37cc72a">getValue</a> (unsigned i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a> (unsigned FileIndex, int Delta, InsertResult *InsertRes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DoInsertion - Do an insertion of the specified FileIndex/Delta pair into this node. <a href="#ad744e6529f224d58855be55473bb3d8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355b36c9c52d94268ba6f5564f084e2d">DoSplit</a> (InsertResult &amp;InsertRes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DoSplit - Split the currently full node (which has 2*WidthFactor-1 values) into two subtrees each with "WidthFactor-1" values and a pivot value. <a href="#a355b36c9c52d94268ba6f5564f084e2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f769afe7a45a8ad6c1d8908b957e401">RecomputeFullDeltaLocally</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RecomputeFullDeltaLocally - Recompute the FullDelta field by doing a local walk over our contained deltas. <a href="#a0f769afe7a45a8ad6c1d8908b957e401">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63db0172e9f7379f64ef90254ec30906">Destroy</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy - A 'virtual' destructor. <a href="#a63db0172e9f7379f64ef90254ec30906">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f6ebda892fb9daee0c913d30e7f1a3">Values</a>[2 *WidthFactor - 1]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values - This tracks the <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a>'s currently in this node. <a href="#a49f6ebda892fb9daee0c913d30e7f1a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c47c3cc8c7083ff0ecba4b18666da69">NumValuesUsed</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NumValuesUsed - This tracks the number of values this node currently holds. <a href="#a2c47c3cc8c7083ff0ecba4b18666da69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f36e54936b7e6a83c5b410cc0cdc668">IsLeaf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsLeaf - This is true if this is a leaf of the btree. <a href="#a7f36e54936b7e6a83c5b410cc0cdc668">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a2103e69ca6e36d3741aa493859b34">FullDelta</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FullDelta - This is the full delta of all the values in this node and all children nodes. <a href="#ac2a2103e69ca6e36d3741aa493859b34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode">DeltaTreeNode</a> - The common part of all nodes.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a455e5ebc3ad620af5cdb8adc76e6f24b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>WidthFactor - This controls the number of K/V slots held in the BTree: how wide it is.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WidthFactor<a id="a455e5ebc3ad620af5cdb8adc76e6f24ba335ebb4a1d52ebacc778ba9becbc070f"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

</table>
</dd>
</dl>


<p>Each level of the BTree is guaranteed to have at least WidthFactor-1 K/V pairs (except the root) and may have at most 2*WidthFactor-1 K/V pairs.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DeltaTreeInteriorNode {#a214f196cfb002cb214c446017df4eaa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode">DeltaTreeInteriorNode</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Reference <a href="#a214f196cfb002cb214c446017df4eaa6">DeltaTreeInteriorNode</a>.</p>


<p>Referenced by <a href="#a214f196cfb002cb214c446017df4eaa6">DeltaTreeInteriorNode</a>, <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a> and <a href="#a355b36c9c52d94268ba6f5564f084e2d">DoSplit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DeltaTreeNode() {#a9e297565b80638f97e409c2f6d579332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DeltaTree.cpp}::DeltaTreeNode::DeltaTreeNode (bool isLeaf=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Reference <a href="#a5c3a4d52017fd2315e4e155e22ca4151">isLeaf</a>.</p>


<p>Referenced by <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a>, <a href="#a355b36c9c52d94268ba6f5564f084e2d">DoSplit</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp/#ab590661425ca60ca82edfdb4cf22233d">getRoot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Destroy() {#a63db0172e9f7379f64ef90254ec30906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeltaTreeNode::Destroy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroy - A 'virtual' destructor.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a5c3a4d52017fd2315e4e155e22ca4151">isLeaf</a>.</p>

</div>
</div>

### DoInsertion() {#ad744e6529f224d58855be55473bb3d8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DeltaTreeNode::DoInsertion (unsigned FileIndex, int Delta, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/deltatreenode/insertresult">InsertResult</a> * InsertRes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DoInsertion - Do an insertion of the specified FileIndex/Delta pair into this node.</p>


<p>If insertion is easy, do it and return false. Otherwise, split the node, populate InsertRes with info about the split, and return true.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta/#ab1aa86bc36b4f16f872619d117cee52e">anonymous{DeltaTree.cpp}::SourceDelta::Delta</a>, <a href="#a214f196cfb002cb214c446017df4eaa6">DeltaTreeInteriorNode</a>, <a href="#a9e297565b80638f97e409c2f6d579332">DeltaTreeNode</a>, <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a>, <a href="#a355b36c9c52d94268ba6f5564f084e2d">DoSplit</a>, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta/#a645fac4dad15bc20be3537887a7fa953">anonymous{DeltaTree.cpp}::SourceDelta::FileLoc</a>, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta/#a10b1c635492d34dbd3411ac6eaef817f">anonymous{DeltaTree.cpp}::SourceDelta::get</a>, <a href="#a3418845f80bce5764a81fc769cb0f2da">getFullDelta</a>, <a href="#af8651e474075cd4133edfffba3e08e6c">getNumValuesUsed</a>, <a href="#ac7e1b9e22a417698fa120f554ae9e48c">getValue</a>, <a href="#a4ec965054fc8939e804b7afb1eec2147">isFull</a>, <a href="#a5c3a4d52017fd2315e4e155e22ca4151">isLeaf</a>, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/deltatreenode/insertresult/#a64320c81b6091fcc9048f477497bc861">anonymous{DeltaTree.cpp}::DeltaTreeNode::InsertResult::LHS</a>, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/deltatreenode/insertresult/#aa76a311e6fb01173127727b7e15eec49">anonymous{DeltaTree.cpp}::DeltaTreeNode::InsertResult::RHS</a> and <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/deltatreenode/insertresult/#ae7e2b997187957076bda6b4f2f355204">anonymous{DeltaTree.cpp}::DeltaTreeNode::InsertResult::Split</a>.</p>


<p>Referenced by <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a>.</p>

</div>
</div>

### DoSplit() {#a355b36c9c52d94268ba6f5564f084e2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeltaTreeNode::DoSplit (<a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/deltatreenode/insertresult">InsertResult</a> &amp; InsertRes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DoSplit - Split the currently full node (which has 2*WidthFactor-1 values) into two subtrees each with "WidthFactor-1" values and a pivot value.</p>


<p>Return the pieces in InsertRes.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode/#a62df3d1042541face25e40398844a0c7">anonymous{DeltaTree.cpp}::DeltaTreeInteriorNode::DeltaTreeInteriorNode</a>, <a href="#a214f196cfb002cb214c446017df4eaa6">DeltaTreeInteriorNode</a>, <a href="#a9e297565b80638f97e409c2f6d579332">DeltaTreeNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a4ec965054fc8939e804b7afb1eec2147">isFull</a>, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/deltatreenode/insertresult/#a64320c81b6091fcc9048f477497bc861">anonymous{DeltaTree.cpp}::DeltaTreeNode::InsertResult::LHS</a>, <a href="#a0f769afe7a45a8ad6c1d8908b957e401">RecomputeFullDeltaLocally</a>, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/deltatreenode/insertresult/#aa76a311e6fb01173127727b7e15eec49">anonymous{DeltaTree.cpp}::DeltaTreeNode::InsertResult::RHS</a> and <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/deltatreenode/insertresult/#ae7e2b997187957076bda6b4f2f355204">anonymous{DeltaTree.cpp}::DeltaTreeNode::InsertResult::Split</a>.</p>


<p>Referenced by <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a>.</p>

</div>
</div>

### getFullDelta() {#a3418845f80bce5764a81fc769cb0f2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{DeltaTree.cpp}::DeltaTreeNode::getFullDelta ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Referenced by <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a>.</p>

</div>
</div>

### getNumValuesUsed() {#af8651e474075cd4133edfffba3e08e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{DeltaTree.cpp}::DeltaTreeNode::getNumValuesUsed ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Referenced by <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a>, <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode/#ab48435416fb7f6cfdc4250e01b18431d">anonymous{DeltaTree.cpp}::DeltaTreeInteriorNode::getChild</a>, <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode/#a5de7896e63d6f1613086627cba6e6632">anonymous{DeltaTree.cpp}::DeltaTreeInteriorNode::getChild</a> and <a href="#a0f769afe7a45a8ad6c1d8908b957e401">RecomputeFullDeltaLocally</a>.</p>

</div>
</div>

### getValue() {#ac7e1b9e22a417698fa120f554ae9e48c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SourceDelta &amp; anonymous{DeltaTree.cpp}::DeltaTreeNode::getValue (unsigned i)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a>.</p>

</div>
</div>

### getValue() {#a27a756995c91d8eb05fe8d1fc37cc72a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceDelta &amp; anonymous{DeltaTree.cpp}::DeltaTreeNode::getValue (unsigned i)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### isFull() {#a4ec965054fc8939e804b7afb1eec2147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeltaTree.cpp}::DeltaTreeNode::isFull ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Referenced by <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a> and <a href="#a355b36c9c52d94268ba6f5564f084e2d">DoSplit</a>.</p>

</div>
</div>

### isLeaf() {#a5c3a4d52017fd2315e4e155e22ca4151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeltaTree.cpp}::DeltaTreeNode::isLeaf ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Referenced by <a href="#a9e297565b80638f97e409c2f6d579332">DeltaTreeNode</a>, <a href="#a63db0172e9f7379f64ef90254ec30906">Destroy</a> and <a href="#ad744e6529f224d58855be55473bb3d8e">DoInsertion</a>.</p>

</div>
</div>

### RecomputeFullDeltaLocally() {#a0f769afe7a45a8ad6c1d8908b957e401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeltaTreeNode::RecomputeFullDeltaLocally ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RecomputeFullDeltaLocally - Recompute the FullDelta field by doing a local walk over our contained deltas.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#af8651e474075cd4133edfffba3e08e6c">getNumValuesUsed</a>.</p>


<p>Referenced by <a href="#a355b36c9c52d94268ba6f5564f084e2d">DoSplit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FullDelta {#ac2a2103e69ca6e36d3741aa493859b34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{DeltaTree.cpp}::DeltaTreeNode::FullDelta = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FullDelta - This is the full delta of all the values in this node and all children nodes.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>

</div>
</div>

### IsLeaf {#a7f36e54936b7e6a83c5b410cc0cdc668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DeltaTree.cpp}::DeltaTreeNode::IsLeaf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsLeaf - This is true if this is a leaf of the btree.</p>


<p>If false, this is an interior node, and is actually an instance of <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode">DeltaTreeInteriorNode</a>.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>

</div>
</div>

### NumValuesUsed {#a2c47c3cc8c7083ff0ecba4b18666da69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char anonymous{DeltaTree.cpp}::DeltaTreeNode::NumValuesUsed = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NumValuesUsed - This tracks the number of values this node currently holds.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>

</div>
</div>

### Values {#a49f6ebda892fb9daee0c913d30e7f1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceDelta anonymous{DeltaTree.cpp}::DeltaTreeNode::Values[2 *WidthFactor - 1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values - This tracks the <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a>'s currently in this node.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
