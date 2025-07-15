---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/suffixtreeinternalnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SuffixTreeInternalNode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::SuffixTreeInternalNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">llvm/Support/SuffixTreeNode.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreenode">SuffixTreeNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A node in a suffix tree which represents a substring or suffix. <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee4f3eefe02d5d475ffb06b54b7da9ed">SuffixTreeInternalNode</a> (unsigned StartIdx, unsigned EndIdx, SuffixTreeInternalNode *Link)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386252d96ddabf55ee27a621cdfaebd8">~SuffixTreeInternalNode</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b664c3b910cb6d5cda2ba6b83b759c">isRoot</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38ddb7b7fb273fb64379c661efaf974">getEndIdx</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae53280c72c15c2777d813369d19d4868">setLink</a> (SuffixTreeInternalNode *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets <span class="doxyComputerOutput">Link</span> to <span class="doxyComputerOutput">L</span>. Assumes <span class="doxyComputerOutput">L</span> is not null. <a href="#ae53280c72c15c2777d813369d19d4868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ef8294e550ab22ebf4335773828603">getLink</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode">SuffixTreeNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a244b1a8b6c26960faf2663376005ca7a">Children</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The children of this node. <a href="#a244b1a8b6c26960faf2663376005ca7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d706b398cbb51f32bb4da6cc03752d2">EndIdx</a> = <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a9038deca521822084ac798637368c94e">EmptyIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The end index of this node's substring in the main string. <a href="#a6d706b398cbb51f32bb4da6cc03752d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a794cdf01e7ccc874386e611bb1c40ab0">Link</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pointer to the internal node representing the same sequence with the first character chopped off. <a href="#a794cdf01e7ccc874386e611bb1c40ab0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a945ed42e87aca83910a3f79960d00eb7">classof</a> (const SuffixTreeNode *N)</td>
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


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SuffixTreeInternalNode() {#aee4f3eefe02d5d475ffb06b54b7da9ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SuffixTreeInternalNode::SuffixTreeInternalNode (unsigned StartIdx, unsigned EndIdx, <a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> * Link)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#add485021cba74f84f545a03c2deb6db3a1c5cd656d7af113d4cb72dc8046dc1ad">llvm::SuffixTreeNode::ST_Internal</a>, <a href="#aee4f3eefe02d5d475ffb06b54b7da9ed">SuffixTreeInternalNode</a> and <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a81101451dd797327456c73527a6e440b">llvm::SuffixTreeNode::SuffixTreeNode</a>.</p>


<p>Referenced by <a href="#aa3ef8294e550ab22ebf4335773828603">getLink</a>, <a href="#ae53280c72c15c2777d813369d19d4868">setLink</a> and <a href="#aee4f3eefe02d5d475ffb06b54b7da9ed">SuffixTreeInternalNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SuffixTreeInternalNode() {#a386252d96ddabf55ee27a621cdfaebd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::SuffixTreeInternalNode::~SuffixTreeInternalNode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEndIdx() {#ac38ddb7b7fb273fb64379c661efaf974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SuffixTreeInternalNode::getEndIdx ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the end index of this node's substring in the entire string.</p></dd>
</dl>


<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>

</div>
</div>

### getLink() {#aa3ef8294e550ab22ebf4335773828603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SuffixTreeInternalNode * SuffixTreeInternalNode::getLink ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the pointer to the Link node.</p></dd>
</dl>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>


<p>Reference <a href="#aee4f3eefe02d5d475ffb06b54b7da9ed">SuffixTreeInternalNode</a>.</p>

</div>
</div>

### isRoot() {#a05b664c3b910cb6d5cda2ba6b83b759c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SuffixTreeInternalNode::isRoot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this node is the root of its owning <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/suffixtree">SuffixTree</a></span>.</p></dd>
</dl>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a9038deca521822084ac798637368c94e">llvm::SuffixTreeNode::EmptyIdx</a> and <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a9275db494732cf0988a1547c93420de2">llvm::SuffixTreeNode::getStartIdx</a>.</p>

</div>
</div>

### setLink() {#ae53280c72c15c2777d813369d19d4868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SuffixTreeInternalNode::setLink (<a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets <span class="doxyComputerOutput">Link</span> to <span class="doxyComputerOutput">L</span>. Assumes <span class="doxyComputerOutput">L</span> is not null.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aee4f3eefe02d5d475ffb06b54b7da9ed">SuffixTreeInternalNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Children {#a244b1a8b6c26960faf2663376005ca7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, SuffixTreeNode *&gt; llvm::SuffixTreeInternalNode::Children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The children of this node.</p>


<p>A child existing on an unsigned integer implies that from the mapping represented by the current node, there is a way to reach another mapping by tacking that character on the end of the current string.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EndIdx {#a6d706b398cbb51f32bb4da6cc03752d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuffixTreeInternalNode::EndIdx = <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a9038deca521822084ac798637368c94e">EmptyIdx</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The end index of this node's substring in the main string.</p>


<p>Every leaf node must have its <span class="doxyComputerOutput">EndIdx</span> incremented at the end of every step in the construction algorithm. To avoid having to update O(N) nodes individually at the end of every step, the end index is stored as a pointer.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

### Link {#a794cdf01e7ccc874386e611bb1c40ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SuffixTreeInternalNode* llvm::SuffixTreeInternalNode::Link = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A pointer to the internal node representing the same sequence with the first character chopped off.</p>


<p>This acts as a shortcut in Ukkonen's algorithm. One of the things that Ukkonen's algorithm does to achieve linear-time construction is keep track of which node the next insert should be at. This makes each insert O(1), and there are a total of O(N) inserts. The suffix link helps with inserting children of internal nodes.</p>


<p>Say we add a child to an internal node with associated mapping S. The next insertion must be at the node representing S - its first character. This is given by the way that we iteratively build the tree in Ukkonen's algorithm. The main idea is to look at the suffixes of each prefix in the string, starting with the longest suffix of the prefix, and ending with the shortest. Therefore, if we keep pointers between such nodes, we can move to the next insertion point in O(1) time. If we don't, then we'd have to query from the root, which takes O(N) time. This would make the construction algorithm O(N^2) rather than O(N).</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a945ed42e87aca83910a3f79960d00eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SuffixTreeInternalNode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode">SuffixTreeNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#add485021cba74f84f545a03c2deb6db3a1c5cd656d7af113d4cb72dc8046dc1ad">llvm::SuffixTreeNode::ST_Internal</a> and <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a81101451dd797327456c73527a6e440b">llvm::SuffixTreeNode::SuffixTreeNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
