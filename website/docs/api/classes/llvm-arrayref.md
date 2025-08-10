---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/arrayref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ArrayRef` Class Template

<p><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> - Represent a constant reference to an array (0 or more elements consecutively in memory), i.e. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
class llvm::ArrayRef&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> - Represent a mutable reference to an array (0 or more elements consecutively in memory), i.e. <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab794baf0d9b92bdff1765d980cf53333">value_type</a> = T</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7fcb22539771f789c2a1439e8131cd1e">pointer</a> = <a href="#ab794baf0d9b92bdff1765d980cf53333">value_type</a> *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46d7c243a28c897d546d59eebc6bbacb">const_pointer</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab794baf0d9b92bdff1765d980cf53333">value_type</a> *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a96ad297002cade6d780c4a282cf6bf62">reference</a> = <a href="#ab794baf0d9b92bdff1765d980cf53333">value_type</a> &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7db8f9b26a3ad04cb2ed18789cb47ade">const_reference</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab794baf0d9b92bdff1765d980cf53333">value_type</a> &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b76b9e6f7d06ec15424e309cf440114">iterator</a> = <a href="#a46d7c243a28c897d546d59eebc6bbacb">const_pointer</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a715fffff3fee0a42f5e52853b4b5b57f">const_iterator</a> = <a href="#a46d7c243a28c897d546d59eebc6bbacb">const_pointer</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4026d0f8ff7f9b60d601d1df7e3e05d">reverse_iterator</a> = std::reverse_iterator&lt; <a href="#a9b76b9e6f7d06ec15424e309cf440114">iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a797c189a2a197f9100f54e2943c96ac8">const_reverse_iterator</a> = std::reverse_iterator&lt; <a href="#a715fffff3fee0a42f5e52853b4b5b57f">const_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14feba3df516c82f8e016374ef4df18b">size_type</a> = size_t</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6133c18bfaf8ba4653d32ffa0d8c10f7">difference_type</a> = ptrdiff_t</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5042834fd1ff61518d8fc567e0e5b51">Data</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The start of the array, in an external buffer. <a href="#af5042834fd1ff61518d8fc567e0e5b51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a14feba3df516c82f8e016374ef4df18b">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe5882244f634402dc01972eae0768a2">Length</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of elements. <a href="#afe5882244f634402dc01972eae0768a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8c5a80e84453eb1a2e851a6c3c92fafd">ArrayRef</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>. <a href="#a8c5a80e84453eb1a2e851a6c3c92fafd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa1459c8bf806db60a9a1c2d11f95536d">ArrayRef</a> (std::nullopt_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from std::nullopt. <a href="#aa1459c8bf806db60a9a1c2d11f95536d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7297c362c4fd96749704f50f1212b823">ArrayRef</a> (const T &amp;OneElt LLVM_LIFETIME_BOUND)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a single element. <a href="#a7297c362c4fd96749704f50f1212b823">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad7dbf1c52893ca8a5fbc208cd5dc2d30">ArrayRef</a> (const T *data LLVM_LIFETIME_BOUND, size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a pointer and length. <a href="#ad7dbf1c52893ca8a5fbc208cd5dc2d30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a787c29c3a723fb96a96cb892c6e4f107">ArrayRef</a> (const T *begin LLVM_LIFETIME_BOUND, const T *end)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a range. <a href="#a787c29c3a723fb96a96cb892c6e4f107">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename U&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#afc866cca8f91f84722e2ef9df16e4543">ArrayRef</a> (const SmallVectorTemplateCommon&lt; T, U &gt; &amp;Vec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>. <a href="#afc866cca8f91f84722e2ef9df16e4543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename A&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad988e5c79df06504e45adaa0b69cf3fa">ArrayRef</a> (const std::vector&lt; T, A &gt; &amp;Vec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a std::vector. <a href="#ad988e5c79df06504e45adaa0b69cf3fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abce7d9de986edb50fb9673e5015917b0">ArrayRef</a> (const std::array&lt; T, N &gt; &amp;Arr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a std::array. <a href="#abce7d9de986edb50fb9673e5015917b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acbeaf6660fa6a272706c71336f0a77b7">ArrayRef</a> (const T(&amp;Arr LLVM_LIFETIME_BOUND)[N])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a C array. <a href="#acbeaf6660fa6a272706c71336f0a77b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a350c562c4e7b8cde89380600c0902617">ArrayRef</a> (std::initializer_list&lt; T &gt; Vec LLVM_LIFETIME_BOUND)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a std::initializer_list. <a href="#a350c562c4e7b8cde89380600c0902617">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename U&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa18328052508718437be128fb36bf70a">ArrayRef</a> (const ArrayRef&lt; U * &gt; &amp;A, std::enable_if_t&lt; std::is_convertible&lt; U *const *, T const * &gt;::value &gt; *=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an ArrayRef&lt;const T*&gt; from ArrayRef&lt;T*&gt;. <a href="#aa18328052508718437be128fb36bf70a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename U, typename DummyT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad27c1cecd81e377baef49e7b383db7bd">ArrayRef</a> (const SmallVectorTemplateCommon&lt; U *, DummyT &gt; &amp;Vec, std::enable_if_t&lt; std::is_convertible&lt; U *const *, T const * &gt;::value &gt; *=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an ArrayRef&lt;const T*&gt; from a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;T*&gt;</a>. <a href="#ad27c1cecd81e377baef49e7b383db7bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename U, typename A&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a31cf6428fd4c3f86cd053885dd280c22">ArrayRef</a> (const std::vector&lt; U *, A &gt; &amp;Vec, std::enable_if_t&lt; std::is_convertible&lt; U *const *, T const * &gt;::value &gt; *=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an ArrayRef&lt;const T*&gt; from std::vector&lt;T*&gt;. <a href="#a31cf6428fd4c3f86cd053885dd280c22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Simple Operations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9b76b9e6f7d06ec15424e309cf440114">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab36927882fbfdcbb860d87fd9c30da8">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9b76b9e6f7d06ec15424e309cf440114">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ca5197533a9c1fb8a2bd30587fcec6b">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa4026d0f8ff7f9b60d601d1df7e3e05d">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aebe6da1ab4a07020669f3d6148c0b559">rbegin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa4026d0f8ff7f9b60d601d1df7e3e05d">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a709f5d7f042648ec20197939d9a6805f">rend</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac835b8735b1b2faec0efdca236e37d94">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>empty - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the array is empty. <a href="#ac835b8735b1b2faec0efdca236e37d94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adb9cab4abca6bf2855c882dcf79fb1cb">data</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85ffb6531d4cda988ea81f18d4e56fb7">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>size - Get the array size. <a href="#a85ffb6531d4cda988ea81f18d4e56fb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a721fc555cb3d8dc2a1a680dcc2ce69b2">front</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>front - Get the first element. <a href="#a721fc555cb3d8dc2a1a680dcc2ce69b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a291ac49156942529f159a9ec003cc25f">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>back - Get the last element. <a href="#a291ac49156942529f159a9ec003cc25f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Allocator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a40ef749f57b30897cbc9ac66edeae908">copy</a> (Allocator &amp;A) -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21ff1fd12b25b79fcd4449c35dc814b6">equals</a> (ArrayRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>equals - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for element-wise equality. <a href="#a21ff1fd12b25b79fcd4449c35dc814b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aebf6ca7590d4f766b894044015a0fa31">slice</a> (size_t N, size_t M) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>slice(n, m) - Chop off the first N elements of the array, and keep M elements in the array. <a href="#aebf6ca7590d4f766b894044015a0fa31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c498de3bb758473707e9198311eb15f">slice</a> (size_t N) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>slice(n) - Chop off the first N elements of the array. <a href="#a5c498de3bb758473707e9198311eb15f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a55089293ebaccd683a82d97170041376">drop_front</a> (size_t N=1) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop the first <span class="doxyComputerOutput">N</span> elements of the array. <a href="#a55089293ebaccd683a82d97170041376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa713e2599e000adc01ced998c05502a7">drop_back</a> (size_t N=1) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop the last <span class="doxyComputerOutput">N</span> elements of the array. <a href="#aa713e2599e000adc01ced998c05502a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PredicateT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27505108d9768764055066869464f7b6">drop_while</a> (PredicateT Pred) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a copy of *this with the first N elements satisfying the given predicate removed. <a href="#a27505108d9768764055066869464f7b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PredicateT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82363b1979b08c15184249052cd81250">drop_until</a> (PredicateT Pred) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a copy of *this with the first N elements not satisfying the given predicate removed. <a href="#a82363b1979b08c15184249052cd81250">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a33da2ddf6f447892591c86d9d3771b9c">take_front</a> (size_t N=1) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a copy of *this with only the first <span class="doxyComputerOutput">N</span> elements. <a href="#a33da2ddf6f447892591c86d9d3771b9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1f72f67a93986bb68c8b7f8a2dba4ba">take_back</a> (size_t N=1) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a copy of *this with only the last <span class="doxyComputerOutput">N</span> elements. <a href="#ac1f72f67a93986bb68c8b7f8a2dba4ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PredicateT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a725ac4896f684f75ab69391e11ae9b43">take_while</a> (PredicateT Pred) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first N elements of this Array that satisfy the given predicate. <a href="#a725ac4896f684f75ab69391e11ae9b43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PredicateT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a80e3c4f2aa4ad50e0d9b606187fc9074">take_until</a> (PredicateT Pred) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first N elements of this Array that don't satisfy the given predicate. <a href="#a80e3c4f2aa4ad50e0d9b606187fc9074">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Operator Overloads Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad8bda555014f88be8886b8e4694e2c78">operator[]</a> (size_t Index) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename U&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9210a8d36502f3d090838bdda24f3f4">operator=</a> (U &amp;&amp;Temporary)=delete -&gt; std::enable_if_t&lt; std::is_same&lt; U, T &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disallow accidental assignment from a temporary. <a href="#ae9210a8d36502f3d090838bdda24f3f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename U&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a060ed5ac235d16662fe2409975c07773">operator=</a> (std::initializer_list&lt; U &gt;)=delete -&gt; std::enable_if_t&lt; std::is_same&lt; U, T &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disallow accidental assignment from a temporary. <a href="#a060ed5ac235d16662fe2409975c07773">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Expensive Operations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d0fa3771a3eafd8df26bca2518b5ad7">vec</a> () const -&gt; std::vector&lt; T &gt;</td>
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

## Conversion operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a745a0df36a633dcbc4acfd0bf9dffe17">operator std::vector&lt; T &gt;</a> () const</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> - Represent a constant reference to an array (0 or more elements consecutively in memory), i.e.</p>


<p>a start pointer and a length. It allows various APIs to take consecutive elements easily and conveniently.</p>


<p>This class does not own the underlying data, it is expected to be used in situations where the data resides in some other buffer, whose lifetime extends past that of the <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>. For this reason, it is not in general safe to store an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>.</p>


<p>This is intended to be trivially copyable, so it should be passed by value.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a715fffff3fee0a42f5e52853b4b5b57f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::const_iterator =  const_pointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### const\_pointer {#a46d7c243a28c897d546d59eebc6bbacb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::const_pointer =  const value_type *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### const\_reference {#a7db8f9b26a3ad04cb2ed18789cb47ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::const_reference =  const value_type &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#a797c189a2a197f9100f54e2943c96ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::const_reverse_iterator =  std::reverse_iterator&lt;const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### difference\_type {#a6133c18bfaf8ba4653d32ffa0d8c10f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::difference_type =  ptrdiff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### iterator {#a9b76b9e6f7d06ec15424e309cf440114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::iterator =  const_pointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### pointer {#a7fcb22539771f789c2a1439e8131cd1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::pointer =  value_type *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### reference {#a96ad297002cade6d780c4a282cf6bf62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::reference =  value_type &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### reverse\_iterator {#aa4026d0f8ff7f9b60d601d1df7e3e05d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::reverse_iterator =  std::reverse_iterator&lt;iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### size\_type {#a14feba3df516c82f8e016374ef4df18b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::size_type =  size_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### value\_type {#ab794baf0d9b92bdff1765d980cf53333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ArrayRef&lt; T &gt;::value_type =  T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Data {#af5042834fd1ff61518d8fc567e0e5b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T* llvm::ArrayRef&lt; T &gt;::Data = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The start of the array, in an external buffer.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### Length {#afe5882244f634402dc01972eae0768a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::ArrayRef&lt; T &gt;::Length = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of elements.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Constructors

### ArrayRef {#a8c5a80e84453eb1a2e851a6c3c92fafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef ()</td>
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

<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#aa1459c8bf806db60a9a1c2d11f95536d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (std::nullopt_t)</td>
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

<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from std::nullopt.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#a7297c362c4fd96749704f50f1212b823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;OneElt LLVM_LIFETIME_BOUND)</td>
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

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a single element.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#ad7dbf1c52893ca8a5fbc208cd5dc2d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *<a href="#adb9cab4abca6bf2855c882dcf79fb1cb">data</a> LLVM_LIFETIME_BOUND, size_t length)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a pointer and length.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#a787c29c3a723fb96a96cb892c6e4f107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *<a href="#aab36927882fbfdcbb860d87fd9c30da8">begin</a> LLVM_LIFETIME_BOUND, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * end)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a range.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#afc866cca8f91f84722e2ef9df16e4543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename U&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon">SmallVectorTemplateCommon</a>&lt; T, U &gt; &amp; Vec)</td>
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

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>.</p>


<p>This is templated in order to avoid instantiating <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon">SmallVectorTemplateCommon&lt;T&gt;</a> whenever we copy-construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>.</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#ad988e5c79df06504e45adaa0b69cf3fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename A&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; T, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> &gt; &amp; Vec)</td>
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

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a std::vector.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#abce7d9de986edb50fb9673e5015917b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::array&lt; T, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt; &amp; Arr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a std::array.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#acbeaf6660fa6a272706c71336f0a77b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T(&amp;) LLVM_LIFETIME_BOUND=[N])</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a C array.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#a350c562c4e7b8cde89380600c0902617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (std::initializer_list&lt; T &gt; Vec LLVM_LIFETIME_BOUND)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> from a std::initializer_list.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#aa18328052508718437be128fb36bf70a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename U&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; U * &gt; &amp; A, std::enable_if_t&lt; std::is_convertible&lt; U *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *, T <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * &gt;::value &gt; *)</td>
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

<p>Construct an ArrayRef&lt;const T*&gt; from ArrayRef&lt;T*&gt;.</p>


<p>This uses SFINAE to ensure that only ArrayRefs of pointers can be converted.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#ad27c1cecd81e377baef49e7b383db7bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename U, typename DummyT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon">SmallVectorTemplateCommon</a>&lt; U *, DummyT &gt; &amp; Vec, std::enable_if_t&lt; std::is_convertible&lt; U *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *, T <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * &gt;::value &gt; *)</td>
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

<p>Construct an ArrayRef&lt;const T*&gt; from a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;T*&gt;</a>.</p>


<p>This is templated in order to avoid instantiating <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon">SmallVectorTemplateCommon&lt;T&gt;</a> whenever we copy-construct an <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>.</p>


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### ArrayRef {#a31cf6428fd4c3f86cd053885dd280c22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename U, typename A&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::ArrayRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; U *, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> &gt; &amp; Vec, std::enable_if_t&lt; std::is_convertible&lt; U *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *, T <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * &gt;::value &gt; *)</td>
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

<p>Construct an ArrayRef&lt;const T*&gt; from std::vector&lt;T*&gt;.</p>


<p>This uses SFINAE to ensure that only vectors of pointers can be converted.</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Simple Operations

### back {#a291ac49156942529f159a9ec003cc25f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; llvm::ArrayRef&lt; T &gt;::back ()</td>
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

<p>back - Get the last element.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a3f1e8df5d1ec58e81979760331f7808e">llvm::AttributeList::addParamAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ac255b2b7ff59963227ea39e1d176f63a">llvm::DIExpression::appendToStack</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a993771e7c58c60044cbc4c57f689406e">llvm::RandomIRBuilder::connectToSink</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#ae8f7b3435e5d6a7132e2e0aba6b347e7">llvm::Record::getDirectSuperClasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aa28651c1e85585ae702f652a8df06019">isSwitchDense</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a679d0966b3083f647af785f24936d3d9">llvm::RandomIRBuilder::newSink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a8263d385de2b406acf8dbef9b0993cc9">llvm::orc::shared::runDeallocActions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### begin {#aab36927882fbfdcbb860d87fd9c30da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ArrayRef&lt; T &gt;::begin ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#a0c3e8ed752bc7ef92ccb9edbd4bb014a">llvm::lto::LTO::add</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#afbe3c388c22fe55467e7f2847d7ec2fd">llvm::SubtargetFeatures::addFeaturesVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae122b7b9960cfd970b1d5c0d83f22039">addMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a3c04d483e66e81efc4812a2d38b93a8d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::addStackNodesForMIB</a>, <a href="/web-llvm/docs/api/classes/llvm/debuglocentry/#a5df10bc170330b17e46917b60c38cf04">llvm::DebugLocEntry::addValues</a>, <a href="/web-llvm/docs/api/classes/llvm/object/dynamicrelocref/#a14e72d8da8272877aec734b67972a0eb">llvm::object::DynamicRelocRef::arm64x_reloc_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#ac7dcecb4ce0bf73a49d45fd5da8ec84a">llvm::DIExpressionCursor::assignNewExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a987811f4399e448a9e1223ee373c1e00">buildFixItLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a646829664451eb913bfa2f92920478ea">calcPredicateUsingInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a7e36a63781989accf846f2e78f510d33">llvm::Interpreter::callFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#ade8a5e3b6a082e4cb8bb4202ae7f652a">canonicalizeDwarfOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe9c37f2ba2d21ae9e526ecec89d431d">llvm::collectGlobalObjectNameStrings</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a0fccac895976ea41f8038b07e18389">llvm::ComputeLinearIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleloopsafetyinfo/#a262c2df9639d3f71b8d2a8158b819809">llvm::SimpleLoopSafetyInfo::computeLoopSafetyInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4288169d91ab0f0f01405115fd2931a7">llvm::concatenateVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelistattributeimpl/#aba61e4f1fe75fe73a617ed967ba11478">llvm::ConstantRangeListAttributeImpl::ConstantRangeListAttributeImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa39d4ce88555d804615c0cd225d9fcb6">llvm::convertUTF32ToUTF8String</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ace7e2f01b65afba76343f22d042a12df">CreateGCRelocates</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addf42fea14164ec994d4d517eaa56688">llvm::DeleteDeadBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9c5f771f232bbd4cf6ec230bd78f9174">llvm::Instruction::dropUnknownNonDebugMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a54244237156023415444d12acb4f2829">llvm::DIExpression::elements_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a42a0cfa56ebe2de750170da9db67f927">llvm::BitstreamWriter::emitBlob</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae29b7bb67763c63132e57471f88ac80f">llvm::FindInsertedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a15fc36bf8d33e06423d939bb34bc9305">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a181dad1cdd60a83a181108d90acd4738">llvm::CondOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a8068bfe8ffd6450e61e72665e6887abc">llvm::DagInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#afe6e63cc76f08a5400707ae311ca1cfd">llvm::gsym::GsymReader::getAddressOffsetIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a9205d579e79767f52c5af57c94d2be74">llvm::omp::getCompoundConstruct</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a331caeb70809f50e71528de06fba7b66">llvm::StructLayout::getElementContainingOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a8528b1c4543692486b82ac9012c1617b">llvm::HexagonRegisterInfo::getHexagonSubRegIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a7d9301f2db70078a258c683a1046f569">llvm::ARMBaseRegisterInfo::getLargestLegalSuperClass</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a842441ec6290263363da4edef875b5c5">llvm::X86RegisterInfo::getLargestLegalSuperClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a433702fa6f12e3710e21ed0fde2a69b0">llvm::omp::getLeafOrCompositeConstructs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ade3b3b604b9b365a57f791ab198a691a">getNoopInput</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debuginfosupport-cpp-/#af708da9529b70292b2712cd7ed80d14e">anonymous{DebugInfoSupport.cpp}::getSectionData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac947597e4f7b21eda127d16de828a5eb">llvm::getShuffleMaskWithWidestElts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3373a145daacecd10f10f8d9622a2114">llvm::hash_value</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a30d8d29c9510e2f8b7f6244979fc9376">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphscc/#a87e1b8515d22eb833375761e19a2d0fe">llvm::CallGraphSCC::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a4d055efabadfeaf759463d4edf2c2207">llvm::RegPressureTracker::initLiveThru</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslices/#a9d50c642270c265bdb2af02bf6d4eed0">anonymous{SROA.cpp}::AllocaSlices::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#ad444e7dc0b30ff2af7e7e3362287f291">llvm::AppendingBinaryByteStream::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a61ef13844d0a136295d9a3acfcf51363">llvm::omp::isCompositeConstruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ad5d72247c1a3137bc2c2c7aaf0000b03">isFixedVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a4e12c0cb71a44b8822c5a35cbbe5c731">llvm::LiveRange::isLiveAtIndexes</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ac4d13f5ea905de676278414d7f7c2601">isSubset</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#a91d6d8d5af0b8ba44a006860ef830113">llvm::coverage::CoverageMapping::load</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ae071c2a56ff28186d5476e562811b2f7">lookupLLVMIntrinsicByName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a22c6a7a1925a0177519e33d49ba91cea">llvm::RISCVTargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a602b901d40f2b6bc5bf489a131309eef">lowerShuffleViaVRegSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a96929c573ae5a98213a4d8c25554e53f">lowerV8I16GeneralSingleInputShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8a1ae2e1de53a840bee516d1f5bb173">llvm::makePostTransformationMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a97074acd3a969b0eb7a6a730c5a1c8f3">llvm::codeview::CodeViewRecordIO::mapByteVectorTail</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a627f84abfceb75ffd72119423d0147a4">mergeVectorRegsToResultRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/#a0a36278d58291d94abb79e3c42b0da80">llvm::ImmutableGraph&lt; MachineInstr *, int &gt;::nodes_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#a8949a90af3c69d31f132d6933c4d5914">optimizeDwarfOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a93f122dff654f8336680531a3898375c">llvm::CallBase::populateBundleOperandInfos</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a85549679782ae212e691a7edfe985550">ProfileCondOpInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#ad69191edb241ddc1918363da6d6b14d1">ProfileDagInit</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-e92e567fbcfc8afd44242d623ff29b96/#a8609213d38c69d46947c06400e50e094">llvm::detail::BCRecordCoding&lt; BCArray&lt; ElementTy &gt; &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a1cbc5251f13ad42510760ed61c71e874">llvm::BinaryStreamReader::readCString</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aac42f02dfb2a8bbe2f6bedea0ff7b29c">llvm::BinaryStreamReader::readFixedString</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af0ce60c4a958016f62ce78f1eda423af">removeUnusedBlocksFromParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a64261c5840053afd36cfbb72666ace95">anonymous{ValueMapper.cpp}::Mapper::scheduleMapAppendingVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a9bbfc66d078e240930409cc562753881">llvm::SDDbgValue::SDDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6f526a87cef7533f13e0a80937776c20">llvm::MachineFunction::setCallSiteLandingPad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a6ac158cfb39dae5f6514d2508e735115">llvm::X86MachineFunctionInfo::setPreallocatedArgOffsets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad272ce4631595e235e560baf59dc1ffd">llvm::setProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#ab85ea74b3cb2aeabcf765b1892ff9d91">llvm::gsym::GsymCreator::setUUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#afb0d2b520c6cf9984ec6a40e7af31dca">stackFrameIncludesInlinedCallStack</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scheduler/#a9c67d906d22a6018e3ff649bafed6a1a">llvm::sandboxir::Scheduler::trySchedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#ae8bfab8841d5d8482833437e8b4309b9">shuffles::vdealvdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/misexpect/#a8677c5d2618fcf52eda43f5530decb6b">llvm::misexpect::verifyMisExpect</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a2337e506453c5ed1ec20ebabbafbc014">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a05231a6703f721a7938ce95de41743f1">shuffles::vshuffvdd</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ae6b63bcaa1f6638b608f911cd04341e2">llvm::MemorySSAUpdater::wireOldPredecessorsToNewImmediatePredecessor</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a2b96fb8bf782a1b498a82682ab8e74c9">writeToResolutionFile</a>.</p>

</div>
</div>

### copy {#a40ef749f57b30897cbc9ac66edeae908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Allocator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::copy (<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a> &amp; A)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### data {#adb9cab4abca6bf2855c882dcf79fb1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * llvm::ArrayRef&lt; T &gt;::data ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsection/#a6a2a290a120bc84d74855227e361b9ad">llvm::codeview::DebugChecksumsSubsection::addChecksum</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aebcf13b2162f23607396fffbf2b6ef7e">analyzeHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#ab3e5050d43a1deb05a2878c74eb99abd">llvm::orc::SelfExecutorProcessControl::callWrapperAsync</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a00f85301e155c37fcab125f50a67cfb4">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneBlockAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a491cbe61681e7c63ac7d01ce209a4682">llvm::ConstantFoldGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a6e3f70a5f3d1222550716fb9db632c6a">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#a992787f0142954b821c221ff5a2c921f">llvm::symbolize::anonymous{Symbolize.cpp}::darwinDsymMatchesBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a0bf5f8e45bfccb0805b5e12d44622271">llvm::MutableArrayRef&lt; uint8_t &gt;::data</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a6c25c8fa1e18bfa4689e9982991c9791">discoverTypeIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a25991c233686a63c58cc75b2fc0d9a5f">discoverTypeIndices</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a472577b022e0997fbd409d82078df025">llvm::codeview::discoverTypeIndices</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aec9651c2f12f43fcdf5d88492040e24b">llvm::codeview::discoverTypeIndicesInSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a00c8a16f00462fc9765f5922f3ba761c">llvm::object::doesXCOFFTracebackTableBegin</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a180f88c410e11a7df7b17e9a782197e2">dumpLocationExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a434621cd1f8f1c0240a47b65ba19ea9b">eat12Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a7d8ee6944c8121c49c2a8da4b1695fe7">eat16Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aaff8a7b712c8ea0bb1275e621119e498">eatBytes</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mctargetdesc-cpp-/aarch64mcinstranalysis/#ab74d7f466279e42ef6ac5ba405ef4301">anonymous{AArch64MCTargetDesc.cpp}::AArch64MCInstrAnalysis::findPltEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#a9dc8dda7e6f1c6adc7eaaf755f6c27a5">llvm::X86_MC::findX86_64PltEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#aa32860b6f507582db22346076bf5caa0">llvm::X86_MC::findX86PltEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38f536657a01f40d99f770fddee8e14a">llvm::codeview::forEachCodeViewRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee5f6b149b3f5ee5ed6ad7db9b58b148">llvm::fullyRecomputeLiveIns</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a4a1000e5803e731e9dcc572042a98a0b">llvm::ConstantDataArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a79459acee890c44fac5c279584480b08">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a2b15feb32345af4916487fa3fa9d6227">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a0ad360dbce483cc0903211b623b9debd">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ae5bc9cac664aeb67c181f9add7309cfa">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a8ee97870547b76f8387091128a00e90c">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ab8b693ee2fbb4c4173fa2725c110021b">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a746052f3a8d6068791b8fc33a2dd0c64">llvm::codeview::getBytesAsCharacters</a>, <a href="/web-llvm/docs/api/classes/llvm/object/resourcesectionref/#acda81c3c28377b5e191fbfdd745d6644">llvm::object::ResourceSectionRef::getContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ae18b7d7be4354e3df59467ddf7d35c63">llvm::object::COFFObjectFile::getDebugPDBInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ae6bcc7c94e3742c313341e5883ac618d">getExpressionFrameOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a6eec77c77aa76611db6766a3f205570c">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a54e552ee615150b4efe5195ac45d4389">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a3d4228cf6f5c478449deca90c6ce2255">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#acc193957138fece590fe07417912f018">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aeecde9516e68842cb97c340bb693a7a9">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aa736794cd9a0acefdb428c5ed892a66f">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-764fe38a670fa71a18e1c5f119bcef9d/#a2895334c043839ae91cec9fc7eb3eded">llvm::DenseMapInfo&lt; ArrayRef&lt; T &gt;, void &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskydisassembler-cpp-/cskydisassembler/#ab02ac21009a84db6e0a786c08e2be1b5">anonymous{CSKYDisassembler.cpp}::CSKYDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdisassembler-cpp-/loongarchdisassembler/#a38b30661f2481e385870d52d8cc9e996">anonymous{LoongArchDisassembler.cpp}::LoongArchDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430disassembler-cpp-/msp430disassembler/#a55019fcf219b7cac44ca62e49a0eeb6a">anonymous{MSP430Disassembler.cpp}::MSP430Disassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcdisassembler-cpp-/ppcdisassembler/#aae7fc67fba3d73dc2dfe4a44f5e399af">anonymous{PPCDisassembler.cpp}::PPCDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/structs/m68kdisassembler/#a148939039bc8201973e8931087aa62a6">M68kDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp/#a8aac3d1bd9fe9005fb56a087e0a824e2">getLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a647f0ec13a56dcdcf59ff036090db193">llvm::object::MachOObjectFile::getSectionFinalSegmentName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ac459e969de113b3d211c0a4087656dc7">llvm::object::MachOObjectFile::getSectionName</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#ad11c85a64a9aca0f5035553171364591">llvm::MipsTargetLowering::HandleByVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#abbb20c80e0c1ab59446de978f898fc1e">handleMethodOverloadList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aa7574b8c35b165904ab21971f6f786a1">llvm::pdb::hashStringV2</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#adeacac9b0dabeafe536c99c4c3151fef">llvm::HexagonTargetLowering::LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a62ff5ad430418e75c001811d0c3a976c">llvm::codeview::CodeViewRecordIO::mapGuid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/disassembler/webassemblydisassembler-cpp/#a65e13c057217c221d060184d88638f07">nextLEB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/disassembler/webassemblydisassembler-cpp/#ae6a0d5accd0cfdbb19d3201773677035">parseImmediate</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/permnetwork/#a783d5995993cd1da9450a50b1a9f3281">anonymous{HexagonISelDAGToDAGHVX.cpp}::PermNetwork::PermNetwork</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab88a8b3835c1028f8fd6c2b23f396d30">llvm::BinaryStreamReader::readArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#aa883a589f91024d0a09d1b3c1821ec85">readBinaryIdsInternal</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/compactunwindtraits/#a9d9ddd9fe748227f30368cf9bf586ead">llvm::jitlink::CompactUnwindTraits&lt; CRTPImpl, PtrSize &gt;::readEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a6bb348b0b716cb9d060ecaef7a49dcc6">llvm::BinaryStreamReader::readInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a07e25e055f92f545f94821c4a3cbded8">llvm::BinaryStreamReader::readObject</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/compactunwindtraits/#a183445ddb7eddb88ddac8aa02c0db977">llvm::jitlink::CompactUnwindTraits&lt; CRTPImpl, PtrSize &gt;::readPCRangeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#ab04dd8530994d3914c2398c5105bd74b">llvm::orc::ExecutionSession::runJITDispatchHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#ac70eafd527c133cbc9773c9237179b17">llvm::orc::FDSimpleRemoteEPCTransport::sendMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a90a04d547b4e34b51c649f8fe259d461">llvm::jitlink::Block::setContent</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldchecker/memoryregioninfo/#a07c4b86a6f964b89024354dbc0168104">llvm::RuntimeDyldChecker::MemoryRegionInfo::setContent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae12d768edcecd309ab9fa48c23f9bc07">llvm::stable_hash_combine</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a59a5eeccde7b8eef0833cee7b914443b">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::startSynthesis</a>, <a href="/web-llvm/docs/api/classes/anonymous-armdisassembler-cpp-/armdisassembler/#aff1d6eda516ee7a8ce4dd5334cc39586">anonymous{ARMDisassembler.cpp}::ARMDisassembler::suggestBytesToSkip</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a73b370d004cc941240050b8048fefb7e">verifyNoteSection</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#a5da8fa1c8cd50b1cccfb561b40d88532">llvm::AppendingBinaryByteStream::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#abe3861e116c9da3ce15c4dd46a1bfaf7">llvm::msf::WritableMappedBlockStream::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablebinarybytestream/#ab01e4768ed6edae5181351ec2fc8be15">llvm::MutableBinaryByteStream::writeBytes</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a8dd06742877ada9717169e974f5f5de2">writeWithCommas</a>.</p>

</div>
</div>

### drop\_back {#aa713e2599e000adc01ced998c05502a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::drop_back (size_t N=1)</td>
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

<p>Drop the last <span class="doxyComputerOutput">N</span> elements of the array.</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ac255b2b7ff59963227ea39e1d176f63a">llvm::DIExpression::appendToStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#ae8f7b3435e5d6a7132e2e0aba6b347e7">llvm::Record::getDirectSuperClasses</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#afe13f78db01d9c3d12b2cf017bd9fbeb">llvm::sampleprof::SampleContext::isPrefixOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a8263d385de2b406acf8dbef9b0993cc9">llvm::orc::shared::runDeallocActions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>.</p>

</div>
</div>

### drop\_front {#a55089293ebaccd683a82d97170041376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::drop_front (size_t N=1)</td>
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

<p>Drop the first <span class="doxyComputerOutput">N</span> elements of the array.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aabfbce373feafd33ca9e104d8b164ece">allSameType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2d26c707fd7389b46ad98970d56faf24">clusterSortPtrAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/lineprinter-cpp/#abb45fec195a32d6c9255a3d626d41771">computeBlockRuns</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae06eb06e1d6ba6b5e8d319eef5d16280">computeCommonAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a472577b022e0997fbd409d82078df025">llvm::codeview::discoverTypeIndices</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aec9651c2f12f43fcdf5d88492040e24b">llvm::codeview::discoverTypeIndicesInSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a5ae41c589bd3c54f2a968e8336f3aa98">dropInitialDeref</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree/#a5d9f37d3681f5f14f5cf21fdf060703f">llvm::MachinePostDominatorTree::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38f536657a01f40d99f770fddee8e14a">llvm::codeview::forEachCodeViewRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord/#a20ab345d5cce9e08d1319607834b711f">llvm::CodeViewYAML::detail::UnknownSymbolRecord::fromCodeViewSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#aefb32da5629b40ca54fd1cae35c36d4a">llvm::fuzzerop::gepDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ae18b7d7be4354e3df59467ddf7d35c63">llvm::object::COFFObjectFile::getDebugPDBInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ac93b77f1f537436cbb281bbc34b3bd96">llvm::DIExpression::getSingleLocationExpressionElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#abbb20c80e0c1ab59446de978f898fc1e">handleMethodOverloadList</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#ab36e33dbf8516f7892bd335ff40545e9">handlePointer</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype/#acc7b052c15351bf328b64c17027eae9d">llvm::codeview::GloballyHashedType::hashType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7593114c182697759ffe3404df7df008">llvm::orc::lookupSymbolsAsyncHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/memcmpexpansion/#a9d922a46df77f0b5f112cd90f0b853c5">anonymous{ExpandMemCmp.cpp}::MemCmpExpansion::MemCmpExpansion</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a350ae3fe286b68175d7eee301904506c">resolveTypeIndexReferences</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/compatiblesets/#a4ef2eab86cf6fefd01ef4607cc834432">anonymous{SimplifyCFG.cpp}::CompatibleSets::shouldBelongToSameSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aedc4689962ab6d484f7b768c64dc8ad6">llvm::pdb::typesetItemList</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a8dd06742877ada9717169e974f5f5de2">writeWithCommas</a>.</p>

</div>
</div>

### drop\_until {#a82363b1979b08c15184249052cd81250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::drop_until (PredicateT Pred)</td>
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

<p>Return a copy of *this with the first N elements not satisfying the given predicate removed.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### drop\_while {#a27505108d9768764055066869464f7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::drop_while (PredicateT Pred)</td>
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

<p>Return a copy of *this with the first N elements satisfying the given predicate removed.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### empty {#ac835b8735b1b2faec0efdca236e37d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ArrayRef&lt; T &gt;::empty ()</td>
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

<p>empty - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the array is empty.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/irsymbolmapper/#a49258c0e5a9200b48bd7122eea077796">llvm::orc::IRSymbolMapper::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ac36177cea684b1e36fdbc92d692f69d0">addBasicBlockMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsection/#a6a2a290a120bc84d74855227e361b9ad">llvm::codeview::DebugChecksumsSubsection::addChecksum</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae122b7b9960cfd970b1d5c0d83f22039">addMask</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a952c8adfe8553406e169b98200072a69">llvm::LazyCallGraph::addSplitRefRecursiveFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a3c04d483e66e81efc4812a2d38b93a8d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::addStackNodesForMIB</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#adf31b047847bd798a010f641466ae838">llvm::pdb::DbiModuleDescriptorBuilder::addSymbolsInBulk</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a906252d050eac0a94e30d77a219a9c6f">llvm::pdb::TpiStreamBuilder::addTypeRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a521a0263cd32258d251908a3b8ab2f78">llvm::annotateValueSite</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ac255b2b7ff59963227ea39e1d176f63a">llvm::DIExpression::appendToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#acbf2b914f43ca98a8c1ea9bd11a92de4">llvm::DominatorTreeBase&lt; BlockT, false &gt;::applyUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelistimpl/#a6f9b9f798d2c70c515f146562de005b1">llvm::AttributeListImpl::AttributeListImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a0b51b9342dd5e45edcbc6c7237cb1ca7">anonymous{IRSymtab.cpp}::Builder::build</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a10e1b14fd1da88aad682e5d70ab224bb">buildExtractionBlockSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a987811f4399e448a9e1223ee373c1e00">buildFixItLine</a>, <a href="/web-llvm/docs/api/classes/llvm/vplanslp/#a58eaa1512d1998338ab6f9e8e710a46e">llvm::VPlanSlp::buildGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6dacb1328b30771530a48be17307efb0">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#af83167f66d93e94ff003e7a130b823f0">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a6a91ff524836d3fca6cabe37c8fb7dc5">canClobberPhysRegDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a61009b749b466b57d30ec5134bf613bb">CC_X86_64_I128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7abd0e34c17dcb201a4138dc65cc067">llvm::cloneAndAdaptNoAliasScopes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2489602598b96c9729c75a25ab8ff4cb">llvm::cloneAndAdaptNoAliasScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a7a5607fcb0a195620036bb0f1217c8a2">llvm::MachineInstr::cloneMergedMemRefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe9c37f2ba2d21ae9e526ecec89d431d">llvm::collectGlobalObjectNameStrings</a>, <a href="/web-llvm/docs/api/classes/llvm/combinationgenerator/#accd3e7cb7a9aae7e0e7f6b2d67ad23a7">llvm::CombinationGenerator&lt; choice_type, choices_storage_type, variable_smallsize &gt;::CombinationGenerator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4bbe053c13b73cf6ed1276f66b615fc7">combineOrders</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/lineprinter-cpp/#abb45fec195a32d6c9255a3d626d41771">computeBlockRuns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a013f10c0323064cf28c1aed647c0b478">computeExcessPressureDelta</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a701e935a2d02fd488218cf26b8eedb67">anonymous{ELFObjectWriter.cpp}::ELFWriter::computeSymbolTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a557be4c1daf6eb2611b214f927dccee2">llvm::ConstantFoldExtractValueInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a491cbe61681e7c63ac7d01ce209a4682">llvm::ConstantFoldGetElementPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7fa9b738742521d0a684cec016ef47e">llvm::ConstantFoldInsertValueInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa39d4ce88555d804615c0cd225d9fcb6">llvm::convertUTF32ToUTF8String</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#a75f0ba2a248f2f7f77f477bfb8d6dab2">llvm::coverage::BinaryCoverageReader::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#a7cbecc17bbb64783431627bcf1f433c7">createMIBNode</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3e1a0b27abb4d57e2293c46802eee89d">llvm::OpenMPIRBuilder::createSingle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#a992787f0142954b821c221ff5a2c921f">llvm::symbolize::anonymous{Symbolize.cpp}::darwinDsymMatchesBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#abe70653ea636e6b63159edf52d38afc5">llvm::objcopy::deepWriteArchive</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abed730d9d5b8f4c70f4fbe1094a0157f">llvm::doesNotNeedToSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aa438ee4f7cc143674ffb81a41c01fcb2">llvm::object::ELFFile&lt; ELFT &gt;::dynamicEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a2c00c11ef810b9f4ca1781a341de60d3">llvm::CodeViewContext::encodeInlineLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a99ce62ce3455a7a99df0daaee4fd516e">llvm::object::MachOObjectFile::exports</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph/#ab89419b289ce60676c9dcca14e365b7b">llvm::sandboxir::DependencyGraph::extend</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a7184c737372d1fa8d3783e5000463f2b">llvm::ThreadSafeTrieRawHashMapBase::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae29b7bb67763c63132e57471f88ac80f">llvm::FindInsertedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree/#a5d9f37d3681f5f14f5cf21fdf060703f">llvm::MachinePostDominatorTree::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38f536657a01f40d99f770fddee8e14a">llvm::codeview::forEachCodeViewRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#a26e5b6731c22761e5c4e7abe1dc13a21">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/darwinx86asmbackend/#a0423592792c76af41a0db8233e30bf45">anonymous{X86AsmBackend.cpp}::DarwinX86AsmBackend::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackenddarwin/#a0734a023f800982945eec5cff4e9fb22">llvm::ARMAsmBackendDarwin::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ad3a7b88fce11b12853e7b60a06a033ec">llvm::InstrProfCorrelator::get</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af99419a971a2b329732cb2a89e6a004b">llvm::RecordRecTy::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ae76b640db72efe7da1107ed796890d99">getBuildDwordsVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a9205d579e79767f52c5af57c94d2be74">llvm::omp::getCompoundConstruct</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a814ccfa400b06db7a01885ddcc21196a">llvm::orc::JITDylib::getDFSLinkOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#ae8f7b3435e5d6a7132e2e0aba6b347e7">llvm::Record::getDirectSuperClasses</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1558554539a5b133b8e361c0517e9fb1">llvm::RegAllocBase::getErrorAssignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ae6bcc7c94e3742c313341e5883ac618d">getExpressionFrameOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a2ffebbabe0c187d8c92743daf4e83edb">llvm::MCSchedModel::getForwardingDelayCycles</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a8528b1c4543692486b82ac9012c1617b">llvm::HexagonRegisterInfo::getHexagonSubRegIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a90bc029b97b6d91b7a77c86bb88630c2">getIndexedTypeInternal</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86disassembler-cpp-/x86genericdisassembler/#a5872d463242e5872d4df00b5862e403f">anonymous{X86Disassembler.cpp}::X86GenericDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#abc325a2174e8b3649c8867e57f66f3b5">getMaxCalleeSavedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a30a7ce961d5d90ff2fb6c9cee4576e5a">llvm::DILocation::getMergedLocations</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#abf54ff8f66bc899700aaf8887f85313c">llvm::SystemZTTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#adb68429296d9cd8a13b4aa3f10f2e780">llvm::object::MachOObjectFile::getSegmentContents</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a266c328585c72cd84dc48ef488acef49">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getShallowScore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7f5e446b08fdb38a854b35dbab34bc0c">getShufflevectorNumGroups</a>, <a href="/web-llvm/docs/api/classes/llvm/dfapacketizer/#a0afd27b8b7741b32607d3c24dd91eff5">llvm::DFAPacketizer::getUsedResources</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#abbb20c80e0c1ab59446de978f898fc1e">handleMethodOverloadList</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#aa9dbc0a952dfbed82b71fd482c4fcdd7">llvm::ThreadSafeTrieRawHashMapBase::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a150e7cedb8221a184efe28d747fd3382">llvm::LanaiInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#ae3b43649c18ab9e63c1be61b93dd7031">insertLifetimeMarkersSurroundingCall</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder/#a7c1575ca2aa02aa24752ae549aa177f8">llvm::codeview::GlobalTypeTableBuilder::insertRecordAs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6b7912ea5edc4563fe03afc57fa9b0c6">insertUseHolderAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval/#a65aee3487cb3db7cca90a7d3efd0aaf1">llvm::sandboxir::Interval&lt; T &gt;::Interval</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ae420d94473ac8cb96686184a551f6097">llvm::slpvectorizer::BoUpSLP::isIdentityOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a3e874f5073fd59211348a2ea23e9d0ce">llvm::GCNTTIImpl::isInlineAsmSourceOfDivergence</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#aeb78ce0ad4d22082b130cd97900caa5d">llvm::ConstantRangeList::isOrderedRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#afa640d51b943ce0396e7131bf2352f8a">isReverseOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#a91d6d8d5af0b8ba44a006860ef830113">llvm::coverage::CoverageMapping::load</a>, <a href="/web-llvm/docs/api/classes/llvm/loadandstorepromoter/#a5a4040326a09f994f2b5481cf5c8da82">llvm::LoadAndStorePromoter::LoadAndStorePromoter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7593114c182697759ffe3404df7df008">llvm::orc::lookupSymbolsAsyncHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9157e4aca11eca217c5c6d2c6a2eadbf">llvm::X86TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a51d9ea5d0487385704b6aa356485b70c">llvm::AMDGPUCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#a49a30e74a8632576007b3678649c9fb9">llvm::ARMCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfcalllowering/#a233177d33a84d04ee5ff91e1c33d16e0">llvm::BPFCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#abfdadd18c92c595797ca5409d708f2ef">llvm::M68kCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a821ed33f62736f960fa90c585205677d">llvm::MipsCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/ppccalllowering/#a0895983a48b4fe2de9c52579431f8744">llvm::PPCCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a2a90be51e47dadfbb04df4f64465ea04">llvm::RISCVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ace03d9ed2825d1401093a441f164ecdf">llvm::X86CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a96929c573ae5a98213a4d8c25554e53f">lowerV8I16GeneralSingleInputShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a2bff55a07291d47843ff3e4a1548c154">llvm::fuzzerop::matchFirstLengthWAnyType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#ad3d7a249e54c1fd78688913ffcc2e899">llvm::fuzzerop::matchFirstType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#af8db50c76878b9d7747a77ecdeadbb48">llvm::Intrinsic::matchIntrinsicVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a764af34b63a5c94bdfc643668bb4c885">llvm::fuzzerop::matchScalarOfFirstType</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/memcmpexpansion/#a9d922a46df77f0b5f112cd90f0b853c5">anonymous{ExpandMemCmp.cpp}::MemCmpExpansion::MemCmpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae69dd69c07ac063e85030679ceba2f93">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#aebda89a6230d3b4ac098b18b57c16f4b">llvm::raw_ostream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a45007554e260296266b8ae927dde223f">postUnswitch</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a21a6098da614f4229dee3de0432aa83a">llvm::DebugCounter::printChunks</a>, <a href="/web-llvm/docs/api/classes/anonymous-detailedrecordsbackend-cpp-/detailedrecordsemitter/#aff15dd7156e8ad1d38a077572c0fe4f0">anonymous{DetailedRecordsBackend.cpp}::DetailedRecordsEmitter::printSuperclasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae529107c3b550f7e2fe6128a26c8f1da">llvm::promoteCallWithVTableCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a4cac84457299517e69ff9764fed2db">llvm::PromoteMemToReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48a6deb3e714d54e75caadcf84b0ca76">llvm::propagateMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding/#a899ed81dbda72496c2d105042da6acef">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding/#af455dc61361369b5ef61f16db37c3c66">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a97b7a3d43f4f6eb3ab16554f56bd0cc4">llvm::LazyCallGraph::removeDeadFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a350ae3fe286b68175d7eee301904506c">resolveTypeIndexReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a03aa2120f2d9d154313c31faec3d97d2">llvm::ARMFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a8b418b49786b4eb1c06b0e407e346c01">llvm::AVRFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a7c89ea904b5a33a2c24357c301e4ea21">llvm::CSKYFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ad8f2dd732e11ab2eed0563516a0128e8">llvm::MSP430FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a15d74c0d6159ac707f99c91219d0c6a5">llvm::SystemZELFFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a3d043cad28262fefa366ecc64c9591f1">llvm::SystemZXPLINKFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#adca65a5406a289a41bd58993e28bb3aa">llvm::Thumb1FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a94ed22ca5dc3213bfb96e1ddbc41952e">llvm::X86FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfopropagate-cpp-/regusageinfopropagation/#a69819f2acbe4f8a2cd38c871d3c9b96f">anonymous{RegUsageInfoPropagate.cpp}::RegUsageInfoPropagation::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a8263d385de2b406acf8dbef9b0993cc9">llvm::orc::shared::runDeallocActions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5981137a17cad3d9b2276ad63e15ee40">llvm::MachineInstr::setMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a66ebc3ec1c8816b16a5f239a8631c780">llvm::SelectionDAG::setNodeMemRefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a9ad2ee389fa99a4c02f610183530735c">llvm::VFABI::setVectorVariantNames</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#af5c90aadc6c53b0224c421a998d85587">llvm::RISCVInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a48560701bbaa0465f8ef8d92874caaf0">llvm::SIInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a77dc4905d180a52615d00a760b111f9a">llvm::ARMFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#af676cadcef1e3d4d159420f075a083da">llvm::AVRFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#af57354b85b1bb51bd0d56651205786a9">llvm::CSKYFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a6d7492a7a948b4a2d3bb8fd69395503d">llvm::LoongArchFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a4d6b288488bfee7d307b78a36e230986">llvm::MSP430FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a9db07f97c8d52e506e689b789b231f0c">llvm::SystemZXPLINKFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#af07ce77a4beea41a98862690cee5ec2d">llvm::Thumb1FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#acc16e0a256c156ca27db8e17d37cceab">llvm::XCoreFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#a60bfd268a9634bf18e34825e171528fe">llvm::CodeViewYAML::toCodeViewSubsectionList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a2969e8555a2230d375d57d0b49f80229">toSpvOverloadedIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a96196ee6ac47c0ff8c2398bbc4cb775d">llvm::mca::RegisterFile::tryEliminateMoveOrSwap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aedc4689962ab6d484f7b768c64dc8ad6">llvm::pdb::typesetItemList</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aee075a4b7e853e004ad694f7ef959f28">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ae6b63bcaa1f6638b608f911cd04341e2">llvm::MemorySSAUpdater::wireOldPredecessorsToNewImmediatePredecessor</a>, <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/jsonwriter/#a1b1532a2254d760451e96bf7b299943b">anonymous{VirtualFileSystem.cpp}::JSONWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#a5da8fa1c8cd50b1cccfb561b40d88532">llvm::AppendingBinaryByteStream::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablebinarybytestream/#ab01e4768ed6edae5181351ec2fc8be15">llvm::MutableBinaryByteStream::writeBytes</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a8dd06742877ada9717169e974f5f5de2">writeWithCommas</a>.</p>

</div>
</div>

### end {#a7ca5197533a9c1fb8a2bd30587fcec6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ArrayRef&lt; T &gt;::end ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#a0c3e8ed752bc7ef92ccb9edbd4bb014a">llvm::lto::LTO::add</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#afbe3c388c22fe55467e7f2847d7ec2fd">llvm::SubtargetFeatures::addFeaturesVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae122b7b9960cfd970b1d5c0d83f22039">addMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a3c04d483e66e81efc4812a2d38b93a8d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::addStackNodesForMIB</a>, <a href="/web-llvm/docs/api/classes/llvm/debuglocentry/#a5df10bc170330b17e46917b60c38cf04">llvm::DebugLocEntry::addValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abd5114d6b451e9ca85a36fc3f19f76c4">allSameBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/object/dynamicrelocref/#a667314594711210c817f136e0966c0e6">llvm::object::DynamicRelocRef::arm64x_reloc_end</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#ac7dcecb4ce0bf73a49d45fd5da8ec84a">llvm::DIExpressionCursor::assignNewExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#a66b1304ca72d9916db93a0ab9a55697c">llvm::ELFAttrs::attrTypeAsString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#a343d704d236717ce9399b288a622a222">llvm::ELFAttrs::attrTypeFromString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a987811f4399e448a9e1223ee373c1e00">buildFixItLine</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a7e36a63781989accf846f2e78f510d33">llvm::Interpreter::callFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe9c37f2ba2d21ae9e526ecec89d431d">llvm::collectGlobalObjectNameStrings</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a0fccac895976ea41f8038b07e18389">llvm::ComputeLinearIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4288169d91ab0f0f01405115fd2931a7">llvm::concatenateVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelistattributeimpl/#aba61e4f1fe75fe73a617ed967ba11478">llvm::ConstantRangeListAttributeImpl::ConstantRangeListAttributeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#a4386ffb2e777bd2b2f2a30e89decfebc">convertSSEToAVX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa39d4ce88555d804615c0cd225d9fcb6">llvm::convertUTF32ToUTF8String</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ace7e2f01b65afba76343f22d042a12df">CreateGCRelocates</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addf42fea14164ec994d4d517eaa56688">llvm::DeleteDeadBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9c5f771f232bbd4cf6ec230bd78f9174">llvm::Instruction::dropUnknownNonDebugMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a00c248324c8be329a7f619041c4d19ea">llvm::DIExpression::elements_end</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#a6db5460aea8388ba1f9bec6c47f6c741">llvm::MCDwarfFrameEmitter::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a42a0cfa56ebe2de750170da9db67f927">llvm::BitstreamWriter::emitBlob</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae29b7bb67763c63132e57471f88ac80f">llvm::FindInsertedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a181dad1cdd60a83a181108d90acd4738">llvm::CondOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a8068bfe8ffd6450e61e72665e6887abc">llvm::DagInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#afe6e63cc76f08a5400707ae311ca1cfd">llvm::gsym::GsymReader::getAddressOffsetIndex</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-targetparser-cpp-/#a1cb029bce98099dc3aa7b90d708e77d0">anonymous{TargetParser.cpp}::getArchEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a9205d579e79767f52c5af57c94d2be74">llvm::omp::getCompoundConstruct</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a331caeb70809f50e71528de06fba7b66">llvm::StructLayout::getElementContainingOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ae6bcc7c94e3742c313341e5883ac618d">getExpressionFrameOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ac81c73fb91e0b2c0c30ae63c671d23">llvm::getFMA3Group</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac10dff634cacc4be44046af5ee45f92a">getGEPCosts</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a7d9301f2db70078a258c683a1046f569">llvm::ARMBaseRegisterInfo::getLargestLegalSuperClass</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a842441ec6290263363da4edef875b5c5">llvm::X86RegisterInfo::getLargestLegalSuperClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a433702fa6f12e3710e21ed0fde2a69b0">llvm::omp::getLeafOrCompositeConstructs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp/#a8aac3d1bd9fe9005fb56a087e0a824e2">getLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vecutils/#a47d4037afa835a57270728d8d3ffb051">llvm::sandboxir::VecUtils::getLowest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a210188f72593e018067353026bdd4fe3">getNewOpcFromTable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#ab2dce2d77f65b46dcc8187d9eb10a8bf">anonymous{DWARFEmitter.cpp}::getNonZeroDataSizesFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ade3b3b604b9b365a57f791ab198a691a">getNoopInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a93999c78a867aff95a79a69f287e68c5">getRegLanes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debuginfosupport-cpp-/#af708da9529b70292b2712cd7ed80d14e">anonymous{DebugInfoSupport.cpp}::getSectionData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac947597e4f7b21eda127d16de828a5eb">llvm::getShuffleMaskWithWidestElts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3373a145daacecd10f10f8d9622a2114">llvm::hash_value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1737ab2b5a4c39b8eb3fcbd2e47abb65">llvm::pdb::hashStringV1</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a30d8d29c9510e2f8b7f6244979fc9376">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphscc/#a87e1b8515d22eb833375761e19a2d0fe">llvm::CallGraphSCC::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a4d055efabadfeaf759463d4edf2c2207">llvm::RegPressureTracker::initLiveThru</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslices/#a9d50c642270c265bdb2af02bf6d4eed0">anonymous{SROA.cpp}::AllocaSlices::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#ad444e7dc0b30ff2af7e7e3362287f291">llvm::AppendingBinaryByteStream::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a61ef13844d0a136295d9a3acfcf51363">llvm::omp::isCompositeConstruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ad5d72247c1a3137bc2c2c7aaf0000b03">isFixedVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a4e12c0cb71a44b8822c5a35cbbe5c731">llvm::LiveRange::isLiveAtIndexes</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ac4d13f5ea905de676278414d7f7c2601">isSubset</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a06632f7f66681098316a7cbf42927d09">llvm::RISCVISAInfo::isSupportedExtensionFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#a91d6d8d5af0b8ba44a006860ef830113">llvm::coverage::CoverageMapping::load</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#ac28513e2e067144d291d2d8f0301b61a">Lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfoldtables-cpp/#ac9968c8a44bfeea04a9923a6e997d62a">lookupFoldTableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ae071c2a56ff28186d5476e562811b2f7">lookupLLVMIntrinsicByName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a22c6a7a1925a0177519e33d49ba91cea">llvm::RISCVTargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a602b901d40f2b6bc5bf489a131309eef">lowerShuffleViaVRegSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a96929c573ae5a98213a4d8c25554e53f">lowerV8I16GeneralSingleInputShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8a1ae2e1de53a840bee516d1f5bb173">llvm::makePostTransformationMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a97074acd3a969b0eb7a6a730c5a1c8f3">llvm::codeview::CodeViewRecordIO::mapByteVectorTail</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a627f84abfceb75ffd72119423d0147a4">mergeVectorRegsToResultRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/#a24d580253e70f01bd7316f249f17482f">llvm::ImmutableGraph&lt; MachineInstr *, int &gt;::nodes_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a93f122dff654f8336680531a3898375c">llvm::CallBase::populateBundleOperandInfos</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a85549679782ae212e691a7edfe985550">ProfileCondOpInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#ad69191edb241ddc1918363da6d6b14d1">ProfileDagInit</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-e92e567fbcfc8afd44242d623ff29b96/#a8609213d38c69d46947c06400e50e094">llvm::detail::BCRecordCoding&lt; BCArray&lt; ElementTy &gt; &gt;::read</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af0ce60c4a958016f62ce78f1eda423af">removeUnusedBlocksFromParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a64261c5840053afd36cfbb72666ace95">anonymous{ValueMapper.cpp}::Mapper::scheduleMapAppendingVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a9bbfc66d078e240930409cc562753881">llvm::SDDbgValue::SDDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6f526a87cef7533f13e0a80937776c20">llvm::MachineFunction::setCallSiteLandingPad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a6ac158cfb39dae5f6514d2508e735115">llvm::X86MachineFunctionInfo::setPreallocatedArgOffsets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad272ce4631595e235e560baf59dc1ffd">llvm::setProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#ab85ea74b3cb2aeabcf765b1892ff9d91">llvm::gsym::GsymCreator::setUUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#afb0d2b520c6cf9984ec6a40e7af31dca">stackFrameIncludesInlinedCallStack</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a19a6a168a50b639280b51eada31cae76">llvm::DbgValueHistoryMap::trimLocationRanges</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#ae8bfab8841d5d8482833437e8b4309b9">shuffles::vdealvdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/misexpect/#a8677c5d2618fcf52eda43f5530decb6b">llvm::misexpect::verifyMisExpect</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a2337e506453c5ed1ec20ebabbafbc014">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a05231a6703f721a7938ce95de41743f1">shuffles::vshuffvdd</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ae6b63bcaa1f6638b608f911cd04341e2">llvm::MemorySSAUpdater::wireOldPredecessorsToNewImmediatePredecessor</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a2b96fb8bf782a1b498a82682ab8e74c9">writeToResolutionFile</a>.</p>

</div>
</div>

### equals {#a21ff1fd12b25b79fcd4449c35dc814b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ArrayRef&lt; T &gt;::equals (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> RHS)</td>
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

<p>equals - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for element-wise equality.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a966fef46fe7ea0cbede6e40248eae243">llvm::operator==</a>.</p>

</div>
</div>

### front {#a721fc555cb3d8dc2a1a680dcc2ce69b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; llvm::ArrayRef&lt; T &gt;::front ()</td>
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

<p>front - Get the first element.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aabfbce373feafd33ca9e104d8b164ece">allSameType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a646829664451eb913bfa2f92920478ea">calcPredicateUsingInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aa9f28186f9e231cea3f08c0b623129f4">calculateShufflevectorMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ae9efb27478c86bece81f1bf5bca2d348">canSinkInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2d26c707fd7389b46ad98970d56faf24">clusterSortPtrAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/lineprinter-cpp/#abb45fec195a32d6c9255a3d626d41771">computeBlockRuns</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae06eb06e1d6ba6b5e8d319eef5d16280">computeCommonAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a99b699ca919e40ac78708ea425fbfa98">convertToGuardPredicates</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#abe70653ea636e6b63159edf52d38afc5">llvm::objcopy::deepWriteArchive</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a2c00c11ef810b9f4ca1781a341de60d3">llvm::CodeViewContext::encodeInlineLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree/#a5d9f37d3681f5f14f5cf21fdf060703f">llvm::MachinePostDominatorTree::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#aaba8002e40481888d8e4933ce4487081">generateNewInstTree</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ad3a7b88fce11b12853e7b60a06a033ec">llvm::InstrProfCorrelator::get</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a814ccfa400b06db7a01885ddcc21196a">llvm::orc::JITDylib::getDFSLinkOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1558554539a5b133b8e361c0517e9fb1">llvm::RegAllocBase::getErrorAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vecutils/#a089cccbe66baa77d85c8a291030c7796">llvm::sandboxir::VecUtils::getLowest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7f5e446b08fdb38a854b35dbab34bc0c">getShufflevectorNumGroups</a>, <a href="/web-llvm/docs/api/classes/llvm/dfapacketizer/#a0afd27b8b7741b32607d3c24dd91eff5">llvm::DFAPacketizer::getUsedResources</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a16658fce14f4b2888f76f0972d239139">isFreeConcat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aa28651c1e85585ae702f652a8df06019">isSwitchDense</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#a91d6d8d5af0b8ba44a006860ef830113">llvm::coverage::CoverageMapping::load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7593114c182697759ffe3404df7df008">llvm::orc::lookupSymbolsAsyncHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#af8db50c76878b9d7747a77ecdeadbb48">llvm::Intrinsic::matchIntrinsicVarArg</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a0efb7aefc1fd76a565c2ced7d2ff14cb">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::materializeInstructionChecks</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/memcmpexpansion/#a9d922a46df77f0b5f112cd90f0b853c5">anonymous{ExpandMemCmp.cpp}::MemCmpExpansion::MemCmpExpansion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a951bbdda542205db9de80f6bf44f571c">memOpsHaveSameBasePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a951bbdda542205db9de80f6bf44f571c">memOpsHaveSameBasePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding/#a899ed81dbda72496c2d105042da6acef">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-7416a4930392106d56f3af1734eb69d7/#abcef45d7793b7eae2f2789356d2f34bd">llvm::detail::BCRecordCoding&lt; ElementTy &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#ab3635230226f6d60dad04b8e83d848fd">llvm::slpvectorizer::BoUpSLP::VLOperands::reorder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9f3bcb74818214fe1e8df656c52ab206">shortBundleName</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/compatiblesets/#a4ef2eab86cf6fefd01ef4607cc834432">anonymous{SimplifyCFG.cpp}::CompatibleSets::shouldBelongToSameSet</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#af5c90aadc6c53b0224c421a998d85587">llvm::RISCVInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a48560701bbaa0465f8ef8d92874caaf0">llvm::SIInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4373d3025961c2c2eeca56b02d7d009d">llvm::widenShuffleMaskElts</a> and <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/jsonwriter/#a1b1532a2254d760451e96bf7b299943b">anonymous{VirtualFileSystem.cpp}::JSONWriter::write</a>.</p>

</div>
</div>

### rbegin {#aebe6da1ab4a07020669f3d6148c0b559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::ArrayRef&lt; T &gt;::rbegin ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ade3b3b604b9b365a57f791ab198a691a">getNoopInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a3030fa8e5d4a78aef7c5a7fa00294ac6">getPropIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1f98694f104d052d71ed74ade38d69f0">llvm::ScheduleDAGMI::initQueues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a948aaf9d2ae438b3e2369223f55ec841">rematerializeChain</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc942a637e5d48a94d4033498b7479dd">llvm::X86FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### rend {#a709f5d7f042648ec20197939d9a6805f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::ArrayRef&lt; T &gt;::rend ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ade3b3b604b9b365a57f791ab198a691a">getNoopInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a3030fa8e5d4a78aef7c5a7fa00294ac6">getPropIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1f98694f104d052d71ed74ade38d69f0">llvm::ScheduleDAGMI::initQueues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a948aaf9d2ae438b3e2369223f55ec841">rematerializeChain</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc942a637e5d48a94d4033498b7479dd">llvm::X86FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### size {#a85ffb6531d4cda988ea81f18d4e56fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ArrayRef&lt; T &gt;::size ()</td>
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

<p>size - Get the array size.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator/#ac1f4ba74dc5112ee745cc214c2ae31b9">llvm::dwarf_linker::parallel::DIEGenerator::addBlockAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugchecksumssubsection/#a6a2a290a120bc84d74855227e361b9ad">llvm::codeview::DebugChecksumsSubsection::addChecksum</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator/#a2a2762a53f796809b0cc3f70b57024de">llvm::dwarf_linker::parallel::DIEGenerator::addLocationAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9c6d364a5079f4f7a166cbaa1ba24ebb">llvm::DwarfCompileUnit::addLocationAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae122b7b9960cfd970b1d5c0d83f22039">addMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a00870d00a6899aedeef7ebdd65fc1724">addOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a938be134329f4243053d957980a79724">llvm::gsym::GsymReader::addressForIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16instrinfo-cpp/#a8307fba45b5b2a7e89011a2a789a9a31">addSaveRestoreRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#af4a2024c4c2cee5d75b2146a5bc544d4">llvm::msf::MSFBuilder::addStream</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptorbuilder/#adf31b047847bd798a010f641466ae838">llvm::pdb::DbiModuleDescriptorBuilder::addSymbolsInBulk</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a906252d050eac0a94e30d77a219a9c6f">llvm::pdb::TpiStreamBuilder::addTypeRecords</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a661ee64d4ed40dfc71b7a2bd4d2fd4a2">llvm::InstrProfRecord::addValueData</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a1fb252b26b548e2ed904e02782013abd">llvm::DbgVariableIntrinsic::addVariableLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ab6d5d78fdfb9f1254c0471d2a3be0e65">llvm::DbgVariableRecord::addVariableLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a2d13a28563f7bcce62ca94550c02f405">llvm::CCState::AllocateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ac91c138875449056b2b6201eadb4f63f">llvm::CCState::AllocateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a80596370c938add79f4045e0dfe08a4d">llvm::CCState::AllocateRegBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a8688cc0d4d5620a54a1d45bd3087de1f">allocateSGPR32InputImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abcfc092d297e085e5b5390b5b1656236">allocateVGPR32Input</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8423e53bcc9782e23a4e48e8ef88d150">llvm::analyzeArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aebcf13b2162f23607396fffbf2b6ef7e">analyzeHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a0752ad646759ea4a034a218da571ab8b">llvm::object::ELFFile&lt; ELFT &gt;::android_relas</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a363d442ff7f9a13eafaee275aad9f54c">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdates</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref/#a14c551d5c5951cce16714126f6cadcee">llvm::yaml::BinaryRef::binary_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#ac65c36245c627cb9fb40879101d952a8">buildFatArchList</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6dacb1328b30771530a48be17307efb0">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#af83167f66d93e94ff003e7a130b823f0">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildLookupTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfe6e5ec3e8d8ad4632758a0af06b8f9">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a8efa56ca3bfdd8c715939f9e0b24ccda">buildNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#ab9785654b9d9d59e9f47ceac3364de40">llvm::codelayout::calcExtTspScore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#a70c3cab5f18ff0a00d4ad43ec3287021">llvm::codelayout::calcExtTspScore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a0bfeadac5ccd4e56b4c5df9dc6bb8817">calcPredicateUsingBooleans</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a646829664451eb913bfa2f92920478ea">calcPredicateUsingInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a7e36a63781989accf846f2e78f510d33">llvm::Interpreter::callFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#ab3e5050d43a1deb05a2878c74eb99abd">llvm::orc::SelfExecutorProcessControl::callWrapperAsync</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#ade8a5e3b6a082e4cb8bb4202ae7f652a">canonicalizeDwarfOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityanalysis/#a5c81ada05bd736617bf16b24329360b8">llvm::sandboxir::LegalityAnalysis::canVectorize</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa32035802671dce51123a77b96594506">checkARM64Instructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#affd5619a70ecc254d62f604150468f1d">CheckForLiveRegDefMasked</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a99fbec7515ca1c665315334c1a67d3a5">checkOperandCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9826d594303bc76fe0df7ab9face2d1a">llvm::cleanUpTempFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7abd0e34c17dcb201a4138dc65cc067">llvm::cloneAndAdaptNoAliasScopes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2489602598b96c9729c75a25ab8ff4cb">llvm::cloneAndAdaptNoAliasScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a00f85301e155c37fcab125f50a67cfb4">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneBlockAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a7a5607fcb0a195620036bb0f1217c8a2">llvm::MachineInstr::cloneMergedMemRefs</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a54fbbf29fc459bb243a1a43fb2ab9c1a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::clusterNeighboringMemOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2d26c707fd7389b46ad98970d56faf24">clusterSortPtrAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#aa359aa2850f74fbc9dbdb4650c13f4cf">llvm::FunctionComparator::cmpOperations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab349dce775a8c8dcd72c24059e8357a2">coerceArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe9c37f2ba2d21ae9e526ecec89d431d">llvm::collectGlobalObjectNameStrings</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#af8efd31679b2381827db95f3cad5ba44">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::combineMasks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4bbe053c13b73cf6ed1276f66b615fc7">combineOrders</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a7847dc95e3ec6e1cdaa66ac48a0f7985">combineShuffleOfSplatVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#adff1fcbcf8e82995a72f1efd2d62ec11">llvm::TargetLowering::DAGCombinerInfo::CombineTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aab7406f11829e7505acce1a7d4a7803d">combineX86ShuffleChainWithExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a2d2b8c755a8e7b54f4680d27cd40d244">llvm::IRSimilarity::IRSimilarityCandidate::compareStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a369b6ca6828ed902608da470a95bfd93">llvm::compareTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#a73e7e6f4b8c90a37295178a56661de2d">llvm::codelayout::computeCacheDirectedLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a013f10c0323064cf28c1aed647c0b478">computeExcessPressureDelta</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codelayout/#ab265fb35ca9607f01d99dae7a386ef77">llvm::codelayout::computeExtTspLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a5e95e012bf0ddb58e7aa1025f7d093c8">computeIndirectRegIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0947a70171b7e63f155a2eae2bfd706">llvm::ComputeMappedEditDistance</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a822aec28298cd2dc8f346d4753a4154b">computeMaxPressureDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ae1d3c5a1f43dcec43774a3767b41e447">llvm::mca::computeProcResourceMasks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4288169d91ab0f0f01405115fd2931a7">llvm::concatenateVectors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a491cbe61681e7c63ac7d01ce209a4682">llvm::ConstantFoldGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constraintsystem/#aeb648e3658a39e3b9db30676cb6cb728">llvm::ConstraintSystem::ConstraintSystem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a99b699ca919e40ac78708ea425fbfa98">convertToGuardPredicates</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#af5c4dc333adfdd30afcce056b9b97484">llvm::detail::IEEEFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa39d4ce88555d804615c0cd225d9fcb6">llvm::convertUTF32ToUTF8String</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#acd4e3782462bd215bc07bd1f9b2b01b5">llvm::AArch64InstrInfo::copyGPRRegTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a6aa0afd1200f5f282ca02a9ebcf87ca7">llvm::GlobalObject::copyMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a519410003771768aef013bd57efa6cf4">llvm::SIInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af01e300c1d03a13eb9edabea4ed9aef5">llvm::AArch64InstrInfo::copyPhysRegTuple</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#aa4f1a33698e2466ce414169501f01cf4">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::copyToShadow</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a37064f808b1971939c4076441e36f79d">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::copyToShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ad827d6e6b726bda4090423719c8a6fff">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrconstantexpr/#afa68387dc2d89f1da72ba37c23ab49e6">llvm::GetElementPtrConstantExpr::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a7e5d474f9fda4b2b2e5de3dcfefcc472">llvm::GetElementPtrInst::Create</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodeconstant/#aa4ff2e568cb9038b2572ae630057f9f2">anonymous{BitcodeReader.cpp}::BitcodeConstant::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#af9e525905347a63733a094e254637234">llvm::sandboxir::GetElementPtrInst::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a3ed7e979bee3c9d43ed5128461ca9070">createAndCheckVectorTypesForPromotion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#ab69bfee9fa1bf844067b1fd7dcbe7c0f">llvm::jitlink::ppc64::createAnonymousPointerJumpStub</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#adff293fef41b4eb80fca7c47b2e2c99a">llvm::MDBuilder::createBranchWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ace7e2f01b65afba76343f22d042a12df">CreateGCRelocates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#ae9deb009b49abafc4debcd727b89cdb8">createIndexMap</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ac22ab49b0b7cf93ae570c6a5b8049b34">llvm::jitlink::LinkGraph::createMutableContentBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#af36172c1f538b7305b44760997d5a3c2">llvm::OpenMPIRBuilder::createSections</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3e1a0b27abb4d57e2293c46802eee89d">llvm::OpenMPIRBuilder::createSingle</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#abf39f615f0eef682e349ee230cec4fbf">llvm::MDBuilder::createTBAAStructNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#aecae3ba429df973662fc145e3347149b">llvm::MDBuilder::createTBAATypeNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a8d179b8dd229c1d46eee4c257e717e25">createThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a097c2cf1ff74009e3254960e61688c17">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::createTuple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#afb7df659747f14484e642788c2fe6788">createTuple</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af01161a775d8cf6057a315b19a8be842">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::createZMulTuple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#a992787f0142954b821c221ff5a2c921f">llvm::symbolize::anonymous{Symbolize.cpp}::darwinDsymMatchesBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ab29da57c63bb1608298c863ea81696cc">DecodeIITType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb680fe35fd4d397b7d0674c45861008">llvm::DecodePSHUFBMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a8199e9ace5520235a9e3717a7cb5992e">DecodeRegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5fb0db87ada1b48888e070c009007845">llvm::DecodeVPERMIL2PMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ed1906d1fc3026d1bf29313dfcfa68">llvm::DecodeVPERMILPMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33cfdeaaf372a893845f4283d8b38721">llvm::DecodeVPERMV3Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b736243d275dddeb7c434f0b03841bf">llvm::DecodeVPERMVMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2ea0deda81eb9adf593b817b901fc1e">llvm::DecodeVPPERMMask</a>, <a href="/web-llvm/docs/api/classes/llvm/object/decompressor/#aeff1a966d66b995e39f35c393a437a10">llvm::object::Decompressor::decompress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addf42fea14164ec994d4d517eaa56688">llvm::DeleteDeadBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#af7c58c4a38a2148e0a6eec44b8749bbb">llvm::GCNIterativeScheduler::detachSchedule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a00c8a16f00462fc9765f5922f3ba761c">llvm::object::doesXCOFFTracebackTableBegin</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a180f88c410e11a7df7b17e9a782197e2">dumpLocationExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb6fca77863850136760be488d6ea345">llvm::dumpRegSetPressure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#a81e88ae7d3e872ba0cdc367330b2974d">llvm::objcopy::coff::dumpSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a434621cd1f8f1c0240a47b65ba19ea9b">eat12Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a7d8ee6944c8121c49c2a8da4b1695fe7">eat16Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aaff8a7b712c8ea0bb1275e621119e498">eatBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a42a0cfa56ebe2de750170da9db67f927">llvm::BitstreamWriter::emitBlob</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#a157d897bbd822c5ca7a4dd59536d0945">anonymous{DWARFEmitter.cpp}::emitDebugNamesNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ad48c785749c7160070b39be42c67d2b7">llvm::OpenMPIRBuilder::emitTargetKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a0cf3c7ba2564fa10526e70ecd607db74">expandSGPRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#a4d0d05a3c39242b69eec429ba4945c64">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#a702eff07aa75ca8d8cfaba044f7b3f29">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae29b7bb67763c63132e57471f88ac80f">llvm::FindInsertedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ae4bde92835730133920c426289e5d59b">findLiveReferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wholeprogramdevirt/#a8ab22ea42eaf359bb9eb8382c0afc616">llvm::wholeprogramdevirt::findLowestOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mctargetdesc-cpp-/aarch64mcinstranalysis/#ab74d7f466279e42ef6ac5ba405ef4301">anonymous{AArch64MCTargetDesc.cpp}::AArch64MCInstrAnalysis::findPltEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp/#af2cb91b4a276a9864c39790b06f72678">FindSequence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a85cf54f25bd787c7983fe72e15233000">llvm::lto::findThinLTOModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#a9dc8dda7e6f1c6adc7eaaf755f6c27a5">llvm::X86_MC::findX86_64PltEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#aa32860b6f507582db22346076bf5caa0">llvm::X86_MC::findX86PltEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a53f06c06e81412900ac140caaf764ff8">foldSwitchToSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38f536657a01f40d99f770fddee8e14a">llvm::codeview::forEachCodeViewRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a614caf1728d9aec23d5fe873c92208c1">formSplatFromShuffles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ae656922d1c902f1107654bd1ae01501a">llvm::CodeViewYAML::fromDebugH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee5f6b149b3f5ee5ed6ad7db9b58b148">llvm::fullyRecomputeLiveIns</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#a26e5b6731c22761e5c4e7abe1dc13a21">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a293fb71d9772916004e2e65674d0bed0">GenerateFixedLengthSVETBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#aaba8002e40481888d8e4933ce4487081">generateNewInstTree</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a39a3342c858856b421c6e2c306aaf241">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ad544515efb693b15ac9855c6be03189b">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a15fc36bf8d33e06423d939bb34bc9305">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a181dad1cdd60a83a181108d90acd4738">llvm::CondOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a4a1000e5803e731e9dcc572042a98a0b">llvm::ConstantDataArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a79459acee890c44fac5c279584480b08">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a2b15feb32345af4916487fa3fa9d6227">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a0ad360dbce483cc0903211b623b9debd">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ae5bc9cac664aeb67c181f9add7309cfa">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a8ee97870547b76f8387091128a00e90c">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ab8b693ee2fbb4c4173fa2725c110021b">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a8068bfe8ffd6450e61e72665e6887abc">llvm::DagInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelator/#ad3a7b88fce11b12853e7b60a06a033ec">llvm::InstrProfCorrelator::get</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a6553e4e7f2cae85df3c310267a3797c9">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::getAddressesOfVariablesInKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/recordkeeper/#a42410e0ce2a641ccb68ba031c667f2ad">llvm::RecordKeeper::getAllDerivedDefinitions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4617b6f7b2916249d12f30bc81a17855">getAltInstrMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ae76b640db72efe7da1107ed796890d99">getBuildDwordsVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a746052f3a8d6068791b8fc33a2dd0c64">llvm::codeview::getBytesAsCharacters</a>, <a href="/web-llvm/docs/api/classes/llvm/object/resourcesectionref/#acda81c3c28377b5e191fbfdd745d6644">llvm::object::ResourceSectionRef::getContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ae18b7d7be4354e3df59467ddf7d35c63">llvm::object::COFFObjectFile::getDebugPDBInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9446a50b15b6c000a5b3049b1207480c">llvm::getDescImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a98e19eaf03c9744a18996776d77d0ee1">llvm::object::ELFFile&lt; ELFT &gt;::getEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/vftableshaperecord/#ae4b38070fd44d5456121745954d85e47">llvm::codeview::VFTableShapeRecord::getEntryCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#ae6bcc7c94e3742c313341e5883ac618d">getExpressionFrameOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1b29e216a7c9ceac22f3a0467084b2b5">llvm::MachineFunction::getFilterIDFor</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a191a65cff7d80b2651df427db2bbf908">llvm::CCState::getFirstUnallocated</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a6eec77c77aa76611db6766a3f205570c">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a54e552ee615150b4efe5195ac45d4389">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a3d4228cf6f5c478449deca90c6ce2255">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#acc193957138fece590fe07417912f018">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aeecde9516e68842cb97c340bb693a7a9">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aa736794cd9a0acefdb428c5ed892a66f">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aa0e2f7f2755f0a5cb30f1cc35957cb27">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f61cf26d62c676d9c56f47aff24c055">getHalfShuffleMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcdisassembler-cpp-/arcdisassembler/#a60a4c495767416121a1937808b181361">anonymous{ARCDisassembler.cpp}::ARCDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfdisassembler-cpp-/bpfdisassembler/#a5046a0024e7712f11848e29914c387b6">anonymous{BPFDisassembler.cpp}::BPFDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskydisassembler-cpp-/cskydisassembler/#ab02ac21009a84db6e0a786c08e2be1b5">anonymous{CSKYDisassembler.cpp}::CSKYDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a963b35ab133a680b8e40743b1780d099">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdisassembler-cpp-/loongarchdisassembler/#a38b30661f2481e385870d52d8cc9e996">anonymous{LoongArchDisassembler.cpp}::LoongArchDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430disassembler-cpp-/msp430disassembler/#a55019fcf219b7cac44ca62e49a0eeb6a">anonymous{MSP430Disassembler.cpp}::MSP430Disassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcdisassembler-cpp-/ppcdisassembler/#aae7fc67fba3d73dc2dfe4a44f5e399af">anonymous{PPCDisassembler.cpp}::PPCDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdisassembler-cpp-/riscvdisassembler/#a4f3feb7d6e293c81671a60e310dc0382">anonymous{RISCVDisassembler.cpp}::RISCVDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzdisassembler-cpp-/systemzdisassembler/#a63dafb8f39f91ffd08d55e3865374435">anonymous{SystemZDisassembler.cpp}::SystemZDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64disassembler/#aeb2497953080ddc86f9e05b674454ac6">llvm::AArch64Disassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ad9305ad45a7db970a0a198791bea136a">llvm::AMDGPUDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a6df4ba22a0f74d53fd7308406c438a95">llvm::HexagonTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a264036c4b5fffd4ce40a5414d587d26b">llvm::Intrinsic::getIntrinsicInfoTableEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/dataextractor-cpp/#a8aac3d1bd9fe9005fb56a087e0a824e2">getLEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#abc325a2174e8b3649c8867e57f66f3b5">getMaxCalleeSavedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a30a7ce961d5d90ff2fb6c9cee4576e5a">llvm::DILocation::getMergedLocations</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ade3b3b604b9b365a57f791ab198a691a">getNoopInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ae954fcbf0e9b2fe89cfa9d21b931b063">llvm::HvxSelector::getPerfectCompletions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a3030fa8e5d4a78aef7c5a7fa00294ac6">getPropIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a69a2253decaa6ee31ae96ec6e0b3de13">llvm::AArch64RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#ade9b053c3235bc1f054a7086bf1c5551">llvm::MachineTraceMetrics::Trace::getResourceDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#a3bab5c2e4f0b9a464665f79677b7f7e7">llvm::MachineTraceMetrics::Trace::getResourceLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#abf54ff8f66bc899700aaf8887f85313c">llvm::SystemZTTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#aa7c80d89ddf584fde12a68516fe703c2">llvm::object::WasmObjectFile::getSectionSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac947597e4f7b21eda127d16de828a5eb">llvm::getShuffleMaskWithWidestElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7f5e446b08fdb38a854b35dbab34bc0c">getShufflevectorNumGroups</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a9d755165fee4597d8598f64188cd8efe">getStatepointArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a5ed1225be79d7074b85402de2dc1f686">getStatepointBundles</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#af7a0688faef62284ad684e70f342b3da">llvm::RegPressureTracker::getUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#ae3341aa2a4a16c49b2be04002018a1a6">getVectorDeinterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aec2d2e0aa87b178bb2cf624071281e62">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/globalhash/#a61893bf07a35bee262986d74293c6c36">llvm::CodeViewYAML::GlobalHash::GlobalHash</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a456ce65cd7eb7154bc9a1460dcd3eb4a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::groupMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#ad11c85a64a9aca0f5035553171364591">llvm::MipsTargetLowering::HandleByVal</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a8b6fc6699e686f04ca76a628511741b5">llvm::Record::hasDirectSuperClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aa7574b8c35b165904ab21971f6f786a1">llvm::pdb::hashStringV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48e995cee96e6cb663791d755d6b7ef1">llvm::hasUTF16ByteOrderMark</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a376abaf43fce7db08a674a90db19f84c">hasUTF8ByteOrderMark</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a5a2fef7cac2e3df0e6a7d8db4a2db823">shuffles::hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7851d1e39cf3c6f27aa6fe911056a142">incomingValuesAreCompatible</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#a4813065b259c6f6a34961b286913f06c">llvm::coro::AnyRetconABI::init</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#aa9dbc0a952dfbed82b71fd482c4fcdd7">llvm::ThreadSafeTrieRawHashMapBase::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a150e7cedb8221a184efe28d747fd3382">llvm::LanaiInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad64501a368789645f6f80afbce82da90">llvm::insertMultibyteShift</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a33a30176a7fd636333a4e618ef109f57">llvm::CallLowering::insertSRetLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a852a45fa0766bf5cb65ea6010d32330a">llvm::CallLowering::insertSRetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#aba37dfbf85878dd8f544c9bcca63bc48">interleaveLeafValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a204934c6800bce8f4ce892221de4ebbe">interleaveVectors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f0917bf2ae18fac81fea6bf7e887115">llvm::inversePermutation</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a11fb81052cf8abb712c95daa2f0344d6">llvm::GCNTTIImpl::isAlwaysUniform</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae19e733feb019dfcc322e78c91325511">isBigEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a61ef13844d0a136295d9a3acfcf51363">llvm::omp::isCompositeConstruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ad5d72247c1a3137bc2c2c7aaf0000b03">isFixedVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a16658fce14f4b2888f76f0972d239139">isFreeConcat</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ae420d94473ac8cb96686184a551f6097">llvm::slpvectorizer::BoUpSLP::isIdentityOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a3e874f5073fd59211348a2ea23e9d0ce">llvm::GCNTTIImpl::isInlineAsmSourceOfDivergence</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a49a7bbde7c622cc904ed4f8c1857cae6">llvm::slpvectorizer::BoUpSLP::isLoadCombineCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#aeb78ce0ad4d22082b130cd97900caa5d">llvm::ConstantRangeList::isOrderedRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a95644d0b13092f37423d18945ec0f5be">isReplicationMaskWithParams</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#afa640d51b943ce0396e7131bf2352f8a">isReverseOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae3dc8b7983e80b5f9a0af208276e918a">isShuffleEquivalent</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a05d88c62bda0d2e90b00e2407db9b556">isStrictSubset</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ac4d13f5ea905de676278414d7f7c2601">isSubset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aa28651c1e85585ae702f652a8df06019">isSwitchDense</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af83ff96c157ea2db2a7f032cc9c80369">isTargetShuffleEquivalent</a>, <a href="/web-llvm/docs/api/structs/llvm/binaryitemtraits-7e3dbb0894d46ad0ca22830f22e986bb/#a6c96273f1093282fe3c39cc238411483">llvm::BinaryItemTraits&lt; codeview::CVSymbol &gt;::length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ae77cc39ccd9efa05d6afa6936cfc8cd8">llvm::codeview::limitSymbolArrayToScope</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#ae36780715b6058822ae73eb3caeef3aa">shuffles::lo</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#a91d6d8d5af0b8ba44a006860ef830113">llvm::coverage::CoverageMapping::load</a>, <a href="/web-llvm/docs/api/classes/llvm/object/resourcesectionref/#a778c6e8a9d2903a6c5b0501015acd0e2">llvm::object::ResourceSectionRef::load</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab83ddc0d46d65b1f035e1c8599b22b8d">lowerBitreverseShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4e7be374a3346400a32967d91108c3e">llvm::LoongArchTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9157e4aca11eca217c5c6d2c6a2eadbf">llvm::X86TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a22c6a7a1925a0177519e33d49ba91cea">llvm::RISCVTargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ac8dc1642db124c4da34fbec06040a0c4">llvm::SPIRVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac7304188de3005e0d0f0a62cbff5ad31">lowerV16I8Shuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a96929c573ae5a98213a4d8c25554e53f">lowerV8I16GeneralSingleInputShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#adeacac9b0dabeafe536c99c4c3151fef">llvm::HexagonTargetLowering::LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a09b35db55ed7bd3a4027630fff72d970">LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab9c1fef093fb9dfcad2e86ddd0a2a4e6">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a14f663a8d190b740cfb9cbf0d88a7619">llvm::orc::makeJITDylibSearchOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#ae835f4af45721bc129de5e1447cfa4a6">llvm::codeview::CodeViewRecordIO::mapByteVectorTail</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#af8db50c76878b9d7747a77ecdeadbb48">llvm::Intrinsic::matchIntrinsicVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#afffaaa44175e2eeebcc852c80fb03c40">llvm::fuzzerop::matchSecondType</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3df1d9d3afbfe5db4027289cf28d4726">llvm::CombinerHelper::matchShuffleUndefRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a9fac55ed154a25a20608a5f71dc833c0">llvm::SIInstrInfo::materializeImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a51d820fe919d94f220e21e9d1f7361ad">memOpsHaveSameBaseOperands</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aa7e215bdd027461da0d8205cf5ef0e32">mergeCompatibleInvokes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a627f84abfceb75ffd72119423d0147a4">mergeVectorRegsToResultRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp/#a9ee0fea813b095ebe4fc342a4b3c4b53">multikeySort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloadstoreoptimizer-cpp/#a36f341897beb949904185df801dcc02a">needsConstrainedOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/disassembler/webassemblydisassembler-cpp/#a3af3220ede6cc99137a661c057fb4042">nextByte</a>, <a href="/web-llvm/docs/api/classes/anonymous-coveragemapping-cpp-/nextidsbuilder/#a8aa8068dd2c7f1dae5774ac028abe168">anonymous{CoverageMapping.cpp}::NextIDsBuilder::NextIDsBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/disassembler/webassemblydisassembler-cpp/#a65e13c057217c221d060184d88638f07">nextLEB</a>, <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/nsanmemopfn/#a85787eb1162b7d741f8f3b29601e7860">anonymous{NumericalStabilitySanitizer.cpp}::NsanMemOpFn::NsanMemOpFn</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a2f34643744ac2bf92d700a8461d9aeb0">llvm::sampleprof::SampleContext::operator&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#a8949a90af3c69d31f132d6933c4d5914">optimizeDwarfOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/owningarrayref/#a8fbca60dd9be73c5618f85b18a3862ce">llvm::OwningArrayRef&lt; T &gt;::OwningArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodaghvx-cpp/#a72008f93dcab17ba9c0e64f267fd0fab">packSegmentMask</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a9587b0ef9788175b49acc32e1c898642">llvm::ELFAttributeParser::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/object/directx/psvruntimeinfo/#ac30f90a499bf2baa821b2838a784b86b">llvm::object::DirectX::PSVRuntimeInfo::parse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/disassembler/webassemblydisassembler-cpp/#ae6a0d5accd0cfdbb19d3201773677035">parseImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#abf992f403d584a1d6b24de79a3a658b5">llvm::ELFAttributeParser::parseStringAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a066421d8538981830a93a7598a571e8f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef79c7512f86471adf8452b0cf8e2f58">peek</a>, <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a18e95622dd1cef434cddeae8612854d8">llvm::AsmLexer::peekTokens</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/permnetwork/#a783d5995993cd1da9450a50b1a9f3281">anonymous{HexagonISelDAGToDAGHVX.cpp}::PermNetwork::PermNetwork</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fa39647aed67bc62e126a8d8812900f">llvm::prepareTempFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad35f9d7d71a4bdf20246882f712b3c88">llvm::processShuffleMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeimpl/#a6799f9331fcf2d45f792f8c23038aea3">llvm::AttributeImpl::Profile</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a85549679782ae212e691a7edfe985550">ProfileCondOpInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#ad304084fb6fb29e682d116aa9afe3b16">ProfileRecordRecTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48a6deb3e714d54e75caadcf84b0ca76">llvm::propagateMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-7416a4930392106d56f3af1734eb69d7/#abcef45d7793b7eae2f2789356d2f34bd">llvm::detail::BCRecordCoding&lt; ElementTy &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding-7416a4930392106d56f3af1734eb69d7/#a8b116d803b693b21ad96ec7134bc2176">llvm::detail::BCRecordCoding&lt; ElementTy &gt;::read</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofreader-cpp/#aa883a589f91024d0a09d1b3c1821ec85">readBinaryIdsInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#acbb5be14a8102feef6f84e1d2adfaeb7">llvm::AppendingBinaryByteStream::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a1cbc5251f13ad42510760ed61c71e874">llvm::BinaryStreamReader::readCString</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/compactunwindtraits/#a9d9ddd9fe748227f30368cf9bf586ead">llvm::jitlink::CompactUnwindTraits&lt; CRTPImpl, PtrSize &gt;::readEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aac42f02dfb2a8bbe2f6bedea0ff7b29c">llvm::BinaryStreamReader::readFixedString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#ae833f3168bbfb866c7e699bcc31fa19a">readInstruction16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a9cf94f76dec1de7e52ae168a3f24d86b">readInstruction16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a197258c284317a10774b00294361183b">readInstruction16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a9da1c2a7c067001d8f7a38330911f457">readInstruction16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a328747ad97067de92be77a78b8f9507d">readInstruction24</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a2cc677eee55aee4a2a187254920d121c">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#ac019218333036d85003d3db715dfcab7">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a9d2ff5b7963ea79edc3889c72d7c39f5">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a0f7c0a1c6dcff81f4f35cebe317bde15">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#aa30249bb0a7b58400839efb59e26eaff">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#a3fcc2328b16aab5f5620750b7e9b4c41">readInstruction64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#a3fcc2328b16aab5f5620750b7e9b4c41">readInstruction64</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aa580bf8bd5d8f755f546fa9df986260b">llvm::BinaryStreamReader::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamref/#a113ac5e2f45385477dca911a3830d801">llvm::BinaryStreamRef::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/compactunwindtraits/#a183445ddb7eddb88ddac8aa02c0db977">llvm::jitlink::CompactUnwindTraits&lt; CRTPImpl, PtrSize &gt;::readPCRangeSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8fb04904ff931fa4871c8b9601f2a04">llvm::readWideAPInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a17d6db03c2e193f9d391dae5b3847edf">recomputeLiveInValues</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0121eb7b984a5cf2527133cb838d5982">llvm::Attributor::registerFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elf-loongarch-cpp-/#a311b610708cc07a8c2d9808e4ef6761e">anonymous{ELF_loongarch.cpp}::relaxBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad80e7bb9ca75bc924f1a6dfeb9ef3efb">llvm::jitlink::relaxBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a2eb73a15ea2a5105bd2cec95863d7113">llvm::slpvectorizer::BoUpSLP::reorderBottomToTop</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ac54843966305eb21541468d352728681">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ab753ecd3bbe05bc8ceb961ca8f2c6480">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::replaceUsesInInstructionsWithTableLookup</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aae5bad356a0c0583ebad92fbe899230c">llvm::PPCFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a92bee9b9d1c7a9396f6d32bae5f7a563">llvm::Interpreter::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#ab04dd8530994d3914c2398c5105bd74b">llvm::orc::ExecutionSession::runJITDispatchHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a64261c5840053afd36cfbb72666ace95">anonymous{ValueMapper.cpp}::Mapper::scheduleMapAppendingVariable</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopinterchange-cpp-/loopinterchange/#af36ddc49228f8cf6ea22991daf2b26b0">anonymous{LoopInterchange.cpp}::LoopInterchange::selectLoopForInterchange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a750e795af7ca75cfebb03e563cbaddc5">SelectOpcodeFromVT</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/fdsimpleremoteepctransport/#ac70eafd527c133cbc9773c9237179b17">llvm::orc::FDSimpleRemoteEPCTransport::sendMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a90a04d547b4e34b51c649f8fe259d461">llvm::jitlink::Block::setContent</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldchecker/memoryregioninfo/#a07c4b86a6f964b89024354dbc0168104">llvm::RuntimeDyldChecker::MemoryRegionInfo::setContent</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue/#a7230438e78079233a5d7b3bc1d4f14b2">LiveDebugValues::DbgValue::setDbgOpIDs</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a8578a2012c775a890abbda778a6adfa1">llvm::jitlink::Block::setMutableContent</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a66ebc3ec1c8816b16a5f239a8631c780">llvm::SelectionDAG::setNodeMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobeinlinetree/#ab76cb3f6b6cea02db1cc6ebf0704be34">llvm::MCDecodedPseudoProbeInlineTree::setProbes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a0fafeb4f9eaccefdd578d45fa0fd1f9f">setupBranchForGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/shapet/#a728e2c56c479c4da1781fdde8d37728a">llvm::ShapeT::ShapeT</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9f3bcb74818214fe1e8df656c52ab206">shortBundleName</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/compatiblesets/#a4ef2eab86cf6fefd01ef4607cc834432">anonymous{SimplifyCFG.cpp}::CompatibleSets::shouldBelongToSameSet</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a37493b7a361d3374a2731470d964c183">simplifyExtractValueInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a367cc3c1cd48f8723586daebe9a17d00">llvm::simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr/#a28567a06f9ff4a7bbdb9d23603b14cf5">llvm::mca::SourceMgr::size</a>, <a href="/web-llvm/docs/api/classes/llvm/prediteratorcache/#a60c3960dda906754affa59a2fb7c632f">llvm::PredIteratorCache::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d9d7c33311a38eae588e12caf8985ce">llvm::sortPtrAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a4d6b288488bfee7d307b78a36e230986">llvm::MSP430FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a757685f42fe19ad1375d53c7e5aa95b1">llvm::XtensaFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodaghvx-cpp/#a3958b3a97f771703fdce1a60b9e44881">splitMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae12d768edcecd309ab9fa48c23f9bc07">llvm::stable_hash_combine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ac0158188ba4a3924c0284491250b3474">llvm::ARMBaseInstrInfo::SubsumesPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a87b39c65c6a9fd9acdc3cd6ea03ed323">llvm::PPCInstrInfo::SubsumesPredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-armdisassembler-cpp-/armdisassembler/#aff1d6eda516ee7a8ce4dd5334cc39586">anonymous{ARMDisassembler.cpp}::ARMDisassembler::suggestBytesToSkip</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelistattributeimpl/#a86df45aa005496277266b034a8ddfdcd">llvm::ConstantRangeListAttributeImpl::totalSizeToAlloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a75f6ee141c70a7f17fefb2706f5cf6ac">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::transformMaskAfterShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a96196ee6ac47c0ff8c2398bbc4cb775d">llvm::mca::RegisterFile::tryEliminateMoveOrSwap</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ad722656aa63d87c356ec659228865f65">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryICallBranchFunnel</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aedc4689962ab6d484f7b768c64dc8ad6">llvm::pdb::typesetItemList</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#adb133e739b469808feb3635786aeaa01">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::unifyReturnBlockSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjcopy-cpp-/removenotedetail/#aed2b24c385053ea197788dfc04744582">anonymous{ELFObjcopy.cpp}::RemoveNoteDetail::updateData</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#acb739135f91e78694f907e86e5a6c63f">shuffles::vdeal</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a9619ed869f0ef7b7ac90a74c1fdcdfe0">shuffles::vdealb4w</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#ae8bfab8841d5d8482833437e8b4309b9">shuffles::vdealvdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/misexpect/#a8677c5d2618fcf52eda43f5530decb6b">llvm::misexpect::verifyMisExpect</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevsequentialminmaxdeduplicatingvisitor/#a0c647ad9497df165dbc5fd606873b15c">anonymous{ScalarEvolution.cpp}::SCEVSequentialMinMaxDeduplicatingVisitor::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a0015ff019ddc43f0e4840febaf74664d">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ab7d42ec1825f9e56033a386b52d39337">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9ec578dadc7c4409612fdaf21e83dcec">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a220bdf792ced3705543a6e2e5b7e6bfe">shuffles::vpack</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a91e69e6f05e66ead5fa0622d7e113642">shuffles::vshuff</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a05231a6703f721a7938ce95de41743f1">shuffles::vshuffvdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a711350a8af2fb95f4f1ca8cb7fa79374">llvm::WebAssembly::wasmSymbolSetType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4373d3025961c2c2eeca56b02d7d009d">llvm::widenShuffleMaskElts</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ae6b63bcaa1f6638b608f911cd04341e2">llvm::MemorySSAUpdater::wireOldPredecessorsToNewImmediatePredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#a5da8fa1c8cd50b1cccfb561b40d88532">llvm::AppendingBinaryByteStream::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#abb614d7e749a1af26c1d719b28ba4fb7">llvm::BinaryStreamWriter::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/writablemappedblockstream/#abe3861e116c9da3ce15c4dd46a1bfaf7">llvm::msf::WritableMappedBlockStream::writeBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablebinarybytestream/#ab01e4768ed6edae5181351ec2fc8be15">llvm::MutableBinaryByteStream::writeBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e7754bbc7c049946acba12e02f815">llvm::writeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a3da63e49444198a2e47dad26fb6feb67">llvm::orc::writeMachOStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a74c686413929f11d2301cb47bec0fcdb">llvm::sampleprof::SampleProfileWriterBinary::writeSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a5b06dd328e277cc107d21a8ee4266e04">writeSymbolMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a948d67dcc777891db830488aaa2ff78d">llvm::object::writeUniversalBinaryToStream</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a8dd06742877ada9717169e974f5f5de2">writeWithCommas</a>.</p>

</div>
</div>

### slice {#aebf6ca7590d4f766b894044015a0fa31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::slice (size_t N, size_t M)</td>
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

<p>slice(n, m) - Chop off the first N elements of the array, and keep M elements in the array.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a80596370c938add79f4045e0dfe08a4d">llvm::CCState::AllocateRegBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a8efa56ca3bfdd8c715939f9e0b24ccda">buildNew</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a7a5607fcb0a195620036bb0f1217c8a2">llvm::MachineInstr::cloneMergedMemRefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a557be4c1daf6eb2611b214f927dccee2">llvm::ConstantFoldExtractValueInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7fa9b738742521d0a684cec016ef47e">llvm::ConstantFoldInsertValueInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a582e15236324209782fbeb6b5079e93a">llvm::dlltoolDriverMain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a434621cd1f8f1c0240a47b65ba19ea9b">eat12Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a7d8ee6944c8121c49c2a8da4b1695fe7">eat16Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aaff8a7b712c8ea0bb1275e621119e498">eatBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae29b7bb67763c63132e57471f88ac80f">llvm::FindInsertedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wholeprogramdevirt/#a8ab22ea42eaf359bb9eb8382c0afc616">llvm::wholeprogramdevirt::findLowestOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a90bc029b97b6d91b7a77c86bb88630c2">getIndexedTypeInternal</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a963b35ab133a680b8e40743b1780d099">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#ad9305ad45a7db970a0a198791bea136a">llvm::AMDGPUDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7f5e446b08fdb38a854b35dbab34bc0c">getShufflevectorNumGroups</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a93b09ffda91456ad8838782c225842d0">llvm::jitlink::Symbol::getSymbolContent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aa7574b8c35b165904ab21971f6f786a1">llvm::pdb::hashStringV2</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype/#acc7b052c15351bf328b64c17027eae9d">llvm::codeview::GloballyHashedType::hashType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0469afc3caef8616d4b1c7501cba1b8">isHorizontalBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1df6c429f484cbf4fd21a5d306f53671">llvm::libDriverMain</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ae9677047c398a916ab4a5a6fabeb36e7">llvm::MCInstPrinter::matchAliasPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#af8db50c76878b9d7747a77ecdeadbb48">llvm::Intrinsic::matchIntrinsicVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a33ec230e070e9dc242e28bf8fd9c28f9">llvm::jitlink::ppc64::pickStub</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding/#a899ed81dbda72496c2d105042da6acef">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/bcrecordcoding/#af455dc61361369b5ef61f16db37c3c66">llvm::detail::BCRecordCoding&lt; ElementTy, Fields &gt;::read</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#acbb5be14a8102feef6f84e1d2adfaeb7">llvm::AppendingBinaryByteStream::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream/#a1a421432438b984e24590ea8169dc589">llvm::msf::MappedBlockStream::readBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/appendingbinarybytestream/#acc2ef96d39a2d4d967fc235188ef4797">llvm::AppendingBinaryByteStream::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamref/#a113ac5e2f45385477dca911a3830d801">llvm::BinaryStreamRef::readLongestContiguousChunk</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elf-loongarch-cpp-/#a311b610708cc07a8c2d9808e4ef6761e">anonymous{ELF_loongarch.cpp}::relaxBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad80e7bb9ca75bc924f1a6dfeb9ef3efb">llvm::jitlink::relaxBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a92bee9b9d1c7a9396f6d32bae5f7a563">llvm::Interpreter::runFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a37493b7a361d3374a2731470d964c183">simplifyExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjcopy-cpp-/removenotedetail/#aed2b24c385053ea197788dfc04744582">anonymous{ELFObjcopy.cpp}::RemoveNoteDetail::updateData</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a9c48163b33da5da66af7a1e8f4deb637">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a> and <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/jsonwriter/#a1b1532a2254d760451e96bf7b299943b">anonymous{VirtualFileSystem.cpp}::JSONWriter::write</a>.</p>

</div>
</div>

### slice {#a5c498de3bb758473707e9198311eb15f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::slice (size_t N)</td>
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

<p>slice(n) - Chop off the first N elements of the array.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### take\_back {#ac1f72f67a93986bb68c8b7f8a2dba4ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::take_back (size_t N=1)</td>
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

<p>Return a copy of *this with only the last <span class="doxyComputerOutput">N</span> elements.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/shuffles/#a5a2fef7cac2e3df0e6a7d8db4a2db823">shuffles::hi</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a75e6b6bf03adf614aaf100a9afdcd612">optimizeVectorResizeWithIntegerBitCasts</a>.</p>

</div>
</div>

### take\_front {#a33da2ddf6f447892591c86d9d3771b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::take_front (size_t N=1)</td>
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

<p>Return a copy of *this with only the first <span class="doxyComputerOutput">N</span> elements.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a38f536657a01f40d99f770fddee8e14a">llvm::codeview::forEachCodeViewRecord</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ad544515efb693b15ac9855c6be03189b">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype/#acc7b052c15351bf328b64c17027eae9d">llvm::codeview::GloballyHashedType::hashType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/memory64iterator/#ad39ec39419bdf09f905180dae5d93b8f">llvm::object::MinidumpFile::Memory64Iterator::inc</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#afe13f78db01d9c3d12b2cf017bd9fbeb">llvm::sampleprof::SampleContext::isPrefixOf</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#ae36780715b6058822ae73eb3caeef3aa">shuffles::lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a75e6b6bf03adf614aaf100a9afdcd612">optimizeVectorResizeWithIntegerBitCasts</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryitemstream/#a6f2c735b75cbf7437533bbe15c76563a">llvm::BinaryItemStream&lt; T, Traits &gt;::readBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aedc4689962ab6d484f7b768c64dc8ad6">llvm::pdb::typesetItemList</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a8dd06742877ada9717169e974f5f5de2">writeWithCommas</a>.</p>

</div>
</div>

### take\_until {#a80e3c4f2aa4ad50e0d9b606187fc9074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::take_until (PredicateT Pred)</td>
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

<p>Return the first N elements of this Array that don't satisfy the given predicate.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### take\_while {#a725ac4896f684f75ab69391e11ae9b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::ArrayRef&lt; T &gt;::take_while (PredicateT Pred)</td>
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

<p>Return the first N elements of this Array that satisfy the given predicate.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operator Overloads

### operator\[\] {#ad8bda555014f88be8886b8e4694e2c78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; llvm::ArrayRef&lt; T &gt;::operator[] (size_t Index)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### operator= {#ae9210a8d36502f3d090838bdda24f3f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename U&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_same&lt; U, T &gt;::value, ArrayRef&lt; T &gt; &gt; &amp; llvm::ArrayRef&lt; T &gt;::operator= (U &amp;&amp; Temporary)</td>
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

<p>Disallow accidental assignment from a temporary.</p>


<p>The declaration here is extra complicated so that "arrayRef = {}" continues to select the move assignment operator.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/owningarrayref/#a1bebad48e7eabac87a08e88f241ff072">llvm::OwningArrayRef&lt; T &gt;::operator=</a>.</p>

</div>
</div>

### operator= {#a060ed5ac235d16662fe2409975c07773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename U&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_same&lt; U, T &gt;::value, ArrayRef&lt; T &gt; &gt; &amp; llvm::ArrayRef&lt; T &gt;::operator= (std::initializer_list&lt; U &gt;)</td>
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

<p>Disallow accidental assignment from a temporary.</p>


<p>The declaration here is extra complicated so that "arrayRef = {}" continues to select the move assignment operator.</p>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Expensive Operations

### vec {#a1d0fa3771a3eafd8df26bca2518b5ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; T &gt; llvm::ArrayRef&lt; T &gt;::vec ()</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aca4868511b7a594d12cd9581b9777e9f">combineDIExpressions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Conversion operators

### operator std::vector&lt; T &gt; {#a745a0df36a633dcbc4acfd0bf9dffe17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; T &gt;::operator std::vector&lt; T &gt; ()</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
