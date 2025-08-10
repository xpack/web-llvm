---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/denseset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DenseSet` Class Template

<p>Implements a dense probed hash-table based set. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ValueT, typename ValueInfoT = DenseMapInfo&lt;ValueT&gt;&gt;
class llvm::DenseSet&lt;ValueT, ValueInfoT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl">DenseSetImpl&lt;ValueT, MapTy, ValueInfoT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a> and DenseSmallSet. <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT, typename ValueInfoT = DenseMapInfo&lt;ValueT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0be13de486f4477ca657b6f613674b2d">BaseT</a> = <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl">detail::DenseSetImpl</a>&lt; ValueT, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; ValueT, <a href="/web-llvm/docs/api/structs/llvm/detail/densesetempty">detail::DenseSetEmpty</a>, ValueInfoT, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetpair">detail::DenseSetPair</a>&lt; ValueT &gt; &gt;, ValueInfoT &gt;</td>
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

<p>Implements a dense probed hash-table based set.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">DenseSet.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BaseT {#a0be13de486f4477ca657b6f613674b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename ValueInfoT = DenseMapInfo&lt;ValueT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DenseSet&lt; ValueT, ValueInfoT &gt;::BaseT = 
      detail::DenseSetImpl&lt;ValueT,
                           DenseMap&lt;ValueT, detail::DenseSetEmpty, ValueInfoT,
                                    detail::DenseSetPair&lt;ValueT&gt;&gt;,
                           ValueInfoT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">DenseSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">DenseSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
