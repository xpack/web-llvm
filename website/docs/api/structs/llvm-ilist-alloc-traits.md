---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ilist-alloc-traits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ilist_alloc_traits` Struct Template

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> delete by default for iplist and ilist. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename NodeTy&gt;
struct llvm::ilist_alloc_traits&lt;NodeTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-h">llvm/ADT/ilist.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ilist-node-traits">ilist_node_traits&lt;NodeTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A fragment for template traits for intrusive list that provides default node related operations. <a href="/web-llvm/docs/api/structs/llvm/ilist-node-traits/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8777b33ad86e229baccdc17baf8ca32c">deleteNode</a> (NodeTy *V)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> delete by default for iplist and ilist.</p>


<p>Specialize this to get different behaviour for ownership-related API. (If you really want ownership semantics, consider using std::list or building something like <em><a href="/web-llvm/docs/api/namespaces/llvm/#af7dca6236dc4685d19780a150377258d">BumpPtrList</a></em>.)</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/structs/llvm/ilist-noalloc-traits">ilist_noalloc_traits</a></p></dd>
</dl>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-h">ilist.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### deleteNode() {#a8777b33ad86e229baccdc17baf8ca32c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ilist_alloc_traits::deleteNode (NodeTy * V)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-h">ilist.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ilist-alloc-traits-ae18c05c9a42639c0b95d01fb38d55c7/#aa14d1c8173fa2f191a8608dec3e1c9b1">llvm::ilist_alloc_traits&lt; Instruction &gt;::deleteNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-h">ilist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
