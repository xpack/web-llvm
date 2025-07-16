---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/suffixtree
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SuffixTree` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SuffixTree { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">llvm/Support/SuffixTree.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtree/repeatedsubstringiterator">RepeatedSubstringIterator</a> <a href="#aabca947847ba6f5cc1361be91ba9717c">iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27fe0d1c22c4e49e3909514161e7b481">SuffixTree</a> (const ArrayRef&lt; unsigned &gt; &amp;Str, bool OutlinerLeafDescendants=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a suffix tree from a sequence of unsigned integers. <a href="#a27fe0d1c22c4e49e3909514161e7b481">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aabca947847ba6f5cc1361be91ba9717c">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f2e900a260f932d4f3d87c93c55eaa">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aabca947847ba6f5cc1361be91ba9717c">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94ad78b0bfc461f317f6824aca96e486">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreenode">SuffixTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4e0b7bbb9f179021e6f8d0ca4298aee">insertLeaf</a> (SuffixTreeInternalNode &amp;Parent, unsigned StartIdx, unsigned Edge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a leaf node and add it to the tree. <a href="#ad4e0b7bbb9f179021e6f8d0ca4298aee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987cc15249f7b760c0abe7cfa747e079">insertInternalNode</a> (SuffixTreeInternalNode *Parent, unsigned StartIdx, unsigned EndIdx, unsigned Edge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate an internal node and add it to the tree. <a href="#a987cc15249f7b760c0abe7cfa747e079">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4371893240d4f09a3a782163a97392">insertRoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate the root node and add it to the tree. <a href="#a7f4371893240d4f09a3a782163a97392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b598d985a6a56011d6b4808cf951a8">setSuffixIndices</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the suffix indices of the leaves to the start indices of their respective suffixes. <a href="#a87b598d985a6a56011d6b4808cf951a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485ccf00cca04710ba96f038d166de65">extend</a> (unsigned EndIdx, unsigned SuffixesToAdd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the suffix tree for the prefix of the input ending at <span class="doxyComputerOutput">EndIdx</span>. <a href="#a485ccf00cca04710ba96f038d166de65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5201fe4e74dbfafb4dd87b9d7fba325e">setLeafNodes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a post-order depth-first traversal of the tree and perform two tasks during the traversal. <a href="#a5201fe4e74dbfafb4dd87b9d7fba325e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49bfcd763abc20e39f1f6ea9bffc0fb">Str</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Each element is an integer representing an instruction in the module. <a href="#aa49bfcd763abc20e39f1f6ea9bffc0fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af73cec98a8c1f4c57f72cdd127716536">OutlinerLeafDescendants</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to consider leaf descendants or only leaf children. <a href="#af73cec98a8c1f4c57f72cdd127716536">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa10ae368e9294e765d41ff9dd0e766a5">InternalNodeAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maintains internal nodes in the tree. <a href="#aa10ae368e9294e765d41ff9dd0e766a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/suffixtreeleafnode">SuffixTreeLeafNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96f7cafd3c71149bf70f4432598fad1">LeafNodeAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maintains leaf nodes in the tree. <a href="#af96f7cafd3c71149bf70f4432598fad1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff03850e3057a6a44714f4590898d99">Root</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The root of the suffix tree. <a href="#adff03850e3057a6a44714f4590898d99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3649460eadf427d7e408afa34ff55e">LeafEndIdx</a> = <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a9038deca521822084ac798637368c94e">SuffixTreeNode::EmptyIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The end index of each leaf in the tree. <a href="#a4f3649460eadf427d7e408afa34ff55e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ActiveState</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a3263b9639c904e8c74665b70b87c7">Active</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The point the next insertion will take place at in the construction algorithm. <a href="#a67a3263b9639c904e8c74665b70b87c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/suffixtreeleafnode">SuffixTreeLeafNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adadcf76beb8d18413c5f0e69c9aab090">LeafNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This vector contains all leaf nodes of this suffix tree. <a href="#adadcf76beb8d18413c5f0e69c9aab090">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#aabca947847ba6f5cc1361be91ba9717c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef RepeatedSubstringIterator llvm::SuffixTree::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SuffixTree() {#a27fe0d1c22c4e49e3909514161e7b481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SuffixTree::SuffixTree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; &amp; Str, bool OutlinerLeafDescendants=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a suffix tree from a sequence of unsigned integers.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Str</td>
<td class="doxyParamItemDescription"><p>The string to construct the suffix tree for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutlinerLeafDescendants</td>
<td class="doxyParamItemDescription"><p>Whether to consider leaf descendants or only leaf children (used by Machine Outliner).</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtree-cpp">SuffixTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af73cec98a8c1f4c57f72cdd127716536">OutlinerLeafDescendants</a> and <a href="#aa49bfcd763abc20e39f1f6ea9bffc0fb">Str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a53f2e900a260f932d4f3d87c93c55eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SuffixTree::begin ()</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

### end() {#a94ad78b0bfc461f317f6824aca96e486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SuffixTree::end ()</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### extend() {#a485ccf00cca04710ba96f038d166de65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SuffixTree::extend (unsigned EndIdx, unsigned SuffixesToAdd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the suffix tree for the prefix of the input ending at <span class="doxyComputerOutput">EndIdx</span>.</p>


<p>Used to construct the full suffix tree iteratively. At the end of each step, the constructed suffix tree is either a valid suffix tree, or a suffix tree with implicit suffixes. At the end of the final step, the suffix tree is a valid tree.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">EndIdx</td>
<td class="doxyParamItemDescription"><p>The end index of the current prefix in the main string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SuffixesToAdd</td>
<td class="doxyParamItemDescription"><p>The number of suffixes that must be added to complete the suffix tree at the current phase.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of suffixes that have not been added at the end of this step.</p></dd>
</dl>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtree-cpp">SuffixTree.cpp</a>.</p>

</div>
</div>

### insertInternalNode() {#a987cc15249f7b760c0abe7cfa747e079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SuffixTreeInternalNode * SuffixTree::insertInternalNode (<a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> * Parent, unsigned StartIdx, unsigned EndIdx, unsigned Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate an internal node and add it to the tree.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parent</td>
<td class="doxyParamItemDescription"><p>The parent of this node. Only null when allocating the root.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StartIdx</td>
<td class="doxyParamItemDescription"><p>The start index of this node's associated string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EndIdx</td>
<td class="doxyParamItemDescription"><p>The end index of this node's associated string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Edge</td>
<td class="doxyParamItemDescription"><p>The label on the edge leaving <span class="doxyComputerOutput">Parent</span> to this node.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A pointer to the allocated internal node.</p></dd>
</dl>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtree-cpp">SuffixTree.cpp</a>.</p>

</div>
</div>

### insertLeaf() {#ad4e0b7bbb9f179021e6f8d0ca4298aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SuffixTreeNode * SuffixTree::insertLeaf (<a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> &amp; Parent, unsigned StartIdx, unsigned Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate a leaf node and add it to the tree.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parent</td>
<td class="doxyParamItemDescription"><p>The parent of this node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StartIdx</td>
<td class="doxyParamItemDescription"><p>The start index of this node's associated string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Edge</td>
<td class="doxyParamItemDescription"><p>The label on the edge leaving <span class="doxyComputerOutput">Parent</span> to this node.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A pointer to the allocated leaf node.</p></dd>
</dl>


<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtree-cpp">SuffixTree.cpp</a>.</p>

</div>
</div>

### insertRoot() {#a7f4371893240d4f09a3a782163a97392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SuffixTreeInternalNode * SuffixTree::insertRoot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate the root node and add it to the tree.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A pointer to the root.</p></dd>
</dl>


<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtree-cpp">SuffixTree.cpp</a>.</p>

</div>
</div>

### setLeafNodes() {#a5201fe4e74dbfafb4dd87b9d7fba325e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SuffixTree::setLeafNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a post-order depth-first traversal of the tree and perform two tasks during the traversal.</p>


<p>The first is to populate LeafNodes, adding nodes in order of the traversal. The second is to keep track of the leaf descendants of every internal node by assigning values to LeftLeafIndex and RightLefIndex fields of <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode">SuffixTreeNode</a> for all internal nodes.</p>


<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtree-cpp">SuffixTree.cpp</a>.</p>

</div>
</div>

### setSuffixIndices() {#a87b598d985a6a56011d6b4808cf951a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SuffixTree::setSuffixIndices ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the suffix indices of the leaves to the start indices of their respective suffixes.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtree-cpp">SuffixTree.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### OutlinerLeafDescendants {#af73cec98a8c1f4c57f72cdd127716536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SuffixTree::OutlinerLeafDescendants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to consider leaf descendants or only leaf children.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>


<p>Referenced by <a href="#a27fe0d1c22c4e49e3909514161e7b481">SuffixTree</a>.</p>

</div>
</div>

### Str {#aa49bfcd763abc20e39f1f6ea9bffc0fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;unsigned&gt; llvm::SuffixTree::Str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Each element is an integer representing an instruction in the module.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>


<p>Referenced by <a href="#a27fe0d1c22c4e49e3909514161e7b481">SuffixTree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Active {#a67a3263b9639c904e8c74665b70b87c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ActiveState llvm::SuffixTree::Active</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The point the next insertion will take place at in the construction algorithm.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

### InternalNodeAllocator {#aa10ae368e9294e765d41ff9dd0e766a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;SuffixTreeInternalNode&gt; llvm::SuffixTree::InternalNodeAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maintains internal nodes in the tree.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

### LeafEndIdx {#a4f3649460eadf427d7e408afa34ff55e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuffixTree::LeafEndIdx = <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a9038deca521822084ac798637368c94e">SuffixTreeNode::EmptyIdx</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The end index of each leaf in the tree.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

### LeafNodeAllocator {#af96f7cafd3c71149bf70f4432598fad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;SuffixTreeLeafNode&gt; llvm::SuffixTree::LeafNodeAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maintains leaf nodes in the tree.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

### LeafNodes {#adadcf76beb8d18413c5f0e69c9aab090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SuffixTreeLeafNode *&gt; llvm::SuffixTree::LeafNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This vector contains all leaf nodes of this suffix tree.</p>


<p>These leaf nodes are identified using post-order depth-first traversal, so that the order of these leaf nodes in the vector matches the order of the leaves in the tree from left to right if one were to draw the tree on paper.</p>


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

### Root {#adff03850e3057a6a44714f4590898d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SuffixTreeInternalNode* llvm::SuffixTree::Root = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The root of the suffix tree.</p>


<p>The root represents the empty string. It is maintained by the <span class="doxyComputerOutput">NodeAllocator</span> like every other node in the tree.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/suffixtree-cpp">SuffixTree.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
