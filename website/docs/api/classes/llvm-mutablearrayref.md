---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mutablearrayref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MutableArrayRef` Class Template

<p><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> - Represent a mutable reference to an array (0 or more elements consecutively in memory), i.e. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
class llvm::MutableArrayRef&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> - Represent a constant reference to an array (0 or more elements consecutively in memory), i.e. <a href="/web-llvm/docs/api/classes/llvm/arrayref/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/owningarrayref">OwningArrayRef&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> that owns its array. <a href="/web-llvm/docs/api/classes/llvm/owningarrayref/#details">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63cc60c25af6bab71c0d5e415613249a">value_type</a> = T</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae585dc2bb725411691c2cd3b425580f">pointer</a> = <a href="#a63cc60c25af6bab71c0d5e415613249a">value_type</a> *</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29cdddbb6f548462d7581ba1444278ba">const_pointer</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a63cc60c25af6bab71c0d5e415613249a">value_type</a> *</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a42bb48d9bab4431e28cef961c1a29367">reference</a> = <a href="#a63cc60c25af6bab71c0d5e415613249a">value_type</a> &amp;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac906c239c48de1ee82498173d0b159a7">const_reference</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a63cc60c25af6bab71c0d5e415613249a">value_type</a> &amp;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82721df9f348725763590ea24d8176a2">iterator</a> = <a href="#aae585dc2bb725411691c2cd3b425580f">pointer</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6ae59d0f42f3a52a32b2e0a72de6787a">const_iterator</a> = <a href="#a29cdddbb6f548462d7581ba1444278ba">const_pointer</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afefa3947fd9e8ffc639c675702b6e6f3">reverse_iterator</a> = std::reverse_iterator&lt; <a href="#a82721df9f348725763590ea24d8176a2">iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75379f35af587304f2e4835121ded6e0">const_reverse_iterator</a> = std::reverse_iterator&lt; <a href="#a6ae59d0f42f3a52a32b2e0a72de6787a">const_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a90991eb77b7aa616cdbe3cd306e95a37">size_type</a> = size_t</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aede3356080eefde9a707900e176803c4">difference_type</a> = ptrdiff_t</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a6232f41270179aa7dba932bd57db9c67">MutableArrayRef</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>. <a href="#a6232f41270179aa7dba932bd57db9c67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af93287e76168401e47ea6268ecd80d3e">MutableArrayRef</a> (std::nullopt_t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from std::nullopt. <a href="#af93287e76168401e47ea6268ecd80d3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a15b271ae19fe28f3311f7a18a3644ee0">MutableArrayRef</a> (T &amp;OneElt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a single element. <a href="#a15b271ae19fe28f3311f7a18a3644ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a597692d37f65128b2753742b8b19f023">MutableArrayRef</a> (T *data, size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a pointer and length. <a href="#a597692d37f65128b2753742b8b19f023">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a47898b065f2b1fd92df28fa66b9198d1">MutableArrayRef</a> (T *begin, T *end)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a range. <a href="#a47898b065f2b1fd92df28fa66b9198d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#acdbc443c0878ab2f91a0fd112b07d9b3">MutableArrayRef</a> (SmallVectorImpl&lt; T &gt; &amp;Vec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>. <a href="#acdbc443c0878ab2f91a0fd112b07d9b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac56caee1859ddca4cf349523db072421">MutableArrayRef</a> (std::vector&lt; T &gt; &amp;Vec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a std::vector. <a href="#ac56caee1859ddca4cf349523db072421">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a691c7628d7170486a8cff1c89ea0fcd1">MutableArrayRef</a> (std::array&lt; T, N &gt; &amp;Arr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a std::array. <a href="#a691c7628d7170486a8cff1c89ea0fcd1">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acca5e74fa7d80fec49d0f74f1e70c40f">MutableArrayRef</a> (T(&amp;Arr)[N])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a C array. <a href="#acca5e74fa7d80fec49d0f74f1e70c40f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0bf5f8e45bfccb0805b5e12d44622271">data</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a82721df9f348725763590ea24d8176a2">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae2bf8b46988a2fc0589e95903930c19">begin</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a82721df9f348725763590ea24d8176a2">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d959094f4544749c129c46034cbed67">end</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#afefa3947fd9e8ffc639c675702b6e6f3">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3df721fcf3c8137e001ed99aded1be59">rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#afefa3947fd9e8ffc639c675702b6e6f3">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aef01345ce5602b267175a8b505b4be04">rend</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fb86e9e92241fe6fe6b2058650e3a67">front</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>front - Get the first element. <a href="#a6fb86e9e92241fe6fe6b2058650e3a67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf7853428d9cb2b59fe268b757e3dc16">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>back - Get the last element. <a href="#aaf7853428d9cb2b59fe268b757e3dc16">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae671f7b11f895cb673f6ee9a3c694359">slice</a> (size_t N, size_t M) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>slice(n, m) - Chop off the first N elements of the array, and keep M elements in the array. <a href="#ae671f7b11f895cb673f6ee9a3c694359">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a526a7f286fa3dbf805ff61fbb35d84f7">slice</a> (size_t N) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>slice(n) - Chop off the first N elements of the array. <a href="#a526a7f286fa3dbf805ff61fbb35d84f7">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a23489fd833f61022bf08dbe3ba9f1973">drop_front</a> (size_t N=1) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop the first <span class="doxyComputerOutput">N</span> elements of the array. <a href="#a23489fd833f61022bf08dbe3ba9f1973">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1acfeed5712da9a4ffafda05fac15ac">drop_back</a> (size_t N=1) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class PredicateT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae96bbcc72fae849ad6258d7f1fb381ba">drop_while</a> (PredicateT Pred) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a copy of *this with the first N elements satisfying the given predicate removed. <a href="#ae96bbcc72fae849ad6258d7f1fb381ba">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af35bc4512e46f60f38777f1e4f807712">drop_until</a> (PredicateT Pred) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a copy of *this with the first N elements not satisfying the given predicate removed. <a href="#af35bc4512e46f60f38777f1e4f807712">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af7f90a0fd93435c0e075d55928d4320d">take_front</a> (size_t N=1) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a copy of *this with only the first <span class="doxyComputerOutput">N</span> elements. <a href="#af7f90a0fd93435c0e075d55928d4320d">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2efcc9f83bc3a5da3fbfc9feb047a7a0">take_back</a> (size_t N=1) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a copy of *this with only the last <span class="doxyComputerOutput">N</span> elements. <a href="#a2efcc9f83bc3a5da3fbfc9feb047a7a0">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad66ff8aa58d4407e275b9d4c637b434b">take_while</a> (PredicateT Pred) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first N elements of this Array that satisfy the given predicate. <a href="#ad66ff8aa58d4407e275b9d4c637b434b">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ff1a1b476288aaf721d158bcfaf8767">take_until</a> (PredicateT Pred) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first N elements of this Array that don't satisfy the given predicate. <a href="#a0ff1a1b476288aaf721d158bcfaf8767">More...</a></p>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaed2ef7ac9490f46b0eacddd11dd015d">operator[]</a> (size_t Index) const</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> - Represent a mutable reference to an array (0 or more elements consecutively in memory), i.e.</p>


<p>a start pointer and a length. It allows various APIs to take and modify consecutive elements easily and conveniently.</p>


<p>This class does not own the underlying data, it is expected to be used in situations where the data resides in some other buffer, whose lifetime extends past that of the <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>. For this reason, it is not in general safe to store a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>.</p>


<p>This is intended to be trivially copyable, so it should be passed by value.</p>


<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a6ae59d0f42f3a52a32b2e0a72de6787a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::const_iterator =  const_pointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### const\_pointer {#a29cdddbb6f548462d7581ba1444278ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::const_pointer =  const value_type *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### const\_reference {#ac906c239c48de1ee82498173d0b159a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::const_reference =  const value_type &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#a75379f35af587304f2e4835121ded6e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::const_reverse_iterator =  std::reverse_iterator&lt;const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### difference\_type {#aede3356080eefde9a707900e176803c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::difference_type =  ptrdiff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### iterator {#a82721df9f348725763590ea24d8176a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::iterator =  pointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### pointer {#aae585dc2bb725411691c2cd3b425580f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::pointer =  value_type *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### reference {#a42bb48d9bab4431e28cef961c1a29367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::reference =  value_type &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### reverse\_iterator {#afefa3947fd9e8ffc639c675702b6e6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::reverse_iterator =  std::reverse_iterator&lt;iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### size\_type {#a90991eb77b7aa616cdbe3cd306e95a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::size_type =  size_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### value\_type {#a63cc60c25af6bab71c0d5e415613249a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MutableArrayRef&lt; T &gt;::value_type =  T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MutableArrayRef() {#a6232f41270179aa7dba932bd57db9c67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MutableArrayRef&lt; T &gt;::MutableArrayRef ()</td>
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

<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>.</p>

<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/owningarrayref/#a1bebad48e7eabac87a08e88f241ff072">llvm::OwningArrayRef&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/owningarrayref/#a8fbca60dd9be73c5618f85b18a3862ce">llvm::OwningArrayRef&lt; T &gt;::OwningArrayRef</a> and <a href="/web-llvm/docs/api/classes/llvm/owningarrayref/#ab3e9d8b98f7f93718944a87f974de2a5">llvm::OwningArrayRef&lt; T &gt;::OwningArrayRef</a>.</p>

</div>
</div>

### MutableArrayRef() {#af93287e76168401e47ea6268ecd80d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MutableArrayRef&lt; T &gt;::MutableArrayRef (std::nullopt_t)</td>
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

<p>Construct an empty <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from std::nullopt.</p>

<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### MutableArrayRef() {#a15b271ae19fe28f3311f7a18a3644ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MutableArrayRef&lt; T &gt;::MutableArrayRef (T &amp; OneElt)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a single element.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### MutableArrayRef() {#a597692d37f65128b2753742b8b19f023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MutableArrayRef&lt; T &gt;::MutableArrayRef (T * data, size_t length)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a pointer and length.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### MutableArrayRef() {#a47898b065f2b1fd92df28fa66b9198d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MutableArrayRef&lt; T &gt;::MutableArrayRef (T * begin, T * end)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a range.</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### MutableArrayRef() {#acdbc443c0878ab2f91a0fd112b07d9b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MutableArrayRef&lt; T &gt;::MutableArrayRef (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; T &gt; &amp; Vec)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### MutableArrayRef() {#ac56caee1859ddca4cf349523db072421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MutableArrayRef&lt; T &gt;::MutableArrayRef (std::vector&lt; T &gt; &amp; Vec)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a std::vector.</p>

<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### MutableArrayRef() {#a691c7628d7170486a8cff1c89ea0fcd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MutableArrayRef&lt; T &gt;::MutableArrayRef (std::array&lt; T, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt; &amp; Arr)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a std::array.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### MutableArrayRef() {#acca5e74fa7d80fec49d0f74f1e70c40f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MutableArrayRef&lt; T &gt;::MutableArrayRef (T(&amp;) Arr=[N])</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a> from a C array.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#aaf7853428d9cb2b59fe268b757e3dc16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; llvm::MutableArrayRef&lt; T &gt;::back ()</td>
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

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>.</p>

</div>
</div>

### begin() {#aae2bf8b46988a2fc0589e95903930c19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MutableArrayRef&lt; T &gt;::begin ()</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a701e935a2d02fd488218cf26b8eedb67">anonymous{ELFObjectWriter.cpp}::ELFWriter::computeSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a85cf54f25bd787c7983fe72e15233000">llvm::lto::findThinLTOModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#aba37dfbf85878dd8f544c9bcca63bc48">interleaveLeafValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a94ed22ca5dc3213bfb96e1ddbc41952e">llvm::X86FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/djb-cpp/#aac5945e1ef4a322f993cb0d06c781e85">toUTF8</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#aae6594d69bd253616ae16674187e6396">turnVectorIntoSplatVector</a>.</p>

</div>
</div>

### data() {#a0bf5f8e45bfccb0805b5e12d44622271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::MutableArrayRef&lt; T &gt;::data ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#af5c4dc333adfdd30afcce056b9b97484">llvm::detail::IEEEFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ac22ab49b0b7cf93ae570c6a5b8049b34">llvm::jitlink::LinkGraph::createMutableContentBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/object/decompressor/#aeff1a966d66b995e39f35c393a437a10">llvm::object::Decompressor::decompress</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elf-loongarch-cpp-/#ab95caecf5183ebc775ad57c57b601666">anonymous{ELF_loongarch.cpp}::finalizeBlockRelax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4e54d7200f6c98e3f58a44763335d5f6">llvm::jitlink::finalizeBlockRelax</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a65f27123f9333b3ee05446a346267d87">llvm::pdb::TpiStreamBuilder::finalizeMsfLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/owningarrayref/#a1bebad48e7eabac87a08e88f241ff072">llvm::OwningArrayRef&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block/#a8578a2012c775a890abbda778a6adfa1">llvm::jitlink::Block::setMutableContent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobeinlinetree/#ab76cb3f6b6cea02db1cc6ebf0704be34">llvm::MCDecodedPseudoProbeInlineTree::setProbes</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilderloadcommand-53fbc3ff1fe537ac82d0dbe3f046b52d/#a035c6857b0d8984299f7f484bfb51247">llvm::orc::MachOBuilderLoadCommand&lt; MachO::LC_ID_DYLIB &gt;::write</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilderloadcommand-4061795aedd4928f0b62c3a8172ddd1d/#a2ee15e7913566fd723075d88af8f800e">llvm::orc::MachOBuilderLoadCommand&lt; MachO::LC_LOAD_DYLIB &gt;::write</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilderloadcommand-2bc3393507a2277c971c82f4255da9a6/#a886e99a47d5a88ef183fe4ef99919a6f">llvm::orc::MachOBuilderLoadCommand&lt; MachO::LC_RPATH &gt;::write</a> and <a href="/web-llvm/docs/api/classes/llvm/owningarrayref/#a4b29b5dc68eaaba0747d2e1314b3059f">llvm::OwningArrayRef&lt; T &gt;::~OwningArrayRef</a>.</p>

</div>
</div>

### drop\_back() {#ad1acfeed5712da9a4ffafda05fac15ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::drop_back (size_t N=1)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### drop\_front() {#a23489fd833f61022bf08dbe3ba9f1973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::drop_front (size_t N=1)</td>
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

<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#aba37dfbf85878dd8f544c9bcca63bc48">interleaveLeafValues</a>.</p>

</div>
</div>

### drop\_until() {#af35bc4512e46f60f38777f1e4f807712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::drop_until (PredicateT Pred)</td>
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

<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### drop\_while() {#ae96bbcc72fae849ad6258d7f1fb381ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::drop_while (PredicateT Pred)</td>
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

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### end() {#a9d959094f4544749c129c46034cbed67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MutableArrayRef&lt; T &gt;::end ()</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a701e935a2d02fd488218cf26b8eedb67">anonymous{ELFObjectWriter.cpp}::ELFWriter::computeSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a94ed22ca5dc3213bfb96e1ddbc41952e">llvm::X86FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/djb-cpp/#aac5945e1ef4a322f993cb0d06c781e85">toUTF8</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#aae6594d69bd253616ae16674187e6396">turnVectorIntoSplatVector</a>.</p>

</div>
</div>

### front() {#a6fb86e9e92241fe6fe6b2058650e3a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; llvm::MutableArrayRef&lt; T &gt;::front ()</td>
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

<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### rbegin() {#a3df721fcf3c8137e001ed99aded1be59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::MutableArrayRef&lt; T &gt;::rbegin ()</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### rend() {#aef01345ce5602b267175a8b505b4be04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::MutableArrayRef&lt; T &gt;::rend ()</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### slice() {#ae671f7b11f895cb673f6ee9a3c694359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::slice (size_t N, size_t M)</td>
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

<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad64501a368789645f6f80afbce82da90">llvm::insertMultibyteShift</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp/#a9ee0fea813b095ebe4fc342a4b3c4b53">multikeySort</a>.</p>

</div>
</div>

### slice() {#a526a7f286fa3dbf805ff61fbb35d84f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::slice (size_t N)</td>
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

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### take\_back() {#a2efcc9f83bc3a5da3fbfc9feb047a7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::take_back (size_t N=1)</td>
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

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>.</p>

</div>
</div>

### take\_front() {#af7f90a0fd93435c0e075d55928d4320d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::take_front (size_t N=1)</td>
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

<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#aba37dfbf85878dd8f544c9bcca63bc48">interleaveLeafValues</a>.</p>

</div>
</div>

### take\_until() {#a0ff1a1b476288aaf721d158bcfaf8767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::take_until (PredicateT Pred)</td>
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

<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

### take\_while() {#ad66ff8aa58d4407e275b9d4c637b434b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; T &gt; llvm::MutableArrayRef&lt; T &gt;::take_while (PredicateT Pred)</td>
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

<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operator Overloads

### operator\[\] {#aaed2ef7ac9490f46b0eacddd11dd015d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; llvm::MutableArrayRef&lt; T &gt;::operator[] (size_t Index)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">ArrayRef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
