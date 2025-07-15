---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/domtreebuilder/semincainfo/inforec
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InfoRec` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DomTreeBuilder::SemiNCAInfo::InfoRec { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">llvm/Support/GenericDomTreeConstruction.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3bfb4f61599f17708e91db1a0c2be6">DFSNum</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e6152fd055f0d00d6d6c1386bf3fd92">Parent</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf7afef13861e3f6ce5dc5c4ba63d20">Semi</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b23e8ba215f9241cffa0f3c9c351c8b">Label</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a5669fb284cfbf3893c2be26690f5d383">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6452d57b10c414e7bcc84418ce8fc609">IDom</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684f9c7cd717372292ce444834f090ea">ReverseChildren</a></td>
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


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### DFSNum {#aea3bfb4f61599f17708e91db1a0c2be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::DFSNum = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aeeca9e1d5c151829946fa95f9b9b30c7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>.</p>

</div>
</div>

### IDom {#a6452d57b10c414e7bcc84418ce8fc609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodePtr llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::IDom = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#acf1f2289b1f5ffbdf55e3f5ac555fed8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::attachNewSubtree</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a09cf9d5143816f847afdde1cf03cebfe">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getIDom</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a6ab30bb387a6e7086235e9ff7ad01941">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::reattachExistingSubtree</a>.</p>

</div>
</div>

### Label {#a3b23e8ba215f9241cffa0f3c9c351c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::Label = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4d03a4fddccb0dc066cb7195003db24e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::eval</a>.</p>

</div>
</div>

### Parent {#a8e6152fd055f0d00d6d6c1386bf3fd92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::Parent = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4d03a4fddccb0dc066cb7195003db24e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::eval</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>.</p>

</div>
</div>

### ReverseChildren {#a684f9c7cd717372292ce444834f090ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 4&gt; llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::ReverseChildren</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### Semi {#a7cf7afef13861e3f6ce5dc5c4ba63d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InfoRec::Semi = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4d03a4fddccb0dc066cb7195003db24e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::eval</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
