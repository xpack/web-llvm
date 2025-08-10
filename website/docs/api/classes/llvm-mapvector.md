---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mapvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MapVector` Class Template

<p>This class implements a map that also provides access to all stored values in a deterministic order. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;
class llvm::MapVector&lt;KeyT, ValueT, MapType, VectorType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector&lt;KeyT, ValueT, N&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> that performs no allocations if smaller than a certain size. <a href="/web-llvm/docs/api/structs/llvm/smallmapvector/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector&lt;KeyT, ValueT, N&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> that performs no allocations if smaller than a certain size. <a href="/web-llvm/docs/api/structs/llvm/smallmapvector/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf005811d9c2c5afec511e7ea4685095">key_type</a> = KeyT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a635be72da071c449caa8f9346c88a6eb">value_type</a> = typename VectorType::value_type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b5a86fbd0b6ae0086668689408a04d9">size_type</a> = typename VectorType::size_type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a085f340f16ff796202863961ff734902">iterator</a> = typename VectorType::iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad44c8437ba63debbd571e56269a8ddfd">const_iterator</a> = typename VectorType::const_iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd492f1494d1a79ced42776f219f5f42">reverse_iterator</a> = typename VectorType::reverse_iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63166794b71cca0bd30d355b8015fb96">const_reverse_iterator</a> = typename VectorType::const_reverse_iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ValueT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32a1366139fd98139d346e5f8912a9b9">operator[]</a> (const KeyT &amp;Key)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a48284a35966b520c1da3a34a112726f5">takeVector</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> and return the underlying vector. <a href="#a48284a35966b520c1da3a34a112726f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a4b5a86fbd0b6ae0086668689408a04d9">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acf4c09e1f30cdd4e0b5b1b8a236ead34">size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac68b36c64462cf547b2b334c67bf651b">reserve</a> (size_type NumEntries)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Grow the <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> so that it can contain at least <span class="doxyComputerOutput">NumEntries</span> items before resizing again. <a href="#ac68b36c64462cf547b2b334c67bf651b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a085f340f16ff796202863961ff734902">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa610cab7ee61e36a6d1d122fc252c278">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad44c8437ba63debbd571e56269a8ddfd">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8fa5d6a51448a539cf6508ccd853bb1d">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a085f340f16ff796202863961ff734902">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0881334358ff6ff7ff8cea5562c7988e">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad44c8437ba63debbd571e56269a8ddfd">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a33b09e344ff0f9a2b1039b4738d04be9">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#acd492f1494d1a79ced42776f219f5f42">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa84f2e649eac2b43ff8e4a5e3d866e8">rbegin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a63166794b71cca0bd30d355b8015fb96">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12c6c813bc405d136a24dda9b39d4da1">rbegin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#acd492f1494d1a79ced42776f219f5f42">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a290c99a05ce4f33c242f41f0a1d59b84">rend</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a63166794b71cca0bd30d355b8015fb96">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af367bfb28fe29ec72c559430522dbfe4">rend</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8da97c44f514ad1ae9ccf4518b0f88aa">empty</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adb824684d8ec5b843fb4d9b5ac906c9a">front</a> () -&gt; std::pair&lt; KeyT, ValueT &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5526dcd6cc74a6840830de1e55d6293a">front</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; KeyT, ValueT &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd59a8e8a7a844c82a3510aa587c97c9">back</a> () -&gt; std::pair&lt; KeyT, ValueT &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4cc821f83c7282ba778891283d015964">back</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; KeyT, ValueT &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae091b147039557cf8ce505740e7ff7ac">clear</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a281df40be4ec00076eef383da4efb9b3">swap</a> (MapVector &amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ValueT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abca23bddf517f69d28c6d30c58a7b6f9">lookup</a> (const KeyT &amp;Key) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab23f183e7947aaf3caad7960217f843c">try_emplace</a> (const KeyT &amp;Key, Ts &amp;&amp;...Args) -&gt; std::pair&lt; <a href="#a085f340f16ff796202863961ff734902">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a00d1da5a2b498afd67078870c64061a6">try_emplace</a> (KeyT &amp;&amp;Key, Ts &amp;&amp;...Args) -&gt; std::pair&lt; <a href="#a085f340f16ff796202863961ff734902">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">insert</a> (const std::pair&lt; KeyT, ValueT &gt; &amp;KV) -&gt; std::pair&lt; <a href="#a085f340f16ff796202863961ff734902">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aea49fdf7a17296b4c8a6d581f35785fb">insert</a> (std::pair&lt; KeyT, ValueT &gt; &amp;&amp;KV) -&gt; std::pair&lt; <a href="#a085f340f16ff796202863961ff734902">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa79f573e4e5c668610c5a6845783c636">insert_or_assign</a> (const KeyT &amp;Key, V &amp;&amp;Val) -&gt; std::pair&lt; <a href="#a085f340f16ff796202863961ff734902">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename V&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c2fdeded75625410c09da3295e114f7">insert_or_assign</a> (KeyT &amp;&amp;Key, V &amp;&amp;Val) -&gt; std::pair&lt; <a href="#a085f340f16ff796202863961ff734902">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8757ce7071547a0410c82cc096b1ec9a">contains</a> (const KeyT &amp;Key) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a4b5a86fbd0b6ae0086668689408a04d9">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a041e60c6f5f9841f3dc74921ea87bec2">count</a> (const KeyT &amp;Key) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a085f340f16ff796202863961ff734902">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6b0c3e15c351ba9682837c29b0a141b6">find</a> (const KeyT &amp;Key)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad44c8437ba63debbd571e56269a8ddfd">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aada38bc8836def406cc1c537ad613d02">find</a> (const KeyT &amp;Key) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f8b8cde254dee3e797ca4fe8c0551b9">pop_back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the last element from the vector. <a href="#a0f8b8cde254dee3e797ca4fe8c0551b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">VectorType::iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a8171298a7d19a309d599de01906703">erase</a> (typename VectorType::iterator Iterator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the element given by Iterator. <a href="#a3a8171298a7d19a309d599de01906703">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a4b5a86fbd0b6ae0086668689408a04d9">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0c44e77418cb6f3fa64f0ae5400f698">erase</a> (const KeyT &amp;Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all elements with the key value Key. <a href="#ad0c44e77418cb6f3fa64f0ae5400f698">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Predicate&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a862208c77d7ea13b440b4ff84911c1a4">remove_if</a> (Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the elements that match the predicate. <a href="#a862208c77d7ea13b440b4ff84911c1a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Function&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf31a8aa98ad9fb33f2aeb5af238012f">remove_if</a> (Function Pred)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">MapType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af2517c53bd0d564691da7e2a9dfd1c9c">Map</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add59dca36e15a9a00250393af8aa4ee8">Vector</a></td>
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

<p>This class implements a map that also provides access to all stored values in a deterministic order.</p>


<p>The values are kept in a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;*, 0&gt;</a> and the mapping is done with <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> from Keys to indexes in that vector.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ad44c8437ba63debbd571e56269a8ddfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::const_iterator =  typename VectorType::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#a63166794b71cca0bd30d355b8015fb96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::const_reverse_iterator =  typename VectorType::const_reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### iterator {#a085f340f16ff796202863961ff734902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::iterator =  typename VectorType::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### key\_type {#aaf005811d9c2c5afec511e7ea4685095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::key_type =  KeyT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### reverse\_iterator {#acd492f1494d1a79ced42776f219f5f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::reverse_iterator =  typename VectorType::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### size\_type {#a4b5a86fbd0b6ae0086668689408a04d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::size_type =  typename VectorType::size_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### value\_type {#a635be72da071c449caa8f9346c88a6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::value_type =  typename VectorType::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a32a1366139fd98139d346e5f8912a9b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueT &amp; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/scheduledaginstrs/value2susmap/#a0b589d5a5454606a0a9024a106844cf1">llvm::ScheduleDAGInstrs::Value2SUsMap::insert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#afd59a8e8a7a844c82a3510aa587c97c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; KeyT, ValueT &gt; &amp; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::back ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### back() {#a4cc821f83c7282ba778891283d015964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::pair&lt; KeyT, ValueT &gt; &amp; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::back ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### begin() {#aa610cab7ee61e36a6d1d122fc252c278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::begin ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ac483efdc6c5ab7a20f776b77f986b6cf">llvm::ScheduleDAGInstrs::insertBarrierChain</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aa3921084f5ef700564dcb83801124551">anonymous{LiveDebugVariables.cpp}::UserValue::rewriteLocations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>, <a href="#ab23f183e7947aaf3caad7960217f843c">llvm::MapVector&lt; StringRef, HashData &gt;::try_emplace</a>, <a href="#a00d1da5a2b498afd67078870c64061a6">llvm::MapVector&lt; StringRef, HashData &gt;::try_emplace</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e7754bbc7c049946acba12e02f815">llvm::writeIndex</a>.</p>

</div>
</div>

### begin() {#a8fa5d6a51448a539cf6508ccd853bb1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::begin ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### clear() {#ae091b147039557cf8ce505740e7ff7ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::clear ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#adaf1a735e35b87dee5107e5ccd874783">ARM64ProcessEpilogs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#ae0bb182de61b858a03a99b3ea2662e1c">writeMemProfFrameArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#a953c955a410efd221c0a76d209891718">writeMemProfFrames</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#a38203c3ce4c256dc041166735c6e007e">writeMemProfRecords</a>.</p>

</div>
</div>

### contains() {#a8757ce7071547a0410c82cc096b1ec9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#adaf1a735e35b87dee5107e5ccd874783">ARM64ProcessEpilogs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="#a041e60c6f5f9841f3dc74921ea87bec2">llvm::MapVector&lt; StringRef, HashData &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a732bd4cf41862afa6092c1648c02e256">llvm::SelectionDAGBuilder::shouldKeepJumpConditionsTogether</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>.</p>

</div>
</div>

### count() {#a041e60c6f5f9841f3dc74921ea87bec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::count (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad3bf571f4743d886275638484d6a3389">llvm::coro::doRematerializations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>.</p>

</div>
</div>

### empty() {#a8da97c44f514ad1ae9ccf4518b0f88aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::empty ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo/#af587d7218fa15a456103c3d2125a1fc8">llvm::InterleavedAccessInfo::analyzeInterleaving</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a1e5d35d93b0a1cd5f85018b1a98a883f">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::collectConstantsForGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7144f12bd93229efcf87a052ab80d5e6">getSalvageOpsForGEP</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a15231e29111a0d8c49ffbe239f7047b6">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::insertBaseTaggedPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a8e190b21eafd467bfcb3cad647c2b3d3">interpretNextInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e7754bbc7c049946acba12e02f815">llvm::writeIndex</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#ad8b12ebb23f57815dfdaa7a14562aa5f">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### end() {#a0881334358ff6ff7ff8cea5562c7988e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a14962363da4c4a48ad6646cb05f49b77">llvm::ScheduleDAGInstrs::addChainDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#ac398fa604fb57503d55fd556af91e41a">checkFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#af718a7db460e96f14b7c380d841cbcd8">checkInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#ae340f07c3f677f4518e4884b9043f5d8">checkVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a8f5b32a03cc4a6072855d8c8cf7c748f">computeBaseDerivedRelocateMap</a>, <a href="#ad0c44e77418cb6f3fa64f0ae5400f698">llvm::MapVector&lt; StringRef, HashData &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ac483efdc6c5ab7a20f776b77f986b6cf">llvm::ScheduleDAGInstrs::insertBarrierChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>, <a href="#ab23f183e7947aaf3caad7960217f843c">llvm::MapVector&lt; StringRef, HashData &gt;::try_emplace</a>, <a href="#a00d1da5a2b498afd67078870c64061a6">llvm::MapVector&lt; StringRef, HashData &gt;::try_emplace</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### end() {#a33b09e344ff0f9a2b1039b4738d04be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### erase() {#a3a8171298a7d19a309d599de01906703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType::iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::erase (typename VectorType::iterator Iterator)</td>
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

<p>Remove the element given by Iterator.</p>


<p>Returns an iterator to the element following the one which was removed, which may be <a href="#a0881334358ff6ff7ff8cea5562c7988e">end()</a>.</p>



:::info
<p>This is a deceivingly expensive operation (linear time). It's usually better to use <em><a href="#a862208c77d7ea13b440b4ff84911c1a4">remove_if()</a></em> if possible.</p>
:::


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>, <a href="#ad0c44e77418cb6f3fa64f0ae5400f698">llvm::MapVector&lt; StringRef, HashData &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>.</p>

</div>
</div>

### erase() {#ad0c44e77418cb6f3fa64f0ae5400f698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::erase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>Remove all elements with the key value Key.</p>


<p>Returns the number of elements removed.</p>


<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### find() {#a6b0c3e15c351ba9682837c29b0a141b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a14962363da4c4a48ad6646cb05f49b77">llvm::ScheduleDAGInstrs::addChainDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo/#af587d7218fa15a456103c3d2125a1fc8">llvm::InterleavedAccessInfo::analyzeInterleaving</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#ac398fa604fb57503d55fd556af91e41a">checkFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#af718a7db460e96f14b7c380d841cbcd8">checkInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#ae340f07c3f677f4518e4884b9043f5d8">checkVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a8f5b32a03cc4a6072855d8c8cf7c748f">computeBaseDerivedRelocateMap</a>, <a href="#ad0c44e77418cb6f3fa64f0ae5400f698">llvm::MapVector&lt; StringRef, HashData &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a74bcb5c6d80d9d7fb0eeb1131eeef2dc">llvm::LoopVectorizationLegality::getIntOrFpInductionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a728069d0bcacf976cbb3764bad749562">llvm::LoopVectorizationLegality::getPointerInductionDescriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### find() {#aada38bc8836def406cc1c537ad613d02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### front() {#adb824684d8ec5b843fb4d9b5ac906c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; KeyT, ValueT &gt; &amp; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::front ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#a8f3e4fda4ce5ab01260df66b88ebabd3">GEPToVectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### front() {#a5526dcd6cc74a6840830de1e55d6293a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::pair&lt; KeyT, ValueT &gt; &amp; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::front ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### insert() {#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; KeyT, ValueT &gt; &amp; KV)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#af2db0d7fc3c09fcac8bfcc6bc3cdbd6c">addAllTypesFromDWP</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a82237aa799c6a24c6bc9f95c01b137d4">addAllTypesFromTypesSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a19b02b875049489fedf9c500d2424fa3">llvm::GEPOperator::collectOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a8f5b32a03cc4a6072855d8c8cf7c748f">computeBaseDerivedRelocateMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ac224640f48ef4ce451d49bbb1b68e9ca">llvm::object::ELFFile&lt; ELFT &gt;::getSectionAndRelocations</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ae0bf03df2431c543590180658ce4709d">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctionsWithPriority</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aa3921084f5ef700564dcb83801124551">anonymous{LiveDebugVariables.cpp}::UserValue::rewriteLocations</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>.</p>

</div>
</div>

### insert() {#aea49fdf7a17296b4c8a6d581f35785fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert (std::pair&lt; KeyT, ValueT &gt; &amp;&amp; KV)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### insert\_or\_assign() {#aa79f573e4e5c668610c5a6845783c636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert_or_assign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key, V &amp;&amp; Val)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### insert\_or\_assign() {#a3c2fdeded75625410c09da3295e114f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename V&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert_or_assign (KeyT &amp;&amp; Key, V &amp;&amp; Val)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### lookup() {#abca23bddf517f69d28c6d30c58a7b6f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueT llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#adaf1a735e35b87dee5107e5ccd874783">ARM64ProcessEpilogs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ad76b6b11eecce5628e34b552cc6878b1">checkConstLocationCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/valueenumerator-cpp/#a3ae1d92a49245fac09d70bb91ff515ce">orderValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3ae1d92a49245fac09d70bb91ff515ce">orderValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilvalueenumerator-cpp/#a3ae1d92a49245fac09d70bb91ff515ce">orderValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a385464d789381c250f924d62222498f3">predictValueUseListOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/valueenumerator-cpp/#a0446dc9c4c3fd1116f5510fab7d64a43">predictValueUseListOrderImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilvalueenumerator-cpp/#a0446dc9c4c3fd1116f5510fab7d64a43">predictValueUseListOrderImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>.</p>

</div>
</div>

### pop\_back() {#a0f8b8cde254dee3e797ca4fe8c0551b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::pop_back ()</td>
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

<p>Remove the last element from the vector.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### rbegin() {#afa84f2e649eac2b43ff8e4a5e3d866e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::rbegin ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo/#af587d7218fa15a456103c3d2125a1fc8">llvm::InterleavedAccessInfo::analyzeInterleaving</a>.</p>

</div>
</div>

### rbegin() {#a12c6c813bc405d136a24dda9b39d4da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::rbegin ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### remove\_if() {#a862208c77d7ea13b440b4ff84911c1a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Predicate&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::remove_if (<a href="/web-llvm/docs/api/classes/predicate">Predicate</a> Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the elements that match the predicate.</p>


<p>Erase all elements that match <span class="doxyComputerOutput">Pred</span> in a single pass. Takes linear time.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a9f3bc3cacc5c440fc83d37726a3af8aa">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::handleCallsitesWithMultipleTargets</a>.</p>

</div>
</div>

### remove\_if() {#aaf31a8aa98ad9fb33f2aeb5af238012f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Function&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::remove_if (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ac483efdc6c5ab7a20f776b77f986b6cf">llvm::ScheduleDAGInstrs::insertBarrierChain</a>.</p>

</div>
</div>

### rend() {#a290c99a05ce4f33c242f41f0a1d59b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::rend ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo/#af587d7218fa15a456103c3d2125a1fc8">llvm::InterleavedAccessInfo::analyzeInterleaving</a>.</p>

</div>
</div>

### rend() {#af367bfb28fe29ec72c559430522dbfe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::rend ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### reserve() {#ac68b36c64462cf547b2b334c67bf651b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::reserve (<a href="#a4b5a86fbd0b6ae0086668689408a04d9">size_type</a> NumEntries)</td>
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

<p>Grow the <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> so that it can contain at least <span class="doxyComputerOutput">NumEntries</span> items before resizing again.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### size() {#acf4c09e1f30cdd4e0b5b1b8a236ead34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::size ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ad76b6b11eecce5628e34b552cc6878b1">checkConstLocationCompatible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a74bfb3b0492b90d4a296f4e0f131877c">collectOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#a8f3e4fda4ce5ab01260df66b88ebabd3">GEPToVectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/valueenumerator-cpp/#aca141f282be02fdae7bbaaaa2999a4b4">orderModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilvalueenumerator-cpp/#aca141f282be02fdae7bbaaaa2999a4b4">orderModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3ae1d92a49245fac09d70bb91ff515ce">orderValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ab68c7ba7bd95784715357a3fbf5235a7">llvm::AArch64TTIImpl::preferPredicateOverEpilogue</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e7754bbc7c049946acba12e02f815">llvm::writeIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#ae0bb182de61b858a03a99b3ea2662e1c">writeMemProfFrameArray</a>.</p>

</div>
</div>

### swap() {#a281df40be4ec00076eef383da4efb9b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::swap (<a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> &amp; RHS)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### takeVector() {#a48284a35966b520c1da3a34a112726f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::takeVector ()</td>
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

<p>Clear the <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> and return the underlying vector.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>.</p>

</div>
</div>

### try\_emplace() {#ab23f183e7947aaf3caad7960217f843c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::try_emplace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key, Ts &amp;&amp;... Args)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a9e90083bd35fdc6271e1c0060a6290d5">collectInstructionDeps</a>, <a href="#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; StringRef, HashData &gt;::insert</a>, <a href="#aea49fdf7a17296b4c8a6d581f35785fb">llvm::MapVector&lt; StringRef, HashData &gt;::insert</a>, <a href="#aa79f573e4e5c668610c5a6845783c636">llvm::MapVector&lt; StringRef, HashData &gt;::insert_or_assign</a>, <a href="#a3c2fdeded75625410c09da3295e114f7">llvm::MapVector&lt; StringRef, HashData &gt;::insert_or_assign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4dfea19770364b880a77c3f0c1c0f67c">llvm::insertDebugValuesForPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a732bd4cf41862afa6092c1648c02e256">llvm::SelectionDAGBuilder::shouldKeepJumpConditionsTogether</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### try\_emplace() {#a00d1da5a2b498afd67078870c64061a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::try_emplace (KeyT &amp;&amp; Key, Ts &amp;&amp;... Args)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Map {#af2517c53bd0d564691da7e2a9dfd1c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapType llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::Map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

### Vector {#add59dca36e15a9a00250393af8aa4ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename MapType = DenseMap&lt;KeyT, unsigned&gt;, typename VectorType = SmallVector&lt;std::pair&lt;KeyT, ValueT&gt;, 0&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::Vector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">MapVector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
