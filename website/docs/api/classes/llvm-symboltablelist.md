---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/symboltablelist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SymbolTableList` Class Template Reference

<p>List that automatically updates parent links and symbol tables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T, typename... Args&gt;
class llvm::SymbolTableList&lt;T, Args&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/symboltablelisttraits-h">llvm/IR/SymbolTableListTraits.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist-impl">iplist_impl&lt;IntrusiveListT, TraitsT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around an intrusive list with callbacks and non-intrusive ownership. <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>List that automatically updates parent links and symbol tables.</p>


<p>When nodes are inserted into and removed from this list, the associated symbol table will be automatically updated. Similarly, parent links get updated automatically.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/symboltablelisttraits-h">SymbolTableListTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
