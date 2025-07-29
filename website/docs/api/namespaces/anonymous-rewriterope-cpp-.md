---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-rewriterope-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{RewriteRope.cpp}` Namespace

<p><a href="/web-llvm/docs/api/classes/llvm/rewriterope">RewriteRope</a> is a "strong" string class, designed to make insertions and deletions in the middle of the string nearly constant time (really, they are O(log N), but with a very low constant factor). <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace anonymous{RewriteRope.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> - Common base class of <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a>. <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> - Directly manages up to '2*WidthFactor' <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> nodes. <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a> - This represents an interior node in the B+Tree, which holds up to 2*WidthFactor pointers to child nodes. <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/rewriterope">RewriteRope</a> is a "strong" string class, designed to make insertions and deletions in the middle of the string nearly constant time (really, they are O(log N), but with a very low constant factor).</p>


<p>The implementation of this datastructure is a conceptual linear sequence of <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> elements. Each <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> represents a view on a separately allocated and reference counted string. This means that splitting a very long string can be done in constant time by splitting a <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> that references the whole string into two rope pieces that reference each half. Once split, another string can be inserted in between the two halves by inserting a <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> in between the two others. All of this is very inexpensive: it takes time proportional to the number of RopePieces, not the length of the strings they represent.</p>


<p>While a linear sequences of RopePieces is the conceptual model, the actual implementation captures them in an adapted B+ Tree. Using a B+ tree (which is a tree that keeps the values in the leaves and has where each node contains a reasonable number of pointers to children/values) allows us to maintain efficient operation when the <a href="/web-llvm/docs/api/classes/llvm/rewriterope">RewriteRope</a> contains a <em>huge</em> number of RopePieces. The basic idea of the B+ Tree is that it allows us to find the <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> corresponding to some offset very efficiently, and it automatically balances itself on insertions of RopePieces (which can happen for both insertions and erases of string ranges).</p>


<p>The one wrinkle on the theory is that we don't attempt to keep the tree properly balanced when erases happen. Erases of string data can both insert new RopePieces (e.g. when the middle of some other rope piece is deleted, which results in two rope pieces, which is just like an insert) or it can reduce the number of RopePieces maintained by the B+Tree. In the case when the number of RopePieces is reduced, we don't attempt to maintain the standard 'invariant' that each node in the tree contains at least 'WidthFactor' children/values. For our use cases, this doesn't seem to matter.</p>


<p>The implementation below is primarily implemented in terms of three classes: <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> - Common base class for:</p>


<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> - Directly manages up to '2*WidthFactor' <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> nodes. This directly represents a chunk of the string with those RopePieces concatenated. <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a> - An interior node in the B+ Tree, which manages up to '2*WidthFactor' other nodes in the tree.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
