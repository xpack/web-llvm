---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ilist-detail/iterator-parent-access
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `iterator_parent_access` Class Template Reference

<p>Mixin class used to add a <em>getNodeParent()</em> function to iterators iff the list uses <em><a href="/web-llvm/docs/api/structs/llvm/ilist-parent">ilist_parent</a></em>, calling through to the node's <em><a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent()</a></em>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class IteratorTy, class ParentTy, bool IsConst&gt;
class llvm::ilist_detail::iterator_parent_access&lt;IteratorTy, ParentTy, IsConst&gt; { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-iterator">ilist_iterator&lt;OptionsT, IsReverse, IsConst&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator for intrusive lists based on <a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a>. <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-iterator-w-bits">ilist_iterator_w_bits&lt;OptionsT, IsReverse, IsConst&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator for intrusive lists based on <a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a>. <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator-w-bits/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Mixin class used to add a <em>getNodeParent()</em> function to iterators iff the list uses <em><a href="/web-llvm/docs/api/structs/llvm/ilist-parent">ilist_parent</a></em>, calling through to the node's <em><a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent()</a></em>.</p>


<p>For more details see <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a></em>.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-iterator-h">ilist_iterator.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
