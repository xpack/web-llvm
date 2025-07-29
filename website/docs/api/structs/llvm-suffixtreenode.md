---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/suffixtreenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SuffixTreeNode` Struct

<p>A node in a suffix tree which represents a substring or suffix. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SuffixTreeNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">llvm/Support/SuffixTreeNode.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode">SuffixTreeInternalNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/suffixtreeleafnode">SuffixTreeLeafNode</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeKind { <a href="#add485021cba74f84f545a03c2deb6db3">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81101451dd797327456c73527a6e440b">SuffixTreeNode</a> (NodeKind Kind, unsigned StartIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c39a86a8a3f647d11979a1673a5df5">~SuffixTreeNode</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#add485021cba74f84f545a03c2deb6db3">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29aabba4cb1896a6fe8105e057f01d91">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9275db494732cf0988a1547c93420de2">getStartIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90024f4af921f97f605e44d44ce9f75">getEndIdx</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a313f5d2a493bd19ab5f45bb7bc75ec1b">getLeftLeafIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746c7e9598d369801d5d5de0bc9797ff">getRightLeafIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb4b3d19d24fb4fbc75f79f39b2e1d1d">setLeftLeafIdx</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the index of the left most leaf node of this node to <span class="doxyComputerOutput">Idx</span>. <a href="#abb4b3d19d24fb4fbc75f79f39b2e1d1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4339e85622b27800a2377f11bac448">setRightLeafIdx</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the index of the right most leaf node of this node to <span class="doxyComputerOutput">Idx</span>. <a href="#a7a4339e85622b27800a2377f11bac448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d2939d64e268faf36ff88c09d1a59ec">incrementStartIdx</a> (unsigned Inc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance this node's StartIdx by <span class="doxyComputerOutput">Inc</span>. <a href="#a0d2939d64e268faf36ff88c09d1a59ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a059f8fe4042aa575b538abdb731392">setConcatLen</a> (unsigned Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the length of the string from the root to this node to <span class="doxyComputerOutput">Len</span>. <a href="#a2a059f8fe4042aa575b538abdb731392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8223ad595580e9b1004f565a43ba4c20">getConcatLen</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#add485021cba74f84f545a03c2deb6db3">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90d54a4eae8b8ae3c2d07cfdf06cd31b">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe53a105cf259056b284d858bd19bb5b">StartIdx</a> = <a href="#a9038deca521822084ac798637368c94e">EmptyIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The start index of this node's substring in the main string. <a href="#abe53a105cf259056b284d858bd19bb5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2734d6d63a72ae6f68c3e3c8ab6f47">ConcatLen</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The length of the string formed by concatenating the edge labels from the root to this node. <a href="#a5e2734d6d63a72ae6f68c3e3c8ab6f47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae690b7609ccab3a4a39ecc95403f1644">LeftLeafIdx</a> = <a href="#a9038deca521822084ac798637368c94e">EmptyIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These two indices give a range of indices for its leaf descendants. <a href="#ae690b7609ccab3a4a39ecc95403f1644">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9c0cab6fab6afb4c0035abf31120cb">RightLeafIdx</a> = <a href="#a9038deca521822084ac798637368c94e">EmptyIdx</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9038deca521822084ac798637368c94e">EmptyIdx</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an undefined index in the suffix tree. <a href="#a9038deca521822084ac798637368c94e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A node in a suffix tree which represents a substring or suffix.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### NodeKind {#add485021cba74f84f545a03c2deb6db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::SuffixTreeNode::NodeKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST_Leaf<a id="add485021cba74f84f545a03c2deb6db3ad1b1b9b5c752b94811f35b42dd4f48fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST_Internal<a id="add485021cba74f84f545a03c2deb6db3a1c5cd656d7af113d4cb72dc8046dc1ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SuffixTreeNode() {#a81101451dd797327456c73527a6e440b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SuffixTreeNode::SuffixTreeNode (<a href="#add485021cba74f84f545a03c2deb6db3">NodeKind</a> Kind, unsigned StartIdx)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode/#a945ed42e87aca83910a3f79960d00eb7">llvm::SuffixTreeInternalNode::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/suffixtreeleafnode/#aad2e2f2432231920dd40153553db08fd">llvm::SuffixTreeLeafNode::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode/#aee4f3eefe02d5d475ffb06b54b7da9ed">llvm::SuffixTreeInternalNode::SuffixTreeInternalNode</a> and <a href="/web-llvm/docs/api/structs/llvm/suffixtreeleafnode/#af5c90c6f297ac5c895a657cc9f09a948">llvm::SuffixTreeLeafNode::SuffixTreeLeafNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SuffixTreeNode() {#a67c39a86a8a3f647d11979a1673a5df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::SuffixTreeNode::~SuffixTreeNode ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getConcatLen() {#a8223ad595580e9b1004f565a43ba4c20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SuffixTreeNode::getConcatLen ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the length of the string from the root to this node.</p></dd>
</dl>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>

</div>
</div>

### getEndIdx() {#ad90024f4af921f97f605e44d44ce9f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::SuffixTreeNode::getEndIdx ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the end index of this node.</p></dd>
</dl>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

### getKind() {#a29aabba4cb1896a6fe8105e057f01d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeKind llvm::SuffixTreeNode::getKind ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

### getLeftLeafIdx() {#a313f5d2a493bd19ab5f45bb7bc75ec1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SuffixTreeNode::getLeftLeafIdx ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the index of this node's left most leaf node.</p></dd>
</dl>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>

</div>
</div>

### getRightLeafIdx() {#a746c7e9598d369801d5d5de0bc9797ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SuffixTreeNode::getRightLeafIdx ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the index of this node's right most leaf node.</p></dd>
</dl>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>

</div>
</div>

### getStartIdx() {#a9275db494732cf0988a1547c93420de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SuffixTreeNode::getStartIdx ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the start index of this node's substring in the entire string.</p></dd>
</dl>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode/#a05b664c3b910cb6d5cda2ba6b83b759c">llvm::SuffixTreeInternalNode::isRoot</a>.</p>

</div>
</div>

### incrementStartIdx() {#a0d2939d64e268faf36ff88c09d1a59ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SuffixTreeNode::incrementStartIdx (unsigned Inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance this node's StartIdx by <span class="doxyComputerOutput">Inc</span>.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>

</div>
</div>

### setConcatLen() {#a2a059f8fe4042aa575b538abdb731392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SuffixTreeNode::setConcatLen (unsigned Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the length of the string from the root to this node to <span class="doxyComputerOutput">Len</span>.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>

</div>
</div>

### setLeftLeafIdx() {#abb4b3d19d24fb4fbc75f79f39b2e1d1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SuffixTreeNode::setLeftLeafIdx (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the index of the left most leaf node of this node to <span class="doxyComputerOutput">Idx</span>.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>

</div>
</div>

### setRightLeafIdx() {#a7a4339e85622b27800a2377f11bac448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SuffixTreeNode::setRightLeafIdx (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the index of the right most leaf node of this node to <span class="doxyComputerOutput">Idx</span>.</p>

<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtreenode-cpp">SuffixTreeNode.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ConcatLen {#a5e2734d6d63a72ae6f68c3e3c8ab6f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuffixTreeNode::ConcatLen = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The length of the string formed by concatenating the edge labels from the root to this node.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

### Kind {#a90d54a4eae8b8ae3c2d07cfdf06cd31b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeKind llvm::SuffixTreeNode::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

### LeftLeafIdx {#ae690b7609ccab3a4a39ecc95403f1644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuffixTreeNode::LeftLeafIdx = <a href="#a9038deca521822084ac798637368c94e">EmptyIdx</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These two indices give a range of indices for its leaf descendants.</p>


<p>Imagine drawing a tree on paper and assigning a unique index to each leaf node in monotonically increasing order from left to right. This way of numbering the leaf nodes allows us to associate a continuous range of indices with each internal node. For example, if a node has leaf descendants with indices i, i+1, ..., j, then its LeftLeafIdx is i and its RightLeafIdx is j. These indices are for LeafNodes in the <a href="/web-llvm/docs/api/classes/llvm/suffixtree">SuffixTree</a> class, which is constructed using post-order depth-first traversal.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

### RightLeafIdx {#a0f9c0cab6fab6afb4c0035abf31120cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuffixTreeNode::RightLeafIdx = <a href="#a9038deca521822084ac798637368c94e">EmptyIdx</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

### StartIdx {#abe53a105cf259056b284d858bd19bb5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SuffixTreeNode::StartIdx = <a href="#a9038deca521822084ac798637368c94e">EmptyIdx</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The start index of this node's substring in the main string.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### EmptyIdx {#a9038deca521822084ac798637368c94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SuffixTreeNode::EmptyIdx = -1</td>
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

<p>Represents an undefined index in the suffix tree.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtreenode-h">SuffixTreeNode.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode/#a05b664c3b910cb6d5cda2ba6b83b759c">llvm::SuffixTreeInternalNode::isRoot</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
