---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RopePieceBTreeLeaf` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> - Directly manages up to '2*WidthFactor' <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> nodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1ad9b9cc567a789627f8230ddeee241">RopePieceBTreeLeaf</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb8ce10e3aaaded35e04b7e37a6f803">~RopePieceBTreeLeaf</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b5de49a36c6fb4157c438eb369a231">isFull</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eff93ffbbf483da5d779d08e2d84ac8">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Remove all rope pieces from this leaf. <a href="#a9eff93ffbbf483da5d779d08e2d84ac8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ba074a7cab54528571c55277cf48e97">getNumPieces</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7792068e46155919bc78070c764ba2a">getPiece</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3520748e2347e3c20db12586f6667590">getNextLeafInOrder</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc65a9368ed57d8021af418102ec88c">insertAfterLeafInOrder</a> (RopePieceBTreeLeaf *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b065d41d05b2fc97a36d08f64e47889">removeFromLeafInOrder</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d51380f73522f3b54302131ee48354">FullRecomputeSizeLocally</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FullRecomputeSizeLocally - This method recomputes the 'Size' field by summing the size of all RopePieces. <a href="#af5d51380f73522f3b54302131ee48354">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c8dc367b84e8104ed2e8062caa6c165">split</a> (unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>split - Split the range containing the specified offset so that we are guaranteed that there is a place to do an insertion at the specified offset. <a href="#a5c8dc367b84e8104ed2e8062caa6c165">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf7193c4f9e38edd218457ecad2b11c8">insert</a> (unsigned Offset, const RopePiece &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insert - Insert the specified ropepiece into this tree node at the specified offset. <a href="#acf7193c4f9e38edd218457ecad2b11c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838a0abe15a9d3a9a65575766ca82e07">erase</a> (unsigned Offset, unsigned NumBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>erase - Remove NumBytes from this node at the specified offset. <a href="#a838a0abe15a9d3a9a65575766ca82e07">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1e46bfb3b581c7ba44c08dbf436fad4">NumPieces</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NumPieces - This holds the number of rope pieces currently active in the Pieces array. <a href="#ad1e46bfb3b581c7ba44c08dbf436fad4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5730d96d5d30aebe76a1e4f1dc99ae9">Pieces</a>[2 *WidthFactor]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pieces - This tracks the file chunks currently in this leaf. <a href="#ae5730d96d5d30aebe76a1e4f1dc99ae9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f78b77fcb1a751416f2955cc12b4df">PrevLeaf</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NextLeaf - This is a pointer to the next leaf in the tree, allowing efficient in-order forward iteration of the tree without traversal. <a href="#ac9f78b77fcb1a751416f2955cc12b4df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f4a15b130f9ea229a2d93fdd44d6be7">NextLeaf</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f112cc839a156174e9aece8b339e68">classof</a> (const RopePieceBTreeNode *N)</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> - Directly manages up to '2*WidthFactor' <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> nodes.</p>


<p>This directly represents a chunk of the string with those RopePieces concatenated. Since this is a B+Tree, all values (in this case instances of <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a>) are stored in leaves like this. To make iteration over the leaves efficient, they maintain a singly linked list through the NextLeaf field. This allows the B+Tree forward iterator to be constant time for all increments.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RopePieceBTreeLeaf() {#ae1ad9b9cc567a789627f8230ddeee241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::RopePieceBTreeLeaf ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp/#aaaf8a617a854421722dff2700940de96">getCN</a>, <a href="#a3520748e2347e3c20db12586f6667590">getNextLeafInOrder</a>, <a href="#acf7193c4f9e38edd218457ecad2b11c8">insert</a> and <a href="#a8bc65a9368ed57d8021af418102ec88c">insertAfterLeafInOrder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RopePieceBTreeLeaf() {#a8cb8ce10e3aaaded35e04b7e37a6f803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::~RopePieceBTreeLeaf ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="#a9eff93ffbbf483da5d779d08e2d84ac8">clear</a> and <a href="#a8b065d41d05b2fc97a36d08f64e47889">removeFromLeafInOrder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a9eff93ffbbf483da5d779d08e2d84ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::clear ()</td>
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

<p>clear - Remove all rope pieces from this leaf.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#ae3581c932c9c8f1e289bc772ba5dc0c0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size</a>.</p>


<p>Referenced by <a href="#a8cb8ce10e3aaaded35e04b7e37a6f803">~RopePieceBTreeLeaf</a>.</p>

</div>
</div>

### erase() {#a838a0abe15a9d3a9a65575766ca82e07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RopePieceBTreeLeaf::erase (unsigned Offset, unsigned NumBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>erase - Remove NumBytes from this node at the specified offset.</p>


<p>We are guaranteed that there is a split at Offset.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2ba074a7cab54528571c55277cf48e97">getNumPieces</a>, <a href="#aa7792068e46155919bc78070c764ba2a">getPiece</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#ae3581c932c9c8f1e289bc772ba5dc0c0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a65789943b6e154b98f662c1e2d882c82">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::size</a> and <a href="/web-llvm/docs/api/structs/llvm/ropepiece/#ae73820aec7ee77100f5b9af4443890aa">llvm::RopePiece::size</a>.</p>

</div>
</div>

### FullRecomputeSizeLocally() {#af5d51380f73522f3b54302131ee48354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::FullRecomputeSizeLocally ()</td>
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

<p>FullRecomputeSizeLocally - This method recomputes the 'Size' field by summing the size of all RopePieces.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="#a2ba074a7cab54528571c55277cf48e97">getNumPieces</a>, <a href="#aa7792068e46155919bc78070c764ba2a">getPiece</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#ae3581c932c9c8f1e289bc772ba5dc0c0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#ac323732b9264b45b563594cbe953b0dc">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::HandleChildPiece</a> and <a href="#acf7193c4f9e38edd218457ecad2b11c8">insert</a>.</p>

</div>
</div>

### getNextLeafInOrder() {#a3520748e2347e3c20db12586f6667590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RopePieceBTreeLeaf * anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::getNextLeafInOrder ()</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Reference <a href="#ae1ad9b9cc567a789627f8230ddeee241">RopePieceBTreeLeaf</a>.</p>

</div>
</div>

### getNumPieces() {#a2ba074a7cab54528571c55277cf48e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::getNumPieces ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Referenced by <a href="#a838a0abe15a9d3a9a65575766ca82e07">erase</a>, <a href="#af5d51380f73522f3b54302131ee48354">FullRecomputeSizeLocally</a>, <a href="#aa7792068e46155919bc78070c764ba2a">getPiece</a> and <a href="#acf7193c4f9e38edd218457ecad2b11c8">insert</a>.</p>

</div>
</div>

### getPiece() {#aa7792068e46155919bc78070c764ba2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RopePiece &amp; anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::getPiece (unsigned i)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a2ba074a7cab54528571c55277cf48e97">getNumPieces</a>.</p>


<p>Referenced by <a href="#a838a0abe15a9d3a9a65575766ca82e07">erase</a>, <a href="#af5d51380f73522f3b54302131ee48354">FullRecomputeSizeLocally</a> and <a href="#acf7193c4f9e38edd218457ecad2b11c8">insert</a>.</p>

</div>
</div>

### insert() {#acf7193c4f9e38edd218457ecad2b11c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode * RopePieceBTreeLeaf::insert (unsigned Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>insert - Insert the specified ropepiece into this tree node at the specified offset.</p>


<p>insert - Insert the specified <a href="/web-llvm/docs/api/structs/llvm/ropepiece">RopePiece</a> into this tree node at the specified offset.</p>


<p>The offset is relative, so "0" is the start of the node.</p>


<p>If there is no space in this subtree for the extra piece, the extra tree node is returned and must be inserted into a parent.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af5d51380f73522f3b54302131ee48354">FullRecomputeSizeLocally</a>, <a href="#a2ba074a7cab54528571c55277cf48e97">getNumPieces</a>, <a href="#aa7792068e46155919bc78070c764ba2a">getPiece</a>, <a href="#acf7193c4f9e38edd218457ecad2b11c8">insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a5a8475c86206d8ba61d5ecd244871a2c">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::insert</a>, <a href="#a8bc65a9368ed57d8021af418102ec88c">insertAfterLeafInOrder</a>, <a href="#a54b5de49a36c6fb4157c438eb369a231">isFull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#ae1ad9b9cc567a789627f8230ddeee241">RopePieceBTreeLeaf</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#ae3581c932c9c8f1e289bc772ba5dc0c0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a65789943b6e154b98f662c1e2d882c82">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::size</a>, <a href="/web-llvm/docs/api/structs/llvm/ropepiece/#ae73820aec7ee77100f5b9af4443890aa">llvm::RopePiece::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a4ba733354167c4801fb98506f22a6c3ca4a2ee1f78a24b36d2981e78ec567d4f0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::WidthFactor</a>.</p>


<p>Referenced by <a href="#acf7193c4f9e38edd218457ecad2b11c8">insert</a>.</p>

</div>
</div>

### insertAfterLeafInOrder() {#a8bc65a9368ed57d8021af418102ec88c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::insertAfterLeafInOrder (<a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf">RopePieceBTreeLeaf</a> * Node)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae1ad9b9cc567a789627f8230ddeee241">RopePieceBTreeLeaf</a>.</p>


<p>Referenced by <a href="#acf7193c4f9e38edd218457ecad2b11c8">insert</a>.</p>

</div>
</div>

### isFull() {#a54b5de49a36c6fb4157c438eb369a231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::isFull ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a4ba733354167c4801fb98506f22a6c3ca4a2ee1f78a24b36d2981e78ec567d4f0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::WidthFactor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#ac323732b9264b45b563594cbe953b0dc">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::HandleChildPiece</a> and <a href="#acf7193c4f9e38edd218457ecad2b11c8">insert</a>.</p>

</div>
</div>

### removeFromLeafInOrder() {#a8b065d41d05b2fc97a36d08f64e47889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::removeFromLeafInOrder ()</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>Referenced by <a href="#a8cb8ce10e3aaaded35e04b7e37a6f803">~RopePieceBTreeLeaf</a>.</p>

</div>
</div>

### split() {#a5c8dc367b84e8104ed2e8062caa6c165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeNode * RopePieceBTreeLeaf::split (unsigned Offset)</td>
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


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a5a8475c86206d8ba61d5ecd244871a2c">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a469f9d8881255bab80c4a1cf69696f0f">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::RopePieceBTreeNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#ae3581c932c9c8f1e289bc772ba5dc0c0">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::Size</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode/#a65789943b6e154b98f662c1e2d882c82">anonymous{RewriteRope.cpp}::RopePieceBTreeNode::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NextLeaf {#a5f4a15b130f9ea229a2d93fdd44d6be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeLeaf* anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::NextLeaf = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>

</div>
</div>

### NumPieces {#ad1e46bfb3b581c7ba44c08dbf436fad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::NumPieces = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NumPieces - This holds the number of rope pieces currently active in the Pieces array.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>

</div>
</div>

### Pieces {#ae5730d96d5d30aebe76a1e4f1dc99ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePiece anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::Pieces[2 *WidthFactor]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pieces - This tracks the file chunks currently in this leaf.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>

</div>
</div>

### PrevLeaf {#ac9f78b77fcb1a751416f2955cc12b4df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RopePieceBTreeLeaf** anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::PrevLeaf = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NextLeaf - This is a pointer to the next leaf in the tree, allowing efficient in-order forward iteration of the tree without traversal.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a32f112cc839a156174e9aece8b339e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreenode">RopePieceBTreeNode</a> * N)</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/support/rewriterope-cpp">RewriteRope.cpp</a>.</p>


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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
