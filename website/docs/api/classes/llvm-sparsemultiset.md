---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sparsemultiset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SparseMultiSet` Class Template Reference

<p>Fast multiset implementation for objects that can be identified by small unsigned keys. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;
class llvm::SparseMultiSet&lt;ValueT, KeyFunctorT, SparseT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">llvm/ADT/SparseMultiSet.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab8dffcfeacb8cce39fd14cceadb3ceea">value_type</a> = ValueT</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c3aafdeec18d298f96df3eb4b46ada2">reference</a> = ValueT &amp;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b3f3a95746eeb974958d3605c8c2521">const_reference</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT &amp;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4cfb52a7ffa678488c329f891f823338">pointer</a> = ValueT *</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1badaaa7449797da1b668e687b6de23">const_pointer</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT *</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a0e116fdaa2041ec3d61c9d110b0c2f">size_type</a> = unsigned</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset/iterator-base">iterator_base</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> * &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a13be60676bc49a4629a0bfd8bf671174">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset/iterator-base">iterator_base</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> * &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aedf030829902cd1a8e3ed4a24820e3a7">RangePair</a> = std::pair&lt; <a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a>, <a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad039913e011b603056874997f4ccc438">KeyT</a> = typename KeyFunctorT::argument_type</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4ce4893dc34479447853671cf8b5253">DenseT</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; SMSNode, 8 &gt;</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac25748f56dc1c73fd9c021d5dbc751bd">SparseMultiSet</a> ()=default</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8943b7ab698dabcabebe73bb98fe340c">SparseMultiSet</a> (const SparseMultiSet &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad48508707ac902124dfd05481728014f">~SparseMultiSet</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac9658f836f5eaea6f157afb14c7239a">operator=</a> (const SparseMultiSet &amp;)=delete</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af781b01667ff848f2b07b4b51660a714">setUniverse</a> (unsigned U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the universe size which determines the largest key the set can hold. <a href="#af781b01667ff848f2b07b4b51660a714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6123d1aa335e5d9c6299050c2cc5193e">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator past this container. <a href="#a6123d1aa335e5d9c6299050c2cc5193e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a13be60676bc49a4629a0bfd8bf671174">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9dc8a38575ad6af2633fd5bd0e7aba9d">end</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02504d447f0362be1ffc1cc19f6e48ef">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the set is empty. <a href="#a02504d447f0362be1ffc1cc19f6e48ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a3a0e116fdaa2041ec3d61c9d110b0c2f">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5bb43880c7874561f71afdebbc59e2ed">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of elements in the set. <a href="#a5bb43880c7874561f71afdebbc59e2ed">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2554bf4e6f211e29c3e80fd4c9141c79">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears the set. <a href="#a2554bf4e6f211e29c3e80fd4c9141c79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16a780296035cd55839932310e5dc672">findIndex</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find an element by its index. <a href="#a16a780296035cd55839932310e5dc672">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a007d043f89bfaefaec158a7e93b39832">find</a> (const KeyT &amp;Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find an element by its key. <a href="#a007d043f89bfaefaec158a7e93b39832">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a13be60676bc49a4629a0bfd8bf671174">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a61aff372ad2255f01e286bc010c9f575">find</a> (const KeyT &amp;Key) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a3a0e116fdaa2041ec3d61c9d110b0c2f">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f0300f83a134efc4ff02bb922d10cd2">count</a> (const KeyT &amp;Key) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of elements identified by Key. <a href="#a7f0300f83a134efc4ff02bb922d10cd2">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14465cc22942098bf446b8d96d018cd4">contains</a> (const KeyT &amp;Key) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this set contains an element identified by Key. <a href="#a14465cc22942098bf446b8d96d018cd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9bbecf0bb2b7cc5819bb54f53fbf4622">getHead</a> (const KeyT &amp;Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the head and tail of the subset's list, otherwise returns <a href="#a6123d1aa335e5d9c6299050c2cc5193e">end()</a>. <a href="#a9bbecf0bb2b7cc5819bb54f53fbf4622">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa107631835001303a52fc79b695d2f41">getTail</a> (const KeyT &amp;Key)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aedf030829902cd1a8e3ed4a24820e3a7">RangePair</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac92517e8c9066cbd446b0589a50c16f6">equal_range</a> (const KeyT &amp;K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bounds of the range of items sharing Key K. <a href="#ac92517e8c9066cbd446b0589a50c16f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8586fb88f0c2e2236a1552292cba1dd3">insert</a> (const ValueT &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new element at the tail of the subset list. <a href="#a8586fb88f0c2e2236a1552292cba1dd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ab390f0c1123852f16664da01de672a">erase</a> (iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erases an existing element identified by a valid iterator. <a href="#a3ab390f0c1123852f16664da01de672a">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab911382d02334b8421f4dbca8c53ff27">eraseAll</a> (const KeyT &amp;K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase all elements with the given key. <a href="#ab911382d02334b8421f4dbca8c53ff27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c283a279de2c059b44b47055902d931">sparseIndex</a> (const ValueT &amp;Val) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a616152c51e1d8fa2afc6fb4da430356f">sparseIndex</a> (const SMSNode &amp;N) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a976d6c2891a6abc45814f504c0b8ea68">isHead</a> (const SMSNode &amp;D) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the given entry is the head of the list. <a href="#a976d6c2891a6abc45814f504c0b8ea68">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd07013b976c74dc76fc24246a182e15">isSingleton</a> (const SMSNode &amp;N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the given entry is a singleton entry, i.e. <a href="#afd07013b976c74dc76fc24246a182e15">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8187526ec61c0b1bcc4b402c702793e5">addValue</a> (const ValueT &amp;V, unsigned Prev, unsigned Next)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add in the given SMSNode. <a href="#a8187526ec61c0b1bcc4b402c702793e5">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5bff4e7767b1cee69df628fa5319fa6">makeTombstone</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make the current index a new tombstone. Pushes it onto the freelist. <a href="#aa5bff4e7767b1cee69df628fa5319fa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#addec8e14b0fbd90dd80040e5508ebd19">unlink</a> (const SMSNode &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink the node from its list. Returns the next node in the list. <a href="#addec8e14b0fbd90dd80040e5508ebd19">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d5c7c332cc0b999f4c9ebd6d8c78a7a">Dense</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SparseT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a677c556469b7f6237a95eefa14776f01">Sparse</a> = nullptr</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae3a33a15ec5113d36ae441f2a111daa3">Universe</a> = 0</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aef597c1d5e3f4d977307ce5bf69e3ffe">KeyIndexOf</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7cae4d2b1cf27f0463f51856ce7476af">ValIndexOf</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af825be22b4ef291e85ef0f74b0a840f6">FreelistIdx</a> = SMSNode::INVALID</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We have a built-in recycler for reusing tombstone slots. <a href="#af825be22b4ef291e85ef0f74b0a840f6">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1e9473acbb3ca404e3b57f2fc2afab2">NumFree</a> = 0</td>
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

<p>Fast multiset implementation for objects that can be identified by small unsigned keys.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> allocates memory proportional to the size of the key universe, so it is not recommended for building composite data structures. It is useful for algorithms that require a single set with fast operations.</p>


<p>Compared to <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a> and <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> provides constant-time fast <a href="#a2554bf4e6f211e29c3e80fd4c9141c79">clear()</a> as fast as a vector. The <a href="#a007d043f89bfaefaec158a7e93b39832">find()</a>, <a href="#a8586fb88f0c2e2236a1552292cba1dd3">insert()</a>, and <a href="#a3ab390f0c1123852f16664da01de672a">erase()</a> operations are all constant time, and typically faster than a hash table. The iteration order doesn't depend on numerical key values, it only depends on the order of <a href="#a8586fb88f0c2e2236a1552292cba1dd3">insert()</a> and <a href="#a3ab390f0c1123852f16664da01de672a">erase()</a> operations. Iteration order is the insertion order. Iteration is only provided over elements of equivalent keys, but iterators are bidirectional.</p>


<p>Compared to <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a>, SparseMultiSet&lt;unsigned&gt; uses 8x-40x more memory, but offers constant-time <a href="#a2554bf4e6f211e29c3e80fd4c9141c79">clear()</a> and <a href="#a5bb43880c7874561f71afdebbc59e2ed">size()</a> operations as well as fast iteration independent on the size of the universe.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> contains a dense vector holding all the objects and a sparse array holding indexes into the dense vector. Most of the memory is used by the sparse array which is the size of the key universe. The SparseT template parameter provides a space/speed tradeoff for sets holding many elements.</p>


<p>When SparseT is uint32_t, <a href="#a007d043f89bfaefaec158a7e93b39832">find()</a> only touches up to 3 cache lines, but the sparse array uses 4 x Universe bytes.</p>


<p>When SparseT is uint8_t (the default), <a href="#a007d043f89bfaefaec158a7e93b39832">find()</a> touches up to 3+[N/256] cache lines, but the sparse array is 4x smaller. N is the number of elements in the set.</p>


<p>For sets that may grow to thousands of elements, SparseT should be set to uint16_t or uint32_t.</p>


<p>Multiset behavior is provided by providing doubly linked lists for values that are inlined in the dense vector. <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> is a good choice when one desires a growable number of entries per key, as it will retain the <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> algorithmic properties despite being growable. Thus, it is often a better choice than a <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> of growable containers or a vector of vectors. <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> also keeps iterators valid after erasure (provided the iterators don't point to the element erased), allowing for more intuitive and fast removal.</p>


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

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a13be60676bc49a4629a0bfd8bf671174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::const_iterator =  iterator_base&lt;const SparseMultiSet *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### const\_pointer {#ad1badaaa7449797da1b668e687b6de23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::const_pointer =  const ValueT *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### const\_reference {#a8b3f3a95746eeb974958d3605c8c2521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::const_reference =  const ValueT &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### iterator {#ada97379dfb89c01fb4065e33bf180f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::iterator =  iterator_base&lt;SparseMultiSet *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### pointer {#a4cfb52a7ffa678488c329f891f823338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::pointer =  ValueT *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### RangePair {#aedf030829902cd1a8e3ed4a24820e3a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::RangePair =  std::pair&lt;iterator, iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### reference {#a5c3aafdeec18d298f96df3eb4b46ada2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::reference =  ValueT &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### size\_type {#a3a0e116fdaa2041ec3d61c9d110b0c2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::size_type =  unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### value\_type {#ab8dffcfeacb8cce39fd14cceadb3ceea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::value_type =  ValueT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### DenseT {#ab4ce4893dc34479447853671cf8b5253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::DenseT =  SmallVector&lt;SMSNode, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### KeyT {#ad039913e011b603056874997f4ccc438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::KeyT =  typename KeyFunctorT::argument_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SparseMultiSet() {#ac25748f56dc1c73fd9c021d5dbc751bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::SparseMultiSet ()</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### SparseMultiSet() {#a8943b7ab698dabcabebe73bb98fe340c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::SparseMultiSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> &amp;)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SparseMultiSet() {#ad48508707ac902124dfd05481728014f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::~SparseMultiSet ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aac9658f836f5eaea6f157afb14c7239a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseMultiSet &amp; llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sparsemultiset">SparseMultiSet</a> &amp;)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a2554bf4e6f211e29c3e80fd4c9141c79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::clear ()</td>
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

<p>Clears the set.</p>


<p>This is a very fast constant time operation.</p>


<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### contains() {#a14465cc22942098bf446b8d96d018cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>Returns true if this set contains an element identified by Key.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### count() {#a7f0300f83a134efc4ff02bb922d10cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::count (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>Returns the number of elements identified by Key.</p>


<p>This will be linear in the number of elements of that key.</p>


<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### empty() {#a02504d447f0362be1ffc1cc19f6e48ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::empty ()</td>
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

<p>Returns true if the set is empty.</p>


<p>This is not the same as <a href="/web-llvm/docs/api/classes/llvm/bitvector/#ae308e6ee93ceb33e921d72d659230669">BitVector::empty()</a>.</p>


<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>


<p>Referenced by <a href="#af781b01667ff848f2b07b4b51660a714">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::setUniverse</a>.</p>

</div>
</div>

### end() {#a6123d1aa335e5d9c6299050c2cc5193e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::end ()</td>
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

<p>Returns an iterator past this container.</p>


<p>Note that such an iterator cannot be decremented, but will compare equal to other end iterators.</p>


<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>


<p>Referenced by <a href="#a14465cc22942098bf446b8d96d018cd4">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::contains</a>, <a href="#a7f0300f83a134efc4ff02bb922d10cd2">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::count</a>, <a href="#ab911382d02334b8421f4dbca8c53ff27">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::eraseAll</a>, <a href="#a16a780296035cd55839932310e5dc672">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::findIndex</a>, <a href="#aa107631835001303a52fc79b695d2f41">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::getTail</a> and <a href="#a8586fb88f0c2e2236a1552292cba1dd3">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::insert</a>.</p>

</div>
</div>

### end() {#a9dc8a38575ad6af2633fd5bd0e7aba9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::end ()</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### equal\_range() {#ac92517e8c9066cbd446b0589a50c16f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RangePair llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::equal_range (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; K)</td>
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

<p>The bounds of the range of items sharing Key K.</p>


<p>First member is the head of the list, and the second member is a decrementable end iterator for that key.</p>


<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### erase() {#a3ab390f0c1123852f16664da01de672a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::erase (<a href="#ada97379dfb89c01fb4065e33bf180f0e">iterator</a> I)</td>
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

<p>Erases an existing element identified by a valid iterator.</p>


<p>This invalidates iterators pointing at the same entry, but <a href="#a3ab390f0c1123852f16664da01de672a">erase()</a> returns an iterator pointing to the next element in the subset's list. This makes it possible to erase selected elements while iterating over the subset:</p>


<p>tie(I, E) = Set.equal_range(Key); while (I != E) if (<a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test(*I)</a>) I = Set.erase(I); else ++I;</p>


<p>Note that if the last element in the subset list is erased, this will return an end iterator which can be decremented to get the new tail (if it exists):</p>


<p>tie(B, I) = Set.equal_range(Key); for (bool isBegin = B == I; !isBegin; /* empty *‍/) { isBegin = (–I) == B; if (<a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test(I)</a>) break; I = erase(I); }</p>


<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>


<p>Referenced by <a href="#ab911382d02334b8421f4dbca8c53ff27">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::eraseAll</a>.</p>

</div>
</div>

### eraseAll() {#ab911382d02334b8421f4dbca8c53ff27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::eraseAll (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; K)</td>
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

<p>Erase all elements with the given key.</p>


<p>This invalidates all iterators of that key.</p>


<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### find() {#a007d043f89bfaefaec158a7e93b39832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>Find an element by its key.</p>


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
<dd><p>An iterator to the element identified by key, or <a href="#a6123d1aa335e5d9c6299050c2cc5193e">end()</a>.</p></dd>
</dl>


<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>


<p>Referenced by <a href="#a14465cc22942098bf446b8d96d018cd4">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::contains</a>, <a href="#a7f0300f83a134efc4ff02bb922d10cd2">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::count</a>, <a href="#ac92517e8c9066cbd446b0589a50c16f6">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::equal_range</a>, <a href="#ab911382d02334b8421f4dbca8c53ff27">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::eraseAll</a>, <a href="#a9bbecf0bb2b7cc5819bb54f53fbf4622">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::getHead</a> and <a href="#aa107631835001303a52fc79b695d2f41">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::getTail</a>.</p>

</div>
</div>

### find() {#a61aff372ad2255f01e286bc010c9f575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### findIndex() {#a16a780296035cd55839932310e5dc672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::findIndex (unsigned Idx)</td>
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

<p>Find an element by its index.</p>


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
<dd><p>An iterator to the element identified by key, or <a href="#a6123d1aa335e5d9c6299050c2cc5193e">end()</a>.</p></dd>
</dl>


<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>


<p>Referenced by <a href="#a007d043f89bfaefaec158a7e93b39832">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::find</a>, <a href="#a61aff372ad2255f01e286bc010c9f575">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::find</a> and <a href="#a8586fb88f0c2e2236a1552292cba1dd3">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::insert</a>.</p>

</div>
</div>

### getHead() {#a9bbecf0bb2b7cc5819bb54f53fbf4622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::getHead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>Return the head and tail of the subset's list, otherwise returns <a href="#a6123d1aa335e5d9c6299050c2cc5193e">end()</a>.</p>

<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### getTail() {#aa107631835001303a52fc79b695d2f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::getTail (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### insert() {#a8586fb88f0c2e2236a1552292cba1dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT &amp; Val)</td>
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

<p>Insert a new element at the tail of the subset list.</p>


<p>Returns an iterator to the newly added entry.</p>


<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### setUniverse() {#af781b01667ff848f2b07b4b51660a714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::setUniverse (unsigned U)</td>
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

<p>Set the universe size which determines the largest key the set can hold.</p>


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

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### size() {#a5bb43880c7874561f71afdebbc59e2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::size ()</td>
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

<p>Returns the number of elements in the set.</p>


<p>This is not the same as <a href="/web-llvm/docs/api/classes/llvm/bitvector/#abf86e1383aec181a5a2d9967eb8070fd">BitVector::size()</a> which returns the size of the universe.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>


<p>Referenced by <a href="#a02504d447f0362be1ffc1cc19f6e48ef">llvm::SparseMultiSet&lt; PhysRegSUOper, identity&lt; unsigned &gt;, uint16_t &gt;::empty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addValue() {#a8187526ec61c0b1bcc4b402c702793e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::addValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT &amp; V, unsigned Prev, unsigned Next)</td>
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

<p>Add in the given SMSNode.</p>


<p>Uses a free entry in our freelist if available. Returns the index of the added node.</p>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### isHead() {#a976d6c2891a6abc45814f504c0b8ea68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::isHead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SMSNode &amp; D)</td>
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

<p>Whether the given entry is the head of the list.</p>


<p>List heads's previous pointers are to the tail of the list, allowing for efficient access to the list tail. D must be a valid entry node.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### isSingleton() {#afd07013b976c74dc76fc24246a182e15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::isSingleton (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SMSNode &amp; N)</td>
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

<p>Whether the given entry is a singleton entry, i.e.</p>


<p>the only entry with that key.</p>


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### makeTombstone() {#aa5bff4e7767b1cee69df628fa5319fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::makeTombstone (unsigned Idx)</td>
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

<p>Make the current index a new tombstone. Pushes it onto the freelist.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### sparseIndex() {#a6c283a279de2c059b44b47055902d931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::sparseIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT &amp; Val)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### sparseIndex() {#a616152c51e1d8fa2afc6fb4da430356f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::sparseIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SMSNode &amp; N)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### unlink() {#addec8e14b0fbd90dd80040e5508ebd19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::unlink (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SMSNode &amp; N)</td>
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

<p>Unlink the node from its list. Returns the next node in the list.</p>

<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Dense {#a3d5c7c332cc0b999f4c9ebd6d8c78a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseT llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::Dense</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### FreelistIdx {#af825be22b4ef291e85ef0f74b0a840f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::FreelistIdx = SMSNode::INVALID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We have a built-in recycler for reusing tombstone slots.</p>


<p>This recycler puts a singly-linked free list into tombstone slots, allowing us quick erasure, iterator preservation, and dense size.</p>


<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### KeyIndexOf {#aef597c1d5e3f4d977307ce5bf69e3ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyFunctorT llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::KeyIndexOf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### NumFree {#ac1e9473acbb3ca404e3b57f2fc2afab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::NumFree = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### Sparse {#a677c556469b7f6237a95eefa14776f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseT* llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::Sparse = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### Universe {#ae3a33a15ec5113d36ae441f2a111daa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::Universe = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

### ValIndexOf {#a7cae4d2b1cf27f0463f51856ce7476af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename KeyFunctorT = identity&lt;unsigned&gt;, typename SparseT = uint8_t&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseSetValFunctor&lt;KeyT, ValueT, KeyFunctorT&gt; llvm::SparseMultiSet&lt; ValueT, KeyFunctorT, SparseT &gt;::ValIndexOf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparsemultiset-h">SparseMultiSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
