---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/suffixtree/activestate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ActiveState` Struct Reference

<p>Helper struct which keeps track of the next insertion point in Ukkonen's algorithm. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SuffixTree::ActiveState { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a970208d798cdac386c47529f245a18ad">Node</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The next node to insert at. <a href="#a970208d798cdac386c47529f245a18ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c3225cd29f66a2c3871cfe9249158a">Idx</a> = <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a9038deca521822084ac798637368c94e">SuffixTreeNode::EmptyIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the first character in the substring currently being added. <a href="#ad6c3225cd29f66a2c3871cfe9249158a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaddccf29306a18928b80b6f29f10d596">Len</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The length of the substring we have to add at the current step. <a href="#aaddccf29306a18928b80b6f29f10d596">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper struct which keeps track of the next insertion point in Ukkonen's algorithm.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Idx {#ad6c3225cd29f66a2c3871cfe9249158a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuffixTree::ActiveState::Idx = <a href="/web-llvm/docs/api/structs/llvm/suffixtreenode/#a9038deca521822084ac798637368c94e">SuffixTreeNode::EmptyIdx</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the first character in the substring currently being added.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

### Len {#aaddccf29306a18928b80b6f29f10d596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuffixTree::ActiveState::Len = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The length of the substring we have to add at the current step.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

### Node {#a970208d798cdac386c47529f245a18ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SuffixTreeInternalNode* llvm::SuffixTree::ActiveState::Node = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The next node to insert at.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">SuffixTree.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
