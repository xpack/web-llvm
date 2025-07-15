---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/rewriterope-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RewriteRope.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/rewriterope-h">llvm/ADT/RewriteRope.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstring&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-rewriterope-cpp-">anonymous{RewriteRope.cpp}</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/rewriterope">RewriteRope</a> is a "strong" string class, designed to make insertions and deletions in the middle of the string nearly constant time (really, they are O(log N), but with a very low constant factor). <a href="/web-llvm/docs/api/namespaces/anonymous-rewriterope-cpp-/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RopePieceBTreeLeaf *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf8a617a854421722dff2700940de96">getCN</a> (const void *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static RopePieceBTreeNode *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c7d5e4429731aca8a7c0396904ef124">getRoot</a> (void *P)</td>
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

### getCN() {#aaaf8a617a854421722dff2700940de96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RopePieceBTreeLeaf * getCN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
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



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#ae1ad9b9cc567a789627f8230ddeee241">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::RopePieceBTreeLeaf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ropepiecebtreeiterator/#ad9b95870bbbafabe82784b169e314896">llvm::RopePieceBTreeIterator::MoveToNextPiece</a> and <a href="/web-llvm/docs/api/classes/llvm/ropepiecebtreeiterator/#a55a2ecf8e4070a3b18e48b780cdd6f51">llvm::RopePieceBTreeIterator::RopePieceBTreeIterator</a>.</p>

</div>
</div>

### getRoot() {#a5c7d5e4429731aca8a7c0396904ef124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode * getRoot (void * P)</td>
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



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
