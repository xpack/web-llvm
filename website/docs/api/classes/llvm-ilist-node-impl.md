---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ilist-node-impl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ilist_node_impl` Class Template

<p>Implementation for an ilist node. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class OptionsT&gt;
class llvm::ilist_node_impl&lt;OptionsT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">llvm/ADT/ilist_node.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OptionsT::node_base_type</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access">node_parent_access&lt;NodeTy, ParentTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mixin base class that is used to add <em><a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">getParent()</a></em> and <em><a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#ad4cf5562c8c361844baaeb6a8b5cfb7e">setParent(ParentTy*)</a></em> methods to <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl">ilist_node_impl</a></em> iff <em><a href="/web-llvm/docs/api/structs/llvm/ilist-parent">ilist_parent</a></em> has been set in the list options. <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-sentinel">ilist_sentinel&lt;OptionsT&gt;</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69f57da2cbacc606919dd017badf7da1">self_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/ilist-select-iterator-type">ilist_select_iterator_type</a>&lt; OptionsT::has_iterator_bits, OptionsT, false, false &gt;::type</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a062ff5e5271611eab47e721ed04fb5e6">const_self_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/ilist-select-iterator-type">ilist_select_iterator_type</a>&lt; OptionsT::has_iterator_bits, OptionsT, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;::type</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad170cf283717735d286c0d6975a9ccfa">reverse_self_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/ilist-select-iterator-type">ilist_select_iterator_type</a>&lt; OptionsT::has_iterator_bits, OptionsT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;::type</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d9f729fc5a6da4e689f24e7b28fc37e">const_reverse_self_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/ilist-select-iterator-type">ilist_select_iterator_type</a>&lt; OptionsT::has_iterator_bits, OptionsT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;::type</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a96d7c0593987da01d3f0a607ba567a47">value_type</a> = typename OptionsT::value_type</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab8aaea286ae1bc2b27a4c349713d16ec">node_base_type</a> = typename OptionsT::node_base_type</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7510f12afceb19916944cccac6fdb14">list_base_type</a> = typename OptionsT::list_base_type</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a998722253907efb4c0db48a3457f7f01">ilist_detail::NodeAccess</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad126b29d44ad30c278ca5c42d499c5aa">ilist_sentinel&lt; OptionsT &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3fc2c089c25c6d4aa4cdf95d2aaf7eb4">ilist_detail::node_parent_access&lt; ilist_node_impl&lt; OptionsT &gt;, typename OptionsT::parent_ty &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a814e97d3e309fedf1d5cc1a4ad8d2dda">ilist_iterator&lt; OptionsT, false, false &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac5de4eee5b1574abe3b5e9ff087bcbd7">ilist_iterator&lt; OptionsT, false, true &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3aa8fa1e78e76a3bdfec6a99669777ea">ilist_iterator&lt; OptionsT, true, false &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a40d0d6ad945e02d10d7afb1c7faf055c">ilist_iterator&lt; OptionsT, true, true &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06b78b3220c663f87a4436de5550cd22">ilist_iterator_w_bits&lt; OptionsT, false, false &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace634de989dc22363ab0195f6988a81d">ilist_iterator_w_bits&lt; OptionsT, false, true &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac9ba0784a812aedea9acef05a9b98815">ilist_iterator_w_bits&lt; OptionsT, true, false &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af83f3fb0b8a9e76ab3943095d44365e0">ilist_iterator_w_bits&lt; OptionsT, true, true &gt;</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a01609a46da35cca87e8ada6f7de40d23">ilist_node_impl</a> ()=default</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a69f57da2cbacc606919dd017badf7da1">self_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af719fc783be6589465137d997701a432">getIterator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a062ff5e5271611eab47e721ed04fb5e6">const_self_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad15186d74661a6fb15b986b4b204559d">getIterator</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad170cf283717735d286c0d6975a9ccfa">reverse_self_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad4bb544993573a6677d97cf5413110c7">getReverseIterator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a5d9f729fc5a6da4e689f24e7b28fc37e">const_reverse_self_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3048b72bb23d82c6468d251ac7404cb1">getReverseIterator</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0570092282570244c4d7af86003f0aa9">isSentinel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this is the sentinel node. <a href="#a0570092282570244c4d7af86003f0aa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl">ilist_node_impl</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa04b309a94cf8f37c90e9aeea242b77e">getPrev</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl">ilist_node_impl</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d9fccf1c26caaa5e19d9d08decf1e56">getNext</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl">ilist_node_impl</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acae0d912c873a3e551bd276c39956c30">getPrev</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl">ilist_node_impl</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab1a70f0a75ca2a2d56be7293c1ab8921">getNext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c8af91d7a6274a7caf60244b03754eb">setPrev</a> (ilist_node_impl *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OptionsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a460e37271b4df9defdddc12db903e543">setNext</a> (ilist_node_impl *N)</td>
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

<p>Implementation for an ilist node.</p>


<p>Templated on an appropriate <em><a href="/web-llvm/docs/api/structs/llvm/ilist-detail/node-options">ilist_detail::node_options</a></em>, usually computed by <em><a href="/web-llvm/docs/api/structs/llvm/ilist-detail/compute-node-options">ilist_detail::compute_node_options</a></em>.</p>


<p>This is a wrapper around <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node-base">ilist_node_base</a></em> whose main purpose is to provide type safety: you can't insert nodes of <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl">ilist_node_impl</a></em> into the wrong <em><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a></em> or <em>iplist</em>.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### const\_reverse\_self\_iterator {#a5d9f729fc5a6da4e689f24e7b28fc37e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ilist_node_impl&lt; OptionsT &gt;::const_reverse_self_iterator = 
      typename ilist_select_iterator_type&lt;OptionsT::has_iterator_bits, OptionsT,
                                          true, true&gt;::type</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### const\_self\_iterator {#a062ff5e5271611eab47e721ed04fb5e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ilist_node_impl&lt; OptionsT &gt;::const_self_iterator = 
      typename ilist_select_iterator_type&lt;OptionsT::has_iterator_bits, OptionsT,
                                          false, true&gt;::type</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### reverse\_self\_iterator {#ad170cf283717735d286c0d6975a9ccfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ilist_node_impl&lt; OptionsT &gt;::reverse_self_iterator = 
      typename ilist_select_iterator_type&lt;OptionsT::has_iterator_bits, OptionsT,
                                          true, false&gt;::type</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### self\_iterator {#a69f57da2cbacc606919dd017badf7da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ilist_node_impl&lt; OptionsT &gt;::self_iterator = 
      typename ilist_select_iterator_type&lt;OptionsT::has_iterator_bits, OptionsT,
                                          false, false&gt;::type</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### list\_base\_type {#ac7510f12afceb19916944cccac6fdb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ilist_node_impl&lt; OptionsT &gt;::list_base_type =  typename OptionsT::list_base_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### node\_base\_type {#ab8aaea286ae1bc2b27a4c349713d16ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ilist_node_impl&lt; OptionsT &gt;::node_base_type =  typename OptionsT::node_base_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### value\_type {#a96d7c0593987da01d3f0a607ba567a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ilist_node_impl&lt; OptionsT &gt;::value_type =  typename OptionsT::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ilist\_detail::node\_parent\_access&lt; ilist\_node\_impl&lt; OptionsT &gt;, typename OptionsT::parent\_ty &gt; {#a3fc2c089c25c6d4aa4cdf95d2aaf7eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access">ilist_detail::node_parent_access</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl">ilist_node_impl</a>&lt; OptionsT &gt;, typename OptionsT::parent_ty &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_detail::NodeAccess {#a998722253907efb4c0db48a3457f7f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/nodeaccess">ilist_detail::NodeAccess</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_iterator\_w\_bits&lt; OptionsT, false, false &gt; {#a06b78b3220c663f87a4436de5550cd22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator-w-bits">ilist_iterator_w_bits</a>&lt; OptionsT, false, false &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_iterator\_w\_bits&lt; OptionsT, false, true &gt; {#ace634de989dc22363ab0195f6988a81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator-w-bits">ilist_iterator_w_bits</a>&lt; OptionsT, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_iterator\_w\_bits&lt; OptionsT, true, false &gt; {#ac9ba0784a812aedea9acef05a9b98815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator-w-bits">ilist_iterator_w_bits</a>&lt; OptionsT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_iterator\_w\_bits&lt; OptionsT, true, true &gt; {#af83f3fb0b8a9e76ab3943095d44365e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator-w-bits">ilist_iterator_w_bits</a>&lt; OptionsT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_iterator&lt; OptionsT, false, false &gt; {#a814e97d3e309fedf1d5cc1a4ad8d2dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator">ilist_iterator</a>&lt; OptionsT, false, false &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_iterator&lt; OptionsT, false, true &gt; {#ac5de4eee5b1574abe3b5e9ff087bcbd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator">ilist_iterator</a>&lt; OptionsT, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_iterator&lt; OptionsT, true, false &gt; {#a3aa8fa1e78e76a3bdfec6a99669777ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator">ilist_iterator</a>&lt; OptionsT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_iterator&lt; OptionsT, true, true &gt; {#a40d0d6ad945e02d10d7afb1c7faf055c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator">ilist_iterator</a>&lt; OptionsT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### ilist\_sentinel&lt; OptionsT &gt; {#ad126b29d44ad30c278ca5c42d499c5aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-sentinel">ilist_sentinel</a>&lt; OptionsT &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### ilist\_node\_impl() {#a01609a46da35cca87e8ada6f7de40d23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ilist_node_impl&lt; OptionsT &gt;::ilist_node_impl ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIterator() {#af719fc783be6589465137d997701a432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">self_iterator llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aebae63f31076e8c0dfe153c45a730497">addAssumeNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a19dd673b5e34f3c83c6c17f780836bc7">addUnreachableAfterTryTables</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a38ff3df1feb7915dfda6303a34484534">llvm::GCNSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#aefcb18d60b47720b919eb6b0ce98b05e">allocateFrameInCaller</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a36c56da02f10d527ab7084e5d172d1d4">llvm::HexagonInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aa20f5e3d228e0f30d2f3c53c53cc6c93">llvm::AMDGPUCombinerHelper::applyFoldableFneg</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a420bedce165a865417db21cdc88307cb">BreakUpSubtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#aeb62f5a3d52d7c6110425de48f59ed69">canFallThroughTo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ad4acb872174d072853dcba1adb7c16d3">llvm::AAResults::canInstructionRangeModRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a435084f5e140c85f72921239385f9edb">canRenameUntilSecondLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#aab2eda4003703fcc548e36043debfafa">canSplitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2489602598b96c9729c75a25ab8ff4cb">llvm::cloneAndAdaptNoAliasScopes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a6766bb9d415c3d929afaa24877e14fc6">cloneCfiPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3c50b05be0be83e693f50b87284c76d6">llvm::MachineFunction::cloneMachineInstrBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a609c78a9c329baf4d3aa095a80784a4c">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::combineOperandOrigins</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ad7d79bd0b027705195d79619a1d0450a">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::combineOperandShadows</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a5982dea08cc92ad6fd8776a506980a69">llvm::MIRPrinter::convertCalledGlobals</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a0adb0a856adef09fd017379f4644ba4e">convertFSqrtDivIntoFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a125e2946cdcc7555d8f5c383681d7097">convertMetadataToAssumes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a5ccdf0465e957f46ac1241b63af00864">ConvertShiftToMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a1548d6cc07c1c5595817e73713d58a23">copyMustTailReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#aae3714d6fe11a1e8c559880caf67fbc7">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#ad623ba85ece2827b2a9c853e95ee24fc">createCoroSave</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#adc686ba917c4b589803df62f9a0c75d6">llvm::DbgLabelRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad399adefaffab058aa56567aa1b59df9">llvm::DbgVariableRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-promotememorytoregister-cpp-/#acce7135d82ed41802b7c4ccd9059d3db">anonymous{PromoteMemoryToRegister.cpp}::createDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ac438bed7ae6afbb9ff9e0be02099ad0f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab464550d233a70bf18d772d204549342">llvm::InstCombinerImpl::CreateNonTerminatorUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#af05ad96486c97ea7158a65507aaee0ef">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::createReplacementValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#a8c9ae0be5e6bcad90cdf141962a117f3">createRetBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#af36172c1f538b7305b44760997d5a3c2">llvm::OpenMPIRBuilder::createSections</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a50ee598578572bbfadfb9279f650cdd7">llvm::RandomIRBuilder::createStackMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a26d326912ec9ff7ea15f2b356f5d31eb">createTileStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aa12c0d3acb3f625ee09d2919907d4067">llvm::VPlan::createVPIRBasicBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad46652b66427679d9c221df6915019ca">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::discardEVLParameter</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#acde68625afdf845a15c3358956e34057">llvm::DbgMarker::dropOneDbgRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a7a4e4e4a8fa157eb9945d44717359bb1">llvm::ARMBaseInstrInfo::duplicate</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cd89ca702a817aac3a4521dd2462a2e">llvm::DuplicateInstructionsInSplitBetween</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#ad9c37680a58c2590f08d938aa1a44d6c">anonymous{CoroElide.cpp}::CoroIdElider::elideHeapAllocations</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a664aaf46532d6ebeed0dfeb704308d33">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a9199bb920d3966ef9c614a623c7af495">llvm::OpenMPIRBuilder::emitBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#afea2f73a2971b1c2238c0996efdb1201">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::emitClause</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/userlabel/#ada0f64f2cd5510902725c8a47d5bf56d">anonymous{LiveDebugVariables.cpp}::UserLabel::emitDebugLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a38c76eebc11caaa9225a4bfe146585a6">anonymous{LiveDebugVariables.cpp}::UserValue::emitDebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#ac05188b9f403d9279681683e2a7b3d3e">llvm::VLIWPacketizerList::endPacket</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a63540fe3243b44a62cb656c73274f8ac">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::ensureType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d6c4616e2c2cc90d58377868eda6102">llvm::examineCFlagsUse</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d3e8ce57fb65481a42b256d26c264d">llvm::expandDivision</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0154d60f04a5d8549b44635852557f0">llvm::expandRemainder</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#afa3ae93d47c5dcf2858522c9868301ca">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findAvailCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/dependencyanalysis-cpp/#aab3179ea6d16c5998772f644a2a205ac">findDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a9d0e45d07c65ef73adf90a69ca3ebedf">findInitTrampolineFromBB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-guardwidening-cpp-/#a0d69c80bfa592d9ac6901fa22f7ff405">anonymous{GuardWidening.cpp}::findInsertionPointForWideCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#adc8ca4d1d7106281e788558813399a48">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findLastSeenDefInCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a990710c9124f4c4183d029f678f8c13b">findLiveSetAtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#ab273671903c0baabbbf098a0a4581101">llvm::ARMBlockPlacement::fixBackwardsWLS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ad3259dc4dae742caac6c6e4f577d1760">foldInsSequenceIntoSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4dbcb044eda11161781dfbf3f007f04">llvm::InstCombinerImpl::foldPHIArgExtractValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a29028fb86efd0ff0ea01f243f47684fc">llvm::InstCombinerImpl::foldPHIArgInsertValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e4b18daaf5f20f1ade3a9f66b86d843">llvm::FoldReturnIntoUncondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a550ee33b5be6c859c443739649308721">foldSelectZeroOrMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a660392f54efb6a70e2b59a840ccf1728">getAllocaPos</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloop/#aa5d6d2568abd0f3161ac255b4c6e1f4c">llvm::MachineLoop::getBottomBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a6141f01c038a2c06c7b2e8f434aa81b6">llvm::MemoryAccess::getDefsIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a5910c0aae54b0639798fd96cc8450b45">llvm::MemoryAccess::getDefsIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#af9653b051f47859d60d83527d0460e87">llvm::MemoryAccess::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a0fc1bd8c18c606de91bfce96a9ce7b50">llvm::MemoryAccess::getIterator</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/valuetable/#a0f202a9387b6d7a60044c0ea986e7cb4">anonymous{GVNSink.cpp}::ValueTable::getMemoryUseOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a05eb84c8f630be406f61761013146574">getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aee3b49d7f15550d64c7db0e29a124c6d">llvm::slpvectorizer::BoUpSLP::getSpillCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a58bcd428c0ca38b723b8ef938868ec4a">llvm::coro::getSpillInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloop/#adfb3765b2827835823c1c55d12b33957">llvm::MachineLoop::getTopBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4cbd6aad6f6b93f79dc435feab77550e">HandleInlinedLandingPad</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aa1a6fbdf0a3311c7b9602dd67e46fef9">llvm::LiveIntervals::handleMoveIntoNewBundle</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a92756d26ffe5c46811ee48f629857ba2">llvm::objcarc::BottomUpPtrState::HandlePotentialUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a116742dc8bd808e796becf1166383f63">hasCallsBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a3a3a3183a327e1186dbe900032390ec6">hoist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab4d6b37c7f97bad2b1f441dc3fd43e0">llvm::hoistAllInstructionsInto</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aa3255071e8195c43058f7e265c54677f">llvm::SCEVExpander::hoistIVInc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedc31552ebf0ce116c665da44b4a97a5">hoistLockstepIdenticalDbgVariableRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a64bba3cf05c8cb1baa848483e7150830">hoistValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxloweralloca-cpp/#a76288e65bf2155a44597a9ffb783d25a">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregularizer-cpp/#a70c9d5004bb64ce7c4ed2dab4acda63b">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a8c02e0ea8aec7fa58b24b6d22f0e3e8e">llvm::VPRecipeBase::insertAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#aeda4df10362479b2eb3d6b12f895401f">llvm::sandboxir::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a8859e5e8cad5653b278964f47414fd84">llvm::VPRecipeBase::insertBefore</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a7c404b9b284d7d53f3aec00e776cd5b7">insertDAGNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#ae61c505ef5dc38733d7b12b91e545a44">insertDAGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5a6937fcd639ac78a93b48ab6624e957">llvm::DIBuilder::insertDbgAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#ad39cef6524b0757f3d47c5e988c20214">llvm::DbgMarker::insertDbgRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a4e3e46a5043b9376725624d0655d187a">llvm::DbgMarker::insertDbgRecordAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a9019e662ee1c0c04e06e9871650268c8">llvm::DIBuilder::insertDeclare</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a8b52fc13d6793d152a3d9dc210f5156e">llvm::sandboxir::Instruction::insertInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#ae3b43649c18ab9e63c1be61b93dd7031">insertLifetimeMarkersSurroundingCall</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a10aea73adf903930a8ce4c133dfa5a1e">llvm::SlotIndexes::insertMachineInstrInMaps</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a55bd6e17074a39a9aad2ee8cd6f541fb">llvm::SlotIndexes::insertMBBInMaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab994e75dc5cae892a87ae9a86d4b767a">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a8b2189b37dac8aba6dc3f5a39824d00b">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::insertReloads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3e3071be46334a57263e70548609d657">insertRelocationStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a8210289419425d82cf453d7b32bd2d2c">insertRematerializationStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a313dff6a75b3ae9c5c5d6802f3007a56">insertRememberRestorePair</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a953f3ddec823a0c7db75e73dbf550632">llvm::SIInstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#ad73240db48b2eda2b2ca2ce38530c552">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentMaskedLoadOrStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fcd2292dd9e51480a2f43d41acfe2">llvm::invertCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a55d78ed0d26d6a1cde6e30c6f43a5452">isCopyOfBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#acc7375926290b7d52cce5ef2c03505f7">llvm::GIMatchTableExecutor::isObviouslySafeToFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bca5709e8d5f8d45c9e46c51322e017">llvm::isSafeToLoadUnconditionally</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp/#ad1ace11555e6a74661cd750915d2c2f4">isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp/#a011daeefef283046fe04a47f46d857ef">isSafeToSinkLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f7c11444c9e7d7c1036ae1f049f4cee">llvm::isValidAssumeForContext</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a31dc649eb968f53e71376a708b40333f">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::isWaterInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a54ee101062ec8079d8d7fadafb29c511">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::isWaterInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#a22895e7a8fa9fc2f5a3306dd7aebbb33">jumpTableFollowsTB</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluebasicblock/#ga685b3eca9432cb6b80cc96dd54d025a3">LLVMInsertExistingBasicBlockAfterInsertBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a790c96adef17241b1ba4dbf475c3e57e">LowerNegateToMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a9f134722dec96eeaf23085a29b5da9f7">llvm::Loop::makeLoopInvariant</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/lowererbase/#a8e44a67be75da70df132c8683575d772">llvm::coro::LowererBase::makeSubFnCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ac388d17329447d2fd72ceabf79fefeba">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae2bd5329e5726d560529de68df90503c">llvm::CombinerHelper::matchFreezeOfSingleMaybePoisonOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue/#ac96558c87ecbcc96f020a0efcaade750">llvm::gvn::AvailableValue::MaterializeAdjustedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp/#a0c90ca0636305936b0f39e94b9702ec7">mayBeVisibleThroughUnwinding</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a91afe718c3cb2b248f39e1fd250ac91a">MayContainThrowingOrExitingCallAfterCB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af3c2dc75190645b72eee3c416cd14885">llvm::MachineBasicBlock::moveAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a64307c8cbf811329320f43f90c434c08">moveBBContents</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ac1fd6437bbfce263b87f01767d950ce5">llvm::BasicBlock::moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a25c2a6ee39d0d97dac2184e8bd942300">llvm::MachineBasicBlock::moveBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4972d73b274f1c9bb08ff314cba26522">llvm::moveInstructionsToTheEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4da36cb65ef881f12fe1d40a47223a61">MoveVPNOTBeforeFirstUser</a>, <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a5d0250802fc18f3e96531f43c6280c18">llvm::InstDeleterIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/shuffleblockstrategy/#a3bad39b7c7fd81aa15068f082eb6f0a6">llvm::ShuffleBlockStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8b569b7040c15c2e2233b3064caa8f4f">llvm::RandomIRBuilder::newSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a9ace593776041510de450a2eccc56eeb">operandWithNewAddressSpaceOrCreatePoison</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a3c38fd13d9fa38356cca5ecdf7cfba23">optimizeSQRT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a4839bb9ff9510a0c0bda1e41cabe4714">placeSplitBlockCarefully</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac06e19670a4cb86b0c885cf67bdb1bc4">llvm::JumpThreadingPass::processImpliedCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ad47460e620c33c83309f749ea8f34c6b">processSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ace24fe825742577e78df32f725ad7b26">processSIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a914ea1510476a800508ae70d159bd8c0">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::processStaticAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae1f1125c20c109a1dedb0cafbb501c22">programUndefinedIfUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9469fd548994812c12e4c10d42ec82a3">llvm::promoteCallWithIfThenElse</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a664436e80e651ce40c1abcf063d58fa9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::promoteLoadFromStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#aeae677889401c02a8def9a0508e858c7">reinsertVectorIndexAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a0650e5c5d027b7ef00c23a7921c114db">rematerializeLiveValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a4082748189dc3460ea7130cd8d7790b5">llvm::MemoryDependenceResults::removeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a98eceec46c49f571b3413d3f91e31e10">llvm::DbgMarker::removeMarker</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a453e4d014fa115aebac6e1416cf7d64c">llvm::SlotIndexes::repairIndexesInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a97741acf9b0e38ab508c939d99e53767">ReplaceCallWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#a1ad5c109b5218ec1d5f5fcd6390636ba">replaceConstantExprOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8b22bf92719f6baa98dcfe7e99bd5389">replaceCoroEndAsync</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a23239d94380595765d9caf8bae661d7a">replaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a645f6e970e94d7ca51922b3932338f51">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceRemWithNumeratorOrZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8a96c9b1143670a73852464de9950e8e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceSRemWithURem</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ad87f4b76b6846d029880d6b9012a7e69">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad75372cc26ff6f641159aed90d5fc11e">reuseTableCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kernelrewriter/#a2e7a99d381fd8c317ade905833ae3138">anonymous{ModuloSchedule.cpp}::KernelRewriter::rewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/materializationutils-cpp/#aba618c16a34739af0506ba1082d209a3">rewriteMaterializableInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass/#aa6e4c71c550683bb7d117491b717e2d1">anonymous{PassBuilder.cpp}::TriggerVerifierErrorPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/finalizeisel-cpp/#a6395b072c4fb781dca4789de8aba1f55">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxallocahoisting-cpp-/nvptxallocahoisting/#a3e0401219219142d6d4aa7cb0859afc7">anonymous{NVPTXAllocaHoisting.cpp}::NVPTXAllocaHoisting::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#ad69716246dabb743839cafceb902ef46">llvm::RewriteStatepointsForGC::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/cfifixup/#a7d1808859a4351ab820d5fa17a0e2685">llvm::CFIFixup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a984df453a762468ca683f6e83cf50e17">runPass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fa258f0e297563fcec4bb619d2a759">llvm::MachineFunction::salvageCopySSAImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a16c5883e0be30cbd188280eec8941f6e">llvm::VPBuilder::setInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63f2a772f8b7a673be8aa85f4ea406d7">llvm::setWidenableBranchCond</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad295cb34421c21507bc9cdefe1ba3f16">llvm::SplitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1b1bad7e6f993aef1349ee9ffe1f0e41">llvm::SplitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86flagscopylowering-cpp/#a9d9c7bebc5b5d451511265937418ed6a">splitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adbb5b5ef063bbc4e62efdebb19df690e">llvm::SplitBlockAndInsertIfElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a30e63edf97576526208113bb1b049364">llvm::SplitBlockAndInsertIfThen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aede2d32bd3bfd179688c57186b3fc69d">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabaaa075dbd0b194f8fce41baa5e5be5">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ec3ebb45e7dea6a1d64b09007f11c7a">llvm::splitBlockBefore</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae708a0dc9c80038ba6d971c94eb9db5c">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a747abf73a79323919b62fb98e61aeaf2">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a761b3c02cd196cb5f6fb019bcd86866e">llvm::OutlinableRegion::splitCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a3f8efd734c37d01f22580c2211a68483">splitEndLoopBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a96e05005577b2873e5ef9b3c99c4e30c">swapBBContents</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#ab9fe9fd51104da9e7faa88a213b74b9b">anonymous{LowerSwitch.cpp}::SwitchConvert</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#aebda974c30b92d0f6ffca66705d27f35">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::transform</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a8562a883d9494266aca5d1b2f8b5dc5e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryOptimizeAGPRPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#aadcf41a9f704494210a217eb089678b3">tryToReplaceWithGEPBuiltin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a97cbd12fcf61e3cf7db640c3661e66df">tryToShorten</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a3dc1ad6a578f69fed203a6022699080f">updateGetPCBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a714c6f3608e37d0dba17cdc086dc16d2">llvm::updatePublicTypeTestCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a4d1d15c0a00a9b9391977c8f482e0428">updateScopeLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#adaf155c02ba4c5b8ec6d8d72b50e0f91">upgradeDbgIntrinsicToDbgRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a87e58e9d24983c7890c502fbe731f950">verifyCFIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ab1f923b66b5437b4912f28e87b6076ff">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a3a5f2e657c4828861cdc11d66c9e0a78">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitPHINode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a27f63a779f3bcae1f300371e33227bed">llvm::widenWidenableBranch</a>.</p>

</div>
</div>

### getIterator() {#ad15186d74661a6fb15b986b4b204559d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_self_iterator llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### getReverseIterator() {#ad4bb544993573a6677d97cf5413110c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_self_iterator llvm::ilist_node_impl&lt; OptionsT &gt;::getReverseIterator ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a57a867565747e5ed15e3f6e417857a1b">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findAvailBackwardCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a6d56464060a479164dcac19b3a0fd7e3">llvm::MemoryAccess::getReverseDefsIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a707579b9929664f975f53cb858685397">llvm::MemoryAccess::getReverseDefsIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a0335bbe7f97148c901d8cd85ef2b7858">llvm::MemoryAccess::getReverseIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#aa921b533f8d032b3db40d3ff42cf3767">llvm::MemoryAccess::getReverseIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a352cde174c12aa24afbb7e61c22853e2">llvm::InstCombinerImpl::handleUnreachableFrom</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>.</p>

</div>
</div>

### getReverseIterator() {#a3048b72bb23d82c6468d251ac7404cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_self_iterator llvm::ilist_node_impl&lt; OptionsT &gt;::getReverseIterator ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### isSentinel() {#a0570092282570244c4d7af86003f0aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ilist_node_impl&lt; OptionsT &gt;::isSentinel ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this is the sentinel node.</p>


<p>This requires sentinel tracking to be explicitly enabled. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the <a href="/web-llvm/docs/api/structs/llvm/ilist-sentinel-tracking">ilist_sentinel_tracking&lt;true&gt;</a> option to get this API.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNext() {#a7d9fccf1c26caaa5e19d9d08decf1e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ilist_node_impl * llvm::ilist_node_impl&lt; OptionsT &gt;::getNext ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### getNext() {#ab1a70f0a75ca2a2d56be7293c1ab8921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ilist_node_impl * llvm::ilist_node_impl&lt; OptionsT &gt;::getNext ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### getPrev() {#aa04b309a94cf8f37c90e9aeea242b77e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ilist_node_impl * llvm::ilist_node_impl&lt; OptionsT &gt;::getPrev ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### getPrev() {#acae0d912c873a3e551bd276c39956c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ilist_node_impl * llvm::ilist_node_impl&lt; OptionsT &gt;::getPrev ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### setNext() {#a460e37271b4df9defdddc12db903e543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ilist_node_impl&lt; OptionsT &gt;::setNext (<a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl">ilist_node_impl</a> * N)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

### setPrev() {#a5c8af91d7a6274a7caf60244b03754eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OptionsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ilist_node_impl&lt; OptionsT &gt;::setPrev (<a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl">ilist_node_impl</a> * N)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-h">ilist_node.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
