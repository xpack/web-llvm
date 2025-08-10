---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RopePieceBTreeNode` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> - Common base class of <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{RewriteRope.cpp}::RopePieceBTreeNode { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

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

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a4ba733354167c4801fb98506f22a6c3c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WidthFactor - This controls the number of K/V slots held in the BTree: how wide it is. <a href="#a4ba733354167c4801fb98506f22a6c3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469f9d8881255bab80c4a1cf69696f0f">RopePieceBTreeNode</a> (bool isLeaf)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0216abc5f38c5491ca808b47c6ba88b4">~RopePieceBTreeNode</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509afbe923622193704c25b43010763a">isLeaf</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65789943b6e154b98f662c1e2d882c82">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28686a28e1db673c0422c0cabd529373">Destroy</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02b6f427df62fc4de4b851a72ce6da66">split</a> (unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>split - Split the range containing the specified offset so that we are guaranteed that there is a place to do an insertion at the specified offset. <a href="#a02b6f427df62fc4de4b851a72ce6da66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a8475c86206d8ba61d5ecd244871a2c">insert</a> (unsigned Offset, const RopePiece &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insert - Insert the specified ropepiece into this tree node at the specified offset. <a href="#a5a8475c86206d8ba61d5ecd244871a2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ebe00475d51e2c28cf5dcd1e260afa5">erase</a> (unsigned Offset, unsigned NumBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>erase - Remove NumBytes from this node at the specified offset. <a href="#a0ebe00475d51e2c28cf5dcd1e260afa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3581c932c9c8f1e289bc772ba5dc0c0">Size</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size - This is the number of bytes of file this node (including any potential children) covers. <a href="#ae3581c932c9c8f1e289bc772ba5dc0c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a561c6bd84db78f8d3e68d4b85db67ea9">IsLeaf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsLeaf - True if this is an instance of <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a>, false if it is an instance of <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a>. <a href="#a561c6bd84db78f8d3e68d4b85db67ea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> - Common base class of <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a>.</p>


<p>This provides some 'virtual' dispatching methods and a flag that determines which subclass the instance is. Also important, this node knows the full extend of the node, including any children that it has. This allows efficient skipping over entire subtrees when looking for an offset in the BTree.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a4ba733354167c4801fb98506f22a6c3c}

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
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
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
<td class="doxyEnumItemName">WidthFactor<a id="a4ba733354167c4801fb98506f22a6c3ca4a2ee1f78a24b36d2981e78ec567d4f0"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

</table>
</dd>
</dl>


<p>Each level of the BTree is guaranteed to have at least 'WidthFactor' elements in it (either ropepieces or children), (except the root, which may have less) and may have at most 2*WidthFactor elements.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### RopePieceBTreeNode() {#a469f9d8881255bab80c4a1cf69696f0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode (bool isLeaf)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="#a561c6bd84db78f8d3e68d4b85db67ea9">IsLeaf</a> and <a href="#a509afbe923622193704c25b43010763a">isLeaf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a499900d391955de65b1453c41b8e81c2">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::classof</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a32f112cc839a156174e9aece8b339e68">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::classof</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a818b36cd754cef2ffba33952d59076dd">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::erase</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a9ad1ce2238d549d1d060eba35eecbf70">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::getChild</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#aa3c9b7644751344ccf4b40366a1af0d5">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::getChild</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#ac323732b9264b45b563594cbe953b0dc">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::HandleChildPiece</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a65b9f4e3cf9e00380b3162e8ec60769a">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#acf7193c4f9e38edd218457ecad2b11c8">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::insert</a>, <a href="#a5a8475c86206d8ba61d5ecd244871a2c">insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#af3b75c81f7695dc736c4cc9a02e1933a">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::RopePieceBTreeInterior</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a34ce37cfbd4b1f9af4c0048e7dcebca8">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::RopePieceBTreeInterior</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#ae1ad9b9cc567a789627f8230ddeee241">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::RopePieceBTreeLeaf</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a349144eaec23b627096e031c7c2b3425">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::split</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a5c8dc367b84e8104ed2e8062caa6c165">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::split</a> and <a href="#a02b6f427df62fc4de4b851a72ce6da66">split</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~RopePieceBTreeNode() {#a0216abc5f38c5491ca808b47c6ba88b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::~RopePieceBTreeNode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Destroy() {#a28686a28e1db673c0422c0cabd529373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RopePieceBTreeNode::Destroy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a818b36cd754cef2ffba33952d59076dd">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::erase</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a5deb480c9ba43cf135e1291b07841a92">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::~RopePieceBTreeInterior</a>.</p>

</div>
</div>

### erase() {#a0ebe00475d51e2c28cf5dcd1e260afa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RopePieceBTreeNode::erase (unsigned Offset, unsigned NumBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>erase - Remove NumBytes from this node at the specified offset.</p>


<p>We are guaranteed that there is a split at Offset.</p>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a65789943b6e154b98f662c1e2d882c82">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a818b36cd754cef2ffba33952d59076dd">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::erase</a>.</p>

</div>
</div>

### insert() {#a5a8475c86206d8ba61d5ecd244871a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode * RopePieceBTreeNode::insert (unsigned Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> &amp; R)</td>
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


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a469f9d8881255bab80c4a1cf69696f0f">RopePieceBTreeNode</a> and <a href="#a65789943b6e154b98f662c1e2d882c82">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a65b9f4e3cf9e00380b3162e8ec60769a">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#acf7193c4f9e38edd218457ecad2b11c8">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::insert</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a5c8dc367b84e8104ed2e8062caa6c165">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::split</a>.</p>

</div>
</div>

### isLeaf() {#a509afbe923622193704c25b43010763a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RewriteRope.cpp}::RopePieceBTreeNode::isLeaf ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Reference <a href="#a561c6bd84db78f8d3e68d4b85db67ea9">IsLeaf</a>.</p>


<p>Referenced by <a href="#a469f9d8881255bab80c4a1cf69696f0f">RopePieceBTreeNode</a>.</p>

</div>
</div>

### size() {#a65789943b6e154b98f662c1e2d882c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RewriteRope.cpp}::RopePieceBTreeNode::size ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Reference <a href="#ae3581c932c9c8f1e289bc772ba5dc0c0">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a818b36cd754cef2ffba33952d59076dd">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::erase</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a838a0abe15a9d3a9a65575766ca82e07">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::erase</a>, <a href="#a0ebe00475d51e2c28cf5dcd1e260afa5">erase</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a65b9f4e3cf9e00380b3162e8ec60769a">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#acf7193c4f9e38edd218457ecad2b11c8">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::insert</a>, <a href="#a5a8475c86206d8ba61d5ecd244871a2c">insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a349144eaec23b627096e031c7c2b3425">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::split</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a5c8dc367b84e8104ed2e8062caa6c165">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::split</a> and <a href="#a02b6f427df62fc4de4b851a72ce6da66">split</a>.</p>

</div>
</div>

### split() {#a02b6f427df62fc4de4b851a72ce6da66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode * RopePieceBTreeNode::split (unsigned Offset)</td>
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


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a469f9d8881255bab80c4a1cf69696f0f">RopePieceBTreeNode</a> and <a href="#a65789943b6e154b98f662c1e2d882c82">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a349144eaec23b627096e031c7c2b3425">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::split</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### IsLeaf {#a561c6bd84db78f8d3e68d4b85db67ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RewriteRope.cpp}::RopePieceBTreeNode::IsLeaf</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsLeaf - True if this is an instance of <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a>, false if it is an instance of <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior">RopePieceBTreeInterior</a>.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Referenced by <a href="#a509afbe923622193704c25b43010763a">isLeaf</a> and <a href="#a469f9d8881255bab80c4a1cf69696f0f">RopePieceBTreeNode</a>.</p>

</div>
</div>

### Size {#ae3581c932c9c8f1e289bc772ba5dc0c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size - This is the number of bytes of file this node (including any potential children) covers.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a9eff93ffbbf483da5d779d08e2d84ac8">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::clear</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a818b36cd754cef2ffba33952d59076dd">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::erase</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a838a0abe15a9d3a9a65575766ca82e07">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::erase</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a1282a6c0c36003b598a31f7c1179eb69">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::FullRecomputeSizeLocally</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#af5d51380f73522f3b54302131ee48354">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::FullRecomputeSizeLocally</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a65b9f4e3cf9e00380b3162e8ec60769a">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#acf7193c4f9e38edd218457ecad2b11c8">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a34ce37cfbd4b1f9af4c0048e7dcebca8">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::RopePieceBTreeInterior</a>, <a href="#a65789943b6e154b98f662c1e2d882c82">size</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a5c8dc367b84e8104ed2e8062caa6c165">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::split</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
