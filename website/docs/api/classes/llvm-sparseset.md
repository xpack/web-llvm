---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sparseset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SparseSet` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> - Fast set implementation for objects that can be identified by small unsigned keys. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;
class llvm::SparseSet&lt;ValueT, KeyFunctorT, SparseT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">llvm/ADT/SparseSet.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7bb1d1e31202f5c6fae7a9f0dcdb7d28">value_type</a> = ValueT</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8df96b18e035c6bf5b5ca9a9eb6c0a6">reference</a> = ValueT &amp;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8780330d2401656ec3f8d526e4644e72">const_reference</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT &amp;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa86cd650bc7a80d75fd483cd6275e004">pointer</a> = ValueT *</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46930fc8d3821a276ec69308166a983a">const_pointer</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT *</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9dd9e59619f2ce3f425abb29690ff88d">iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a9eae7ba1448d9866beca95a042de2e11">DenseT::iterator</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adcffed9f9e28c03e4b254b733dd9a9d1">const_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">DenseT::const_iterator</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a683b8276f7f4a96e678f4c685c2ff388">KeyT</a> = typename KeyFunctorT::argument_type</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b6d3b07cf5860db9e9edbc457bc6edd">DenseT</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; ValueT, 8 &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a898808b5645325d45c88fea7e1323d2e">size_type</a> = unsigned</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ae9eb53a938d63131879d07443367572e">SparseSet</a> ()=default</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab989758604311c501a45aff5bfc46c3d">SparseSet</a> (const SparseSet &amp;)=delete</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a927086ef3c1f883df8e345579101d237">SparseSet</a> (SparseSet &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a10e10375651be2f363a54c3fe4f3d432">operator=</a> (const SparseSet &amp;)=delete</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ValueT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac424cd6d9b562d39bde27afafaf485a5">operator[]</a> (const KeyT &amp;Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>array subscript - If an element already exists with this key, return it. <a href="#ac424cd6d9b562d39bde27afafaf485a5">More...</a></p>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac5c4065b01268eb6764867041cd1d96c">setUniverse</a> (unsigned U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setUniverse - Set the universe size which determines the largest key the set can hold. <a href="#ac5c4065b01268eb6764867041cd1d96c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#adcffed9f9e28c03e4b254b733dd9a9d1">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba206b8828cec695dbe9fadfe2cddbfa">begin</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#adcffed9f9e28c03e4b254b733dd9a9d1">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abbb7ba5407bdf1f0c42a4ddbaa492131">end</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9dd9e59619f2ce3f425abb29690ff88d">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab909857ec408069fa22068d51bea4316">begin</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9dd9e59619f2ce3f425abb29690ff88d">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd2076fc1245fa8c4c108de1e133a41a">end</a> ()</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4dfc2338a3ed82eb01661c5391339d6">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>empty - Returns true if the set is empty. <a href="#aa4dfc2338a3ed82eb01661c5391339d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02a393a8e880f597847b25bf64c19020">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>size - Returns the number of elements in the set. <a href="#a02a393a8e880f597847b25bf64c19020">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab146f4c3793a4a99649ce52b3badc15">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Clears the set. <a href="#aab146f4c3793a4a99649ce52b3badc15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9dd9e59619f2ce3f425abb29690ff88d">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a037d6235d5fcccb54010dd1aec2572ff">findIndex</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findIndex - Find an element by its index. <a href="#a037d6235d5fcccb54010dd1aec2572ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9dd9e59619f2ce3f425abb29690ff88d">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af521754c270d66c0596d082a7eb6766d">find</a> (const KeyT &amp;Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find - Find an element by its key. <a href="#af521754c270d66c0596d082a7eb6766d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#adcffed9f9e28c03e4b254b733dd9a9d1">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8bf0b3cead3bffdb70639e596bbcf812">find</a> (const KeyT &amp;Key) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af389391f11fe928c911f83cb184f2c8b">contains</a> (const KeyT &amp;Key) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the set contains the given <span class="doxyComputerOutput">Key</span>. <a href="#af389391f11fe928c911f83cb184f2c8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa64c898bcf46c07ce0601865914b21d6">count</a> (const KeyT &amp;Key) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>count - Returns 1 if this set contains an element identified by Key, 0 otherwise. <a href="#aa64c898bcf46c07ce0601865914b21d6">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab13fb368c99a6af1ec6d55b0fadb61c0">insert</a> (const ValueT &amp;Val) -&gt; std::pair&lt; <a href="#a9dd9e59619f2ce3f425abb29690ff88d">iterator</a>, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insert - Attempts to insert a new element. <a href="#ab13fb368c99a6af1ec6d55b0fadb61c0">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8aaae0a835db2df0f57f194c960372b">pop_back_val</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9dd9e59619f2ce3f425abb29690ff88d">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5a00f6afdfec487d3165d29e57452b32">erase</a> (iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>erase - Erases an existing element identified by a valid iterator. <a href="#a5a00f6afdfec487d3165d29e57452b32">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acee53271ae06fdfe056b7ab15d08cd58">erase</a> (const KeyT &amp;Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>erase - Erases an element identified by Key, if it exists. <a href="#acee53271ae06fdfe056b7ab15d08cd58">More...</a></p>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">DenseT</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f4450e2d6cbc8639f594ae7397e8ee0">Dense</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unique_ptr&lt; SparseT[], Deleter &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab8c3a2cc7a3149a61b99706414998119">Sparse</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ffaedbf56b20219f049d744f5386727">Universe</a> = 0</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">KeyFunctorT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8cc3651462964e679ba2a97468fefc5e">KeyIndexOf</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sparsesetvalfunctor">SparseSetValFunctor</a>&lt; KeyT, ValueT, KeyFunctorT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a72a3604a8218cca8bca35522ddb9840c">ValIndexOf</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> - Fast set implementation for objects that can be identified by small unsigned keys.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> allocates memory proportional to the size of the key universe, so it is not recommended for building composite data structures. It is useful for algorithms that require a single set with fast operations.</p>


<p>Compared to <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a> and <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>, <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> provides constant-time fast <a href="#aab146f4c3793a4a99649ce52b3badc15">clear()</a> and iteration as fast as a vector. The <a href="#af521754c270d66c0596d082a7eb6766d">find()</a>, <a href="#ab13fb368c99a6af1ec6d55b0fadb61c0">insert()</a>, and <a href="#a5a00f6afdfec487d3165d29e57452b32">erase()</a> operations are all constant time, and typically faster than a hash table. The iteration order doesn't depend on numerical key values, it only depends on the order of <a href="#ab13fb368c99a6af1ec6d55b0fadb61c0">insert()</a> and <a href="#a5a00f6afdfec487d3165d29e57452b32">erase()</a> operations. When no elements have been erased, the iteration order is the insertion order.</p>


<p>Compared to <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet&lt;unsigned&gt;</a> uses 8x-40x more memory, but offers constant-time <a href="#aab146f4c3793a4a99649ce52b3badc15">clear()</a> and <a href="#a02a393a8e880f597847b25bf64c19020">size()</a> operations as well as fast iteration independent on the size of the universe.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> contains a dense vector holding all the objects and a sparse array holding indexes into the dense vector. Most of the memory is used by the sparse array which is the size of the key universe. The SparseT template parameter provides a space/speed tradeoff for sets holding many elements.</p>


<p>When SparseT is uint32_t, <a href="#af521754c270d66c0596d082a7eb6766d">find()</a> only touches 2 cache lines, but the sparse array uses 4 x Universe bytes.</p>


<p>When SparseT is uint8_t (the default), <a href="#af521754c270d66c0596d082a7eb6766d">find()</a> touches up to 2+[N/256] cache lines, but the sparse array is 4x smaller. N is the number of elements in the set.</p>


<p>For sets that may grow to thousands of elements, SparseT should be set to uint16_t or uint32_t.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Template Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ValueT</td>
<td class="doxyParamItemDescription"><p>The type of objects in the set.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KeyFunctorT</td>
<td class="doxyParamItemDescription"><p>A functor that computes an unsigned index from KeyT.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SparseT</td>
<td class="doxyParamItemDescription"><p>An unsigned integer type. See above.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#adcffed9f9e28c03e4b254b733dd9a9d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::const_iterator =  typename DenseT::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### const\_pointer {#a46930fc8d3821a276ec69308166a983a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::const_pointer =  const ValueT *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### const\_reference {#a8780330d2401656ec3f8d526e4644e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::const_reference =  const ValueT &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### iterator {#a9dd9e59619f2ce3f425abb29690ff88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::iterator =  typename DenseT::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### pointer {#aa86cd650bc7a80d75fd483cd6275e004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::pointer =  ValueT *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### reference {#aa8df96b18e035c6bf5b5ca9a9eb6c0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::reference =  ValueT &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### value\_type {#a7bb1d1e31202f5c6fae7a9f0dcdb7d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::value_type =  ValueT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### DenseT {#a8b6d3b07cf5860db9e9edbc457bc6edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::DenseT =  SmallVector&lt;ValueT, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### KeyT {#a683b8276f7f4a96e678f4c685c2ff388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::KeyT =  typename KeyFunctorT::argument_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### size\_type {#a898808b5645325d45c88fea7e1323d2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::size_type =  unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SparseSet() {#ae9eb53a938d63131879d07443367572e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::SparseSet ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### SparseSet() {#ab989758604311c501a45aff5bfc46c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::SparseSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> &amp;)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### SparseSet() {#a927086ef3c1f883df8e345579101d237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::SparseSet (<a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> &amp;&amp;)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#ac424cd6d9b562d39bde27afafaf485a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueT &amp; llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>array subscript - If an element already exists with this key, return it.</p>


<p>Otherwise, automatically construct a new value from Key, insert it, and return the newly inserted element.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### operator=() {#a10e10375651be2f363a54c3fe4f3d432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseSet &amp; llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> &amp;)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#aba206b8828cec695dbe9fadfe2cddbfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::begin ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="#a5a00f6afdfec487d3165d29e57452b32">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::erase</a>, <a href="#a037d6235d5fcccb54010dd1aec2572ff">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::findIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecombiner-cpp/#a009d1779a003a0d7f14fbc05073dc987">insertDeleteInstructions</a>.</p>

</div>
</div>

### begin() {#ab909857ec408069fa22068d51bea4316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::begin ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### clear() {#aab146f4c3793a4a99649ce52b3badc15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::clear ()</td>
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

<p>clear - Clears the set.</p>


<p>This is a very fast constant time operation.</p>


<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### contains() {#af389391f11fe928c911f83cb184f2c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the set contains the given <span class="doxyComputerOutput">Key</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Key</td>
<td class="doxyParamItemDescription"><p>A valid key to find.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="#aa64c898bcf46c07ce0601865914b21d6">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::count</a>.</p>

</div>
</div>

### count() {#aa64c898bcf46c07ce0601865914b21d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::count (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>count - Returns 1 if this set contains an element identified by Key, 0 otherwise.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a9a5c05172bf1b5e36b42f412c4a176cf">UpdatePredRedefs</a>.</p>

</div>
</div>

### empty() {#aa4dfc2338a3ed82eb01661c5391339d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::empty ()</td>
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

<p>empty - Returns true if the set is empty.</p>


<p>This is not the same as <a href="/web-llvm/docs/api/classes/llvm/bitvector/#ae308e6ee93ceb33e921d72d659230669">BitVector::empty()</a>.</p>


<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="#ac5c4065b01268eb6764867041cd1d96c">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::setUniverse</a>.</p>

</div>
</div>

### end() {#abbb7ba5407bdf1f0c42a4ddbaa492131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::end ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="#af389391f11fe928c911f83cb184f2c8b">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::contains</a>, <a href="#acee53271ae06fdfe056b7ab15d08cd58">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::erase</a>, <a href="#a5a00f6afdfec487d3165d29e57452b32">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::erase</a>, <a href="#a037d6235d5fcccb54010dd1aec2572ff">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::findIndex</a>, <a href="#ab13fb368c99a6af1ec6d55b0fadb61c0">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecombiner-cpp/#a009d1779a003a0d7f14fbc05073dc987">insertDeleteInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6eb3ac91456a9880aecf25dc8e3cbaa5">updatePhysDepsDownwards</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a79107186b863ddb50f8bfdb721aa41d8">updatePhysDepsUpwards</a>.</p>

</div>
</div>

### end() {#afd2076fc1245fa8c4c108de1e133a41a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::end ()</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### erase() {#a5a00f6afdfec487d3165d29e57452b32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::erase (<a href="#a9dd9e59619f2ce3f425abb29690ff88d">iterator</a> I)</td>
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

<p>erase - Erases an existing element identified by a valid iterator.</p>


<p>This invalidates all iterators, but <a href="#a5a00f6afdfec487d3165d29e57452b32">erase()</a> returns an iterator pointing to the next element. This makes it possible to erase selected elements while iterating over the set:</p>


<p>for (<a href="#a9dd9e59619f2ce3f425abb29690ff88d">SparseSet::iterator</a> I = Set.begin(); I != Set.end();) if (<a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test(*I)</a>) I = Set.erase(I); else ++I;</p>


<p>Note that <a href="#abbb7ba5407bdf1f0c42a4ddbaa492131">end()</a> changes when elements are erased, unlike std::list.</p>


<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="#acee53271ae06fdfe056b7ab15d08cd58">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecombiner-cpp/#a009d1779a003a0d7f14fbc05073dc987">insertDeleteInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6eb3ac91456a9880aecf25dc8e3cbaa5">updatePhysDepsDownwards</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a79107186b863ddb50f8bfdb721aa41d8">updatePhysDepsUpwards</a>.</p>

</div>
</div>

### erase() {#acee53271ae06fdfe056b7ab15d08cd58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::erase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>erase - Erases an element identified by Key, if it exists.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Key</td>
<td class="doxyParamItemDescription"><p>The key identifying the element to erase.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True when an element was erased, false if no element was found.</p></dd>
</dl>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### find() {#af521754c270d66c0596d082a7eb6766d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>find - Find an element by its key.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Key</td>
<td class="doxyParamItemDescription"><p>A valid key to find.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An iterator to the element identified by key, or <a href="#abbb7ba5407bdf1f0c42a4ddbaa492131">end()</a>.</p></dd>
</dl>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="#af389391f11fe928c911f83cb184f2c8b">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::contains</a>, <a href="#acee53271ae06fdfe056b7ab15d08cd58">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6eb3ac91456a9880aecf25dc8e3cbaa5">updatePhysDepsDownwards</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a79107186b863ddb50f8bfdb721aa41d8">updatePhysDepsUpwards</a>.</p>

</div>
</div>

### find() {#a8bf0b3cead3bffdb70639e596bbcf812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### findIndex() {#a037d6235d5fcccb54010dd1aec2572ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::findIndex (unsigned Idx)</td>
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

<p>findIndex - Find an element by its index.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Idx</td>
<td class="doxyParamItemDescription"><p>A valid index to find.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An iterator to the element identified by key, or <a href="#abbb7ba5407bdf1f0c42a4ddbaa492131">end()</a>.</p></dd>
</dl>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="#af521754c270d66c0596d082a7eb6766d">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::find</a>, <a href="#a8bf0b3cead3bffdb70639e596bbcf812">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::find</a> and <a href="#ab13fb368c99a6af1ec6d55b0fadb61c0">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::insert</a>.</p>

</div>
</div>

### insert() {#ab13fb368c99a6af1ec6d55b0fadb61c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT &amp; Val)</td>
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

<p>insert - Attempts to insert a new element.</p>


<p>If Val is successfully inserted, return (I, true), where I is an iterator pointing to the newly inserted element.</p>


<p>If the set already contains an element with the same key as Val, return (I, false), where I is an iterator pointing to the existing element.</p>


<p>Insertion invalidates all iterators.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="#ac424cd6d9b562d39bde27afafaf485a5">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::operator[]</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a9a5c05172bf1b5e36b42f412c4a176cf">UpdatePredRedefs</a>.</p>

</div>
</div>

### pop\_back\_val() {#aa8aaae0a835db2df0f57f194c960372b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueT llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::pop_back_val ()</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### setUniverse() {#ac5c4065b01268eb6764867041cd1d96c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::setUniverse (unsigned U)</td>
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

<p>setUniverse - Set the universe size which determines the largest key the set can hold.</p>


<p>The universe must be sized before any elements can be added.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">U</td>
<td class="doxyParamItemDescription"><p>Universe size. All object keys must be less than U.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a9a5c05172bf1b5e36b42f412c4a176cf">UpdatePredRedefs</a>.</p>

</div>
</div>

### size() {#a02a393a8e880f597847b25bf64c19020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::size ()</td>
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

<p>size - Returns the number of elements in the set.</p>


<p>This is not the same as <a href="/web-llvm/docs/api/classes/llvm/bitvector/#abf86e1383aec181a5a2d9967eb8070fd">BitVector::size()</a> which returns the size of the universe.</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="#a5a00f6afdfec487d3165d29e57452b32">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::erase</a>, <a href="#a037d6235d5fcccb54010dd1aec2572ff">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::findIndex</a> and <a href="#ab13fb368c99a6af1ec6d55b0fadb61c0">llvm::SparseSet&lt; MCPhysReg, identity&lt; MCPhysReg &gt; &gt;::insert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Dense {#a0f4450e2d6cbc8639f594ae7397e8ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseT llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::Dense</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### KeyIndexOf {#a8cc3651462964e679ba2a97468fefc5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyFunctorT llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::KeyIndexOf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### Sparse {#ab8c3a2cc7a3149a61b99706414998119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SparseT[], Deleter&gt; llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::Sparse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### Universe {#a7ffaedbf56b20219f049d744f5386727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::Universe = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

### ValIndexOf {#a72a3604a8218cca8bca35522ddb9840c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseSetValFunctor&lt;KeyT, ValueT, KeyFunctorT&gt; llvm::SparseSet&lt; ValueT, KeyFunctorT, SparseT &gt;::ValIndexOf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
