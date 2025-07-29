---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/domtreebuilder/semincainfo/insertioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InsertionInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::DomTreeBuilder::SemiNCAInfo::InsertionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">llvm/Support/GenericDomTreeConstruction.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::priority_queue&lt; <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a>, 8 &gt;, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/insertioninfo/compare">Compare</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628a606cded13014b9f2ce9a42ead0d3">Bucket</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27475b6e0a6bbdd0a354f9aa8f0fc4b">Visited</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ab841529e1d6fd801bdeb291409119aef">TreeNodePtr</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96afdf4edb6595d905b097dd2c95bf02">Affected</a></td>
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


<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Affected {#a96afdf4edb6595d905b097dd2c95bf02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TreeNodePtr, 8&gt; llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertionInfo::Affected</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### Bucket {#a628a606cded13014b9f2ce9a42ead0d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::priority_queue&lt;TreeNodePtr, SmallVector&lt;TreeNodePtr, 8&gt;, Compare&gt; llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertionInfo::Bucket</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

### Visited {#ab27475b6e0a6bbdd0a354f9aa8f0fc4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseSet&lt;TreeNodePtr, 8&gt; llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertionInfo::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
