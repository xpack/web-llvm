---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/simple-ilist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `simple_ilist` Class Template Reference

<p>A simple intrusive list implementation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, class... Options&gt;
class llvm::simple_ilist&lt;T, Options&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">llvm/ADT/simple_ilist.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-base">ilist_base&lt;EnableSentinelTracking, ParentTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of list algorithms using <a href="/web-llvm/docs/api/classes/llvm/ilist-node-base">ilist_node_base</a>. <a href="/web-llvm/docs/api/classes/llvm/ilist-base/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ilist-detail/specificnodeaccess">SpecificNodeAccess&lt;OptionsT&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd18cf13fcfc381cea38722838403e85">value_type</a> = typename OptionsT::value_type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af49920afbc32b9463de003e11af96edf">pointer</a> = typename OptionsT::pointer</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a00c811b25231ad81da2d78722876857b">reference</a> = typename OptionsT::reference</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad031caec508a4d9a74c925ce7335b68f">const_pointer</a> = typename OptionsT::const_pointer</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1951d42bcac1ca78715de0b244f38bd3">const_reference</a> = typename OptionsT::const_reference</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/ilist-select-iterator-type">ilist_select_iterator_type</a>&lt; OptionsT::has_iterator_bits, OptionsT, false, false &gt;::type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adfa153d64dea8943e434e79c1a8daf6f">const_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/ilist-select-iterator-type">ilist_select_iterator_type</a>&lt; OptionsT::has_iterator_bits, OptionsT, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;::type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8d64379d76bba443914771d3f510547">reverse_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/ilist-select-iterator-type">ilist_select_iterator_type</a>&lt; OptionsT::has_iterator_bits, OptionsT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;::type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a707e84629a240dd0d4866d1f3b602f37">const_reverse_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/ilist-select-iterator-type">ilist_select_iterator_type</a>&lt; OptionsT::has_iterator_bits, OptionsT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;::type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1bf59040e990a6ef68062aa6d2bb0b12">size_type</a> = size_t</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5da3239917a2962e7d5981cd659a8927">difference_type</a> = ptrdiff_t</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26207bf6732b37fcec7496913f074252">OptionsT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/compute-node-options">ilist_detail::compute_node_options</a>&lt; T, Options... &gt;::type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7e4523bcb61a44e5812738659410491">list_base_type</a> = typename OptionsT::list_base_type</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa4d5d2d0c3d7d2305b8ca6808d337f73">simple_ilist</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5c8bead4296acab6cf828f2b49161c27">simple_ilist</a> (const simple_ilist &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a19f9df1fa9e01273fcca82cc50629b64">simple_ilist</a> (simple_ilist &amp;&amp;X)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a715382f02a4ab999b3b785a230ed3825">~simple_ilist</a> ()=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1bdabb81bc924d597093b4e98cb3e41b">operator=</a> (const simple_ilist &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a31cbf55b205e721e34eb167c7953b18c">operator=</a> (simple_ilist &amp;&amp;X)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c6d7a572d863e2f211551f91e06729c">merge</a> (simple_ilist &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge in another list. <a href="#a9c6d7a572d863e2f211551f91e06729c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Compare&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b421edc9bf13444958122009e6be70d">merge</a> (simple_ilist &amp;RHS, Compare comp)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeaf24ea7aa5bb7d784972a4ceb2ee13a">sort</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort the list. <a href="#aeaf24ea7aa5bb7d784972a4ceb2ee13a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Compare&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5887db510387adbdb0819190ad287754">sort</a> (Compare comp)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abc96513a79d236fe7f052a1ec7d0eb05">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#adfa153d64dea8943e434e79c1a8daf6f">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad680a16e4f1ff88ee2735771e821645">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ed194b42c5b8ba68764c26760c9ddfe">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#adfa153d64dea8943e434e79c1a8daf6f">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d2f378978e405cb49b463c884454cd7">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa8d64379d76bba443914771d3f510547">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aefb5430ea919aa7223dbf8583e947111">rbegin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a707e84629a240dd0d4866d1f3b602f37">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29fbeebf7cbbe5829299cc037fa1299c">rbegin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa8d64379d76bba443914771d3f510547">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a829db5029599933ad38679d76e0f4975">rend</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a707e84629a240dd0d4866d1f3b602f37">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a263bb549442ab1820df2a77843245bce">rend</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abba3186fa8d1f1f71c2cc11221f9652c">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the list is empty in constant time. <a href="#abba3186fa8d1f1f71c2cc11221f9652c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a1bf59040e990a6ef68062aa6d2bb0b12">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa0023985597fbbf0647e97472ff5b57">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the size of the list in linear time. <a href="#afa0023985597fbbf0647e97472ff5b57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a00c811b25231ad81da2d78722876857b">reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc8f7be86492c65c4894c5456eb08573">front</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a1951d42bcac1ca78715de0b244f38bd3">const_reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2cee63e92f8efc2150567a839134021b">front</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a00c811b25231ad81da2d78722876857b">reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3333290ba61b2ce8abdfa4e1ec0e0644">back</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a1951d42bcac1ca78715de0b244f38bd3">const_reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47ba410dd317ee60b19acd732159c029">back</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6941eb16363576156b03219aea264b91">push_front</a> (reference Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a node at the front; never copies. <a href="#a6941eb16363576156b03219aea264b91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd9e9e84ef0b4b94fdda7d6ceff1e01d">push_back</a> (reference Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a node at the back; never copies. <a href="#acd9e9e84ef0b4b94fdda7d6ceff1e01d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe412c814d4062a3d1867651df73dfc8">pop_front</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the node at the front; never deletes. <a href="#abe412c814d4062a3d1867651df73dfc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a58dab60738a2a2a618ae54461b1bc5ea">pop_back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the node at the back; never deletes. <a href="#a58dab60738a2a2a618ae54461b1bc5ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a44786e29c18a83345c3a554955da5e3a">swap</a> (simple_ilist &amp;X)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Swap with another list in place using <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>. <a href="#a44786e29c18a83345c3a554955da5e3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f4bd492b552181942252ccddc0db26e">insert</a> (iterator I, reference Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a node by reference; never copies. <a href="#a7f4bd492b552181942252ccddc0db26e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Iterator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaaa2964e6879a028119118f58bf4e108">insert</a> (iterator I, Iterator First, Iterator Last)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a range of nodes; never copies. <a href="#aaaa2964e6879a028119118f58bf4e108">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Cloner, class Disposer&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a77f246fe90c85e3de7a8caf4715ad5ba">cloneFrom</a> (const simple_ilist &amp;L2, Cloner clone, Disposer dispose)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone another list. <a href="#a77f246fe90c85e3de7a8caf4715ad5ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af373b4ab7e8cd5a179d3c86ee3404912">remove</a> (reference N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a node by reference; never deletes. <a href="#af373b4ab7e8cd5a179d3c86ee3404912">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Disposer&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afb5871f1692d8db06f33611f9bdddb85">removeAndDispose</a> (reference N, Disposer dispose)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a node by reference and dispose of it. <a href="#afb5871f1692d8db06f33611f9bdddb85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b588a868b58f1ac0917a59e7c48b5cc">erase</a> (iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a node by iterator; never deletes. <a href="#a4b588a868b58f1ac0917a59e7c48b5cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac35188eb93675946884adadbd5a507ab">erase</a> (iterator First, iterator Last)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a range of nodes; never deletes. <a href="#ac35188eb93675946884adadbd5a507ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Disposer&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a07d0b4e0e3d2ef200f612297e7d63b9d">eraseAndDispose</a> (iterator I, Disposer dispose)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a node by iterator and dispose of it. <a href="#a07d0b4e0e3d2ef200f612297e7d63b9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Disposer&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0451b587b609d6ada6b57fdac2cc811d">eraseAndDispose</a> (iterator First, iterator Last, Disposer dispose)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a range of nodes and dispose of them. <a href="#a0451b587b609d6ada6b57fdac2cc811d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9e8f24dd616634c0f94649826a6c534f">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the list; never deletes. <a href="#a9e8f24dd616634c0f94649826a6c534f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Disposer&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af3e13ba39a57af4a57b5e7d0cc553f0e">clearAndDispose</a> (Disposer dispose)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the list and dispose of the nodes. <a href="#af3e13ba39a57af4a57b5e7d0cc553f0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2cc787652fd821d6aa9af1c96866e00e">splice</a> (iterator I, simple_ilist &amp;L2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splice in another list. <a href="#a2cc787652fd821d6aa9af1c96866e00e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aee3c1c7a64e09824677d53e5aaa7494d">splice</a> (iterator I, simple_ilist &amp;L2, iterator Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splice in a node from another list. <a href="#aee3c1c7a64e09824677d53e5aaa7494d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a08d5b70e605ea0a330e24d7fc2b69886">splice</a> (iterator I, simple_ilist &amp;, iterator First, iterator Last)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splice in a range of nodes from another list. <a href="#a08d5b70e605ea0a330e24d7fc2b69886">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, class... Options&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-sentinel">ilist_sentinel</a>&lt; OptionsT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d4dc123588a821ba5f695001db77552">Sentinel</a></td>
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

<p>A simple intrusive list implementation.</p>


<p>This is a simple intrusive list for a <span class="doxyComputerOutput">T</span> that inherits from <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T&gt;</a></span>. The list never takes ownership of anything inserted in it.</p>


<p>Unlike <em><a href="/web-llvm/docs/api/classes/llvm/iplist">iplist&lt;T&gt;</a></em> and <em><a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist&lt;T&gt;</a></em>, <em>simple_ilist&lt;T&gt;</em> never deletes values, and has no callback traits.</p>


<p>The API for adding nodes include <em><a href="#a6941eb16363576156b03219aea264b91">push_front()</a></em>, <em><a href="#acd9e9e84ef0b4b94fdda7d6ceff1e01d">push_back()</a></em>, and <em><a href="#a7f4bd492b552181942252ccddc0db26e">insert()</a></em>. These all take values by reference (not by pointer), except for the range version of <em><a href="#a7f4bd492b552181942252ccddc0db26e">insert()</a></em>.</p>


<p>There are three sets of API for discarding nodes from the list: <em><a href="#af373b4ab7e8cd5a179d3c86ee3404912">remove()</a></em>, which takes a reference to the node to remove, <em><a href="#a4b588a868b58f1ac0917a59e7c48b5cc">erase()</a></em>, which takes an iterator or iterator range and returns the next one, and <em><a href="#a9e8f24dd616634c0f94649826a6c534f">clear()</a></em>, which empties out the container. All three are constant time operations. None of these deletes any nodes; in particular, if there is a single node in the list, then these have identical semantics:</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">L.remove</span>(L.front());</li>
<li><span class="doxyComputerOutput">L.erase</span>(L.begin());</li>
<li><span class="doxyComputerOutput">L.clear()</span>;</li>
</ul>

<p>As a convenience for callers, there are parallel APIs that take a <span class="doxyComputerOutput">Disposer</span> (such as <span class="doxyComputerOutput">std::default_delete&lt;T&gt;</span>): <em><a href="#afb5871f1692d8db06f33611f9bdddb85">removeAndDispose()</a></em>, <em><a href="#a07d0b4e0e3d2ef200f612297e7d63b9d">eraseAndDispose()</a></em>, and <em><a href="#af3e13ba39a57af4a57b5e7d0cc553f0e">clearAndDispose()</a></em>. These have different names because the extra semantic is otherwise non-obvious. They are equivalent to calling <em>std::for_each()</em> on the range to be discarded.</p>


<p>The currently available <span class="doxyComputerOutput">Options</span> customize the nodes in the list. The same options must be specified in the <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a></em> instantiation for compatibility (although the order is irrelevant).</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <em><a href="/web-llvm/docs/api/structs/llvm/ilist-tag">ilist_tag</a></em> to designate which <a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a> for a given <span class="doxyComputerOutput">T</span> this list should use. This is useful if a type <span class="doxyComputerOutput">T</span> is part of multiple, independent lists simultaneously.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <em><a href="/web-llvm/docs/api/structs/llvm/ilist-sentinel-tracking">ilist_sentinel_tracking</a></em> to always (or never) track whether a node is a sentinel. Specifying <span class="doxyComputerOutput">true</span> enables the <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a0570092282570244c4d7af86003f0aa9">ilist_node::isSentinel()</a></em> API. Unlike <em>ilist_node::isKnownSentinel()</em>, which is only appropriate for assertions, <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a0570092282570244c4d7af86003f0aa9">ilist_node::isSentinel()</a></em> is appropriate for real logic.</li>
</ul>

<p>Here are examples of <span class="doxyComputerOutput">Options</span> usage:</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">simple_ilist&lt;T&gt;</span> gives the defaults.</li>
<li><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist&lt;T,ilist_sentinel_tracking&lt;true&gt;&gt;</a></span> enables the <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a0570092282570244c4d7af86003f0aa9">ilist_node::isSentinel()</a></em> API.</li>
<li><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt;T</span>,<a href="/web-llvm/docs/api/structs/llvm/ilist-tag">ilist_tag</a>,<a href="/web-llvm/docs/api/structs/llvm/ilist-sentinel-tracking">ilist_sentinel_tracking&lt;false&gt;</a>&gt; specifies a tag of A and that tracking should be off (even when LLVM_ENABLE_ABI_BREAKING_CHECKS are enabled).</li>
<li><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt;T</span>,<a href="/web-llvm/docs/api/structs/llvm/ilist-sentinel-tracking">ilist_sentinel_tracking&lt;false&gt;</a>,<a href="/web-llvm/docs/api/structs/llvm/ilist-tag">ilist_tag</a>&gt; is equivalent to the last.</li>
</ul>

<p>See <em>is_valid_option</em> for steps on adding a new option.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#adfa153d64dea8943e434e79c1a8daf6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::const_iterator = 
      typename ilist_select_iterator_type&lt;OptionsT::has_iterator_bits, OptionsT,
                                          false, true&gt;::type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### const\_pointer {#ad031caec508a4d9a74c925ce7335b68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::const_pointer =  typename OptionsT::const_pointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### const\_reference {#a1951d42bcac1ca78715de0b244f38bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::const_reference =  typename OptionsT::const_reference</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#a707e84629a240dd0d4866d1f3b602f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::const_reverse_iterator = 
      typename ilist_select_iterator_type&lt;OptionsT::has_iterator_bits, OptionsT,
                                          true, true&gt;::type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### difference\_type {#a5da3239917a2962e7d5981cd659a8927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::difference_type =  ptrdiff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### iterator {#aaa26237d7a40d3f5207b306d693babbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::iterator = 
      typename ilist_select_iterator_type&lt;OptionsT::has_iterator_bits, OptionsT,
                                          false, false&gt;::type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### pointer {#af49920afbc32b9463de003e11af96edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::pointer =  typename OptionsT::pointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### reference {#a00c811b25231ad81da2d78722876857b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::reference =  typename OptionsT::reference</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### reverse\_iterator {#aa8d64379d76bba443914771d3f510547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::reverse_iterator = 
      typename ilist_select_iterator_type&lt;OptionsT::has_iterator_bits, OptionsT,
                                          true, false&gt;::type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### size\_type {#a1bf59040e990a6ef68062aa6d2bb0b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::size_type =  size_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### value\_type {#acd18cf13fcfc381cea38722838403e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::value_type =  typename OptionsT::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### list\_base\_type {#ac7e4523bcb61a44e5812738659410491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::list_base_type =  typename OptionsT::list_base_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### OptionsT {#a26207bf6732b37fcec7496913f074252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simple_ilist&lt; T, Options &gt;::OptionsT = 
      typename ilist_detail::compute_node_options&lt;T, Options...&gt;::type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### simple\_ilist() {#aa4d5d2d0c3d7d2305b8ca6808d337f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::simple_ilist&lt; T, Options &gt;::simple_ilist ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a9b421edc9bf13444958122009e6be70d">llvm::simple_ilist&lt; T, Options &gt;::merge</a> and <a href="#a5887db510387adbdb0819190ad287754">llvm::simple_ilist&lt; T, Options &gt;::sort</a>.</p>

</div>
</div>

### simple\_ilist() {#a5c8bead4296acab6cf828f2b49161c27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::simple_ilist&lt; T, Options &gt;::simple_ilist (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### simple\_ilist() {#a19f9df1fa9e01273fcca82cc50629b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::simple_ilist&lt; T, Options &gt;::simple_ilist (<a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp;&amp; X)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~simple\_ilist() {#a715382f02a4ab999b3b785a230ed3825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::simple_ilist&lt; T, Options &gt;::~simple_ilist ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a1bdabb81bc924d597093b4e98cb3e41b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">simple_ilist &amp; llvm::simple_ilist&lt; T, Options &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### operator=() {#a31cbf55b205e721e34eb167c7953b18c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">simple_ilist &amp; llvm::simple_ilist&lt; T, Options &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp;&amp; X)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### merge() {#a9c6d7a572d863e2f211551f91e06729c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::merge (<a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp; RHS)</td>
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

<p>Merge in another list.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">this</span> and <span class="doxyComputerOutput">RHS</span> are sorted.</p></dd>
</dl>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a9c6d7a572d863e2f211551f91e06729c">llvm::simple_ilist&lt; Node &gt;::merge</a>.</p>

</div>
</div>

### merge() {#a9b421edc9bf13444958122009e6be70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Compare&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::merge (<a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp; RHS, Compare comp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>References <a href="#abc96513a79d236fe7f052a1ec7d0eb05">llvm::simple_ilist&lt; T, Options &gt;::begin</a>, <a href="#a9ed194b42c5b8ba68764c26760c9ddfe">llvm::simple_ilist&lt; T, Options &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aa4d5d2d0c3d7d2305b8ca6808d337f73">llvm::simple_ilist&lt; T, Options &gt;::simple_ilist</a> and <a href="#a2cc787652fd821d6aa9af1c96866e00e">llvm::simple_ilist&lt; T, Options &gt;::splice</a>.</p>

</div>
</div>

### sort() {#aeaf24ea7aa5bb7d784972a4ceb2ee13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::sort ()</td>
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

<p>Sort the list.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#aeaf24ea7aa5bb7d784972a4ceb2ee13a">llvm::simple_ilist&lt; Node &gt;::sort</a>.</p>

</div>
</div>

### sort() {#a5887db510387adbdb0819190ad287754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Compare&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::sort (Compare comp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>References <a href="#abc96513a79d236fe7f052a1ec7d0eb05">llvm::simple_ilist&lt; T, Options &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a4f1f6016fc9f3f2353c0cc7c67b292bd">llvm::Center</a>, <a href="#abba3186fa8d1f1f71c2cc11221f9652c">llvm::simple_ilist&lt; T, Options &gt;::empty</a>, <a href="#a9ed194b42c5b8ba68764c26760c9ddfe">llvm::simple_ilist&lt; T, Options &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a66a2592ace8a67bc796c72710d632bab">merge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aa4d5d2d0c3d7d2305b8ca6808d337f73">llvm::simple_ilist&lt; T, Options &gt;::simple_ilist</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#a3333290ba61b2ce8abdfa4e1ec0e0644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::simple_ilist&lt; T, Options &gt;::back ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### back() {#a47ba410dd317ee60b19acd732159c029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference llvm::simple_ilist&lt; T, Options &gt;::back ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### begin() {#abc96513a79d236fe7f052a1ec7d0eb05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::simple_ilist&lt; T, Options &gt;::begin ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#af3e13ba39a57af4a57b5e7d0cc553f0e">llvm::simple_ilist&lt; Node &gt;::clearAndDispose</a>, <a href="#afc8f7be86492c65c4894c5456eb08573">llvm::simple_ilist&lt; Node &gt;::front</a>, <a href="#a2cee63e92f8efc2150567a839134021b">llvm::simple_ilist&lt; Node &gt;::front</a>, <a href="#a9b421edc9bf13444958122009e6be70d">llvm::simple_ilist&lt; T, Options &gt;::merge</a>, <a href="#abe412c814d4062a3d1867651df73dfc8">llvm::simple_ilist&lt; Node &gt;::pop_front</a>, <a href="#a6941eb16363576156b03219aea264b91">llvm::simple_ilist&lt; Node &gt;::push_front</a>, <a href="#afa0023985597fbbf0647e97472ff5b57">llvm::simple_ilist&lt; Node &gt;::size</a>, <a href="#a5887db510387adbdb0819190ad287754">llvm::simple_ilist&lt; T, Options &gt;::sort</a> and <a href="#a2cc787652fd821d6aa9af1c96866e00e">llvm::simple_ilist&lt; Node &gt;::splice</a>.</p>

</div>
</div>

### begin() {#aad680a16e4f1ff88ee2735771e821645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::simple_ilist&lt; T, Options &gt;::begin ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### clear() {#a9e8f24dd616634c0f94649826a6c534f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::clear ()</td>
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

<p>Clear the list; never deletes.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><em><a href="#af3e13ba39a57af4a57b5e7d0cc553f0e">clearAndDispose()</a></em> <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> the <a href="/web-llvm/docs/api/namespaces/llvm/#a1f108d77e1ecf5e30bbd3c7d8818af84">nodes</a> should be deleted.</p></dd>
</dl>


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a31cbf55b205e721e34eb167c7953b18c">llvm::simple_ilist&lt; Node &gt;::operator=</a>.</p>

</div>
</div>

### clearAndDispose() {#af3e13ba39a57af4a57b5e7d0cc553f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Disposer&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::clearAndDispose (Disposer dispose)</td>
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

<p>Clear the list and dispose of the nodes.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a77f246fe90c85e3de7a8caf4715ad5ba">llvm::simple_ilist&lt; Node &gt;::cloneFrom</a>.</p>

</div>
</div>

### cloneFrom() {#a77f246fe90c85e3de7a8caf4715ad5ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Cloner, class Disposer&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::cloneFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp; L2, Cloner clone, Disposer dispose)</td>
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

<p>Clone another list.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### empty() {#abba3186fa8d1f1f71c2cc11221f9652c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::simple_ilist&lt; T, Options &gt;::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the list is empty in constant time.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a5887db510387adbdb0819190ad287754">llvm::simple_ilist&lt; T, Options &gt;::sort</a>.</p>

</div>
</div>

### end() {#a9ed194b42c5b8ba68764c26760c9ddfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::simple_ilist&lt; T, Options &gt;::end ()</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#af3e13ba39a57af4a57b5e7d0cc553f0e">llvm::simple_ilist&lt; Node &gt;::clearAndDispose</a>, <a href="#a4b588a868b58f1ac0917a59e7c48b5cc">llvm::simple_ilist&lt; Node &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a99c136a293cd78a1986bc2501e2ca137">llvm::MemorySSA::getWritableBlockDefs</a>, <a href="#a9b421edc9bf13444958122009e6be70d">llvm::simple_ilist&lt; T, Options &gt;::merge</a>, <a href="#a31cbf55b205e721e34eb167c7953b18c">llvm::simple_ilist&lt; Node &gt;::operator=</a>, <a href="#a58dab60738a2a2a618ae54461b1bc5ea">llvm::simple_ilist&lt; Node &gt;::pop_back</a>, <a href="#acd9e9e84ef0b4b94fdda7d6ceff1e01d">llvm::simple_ilist&lt; Node &gt;::push_back</a>, <a href="#a19f9df1fa9e01273fcca82cc50629b64">llvm::simple_ilist&lt; Node &gt;::simple_ilist</a>, <a href="#afa0023985597fbbf0647e97472ff5b57">llvm::simple_ilist&lt; Node &gt;::size</a>, <a href="#a5887db510387adbdb0819190ad287754">llvm::simple_ilist&lt; T, Options &gt;::sort</a> and <a href="#a2cc787652fd821d6aa9af1c96866e00e">llvm::simple_ilist&lt; Node &gt;::splice</a>.</p>

</div>
</div>

### end() {#a9d2f378978e405cb49b463c884454cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::simple_ilist&lt; T, Options &gt;::end ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### erase() {#a4b588a868b58f1ac0917a59e7c48b5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::simple_ilist&lt; T, Options &gt;::erase (<a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> I)</td>
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

<p>Remove a node by iterator; never deletes.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><em><a href="#af373b4ab7e8cd5a179d3c86ee3404912">remove()</a></em> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> removing by <a href="#a00c811b25231ad81da2d78722876857b">reference</a>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><em><a href="#a07d0b4e0e3d2ef200f612297e7d63b9d">eraseAndDispose()</a></em> it the node should be deleted.</p></dd>
</dl>


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a07d0b4e0e3d2ef200f612297e7d63b9d">llvm::simple_ilist&lt; Node &gt;::eraseAndDispose</a>, <a href="#a58dab60738a2a2a618ae54461b1bc5ea">llvm::simple_ilist&lt; Node &gt;::pop_back</a> and <a href="#abe412c814d4062a3d1867651df73dfc8">llvm::simple_ilist&lt; Node &gt;::pop_front</a>.</p>

</div>
</div>

### erase() {#ac35188eb93675946884adadbd5a507ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::simple_ilist&lt; T, Options &gt;::erase (<a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> First, <a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> Last)</td>
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

<p>Remove a range of nodes; never deletes.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><em><a href="#a07d0b4e0e3d2ef200f612297e7d63b9d">eraseAndDispose()</a></em> <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> the <a href="/web-llvm/docs/api/namespaces/llvm/#a1f108d77e1ecf5e30bbd3c7d8818af84">nodes</a> should be deleted.</p></dd>
</dl>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### eraseAndDispose() {#a07d0b4e0e3d2ef200f612297e7d63b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Disposer&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::simple_ilist&lt; T, Options &gt;::eraseAndDispose (<a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> I, Disposer dispose)</td>
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

<p>Remove a node by iterator and dispose of it.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#af3e13ba39a57af4a57b5e7d0cc553f0e">llvm::simple_ilist&lt; Node &gt;::clearAndDispose</a> and <a href="#a0451b587b609d6ada6b57fdac2cc811d">llvm::simple_ilist&lt; Node &gt;::eraseAndDispose</a>.</p>

</div>
</div>

### eraseAndDispose() {#a0451b587b609d6ada6b57fdac2cc811d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Disposer&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::simple_ilist&lt; T, Options &gt;::eraseAndDispose (<a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> First, <a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> Last, Disposer dispose)</td>
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

<p>Remove a range of nodes and dispose of them.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### front() {#afc8f7be86492c65c4894c5456eb08573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::simple_ilist&lt; T, Options &gt;::front ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### front() {#a2cee63e92f8efc2150567a839134021b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference llvm::simple_ilist&lt; T, Options &gt;::front ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### insert() {#a7f4bd492b552181942252ccddc0db26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::simple_ilist&lt; T, Options &gt;::insert (<a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> I, <a href="#a00c811b25231ad81da2d78722876857b">reference</a> Node)</td>
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

<p>Insert a node by reference; never copies.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#aaaa2964e6879a028119118f58bf4e108">llvm::simple_ilist&lt; Node &gt;::insert</a>, <a href="#acd9e9e84ef0b4b94fdda7d6ceff1e01d">llvm::simple_ilist&lt; Node &gt;::push_back</a> and <a href="#a6941eb16363576156b03219aea264b91">llvm::simple_ilist&lt; Node &gt;::push_front</a>.</p>

</div>
</div>

### insert() {#aaaa2964e6879a028119118f58bf4e108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::insert (<a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> I, Iterator First, Iterator Last)</td>
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

<p>Insert a range of nodes; never copies.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### pop\_back() {#a58dab60738a2a2a618ae54461b1bc5ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::pop_back ()</td>
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

<p>Remove the node at the back; never deletes.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### pop\_front() {#abe412c814d4062a3d1867651df73dfc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::pop_front ()</td>
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

<p>Remove the node at the front; never deletes.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### push\_back() {#acd9e9e84ef0b4b94fdda7d6ceff1e01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::push_back (<a href="#a00c811b25231ad81da2d78722876857b">reference</a> Node)</td>
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

<p>Insert a node at the back; never copies.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a77f246fe90c85e3de7a8caf4715ad5ba">llvm::simple_ilist&lt; Node &gt;::cloneFrom</a>.</p>

</div>
</div>

### push\_front() {#a6941eb16363576156b03219aea264b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::push_front (<a href="#a00c811b25231ad81da2d78722876857b">reference</a> Node)</td>
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

<p>Insert a node at the front; never copies.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### rbegin() {#aefb5430ea919aa7223dbf8583e947111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::simple_ilist&lt; T, Options &gt;::rbegin ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a3333290ba61b2ce8abdfa4e1ec0e0644">llvm::simple_ilist&lt; Node &gt;::back</a> and <a href="#a47ba410dd317ee60b19acd732159c029">llvm::simple_ilist&lt; Node &gt;::back</a>.</p>

</div>
</div>

### rbegin() {#a29fbeebf7cbbe5829299cc037fa1299c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::simple_ilist&lt; T, Options &gt;::rbegin ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### remove() {#af373b4ab7e8cd5a179d3c86ee3404912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::remove (<a href="#a00c811b25231ad81da2d78722876857b">reference</a> N)</td>
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

<p>Remove a node by reference; never deletes.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><em><a href="#a4b588a868b58f1ac0917a59e7c48b5cc">erase()</a></em> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> removing by <a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><em><a href="#afb5871f1692d8db06f33611f9bdddb85">removeAndDispose()</a></em> <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> the node should be deleted.</p></dd>
</dl>


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a4b588a868b58f1ac0917a59e7c48b5cc">llvm::simple_ilist&lt; Node &gt;::erase</a> and <a href="#afb5871f1692d8db06f33611f9bdddb85">llvm::simple_ilist&lt; Node &gt;::removeAndDispose</a>.</p>

</div>
</div>

### removeAndDispose() {#afb5871f1692d8db06f33611f9bdddb85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Disposer&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::removeAndDispose (<a href="#a00c811b25231ad81da2d78722876857b">reference</a> N, Disposer dispose)</td>
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

<p>Remove a node by reference and dispose of it.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### rend() {#a829db5029599933ad38679d76e0f4975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::simple_ilist&lt; T, Options &gt;::rend ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### rend() {#a263bb549442ab1820df2a77843245bce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::simple_ilist&lt; T, Options &gt;::rend ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### size() {#afa0023985597fbbf0647e97472ff5b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::simple_ilist&lt; T, Options &gt;::size ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the size of the list in linear time.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### splice() {#a2cc787652fd821d6aa9af1c96866e00e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::splice (<a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp; L2)</td>
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

<p>Splice in another list.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>


<p>Referenced by <a href="#a9b421edc9bf13444958122009e6be70d">llvm::simple_ilist&lt; T, Options &gt;::merge</a>, <a href="#a31cbf55b205e721e34eb167c7953b18c">llvm::simple_ilist&lt; Node &gt;::operator=</a>, <a href="#a19f9df1fa9e01273fcca82cc50629b64">llvm::simple_ilist&lt; Node &gt;::simple_ilist</a>, <a href="#a2cc787652fd821d6aa9af1c96866e00e">llvm::simple_ilist&lt; Node &gt;::splice</a> and <a href="#aee3c1c7a64e09824677d53e5aaa7494d">llvm::simple_ilist&lt; Node &gt;::splice</a>.</p>

</div>
</div>

### splice() {#aee3c1c7a64e09824677d53e5aaa7494d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::splice (<a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp; L2, <a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> Node)</td>
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

<p>Splice in a node from another list.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### splice() {#a08d5b70e605ea0a330e24d7fc2b69886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::splice (<a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp;, <a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> First, <a href="#aaa26237d7a40d3f5207b306d693babbd">iterator</a> Last)</td>
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

<p>Splice in a range of nodes from another list.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

### swap() {#a44786e29c18a83345c3a554955da5e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::simple_ilist&lt; T, Options &gt;::swap (<a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a> &amp; X)</td>
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

<p>Swap with another list in place using <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Sentinel {#a1d4dc123588a821ba5f695001db77552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, class... Options&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ilist_sentinel&lt;OptionsT&gt; llvm::simple_ilist&lt; T, Options &gt;::Sentinel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/simple-ilist-h">simple_ilist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
