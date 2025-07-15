---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RopePieceBTreeInterior` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a> - This represents an interior node in the B+Tree, which holds up to 2*WidthFactor pointers to child nodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{RewriteRope.cpp}::RopePieceBTreeInterior { ... }
</div>

## Base class

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b75c81f7695dc736c4cc9a02e1933a">RopePieceBTreeInterior</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ce37cfbd4b1f9af4c0048e7dcebca8">RopePieceBTreeInterior</a> (RopePieceBTreeNode *LHS, RopePieceBTreeNode *RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5deb480c9ba43cf135e1291b07841a92">~RopePieceBTreeInterior</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4dd7298da0c97f0c367e023f6e2d775">isFull</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cdf1c4e5a3a4bfb4ccfda965a243b47">getNumChildren</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c9b7644751344ccf4b40366a1af0d5">getChild</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ad1ce2238d549d1d060eba35eecbf70">getChild</a> (unsigned i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1282a6c0c36003b598a31f7c1179eb69">FullRecomputeSizeLocally</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FullRecomputeSizeLocally - Recompute the Size field of this node by summing up the sizes of the child nodes. <a href="#a1282a6c0c36003b598a31f7c1179eb69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a349144eaec23b627096e031c7c2b3425">split</a> (unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>split - Split the range containing the specified offset so that we are guaranteed that there is a place to do an insertion at the specified offset. <a href="#a349144eaec23b627096e031c7c2b3425">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b9f4e3cf9e00380b3162e8ec60769a">insert</a> (unsigned Offset, const RopePiece &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insert - Insert the specified ropepiece into this tree node at the specified offset. <a href="#a65b9f4e3cf9e00380b3162e8ec60769a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac323732b9264b45b563594cbe953b0dc">HandleChildPiece</a> (unsigned i, RopePieceBTreeNode *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HandleChildPiece - A child propagated an insertion result up to us. <a href="#ac323732b9264b45b563594cbe953b0dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a818b36cd754cef2ffba33952d59076dd">erase</a> (unsigned Offset, unsigned NumBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>erase - Remove NumBytes from this node at the specified offset. <a href="#a818b36cd754cef2ffba33952d59076dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c5de1fd9dba8ffb61f23173664be45">NumChildren</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NumChildren - This holds the number of children currently active in the Children array. <a href="#a41c5de1fd9dba8ffb61f23173664be45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a05a5909e703af6bd9b6c9944f5345d">Children</a>[2 *WidthFactor]</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a499900d391955de65b1453c41b8e81c2">classof</a> (const RopePieceBTreeNode *N)</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a> - This represents an interior node in the B+Tree, which holds up to 2*WidthFactor pointers to child nodes.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RopePieceBTreeInterior() {#af3b75c81f7695dc736c4cc9a02e1933a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::RopePieceBTreeInterior ()</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a>.</p>


<p>Referenced by <a href="#ac323732b9264b45b563594cbe953b0dc">HandleChildPiece</a>.</p>

</div>
</div>

### RopePieceBTreeInterior() {#a34ce37cfbd4b1f9af4c0048e7dcebca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::RopePieceBTreeInterior (<a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> * LHS, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> * RHS)</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#ae3581c932c9c8f1e289bc772ba5dc0c0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RopePieceBTreeInterior() {#a5deb480c9ba43cf135e1291b07841a92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::~RopePieceBTreeInterior ()</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a28686a28e1db673c0422c0cabd529373">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Destroy</a> and <a href="#a4cdf1c4e5a3a4bfb4ccfda965a243b47">getNumChildren</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### erase() {#a818b36cd754cef2ffba33952d59076dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RopePieceBTreeInterior::erase (unsigned Offset, unsigned NumBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>erase - Remove NumBytes from this node at the specified offset.</p>


<p>We are guaranteed that there is a split at Offset.</p>


<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a28686a28e1db673c0422c0cabd529373">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Destroy</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a0ebe00475d51e2c28cf5dcd1e260afa5">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::erase</a>, <a href="#aa3c9b7644751344ccf4b40366a1af0d5">getChild</a>, <a href="#a4cdf1c4e5a3a4bfb4ccfda965a243b47">getNumChildren</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#ae3581c932c9c8f1e289bc772ba5dc0c0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a65789943b6e154b98f662c1e2d882c82">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::size</a>.</p>

</div>
</div>

### FullRecomputeSizeLocally() {#a1282a6c0c36003b598a31f7c1179eb69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::FullRecomputeSizeLocally ()</td>
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

<p>FullRecomputeSizeLocally - Recompute the Size field of this node by summing up the sizes of the child nodes.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="#aa3c9b7644751344ccf4b40366a1af0d5">getChild</a>, <a href="#a4cdf1c4e5a3a4bfb4ccfda965a243b47">getNumChildren</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#ae3581c932c9c8f1e289bc772ba5dc0c0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size</a>.</p>


<p>Referenced by <a href="#ac323732b9264b45b563594cbe953b0dc">HandleChildPiece</a>.</p>

</div>
</div>

### getChild() {#aa3c9b7644751344ccf4b40366a1af0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RopePieceBTreeNode * anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::getChild (unsigned i)</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a>.</p>


<p>Referenced by <a href="#a818b36cd754cef2ffba33952d59076dd">erase</a>, <a href="#a1282a6c0c36003b598a31f7c1179eb69">FullRecomputeSizeLocally</a>, <a href="#a65b9f4e3cf9e00380b3162e8ec60769a">insert</a> and <a href="#a349144eaec23b627096e031c7c2b3425">split</a>.</p>

</div>
</div>

### getChild() {#a9ad1ce2238d549d1d060eba35eecbf70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode * anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::getChild (unsigned i)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a>.</p>

</div>
</div>

### getNumChildren() {#a4cdf1c4e5a3a4bfb4ccfda965a243b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::getNumChildren ()</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Referenced by <a href="#a818b36cd754cef2ffba33952d59076dd">erase</a>, <a href="#a1282a6c0c36003b598a31f7c1179eb69">FullRecomputeSizeLocally</a>, <a href="#ac323732b9264b45b563594cbe953b0dc">HandleChildPiece</a>, <a href="#a65b9f4e3cf9e00380b3162e8ec60769a">insert</a> and <a href="#a5deb480c9ba43cf135e1291b07841a92">~RopePieceBTreeInterior</a>.</p>

</div>
</div>

### HandleChildPiece() {#ac323732b9264b45b563594cbe953b0dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode * RopePieceBTreeInterior::HandleChildPiece (unsigned i, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HandleChildPiece - A child propagated an insertion result up to us.</p>


<p>Insert the new child, and/or propagate the result further up the tree.</p>


<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="#a1282a6c0c36003b598a31f7c1179eb69">FullRecomputeSizeLocally</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#af5d51380f73522f3b54302131ee48354">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::FullRecomputeSizeLocally</a>, <a href="#a4cdf1c4e5a3a4bfb4ccfda965a243b47">getNumChildren</a>, <a href="#ac323732b9264b45b563594cbe953b0dc">HandleChildPiece</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a54b5de49a36c6fb4157c438eb369a231">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::isFull</a>, <a href="#af3b75c81f7695dc736c4cc9a02e1933a">RopePieceBTreeInterior</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a4ba733354167c4801fb98506f22a6c3ca4a2ee1f78a24b36d2981e78ec567d4f0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::WidthFactor</a>.</p>


<p>Referenced by <a href="#ac323732b9264b45b563594cbe953b0dc">HandleChildPiece</a>, <a href="#a65b9f4e3cf9e00380b3162e8ec60769a">insert</a> and <a href="#a349144eaec23b627096e031c7c2b3425">split</a>.</p>

</div>
</div>

### insert() {#a65b9f4e3cf9e00380b3162e8ec60769a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode * RopePieceBTreeInterior::insert (unsigned Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>insert - Insert the specified ropepiece into this tree node at the specified offset.</p>


<p>The offset is relative, so "0" is the start of the node.</p>


<p>If there is no space in this subtree for the extra piece, the extra tree node is returned and must be inserted into a parent.</p>


<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="#aa3c9b7644751344ccf4b40366a1af0d5">getChild</a>, <a href="#a4cdf1c4e5a3a4bfb4ccfda965a243b47">getNumChildren</a>, <a href="#ac323732b9264b45b563594cbe953b0dc">HandleChildPiece</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a5a8475c86206d8ba61d5ecd244871a2c">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#ae3581c932c9c8f1e289bc772ba5dc0c0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a65789943b6e154b98f662c1e2d882c82">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::size</a>.</p>

</div>
</div>

### isFull() {#ad4dd7298da0c97f0c367e023f6e2d775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::isFull ()</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a4ba733354167c4801fb98506f22a6c3ca4a2ee1f78a24b36d2981e78ec567d4f0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::WidthFactor</a>.</p>

</div>
</div>

### split() {#a349144eaec23b627096e031c7c2b3425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode * RopePieceBTreeInterior::split (unsigned Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>split - Split the range containing the specified offset so that we are guaranteed that there is a place to do an insertion at the specified offset.</p>


<p>The offset is relative, so "0" is the start of the node.</p>


<p>If there is no space in this subtree for the extra piece, the extra tree node is returned and must be inserted into a parent.</p>


<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="#aa3c9b7644751344ccf4b40366a1af0d5">getChild</a>, <a href="#ac323732b9264b45b563594cbe953b0dc">HandleChildPiece</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a65789943b6e154b98f662c1e2d882c82">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8e3001fd5d1324d1e63ddcf56a45e955">llvm::split</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Children {#a3a05a5909e703af6bd9b6c9944f5345d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode* anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::Children[2 *WidthFactor]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>

</div>
</div>

### NumChildren {#a41c5de1fd9dba8ffb61f23173664be45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::NumChildren = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NumChildren - This holds the number of children currently active in the Children array.</p>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a499900d391955de65b1453c41b8e81c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> * N)</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
