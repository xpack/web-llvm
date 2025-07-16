---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stringref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StringRef` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> - Represent a constant reference to a string, i.e. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::StringRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around a string literal that serves as a proxy for constructing global tables of StringRefs with the length computed at compile time. <a href="/web-llvm/docs/api/classes/llvm/stringliteral/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d37563688a61a452fb26e317e37308">iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c923dfa66a41094c8abcd145c7b0a0b">const_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e59e2d53e5ee736ee060be7c457508">size_type</a> = size_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4cb9ad24aa1c964a10403ca9d0f72a5">value_type</a> = char</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71dad3aa532ebd2a4f2eb1a686bafe3e">reverse_iterator</a> = std::reverse_iterator&lt; <a href="#a20d37563688a61a452fb26e317e37308">iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3029690daaf7b8559fc3102afc79f009">const_reverse_iterator</a> = std::reverse_iterator&lt; <a href="#a4c923dfa66a41094c8abcd145c7b0a0b">const_iterator</a> &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb206dfcfc5a1d30e76b35f072728d70">Data</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The start of the string, in an external buffer. <a href="#adb206dfcfc5a1d30e76b35f072728d70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c2386bfb11c7292781ba82dc3094b7">Length</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The length of the string. <a href="#a15c2386bfb11c7292781ba82dc3094b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afba519c3188e4820e2f4d7542732e20f">compareMemory</a> (const char *Lhs, const char *Rhs, size_t Length)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a> = ~size_t(0)</td>
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

## Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an empty string ref. <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dd5c8e50b79ad7ad01c11b63113e1b8">StringRef</a> (std::nullptr_t)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable conversion from nullptr. <a href="#a9dd5c8e50b79ad7ad01c11b63113e1b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc1c70c28eb2f5a53ad0dcac4c56b4d">StringRef</a> (const char *Str LLVM_LIFETIME_BOUND)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a string ref from a cstring. <a href="#a9bc1c70c28eb2f5a53ad0dcac4c56b4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70392c6eca2623b798f965f66db768df">StringRef</a> (const char *data LLVM_LIFETIME_BOUND, size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a string ref from a pointer and length. <a href="#a70392c6eca2623b798f965f66db768df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebcb6e1997e871ac41f506eff6bdc051">StringRef</a> (const std::string &amp;Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a string ref from an std::string. <a href="#aebcb6e1997e871ac41f506eff6bdc051">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7220b1d3bfd1095940206fa563fdb1f">StringRef</a> (std::string_view Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a string ref from an std::string_view. <a href="#af7220b1d3bfd1095940206fa563fdb1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Iterators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a20d37563688a61a452fb26e317e37308">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f643f1eb1939362c7dd79361bcbd0e">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a20d37563688a61a452fb26e317e37308">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a996c7ca3dd6843ba5d55a7c217770270">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a71dad3aa532ebd2a4f2eb1a686bafe3e">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69857be962bd85fe67eb0fb74578c059">rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a71dad3aa532ebd2a4f2eb1a686bafe3e">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d06fee60cfd116e8c2a4baee25a929">rend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbc826dc76fd535f887e035d1795aa84">bytes_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ba44ae8e92a80fde434e1ab19994cc">bytes_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21fde218101d7b15d7e4edddd5b8b0a8">bytes</a> () const</td>
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

## String Operations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>data - Get a pointer to the start of the string (which may not be null terminated). <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc80c585ad5882da8cae7b5968f7e74">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>empty - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the string is empty. <a href="#a2dc80c585ad5882da8cae7b5968f7e74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>size - Get the string size. <a href="#a5db9240c74644c67759dd0f901fc3c7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61364ca3a5ff90fb2aa0d5a371fd43f7">front</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>front - Get the first character in the string. <a href="#a61364ca3a5ff90fb2aa0d5a371fd43f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b6faabb08339ea1dd11e9d37a668634">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>back - Get the last character in the string. <a href="#a5b6faabb08339ea1dd11e9d37a668634">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Allocator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac66731b70af2ad5aded1ce13a20acb29">copy</a> (Allocator &amp;A) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae46058c90a3c703357331a6501b32f1c">equals_insensitive</a> (StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for string equality, ignoring case. <a href="#ae46058c90a3c703357331a6501b32f1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c6424784f132b91eb387a3ee0b57c9">compare</a> (StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>compare - Compare two strings; the result is negative, zero, or positive if this string is lexicographically less than, equal to, or greater than the <span class="doxyComputerOutput">RHS</span>. <a href="#ae0c6424784f132b91eb387a3ee0b57c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c79bda245d64ef5df420f94ec4bbd1">compare_insensitive</a> (StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two strings, ignoring case. <a href="#ae9c79bda245d64ef5df420f94ec4bbd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3989cbad7cca2a86cb7d3a0627748b">compare_numeric</a> (StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>compare_numeric - Compare two strings, treating sequences of digits as numbers. <a href="#a8a3989cbad7cca2a86cb7d3a0627748b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c1f447b5d754191564ae340ee4253b">edit_distance</a> (StringRef Other, bool AllowReplacements=true, unsigned MaxEditDistance=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the edit distance between this string and another string. <a href="#a51c1f447b5d754191564ae340ee4253b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1ef526cd95ea3036b0569aabacc1c9">edit_distance_insensitive</a> (StringRef Other, bool AllowReplacements=true, unsigned MaxEditDistance=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223dd14e7d12bc5cea01889b972a98b2">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>str - Get the contents as an std::string. <a href="#a223dd14e7d12bc5cea01889b972a98b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1344e353958db14e66ec7ab574001a">lower</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c884ed90d5d38e5d0546d61c4bebe3e">upper</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the given ASCII string to uppercase. <a href="#a4c884ed90d5d38e5d0546d61c4bebe3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Operator Overloads Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae8d94051e57dabbf8ffabfcbc9063d">operator[]</a> (size_t Index) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acdf39985a87ec1d031fc9739fa559b71">operator=</a> (T &amp;&amp;Str)=delete -&gt; std::enable_if_t&lt; std::is_same&lt; T, std::string &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disallow accidental assignment from a temporary std::string. <a href="#acdf39985a87ec1d031fc9739fa559b71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Type Conversions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed45f95729e679cb0c160456fe94602b">operator std::string_view</a> () const</td>
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

## String Predicates Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd8968ff703aaeb395dcd63f6805ff1">starts_with</a> (StringRef Prefix) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string starts with the given <span class="doxyComputerOutput">Prefix</span>. <a href="#a2cd8968ff703aaeb395dcd63f6805ff1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ebff92f9ef18f3009f88457a09776d">starts_with</a> (char Prefix) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343b6c58108519aca196bb54b1d1a6ef">starts_with_insensitive</a> (StringRef Prefix) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string starts with the given <span class="doxyComputerOutput">Prefix</span>, ignoring case. <a href="#a343b6c58108519aca196bb54b1d1a6ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca439bf65258d9d8d057812938b617c5">ends_with</a> (StringRef Suffix) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string ends with the given <span class="doxyComputerOutput">Suffix</span>. <a href="#aca439bf65258d9d8d057812938b617c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a393bbf5d4d82eaebfc257042c3a82ece">ends_with</a> (char Suffix) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae57b9ee061903472c1cc9082849ed34e">ends_with_insensitive</a> (StringRef Suffix) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string ends with the given <span class="doxyComputerOutput">Suffix</span>, ignoring case. <a href="#ae57b9ee061903472c1cc9082849ed34e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## String Searching Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab312a8386488873bac2eddfc67c22be">find</a> (char C, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the first character <span class="doxyComputerOutput">C</span> in the string. <a href="#aab312a8386488873bac2eddfc67c22be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc37e42bcf44968ae55ddc8c69748150">find_insensitive</a> (char C, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the first character <span class="doxyComputerOutput">C</span> in the string, ignoring case. <a href="#abc37e42bcf44968ae55ddc8c69748150">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a> (function_ref&lt; bool(char)&gt; F, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the first character satisfying the predicate <span class="doxyComputerOutput">F</span>. <a href="#a24d07ee06f50c285b723a97222619ff0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4ee2901ac2ae201e839a7972038a1c">find_if_not</a> (function_ref&lt; bool(char)&gt; F, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the first character not satisfying the predicate <span class="doxyComputerOutput">F</span>. <a href="#afe4ee2901ac2ae201e839a7972038a1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82369bea2700347f68e1f43e30d2d47b">find</a> (StringRef Str, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the first string <span class="doxyComputerOutput">Str</span> in the string. <a href="#a82369bea2700347f68e1f43e30d2d47b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fab98a15364352e9a7a48da307fde69">find_insensitive</a> (StringRef Str, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the first string <span class="doxyComputerOutput">Str</span> in the string, ignoring case. <a href="#a2fab98a15364352e9a7a48da307fde69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d45ce069c1a09ca84672df63acf096">rfind</a> (char C, size_t From=npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the last character <span class="doxyComputerOutput">C</span> in the string. <a href="#a97d45ce069c1a09ca84672df63acf096">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba4f98b846a8b05965f39ca3a5c33fd2">rfind_insensitive</a> (char C, size_t From=npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the last character <span class="doxyComputerOutput">C</span> in the string, ignoring case. <a href="#aba4f98b846a8b05965f39ca3a5c33fd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af90e5d9d8d99f68f9d4616bd026b0eab">rfind</a> (StringRef Str) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the last string <span class="doxyComputerOutput">Str</span> in the string. <a href="#af90e5d9d8d99f68f9d4616bd026b0eab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e7e0bebc570bc6814cdefd1f2ecda3">rfind_insensitive</a> (StringRef Str) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the last string <span class="doxyComputerOutput">Str</span> in the string, ignoring case. <a href="#a56e7e0bebc570bc6814cdefd1f2ecda3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b15a8c0022febbe39d17ab933737a8">find_first_of</a> (char C, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the first character in the string that is <span class="doxyComputerOutput">C</span>, or npos if not found. <a href="#a93b15a8c0022febbe39d17ab933737a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38cc29d28845d48d8423918d8910d12">find_first_of</a> (StringRef Chars, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the first character in the string that is in <span class="doxyComputerOutput">Chars</span>, or npos if not found. <a href="#af38cc29d28845d48d8423918d8910d12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae851887270f35d2a2670a79b9833d45b">find_first_not_of</a> (char C, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the first character in the string that is not <span class="doxyComputerOutput">C</span> or npos if not found. <a href="#ae851887270f35d2a2670a79b9833d45b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18de63f444e95dfff81803a482ab6eec">find_first_not_of</a> (StringRef Chars, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the first character in the string that is not in the string <span class="doxyComputerOutput">Chars</span>, or npos if not found. <a href="#a18de63f444e95dfff81803a482ab6eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a7c222449f3208a532168c90bfb654d">find_last_of</a> (char C, size_t From=npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the last character in the string that is <span class="doxyComputerOutput">C</span>, or npos if not found. <a href="#a7a7c222449f3208a532168c90bfb654d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1226ed87e22d9ca9bfd8d2876c87ff">find_last_of</a> (StringRef Chars, size_t From=npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the last character in the string that is in <span class="doxyComputerOutput">C</span>, or npos if not found. <a href="#aef1226ed87e22d9ca9bfd8d2876c87ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035cf6768564ead852edfff8ca9c3b6e">find_last_not_of</a> (char C, size_t From=npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the last character in the string that is not <span class="doxyComputerOutput">C</span>, or npos if not found. <a href="#a035cf6768564ead852edfff8ca9c3b6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819cd72313f82bda3742dc58f3862f20">find_last_not_of</a> (StringRef Chars, size_t From=npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the last character in the string that is not in <span class="doxyComputerOutput">Chars</span>, or npos if not found. <a href="#a819cd72313f82bda3742dc58f3862f20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a294111af6d4412163b209725ca556">contains</a> (StringRef Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given string is a substring of *this, and false otherwise. <a href="#a83a294111af6d4412163b209725ca556">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6a78cc34c1b0310fab4a21dd2fc02d">contains</a> (char C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given character is contained in *this, and false otherwise. <a href="#a9d6a78cc34c1b0310fab4a21dd2fc02d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a342b946b5a0944601f80994765e53feb">contains_insensitive</a> (StringRef Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given string is a substring of *this, and false otherwise. <a href="#a342b946b5a0944601f80994765e53feb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412577d3213b59a5da2b380f2feed9a9">contains_insensitive</a> (char C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given character is contained in *this, and false otherwise. <a href="#a412577d3213b59a5da2b380f2feed9a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Helpful Algorithms Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2c31b7b3c778d12aa176f9253511f37">count</a> (char C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of occurrences of <span class="doxyComputerOutput">C</span> in the string. <a href="#ac2c31b7b3c778d12aa176f9253511f37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797db79c8d98dcd992d5fe9a71ffe68c">count</a> (StringRef Str) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of non-overlapped occurrences of <span class="doxyComputerOutput">Str</span> in the string. <a href="#a797db79c8d98dcd992d5fe9a71ffe68c">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1881146f2dcc2ca57c9c5f77f938db9d">getAsInteger</a> (unsigned Radix, T &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the current string as an integer of the specified radix. <a href="#a1881146f2dcc2ca57c9c5f77f938db9d">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1643e7698ddbfd40fbd374a85f015846">consumeInteger</a> (unsigned Radix, T &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the current string as an integer of the specified radix. <a href="#a1643e7698ddbfd40fbd374a85f015846">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9c54d457a9ebc9d909c4b2234c7657">getAsInteger</a> (unsigned Radix, APInt &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the current string as an integer of the specified <span class="doxyComputerOutput">Radix</span>, or of an autosensed radix if the <span class="doxyComputerOutput">Radix</span> given is 0. <a href="#adc9c54d457a9ebc9d909c4b2234c7657">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8628d3c93731ec5ac11a4ca9dbc67dfb">consumeInteger</a> (unsigned Radix, APInt &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the current string as an integer of the specified <span class="doxyComputerOutput">Radix</span>. <a href="#a8628d3c93731ec5ac11a4ca9dbc67dfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23753c04a4ada14fc9c4891d30ed5cdc">getAsDouble</a> (double &amp;Result, bool AllowInexact=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the current string as an IEEE double-precision floating point value. <a href="#a23753c04a4ada14fc9c4891d30ed5cdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Substring Operations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f1fd81f2132805676c82ab8ae0c109">substr</a> (size_t Start, size_t N=npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the substring from [Start, Start + N). <a href="#a25f1fd81f2132805676c82ab8ae0c109">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa28286a33491b5d9a936fb6ae853baee">take_front</a> (size_t N=1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this' but with only the first <span class="doxyComputerOutput">N</span> elements remaining. <a href="#aa28286a33491b5d9a936fb6ae853baee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe565cb0cc832480a9a9ed312dc2962">take_back</a> (size_t N=1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this' but with only the last <span class="doxyComputerOutput">N</span> elements remaining. <a href="#a9fe565cb0cc832480a9a9ed312dc2962">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a27457ad5d68f631c788807c4ff52c">take_while</a> (function_ref&lt; bool(char)&gt; F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the longest prefix of 'this' such that every character in the prefix satisfies the given predicate. <a href="#a34a27457ad5d68f631c788807c4ff52c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa93bf2cc29b3a2ad5056bea30a373d52">take_until</a> (function_ref&lt; bool(char)&gt; F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the longest prefix of 'this' such that no character in the prefix satisfies the given predicate. <a href="#aa93bf2cc29b3a2ad5056bea30a373d52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fb2867a1e9fa36e135d9ee4dffb0167">drop_front</a> (size_t N=1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this' but with the first <span class="doxyComputerOutput">N</span> elements dropped. <a href="#a3fb2867a1e9fa36e135d9ee4dffb0167">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2705fd641fb3d1eefa2691b5117cf22">drop_back</a> (size_t N=1) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this' but with the last <span class="doxyComputerOutput">N</span> elements dropped. <a href="#ae2705fd641fb3d1eefa2691b5117cf22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb414d662ce914329570f0ff92602336">drop_while</a> (function_ref&lt; bool(char)&gt; F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this', but with all characters satisfying the given predicate dropped from the beginning of the string. <a href="#adb414d662ce914329570f0ff92602336">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53315344f92e70843fb54b6b7769de67">drop_until</a> (function_ref&lt; bool(char)&gt; F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this', but with all characters not satisfying the given predicate dropped from the beginning of the string. <a href="#a53315344f92e70843fb54b6b7769de67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a7fac667f8ae35285b8b53d9f2dd9dc">consume_front</a> (StringRef Prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> has the given prefix and removes that prefix. <a href="#a8a7fac667f8ae35285b8b53d9f2dd9dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae94101ab936805840acecc874e70c190">consume_front_insensitive</a> (StringRef Prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> has the given prefix, ignoring case, and removes that prefix. <a href="#ae94101ab936805840acecc874e70c190">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14180977794bfc2a37dbffeef3ca20de">consume_back</a> (StringRef Suffix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> has the given suffix and removes that suffix. <a href="#a14180977794bfc2a37dbffeef3ca20de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5fd848165f133bf149f8f27618ce313">consume_back_insensitive</a> (StringRef Suffix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> has the given suffix, ignoring case, and removes that suffix. <a href="#ac5fd848165f133bf149f8f27618ce313">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4c961b9b6f1da17df74b4496ecb30e">slice</a> (size_t Start, size_t End) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the substring from [Start, End). <a href="#a5d4c961b9b6f1da17df74b4496ecb30e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0320b2a5a6d440bf4479a02e78cf5ca7">split</a> (char Separator) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split into two substrings around the first occurrence of a separator character. <a href="#a0320b2a5a6d440bf4479a02e78cf5ca7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc1b9e00e08cff2c9beb3059efa4200">split</a> (StringRef Separator) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split into two substrings around the first occurrence of a separator string. <a href="#accc1b9e00e08cff2c9beb3059efa4200">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca46fb04897a97747c13d75a06f1215a">rsplit</a> (StringRef Separator) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split into two substrings around the last occurrence of a separator string. <a href="#aca46fb04897a97747c13d75a06f1215a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0284e4c41c0e09c0bc4767bc77a899d">split</a> (SmallVectorImpl&lt; StringRef &gt; &amp;A, StringRef Separator, int MaxSplit=-1, bool KeepEmpty=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split into substrings around the occurrences of a separator string. <a href="#af0284e4c41c0e09c0bc4767bc77a899d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0138ddc186a7cb5cfd04dde671220e">split</a> (SmallVectorImpl&lt; StringRef &gt; &amp;A, char Separator, int MaxSplit=-1, bool KeepEmpty=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split into substrings around the occurrences of a separator character. <a href="#a7b0138ddc186a7cb5cfd04dde671220e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc298d953d88e5a2d7c52a5c9cd2d36">rsplit</a> (char Separator) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split into two substrings around the last occurrence of a separator character. <a href="#a4bc298d953d88e5a2d7c52a5c9cd2d36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8265efd805e4ce0c9d3c18e78194324c">ltrim</a> (char Char) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return string with consecutive <span class="doxyComputerOutput">Char</span> characters starting from the the left removed. <a href="#a8265efd805e4ce0c9d3c18e78194324c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2e33f03956821cbf94c4cd5da01bdd">ltrim</a> (StringRef Chars=" \t\n\v\f\r") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return string with consecutive characters in <span class="doxyComputerOutput">Chars</span> starting from the left removed. <a href="#acd2e33f03956821cbf94c4cd5da01bdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b52404a8d2877d3b32ebb5d1f5c72ff">rtrim</a> (char Char) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return string with consecutive <span class="doxyComputerOutput">Char</span> characters starting from the right removed. <a href="#a9b52404a8d2877d3b32ebb5d1f5c72ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf544fca0b0f46e00e4261bc925104e5">rtrim</a> (StringRef Chars=" \t\n\v\f\r") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return string with consecutive characters in <span class="doxyComputerOutput">Chars</span> starting from the right removed. <a href="#acf544fca0b0f46e00e4261bc925104e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9990397f97b40d5d8564e000d00174a">trim</a> (char Char) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return string with consecutive <span class="doxyComputerOutput">Char</span> characters starting from the left and right removed. <a href="#ab9990397f97b40d5d8564e000d00174a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5126dde83d4cc3f8edaf6ac288b35e">trim</a> (StringRef Chars=" \t\n\v\f\r") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return string with consecutive characters in <span class="doxyComputerOutput">Chars</span> starting from the left and right removed. <a href="#a0c5126dde83d4cc3f8edaf6ac288b35e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9202ca0a40ca22c6198342cf8b0dc050">detectEOL</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Detect the line ending style of the string. <a href="#a9202ca0a40ca22c6198342cf8b0dc050">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> - Represent a constant reference to a string, i.e.</p>


<p>a character array and a length, which need not be null terminated.</p>


<p>This class does not own the string data, it is expected to be used in situations where the character data resides in some other buffer, whose lifetime extends past that of the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. For this reason, it is not in general safe to store a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a4c923dfa66a41094c8abcd145c7b0a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StringRef::const_iterator =  const char *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#a3029690daaf7b8559fc3102afc79f009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StringRef::const_reverse_iterator =  std::reverse_iterator&lt;const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

### iterator {#a20d37563688a61a452fb26e317e37308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StringRef::iterator =  const char *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

### reverse\_iterator {#a71dad3aa532ebd2a4f2eb1a686bafe3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StringRef::reverse_iterator =  std::reverse_iterator&lt;iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

### size\_type {#a54e59e2d53e5ee736ee060be7c457508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StringRef::size_type =  size_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

### value\_type {#ad4cb9ad24aa1c964a10403ca9d0f72a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StringRef::value_type =  char</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Data {#adb206dfcfc5a1d30e76b35f072728d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::StringRef::Data = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The start of the string, in an external buffer.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

### Length {#a15c2386bfb11c7292781ba82dc3094b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringRef::Length = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The length of the string.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### compareMemory() {#afba519c3188e4820e2f4d7542732e20f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::StringRef::compareMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Rhs, size_t Length)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### npos {#ad0f54a163ac500b144590640c6f1eb6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringRef::npos = ~size_t(0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#af4910906a25183ed3ea2984c5b423582">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameBefore</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ae337924e2723d7d8255011f1ac5624cf">llvm::FileCheckString::Check</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ac71c43fb658be4df9989f55be8447e1d">llvm::FileCheckString::CheckDag</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a95a7a7f317661b984c86d196fa44dff9">llvm::FileCheck::checkInput</a>, <a href="#a9d6a78cc34c1b0310fab4a21dd2fc02d">contains</a>, <a href="#a83a294111af6d4412163b209725ca556">contains</a>, <a href="#a412577d3213b59a5da2b380f2feed9a9">contains_insensitive</a>, <a href="#a342b946b5a0944601f80994765e53feb">contains_insensitive</a>, <a href="#a797db79c8d98dcd992d5fe9a71ffe68c">count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#afa70d6de13d68c2e91c3a845211bb49a">llvm::sys::fs::createTemporaryFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86-mc/#ae5725b4767b5ffa093fcf5c21fc2bb27">llvm::X86_MC::createX86MCSubtargetInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a36c152217dc69b5295561b2f99c52c17">llvm::omp::deconstructOpenMPKernelName</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-/#ae263aed138fcb0a6ceea9c9f29fcfb8d">llvm::symbolize::anonymous{Symbolize.cpp}::demanglePE32ExternCFunc</a>, <a href="#a9202ca0a40ca22c6198342cf8b0dc050">detectEOL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfyaml/#ac84f1cd7e37d227e700d6a69398fd3c1">llvm::ELFYAML::dropUniqueSuffix</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ad53613e81c10091896d73287938ab8be">llvm::object::Archive::ec_symbols</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a481e97810e8743a7c0f25a51dbcad8c1">llvm::ELFObjectWriter::executePostLayoutBinding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ad1056825d31bf187d0be430c51aac281">llvm::sys::path::extension</a>, <a href="#a82369bea2700347f68e1f43e30d2d47b">find</a>, <a href="#a18de63f444e95dfff81803a482ab6eec">find_first_not_of</a>, <a href="#af38cc29d28845d48d8423918d8910d12">find_first_of</a>, <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>, <a href="#a2fab98a15364352e9a7a48da307fde69">find_insensitive</a>, <a href="#a035cf6768564ead852edfff8ca9c3b6e">find_last_not_of</a>, <a href="#a819cd72313f82bda3742dc58f3862f20">find_last_not_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a4094843dd73069778eb645198365211c">llvm::SmallString&lt; 0 &gt;::find_last_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a3d61e42dd3a2c362b5b81e8a49e2db72">llvm::SmallString&lt; 0 &gt;::find_last_of</a>, <a href="#a7a7c222449f3208a532168c90bfb654d">find_last_of</a>, <a href="#aef1226ed87e22d9ca9bfd8d2876c87ff">find_last_of</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#aff3380c7e96d28b108876d8e7b66e341">llvm::SourceMgr::FindLocForLineAndColumn</a>, <a href="/web-llvm/docs/api/structs/llvm/format-provider-ecaa20ba3297bf1600b082fe1fca61e7/#a1e190076f44d99f68be134785ae5ad3b">llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_string_formatter&lt; T &gt;::value &gt; &gt;::format</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/sourcecode/#a456ba3a13dcf71ee2ef0384ea0d14989">llvm::symbolize::SourceCode::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a115dd532d6538ed40f42a625343126cc">llvm::ARM::getCanonicalArchName</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a37b7e51dcb0e1efd0a84eb6398fd6301">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a3b587fe584a4e8b02c4ca0426be42918">llvm::DataExtractor::getCStrRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84d9944c268bb7f382490a5507cb6e07">llvm::getFirstValueProfRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a3455f56c4a28156282d4f5cd6265e034">llvm::sys::detail::getHostCPUNameForS390x</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a494d75fe0bc43f9c6b8821f983205649">llvm::SourceMgr::getLineAndColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a940c0b94e9bb9dfdb69961d456b47b60">llvm::object::ArchiveMemberHeader::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac52de24a1dd7695de94261e6ab8bb457">llvm::getObjCNamesIfSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a990a2cc1b018140f8dde6e1a8ad42182">llvm::object::ArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a7bcc5393fb38f7a3fbe2c156abc4e92a">llvm::detail::getTypeNameImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f4f18351f3d6e0d72c55116a8a6ff84">llvm::getValueProfDataSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#af3e1bca92860141baaad0a536334d09f">llvm::object::MachOObjectFile::guessLibraryShortName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38c590804b713ea0d02a8fb5b8fb6f30">llvm::isArm64ECMangledFunctionName</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#aaa821cfa27ddeb5cc419a88fa79804b2">llvm::Regex::isLiteralERE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6abe01777169c2216339a59d84bf3999">llvm::yaml::isNumeric</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a88d6a2d221777b8376bde5d860a219d1">llvm::isSpecialPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a23cdde8b9bdd40fd4a93d3635ca77dc6">llvm::Pattern::match</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/path/reverse-iterator/#a6dc88450dbd179d88fc0b3c9e8fdbda4">llvm::sys::path::reverse_iterator::operator++</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a336063ab4c85ca7260327f7c39a64492">llvm::SPIRV::parseBuiltinTypeStr</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a2407bfb7839e9f051cd446d587f978be">llvm::sys::printArg</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3331028c9eef66f4022ac3efa310af7d">llvm::Pattern::printFuzzyMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a1cbc5251f13ad42510760ed61c71e874">llvm::BinaryStreamReader::readCString</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a03907c7df68a93c377bf90c5bdd78ca3">llvm::sys::path::remove_filename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a4a9c60caa200d23d5e4f12b24d4c8877">llvm::object::replace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1feb0e6007474c599ccfed65dad667c0">llvm::sys::path::replace_extension</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a80b83aa3cd0b6442a32176b58205d98f">llvm::SmallString&lt; 0 &gt;::rfind</a>, <a href="#a97d45ce069c1a09ca84672df63acf096">rfind</a>, <a href="#aba4f98b846a8b05965f39ca3a5c33fd2">rfind_insensitive</a>, <a href="#a56e7e0bebc570bc6814cdefd1f2ecda3">rfind_insensitive</a>, <a href="#aca46fb04897a97747c13d75a06f1215a">rsplit</a>, <a href="#a7b0138ddc186a7cb5cfd04dde671220e">split</a>, <a href="#af0284e4c41c0e09c0bc4767bc77a899d">split</a>, <a href="#accc1b9e00e08cff2c9beb3059efa4200">split</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1d074d016ff4ab25b0d504bf70a89059">llvm::sys::path::stem</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#abab69c8e9372f6a5283db4a059b8d5a0">llvm::SmallString&lt; 0 &gt;::substr</a>, <a href="#a25f1fd81f2132805676c82ab8ae0c109">substr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#af831b7a399b717b9e5abb030a258a6a4">llvm::ifs::terminatedSubstr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7d22c115f5634f10ef137c93c762ebca">llvm::UpgradeDataLayoutString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Constructors

### StringRef {#a95fff1cbaf3b1b5b51870a60df57a6e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef::StringRef ()</td>
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

<p>Construct an empty string ref.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Referenced by <a href="#ae0c6424784f132b91eb387a3ee0b57c9">compare</a>, <a href="#ae9c79bda245d64ef5df420f94ec4bbd1">compare_insensitive</a>, <a href="#a8a3989cbad7cca2a86cb7d3a0627748b">compare_numeric</a>, <a href="#a14180977794bfc2a37dbffeef3ca20de">consume_back</a>, <a href="#ac5fd848165f133bf149f8f27618ce313">consume_back_insensitive</a>, <a href="#a8a7fac667f8ae35285b8b53d9f2dd9dc">consume_front</a>, <a href="#ae94101ab936805840acecc874e70c190">consume_front_insensitive</a>, <a href="#a8628d3c93731ec5ac11a4ca9dbc67dfb">consumeInteger</a>, <a href="#a83a294111af6d4412163b209725ca556">contains</a>, <a href="#a342b946b5a0944601f80994765e53feb">contains_insensitive</a>, <a href="#ac66731b70af2ad5aded1ce13a20acb29">copy</a>, <a href="#a797db79c8d98dcd992d5fe9a71ffe68c">count</a>, <a href="#a9202ca0a40ca22c6198342cf8b0dc050">detectEOL</a>, <a href="#ae2705fd641fb3d1eefa2691b5117cf22">drop_back</a>, <a href="#a3fb2867a1e9fa36e135d9ee4dffb0167">drop_front</a>, <a href="#a53315344f92e70843fb54b6b7769de67">drop_until</a>, <a href="#adb414d662ce914329570f0ff92602336">drop_while</a>, <a href="#aee1ef526cd95ea3036b0569aabacc1c9">edit_distance_insensitive</a>, <a href="#aca439bf65258d9d8d057812938b617c5">ends_with</a>, <a href="#ae57b9ee061903472c1cc9082849ed34e">ends_with_insensitive</a>, <a href="#ae46058c90a3c703357331a6501b32f1c">equals_insensitive</a>, <a href="#a82369bea2700347f68e1f43e30d2d47b">find</a>, <a href="#a18de63f444e95dfff81803a482ab6eec">find_first_not_of</a>, <a href="#af38cc29d28845d48d8423918d8910d12">find_first_of</a>, <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>, <a href="#a2fab98a15364352e9a7a48da307fde69">find_insensitive</a>, <a href="#a819cd72313f82bda3742dc58f3862f20">find_last_not_of</a>, <a href="#aef1226ed87e22d9ca9bfd8d2876c87ff">find_last_of</a>, <a href="#adc9c54d457a9ebc9d909c4b2234c7657">getAsInteger</a>, <a href="#a8265efd805e4ce0c9d3c18e78194324c">ltrim</a>, <a href="#acd2e33f03956821cbf94c4cd5da01bdd">ltrim</a>, <a href="#af90e5d9d8d99f68f9d4616bd026b0eab">rfind</a>, <a href="#a56e7e0bebc570bc6814cdefd1f2ecda3">rfind_insensitive</a>, <a href="#a4bc298d953d88e5a2d7c52a5c9cd2d36">rsplit</a>, <a href="#aca46fb04897a97747c13d75a06f1215a">rsplit</a>, <a href="#a9b52404a8d2877d3b32ebb5d1f5c72ff">rtrim</a>, <a href="#acf544fca0b0f46e00e4261bc925104e5">rtrim</a>, <a href="#a5d4c961b9b6f1da17df74b4496ecb30e">slice</a>, <a href="#a0320b2a5a6d440bf4479a02e78cf5ca7">split</a>, <a href="#a7b0138ddc186a7cb5cfd04dde671220e">split</a>, <a href="#af0284e4c41c0e09c0bc4767bc77a899d">split</a>, <a href="#accc1b9e00e08cff2c9beb3059efa4200">split</a>, <a href="#a2cd8968ff703aaeb395dcd63f6805ff1">starts_with</a>, <a href="#a343b6c58108519aca196bb54b1d1a6ef">starts_with_insensitive</a>, <a href="#a25f1fd81f2132805676c82ab8ae0c109">substr</a>, <a href="#a9fe565cb0cc832480a9a9ed312dc2962">take_back</a>, <a href="#aa28286a33491b5d9a936fb6ae853baee">take_front</a>, <a href="#aa93bf2cc29b3a2ad5056bea30a373d52">take_until</a>, <a href="#a34a27457ad5d68f631c788807c4ff52c">take_while</a>, <a href="#ab9990397f97b40d5d8564e000d00174a">trim</a> and <a href="#a0c5126dde83d4cc3f8edaf6ac288b35e">trim</a>.</p>

</div>
</div>

### StringRef {#a9dd5c8e50b79ad7ad01c11b63113e1b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef::StringRef (std::nullptr_t)</td>
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

<p>Disable conversion from nullptr.</p>


<p>This prevents things like if (S == nullptr)</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

</div>
</div>

### StringRef {#a9bc1c70c28eb2f5a53ad0dcac4c56b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef::StringRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *Str LLVM_LIFETIME_BOUND)</td>
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

<p>Construct a string ref from a cstring.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aac3d0ea99ec07497e1d0fd0cdfc18040">LLVM_LIFETIME_BOUND</a>.</p>

</div>
</div>

### StringRef {#a70392c6eca2623b798f965f66db768df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef::StringRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a> LLVM_LIFETIME_BOUND, size_t length)</td>
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

<p>Construct a string ref from a pointer and length.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aac3d0ea99ec07497e1d0fd0cdfc18040">LLVM_LIFETIME_BOUND</a>.</p>

</div>
</div>

### StringRef {#aebcb6e1997e871ac41f506eff6bdc051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef::StringRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Str)</td>
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

<p>Construct a string ref from an std::string.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Reference <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>.</p>

</div>
</div>

### StringRef {#af7220b1d3bfd1095940206fa563fdb1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef::StringRef (std::string_view Str)</td>
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

<p>Construct a string ref from an std::string_view.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a> and <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Iterators

### begin {#a46f643f1eb1939362c7dd79361bcbd0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::StringRef::begin ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1b070d2edba351e90bf5a08b656895a5">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#aa6b5121c08e5d0f73aa31df414038205">llvm::MDString::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#a85f1cad503bb4c8ac78b28b75832d5b8">llvm::yaml::BlockScalarNode::BlockScalarNode</a>, <a href="#adbc826dc76fd535f887e035d1795aa84">bytes_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/djb-cpp/#af60bf47ef264d1d6c10fea7a1dd7da9f">chopOneUTF32</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a74d9194822bc4e6c84bc71a8ea89db5c">llvm::detail::IEEEFloat::convertFromString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad23b52a299ca563f6e6a6c6cece54dcc">llvm::convertUTF8ToUTF16String</a>, <a href="#ac66731b70af2ad5aded1ce13a20acb29">copy</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab9178a079b54667289f598db5b052ade">llvm::APInt::getBitsNeeded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a506b97a4c93510ccce514cef204be19d">llvm::sys::detail::getHostCPUNameForPowerPC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp/#a9a22b7220c3b5b3b0a05ab7070c8e5ff">getHostID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#aaccb27d091e3f4899c01d6ebc1100967">llvm::object::Archive::Symbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a1e8893b8d88f459187356143661b34a3">llvm::object::Archive::getNumberOfSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#ada5c91ffe6ce1366ef81b5cfea3c59fc">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ac842bb87a969bf50f9a262be16a40d5b">llvm::object::COFFObjectFile::getRelocationTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad4f7324b39a6386811a1d2202cfe1fed">llvm::object::MachOObjectFile::getRelocationTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a6902b7a4807f72288afd6e2c9bbbb721">llvm::object::WasmObjectFile::getRelocationTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a181019615fec687b5203ba7489f65613">llvm::object::XCOFFObjectFile::getRelocationTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a866133bf888d0b8bbce2275845511edb">llvm::TargetLoweringObjectFile::getSymbolWithGlobalValueBase</a>, <a href="/web-llvm/docs/api/classes/llvm/textinstrprofreader/#a54ea33c903b163ee020c34e36d6849c9">llvm::TextInstrProfReader::hasFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d8b4a359e2900fdd4626a9fcdaebc44">llvm::hash_value</a>, <a href="/web-llvm/docs/api/classes/llvm/timer/#ae240a4a86389f8fe3461e34255b971c4">llvm::Timer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/object/directx/signature/#a8f7cfbb475d2b81f3b1c99bb5e74e53d">llvm::object::DirectX::Signature::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/namedstreammap/#a1f4507809faf33bf017aeb193cf9d617">llvm::pdb::NamedStreamMap::load</a>, <a href="#abb1344e353958db14e66ec7ab574001a">lower</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/#a66ced5c57cafe11823df6917a866b17f">llvm::object::MachOUniversalBinary::MachOUniversalBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>, <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem/#ad093e9036111f8dae17691a756eae14f">anonymous{MemoryBuffer.cpp}::MemoryBufferMem&lt; MB &gt;::MemoryBufferMem</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#aaebf85b8ceed858f6323120dc8e3e058">llvm::SmallString&lt; 0 &gt;::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a1b0a7624e9e8209f9bef0f5e227b6eaf">llvm::object::Archive::Child::operator==</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp/#af6e9ec4d94b9ce3ac8849a43fc579aaf">parseMaybeMangledName</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/dxcontainer-cpp/#abc63df5c2aad9dab94dc1eeaa7ca4b57">readInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/dxcontainer-cpp/#aa9e5fb5670969ca81a373909d83d51ae">readStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#ab9cbc0396671b685858c523ed763e724">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::reconstituteName</a>, <a href="#af6d06fee60cfd116e8c2a4baee25a929">rend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1feb0e6007474c599ccfed65dad667c0">llvm::sys::path::replace_extension</a>, <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer/#af4da15ad7c70b2c9ac934adf213819f7">llvm::RewriteBuffer::ReplaceText</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode/#a8cd838d3dcf1efd1367cbed9a0f8a69b">llvm::yaml::ScalarNode::ScalarNode</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a33b972eb34932750dfec21f44f358398">llvm::EngineBuilder::setMArch</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#abeb3f9f8b01e92ccf434c556cdb5afd0">llvm::EngineBuilder::setMCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a29867e6cdcf4cc5c4f0170e34f262ec2">llvm::TimerGroup::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a263bac5d85adb87956f47116b8fd5b2a">llvm::sys::unicode::startsWith</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a03e47f68ebb90174f21f2ab9b95d3d28">llvm::object::Archive::symbol_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a36314b2982eff94abe0b78ad9c97f53f">updateLoadCommandPayloadString</a> and <a href="#a4c884ed90d5d38e5d0546d61c4bebe3e">upper</a>.</p>

</div>
</div>

### bytes {#a21fde218101d7b15d7e4edddd5b8b0a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const unsigned char * &gt; llvm::StringRef::bytes ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#adbc826dc76fd535f887e035d1795aa84">bytes_begin</a>, <a href="#a25ba44ae8e92a80fde434e1ab19994cc">bytes_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aba816fb56fad484d9cd712825dcacaa6">llvm::djbHash</a>.</p>

</div>
</div>

### bytes\_begin {#adbc826dc76fd535f887e035d1795aa84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char * llvm::StringRef::bytes_begin ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Reference <a href="#a46f643f1eb1939362c7dd79361bcbd0e">begin</a>.</p>


<p>Referenced by <a href="#a21fde218101d7b15d7e4edddd5b8b0a8">bytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#a2a4ff2bbf405d8d803f239b15c88b2dd">llvm::MDString::bytes_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp/#a39d3991edccf18f18b801032e9ab89b5">loadObj</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad73613c8e8495c4d7e3aaf2da575f2e2">llvm::readAndDecodeStrings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobjectsection/#a33c62d0d0c29c96b7b48d9e416d655e8">llvm::orc::ELFDebugObjectSection&lt; ELFT &gt;::validateInBounds</a> and <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a78b45ebf4772364c848d6aedf38fd199">llvm::object::WasmObjectFile::WasmObjectFile</a>.</p>

</div>
</div>

### bytes\_end {#a25ba44ae8e92a80fde434e1ab19994cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char * llvm::StringRef::bytes_end ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Reference <a href="#a996c7ca3dd6843ba5d55a7c217770270">end</a>.</p>


<p>Referenced by <a href="#a21fde218101d7b15d7e4edddd5b8b0a8">bytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#aa3641bf7a7d81855bc0518f1f102bc01">llvm::MDString::bytes_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a8e0db63318e9923b354d95e0391c05db">llvm::object::ELFFile&lt; ELFT &gt;::getDynSymtabSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp/#a39d3991edccf18f18b801032e9ab89b5">loadObj</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad73613c8e8495c4d7e3aaf2da575f2e2">llvm::readAndDecodeStrings</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobjectsection/#a33c62d0d0c29c96b7b48d9e416d655e8">llvm::orc::ELFDebugObjectSection&lt; ELFT &gt;::validateInBounds</a>.</p>

</div>
</div>

### end {#a996c7ca3dd6843ba5d55a7c217770270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::StringRef::end ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1b070d2edba351e90bf5a08b656895a5">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#a85f1cad503bb4c8ac78b28b75832d5b8">llvm::yaml::BlockScalarNode::BlockScalarNode</a>, <a href="#a25ba44ae8e92a80fde434e1ab19994cc">bytes_end</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a36305f86aafd6d41b0c449eac6476efd">llvm::FileCheckString::CheckNext</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a82944774d532e6adc41c92e29a00e2e9">llvm::FileCheckString::CheckSame</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/djb-cpp/#af60bf47ef264d1d6c10fea7a1dd7da9f">chopOneUTF32</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad23b52a299ca563f6e6a6c6cece54dcc">llvm::convertUTF8ToUTF16String</a>, <a href="#ac66731b70af2ad5aded1ce13a20acb29">copy</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#afc7d9f82fb18fa4d24ef3667e89e9e6d">llvm::MDString::end</a>, <a href="#aca439bf65258d9d8d057812938b617c5">ends_with</a>, <a href="#ae57b9ee061903472c1cc9082849ed34e">ends_with_insensitive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a506b97a4c93510ccce514cef204be19d">llvm::sys::detail::getHostCPUNameForPowerPC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp/#a9a22b7220c3b5b3b0a05ab7070c8e5ff">getHostID</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ada8e7ae873a0bd17132af43d3a128f8e">getLoadCommandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#ada5c91ffe6ce1366ef81b5cfea3c59fc">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ac842bb87a969bf50f9a262be16a40d5b">llvm::object::COFFObjectFile::getRelocationTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad4f7324b39a6386811a1d2202cfe1fed">llvm::object::MachOObjectFile::getRelocationTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a6902b7a4807f72288afd6e2c9bbbb721">llvm::object::WasmObjectFile::getRelocationTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a181019615fec687b5203ba7489f65613">llvm::object::XCOFFObjectFile::getRelocationTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a866133bf888d0b8bbce2275845511edb">llvm::TargetLoweringObjectFile::getSymbolWithGlobalValueBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d8b4a359e2900fdd4626a9fcdaebc44">llvm::hash_value</a>, <a href="/web-llvm/docs/api/classes/llvm/timer/#ae240a4a86389f8fe3461e34255b971c4">llvm::Timer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/namedstreammap/#a1f4507809faf33bf017aeb193cf9d617">llvm::pdb::NamedStreamMap::load</a>, <a href="#abb1344e353958db14e66ec7ab574001a">lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>, <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem/#ad093e9036111f8dae17691a756eae14f">anonymous{MemoryBuffer.cpp}::MemoryBufferMem&lt; MB &gt;::MemoryBufferMem</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp/#af6e9ec4d94b9ce3ac8849a43fc579aaf">parseMaybeMangledName</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#ad81a87b3f8bbc548c08e343f068aab79">parseRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad5d1fdc8afad445839bca3e15c7ba4bc">parseRegisterNumber</a>, <a href="#a69857be962bd85fe67eb0fb74578c059">rbegin</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/dxcontainer-cpp/#abc63df5c2aad9dab94dc1eeaa7ca4b57">readInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/dxcontainer-cpp/#aa9e5fb5670969ca81a373909d83d51ae">readStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#ab9cbc0396671b685858c523ed763e724">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::reconstituteName</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a80318325208303662f9f20af3a28b1d7">llvm::Regex::Regex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1feb0e6007474c599ccfed65dad667c0">llvm::sys::path::replace_extension</a>, <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer/#af4da15ad7c70b2c9ac934adf213819f7">llvm::RewriteBuffer::ReplaceText</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode/#a8cd838d3dcf1efd1367cbed9a0f8a69b">llvm::yaml::ScalarNode::ScalarNode</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a33b972eb34932750dfec21f44f358398">llvm::EngineBuilder::setMArch</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#abeb3f9f8b01e92ccf434c556cdb5afd0">llvm::EngineBuilder::setMCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a29867e6cdcf4cc5c4f0170e34f262ec2">llvm::TimerGroup::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a263bac5d85adb87956f47116b8fd5b2a">llvm::sys::unicode::startsWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a36314b2982eff94abe0b78ad9c97f53f">updateLoadCommandPayloadString</a> and <a href="#a4c884ed90d5d38e5d0546d61c4bebe3e">upper</a>.</p>

</div>
</div>

### rbegin {#a69857be962bd85fe67eb0fb74578c059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::StringRef::rbegin ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Reference <a href="#a996c7ca3dd6843ba5d55a7c217770270">end</a>.</p>

</div>
</div>

### rend {#af6d06fee60cfd116e8c2a4baee25a929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::StringRef::rend ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Reference <a href="#a46f643f1eb1939362c7dd79361bcbd0e">begin</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## String Operations

### back {#a5b6faabb08339ea1dd11e9d37a668634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::StringRef::back ()</td>
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

<p>back - Get the last character in the string.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="#a2dc80c585ad5882da8cae7b5968f7e74">empty</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5e419b9328977a480fda42c789b77237">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::addExplicitComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfyaml/#ac84f1cd7e37d227e700d6a69398fd3c1">llvm::ELFYAML::dropUniqueSuffix</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ab07e49a5499032dc8f97198892218853">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::EmitCommentsAndEOL</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a161ac460fefc16f98a8dd1a9f019af9a">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitInstruction</a>, <a href="#a393bbf5d4d82eaebfc257042c3a82ece">ends_with</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac52de24a1dd7695de94261e6ab8bb457">llvm::getObjCNamesIfSelector</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a299e5debf3d108b71fc6642ecd31e5e7">llvm::SparcTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a358c1febb02bfec774608e4761b27495">handleCompressedSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a92b68a49e0ce87d4d52c24f060af0502">llvm::yaml::needsQuotes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportentry/#a72daf5129c62d88c70c12dc1b625de1a">llvm::object::ExportEntry::otherName</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/jsonwriter/#a1b1532a2254d760451e96bf7b299943b">anonymous{VirtualFileSystem.cpp}::JSONWriter::write</a>.</p>

</div>
</div>

### compare {#ae0c6424784f132b91eb387a3ee0b57c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::StringRef::compare (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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

<p>compare - Compare two strings; the result is negative, zero, or positive if this string is lexicographically less than, equal to, or greater than the <span class="doxyComputerOutput">RHS</span>.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributeimpl/#a09dae4090576d1532ff1c430cacf0419">llvm::AttributeImpl::cmp</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ab92cd5fe523c73c94aafcd295688606c">llvm::SmallString&lt; 0 &gt;::compare</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ad9ef9dbac3fbf9cc30e63d86bf9d7e34">compareNames</a>.</p>

</div>
</div>

### compare\_insensitive {#ae9c79bda245d64ef5df420f94ec4bbd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int StringRef::compare_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare two strings, ignoring case.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp/#a554122103a690fc7cdc6f99923dce8be">ascii_strncasecmp</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac66bfad9caed191bc784a03cf248ef0c">llvm::SmallString&lt; 0 &gt;::compare_insensitive</a>, <a href="#ae46058c90a3c703357331a6501b32f1c">equals_insensitive</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#abdaa8ae9b3e01099946066f89a8e10ad">anonymous{AsmParser.cpp}::AsmParser::parseRealValue</a> and <a href="/web-llvm/docs/api/classes/llvm/detectroundchange/#a23677a404e91b3491d158fb8b0ea3f49">llvm::DetectRoundChange::runOnMachineFunction</a>.</p>

</div>
</div>

### compare\_numeric {#a8a3989cbad7cca2a86cb7d3a0627748b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int StringRef::compare_numeric (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>compare_numeric - Compare two strings, treating sequences of digits as numbers.</p>


<p>compare_numeric - Compare strings, handle embedded numbers.</p>


<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a12d4f37888b638bcbd9fc0201492c776">isDigit</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ab5dc6cbb11edaab17e562193d8ab71ac">llvm::SmallString&lt; 0 &gt;::compare_numeric</a> and <a href="/web-llvm/docs/api/structs/llvm/lessrecord/#a8f202ce2b8d3b6f352f46ea76da83179">llvm::LessRecord::operator()</a>.</p>

</div>
</div>

### copy {#ac66731b70af2ad5aded1ce13a20acb29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Allocator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::copy (<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a> &amp; A)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a>, <a href="#a46f643f1eb1939362c7dd79361bcbd0e">begin</a>, <a href="#a2dc80c585ad5882da8cae7b5968f7e74">empty</a>, <a href="#a996c7ca3dd6843ba5d55a7c217770270">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/document/#a195e6cd6c71f2fabbd3d99a61627abee">llvm::yaml::Document::parseBlockNode</a>.</p>

</div>
</div>

### data {#a7b0fa1a82461032cdf16b7f6c59f0a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::StringRef::data ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>data - Get a pointer to the start of the string (which may not be null terminated).</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1accb391b511ed37f3b8b88f773f09c">llvm::msgpack::Document::addString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a78deffb09f38652d08cb57cce3119fc7">annotateAllFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a59a90ba7dd76e41d07e6c1cb792e0db3">appendGlobalSymbolTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>, <a href="/web-llvm/docs/api/classes/llvm/cachedhashstring/#a2e1c9187ee4bfb22d0e1de02e3a22ade">llvm::CachedHashString::CachedHashString</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ac71c43fb658be4df9989f55be8447e1d">llvm::FileCheckString::CheckDag</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a36305f86aafd6d41b0c449eac6476efd">llvm::FileCheckString::CheckNext</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a82944774d532e6adc41c92e29a00e2e9">llvm::FileCheckString::CheckSame</a>, <a href="#ae9c79bda245d64ef5df420f94ec4bbd1">compare_insensitive</a>, <a href="#a8a3989cbad7cca2a86cb7d3a0627748b">compare_numeric</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-cpp/#a9d36087a89aca95c0df3141528c1dc2a">constructSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#afc82faca788f75fcf0a8f60a406342ba">constructSymbolEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#afdcc3a66137dcf1fb3dbdc7adaedc26c">llvm::objcopy::coff::createGnuDebugLinkSectionContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4fbdc8f1be1bfc357861f63756755f65">llvm::jitlink::createLinkGraphFromELFObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af194271b77c030b86d1f22f523e7f048">createMemberHeaderParseError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9ec3732ab208437ca6ee8e13438bd0e8">llvm::MachO::createRegexFromGlob</a>, <a href="/web-llvm/docs/api/classes/llvm/object/anonymous-coffimportfile-cpp-/objectfactory/#a0194b0cf6c8e570555fe9a8eb0c8d167">llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::createShortImport</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugpubtable/#a2d35cbb8144f97cd0811de3487719084">llvm::DWARFDebugPubTable::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#aaa38af193e8749bb5d9b945b405e933e">llvm::DWARFDebugLoclists::dumpRawEntry</a>, <a href="#a51c1f447b5d754191564ae340ee4253b">edit_distance</a>, <a href="#aee1ef526cd95ea3036b0569aabacc1c9">edit_distance_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#ac7a72ed69b91577b81089ff1a7a57197">llvm::BitstreamWriter::emitBlob</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a81600054c53c8bfe10547514c330a547">llvm::DWARFYAML::emitDebugAbbrev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#a95b9cd710db1ece98dc23d86c22bdb5b">anonymous{DWARFEmitter.cpp}::emitDebugNamesHeader</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a6c61c3e648797ee04fda231739eedfa2">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::emitFDE</a>, <a href="#aca439bf65258d9d8d057812938b617c5">ends_with</a>, <a href="#ae57b9ee061903472c1cc9082849ed34e">ends_with_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a8be5b89e05ade5c6e5a08c6351b9821a">llvm::cl::Option::error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttype/#a5ce06b7e3524ccb5cde055c3cf596b10">llvm::DWARFListType&lt; ListEntryType &gt;::extract</a>, <a href="#a82369bea2700347f68e1f43e30d2d47b">find</a>, <a href="#a18de63f444e95dfff81803a482ab6eec">find_first_not_of</a>, <a href="#af38cc29d28845d48d8423918d8910d12">find_first_of</a>, <a href="#a035cf6768564ead852edfff8ca9c3b6e">find_last_not_of</a>, <a href="#a819cd72313f82bda3742dc58f3862f20">find_last_not_of</a>, <a href="#aef1226ed87e22d9ca9bfd8d2876c87ff">find_last_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#ab64ede9b347ffd8eb32ed5e05f2520f4">llvm::json::fixUTF8</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a7c59308f5da9f18a578d5dfaed1285a1">llvm::RuntimeDyldCOFFAArch64::generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#ae5595d78c0d45afeec52fccb70b1b209">llvm::RuntimeDyldCOFFX86_64::generateRelocationStub</a>, <a href="/web-llvm/docs/api/classes/llvm/errordiagnostic/#aef72f56d78c257c18bf803045c76eb19">llvm::ErrorDiagnostic::get</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/range/#ad762c8eda87b703a744cf68551b252b8">llvm::irsymtab::storage::Range&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/str/#a02a37f04a82457e3c3658f3f1c046e0f">llvm::irsymtab::storage::Str::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a98013dfe461d03c79996aa701959af99">llvm::DataExtractor::getCStr</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a17638a9e9146a6f6feef1adb50c53d2b">llvm::DataExtractor::getCStr</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a83adaf6fa27a4eb8cd83ab05b0e7908b">llvm::LTOModule::getDependentLibrary</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/srecord/#a8a3e8a37182f3d235fba5f02768ce39a">llvm::objcopy::elf::SRecord::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d440404da44b3480e71ac2793976daf">llvm::HexagonInstrInfo::getInlineAsmLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a6e4cc243fb344193485e9e4fe79399c7">llvm::dwarf_linker::parallel::SectionDescriptor::getIntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxregisterinfo/#a11f68a471f467af9babb2ba236bcf1d9">llvm::NVPTXRegisterInfo::getName</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-sym-impl/#aaba364194724cae8698514b1a4a09f29">llvm::object::Elf_Sym_Impl&lt; ELFT &gt;::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#afdea79cf3204fe335d9ebceb78e6a778">getNextLoadCommandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a33efdfc01aaf654147da9f8c05f7706d">llvm::opt::ArgList::GetOrMakeJoinedArgString</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#add923d3128dce4cad95ce5ad642f6946">llvm::PPCTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a299e5debf3d108b71fc6642ecd31e5e7">llvm::SparcTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a1b21b0b6b92569afb3b677c440ecb3b6">llvm::object::ELFFile&lt; ELFT &gt;::getSectionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a6d7f36df9f1e78161aa1117443ec74e1">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/gsistreambuilder-cpp/#ad8de58e5ee26f7e8a2a509355b0156f4">gsiRecordCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0e06d133446b7cfbee6b1800f3d993f7">llvm::dwarf_linker::guessDeveloperDir</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a068e377306e2029f1a5e24504c1f9cb7">isAsmComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a385765e73480a0f2d49dcc84a8fb70da">llvm::json::isUTF8</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga515bb8a9dede000b935e77958f35a4cf">LLVMGetDebugLocDirectory</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga46f93df14e032eacb6cc772e0a9a03ed">LLVMGetDebugLocFilename</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga638cf10ec868576e2a3be5a17d0ae39b">LLVMGetNamedMetadataName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ae071c2a56ff28186d5476e562811b2f7">lookupLLVMIntrinsicByName</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a76df0b752eddd8b0711d1af16a3658ad">llvm::LegalizerHelper::lowerReadWriteRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a33db5e22d2f3b0403b2fcd906f5a2377">llvm::remarks::magicToFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a23cdde8b9bdd40fd4a93d3635ca77dc6">llvm::Pattern::match</a>, <a href="/web-llvm/docs/api/structs/prefixmatcher/#a06d7229c302f7f9a6e42ad1afdc957c9">PrefixMatcher::match</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a1b51573bc0b0e62d37537759a24a44c3">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyFreeingObject</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6c80295c5037fd265a600ae769440d39">llvm::remarks::parseFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a4df79ca87cfad6de8aad81df9f474540">llvm::remarks::parseHotnessThresholdOption</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5c3abd5a0df4ec19738884622846a92b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp/#af6e9ec4d94b9ce3ac8849a43fc579aaf">parseMaybeMangledName</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#ad81a87b3f8bbc548c08e343f068aab79">parseRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a307619afda1e993b5ab00f907fb103b9">parseStrTab</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a7f3ee08c28f1f56632e9b58a7e90a813">parseStrTabSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a28f2b75ae3485678ba907fd613f90317">parseV2DirFileTables</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a8eb3d9b91beb14411cbb1c3957c5cd49">parseVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aaffdb3054263427a7df8fdac667a0c5b">parseWholeProgramDevirtResolution</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a59aaa2e922d6173cbeaed43a2d58423a">llvm::X86Operand::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#aa386d2cd704c6f1176a5aef1f0f178da">ProcessMatchResult</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/#a7d852659ea6c0a8e12cf0c8d5e8d2e16">llvm::irsymtab::readBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a10b27eac23635b8f40370fe8a4d19967">readCoverageMappingData</a>, <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader/#a7e1679b2628896a1b7e2299c92776503">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readFunctionRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad3d743b368af90b99cf44ff63052c0b2">llvm::jitlink::readTargetMachineArch</a>, <a href="/web-llvm/docs/api/structs/llvm/lessrecordregister/recordparts/#ab6f58b67225aaf63ec2aeee94dd053f4">llvm::LessRecordRegister::RecordParts::RecordParts</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a80318325208303662f9f20af3a28b1d7">llvm::Regex::Regex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66fc8969d714a36fb8b4918753d1b973">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#aecb8af888c92e0b415ae5021d9c7a59a">reportError</a>, <a href="#aba4f98b846a8b05965f39ca3a5c33fd2">rfind_insensitive</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86returnthunks-cpp-/x86returnthunks/#ab4a10d58e295ec66ff8c9c1d3eeb0529">anonymous{X86ReturnThunks.cpp}::X86ReturnThunks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/stringsaver/#aab5ad8c5b3081716904f28dbb1979daf">llvm::StringSaver::save</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section/#aa23e563fc1b4cb6192ce8ea87e0154df">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Section</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/segment/#a483c24f3e678c049cf305bc40281fb08">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Segment</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-df914a78aa74437406828e15b40ba1b2/#a37399dc7cab3f63caf490b1a59fdc832">llvm::orc::shared::SPSSerializationTraits&lt; SPSString, StringRef &gt;::serialize</a>, <a href="#a343b6c58108519aca196bb54b1d1a6ef">starts_with_insensitive</a>, <a href="#a70392c6eca2623b798f965f66db768df">StringRef</a>, <a href="#aebcb6e1997e871ac41f506eff6bdc051">StringRef</a>, <a href="#af7220b1d3bfd1095940206fa563fdb1f">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aff28c3d477d3a7870ec643381f186ed4">llvm::cl::TokenizeGNUCommandLine</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a66ab4e2404f4eed28fd60cc29a7053c2">llvm::Twine::Twine</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#aba6d9549c0ddfa25919915044a81eaf3">llvm::Twine::Twine</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeserver2record/#af76800ba0d52842f185566beebef5be2">llvm::codeview::TypeServer2Record::TypeServer2Record</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-xcoffemitter-cpp-/#a85a0cac85a17a54339c7d5f78ae8d608">anonymous{XCOFFEmitter.cpp}::writeName</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovprofiler/#a5f0fe7fdf331104cd569220040c1cc79">anonymous{GCOVProfiling.cpp}::GCOVProfiler::writeString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ace523ea68fd49787987759de81452913">llvm::yaml::yaml2archive</a>.</p>

</div>
</div>

### edit\_distance {#a51c1f447b5d754191564ae340ee4253b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef::edit_distance (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Other, bool AllowReplacements=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, unsigned MaxEditDistance=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the edit distance between this string and another string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Other</td>
<td class="doxyParamItemDescription"><p>the string to compare this string against.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllowReplacements</td>
<td class="doxyParamItemDescription"><p>whether to allow character replacements (change one character into another) as a single operation, rather than as two operations (an insertion and a removal).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxEditDistance</td>
<td class="doxyParamItemDescription"><p>If non-zero, the maximum edit distance that this routine is allowed to compute. If the edit distance will exceed that maximum, returns <span class="doxyComputerOutput">MaxEditDistance+1</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the minimum number of character insertions, removals, or (if <span class="doxyComputerOutput">AllowReplacements</span> is <span class="doxyComputerOutput">true</span>) replacements needed to transform one of the given strings into the other. If zero, the strings are identical.</p></dd>
</dl>


<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dd37b8e348fbe4c8c870ca00415da92">llvm::ComputeEditDistance</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#ae015be66fae811e0fe4cc32ce868f373">LookupNearestOption</a>.</p>

</div>
</div>

### edit\_distance\_insensitive {#aee1ef526cd95ea3036b0569aabacc1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StringRef::edit_distance_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Other, bool AllowReplacements=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, unsigned MaxEditDistance=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0947a70171b7e63f155a2eae2bfd706">llvm::ComputeMappedEditDistance</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### empty {#a2dc80c585ad5882da8cae7b5968f7e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>empty - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the string is empty.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a8c0a6f5ad327c20349f2a2e0a5845b3e">llvm::MipsTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a068641b222182c6ca0412660993bf1fe">llvm::AMDGPUMachineFunction::AMDGPUMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad1a874181e3007dcd2735f381c3db6d8">llvm::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owneddatasection/#a124ee6d61bfd830c483ce8273529bfcf">llvm::objcopy::elf::OwnedDataSection::appendHexData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a2582ad4e03989cb2e2712ae5ddf5e2a9">llvm::object::applyNameType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b107908666d5d5a2920e6fb28387f7c">llvm::DwarfUnit::applySubprogramDefinitionAttributes</a>, <a href="#a5b6faabb08339ea1dd11e9d37a668634">back</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a37c61e706d286423b2a78eb523392fb2">buildDWODescription</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf688be573d89d297c2971a2bf1ce294">llvm::caseFoldingDjbHash</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#aa39f65efac3a51f3001285439ea997be">anonymous{Debugify.cpp}::checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuremoveincompatiblefunctions-cpp-/amdgpuremoveincompatiblefunctions/#a9910118e4db5bb56e348017ba1460553">anonymous{AMDGPURemoveIncompatibleFunctions.cpp}::AMDGPURemoveIncompatibleFunctions::checkFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a0a06fbb4615244e2f5e81529fd08a9d0">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::checkVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/djb-cpp/#af60bf47ef264d1d6c10fea7a1dd7da9f">chopOneUTF32</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ac4560fb1d6b91d4ba6edb7e907573c1e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::cloneAndEmitDebugFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2f6c06a6e0a4bb5192193116bded1308">llvm::InlineAsm::collectAsmStrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/diehash/#ad27bf36fbf19cdf6d2e5a9dfeebaf260">llvm::DIEHash::computeCUSignature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a2033c9c8bb35857028fedf2f53ffb6de">llvm::ARM::computeDefaultTargetABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a725fe8674a09b1579039321d641118e4">computeTargetABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#af00c65f1a835c8452272468c2f09bd18">llvm::LoongArchABI::computeTargetABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a28e75155ea06a5ad70d3a662be05e350">llvm::RISCVABI::computeTargetABI</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a559ce07c89729386c121ca32098cb0f9">llvm::consumeUnsignedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a74d9194822bc4e6c84bc71a8ea89db5c">llvm::detail::IEEEFloat::convertFromString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad23b52a299ca563f6e6a6c6cece54dcc">llvm::convertUTF8ToUTF16String</a>, <a href="#ac66731b70af2ad5aded1ce13a20acb29">copy</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader/#a0e40bbc853b758d181123ba30308e326">llvm::memprof::RawMemProfReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#aa13d9a01b470d4ae7e0f1ea117f2e3dc">llvm::sampleprof::SampleProfileReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a9f274211d8e2baf7f13ec1e030e09de6">llvm::vfs::RedirectingFileSystem::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab0231205adf0a10ac89540dbcfdcd2d7">llvm::sys::fs::create_directories</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a03a9d7487e3a99b134abd6aa5bf2a101">llvm::sampleprof::SampleContext::createCtxVectorFromStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#adced657ead8595f4da252cea6e2f3dd8">createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd35d43ef05edd633413fa4cfa802c0e">llvm::createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/object/anonymous-coffimportfile-cpp-/objectfactory/#a0194b0cf6c8e570555fe9a8eb0c8d167">llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::createShortImport</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a04b2896c2de03735467fba862459ff2f">llvm::sys::fs::createTemporaryFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d90c79914c0bdfadad630647f8843b">llvm::declareSanitizerInitFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae39bffc615ea979f44a25c730094bbb4">anonymous{MasmParser.cpp}::MasmParser::defineMacro</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfyaml/#ac84f1cd7e37d227e700d6a69398fd3c1">llvm::ELFYAML::dropUniqueSuffix</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#ac0c87bb82a7b90da0291671f18e9f8cd">llvm::gsym::GsymReader::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#aaa38af193e8749bb5d9b945b405e933e">llvm::DWARFDebugLoclists::dumpRawEntry</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#ab3836b4bb1237941003273adb235b8e2">anonymous{AMDGPULibFunc.cpp}::eatNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ab07e49a5499032dc8f97198892218853">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::EmitCommentsAndEOL</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a1400e693c6c532e696d1505b75970187">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitExplicitComments</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a20a4c6ed55ed94fa363e630573918107">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitFileDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a17b7b6be8c77b055cf79259a4af7ff0c">llvm::ARMTargetStreamer::emitTargetAttributes</a>, <a href="#a393bbf5d4d82eaebfc257042c3a82ece">ends_with</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a8be5b89e05ade5c6e5a08c6351b9821a">llvm::cl::Option::error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a632491c0fb6b223c9661724d5f14fd31">llvm::memprof::extractCallsFromIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5cb79e4ed85004fb29c445aea098b923">llvm::AMDGPU::fillAMDGPUFeatureMap</a>, <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a2590274bcc6c09009ed10feb5455243d">llvm::sampleprof::FunctionSamples::findFunctionSamplesAt</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjcopy-cpp-/removenotedetail/#ac4351802dd6ac9ef76f15a38147eb0d7">anonymous{ELFObjcopy.cpp}::RemoveNoteDetail::findNotesToRemove</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19209407d5758bdcecfe6e8f5cea0c2d">llvm::finishBuildOpDecorate</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlstringtablesubsection/#a4f338238a79ff08b58e7caf51b4e4986">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLStringTableSubsection::fromCodeViewSubsection</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="#a61364ca3a5ff90fb2aa0d5a371fd43f7">front</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a3469e685d3fadac587ccaa4ca8144d70">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa15319612cd5edf41994eab4a092896">llvm::get_threadpool_strategy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a35e48627247fb4ab86466af66ed3ec31">llvm::AMDGPU::getArchFamilyNameAMDGCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa92ad486f7d87701440dd069319134d5">llvm::ARM::getARMCPUForArch</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacronode/#a9dc998f25a7d62a23a4ed8bde5b116c9">llvm::DIMacroNode::getCanonicalMDString</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a1c6cc0fd9d9b1a21354f035a9e1536e3">llvm::DINode::getCanonicalMDString</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a36361ab61c92cc509c46bcc75b8dd34a">llvm::objcopy::elf::IHexRecord::getChecksum</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontexttree/#a4bd9844a95feccd824a78e62c476f423">llvm::dwarf_linker::classic::DeclContextTree::getChildDeclContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a64fec16b33fa7f23710afb8904948f30">llvm::MCContext::getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a53949973d752a1d918687b758424714a">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a84ea0567e15790f68c421dada011ec5f">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#aedfa5e387d929b78090c06db5e0965e2">getFeatures</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue/#aa47cad32e9eb34704f1ce2ead863e518">llvm::DWARFDebugLine::Prologue::getFileNameByIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e54b20745d63f337766efd74f06c5c8">llvm::getFuncNameWithoutPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#af7fa5af32e8d5c5142f7a39ae905681b">llvm::InstrProfSymtab::getFuncOrVarNameIfDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#aa167494fa5d265faa5315612cd3d37fe">llvm::gsym::GsymReader::getFunctionInfoDataAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a8601675aad561f5f3467eb4a49c95794">llvm::object::AbstractArchiveMemberHeader::getGID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9f44684437922cc04a01fcdcc73215d0">llvm::GlobalValue::getGlobalIdentifier</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a8e84758998af59452fa777bfd7b7d7d1">getGPUOrDefault</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae254bedbb0fc90b423b5072a97ef3efd">llvm::AMDGPU::getIntegerVecAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4cb54e7d62530f9e973ff35f6301de6a">llvm::X86TargetLowering::getIRStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a0f382b34dc924b235282157869cb3771">llvm::TargetLibraryInfoImpl::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#afea73c1af002769dde1fb465f40b6ac1">llvm::object::MachOObjectFile::getLibraryShortNameByIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a0f432b141d17384c56f11e55de61aff7">llvm::PPC::getNormalizedPPCTargetCPU</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#ad4c0f9a1193f368bbea577f429a3050c">getOpEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#acd9d92f0d78ae680c0eb2a43573b93ff">getOpRefinementSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a53bba044b64b7a894e30aeb52a247515">llvm::DwarfCompileUnit::getOrCreateCommonBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a9bd19f659a2944b4440bafe9f78a0809">llvm::DwarfCompileUnit::getOrCreateGlobalVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/llvmsymbolizer/#aed363690d82a9bc955ab653a37e75090">llvm::symbolize::LLVMSymbolizer::getOrCreateModuleInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a717a199ea9514d956fa87fd23c13a228">llvm::getOrCreateSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a4d52a5b3d278b07fa7992477cc3c5474">getPassNameAndInstanceNum</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-passtiminginfo-cpp-/legacy/passtiminginfo/#a6a4d99a79c2bcaaf0e30b92826156793">llvm::anonymous{PassTimingInfo.cpp}::legacy::PassTimingInfo::getPassTimer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a388b3ce412f145bfac051690e8ef5596">llvm::getPGOFuncName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#abc815b1ea53028ed294488cf5ac69c9e">getPrettyScopeName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a427ea8030e264e1e94ec134806be72a9">llvm::MCObjectFileInfo::getPseudoProbeDescSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#ada5c91ffe6ce1366ef81b5cfea3c59fc">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a299e5debf3d108b71fc6642ecd31e5e7">llvm::SparcTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a8c99c6a7b32e47161b669182402a5c66">getSearchPaths</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a20ae5f9703535cca3725fdb1512125ab">getStackGuard</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf156ed576f5bcdb93911b50b775c8ac">llvm::getSubDirectoryPath</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#a094b53ae338bc1ed10ec35facf8e07b0">llvm::M68kMCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a866133bf888d0b8bbce2275845511edb">llvm::TargetLoweringObjectFile::getSymbolWithGlobalValueBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a18eabcf596deec54ada617114b818baf">llvm::lto::getThinLTOOutputFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a6a8c201e99f1acf8f6cdc654093c0a61">llvm::MCSymbolXCOFF::getUnqualifiedName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a388e35e6191f5f51957c3024ef635190">llvm::yaml::Node::getVerbatimTag</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a15113486c66611b76318afc2c37352c3">llvm::TargetLibraryInfoImpl::getWidestVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#af4c71e263810db89b9093317f9ffb48c">llvm::DWARFVerifier::handleDebugAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a21de2c5fb30965f2300f1e49f791c915">HandlePrefixedOrGroupedOption</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a71f8caad22bde933605f9d1634f63288">llvm::sys::path::has_extension</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ad94879f2cf05db817fc49abbe50fbbb1">llvm::sys::path::has_filename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a532941f1ad0bf4dcc13beb5cd6d000d4">llvm::sys::path::has_parent_path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a111a7c3004bc8e2a53a501c70fd5f392">llvm::sys::path::has_relative_path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#afbfbc19d8aa5dde440140c214c118516">llvm::sys::path::has_root_directory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1dae3a7c3f46eaa1201a537367693f11">llvm::sys::path::has_root_name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a42859e81c863cc365f29938285e98a68">llvm::sys::path::has_root_path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ac4d78a6e97131191378aa1ca03a6c7f5">llvm::sys::path::has_stem</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a8a75c4defaf794fb1baf8afe140c0fe7">llvm::SubtargetFeatures::hasFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9f52d196211845d0d605733e2f699055">llvm::GlobalValue::hasSection</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ac9c3c65b113996cabc72bd6223410369">llvm::X86TargetLowering::hasStackProbeSymbol</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ae6071096c441061cfc9f7b4cf8f4ec9e">anonymous{DlltoolDriver.cpp}::identifyImportName</a>, <a href="/web-llvm/docs/api/classes/llvm/cskysubtarget/#a2ad004b6aae47e79345d419500ec8316">llvm::CSKYSubtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430subtarget/#a50008896c0779df43e90206a6d21686b">llvm::MSP430Subtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcsubtarget/#ad55eb63496266a67be2cd32515446e57">llvm::SparcSubtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af30042e4c09138928b477e3834f0a13e">llvm::X86TargetLowering::insertSSPDeclarations</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a22638e32cb1220ddfacd7eb1bc5dfcf5">llvm::gsym::GsymCreator::insertString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a62ffd7301f2325401902cda2f544da0a">llvm::AMDGPU::insertWaveSizeFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">llvm::ELFAttributeParser::integerAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp/#a97d418be7ec7fc90283cc2fee34599ce">isCanonical</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#ae07a5960fad31a5e146cb9d81dd15b47">llvm::SubtargetFeatures::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a798028b6fc917a63c65f97cb29ab6b69">llvm::TargetLibraryInfoImpl::isFunctionVectorizable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a1dd4a22ee51a1f2aa2cef933db7e2efe">llvm::TargetLibraryInfoImpl::isFunctionVectorizable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lineprinter-cpp-/#af2120c452b8889478d5a51d200a14bef">anonymous{LinePrinter.cpp}::IsItemExcluded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6abe01777169c2216339a59d84bf3999">llvm::yaml::isNumeric</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#afcd8b4904b4e18e880c419386dfe4d85">llvm::RISCVISAInfo::isSupportedExtensionWithVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sendmsg/#adbb10f56f9659f287512e286ededa608">llvm::AMDGPU::SendMsg::isValidMsgOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mtbufformat/#a5ee42390df5ca4d0d3997dec2087c787">llvm::AMDGPU::MTBUFFormat::isValidNfmt</a>, <a href="/web-llvm/docs/api/classes/llvm/loadandstorepromoter/#a5a4040326a09f994f2b5481cf5c8da82">llvm::LoadAndStorePromoter::LoadAndStorePromoter</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a71a8c6078191280b00feef9864b58338">loadBinaryFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ac6293b7ea84a4deac85481dd10dad437">llvm::OpenMPIRBuilder::loadOffloadInfoMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#ae015be66fae811e0fe4cc32ce868f373">LookupNearestOption</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a9a9a7989eeb174879ae8581e33e61824">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a693b6f70fcd9bc58db0af0591dc16b83">llvm::codeview::CodeViewRecordIO::mapStringZVectorZ</a>, <a href="/web-llvm/docs/api/classes/llvm/globpattern/#a7bcd47fe233f29521e2d33adc1bf45e0">llvm::GlobPattern::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6ded20d42a05e6478238dcfd3caceede">matchAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a92b68a49e0ce87d4d52c24f060af0502">llvm::yaml::needsQuotes</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a0db487cbf8c154e299a79baa79fde1ca">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#add5616535a62c9047ccfbf84bf778663">optimizeNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a33721fa1b2c102b1fd611024835681da">llvm::AMDGPULibFunc::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe/#a4f2d81fc8d21674863d5a753df3eed54">llvm::DWARFDebugFrame::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a1d4e2a477b2b896adfdec5e55638b725">llvm::PassBuilder::parseAAPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#acefd73b7cd23506659faf02fd0957914">llvm::MachO::parseAliasList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a98361b28ee9d2d64026953887c1aff33">parseAMDGPUAtomicOptimizerStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a932dc6a42ae580674ab795b1946a9d68">parseAMDGPUAttributorPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a1a125d48909fc453d01785064bfb5e67">llvm::AArch64::parseArchExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a721eb5bffb57cea96d7a9b45cbe302cf">parseARMArch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a51edfbed0895aa13fbac2ec63d1dc755">anonymous{PassBuilder.cpp}::parseASanPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#aa1267723ca2b4fde441e992f4853fa52">anonymous{PassBuilder.cpp}::parseBoundsCheckingOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#a874fe455718e3ea10454347888391fc2">parseCC</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a85286c436c5c0f09abe43dc522fe5f2d">anonymous{PassBuilder.cpp}::parseCFGuardPassOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#aa7b40dda7a09e0c055d6138b404d0789">llvm::DebugCounter::parseChunks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3b7e007d72635d0f8c320a122f71947">llvm::parseDenormalFPAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a3237e027b109101104739097a3e415da">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSecureLogUnique</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/parsedstringtable/#ade4e99d5844b81145b0a95e2102e8bd4">llvm::remarks::ParsedStringTable::ParsedStringTable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#afd6042c1b738cd6940d1f0c8e7e22090">anonymous{PassBuilder.cpp}::parseEmbedBitcodePassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a4f4bb162495773b87818cf7a66410c42">anonymous{PassBuilder.cpp}::parseGlobalMergeOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a6a2c903206e499a40b30eacec625bab4">anonymous{PassBuilder.cpp}::parseGVNOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#aa6ce0897e0923130a01d2226559275c4">anonymous{PassBuilder.cpp}::parseHardwareLoopOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a6b63475afb18b589e0cd668a55da3f0b">anonymous{PassBuilder.cpp}::parseHWASanPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a705e25c3f466b071036bde5de60454c5">anonymous{PassBuilder.cpp}::parseInstCombineOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/versiontuple-cpp/#a78818341564bdaf1e6ec53d418cb5cc2">parseInt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a63d8077ac333f927273b1e014644cf89">anonymous{PassBuilder.cpp}::parseInternalizeGVs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a258bac7878912fdc0517663e0ef41f2e">anonymous{PassBuilder.cpp}::parseIPSCCPOptions</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ae671ad01f3f6d26f481c1f6cf0ac770e">anonymous{PassBuilder.cpp}::parseLICMOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ae99f09b9fc8bb52957b29dc409b67044">anonymous{PassBuilder.cpp}::parseLoopRotateOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#adfcb070aecda48cfd7f3d5bb78b23c3f">anonymous{PassBuilder.cpp}::parseLoopUnswitchOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a0bf1de19ee39f1ce18df8c0b5e42a1c2">anonymous{PassBuilder.cpp}::parseLoopVectorizeOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2de75d77a5ee094dabe819e4b5855a6a">anonymous{PassBuilder.cpp}::parseLowerAllowCheckPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a18cb2b53fc5dbf94a7751fe179ac4ebc">anonymous{PassBuilder.cpp}::parseMemProfUsePassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2a5fbe887884963e5fc19c8d823ef83c">anonymous{PassBuilder.cpp}::parseMergedLoadStoreMotionOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#af9206ecc850cac7b88622396c3025f57">anonymous{PassBuilder.cpp}::parseMSanPassOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2b97735452295d7091f55cfaf309ad4c">anonymous{PassBuilder.cpp}::parseRegAllocFastPassOptions</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac4d29f90f81ea8264f49bb0736faf1d0">llvm::remarks::YAMLRemarkParser::parseRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a93e1f93d537243a559abd940ec1b6f53">parseReplacementItem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a24172b22d5d5ef8caa9223a259787420">anonymous{PassBuilder.cpp}::parseScalarizerOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a1ea0b527a25e96bb74c8217704b22a07">llvm::MCSectionMachO::ParseSectionSpecifier</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ab47e139366ce224347ee4ea7313c7ff9">anonymous{PassBuilder.cpp}::parseSimplifyCFGOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adc2db790282de50547f17992a5dece6b">llvm::PassBuilder::parseSinglePassOption</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a699c91d49b498d9a894ce603b4d56a89">anonymous{PassBuilder.cpp}::parseSROAOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ab72e4b451f3f28ac0f1f862b8e9f8809">anonymous{PassBuilder.cpp}::parseStackLifetimeOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a6aa09786a870818c81688905eb2dd903">anonymous{PassBuilder.cpp}::parseStructuralHashPrinterPassOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ac784253baaaa3c7ac2760f3d9b71f1c1">parseSubArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#a28f2b75ae3485678ba907fd613f90317">parseV2DirFileTables</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#ad17bf01008144e718fa39ffa0ef84733">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::prettyPrintAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/operation/#a776144ebd87427d17aaade268a4c1c6e">llvm::DWARFExpression::Operation::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aab90c946a08959c165433b2c125895ea">llvm::MCInstPrinter::printAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#adf641c6eb9421f15fc9015e7032b71fb">llvm::ELFAttributeParser::printAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a0cfb229540a44ffdd406ca12e441fd47">PrintCFIEscape</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a6bcdb97daefc7a1ed36de42e22be84b2">printExtendedName</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a9eeb6ab7ee4a2fd19e22f671d7ce32b2">PrintExtension</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/moduledebuginfoprinter-cpp/#acbf578ca2e23ec24ac92210d63747ca0">printFile</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a7306dff221a5075d2166c3cf6b740b35">llvm::AMDGPUInstPrinter::printHwreg</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#ad90a9106e87fa0c49bb103bf97f23336">llvm::NVPTXInstPrinter::printMmaCode</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a84230421edc594e09adc8a9a743823de">llvm::cl::generic_parser_base::printOptionInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/categorizedhelpprinter/#ab00bf8967de6bcd0ed813dd9ec8b09a9">anonymous{CommandLine.cpp}::CategorizedHelpPrinter::printOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a74ff02d9e2d701854db9c4f86ddbd3d4">llvm::AMDGPUInstPrinter::printSendMsg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a14dfead54615906a608b43ce6881920b">processLoadCommands</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeimpl/#a2d70fffce492b01bdb5fb0e43d33372c">llvm::AttributeImpl::Profile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/#a7d852659ea6c0a8e12cf0c8d5e8d2e16">llvm::irsymtab::readBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>, <a href="/web-llvm/docs/api/structs/llvm/lessrecordregister/recordparts/#ab6f58b67225aaf63ec2aeee94dd053f4">llvm::LessRecordRegister::RecordParts::RecordParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb31f2db6f0fe5eaa5b28464141223aa">llvm::sys::path::replace_path_prefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#a3985f1f39349428d17f0d2b81ebc6349">runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a25da45ec2b5b7dacb22e831cb7aef0c5">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a3093181fe818bf3fe03f72887de8943f">llvm::sampleprof::SampleContext::SampleContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a147437aa3b97e99609ae28aa1ee2eb32">sanitizeFunctionName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#aca2d3ebfb1896c7f85f76bcb6dea8b81">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::save</a>, <a href="/web-llvm/docs/api/classes/llvm/stringsaver/#aab5ad8c5b3081716904f28dbb1979daf">llvm::StringSaver::save</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a70182ac5a86e57b12b56cb214b78a8f1">saveTempBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#a1c21bccdd0b08748a1e0822417c8fd8e">llvm::yaml::Output::scalarString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#aa93fa22630383fe07736811e31c03f81">llvm::Hexagon_MC::selectHexagonCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-df914a78aa74437406828e15b40ba1b2/#a37399dc7cab3f63caf490b1a59fdc832">llvm::orc::shared::SPSSerializationTraits&lt; SPSString, StringRef &gt;::serialize</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile/#a0fb71da1c873d2aedfa32922154d7d39">llvm::MachO::InterfaceFile::setFromBinaryAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac12e315180fb16cb5874fb41526ca453">llvm::codegen::setFunctionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aff8740863a5ee2650339400236b6224b">llvm::GlobalValue::setPartition</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a25d8acedc0fc6a1fbd8a2eea6dcd0f4c">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::setPassPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a959c99adbdc7f8375cf866916c6b60f2">llvm::GlobalObject::setSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a7df2e6bd8a987ca6e4e4ced678ecbfcf">llvm::lto::setupStatsFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a9ad2ee389fa99a4c02f610183530735c">llvm::VFABI::setVectorVariantNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a1e3a00a397d505999a690bef5cdee1c8">shouldPrintOption</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ace7305e89af1fe5485e070f9b0187805">llvm::MachO::shouldSkipSymLink</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af63d1fba23bc323d27c9dc50313698eb">llvm::SIMachineFunctionInfo::SIMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#ad34c639c525fbb1dc22558683559f46d">llvm::SIModeRegisterDefaults::SIModeRegisterDefaults</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>, <a href="#a7b0138ddc186a7cb5cfd04dde671220e">split</a>, <a href="#af0284e4c41c0e09c0bc4767bc77a899d">split</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a>, <a href="#a71ebff92f9ef18f3009f88457a09776d">starts_with</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a263bac5d85adb87956f47116b8fd5b2a">llvm::sys::unicode::startsWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a59a5eeccde7b8eef0833cee7b914443b">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::startSynthesis</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a8125ecaffe4cb18a746e29ec30bc74c5">llvm::ELFAttributeParser::stringAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a865e83348693ae24ada91964c6da76e4">llvm::symbolize::toJSON</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineadvisoranalysis/result/#a64e2a53c670b4531950c994d84bc4e39">llvm::InlineAdvisorAnalysis::Result::tryCreate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#af400fb04adbd61dff400a8a4a756aff9">llvm::MCDwarfLineTableHeader::tryGetFile</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a6b61483aaba059f71022975a37737e15">llvm::VersionTuple::tryParse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1e256b3e261a7e37851be3f91173e6c0">anonymous{VFABIDemangler.cpp}::tryParseISA</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34c89c416395df723a937ace993f511a">llvm::UpgradeAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#adfcd3a2486f54c348da1859c41f6cc09">llvm::InlineAsm::verify</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a6c13c3a269c58cac403ad567c29d679e">verifyFuncBFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a9d1c89a919275d8aa033388862d7771e">writeDWARFExpression</a>, <a href="/web-llvm/docs/api/groups/set/#gacacf298ae33051bd387434c4ebdd2be7">llvm::ThinLTOCodeGenerator::writeGeneratedObject</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f7d4f36e40ebd1e64d3c802976e7225">llvm::writeStringsAndOffsets</a>.</p>

</div>
</div>

### equals\_insensitive {#ae46058c90a3c703357331a6501b32f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::equals_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for string equality, ignoring case.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#ae9c79bda245d64ef5df420f94ec4bbd1">compare_insensitive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ab2316bb8a6ff1ce90efe6cff6d32c3f3">llvm::SmallString&lt; 0 &gt;::equals_insensitive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a9952645a56e841314d2b880bd31375">llvm::findVCToolChainViaEnvironment</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a528ccfe220ae477b22431f3328d0b90e">llvm::X86TargetLowering::isInlineAsmTargetBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a09ddc9ac2f9a0ce92be5565eff4f3869">llvm::HexagonMCInstrInfo::isOrderedDuplexPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#afa801ffa70e7cd238829a01fa92d71c4">anonymous{MasmParser.cpp}::MasmParser::Lex</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#a605f317c5671abb87131f5dcb6b2fe4a">anonymous{X86AsmParser.cpp}::X86AsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a64ef2d014c82249a7bc8cb033757d7f1">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/asmparser/hexagonasmparser-cpp/#a9b92870ea1113bbbf2380a032c4eae73">previousEqual</a> and <a href="#a56e7e0bebc570bc6814cdefd1f2ecda3">rfind_insensitive</a>.</p>

</div>
</div>

### front {#a61364ca3a5ff90fb2aa0d5a371fd43f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::StringRef::front ()</td>
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

<p>front - Get the first character in the string.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> and <a href="#a2dc80c585ad5882da8cae7b5968f7e74">empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5e419b9328977a480fda42c789b77237">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::addExplicitComment</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#ab3836b4bb1237941003273adb235b8e2">anonymous{AMDGPULibFunc.cpp}::eatNumber</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#a41c1d2d1393c23d25c9cc13f39ca6742">anonymous{AMDGPULibFunc.cpp}::eatTerm</a>, <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode/#a8f6028cdd89adeb15d6755814af79718">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getBodyContent</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/vftablerecord/#aaf72b9fe672ccad7a9cbe3525203db09">llvm::codeview::VFTableRecord::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a299e5debf3d108b71fc6642ecd31e5e7">llvm::SparcTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6abe01777169c2216339a59d84bf3999">llvm::yaml::isNumeric</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a92b68a49e0ce87d4d52c24f060af0502">llvm::yaml::needsQuotes</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a594f615f5a0025d4f0c92e27feb9d65d">llvm::yaml::parseBool</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a581197bc2dbbef326892f5ff08761f54">llvm::PassBuilder::parsePassPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ac3231081094bc7fdda779c6b73f9f706">llvm::PassBuilder::parsePassPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9ca0e57e6445ab2fe568e53ba29cc0fd">llvm::PassBuilder::parsePassPipeline</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a96f48f9a5690ef01b9d2574472e1f7e2">anonymous{MIParser.cpp}::MIParser::parseTypedImmediateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5618db29d0000023a813f4d00e3bf484">popFront</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a> and <a href="#a71ebff92f9ef18f3009f88457a09776d">starts_with</a>.</p>

</div>
</div>

### lower {#abb1344e353958db14e66ec7ab574001a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string StringRef::lower ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="#a46f643f1eb1939362c7dd79361bcbd0e">begin</a>, <a href="#a996c7ca3dd6843ba5d55a7c217770270">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a36f31bfe9e8b65522b0be4bdcec96e83">llvm::map_iterator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a9b3a355413b120f5a101863780e3c44a">anonymous{AsmParser.cpp}::AsmParser::addAliasForDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa2bdca1224d6c61d9e395584a3c3eb4b">llvm::ELF::convertArchNameToEMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#aba7c57fb90825072fe1651fa67af9306">llvm::MipsTargetAsmStreamer::emitDirectiveCpAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a1d2c08fcdb60f4cf60dab2907f45c44d">llvm::MipsTargetAsmStreamer::emitDirectiveCpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a6dca65256df2dd8715cf3221e33c6f4e">llvm::MipsTargetAsmStreamer::emitDirectiveCpLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#a56d51423094db4b2932d7e53c69ea140">llvm::MipsTargetAsmStreamer::emitDirectiveCpsetup</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetasmstreamer/#ab08d6867bd7f09740aa8c3d1b07b9f32">llvm::MipsTargetAsmStreamer::emitFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetasmstreamer/#a6a3980f1edbc6f6c9b7ffb5410e4c7bd">llvm::SparcTargetAsmStreamer::emitSparcRegisterIgnore</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetasmstreamer/#ac269ca4bf521cc06f77cbec05c0db34b">llvm::SparcTargetAsmStreamer::emitSparcRegisterScratch</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetasmstreamer/#a08ef7e6f681acad3c0577e07b2403a39">llvm::VETargetAsmStreamer::emitVERegisterIgnore</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetasmstreamer/#afabfdcc7b965906ea092c28d0ccd37e0">llvm::VETargetAsmStreamer::emitVERegisterScratch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#a2980b88b119166ba490ca0ca232a9ca9">getBankedRegisterMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b24b650f118105cc5fbc34c83f006cf">llvm::getMachineType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7ade77bdee8e8fe0f6694d0ef8fda0ad">llvm::RISCVTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a17b4520610e0151c3ea791c6adf27d07">getRegisterName</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#afaaaf7da6379fe3994da86bf71024ddc">anonymous{AsmParser.cpp}::AsmParser::parseAndMatchAndEmitTargetInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a5a86255e1b22fdc61781627d840204c5">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#adf59b005b7771f4aa72204093c13c804">anonymous{ARMAsmParser.cpp}::ARMAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#acb92a6ad259468a1081b2942e9ce8930">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a02d8a789e50e085fa66aac9180bb03f3">llvm::ELFAttributeParser::parseSubsection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a6e6c0bab5a3be5e64ec9e03316c0c782">parseVectorKind</a>, <a href="/web-llvm/docs/api/classes/llvm/miprinter/#a0dec8c3931e753255d1e88ab0216e629">llvm::MIPrinter::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a94ccb5d36399ea8c01c40c8c28123454">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84f1f18b0f13167b8e9c455b9524b58d">llvm::printRegClassOrBank</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstprinter/#a7ec3ec3631ebb4ecb27b48aca089309f">llvm::ARCInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a6665a169575ce37fdf74c68c7c895510">llvm::LanaiInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstprinter/#a4b850cbcb67aa7a498a57cb99d850609">llvm::MipsInstPrinter::printRegName</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoreinstprinter/#a76882af8e78c6b2d4751af07b8459b4c">llvm::XCoreInstPrinter::printRegName</a>.</p>

</div>
</div>

### size {#a5db9240c74644c67759dd0f901fc3c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringRef::size ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>size - Get the string size.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a9fd3cdd22c698232d4998d7b3ea7b21a">llvm::AArch64FunctionInfo::AArch64FunctionInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a3251137d4e13982c711221d45fff9a09">llvm::json::abbreviate</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/anonymous-lvcodeviewvisitor-cpp-/lvnamespacededuction/#a3e493b76a7bdfe59b7a44c6106b25ff1">llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVNamespaceDeduction::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#ab3006e90ba5c4717808c3c35e1a778a5">llvm::Hexagon_MC::addArchSubtarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5e419b9328977a480fda42c789b77237">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::addExplicitComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa6138676e4615546fc1c7d559029916a">addSection</a>, <a href="/web-llvm/docs/api/classes/llvm/btfstringtable/#aac5fc2f786aca51dda4f7803cd86e847">llvm::BTFStringTable::addString</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1accb391b511ed37f3b8b88f773f09c">llvm::msgpack::Document::addString</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#a97f8c0863c59c4c7900ce9aadf6dff9a">angleBracketString</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp/#af0d778519d3d280962aa0e90f2aa3514">angleBracketString</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owneddatasection/#a124ee6d61bfd830c483ce8273529bfcf">llvm::objcopy::elf::OwnedDataSection::appendHexData</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#a09f85524dd190f2649d7f584a2edcce3">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTypeTagName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a10755af4d39e62dbf3dfb1caa875a822">argPlusPrefixesSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a48d1af604311ed1fe7a55be6137c2253">argPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/cachedhashstring/#a2e1c9187ee4bfb22d0e1de02e3a22ade">llvm::CachedHashString::CachedHashString</a>, <a href="/web-llvm/docs/api/classes/llvm/cachedhashstringref/#a64657de4ef02b08fc25c98512b9984ac">llvm::CachedHashStringRef::CachedHashStringRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a49077c24022f5ec4c84d809abf92e91e">callBufferedPrintfStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp/#a47fecf0b0acf65817de4695e97630cb6">charTailAt</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerimpl/#a03459afe90e9865de42de9912ec0c972">llvm::RuntimeDyldCheckerImpl::checkAllRulesInBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp/#a3854ebadf535d51316afa5e409f22f5c">checkArchVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ab0c070f20da31f2040dbe987dbc6041a">llvm::SITargetLowering::checkAsmConstraintVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a4d955f22836e92a508b414d270041628">checkDyldInfoCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a21566fd3bc19b4348f0deed830e19199">checkDysymtabCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#afbece8143fc21ed045b0d711c7103d17">checkEncryptCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#abe7067ce0893d97940a85141e4c44776">checkLinkeditDataCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#aedcf65b10ecb990ac021daf4f940a881">checkNoteCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a197ed26dbc11fa1cf315ab378b657ec4">checkSymtabCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a1a0d53be15e648f327c4292341fa7dad">checkTwoLevelHintsCommand</a>, <a href="#ae0c6424784f132b91eb387a3ee0b57c9">compare</a>, <a href="#ae9c79bda245d64ef5df420f94ec4bbd1">compare_insensitive</a>, <a href="#a8a3989cbad7cca2a86cb7d3a0627748b">compare_numeric</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobject-cpp/#a9d36087a89aca95c0df3141528c1dc2a">constructSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#afc82faca788f75fcf0a8f60a406342ba">constructSymbolEntry</a>, <a href="#a14180977794bfc2a37dbffeef3ca20de">consume_back</a>, <a href="#ac5fd848165f133bf149f8f27618ce313">consume_back_insensitive</a>, <a href="#a8628d3c93731ec5ac11a4ca9dbc67dfb">consumeInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a559ce07c89729386c121ca32098cb0f9">llvm::consumeUnsignedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a74d9194822bc4e6c84bc71a8ea89db5c">llvm::detail::IEEEFloat::convertFromString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad23b52a299ca563f6e6a6c6cece54dcc">llvm::convertUTF8ToUTF16String</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#a75f0ba2a248f2f7f77f477bfb8d6dab2">llvm::coverage::BinaryCoverageReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#a09f6c55119f75e7997dab2bbd8d2f065">llvm::StringMapEntry&lt; std::nullopt_t &gt;::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a03a9d7487e3a99b134abd6aa5bf2a101">llvm::sampleprof::SampleContext::createCtxVectorFromStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#afdcc3a66137dcf1fb3dbdc7adaedc26c">llvm::objcopy::coff::createGnuDebugLinkSectionContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4fbdc8f1be1bfc357861f63756755f65">llvm::jitlink::createLinkGraphFromELFObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9ec3732ab208437ca6ee8e13438bd0e8">llvm::MachO::createRegexFromGlob</a>, <a href="/web-llvm/docs/api/classes/llvm/object/anonymous-coffimportfile-cpp-/objectfactory/#a0194b0cf6c8e570555fe9a8eb0c8d167">llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::createShortImport</a>, <a href="/web-llvm/docs/api/classes/llvm/object/anonymous-coffimportfile-cpp-/objectfactory/#a3f315ec5e0d164d9cfc44a35fa8d0828">llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::createWeakExternal</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#afb874a51b13c3cdfa8011bbf866c3658">dumpStringOffsetsSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#a5d574989dd4688949082681ec54010f6">anonymous{AMDGPULibFunc.cpp}::eatLengthPrefixedName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#ab3836b4bb1237941003273adb235b8e2">anonymous{AMDGPULibFunc.cpp}::eatNumber</a>, <a href="#a51c1f447b5d754191564ae340ee4253b">edit_distance</a>, <a href="#aee1ef526cd95ea3036b0569aabacc1c9">edit_distance_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#ac7a72ed69b91577b81089ff1a7a57197">llvm::BitstreamWriter::emitBlob</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7e84332e336e7ded64bc2acb2bfc66a7">llvm::dwarf_linker::classic::DwarfStreamer::emitCIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a81600054c53c8bfe10547514c330a547">llvm::DWARFYAML::emitDebugAbbrev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#a95b9cd710db1ece98dc23d86c22bdb5b">anonymous{DWARFEmitter.cpp}::emitDebugNamesHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#ab3efa9219c5d461ff2e67802f8ea6aa7">llvm::dwarf_linker::classic::DwarfStreamer::emitFDE</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a6c61c3e648797ee04fda231739eedfa2">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::emitFDE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ab6508358ece1c10feb9de803b4d27535">llvm::MCObjectStreamer::emitFileDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a161ac460fefc16f98a8dd1a9f019af9a">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a32519abee87d93f315f9da6cbeed31cf">emitPPA1Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c0d4726ea833a35fd64d21ea9964d33">llvm::emitSourceFileHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a9d569b5d160f74ec5712bf4c3be31c60">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitStringSections</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="#aca439bf65258d9d8d057812938b617c5">ends_with</a>, <a href="#ae57b9ee061903472c1cc9082849ed34e">ends_with_insensitive</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ad1056825d31bf187d0be430c51aac281">llvm::sys::path::extension</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-path-cpp-/#aa97df12f81288d1870f96204ed9b65c0">anonymous{Path.cpp}::filename_pos</a>, <a href="#a82369bea2700347f68e1f43e30d2d47b">find</a>, <a href="#a18de63f444e95dfff81803a482ab6eec">find_first_not_of</a>, <a href="#af38cc29d28845d48d8423918d8910d12">find_first_of</a>, <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>, <a href="#a035cf6768564ead852edfff8ca9c3b6e">find_last_not_of</a>, <a href="#a819cd72313f82bda3742dc58f3862f20">find_last_not_of</a>, <a href="#aef1226ed87e22d9ca9bfd8d2876c87ff">find_last_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#abf9183145a865f67edbedc0b24767fd1">llvm::sys::unicode::findSyllable</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#abbad376da1ca0cfd01c2e5effa9fad42">fixupIndexV4</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aec2829b5961eb9e3db39ab8340a361dd">fixupIndexV5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#ab64ede9b347ffd8eb32ed5e05f2520f4">llvm::json::fixUTF8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ae25b1e577bcd72ebc8b84b83aca02662">for</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp/#a6234057413147a09e2c1a0301ed7d452">formatPax</a>, <a href="/web-llvm/docs/api/classes/llvm/errordiagnostic/#aef72f56d78c257c18bf803045c76eb19">llvm::ErrorDiagnostic::get</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab9178a079b54667289f598db5b052ade">llvm::APInt::getBitsNeeded</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode/#a8f6028cdd89adeb15d6755814af79718">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getBodyContent</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a37b7e51dcb0e1efd0a84eb6398fd6301">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a36361ab61c92cc509c46bcc75b8dd34a">llvm::objcopy::elf::IHexRecord::getChecksum</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a367c0fd240000e247269dee3f2db8d7f">llvm::ARMTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a36633fb5c5538d177823d2dbe18458a6">llvm::AVRTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#a00fc80b3fa328fbe28fd9c3e7c336049">llvm::BPFTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a1fe5332b6f233790067eae16a9f88847">llvm::HexagonTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#a0d3c5019618fbdd5dbe8f321aa4e9967">llvm::M68kTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#addbf547ea90bdc1d1e496461455cdc06">llvm::MSP430TargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a0aaad9f7863f88d9aed611bf5f1c92a5">llvm::NVPTXTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a97e1f4e021dcba5a7795f823781e04df">llvm::PPCTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aca527d26f925265f5d193625eeb7bf0c">llvm::RISCVTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4cc2e446c8b94f69ff81fd22efc5d630">llvm::SITargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a2c5a958743bc5a86564032ba9a3aaa58">llvm::SparcTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a9701afa66d8ab97582acbffe33ca3e96">llvm::SystemZTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#afa53b350dc3624841e65fbb4a7011e91">llvm::VETargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a370d811aff2e392f420421995d439701">llvm::X86TargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a4f4aafb669c7b8966f8d921d0c8970ba">llvm::XtensaTargetLowering::getConstraintType</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a83adaf6fa27a4eb8cd83ab05b0e7908b">llvm::LTOModule::getDependentLibrary</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a84ea0567e15790f68c421dada011ec5f">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/nonrelocatablestringpool/#a3f09cd502a02a7f167d302f5bdde88e8">llvm::NonRelocatableStringpool::getEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a85dc884f90867e8bd3fc2f4839de6fdc">getErrorForInvalidExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e54b20745d63f337766efd74f06c5c8">llvm::getFuncNameWithoutPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/srecord/#a8a3e8a37182f3d235fba5f02768ce39a">llvm::objcopy::elf::SRecord::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d440404da44b3480e71ac2793976daf">llvm::HexagonInstrInfo::getInlineAsmLength</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2543fc561fd405e07d0d993a7854b34f">llvm::ARMTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a12fc0d82abf1a7842d4295464c88a4e8">llvm::RISCVTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac00b359e5af562d4db70ff852b38a7e">llvm::SystemZTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#a24660608cb7d9de914c25457314ce881">llvm::MDString::getLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a8da8a8e7960a91583ad18b42ecbbadeb">getMemBufferCopyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-sym-impl/#aaba364194724cae8698514b1a4a09f29">llvm::object::Elf_Sym_Impl&lt; ELFT &gt;::getName</a>, <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#aac246b383c0888833a23c78a0399a3e8">llvm::opt::OptTable::Info::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4cb6ea02c3dec9abe04c03e501c60f75">llvm::WritableMemoryBuffer::getNewUninitMemBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac52de24a1dd7695de94261e6ab8bb457">llvm::getObjCNamesIfSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/basic-parser-impl/#abcd302380d7f7f1143da20a56b23cdec">llvm::cl::basic_parser_impl::getOptionWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a55a39962245dd2e0938194dd3b4438e5">llvm::OpenMPIRBuilder::getOrCreateSrcLocStr</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a33efdfc01aaf654147da9f8c05f7706d">llvm::opt::ArgList::GetOrMakeJoinedArgString</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a024faa768c9d7b624a68980113f92693">llvm::Triple::getOSVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a1dee83379cd715e24ccdec554331a3cf">llvm::object::BigArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ae36dfcf0bacb4009b75fb2323aba6869">llvm::ARMTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a27c6ef6dacc842737370d22c1f7ed946">llvm::AVRTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#aeb5e73aa86ef5c3747a4fa348274ad20">llvm::BPFTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ad1de76d884688c0714045295511132af">llvm::HexagonTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#af08f3cc8369f10594ea18265dde0cab7">llvm::LanaiTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#afd1e3e4aa43dd55aaf713d32f108a3de">llvm::M68kTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a17109faa1b23afe706771effb725d9fb">llvm::MSP430TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ab18a78c277667a151b0cb707c7e80a02">llvm::NVPTXTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#add923d3128dce4cad95ce5ad642f6946">llvm::PPCTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7ade77bdee8e8fe0f6694d0ef8fda0ad">llvm::RISCVTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a299e5debf3d108b71fc6642ecd31e5e7">llvm::SparcTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a8b056a961f0931f4e64f0bddf07ba784">llvm::SystemZTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a04b839fdbef86703e2716838602c37aa">llvm::VETargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7a7237cd5cb35f9159b32a96f4b14541">llvm::X86TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ae09e10149c0fdd82a96ee9252d48354f">llvm::XtensaTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ae97e9ff61c444a8de25aeee6c09ca4e8">llvm::logicalview::getScopedName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a1b21b0b6b92569afb3b677c440ecb3b6">llvm::object::ELFFile&lt; ELFT &gt;::getSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#af0c6e225cf80ae36a9994bd1e79e8655">llvm::object::MachOObjectFile::getSectionSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#ac236558198da971873e571fa38d2b58a">llvm::AMDGPU::Exp::getTgtId</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a3d2c6d71f70d0e607257e6608872884e">getVarName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a6d7f36df9f1e78161aa1117443ec74e1">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/globalhash/#aa6cde89f0c5b372e3d112038e9dbd7e4">llvm::CodeViewYAML::GlobalHash::GlobalHash</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/gsistreambuilder-cpp/#ad8de58e5ee26f7e8a2a509355b0156f4">gsiRecordCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#af3e1bca92860141baaad0a536334d09f">llvm::object::MachOObjectFile::guessLibraryShortName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a21de2c5fb30965f2300f1e49f791c915">HandlePrefixedOrGroupedOption</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9918786a0f26fa3b2f43f2a0fe626f7a">llvm::handleSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#add5a775ece6c949eb80021abd7f49bc8">llvm::jitlink::identifyELFSectionStartAndEndSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#afee996fb446b6f03d652d052d97cf0a5">llvm::jitlink::identifyMachOSectionStartAndEndSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/object/directx/signature/#a8f7cfbb475d2b81f3b1c99bb5e74e53d">llvm::object::DirectX::Signature::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugstringtablesubsection/#ab9c8e8adf41209bcb76980c73fc419c3">llvm::codeview::DebugStringTableSubsection::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a068e377306e2029f1a5e24504c1f9cb7">isAsmComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a6ce84fd8aaeba029e2282946d6849256">isImmConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#aa74c2b313cfce997872aafabddf9866c">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::isLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6abe01777169c2216339a59d84bf3999">llvm::yaml::isNumeric</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a385765e73480a0f2d49dcc84a8fb70da">llvm::json::isUTF8</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga515bb8a9dede000b935e77958f35a4cf">LLVMGetDebugLocDirectory</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga46f93df14e032eacb6cc772e0a9a03ed">LLVMGetDebugLocFilename</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga638cf10ec868576e2a3be5a17d0ae39b">LLVMGetNamedMetadataName</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ae071c2a56ff28186d5476e562811b2f7">lookupLLVMIntrinsicByName</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#adb4ff7051f9fd7cfa91a1b20be1ac880">llvm::ARMTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#ac81e19ad39432150ba023a5d0d4a9d03">llvm::AVRTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#acb1a5b7cd343c725179259bb749f4257">llvm::LanaiTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#a12a4baec6fb389a927821d9ae85bb75e">llvm::M68kTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6e231b2a711b732f0508170edd8d6492">llvm::NVPTXTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a46ae06ee635d7e06d852c36093a4d20e">llvm::PPCTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac77a28c2acd753d94ba0342ebccb58a7">llvm::RISCVTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af4eec9eb2d2c80156afb3788f2361f14">llvm::SparcTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#acacf32699b860563db81e48146e1efe5">llvm::SystemZTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ade4062a36853bbacfea3d28b1ae76bf5">llvm::XtensaTargetLowering::LowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#adaff9002688c9185afc9e8b0e2a46f88">llvm::InlineAsmLowering::lowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/#a66ced5c57cafe11823df6917a866b17f">llvm::object::MachOUniversalBinary::MachOUniversalBinary</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a47366639c363a94f62304e26e09cfb18">anonymous{StandardInstrumentations.cpp}::makeHTMLReady</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a5893f33295c921df5928e5ab9feb90cc">llvm::opt::DerivedArgList::MakeJoinedArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp/#aee6196bb67ae710bbbd44101ea42fc62">mapNameAndUniqueName</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a23cdde8b9bdd40fd4a93d3635ca77dc6">llvm::Pattern::match</a>, <a href="/web-llvm/docs/api/structs/prefixmatcher/#a06d7229c302f7f9a6e42ad1afdc957c9">PrefixMatcher::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#afcc4cdfb302bc22d1b9cdca6a419f7b7">maybeLexIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a81dc0e46445de327a0956a30e6fc0662">maybeLexIndexAndName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a34f0a3b30959de2e7847c340c2b0fea2">maybeLexIRBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#ad97f43f2c733ae0b0506f078fb2768e0">maybeLexIRValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a95bd4c442d09906ba3a98a436150d637">maybeLexMCSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#aeb41fb2d4d98f026a60d1504d92b5a8c">maybeLexSubRegisterIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a21a44946d964a5e69dfa745bb1e9eabd">operator new</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a0db487cbf8c154e299a79baa79fde1ca">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a9b9d8d22a94c1862520178099d37c76e">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aee5d0f05688dce3f38e3c495744d49e8">optimizeMemCmpVarSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe/#a4f2d81fc8d21674863d5a753df3eed54">llvm::DWARFDebugFrame::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/object/directx/psvruntimeinfo/#ac30f90a499bf2baa821b2838a784b86b">llvm::object::DirectX::PSVRuntimeInfo::parse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f5ff058df930ce88aba780fa5191562">llvm::parseAnalysisUtilityPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a594f615f5a0025d4f0c92e27feb9d65d">llvm::yaml::parseBool</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a4f539d580f110fc7b26cd99ae4b09abe">parseBraceExpansions</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#ac44851c2ceedf8a3136d31773e0f20e2">llvm::RISCVISAInfo::parseFeatures</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#adcb372f00f2b01dc20f3567b2eb97be3">parseHeader</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a89eeee4c3ec5d281810e8ac7572ddee4">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1119c30ad17d23efa29bf5593774867d">anonymous{MIParser.cpp}::MIParser::parseLowLevelType</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#ac279fb04abf32461c56ca95dab29e0c4">parseMagic</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp/#af6e9ec4d94b9ce3ac8849a43fc579aaf">parseMaybeMangledName</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abbd69ebe5f468b51fd6fd8122e605a78">parsePredicateRegAsConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#a461ad47a3815838631b7aec404b99d21">parseRefinementStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad5d1fdc8afad445839bca3e15c7ba4bc">parseRegisterNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a488ef72cdaf48278d8a1117a6833bad2">parseSegmentLoadCommand</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a307619afda1e993b5ab00f907fb103b9">parseStrTab</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a7f3ee08c28f1f56632e9b58a7e90a813">parseStrTabSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a6fc763bfb813e4442ede4201150335d7">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSwizzleBitmaskPerm</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a96f48f9a5690ef01b9d2574472e1f7e2">anonymous{MIParser.cpp}::MIParser::parseTypedImmediateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a8eb3d9b91beb14411cbb1c3957c5cd49">parseVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasmstreamer-cpp/#a0cfb229540a44ffdd406ca12e441fd47">PrintCFIEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#acae182b4c4d76e0489cde49f97f4be7f">llvm::cl::Option::printEnumValHelpStr</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3331028c9eef66f4022ac3efa310af7d">llvm::Pattern::printFuzzyMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a7c44bc839272e942aa1a7c622eb9affb">llvm::cl::generic_parser_base::printGenericOptionDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackend-cpp/#a5f10e2bc9876065234ead6b2a02f8af5">printLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5d394830d4143542278afee43f527b48">printNoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a84230421edc594e09adc8a9a743823de">llvm::cl::generic_parser_base::printOptionInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a9d20e2079dcd9a868d4b3af67510647b">printSourceLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/#a7d852659ea6c0a8e12cf0c8d5e8d2e16">llvm::irsymtab::readBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a10b27eac23635b8f40370fe8a4d19967">readCoverageMappingData</a>, <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader/#a7e1679b2628896a1b7e2299c92776503">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readFunctionRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#ab9cbc0396671b685858c523ed763e724">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::reconstituteName</a>, <a href="/web-llvm/docs/api/structs/llvm/lessrecordregister/recordparts/#ab6f58b67225aaf63ec2aeee94dd053f4">llvm::LessRecordRegister::RecordParts::RecordParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#af426cbaa47678fc354ad421fb67e180e">llvm::sys::path::relative_path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a4a9c60caa200d23d5e4f12b24d4c8877">llvm::object::replace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1feb0e6007474c599ccfed65dad667c0">llvm::sys::path::replace_extension</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb31f2db6f0fe5eaa5b28464141223aa">llvm::sys::path::replace_path_prefix</a>, <a href="/web-llvm/docs/api/classes/llvm/rewritebuffer/#af4da15ad7c70b2c9ac934adf213819f7">llvm::RewriteBuffer::ReplaceText</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66fc8969d714a36fb8b4918753d1b973">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a2766ba305c6868870f3c79a2d571e982">llvm::logicalview::LVElement::resolveFullname</a>, <a href="#aba4f98b846a8b05965f39ca3a5c33fd2">rfind_insensitive</a>, <a href="#a56e7e0bebc570bc6814cdefd1f2ecda3">rfind_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a7a4a4089f8f04bc4d76b68399bdb6099">llvm::RISCVMachineFunctionInfo::RISCVMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-path-cpp-/#adcc7a3ee32e009943363aac6387302cb">anonymous{Path.cpp}::root_dir_start</a>, <a href="#aca46fb04897a97747c13d75a06f1215a">rsplit</a>, <a href="/web-llvm/docs/api/classes/llvm/stringsaver/#aab5ad8c5b3081716904f28dbb1979daf">llvm::StringSaver::save</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section/#aa23e563fc1b4cb6192ce8ea87e0154df">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Section</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/segment/#a483c24f3e678c049cf305bc40281fb08">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Segment</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-df914a78aa74437406828e15b40ba1b2/#a37399dc7cab3f63caf490b1a59fdc832">llvm::orc::shared::SPSSerializationTraits&lt; SPSString, StringRef &gt;::serialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-df914a78aa74437406828e15b40ba1b2/#ac7b746d59c1184f97ddc55a2d76152de">llvm::orc::shared::SPSSerializationTraits&lt; SPSString, StringRef &gt;::size</a>, <a href="#af0284e4c41c0e09c0bc4767bc77a899d">split</a>, <a href="#accc1b9e00e08cff2c9beb3059efa4200">split</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a>, <a href="#a343b6c58108519aca196bb54b1d1a6ef">starts_with_insensitive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a263bac5d85adb87956f47116b8fd5b2a">llvm::sys::unicode::startsWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1d074d016ff4ab25b0d504bf70a89059">llvm::sys::path::stem</a>, <a href="#af7220b1d3bfd1095940206fa563fdb1f">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>, <a href="/web-llvm/docs/api/classes/llvm/stringattributeimpl/#ad3ad8ac9b5c1d0ee83844044220d691c">llvm::StringAttributeImpl::totalSizeToAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a66ab4e2404f4eed28fd60cc29a7053c2">llvm::Twine::Twine</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#aba6d9549c0ddfa25919915044a81eaf3">llvm::Twine::Twine</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeserver2record/#af76800ba0d52842f185566beebef5be2">llvm::codeview::TypeServer2Record::TypeServer2Record</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a36314b2982eff94abe0b78ad9c97f53f">updateLoadCommandPayloadString</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#afcfed892d87764504587749693efe357">updateSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a438f99943621d64eb8920e5075719b36">upgradeLoopTag</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobjectsection/#a33c62d0d0c29c96b7b48d9e416d655e8">llvm::orc::ELFDebugObjectSection&lt; ELFT &gt;::validateInBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#a5188e82473da31b6460f80c0612b4d79">llvm::DWARFVerifier::verifyDebugStrOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ae9aeda1f1736cdf67f11ea6f1c99b107">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a78b45ebf4772364c848d6aedf38fd199">llvm::object::WasmObjectFile::WasmObjectFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp/#a07eccafe60da5abc8c63d630c9dcb28f">wordsOfString</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/exprlinearizer/#ae355c14dc0ef26a44f2f296d9e4ced0f">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ExprLinearizer::write</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/exprlinearizer/#a4b04704fe7d58d36b132376c5ad72bfe">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ExprLinearizer::write</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer/#aa3df0d1e99ef22c7868a727016afd661">llvm::msgpack::Writer::write</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-xcoffemitter-cpp-/#a85a0cac85a17a54339c7d5f78ae8d608">anonymous{XCOFFEmitter.cpp}::writeName</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovprofiler/#a5f0fe7fdf331104cd569220040c1cc79">anonymous{GCOVProfiling.cpp}::GCOVProfiler::writeString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f7d4f36e40ebd1e64d3c802976e7225">llvm::writeStringsAndOffsets</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ace523ea68fd49787987759de81452913">llvm::yaml::yaml2archive</a>.</p>

</div>
</div>

### str {#a223dd14e7d12bc5cea01889b972a98b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::StringRef::str ()</td>
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

<p>str - Get the contents as an std::string.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5e419b9328977a480fda42c789b77237">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::addExplicitComment</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#a8328d3e20eac36fdb0b50d0192052c89">llvm::vfs::InMemoryFileSystem::addHardLink</a>, <a href="/web-llvm/docs/api/classes/llvm/dcdata/#a18525952029405e647d86b0697719a8e">llvm::DCData::addSuccessorLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffdisplaygraph/#ac6115bcaadb80250c0f7c81a715d68a2">anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::attribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78b74816ecfd86997bf31b5bc2eb0cd1">llvm::cacheAnnotationFromMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a99fbec7515ca1c665315334c1a67d3a5">checkOperandCount</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiff/#a780f8122d2097c8676cf5749d4765ebc">anonymous{StandardInstrumentations.cpp}::DotCfgDiff::colourize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#ab79e380b2ff4d4653bc9a766e1a59220">anonymous{MachineOutliner.cpp}::MachineOutliner::computeAndPublishHashSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoreader-cpp/#afc82faca788f75fcf0a8f60a406342ba">constructSymbolEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiff/#a3fa9750e84e933fde1239fbf5da2a81f">anonymous{StandardInstrumentations.cpp}::DotCfgDiff::createDisplayGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#afb851cd69bea258a1020b268d3de3abd">llvm::Hexagon_MC::createHexagonMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/macho/#ad23f6403620ffb61f8c0e1f006f6ea66">llvm::objcopy::macho::executeObjcopyOnBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/macho/#af0902234f18e67e03ce4b3d4d8a6a273">llvm::objcopy::macho::executeObjcopyOnMachOUniversalBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a301ba38f5a267f3cf123d6a9f551e3fd">llvm::object::MachOObjectFile::findDsymObjectMembers</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a19fc4c64b801bb8ba465fdede95e7ca3">findSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation/#a7ceb314d2d75df52466e0f586da8bd42">llvm::DiagnosticLocation::getAbsolutePath</a>, <a href="/web-llvm/docs/api/classes/llvm/recordkeeper/#aee91ed23b398230bf5943153cab67dc7">llvm::RecordKeeper::getAllDerivedDefinitions</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ae6bcf159d6ccb3adb4f7409e3adbbb37">llvm::DWARFFormValue::getAsCString</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bfi-detail/#a608965289792ad2d62922c506cf7ea40">llvm::bfi_detail::getBlockName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesourcefile/#a16a32a8230aa939c5aa6b0a8e7adbc2c">llvm::pdb::NativeSourceFile::getChecksum</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mccvdefrangefragment/#a6ac329b00989fb4830246ea923755597">llvm::MCCVDefRangeFragment::getFixedSizePortion</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-55c8cb82503f51812ad190e425a6fd3d/#a33c6f6eb06efcdf1daf21bc77c4b1a6f">llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getGraphName</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02f9563a016dafe7fbc78fcb1f76f101/#af2539ced6ca24d31e88f9b0217579a3e">llvm::DOTGraphTraits&lt; DOTFuncMSSAInfo * &gt;::getGraphName</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-41c48be9c9012afa1dbd1bc6b52e29f7/#a1e3ee7b871f1524057e9d810810771b2">llvm::DOTGraphTraits&lt; DOTMachineFuncInfo * &gt;::getGraphName</a>, <a href="/web-llvm/docs/api/files/lib/lib/windowsdriver/msvcpaths-cpp/#aceedb180a9ae58c316577d97c5850392">getHighestNumericTupleInDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/file/#a68491f4d2058a92d43e0ffad1c6e14bb">llvm::vfs::File::getName</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-8e3d49d8257628f3fde0f02587f68f13/#ad84c5f2b4d317dc0213d926f5bb71e1e">llvm::DOTGraphTraits&lt; AttributorCallGraph * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a59192c42d4cbf804fbcc1deff8edb614">llvm::SDNode::getOperationName</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a388b3ce412f145bfac051690e8ef5596">llvm::getPGOFuncName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a0c85406f393901169b49e3d7a27527e0">anonymous{DlltoolDriver.cpp}::getPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland/#a09a8cb81d55088ca26ab8918686e217b">llvm::pdb::PDBSymbolCompiland::getSourceFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af3a94bd62230f4b9f99b54976663dfe8">llvm::ARMBaseTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a662d6e7c2aa31e6cac9212319d5349e3">llvm::CSKYTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#ab8055e9f4ea2a04ea313d2bcbfeab1a1">llvm::HexagonTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#ac0030767228d11167dfbe14d6c0d369b">llvm::LoongArchTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#acc8d7e573d75a9749702efefef9dc9a2">llvm::M68kTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#ae3a3a1690e01cf8d748aae7010f97687">llvm::MipsTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#afac904db14a3a55833a6293e7b3f222f">llvm::PPCTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a9009458436b2d38a2be9636993ab17e2">llvm::SparcTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ae65ab39e3d2d3b91527cb482c735aa">llvm::SystemZTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#ac5c975b4faf36ed756851c7a84d870ea">llvm::WebAssemblyTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#afcd734d7f68ecebea11378e93eb4b3be">llvm::XtensaTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a93d7a87f617e779623a45518a54db3eb">llvm::getSymbolicOperandMnemonic</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit/#a6d3d35230825470499dc48f866facb9a">llvm::dwarf_linker::classic::CompileUnit::getSysRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a0c84631008c6330d243843e3a2f3088c">llvm::Record::getValueAsBitOrUnset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a7cbd4ee56d74745611d1e1fe7dddf995">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget/#ae3337a826c5ca8fe41a7434b9d028943">llvm::M68kSubtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stdmapstringcustommappingtraitsimpl/#a559d43e1081ed898ddc0330e671c467b">llvm::yaml::StdMapStringCustomMappingTraitsImpl&lt; T &gt;::inputOne</a>, <a href="/web-llvm/docs/api/classes/llvm/lineeditor/#a850c7f0652c0d7273484a266093805dd">llvm::LineEditor::LineEditor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5f79fafdd96856687ba413f53b5c5b5">llvm::lookupPGONameFromMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aac0431719235a7ccda58a3df4894d130">llvm::SPIRV::lowerBuiltinType</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a47366639c363a94f62304e26e09cfb18">anonymous{StandardInstrumentations.cpp}::makeHTMLReady</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#a9dc80501043000f0bf75820ebfef69c4">mangleCoveragePath</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-454a2a2b1a47ec9d4c922b4916225c88/#a206ea5b904d2878c644bcf2c3ce32110">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD::NormalizedTBD</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a756f82cf24e75f443c6f032253d84dba">llvm::vfs::RedirectingFileSystem::openFileForRead</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/loadandlinkdynlibrary/#a4c217254abc9687da4cb2c93308f09a7">llvm::orc::LoadAndLinkDynLibrary::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owneddatasection/#abab1df49b546b59f7fdbf88bae70cda3">llvm::objcopy::elf::OwnedDataSection::OwnedDataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/parser-edddfc8ac2fbd3b9f3586735cc3422d2/#ac48c7ee0155765c5fe110fdcec1c30ce">llvm::cl::parser&lt; std::string &gt;::parse</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvextensionsparser/#a9c59e739efd5cf76e15f932543c272e3">llvm::SPIRVExtensionsParser::parse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#acefd73b7cd23506659faf02fd0957914">llvm::MachO::parseAliasList</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a4f539d580f110fc7b26cd99ae4b09abe">parseBraceExpansions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#ac44851c2ceedf8a3136d31773e0f20e2">llvm::RISCVISAInfo::parseFeatures</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a63d8077ac333f927273b1e014644cf89">anonymous{PassBuilder.cpp}::parseInternalizeGVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a21ef92ee94136c11407030eee4319eab">parseIRConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a18cb2b53fc5dbf94a7751fe179ac4ebc">anonymous{PassBuilder.cpp}::parseMemProfUsePassOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ad7e099354c93867323bca88df83c40b2">llvm::omp::prettifyFunctionName</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#a267ec91f5e1629ab79e6072f219ede70">llvm::dxil::ResourceBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobe/#a34098ed74b8701fdd984122019830dfa">llvm::MCDecodedPseudoProbe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#a85a9f3992a986b8eeb53734efe446bd0">llvm::dxil::ResourceBase::printKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a4357c88d173a81e047c07756ff94ada0">processConstantStringArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopearray/#a1ea12d2cfc5954a2e0e3770f62d6b127">llvm::logicalview::LVScopeArray::resolveExtra</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeverifier/#ac60402c1f75ca79798e4924098bd2066">llvm::PseudoProbeVerifier::runAfterPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ae0683ad49b9a0ccca8bd1c97987a8cf9">llvm::IRSimilarity::IRInstructionData::setCalleeName</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a83fc1b3aaadeeadd3b56de78e1415abb">llvm::MCContext::setCompilationDir</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3dadc94dc9df93690ba937226744797">llvm::setKCFIType</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/yamlvfswriter/#a6597908b15b2182cf75eb6ae0246b931">llvm::vfs::YAMLVFSWriter::setOverlayDir</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a7f03c0aad8c4b61df40be450082ed1b5">llvm::vfs::RedirectingFileSystem::setOverlayFileDir</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp/#ac93e3301780b206d83d8a7c768ce4992">setSocketAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#acb0214b30fb2b9e1d6e1cf6cc851b3e5">suffixed_name_or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95dd9937c9f80f95b741b20bb45e8a33">llvm::timeTraceProfilerWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a865e83348693ae24ada91964c6da76e4">llvm::symbolize::toJSON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a594febf895e59fe42257c1d2918c4f65">llvm::cgdata::warn</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#aea61050e03d2b5de9ef6621624e66122">writeListEntryAddress</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/cachepruning-cpp/#ab9f0418e712e930d9aa516ac08860491">writeTimestampFile</a>.</p>

</div>
</div>

### upper {#a4c884ed90d5d38e5d0546d61c4bebe3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string StringRef::upper ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the given ASCII string to uppercase.</p>

<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="#a46f643f1eb1939362c7dd79361bcbd0e">begin</a>, <a href="#a996c7ca3dd6843ba5d55a7c217770270">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a36f31bfe9e8b65522b0be4bdcec96e83">llvm::map_iterator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindingid/#a8326f8bdde6735a38601fb0e0ac78c11">anonymous{DXILPrettyPrinter.cpp}::FormatBindingID::format</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operator Overloads

### operator\[\] {#a3ae8d94051e57dabbf8ffabfcbc9063d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::StringRef::operator[] (size_t Index)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

### operator= {#acdf39985a87ec1d031fc9739fa559b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_same&lt; T, std::string &gt;::value, StringRef &gt; &amp; llvm::StringRef::operator= (T &amp;&amp; Str)</td>
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

<p>Disallow accidental assignment from a temporary std::string.</p>


<p>The declaration here is extra complicated so that <span class="doxyComputerOutput">stringRef = {}</span> and <span class="doxyComputerOutput">stringRef = "abc"</span> continue to select the move assignment operator.</p>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Type Conversions

### operator std::string\_view {#aed45f95729e679cb0c160456fe94602b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef::operator std::string_view ()</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## String Predicates

### ends\_with {#aca439bf65258d9d8d057812938b617c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::ends_with (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string ends with the given <span class="doxyComputerOutput">Suffix</span>.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#a996c7ca3dd6843ba5d55a7c217770270">end</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#a09f85524dd190f2649d7f584a2edcce3">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTypeTagName</a>, <a href="#a14180977794bfc2a37dbffeef3ca20de">consume_back</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a1e1e2695745252cae26a9843b4d8daa3">llvm::OpenMPIRBuilder::createTargetDeinit</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a7db9daa323dee69eb9ecc380ce6edae8">llvm::OpenMPIRBuilder::createTargetInit</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a89a6b95d310330e345c3aee6a07ffd96">llvm::X86TargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a6f1b0c312b24ebd6db62d9612a466f46">llvm::SmallString&lt; 0 &gt;::ends_with</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a5cd7a516996539c18628e51d9f628e07">llvm::sys::detail::getHostCPUNameForARM</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a33efdfc01aaf654147da9f8c05f7706d">llvm::opt::ArgList::GetOrMakeJoinedArgString</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a1dee83379cd715e24ccdec554331a3cf">llvm::object::BigArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a89316777d66cdd03ab0b656968165c68">llvm::AMDGPU::IsaInfo::getTargetIDSettingFromFeatureString</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a803c3a86a5b67ff8123a45143bbe7586">isDWOSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elfobjectwriter-cpp-/#a740acf4dce2922d79f8d78b15d1387bd">anonymous{ELFObjectWriter.cpp}::isDwoSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-wasmobjectwriter-cpp-/#af778cedd323207eed725ac7e6fdf5ce6">anonymous{WasmObjectWriter.cpp}::isDwoSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a7ae7754aaf6513bc0ea0bd5f457fe7cc">isDwoSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a628acae0faf51d588a48b94e037f40c9">llvm::MachO::isPrivateLibrary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f5ff058df930ce88aba780fa5191562">llvm::parseAnalysisUtilityPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac9eb980260cef7839596d3ca4d742905">llvm::ARM::parseArchEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a7e283edef71599b2ffccac2843fce5a0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abbd69ebe5f468b51fd6fd8122e605a78">parsePredicateRegAsConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ac784253baaaa3c7ac2760f3d9b71f1c1">parseSubArch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ad7e099354c93867323bca88df83c40b2">llvm::omp::prettifyFunctionName</a>.</p>

</div>
</div>

### ends\_with {#a393bbf5d4d82eaebfc257042c3a82ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::ends_with (char Suffix)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a5b6faabb08339ea1dd11e9d37a668634">back</a> and <a href="#a2dc80c585ad5882da8cae7b5968f7e74">empty</a>.</p>

</div>
</div>

### ends\_with\_insensitive {#ae57b9ee061903472c1cc9082849ed34e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StringRef::ends_with_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string ends with the given <span class="doxyComputerOutput">Suffix</span>, ignoring case.</p>

<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp/#a554122103a690fc7cdc6f99923dce8be">ascii_strncasecmp</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#a996c7ca3dd6843ba5d55a7c217770270">end</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="#ac5fd848165f133bf149f8f27618ce313">consume_back_insensitive</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/loadandlinkdynlibrary/#a4c217254abc9687da4cb2c93308f09a7">llvm::orc::LoadAndLinkDynLibrary::operator()</a>.</p>

</div>
</div>

### starts\_with {#a2cd8968ff703aaeb395dcd63f6805ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::starts_with (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string starts with the given <span class="doxyComputerOutput">Prefix</span>.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5e419b9328977a480fda42c789b77237">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::addExplicitComment</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#a09f85524dd190f2649d7f584a2edcce3">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTypeTagName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a8ad341cb471333b07af638089e1dc7c9">llvm::object::Archive::Archive</a>, <a href="/web-llvm/docs/api/classes/llvm/asmlexer/#a2cf3180e209a3079c3c08ab8c818a9ae">llvm::AsmLexer::AsmLexer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#a343d704d236717ce9399b288a622a222">llvm::ELFAttrs::attrTypeFromString</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuremoveincompatiblefunctions-cpp-/amdgpuremoveincompatiblefunctions/#a9910118e4db5bb56e348017ba1460553">anonymous{AMDGPURemoveIncompatibleFunctions.cpp}::AMDGPURemoveIncompatibleFunctions::checkFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#aa740dcfa0d271bee33ae7e65af71662d">llvm::objcopy::elf::Object::compressOrDecompressSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a725fe8674a09b1579039321d641118e4">computeTargetABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a28e75155ea06a5ad70d3a662be05e350">llvm::RISCVABI::computeTargetABI</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#afff545dbbc7e3d85c4e6d914200747db">llvm::object::Archive::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae465be28151991b2345f467899ddb5e5">llvm::remarks::createYAMLParserFromMeta</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a36c152217dc69b5295561b2f99c52c17">llvm::omp::deconstructOpenMPKernelName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a92c1412b091bd6433240e0d7d95c2a3a">doesIgnoreDataTypeSuffix</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#a848a2d90f798473878904dcbddfba506">anonymous{AMDGPULibFunc.cpp}::eatTerm</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a5718ec8f63e95fd6b47488b9e375fbb9">llvm::Attributor::emitRemark</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a361e84c7ad1bb42e35e8a7db774c6a54">llvm::Attributor::emitRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a17b7b6be8c77b055cf79259a4af7ff0c">llvm::ARMTargetStreamer::emitTargetAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetstreamer/#ad3e4f5bb59058be7d568e2505d04b830">llvm::NVPTXTargetStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a481e97810e8743a7c0f25a51dbcad8c1">llvm::ELFObjectWriter::executePostLayoutBinding</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a1933cc94d2453eb9f2cd131e7327ec18">llvm::AArch64::getArchExtFeature</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac905bca0319767a6f6590aa62145c2be">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getCPolKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e54b20745d63f337766efd74f06c5c8">llvm::getFuncNameWithoutPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#accca1ffcde97aed8658b3905915eb84c">llvm::object::getNameType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a33efdfc01aaf654147da9f8c05f7706d">llvm::opt::ArgList::GetOrMakeJoinedArgString</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a024faa768c9d7b624a68980113f92693">llvm::Triple::getOSVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#a4334e601f712be7fd456cd1c5b26e96e">getPointeeTypeByCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ae9f8d60c452f2f26ca84f0bde2b530ad">llvm::SPIRVTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a8b056a961f0931f4e64f0bddf07ba784">llvm::SystemZTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ae5ed3bb52c2c0b532692d33df8dd705f">llvm::TargetLoweringObjectFileELF::getSectionForMachineBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoobjectfile-cpp-/#ad6473b2753bdca7d12955749ed652b7c">anonymous{MachOObjectFile.cpp}::getSegmentContents</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a388e35e6191f5f51957c3024ef635190">llvm::yaml::Node::getVerbatimTag</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a56bb53e2d0b01c78c8c538f903fd45b8">llvm::MVT::getVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a9919c2ab68b72db8776ce21a276a6ba6">hasAnyUnrollPragma</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader/#a3312e664f5df1acd8f78ea8b824e7b5d">llvm::memprof::YAMLMemProfReader::hasFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#ac9720fa4fb8bcc62c98a125f0b09fe9e">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac33e274ca277cfe840f699acc1b8a814">llvm::HexagonSubtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#aa9588be24002d2f7603334d8dd1846e7">llvm::LTOModule::isBitcodeForTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armmnemonicsets/#ac90a4bbed7a48888b21439ce16b55541">anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::isCDEDualRegInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armmnemonicsets/#a2ab7539d76cfca5b4cbcabaf48d20979">anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::isCDEInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad59c456d26c1d5693b83be75c1b23576">llvm::orc::isCOFFInitializerSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizerbase/#a4bdb53614bf065ddc9a5517c445587be">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizerBase::isDebugSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#aa080c38d82f500daf23c736bba23b17b">isDebugSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#a00788ca1cb49affa89933d0eb01101da">llvm::objcopy::coff::isDebugSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#a4dba745db7f48a6b368292275bf556c8">llvm::objcopy::wasm::isDebugSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a7742a02ff9135c94e56122a80beefd9f">llvm::object::isDecorated</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armmnemonicsets/#a361ea7963e2fddb89e0eef0d164ef55e">anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::isITPredicableCDEInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ad82fa2803c170f1ec4d650cf675ac11e">llvm::objcopy::wasm::isLinkerSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6abe01777169c2216339a59d84bf3999">llvm::yaml::isNumeric</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a628acae0faf51d588a48b94e037f40c9">llvm::MachO::isPrivateLibrary</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symbolentry/#a4d7d7d589ddcfe74ece7aee10d38ba5d">llvm::objcopy::macho::SymbolEntry::isSwiftSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armmnemonicsets/#a0e2deb9763940058e9a33e4bea668968">anonymous{ARMAsmParser.cpp}::ARMMnemonicSets::isVPTPredicableCDEInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a1f67f9d068986121afe18f99677d1687">llvm::SPIRV::lookupBuiltinNameHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a368216c9c116e3f30d8dd352ce1370fc">llvm::makeFollowupLoopID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8a1ae2e1de53a840bee516d1f5bb173">llvm::makePostTransformationMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6ded20d42a05e6478238dcfd3caceede">matchAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp/#a4483fb95f4751170fa6aa139f143f02d">matchOption</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f5ff058df930ce88aba780fa5191562">llvm::parseAnalysisUtilityPasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ac9eb980260cef7839596d3ca4d742905">llvm::ARM::parseArchEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a721eb5bffb57cea96d7a9b45cbe302cf">parseARMArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a9249200d14424808c822103928fe7fdc">llvm::SPIRV::parseBuiltinTypeNameToTargetExtType</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#aa7b40dda7a09e0c055d6138b404d0789">llvm::DebugCounter::parseChunks</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a332d48815071fdb4e2e94e999c154559">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDimId</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a0e9209ef161dfa2b45ab9f122f2ada34">anonymous{PPCAsmParser.cpp}::PPCAsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#a605f317c5671abb87131f5dcb6b2fe4a">anonymous{X86AsmParser.cpp}::X86AsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a3390881f203f23dca9f40c151f89d581">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a89eeee4c3ec5d281810e8ac7572ddee4">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2de75d77a5ee094dabe819e4b5855a6a">anonymous{PassBuilder.cpp}::parseLowerAllowCheckPassOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp/#af6e9ec4d94b9ce3ac8849a43fc579aaf">parseMaybeMangledName</a>, <a href="/web-llvm/docs/api/structs/llvm/aarch64/extensionset/#a47d4274efc34b5d09e3d8142be273a11">llvm::AArch64::ExtensionSet::parseModifier</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abbd69ebe5f468b51fd6fd8122e605a78">parsePredicateRegAsConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ac784253baaaa3c7ac2760f3d9b71f1c1">parseSubArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ab0d2fab5845ea5a11a1a57775090aec7">llvm::MachO::parseSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp/#a407041f5d2ea26309c1f9071a724314e">parseThunkName</a>, <a href="/web-llvm/docs/api/structs/anonymous-armslshardening-cpp-/slsblrthunkinserter/#a4c1c2b4d7e1a18edf5b0fb0c26a1bb71">anonymous{ARMSLSHardening.cpp}::SLSBLRThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5cb8771722bfd8bcbdeb391b17e6cfd6">processGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffaarch64/#a9114640d8c0477c8c9c502e8acd7cbf7">llvm::RuntimeDyldCOFFAArch64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffi386/#a47afe575c279c175037d664bde7e53a3">llvm::RuntimeDyldCOFFI386::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#a200d4c53b00f55a8d0911279bf576c18">llvm::RuntimeDyldCOFFThumb::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a4a9c60caa200d23d5e4f12b24d4c8877">llvm::object::replace</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a0caf08c068a9900ddcabffcf9f004b41">replaceAndRemoveSections</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/thunkinserter/#a547880d64e46c0d922e0bb0f0d7f5fb9">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73f3f480c52fd84aac6182d798979181">llvm::runFuzzerOnInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a3093181fe818bf3fe03f72887de8943f">llvm::sampleprof::SampleContext::SampleContext</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession/#a10c66fa7ae2a9b589c8a2738661897ca">llvm::pdb::NativeSession::searchForPdb</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#ab64771f762bdb53411b08c38f9d7b125">llvm::HexagonTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a9174b74c91e38ef13386aaa81fa484f9">llvm::cl::Option::setArgStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a463056de56ab82cc6e2c50e5ccf17626">shouldCheckArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ab9e30dda46fe2b20cf00b33ee9efb3c4">llvm::SmallString&lt; 0 &gt;::starts_with</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dllimportdefinitiongenerator/#a28474a2103675aa30411c3cc01585b0c">llvm::orc::DLLImportDefinitionGenerator::tryToGenerate</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#aae5f020a66b7a61f16cf63e17fa31e56">anonymous{StructuralHash.cpp}::StructuralHashImpl::update</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a4a8b0267a862203c3082ed955abd326c">updateAndRemoveSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a438f99943621d64eb8920e5075719b36">upgradeLoopTag</a> and <a href="/web-llvm/docs/api/structs/anonymous-spirvregularizer-cpp-/spirvregularizer/#a3126f03fedf2204dffcef1c05dee06c2">anonymous{SPIRVRegularizer.cpp}::SPIRVRegularizer::visitCallInst</a>.</p>

</div>
</div>

### starts\_with {#a71ebff92f9ef18f3009f88457a09776d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::starts_with (char Prefix)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a2dc80c585ad5882da8cae7b5968f7e74">empty</a> and <a href="#a61364ca3a5ff90fb2aa0d5a371fd43f7">front</a>.</p>

</div>
</div>

### starts\_with\_insensitive {#a343b6c58108519aca196bb54b1d1a6ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StringRef::starts_with_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string starts with the given <span class="doxyComputerOutput">Prefix</span>, ignoring case.</p>

<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp/#a554122103a690fc7cdc6f99923dce8be">ascii_strncasecmp</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="#ae94101ab936805840acecc874e70c190">consume_front_insensitive</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp/#a4483fb95f4751170fa6aa139f143f02d">matchOption</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## String Searching

### contains {#a83a294111af6d4412163b209725ca556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::contains (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Other)</td>
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

<p>Return true if the given string is a substring of *this, and false otherwise.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#aab312a8386488873bac2eddfc67c22be">find</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#ab3006e90ba5c4717808c3c35e1a778a5">llvm::Hexagon_MC::addArchSubtarget</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a820bfb5af5692fdc662f2a2157d8830f">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::checkForP2AlignIfLoadStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#afb851cd69bea258a1020b268d3de3abd">llvm::Hexagon_MC::createHexagonMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5fdc8e2ed6d4f1c0f6936a0291ec496c">llvm::AsmPrinter::emitPCSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab25d01b38cf3d0b9e22fe06c673243d6">llvm::generateVectorLoadStoreInst</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ade97ab011dc19854c9886f2c6d8ecc66">llvm::Triple::getEnvironmentVersionString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#accca1ffcde97aed8658b3905915eb84c">llvm::object::getNameType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#adb7bfed2c40e61784a27f7a7ccb150a8">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getValueKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a7742a02ff9135c94e56122a80beefd9f">llvm::object::isDecorated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#ad772ba5923d08e11379f06cc8c3c5e4d">llvm::offloading::amdgpu::isImageCompatibleWithEnv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetobjectfile-cpp/#adfc4891114114529b51c8386e89110dc">isSmallDataSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a0db487cbf8c154e299a79baa79fde1ca">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a4f539d580f110fc7b26cd99ae4b09abe">parseBraceExpansions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a9249200d14424808c822103928fe7fdc">llvm::SPIRV::parseBuiltinTypeNameToTargetExtType</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecfgprinter-cpp-/machinecfgprinter/#acaeae56f20830134ab1bcad4eda8ec16">anonymous{MachineCFGPrinter.cpp}::MachineCFGPrinter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a147437aa3b97e99609ae28aa1ee2eb32">sanitizeFunctionName</a>.</p>

</div>
</div>

### contains {#a9d6a78cc34c1b0310fab4a21dd2fc02d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::contains (char C)</td>
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

<p>Return true if the given character is contained in *this, and false otherwise.</p>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a93b15a8c0022febbe39d17ab933737a8">find_first_of</a> and <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>.</p>

</div>
</div>

### contains\_insensitive {#a342b946b5a0944601f80994765e53feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::contains_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Other)</td>
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

<p>Return true if the given string is a substring of *this, and false otherwise.</p>

<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#abc37e42bcf44968ae55ddc8c69748150">find_insensitive</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>.</p>

</div>
</div>

### contains\_insensitive {#a412577d3213b59a5da2b380f2feed9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::contains_insensitive (char C)</td>
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

<p>Return true if the given character is contained in *this, and false otherwise.</p>

<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#abc37e42bcf44968ae55ddc8c69748150">find_insensitive</a> and <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>.</p>

</div>
</div>

### find {#aab312a8386488873bac2eddfc67c22be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringRef::find (char C, size_t From=0)</td>
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

<p>Search for the first character <span class="doxyComputerOutput">C</span> in the string.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the first occurrence of <span class="doxyComputerOutput">C</span>, or npos if not found.</p></dd>
</dl>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a77b750f0deb484099d9f4f3539bda353">checkLinkerOptCommand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a030478956c379ec2bb71550cb0526fb6">CommaSeparateAndAddOccurrence</a>, <a href="#a83a294111af6d4412163b209725ca556">contains</a>, <a href="#a797db79c8d98dcd992d5fe9a71ffe68c">count</a>, <a href="#a9202ca0a40ca22c6198342cf8b0dc050">detectEOL</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ab07e49a5499032dc8f97198892218853">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::EmitCommentsAndEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5fdc8e2ed6d4f1c0f6936a0291ec496c">llvm::AsmPrinter::emitPCSections</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerexpreval/#a83c754c0b8d462edcbfec5424e5a64ae">llvm::RuntimeDyldCheckerExprEval::evaluate</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a481e97810e8743a7c0f25a51dbcad8c1">llvm::ELFObjectWriter::executePostLayoutBinding</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a6be1163dc11ad30299eba8628e991a46">llvm::SmallString&lt; 0 &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a7238e22196b4867a29efb8136ce3e2d2">llvm::SmallString&lt; 0 &gt;::find</a>, <a href="#a93b15a8c0022febbe39d17ab933737a8">find_first_of</a>, <a href="/web-llvm/docs/api/classes/llvm/pgocontextualprofile/#a4e170cc734364539e4e88a9c2823d924">llvm::PGOContextualProfile::getFunctionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensatargetstreamer-cpp/#a0d30b7a632d76eb770508d5d280d3ed9">getLiteralSectionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac52de24a1dd7695de94261e6ab8bb457">llvm::getObjCNamesIfSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a990a2cc1b018140f8dde6e1a8ad42182">llvm::object::ArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ae6071096c441061cfc9f7b4cf8f4ec9e">anonymous{DlltoolDriver.cpp}::identifyImportName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a88d6a2d221777b8376bde5d860a219d1">llvm::isSpecialPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba7165df55c01bd2653b37a6e9f4a8ae">llvm::lookupBuiltin</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a6bb608aba526021fe280a23f84ee7754">anonymous{MasmParser.cpp}::MasmParser::lookUpField</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a23cdde8b9bdd40fd4a93d3635ca77dc6">llvm::Pattern::match</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a4f539d580f110fc7b26cd99ae4b09abe">parseBraceExpansions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a9249200d14424808c822103928fe7fdc">llvm::SPIRV::parseBuiltinTypeNameToTargetExtType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a336063ab4c85ca7260327f7c39a64492">llvm::SPIRV::parseBuiltinTypeStr</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a9d20e2079dcd9a868d4b3af67510647b">printSourceLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a4a9c60caa200d23d5e4f12b24d4c8877">llvm::object::replace</a>, <a href="#a7b0138ddc186a7cb5cfd04dde671220e">split</a>, <a href="#af0284e4c41c0e09c0bc4767bc77a899d">split</a>, <a href="#accc1b9e00e08cff2c9beb3059efa4200">split</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>.</p>

</div>
</div>

### find {#a82369bea2700347f68e1f43e30d2d47b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringRef::find (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, size_t From=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for the first string <span class="doxyComputerOutput">Str</span> in the string.</p>


<p>find - Search for the first string</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the first occurrence of <span class="doxyComputerOutput">Str</span>, or npos if not found.</p></dd>
</dl>


<ul class="doxyList ">
<li>Str in the string.</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>- The index of the first occurrence of</p>


<ul class="doxyList ">
<li>Str, or npos if not found.</li>
</ul>
</dd>
</dl>


<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### find\_first\_not\_of {#ae851887270f35d2a2670a79b9833d45b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::size_type StringRef::find_first_not_of (char C, size_t From=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the first character in the string that is not <span class="doxyComputerOutput">C</span> or npos if not found.</p>


<p>find_first_not_of - Find the first character in the string that is not</p>


<ul class="doxyList ">
<li>C or npos if not found.</li>
</ul>

<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af9d527e5f895e2b6711438706bfc8edd">llvm::SmallString&lt; 0 &gt;::find_first_not_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#abedeac3aa58a765a33e8a146a8d86e4d">llvm::SmallString&lt; 0 &gt;::find_first_not_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6abe01777169c2216339a59d84bf3999">llvm::yaml::isNumeric</a>, <a href="#a8265efd805e4ce0c9d3c18e78194324c">ltrim</a>, <a href="#acd2e33f03956821cbf94c4cd5da01bdd">ltrim</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6ded20d42a05e6478238dcfd3caceede">matchAsm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a112b0124ddda89fd041dbdbc53016275">llvm::dwarf_linker::parseDebugTableName</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>.</p>

</div>
</div>

### find\_first\_not\_of {#a18de63f444e95dfff81803a482ab6eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::size_type StringRef::find_first_not_of (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars, size_t From=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the first character in the string that is not in the string <span class="doxyComputerOutput">Chars</span>, or npos if not found.</p>


<p>find_first_not_of - Find the first character in the string that is not in the string</p>


<p>Complexity: O(<a href="#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<ul class="doxyList ">
<li>Chars, or npos if not found.</li>
</ul>

<p>Note: O(<a href="#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### find\_first\_of {#a93b15a8c0022febbe39d17ab933737a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringRef::find_first_of (char C, size_t From=0)</td>
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

<p>Find the first character in the string that is <span class="doxyComputerOutput">C</span>, or npos if not found.</p>


<p>Same as find.</p>


<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#aab312a8386488873bac2eddfc67c22be">find</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5e419b9328977a480fda42c789b77237">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::addExplicitComment</a>, <a href="#a9d6a78cc34c1b0310fab4a21dd2fc02d">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/globpattern/#ad853cb6a2e5807ae5006c0f5ba1e7b49">llvm::GlobPattern::create</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ae6c79a45fa092aef544c31e4d0eccabf">llvm::SmallString&lt; 0 &gt;::find_first_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a1b57dd47c8dd51ab940377d19626dd56">llvm::SmallString&lt; 0 &gt;::find_first_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a884a65fc47e7cf521d37505e1548e9ca">llvm::generateConvertInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a2407bfb7839e9f051cd446d587f978be">llvm::sys::printArg</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a1cbc5251f13ad42510760ed61c71e874">llvm::BinaryStreamReader::readCString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-path-cpp-/#adcc7a3ee32e009943363aac6387302cb">anonymous{Path.cpp}::root_dir_start</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a>.</p>

</div>
</div>

### find\_first\_of {#af38cc29d28845d48d8423918d8910d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::size_type StringRef::find_first_of (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars, size_t From=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the first character in the string that is in <span class="doxyComputerOutput">Chars</span>, or npos if not found.</p>


<p>find_first_of - Find the first character in the string that is in</p>


<p>Complexity: O(<a href="#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<ul class="doxyList ">
<li>Chars, or npos if not found.</li>
</ul>

<p>Note: O(<a href="#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### find\_if {#a24d07ee06f50c285b723a97222619ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringRef::find_if (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(char)&gt; F, size_t From=0)</td>
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

<p>Search for the first character satisfying the predicate <span class="doxyComputerOutput">F</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the first character satisfying <span class="doxyComputerOutput">F</span> starting from <span class="doxyComputerOutput">From</span>, or npos if not found.</p></dd>
</dl>


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a3fb2867a1e9fa36e135d9ee4dffb0167">drop_front</a>, <a href="#a2dc80c585ad5882da8cae7b5968f7e74">empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a61364ca3a5ff90fb2aa0d5a371fd43f7">front</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="#a53315344f92e70843fb54b6b7769de67">drop_until</a>, <a href="#afe4ee2901ac2ae201e839a7972038a1c">find_if_not</a>, <a href="#abc37e42bcf44968ae55ddc8c69748150">find_insensitive</a> and <a href="#aa93bf2cc29b3a2ad5056bea30a373d52">take_until</a>.</p>

</div>
</div>

### find\_if\_not {#afe4ee2901ac2ae201e839a7972038a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringRef::find_if_not (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(char)&gt; F, size_t From=0)</td>
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

<p>Search for the first character not satisfying the predicate <span class="doxyComputerOutput">F</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the first character not satisfying <span class="doxyComputerOutput">F</span> starting from <span class="doxyComputerOutput">From</span>, or npos if not found.</p></dd>
</dl>


<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>.</p>


<p>Referenced by <a href="#adb414d662ce914329570f0ff92602336">drop_while</a> and <a href="#a34a27457ad5d68f631c788807c4ff52c">take_while</a>.</p>

</div>
</div>

### find\_insensitive {#abc37e42bcf44968ae55ddc8c69748150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringRef::find_insensitive (char C, size_t From=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for the first character <span class="doxyComputerOutput">C</span> in the string, ignoring case.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the first occurrence of <span class="doxyComputerOutput">C</span>, or npos if not found.</p></dd>
</dl>


<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>.</p>


<p>Referenced by <a href="#a412577d3213b59a5da2b380f2feed9a9">contains_insensitive</a>, <a href="#a342b946b5a0944601f80994765e53feb">contains_insensitive</a> and <a href="/web-llvm/docs/api/classes/llvm/pattern/#a23cdde8b9bdd40fd4a93d3635ca77dc6">llvm::Pattern::match</a>.</p>

</div>
</div>

### find\_insensitive {#a2fab98a15364352e9a7a48da307fde69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringRef::find_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, size_t From=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for the first string <span class="doxyComputerOutput">Str</span> in the string, ignoring case.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the first occurrence of <span class="doxyComputerOutput">Str</span>, or npos if not found.</p></dd>
</dl>


<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="#a25f1fd81f2132805676c82ab8ae0c109">substr</a>.</p>

</div>
</div>

### find\_last\_not\_of {#a035cf6768564ead852edfff8ca9c3b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::size_type StringRef::find_last_not_of (char C, size_t From=<a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the last character in the string that is not <span class="doxyComputerOutput">C</span>, or npos if not found.</p>


<p>find_last_not_of - Find the last character in the string that is not</p>


<ul class="doxyList ">
<li>C, or npos if not found.</li>
</ul>

<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a> and <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="#a9b52404a8d2877d3b32ebb5d1f5c72ff">rtrim</a> and <a href="#acf544fca0b0f46e00e4261bc925104e5">rtrim</a>.</p>

</div>
</div>

### find\_last\_not\_of {#a819cd72313f82bda3742dc58f3862f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::size_type StringRef::find_last_not_of (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars, size_t From=<a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the last character in the string that is not in <span class="doxyComputerOutput">Chars</span>, or npos if not found.</p>


<p>find_last_not_of - Find the last character in the string that is not in</p>


<p>Complexity: O(<a href="#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<ul class="doxyList ">
<li>Chars, or npos if not found.</li>
</ul>

<p>Note: O(<a href="#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### find\_last\_of {#a7a7c222449f3208a532168c90bfb654d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringRef::find_last_of (char C, size_t From=<a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
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

<p>Find the last character in the string that is <span class="doxyComputerOutput">C</span>, or npos if not found.</p>

<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a> and <a href="#a97d45ce069c1a09ca84672df63acf096">rfind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ad1056825d31bf187d0be430c51aac281">llvm::sys::path::extension</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-path-cpp-/#aa97df12f81288d1870f96204ed9b65c0">anonymous{Path.cpp}::filename_pos</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a4094843dd73069778eb645198365211c">llvm::SmallString&lt; 0 &gt;::find_last_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a3d61e42dd3a2c362b5b81e8a49e2db72">llvm::SmallString&lt; 0 &gt;::find_last_of</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a494d75fe0bc43f9c6b8821f983205649">llvm::SourceMgr::getLineAndColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a388e35e6191f5f51957c3024ef635190">llvm::yaml::Node::getVerbatimTag</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1d074d016ff4ab25b0d504bf70a89059">llvm::sys::path::stem</a>.</p>

</div>
</div>

### find\_last\_of {#aef1226ed87e22d9ca9bfd8d2876c87ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::size_type StringRef::find_last_of (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars, size_t From=<a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the last character in the string that is in <span class="doxyComputerOutput">C</span>, or npos if not found.</p>


<p>find_last_of - Find the last character in the string that is in</p>


<p>Complexity: O(<a href="#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<ul class="doxyList ">
<li>C, or npos if not found.</li>
</ul>

<p>Note: O(<a href="#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### rfind {#a97d45ce069c1a09ca84672df63acf096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringRef::rfind (char C, size_t From=<a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
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

<p>Search for the last character <span class="doxyComputerOutput">C</span> in the string.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the last occurrence of <span class="doxyComputerOutput">C</span>, or npos if not found.</p></dd>
</dl>


<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a36c152217dc69b5295561b2f99c52c17">llvm::omp::deconstructOpenMPKernelName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfyaml/#ac84f1cd7e37d227e700d6a69398fd3c1">llvm::ELFYAML::dropUniqueSuffix</a>, <a href="#a7a7c222449f3208a532168c90bfb654d">find_last_of</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a37b7e51dcb0e1efd0a84eb6398fd6301">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvelement-cpp/#a0a0a5465a81f37e6f33be77ca0cc85e4">getStringIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#af3e1bca92860141baaad0a536334d09f">llvm::object::MachOObjectFile::guessLibraryShortName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a1f67f9d068986121afe18f99677d1687">llvm::SPIRV::lookupBuiltinNameHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a80b83aa3cd0b6442a32176b58205d98f">llvm::SmallString&lt; 0 &gt;::rfind</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a0941cbbd2c07ccf0158dbe7db2885674">llvm::SmallString&lt; 0 &gt;::rfind</a> and <a href="#aca46fb04897a97747c13d75a06f1215a">rsplit</a>.</p>

</div>
</div>

### rfind {#af90e5d9d8d99f68f9d4616bd026b0eab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringRef::rfind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for the last string <span class="doxyComputerOutput">Str</span> in the string.</p>


<p>rfind - Search for the last string</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the last occurrence of <span class="doxyComputerOutput">Str</span>, or npos if not found.</p></dd>
</dl>


<ul class="doxyList ">
<li>Str in the string.</li>
</ul>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>- The index of the last occurrence of</p>


<ul class="doxyList ">
<li>Str, or npos if not found.</li>
</ul>
</dd>
</dl>


<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>Reference <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### rfind\_insensitive {#aba4f98b846a8b05965f39ca3a5c33fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringRef::rfind_insensitive (char C, size_t From=<a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for the last character <span class="doxyComputerOutput">C</span> in the string, ignoring case.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the last occurrence of <span class="doxyComputerOutput">C</span>, or npos if not found.</p></dd>
</dl>


<p>Declaration at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a> and <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>.</p>

</div>
</div>

### rfind\_insensitive {#a56e7e0bebc570bc6814cdefd1f2ecda3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringRef::rfind_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for the last string <span class="doxyComputerOutput">Str</span> in the string, ignoring case.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the last occurrence of <span class="doxyComputerOutput">Str</span>, or npos if not found.</p></dd>
</dl>


<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="#ae46058c90a3c703357331a6501b32f1c">equals_insensitive</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="#a25f1fd81f2132805676c82ab8ae0c109">substr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Helpful Algorithms

### consumeInteger {#a1643e7698ddbfd40fbd374a85f015846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::consumeInteger (unsigned Radix, T &amp; Result)</td>
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

<p>Parse the current string as an integer of the specified radix.</p>


<p>If <span class="doxyComputerOutput">Radix</span> is specified as zero, this does radix autosensing using extended C rules: 0 is octal, 0x is hex, 0b is binary.</p>


<p>If the string does not begin with a number of the specified radix, this returns true to signify the error. The string is considered erroneous if empty or if it overflows T. The portion of the string representing the discovered numeric value is removed from the beginning of the string.</p>


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aade9e36144bb117240c0d8324e0c5d6c">llvm::consumeSignedInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a559ce07c89729386c121ca32098cb0f9">llvm::consumeUnsignedInteger</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a068641b222182c6ca0412660993bf1fe">llvm::AMDGPUMachineFunction::AMDGPUMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac33e274ca277cfe840f699acc1b8a814">llvm::HexagonSubtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-ad322848578d151a36fcda7ed451f767/#a7d87092d92555db97b2196e799b6d70e">llvm::yaml::ScalarTraits&lt; FrameIndex &gt;::input</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a93e1f93d537243a559abd940ec1b6f53">parseReplacementItem</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a41f2994ff7727a6749e0002ba3852a9a">llvm::AMDGPUPALMetadata::setFromString</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af63d1fba23bc323d27c9dc50313698eb">llvm::SIMachineFunctionInfo::SIMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1381cfa5d5d20b2c0de03ce8f211c1cf">anonymous{VFABIDemangler.cpp}::tryParseAlign</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a856e22af4413a5ea9df66d623f35b824">anonymous{VFABIDemangler.cpp}::tryParseCompileTimeLinearToken</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a4c267f75d0c944ac84dff96f8a4779f3">anonymous{VFABIDemangler.cpp}::tryParseLinearTokenWithRuntimeStep</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a14373b1995a870811ec0b24e8c7bb274">anonymous{VFABIDemangler.cpp}::tryParseVLEN</a>.</p>

</div>
</div>

### consumeInteger {#a8628d3c93731ec5ac11a4ca9dbc67dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StringRef::consumeInteger (unsigned Radix, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the current string as an integer of the specified <span class="doxyComputerOutput">Radix</span>.</p>


<p>If <span class="doxyComputerOutput">Radix</span> is specified as zero, this does radix autosensing using extended C rules: 0 is octal, 0x is hex, 0b is binary.</p>


<p>If the string does not begin with a number of the specified radix, this returns true to signify the error. The string is considered erroneous if empty. The portion of the string representing the discovered numeric value is removed from the beginning of the string.</p>


<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp/#a4183ffbb055bd5689d234921349a02a8">GetAutoSenseRadix</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### count {#ac2c31b7b3c778d12aa176f9253511f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringRef::count (char C)</td>
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

<p>Return the number of occurrences of <span class="doxyComputerOutput">C</span> in the string.</p>

<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac88d0051f2b3b1fa8501b4daeea7b1f5">llvm::SmallString&lt; 0 &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a791bf972fa4fd4d85e7398901b1ea0ec">llvm::SmallString&lt; 0 &gt;::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ad52342fdd467389643191fdac7abcd40">getGridValue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d440404da44b3480e71ac2793976daf">llvm::HexagonInstrInfo::getInlineAsmLength</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02f9563a016dafe7fbc78fcb1f76f101/#ae7114057f671ef14b2fbbb1aa29adfe5">llvm::DOTGraphTraits&lt; DOTFuncMSSAInfo * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9c3ed3171d9efe654f3a3a3f77e7db56/#a6215697818a46a18abcef5d8b0ef8ab7">llvm::yaml::MappingTraits&lt; Argument &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a59a5eeccde7b8eef0833cee7b914443b">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::startSynthesis</a>.</p>

</div>
</div>

### count {#a797db79c8d98dcd992d5fe9a71ffe68c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringRef::count (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of non-overlapped occurrences of <span class="doxyComputerOutput">Str</span> in the string.</p>


<p>count - Return the number of non-overlapped occurrences of</p>


<ul class="doxyList ">
<li>Str in the string.</li>
</ul>

<p>Declaration at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#aab312a8386488873bac2eddfc67c22be">find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### getAsDouble {#a23753c04a4ada14fc9c4891d30ed5cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StringRef::getAsDouble (double &amp; Result, bool AllowInexact=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the current string as an IEEE double-precision floating point value.</p>


<p>The string must be a well-formed double.</p>


<p>If <span class="doxyComputerOutput">AllowInexact</span> is false, the function will fail if the string cannot be represented exactly. Otherwise, the function only fails in case of an overflow or underflow, or an invalid floating point representation.</p>


<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0596fb939ff753151c9c37ed2b671b4c">llvm::errorToBool</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aaba98149aef517089f9868bde5b8c41bc">llvm::APFloatBase::opInexact</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>

</div>
</div>

### getAsInteger {#a1881146f2dcc2ca57c9c5f77f938db9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::getAsInteger (unsigned Radix, T &amp; Result)</td>
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

<p>Parse the current string as an integer of the specified radix.</p>


<p>If <span class="doxyComputerOutput">Radix</span> is specified as zero, this does radix autosensing using extended C rules: 0 is octal, 0x is hex, 0b is binary.</p>


<p>If the string is invalid or if only a subset of the string is valid, this returns true to signify the error. The string is considered erroneous if empty or if it overflows T.</p>


<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0985d5b3033e15cfc007386f580c12f1">llvm::getAsSignedInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aceda0d316aed2b818b731917d21b88bc">llvm::getAsUnsignedInteger</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a5861f2cf66ad90de99ef9dfe8054f75d">adjustCallerStackProbeSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a4edf7cbc1ca95769993535d584f66a3f">adjustMinLegalVectorWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#a9a4cc51d7866092e51abf7273e809191">checkedGetHex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a9537162135cca043a3b82f0df2816ed7">llvm::object::Archive::Child::Child</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa15319612cd5edf41994eab4a092896">llvm::get_threadpool_strategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#ad146f206f099fa725c05238ccdccc333">getArchiveMemberOctField</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inteljiteventlistener-cpp-/#ac5094885b654e66770472d1e6802b21f">anonymous{IntelJITEventListener.cpp}::getBackwardCompatibilityMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#ac69e7d445bf4af727118416d0ea36250">getExtensionVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a73d59676cde66e2b3b227b524b35f891">getGlobalSymtabLocAndSize</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp/#a4d52a5b3d278b07fa7992477cc3c5474">getPassNameAndInstanceNum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7a00b18388711db81874093cc266614">llvm::getStringFnAttrAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#afc11b3df4a2d81fbf25988baf63fc6b3">llvm::X86TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#ac236558198da971873e571fa38d2b58a">llvm::AMDGPU::Exp::getTgtId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a98391472a4d0326c68f3db498e6edcb5">llvm::yaml::isInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#add5616535a62c9047ccfbf84bf778663">optimizeNaN</a>, <a href="/web-llvm/docs/api/structs/anonymous-gcnhazardrecognizer-cpp-/mfmapaddingratioparser/#ae39d4753a21e2556fa87afdce623ac6d">anonymous{GCNHazardRecognizer.cpp}::MFMAPaddingRatioParser::parse</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifylibcalls-cpp-/hotcoldhintparser/#ac6997198e701ceb2c7510cab7219daba">anonymous{SimplifyLibCalls.cpp}::HotColdHintParser::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystemparser/#acd3c926d77e4a86b21ee38acf61ebd32">llvm::vfs::RedirectingFileSystemParser::parse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#aa1267723ca2b4fde441e992f4853fa52">anonymous{PassBuilder.cpp}::parseBoundsCheckingOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4accb2c6a0d7504200a547f2284ff106">llvm::parseCachePruningPolicy</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/cachepruning-cpp/#a7f697d231637348b0d4c6e9efbfe8740">parseDuration</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a4f4bb162495773b87818cf7a66410c42">anonymous{PassBuilder.cpp}::parseGlobalMergeOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#aa6ce0897e0923130a01d2226559275c4">anonymous{PassBuilder.cpp}::parseHardwareLoopOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a4df79ca87cfad6de8aad81df9f474540">llvm::remarks::parseHotnessThresholdOption</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a705e25c3f466b071036bde5de60454c5">anonymous{PassBuilder.cpp}::parseInstCombineOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2de75d77a5ee094dabe819e4b5855a6a">anonymous{PassBuilder.cpp}::parseLowerAllowCheckPassOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#aee16ef63867cb58a1e046d39fb99e49f">parseMetadata</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#af9206ecc850cac7b88622396c3025f57">anonymous{PassBuilder.cpp}::parseMSanPassOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abbd69ebe5f468b51fd6fd8122e605a78">parsePredicateRegAsConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad5d1fdc8afad445839bca3e15c7ba4bc">parseRegisterNumber</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a24172b22d5d5ef8caa9223a259787420">anonymous{PassBuilder.cpp}::parseScalarizerOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/elfasmparser-cpp/#aca08eb38e47de9b8bacac06543256178">parseSectionFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a1ea0b527a25e96bb74c8217704b22a07">llvm::MCSectionMachO::ParseSectionSpecifier</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ab47e139366ce224347ee4ea7313c7ff9">anonymous{PassBuilder.cpp}::parseSimplifyCFGOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a830906f493a6d5c69ac5a94675c657fb">llvm::parseStatepointDirectivesFromAttrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#a8b02ace8c1f9abda69c009da0432e901">llvm::AttributeFuncs::updateMinLegalVectorWidthAttr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>.</p>

</div>
</div>

### getAsInteger {#adc9c54d457a9ebc9d909c4b2234c7657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StringRef::getAsInteger (unsigned Radix, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the current string as an integer of the specified <span class="doxyComputerOutput">Radix</span>, or of an autosensed radix if the <span class="doxyComputerOutput">Radix</span> given is 0.</p>


<p>The current value in <span class="doxyComputerOutput">Result</span> is discarded, and the storage is changed to be wide enough to store the parsed integer.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the string does not solely consist of a valid non-empty number in the appropriate base.</p></dd>
</dl>


<p>APInt::fromString is superficially similar but assumes the string is well-formed in the given radix.</p>


<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>Reference <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Substring Operations

### consume\_back {#a14180977794bfc2a37dbffeef3ca20de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::consume_back (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix)</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> has the given suffix and removes that suffix.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#aca439bf65258d9d8d057812938b617c5">ends_with</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/triple/#ade97ab011dc19854c9886f2c6d8ecc66">llvm::Triple::getEnvironmentVersionString</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

### consume\_back\_insensitive {#ac5fd848165f133bf149f8f27618ce313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::consume_back_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix)</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> has the given suffix, ignoring case, and removes that suffix.</p>

<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#ae57b9ee061903472c1cc9082849ed34e">ends_with_insensitive</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a0c85406f393901169b49e3d7a27527e0">anonymous{DlltoolDriver.cpp}::getPrefix</a>.</p>

</div>
</div>

### consume\_front {#a8a7fac667f8ae35285b8b53d9f2dd9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::consume_front (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> has the given prefix and removes that prefix.</p>

<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h/#a5336c02c81ff675028496f2f2409d30a">starts_with</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode/#a8f6028cdd89adeb15d6755814af79718">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getBodyContent</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ade97ab011dc19854c9886f2c6d8ecc66">llvm::Triple::getEnvironmentVersionString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensatargetstreamer-cpp/#a0d30b7a632d76eb770508d5d280d3ed9">getLiteralSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a024faa768c9d7b624a68980113f92693">llvm::Triple::getOSVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/globpattern/#a7bcd47fe233f29521e2d33adc1bf45e0">llvm::GlobPattern::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a98361b28ee9d2d64026953887c1aff33">parseAMDGPUAtomicOptimizerStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a4f4bb162495773b87818cf7a66410c42">anonymous{PassBuilder.cpp}::parseGlobalMergeOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a6a2c903206e499a40b30eacec625bab4">anonymous{PassBuilder.cpp}::parseGVNOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#aa6ce0897e0923130a01d2226559275c4">anonymous{PassBuilder.cpp}::parseHardwareLoopOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a705e25c3f466b071036bde5de60454c5">anonymous{PassBuilder.cpp}::parseInstCombineOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a63d8077ac333f927273b1e014644cf89">anonymous{PassBuilder.cpp}::parseInternalizeGVs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a258bac7878912fdc0517663e0ef41f2e">anonymous{PassBuilder.cpp}::parseIPSCCPOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ae671ad01f3f6d26f481c1f6cf0ac770e">anonymous{PassBuilder.cpp}::parseLICMOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ae99f09b9fc8bb52957b29dc409b67044">anonymous{PassBuilder.cpp}::parseLoopRotateOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#adfcb070aecda48cfd7f3d5bb78b23c3f">anonymous{PassBuilder.cpp}::parseLoopUnswitchOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a0bf1de19ee39f1ce18df8c0b5e42a1c2">anonymous{PassBuilder.cpp}::parseLoopVectorizeOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2de75d77a5ee094dabe819e4b5855a6a">anonymous{PassBuilder.cpp}::parseLowerAllowCheckPassOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#ac279fb04abf32461c56ca95dab29e0c4">parseMagic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a18cb2b53fc5dbf94a7751fe179ac4ebc">anonymous{PassBuilder.cpp}::parseMemProfUsePassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2a5fbe887884963e5fc19c8d823ef83c">anonymous{PassBuilder.cpp}::parseMergedLoadStoreMotionOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#af9206ecc850cac7b88622396c3025f57">anonymous{PassBuilder.cpp}::parseMSanPassOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2b97735452295d7091f55cfaf309ad4c">anonymous{PassBuilder.cpp}::parseRegAllocFastPassOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a93e1f93d537243a559abd940ec1b6f53">parseReplacementItem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a24172b22d5d5ef8caa9223a259787420">anonymous{PassBuilder.cpp}::parseScalarizerOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ab47e139366ce224347ee4ea7313c7ff9">anonymous{PassBuilder.cpp}::parseSimplifyCFGOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a6b61483aaba059f71022975a37737e15">llvm::VersionTuple::tryParse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1381cfa5d5d20b2c0de03ce8f211c1cf">anonymous{VFABIDemangler.cpp}::tryParseAlign</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a856e22af4413a5ea9df66d623f35b824">anonymous{VFABIDemangler.cpp}::tryParseCompileTimeLinearToken</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1e256b3e261a7e37851be3f91173e6c0">anonymous{VFABIDemangler.cpp}::tryParseISA</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a4c267f75d0c944ac84dff96f8a4779f3">anonymous{VFABIDemangler.cpp}::tryParseLinearTokenWithRuntimeStep</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a3af3ce355fb0d93f751694070efc4c1d">anonymous{VFABIDemangler.cpp}::tryParseMask</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a71eadd5ab74bdb057ebcc6b916924f78">anonymous{VFABIDemangler.cpp}::tryParseParameter</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a14373b1995a870811ec0b24e8c7bb274">anonymous{VFABIDemangler.cpp}::tryParseVLEN</a>.</p>

</div>
</div>

### consume\_front\_insensitive {#ae94101ab936805840acecc874e70c190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringRef::consume_front_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> has the given prefix, ignoring case, and removes that prefix.</p>

<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a343b6c58108519aca196bb54b1d1a6ef">starts_with_insensitive</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>

</div>
</div>

### detectEOL {#a9202ca0a40ca22c6198342cf8b0dc050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::detectEOL ()</td>
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

<p>Detect the line ending style of the string.</p>


<p>If the string contains a line ending, return the line ending character sequence that is detected. Otherwise return '
<br/>
' for unix line endings.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- The line ending character sequence.</p></dd>
</dl>


<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="#aab312a8386488873bac2eddfc67c22be">find</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### drop\_back {#ae2705fd641fb3d1eefa2691b5117cf22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::drop_back (size_t N=1)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this' but with the last <span class="doxyComputerOutput">N</span> elements dropped.</p>

<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a1e1e2695745252cae26a9843b4d8daa3">llvm::OpenMPIRBuilder::createTargetDeinit</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a7db9daa323dee69eb9ecc380ce6edae8">llvm::OpenMPIRBuilder::createTargetInit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a35e48627247fb4ab86466af66ed3ec31">llvm::AMDGPU::getArchFamilyNameAMDGCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac52de24a1dd7695de94261e6ab8bb457">llvm::getObjCNamesIfSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/document/#a195e6cd6c71f2fabbd3d99a61627abee">llvm::yaml::Document::parseBlockNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ad7e099354c93867323bca88df83c40b2">llvm::omp::prettifyFunctionName</a>, <a href="#a9b52404a8d2877d3b32ebb5d1f5c72ff">rtrim</a>, <a href="#acf544fca0b0f46e00e4261bc925104e5">rtrim</a> and <a href="#aa28286a33491b5d9a936fb6ae853baee">take_front</a>.</p>

</div>
</div>

### drop\_front {#a3fb2867a1e9fa36e135d9ee4dffb0167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::drop_front (size_t N=1)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this' but with the first <span class="doxyComputerOutput">N</span> elements dropped.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owneddatasection/#a124ee6d61bfd830c483ce8273529bfcf">llvm::objcopy::elf::OwnedDataSection::appendHexData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#a66b1304ca72d9916db93a0ab9a55697c">llvm::ELFAttrs::attrTypeAsString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#a343d704d236717ce9399b288a622a222">llvm::ELFAttrs::attrTypeFromString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/djb-cpp/#af60bf47ef264d1d6c10fea7a1dd7da9f">chopOneUTF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a36c152217dc69b5295561b2f99c52c17">llvm::omp::deconstructOpenMPKernelName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#af1d0120f54489e515264a9ed0668ce9a">anonymous{AMDGPULibFunc.cpp}::drop_front</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a>, <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a1933cc94d2453eb9f2cd131e7327ec18">llvm::AArch64::getArchExtFeature</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode/#a8f6028cdd89adeb15d6755814af79718">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getBodyContent</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a36361ab61c92cc509c46bcc75b8dd34a">llvm::objcopy::elf::IHexRecord::getChecksum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ad23de4e373a0c20f6b905ae9251a3f5c">llvm::cl::getCompilerBuildConfig</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a9ae632cfb346b34a2a80a7f70e1ee048">getDXILArchNameFromShaderModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e54b20745d63f337766efd74f06c5c8">llvm::getFuncNameWithoutPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensatargetstreamer-cpp/#a0d30b7a632d76eb770508d5d280d3ed9">getLiteralSectionName</a>, <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#aac246b383c0888833a23c78a0399a3e8">llvm::opt::OptTable::Info::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac52de24a1dd7695de94261e6ab8bb457">llvm::getObjCNamesIfSelector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ad540067d5e143dbc9d0a957b4b28968f">llvm::codeview::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a6d7f36df9f1e78161aa1117443ec74e1">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac33e274ca277cfe840f699acc1b8a814">llvm::HexagonSubtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6abe01777169c2216339a59d84bf3999">llvm::yaml::isNumeric</a>, <a href="#a8265efd805e4ce0c9d3c18e78194324c">ltrim</a>, <a href="#acd2e33f03956821cbf94c4cd5da01bdd">ltrim</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a47366639c363a94f62304e26e09cfb18">anonymous{StandardInstrumentations.cpp}::makeHTMLReady</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a594f615f5a0025d4f0c92e27feb9d65d">llvm::yaml::parseBool</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#aa7b40dda7a09e0c055d6138b404d0789">llvm::DebugCounter::parseChunks</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a332d48815071fdb4e2e94e999c154559">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDimId</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#ac44851c2ceedf8a3136d31773e0f20e2">llvm::RISCVISAInfo::parseFeatures</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1119c30ad17d23efa29bf5593774867d">anonymous{MIParser.cpp}::MIParser::parseLowLevelType</a>, <a href="/web-llvm/docs/api/structs/llvm/aarch64/extensionset/#a47d4274efc34b5d09e3d8142be273a11">llvm::AArch64::ExtensionSet::parseModifier</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abbd69ebe5f468b51fd6fd8122e605a78">parsePredicateRegAsConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a307619afda1e993b5ab00f907fb103b9">parseStrTab</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a7f3ee08c28f1f56632e9b58a7e90a813">parseStrTabSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ab0d2fab5845ea5a11a1a57775090aec7">llvm::MachO::parseSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp/#a407041f5d2ea26309c1f9071a724314e">parseThunkName</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a96f48f9a5690ef01b9d2574472e1f7e2">anonymous{MIParser.cpp}::MIParser::parseTypedImmediateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a8eb3d9b91beb14411cbb1c3957c5cd49">parseVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5618db29d0000023a813f4d00e3bf484">popFront</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a9d20e2079dcd9a868d4b3af67510647b">printSourceLine</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a>, <a href="#a9fe565cb0cc832480a9a9ed312dc2962">take_back</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1e256b3e261a7e37851be3f91173e6c0">anonymous{VFABIDemangler.cpp}::tryParseISA</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dllimportdefinitiongenerator/#a28474a2103675aa30411c3cc01585b0c">llvm::orc::DLLImportDefinitionGenerator::tryToGenerate</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a438f99943621d64eb8920e5075719b36">upgradeLoopTag</a>.</p>

</div>
</div>

### drop\_until {#a53315344f92e70843fb54b6b7769de67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::drop_until (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(char)&gt; F)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this', but with all characters not satisfying the given predicate dropped from the beginning of the string.</p>

<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode/#a8f6028cdd89adeb15d6755814af79718">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getBodyContent</a>.</p>

</div>
</div>

### drop\_while {#adb414d662ce914329570f0ff92602336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::drop_while (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(char)&gt; F)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this', but with all characters satisfying the given predicate dropped from the beginning of the string.</p>

<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#afe4ee2901ac2ae201e839a7972038a1c">find_if_not</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>

</div>
</div>

### ltrim {#a8265efd805e4ce0c9d3c18e78194324c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::ltrim (char Char)</td>
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

<p>Return string with consecutive <span class="doxyComputerOutput">Char</span> characters starting from the the left removed.</p>

<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a3fb2867a1e9fa36e135d9ee4dffb0167">drop_front</a>, <a href="#ae851887270f35d2a2670a79b9833d45b">find_first_not_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerexpreval/#a83c754c0b8d462edcbfec5424e5a64ae">llvm::RuntimeDyldCheckerExprEval::evaluate</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a7a9dc76f6cda36296f3df309700937e2">FindCheckType</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a93e1f93d537243a559abd940ec1b6f53">parseReplacementItem</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="#ab9990397f97b40d5d8564e000d00174a">trim</a>, <a href="#a0c5126dde83d4cc3f8edaf6ac288b35e">trim</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

### ltrim {#acd2e33f03956821cbf94c4cd5da01bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::ltrim (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars=" \t\n\v\f\r")</td>
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

<p>Return string with consecutive characters in <span class="doxyComputerOutput">Chars</span> starting from the left removed.</p>

<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a3fb2867a1e9fa36e135d9ee4dffb0167">drop_front</a>, <a href="#ae851887270f35d2a2670a79b9833d45b">find_first_not_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### rsplit {#aca46fb04897a97747c13d75a06f1215a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; StringRef, StringRef &gt; llvm::StringRef::rsplit (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Separator)</td>
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

<p>Split into two substrings around the last occurrence of a separator string.</p>


<p>If <span class="doxyComputerOutput">Separator</span> is in the string, then the result is a pair (LHS, RHS) such that (*this == LHS + Separator + RHS) is true and RHS is minimal. If <span class="doxyComputerOutput">Separator</span> is not in the string, then the result is a pair (LHS, RHS) where (*this == LHS) and (RHS == "").</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Separator</td>
<td class="doxyParamItemDescription"><p>- The string to split on.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- The split substrings.</p></dd>
</dl>


<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a97d45ce069c1a09ca84672df63acf096">rfind</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>, <a href="#a5d4c961b9b6f1da17df74b4496ecb30e">slice</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#ad17bf01008144e718fa39ffa0ef84733">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::prettyPrintAsm</a> and <a href="#a4bc298d953d88e5a2d7c52a5c9cd2d36">rsplit</a>.</p>

</div>
</div>

### rsplit {#a4bc298d953d88e5a2d7c52a5c9cd2d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; StringRef, StringRef &gt; llvm::StringRef::rsplit (char Separator)</td>
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

<p>Split into two substrings around the last occurrence of a separator character.</p>


<p>If <span class="doxyComputerOutput">Separator</span> is in the string, then the result is a pair (LHS, RHS) such that (*this == LHS + Separator + RHS) is true and RHS is minimal. If <span class="doxyComputerOutput">Separator</span> is not in the string, then the result is a pair (LHS, RHS) where (*this == LHS) and (RHS == "").</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Separator</td>
<td class="doxyParamItemDescription"><p>- The character to split on.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- The split substrings.</p></dd>
</dl>


<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#aca46fb04897a97747c13d75a06f1215a">rsplit</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### rtrim {#a9b52404a8d2877d3b32ebb5d1f5c72ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::rtrim (char Char)</td>
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

<p>Return string with consecutive <span class="doxyComputerOutput">Char</span> characters starting from the right removed.</p>

<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#ae2705fd641fb3d1eefa2691b5117cf22">drop_back</a>, <a href="#a035cf6768564ead852edfff8ca9c3b6e">find_last_not_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplanprinter/#abf65de021b888eeddb9cc578116d9211">llvm::VPlanPrinter::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerexpreval/#a83c754c0b8d462edcbfec5424e5a64ae">llvm::RuntimeDyldCheckerExprEval::evaluate</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a896c0342b10ed46345456bd263e5a7ae">getFieldRawString</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a940c0b94e9bb9dfdb69961d456b47b60">llvm::object::ArchiveMemberHeader::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#ae3326a9bb0843a456b29982ae9be935d">getPayloadString</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a0c85406f393901169b49e3d7a27527e0">anonymous{DlltoolDriver.cpp}::getPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a8357e5a2ff9e83794636dc9878659696">llvm::X86InstPrinterCommon::printCondFlags</a>.</p>

</div>
</div>

### rtrim {#acf544fca0b0f46e00e4261bc925104e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::rtrim (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars=" \t\n\v\f\r")</td>
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

<p>Return string with consecutive characters in <span class="doxyComputerOutput">Chars</span> starting from the right removed.</p>

<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#ae2705fd641fb3d1eefa2691b5117cf22">drop_back</a>, <a href="#a035cf6768564ead852edfff8ca9c3b6e">find_last_not_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### slice {#a5d4c961b9b6f1da17df74b4496ecb30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::slice (size_t Start, size_t End)</td>
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

<p>Return a reference to the substring from [Start, End).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Start</td>
<td class="doxyParamItemDescription"><p>The index of the starting character in the substring; if the index is npos or greater than the length of the string then the empty substring will be returned.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">End</td>
<td class="doxyParamItemDescription"><p>The index following the last character to include in the substring. If this is npos or exceeds the number of characters remaining in the string, the string suffix (starting with <span class="doxyComputerOutput">Start</span>) will be returned. If this is less than <span class="doxyComputerOutput">Start</span>, an empty string will be returned.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5e419b9328977a480fda42c789b77237">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::addExplicitComment</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ac71c43fb658be4df9989f55be8447e1d">llvm::FileCheckString::CheckDag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3bcb896473d4c0e5275a58bf731ee899">llvm::object::ObjectFile::createMachOObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a35752ab55341ad5c938ff0a88626bfab">llvm::BTFParser::findString</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/srecord/#a8a3e8a37182f3d235fba5f02768ce39a">llvm::objcopy::elf::SRecord::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#a544c2983fe03425d0dfe7b5ff0b59d9e">llvm::object::MinidumpFile::getRawStream</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoobjectfile-cpp-/#ad6473b2753bdca7d12955749ed652b7c">anonymous{MachOObjectFile.cpp}::getSegmentContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#af3e1bca92860141baaad0a536334d09f">llvm::object::MachOObjectFile::guessLibraryShortName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba7165df55c01bd2653b37a6e9f4a8ae">llvm::lookupBuiltin</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a336063ab4c85ca7260327f7c39a64492">llvm::SPIRV::parseBuiltinTypeStr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad5d1fdc8afad445839bca3e15c7ba4bc">parseRegisterNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a9d20e2079dcd9a868d4b3af67510647b">printSourceLine</a>, <a href="#aca46fb04897a97747c13d75a06f1215a">rsplit</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a25d8acedc0fc6a1fbd8a2eea6dcd0f4c">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::setPassPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#a7c3a261582207f6db4cd6d83732e9ac0">llvm::SmallString&lt; 0 &gt;::slice</a>, <a href="#a7b0138ddc186a7cb5cfd04dde671220e">split</a>, <a href="#af0284e4c41c0e09c0bc4767bc77a899d">split</a>, <a href="#accc1b9e00e08cff2c9beb3059efa4200">split</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>.</p>

</div>
</div>

### split {#a0320b2a5a6d440bf4479a02e78cf5ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; StringRef, StringRef &gt; llvm::StringRef::split (char Separator)</td>
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

<p>Split into two substrings around the first occurrence of a separator character.</p>


<p>If <span class="doxyComputerOutput">Separator</span> is in the string, then the result is a pair (LHS, RHS) such that (*this == LHS + Separator + RHS) is true and RHS is maximal. If <span class="doxyComputerOutput">Separator</span> is not in the string, then the result is a pair (LHS, RHS) where (*this == LHS) and (RHS == "").</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Separator</td>
<td class="doxyParamItemDescription"><p>The character to split on.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The split substrings.</p></dd>
</dl>


<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a0320b2a5a6d440bf4479a02e78cf5ca7">split</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa6138676e4615546fc1c7d559029916a">addSection</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2f6c06a6e0a4bb5192193116bded1308">llvm::InlineAsm::collectAsmStrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a03a9d7487e3a99b134abd6aa5bf2a101">llvm::sampleprof::SampleContext::createCtxVectorFromStr</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a8405818cd197f55e233406e23f59c76e">llvm::sampleprof::SampleContext::decodeContextString</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/classes/llvm/vplanprinter/#abf65de021b888eeddb9cc578116d9211">llvm::VPlanPrinter::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a684f6b8b5cfa3d9d70c557c1d019ac62">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#a19fc4c64b801bb8ba465fdede95e7ca3">findSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a9952645a56e841314d2b880bd31375">llvm::findVCToolChainViaEnvironment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp/#a447453362ec26907f4116a81d6ac91f1">forceAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ad2d9e5a5c22d594a05d4feae337de252">llvm::Triple::getArchName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5eae02b55217e729a02eda2e26b8d689">llvm::codeview::getBytesAsCString</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a37b7e51dcb0e1efd0a84eb6398fd6301">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ae18b7d7be4354e3df59467ddf7d35c63">llvm::object::COFFObjectFile::getDebugPDBInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2dbbd8a3a24b8bec3477cb7aab90b051">llvm::getDefaultDebuginfodUrls</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a685d4808dcb1ae5133120d64593d515b">llvm::Triple::getEnvironmentName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a4bec84a251a1b5d60516bfc63ec06a52">llvm::AArch64TTIImpl::getFeatureMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a5cd7a516996539c18628e51d9f628e07">llvm::sys::detail::getHostCPUNameForARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a6c6d718154a7120db2e00cd7a1895aea">llvm::sys::detail::getHostCPUNameForRISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a3455f56c4a28156282d4f5cd6265e034">llvm::sys::detail::getHostCPUNameForS390x</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae254bedbb0fc90b423b5072a97ef3efd">llvm::AMDGPU::getIntegerVecAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a10d66ea364d36a165309638f88ef0b0f">getIntOperandFromRegisterString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#ac3cb3b8d15dadee766eed8f3eac75ff5">getIntOperandsFromRegisterString</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#ad4c0f9a1193f368bbea577f429a3050c">getOpEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#acd9d92f0d78ae680c0eb2a43573b93ff">getOpRefinementSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9e404426d1eac2b4c19c8986d9d46cb3">llvm::Triple::getOSAndEnvironmentName</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a483bbccede7948c656b0bd339f39218f">llvm::Triple::getOSName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47f269ecf274794f7bc6d65cc50979b9">llvm::getParsedIRPGOName</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#aae7bdcf65f4ce313299a333956258f10">llvm::LoongArchTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a8c99c6a7b32e47161b669182402a5c66">getSearchPaths</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a61b450c11951eeed5ec4560ce599ee87">llvm::object::COFFObjectFile::getSectionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a062f684a024e13d7280e178c95668678">llvm::Triple::getVendorName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d069b5b5139c3ccd0a63545bcfbb98a">llvm::handleExecNameEncodedBEOpts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f99b185789990137a084d3fc1910b47">llvm::handleExecNameEncodedOptimizerOpts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2db677513c23141ea0ec08b46e2b975d">llvm::isHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#ad772ba5923d08e11379f06cc8c3c5e4d">llvm::offloading::amdgpu::isImageCompatibleWithEnv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a5af65e382f22a93146221fa34dbd91eb">isThumbFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/object/lexer/#a0f4fa1946ef0ac461232bc74e92dd921">llvm::object::Lexer::lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba7165df55c01bd2653b37a6e9f4a8ae">llvm::lookupBuiltin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#ae015be66fae811e0fe4cc32ce868f373">LookupNearestOption</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64targettransforminfo-cpp-/tailfoldingoption/#a5df8b2fca0d3dc356531c2f218468d2f">anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::operator=</a>, <a href="/web-llvm/docs/api/structs/anonymous-debug-cpp-/debugonlyopt/#a6d7c1ee5e524ba5a7c325ed08cc5bed8">anonymous{Debug.cpp}::DebugOnlyOpt::operator=</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86alignbranchkind/#a06655a62018f3b5f6bf05639e3f64e7b">anonymous{X86AsmBackend.cpp}::X86AlignBranchKind::operator=</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#add0594bfc35119c8d898c51bb3697823">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionModeFromNumthreadsAttribute</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvextensionsparser/#a9c59e739efd5cf76e15f932543c272e3">llvm::SPIRVExtensionsParser::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a1d4e2a477b2b896adfdec5e55638b725">llvm::PassBuilder::parseAAPipeline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a932dc6a42ae580674ab795b1946a9d68">parseAMDGPUAttributorPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a51edfbed0895aa13fbac2ec63d1dc755">anonymous{PassBuilder.cpp}::parseASanPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#aa1267723ca2b4fde441e992f4853fa52">anonymous{PassBuilder.cpp}::parseBoundsCheckingOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a336063ab4c85ca7260327f7c39a64492">llvm::SPIRV::parseBuiltinTypeStr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a85286c436c5c0f09abe43dc522fe5f2d">anonymous{PassBuilder.cpp}::parseCFGuardPassOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#aff85944087fc349e227e8b737179cb3e">parseCHRFilterFiles</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#afd6042c1b738cd6940d1f0c8e7e22090">anonymous{PassBuilder.cpp}::parseEmbedBitcodePassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-metarenamer-cpp-/#afa80d009777b085fbd5703e90769d652">anonymous{MetaRenamer.cpp}::parseExcludedPrefixes</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a4f4bb162495773b87818cf7a66410c42">anonymous{PassBuilder.cpp}::parseGlobalMergeOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a6a2c903206e499a40b30eacec625bab4">anonymous{PassBuilder.cpp}::parseGVNOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#aa6ce0897e0923130a01d2226559275c4">anonymous{PassBuilder.cpp}::parseHardwareLoopOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a6b63475afb18b589e0cd668a55da3f0b">anonymous{PassBuilder.cpp}::parseHWASanPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a705e25c3f466b071036bde5de60454c5">anonymous{PassBuilder.cpp}::parseInstCombineOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a63d8077ac333f927273b1e014644cf89">anonymous{PassBuilder.cpp}::parseInternalizeGVs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a258bac7878912fdc0517663e0ef41f2e">anonymous{PassBuilder.cpp}::parseIPSCCPOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ae671ad01f3f6d26f481c1f6cf0ac770e">anonymous{PassBuilder.cpp}::parseLICMOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ae99f09b9fc8bb52957b29dc409b67044">anonymous{PassBuilder.cpp}::parseLoopRotateOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a652a936841e4c7f71e374e445a273fdf">anonymous{PassBuilder.cpp}::parseLoopUnrollOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#adfcb070aecda48cfd7f3d5bb78b23c3f">anonymous{PassBuilder.cpp}::parseLoopUnswitchOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a0bf1de19ee39f1ce18df8c0b5e42a1c2">anonymous{PassBuilder.cpp}::parseLoopVectorizeOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2de75d77a5ee094dabe819e4b5855a6a">anonymous{PassBuilder.cpp}::parseLowerAllowCheckPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a18cb2b53fc5dbf94a7751fe179ac4ebc">anonymous{PassBuilder.cpp}::parseMemProfUsePassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2a5fbe887884963e5fc19c8d823ef83c">anonymous{PassBuilder.cpp}::parseMergedLoadStoreMotionOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#af9206ecc850cac7b88622396c3025f57">anonymous{PassBuilder.cpp}::parseMSanPassOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#a56ec8af379a8cf1ff76e2171f0bbbbb3">parseNamePrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2b97735452295d7091f55cfaf309ad4c">anonymous{PassBuilder.cpp}::parseRegAllocFastPassOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a24172b22d5d5ef8caa9223a259787420">anonymous{PassBuilder.cpp}::parseScalarizerOptions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ab47e139366ce224347ee4ea7313c7ff9">anonymous{PassBuilder.cpp}::parseSimplifyCFGOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#adc2db790282de50547f17992a5dece6b">llvm::PassBuilder::parseSinglePassOption</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ab72e4b451f3f28ac0f1f862b8e9f8809">anonymous{PassBuilder.cpp}::parseStackLifetimeOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp/#a407041f5d2ea26309c1f9071a724314e">parseThunkName</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#ad17bf01008144e718fa39ffa0ef84733">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::prettyPrintAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a67552a8bdd1bd0df687842c7acf3efa3">llvm::DebugCounter::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad73613c8e8495c4d7e3aaf2da575f2e2">llvm::readAndDecodeStrings</a>, <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#aa93fa22630383fe07736811e31c03f81">llvm::Hexagon_MC::selectHexagonCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid/#aab792d0c32d4c9a7998c0ba8885693ff">llvm::AMDGPU::IsaInfo::AMDGPUTargetID::setTargetIDFromTargetIDStream</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a10aa0138f3edcc0641294b19c7fdebbb">llvm::SubtargetFeatures::Split</a>, <a href="#a0320b2a5a6d440bf4479a02e78cf5ca7">split</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#aaddd5ed7dd146aad3e0c51691a90f22c">llvm::opt::OptTable::suggestValueCompletions</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>.</p>

</div>
</div>

### split {#accc1b9e00e08cff2c9beb3059efa4200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; StringRef, StringRef &gt; llvm::StringRef::split (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Separator)</td>
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

<p>Split into two substrings around the first occurrence of a separator string.</p>


<p>If <span class="doxyComputerOutput">Separator</span> is in the string, then the result is a pair (LHS, RHS) such that (*this == LHS + Separator + RHS) is true and RHS is maximal. If <span class="doxyComputerOutput">Separator</span> is not in the string, then the result is a pair (LHS, RHS) where (*this == LHS) and (RHS == "").</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Separator</td>
<td class="doxyParamItemDescription"><p>- The string to split on.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- The split substrings.</p></dd>
</dl>


<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#aab312a8386488873bac2eddfc67c22be">find</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>, <a href="#a5d4c961b9b6f1da17df74b4496ecb30e">slice</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>

</div>
</div>

### split {#af0284e4c41c0e09c0bc4767bc77a899d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringRef::split (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; A, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Separator, int MaxSplit=-1, bool KeepEmpty=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split into substrings around the occurrences of a separator string.</p>


<p>Each substring is stored in <span class="doxyComputerOutput">A</span>. If <span class="doxyComputerOutput">MaxSplit</span> is &gt;= 0, at most <span class="doxyComputerOutput">MaxSplit</span> splits are done and consequently &lt;= <span class="doxyComputerOutput">MaxSplit</span> + 1 elements are added to A. If <span class="doxyComputerOutput">KeepEmpty</span> is false, empty strings are not added to <span class="doxyComputerOutput">A</span>. They still count when considering <span class="doxyComputerOutput">MaxSplit</span> An useful invariant is that Separator.join(A) == *this if MaxSplit == -1 and KeepEmpty == true</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>- Where to put the substrings.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Separator</td>
<td class="doxyParamItemDescription"><p>- The string to split on.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxSplit</td>
<td class="doxyParamItemDescription"><p>- The maximum number of times the string is split.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KeepEmpty</td>
<td class="doxyParamItemDescription"><p>- True if empty substring should be added.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a2dc80c585ad5882da8cae7b5968f7e74">empty</a>, <a href="#aab312a8386488873bac2eddfc67c22be">find</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a5db9240c74644c67759dd0f901fc3c7d">size</a>, <a href="#a5d4c961b9b6f1da17df74b4496ecb30e">slice</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="#a25f1fd81f2132805676c82ab8ae0c109">substr</a>.</p>

</div>
</div>

### split {#a7b0138ddc186a7cb5cfd04dde671220e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringRef::split (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; A, char Separator, int MaxSplit=-1, bool KeepEmpty=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split into substrings around the occurrences of a separator character.</p>


<p>Each substring is stored in <span class="doxyComputerOutput">A</span>. If <span class="doxyComputerOutput">MaxSplit</span> is &gt;= 0, at most <span class="doxyComputerOutput">MaxSplit</span> splits are done and consequently &lt;= <span class="doxyComputerOutput">MaxSplit</span> + 1 elements are added to A. If <span class="doxyComputerOutput">KeepEmpty</span> is false, empty strings are not added to <span class="doxyComputerOutput">A</span>. They still count when considering <span class="doxyComputerOutput">MaxSplit</span> An useful invariant is that Separator.join(A) == *this if MaxSplit == -1 and KeepEmpty == true</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>- Where to put the substrings.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Separator</td>
<td class="doxyParamItemDescription"><p>- The string to split on.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxSplit</td>
<td class="doxyParamItemDescription"><p>- The maximum number of times the string is split.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KeepEmpty</td>
<td class="doxyParamItemDescription"><p>- True if empty substring should be added.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a2dc80c585ad5882da8cae7b5968f7e74">empty</a>, <a href="#aab312a8386488873bac2eddfc67c22be">find</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="#a5d4c961b9b6f1da17df74b4496ecb30e">slice</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="#a25f1fd81f2132805676c82ab8ae0c109">substr</a>.</p>

</div>
</div>

### substr {#a25f1fd81f2132805676c82ab8ae0c109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::substr (size_t Start, size_t N=<a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a reference to the substring from [Start, Start + N).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Start</td>
<td class="doxyParamItemDescription"><p>The index of the starting character in the substring; if the index is npos or greater than the length of the string then the empty substring will be returned.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p>The number of characters to included in the substring. If N exceeds the number of characters remaining in the string, the string suffix (starting with <span class="doxyComputerOutput">Start</span>) will be returned.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ad0f54a163ac500b144590640c6f1eb6b">npos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#ab3006e90ba5c4717808c3c35e1a778a5">llvm::Hexagon_MC::addArchSubtarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5e419b9328977a480fda42c789b77237">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::addExplicitComment</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#a09f85524dd190f2649d7f584a2edcce3">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTypeTagName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a2582ad4e03989cb2e2712ae5ddf5e2a9">llvm::object::applyNameType</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ae337924e2723d7d8255011f1ac5624cf">llvm::FileCheckString::Check</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ac71c43fb658be4df9989f55be8447e1d">llvm::FileCheckString::CheckDag</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a95a7a7f317661b984c86d196fa44dff9">llvm::FileCheck::checkInput</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ac4560fb1d6b91d4ba6edb7e907573c1e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::cloneAndEmitDebugFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a030478956c379ec2bb71550cb0526fb6">CommaSeparateAndAddOccurrence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a559ce07c89729386c121ca32098cb0f9">llvm::consumeUnsignedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/globpattern/#ad853cb6a2e5807ae5006c0f5ba1e7b49">llvm::GlobPattern::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#a03a9d7487e3a99b134abd6aa5bf2a101">llvm::sampleprof::SampleContext::createCtxVectorFromStr</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfyaml/#ac84f1cd7e37d227e700d6a69398fd3c1">llvm::ELFYAML::dropUniqueSuffix</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#a5d574989dd4688949082681ec54010f6">anonymous{AMDGPULibFunc.cpp}::eatLengthPrefixedName</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#ab07e49a5499032dc8f97198892218853">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::EmitCommentsAndEOL</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5fdc8e2ed6d4f1c0f6936a0291ec496c">llvm::AsmPrinter::emitPCSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a32519abee87d93f315f9da6cbeed31cf">emitPPA1Name</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerexpreval/#a83c754c0b8d462edcbfec5424e5a64ae">llvm::RuntimeDyldCheckerExprEval::evaluate</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a481e97810e8743a7c0f25a51dbcad8c1">llvm::ELFObjectWriter::executePostLayoutBinding</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ad1056825d31bf187d0be430c51aac281">llvm::sys::path::extension</a>, <a href="#a2fab98a15364352e9a7a48da307fde69">find_insensitive</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a02aebfa7014b1bf9a52445a58163adb8">FindFirstMatchingPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a28cc3d07256589bd54f2d22eb12bafad">llvm::MCJIT::findModuleForSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ae25b1e577bcd72ebc8b84b83aca02662">for</a>, <a href="/web-llvm/docs/api/structs/llvm/format-provider-ecaa20ba3297bf1600b082fe1fca61e7/#a1e190076f44d99f68be134785ae5ad3b">llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_string_formatter&lt; T &gt;::value &gt; &gt;::format</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#aa66476422470ab204074b3198bcf4d15">llvm::JITSymbolFlags::fromGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch/#af15c33e98f6234064d5be2e0dcf7aa7d">llvm::object::MachOUniversalBinary::ObjectForArch::getAsArchive</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch/#ae5f1caff8db19eaa70746ee93fe04b6f">llvm::object::MachOUniversalBinary::ObjectForArch::getAsIRObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch/#a8ab7ed72632476f2d49c80dae14ce478">llvm::object::MachOUniversalBinary::ObjectForArch::getAsObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a37b7e51dcb0e1efd0a84eb6398fd6301">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#aa167494fa5d265faa5315612cd3d37fe">llvm::gsym::GsymReader::getFunctionInfoDataAtIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a5e3a9067624454f77d0c2bc55bcdaf89">getHexUint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensatargetstreamer-cpp/#a0d30b7a632d76eb770508d5d280d3ed9">getLiteralSectionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#ad4c0f9a1193f368bbea577f429a3050c">getOpEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#acd9d92f0d78ae680c0eb2a43573b93ff">getOpRefinementSteps</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f17d3e92f855f675577a021e9bc2a35">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVTypeByName</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a024faa768c9d7b624a68980113f92693">llvm::Triple::getOSVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoobjectfile-cpp-/#a468583934460cfc450055eaac3ec3397">anonymous{MachOObjectFile.cpp}::getSegmentContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvelement-cpp/#a0a0a5465a81f37e6f33be77ca0cc85e4">getStringIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad451ffea9d6ef1b5ec634f176bf6dcad">llvm::object::MachOObjectFile::getStringTableData</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a3d2c6d71f70d0e607257e6608872884e">getVarName</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/node/#a388e35e6191f5f51957c3024ef635190">llvm::yaml::Node::getVerbatimTag</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#af3e1bca92860141baaad0a536334d09f">llvm::object::MachOObjectFile::guessLibraryShortName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a21de2c5fb30965f2300f1e49f791c915">HandlePrefixedOrGroupedOption</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ae6071096c441061cfc9f7b4cf8f4ec9e">anonymous{DlltoolDriver.cpp}::identifyImportName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/directx/signature/#a8f7cfbb475d2b81f3b1c99bb5e74e53d">llvm::object::DirectX::Signature::initialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a88d6a2d221777b8376bde5d860a219d1">llvm::isSpecialPass</a>, <a href="/web-llvm/docs/api/classes/llvm/object/lexer/#a0f4fa1946ef0ac461232bc74e92dd921">llvm::object::Lexer::lex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a1f67f9d068986121afe18f99677d1687">llvm::SPIRV::lookupBuiltinNameHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6ded20d42a05e6478238dcfd3caceede">matchAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/object/directx/psvruntimeinfo/#ac30f90a499bf2baa821b2838a784b86b">llvm::object::DirectX::PSVRuntimeInfo::parse</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvextensionsparser/#a9c59e739efd5cf76e15f932543c272e3">llvm::SPIRVExtensionsParser::parse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f5ff058df930ce88aba780fa5191562">llvm::parseAnalysisUtilityPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/document/#a195e6cd6c71f2fabbd3d99a61627abee">llvm::yaml::Document::parseBlockNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a4f539d580f110fc7b26cd99ae4b09abe">parseBraceExpansions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a9249200d14424808c822103928fe7fdc">llvm::SPIRV::parseBuiltinTypeNameToTargetExtType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a112b0124ddda89fd041dbdbc53016275">llvm::dwarf_linker::parseDebugTableName</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a89eeee4c3ec5d281810e8ac7572ddee4">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/versiontuple-cpp/#a78818341564bdaf1e6ec53d418cb5cc2">parseInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a32990ca8b9376479e983ffed2e0fe9b4">llvm::RISCVISAInfo::parseNormalizedArchString</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abbd69ebe5f468b51fd6fd8122e605a78">parsePredicateRegAsConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3331028c9eef66f4022ac3efa310af7d">llvm::Pattern::printFuzzyMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#afb37a1905e7f29be59a6d5406da52a32">llvm::GCOVBuffer::readGCDAFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#ad1db2af6d2bd3952490d0ecc76aab3b1">llvm::GCOVBuffer::readGCNOFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a4a9c60caa200d23d5e4f12b24d4c8877">llvm::object::replace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb31f2db6f0fe5eaa5b28464141223aa">llvm::sys::path::replace_path_prefix</a>, <a href="#a56e7e0bebc570bc6814cdefd1f2ecda3">rfind_insensitive</a>, <a href="#a7b0138ddc186a7cb5cfd04dde671220e">split</a>, <a href="#af0284e4c41c0e09c0bc4767bc77a899d">split</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1d074d016ff4ab25b0d504bf70a89059">llvm::sys::path::stem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae16a5e96f09ffb2af4badfc60223f631">llvm::stripDirPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a8de4cf7f3a21b57333330349f1f32ff3">llvm::SubtargetFeatures::StripFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#abab69c8e9372f6a5283db4a059b8d5a0">llvm::SmallString&lt; 0 &gt;::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a6b61483aaba059f71022975a37737e15">llvm::VersionTuple::tryParse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08f09f6a0568054ba5a1db783b6eeae5">llvm::UpgradeSectionAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile/#a78b45ebf4772364c848d6aedf38fd199">llvm::object::WasmObjectFile::WasmObjectFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>.</p>

</div>
</div>

### take\_back {#a9fe565cb0cc832480a9a9ed312dc2962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::take_back (size_t N=1)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this' but with only the last <span class="doxyComputerOutput">N</span> elements remaining.</p>


<p>If <span class="doxyComputerOutput">N</span> is greater than the length of the string, the entire string is returned.</p>


<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a3fb2867a1e9fa36e135d9ee4dffb0167">drop_front</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

### take\_front {#aa28286a33491b5d9a936fb6ae853baee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::take_front (size_t N=1)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> equal to 'this' but with only the first <span class="doxyComputerOutput">N</span> elements remaining.</p>


<p>If <span class="doxyComputerOutput">N</span> is greater than the length of the string, the entire string is returned.</p>


<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#ae2705fd641fb3d1eefa2691b5117cf22">drop_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/json/#a3251137d4e13982c711221d45fff9a09">llvm::json::abbreviate</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owneddatasection/#a124ee6d61bfd830c483ce8273529bfcf">llvm::objcopy::elf::OwnedDataSection::appendHexData</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#a3b4618fc48c7d5c6c6e7df30e56f7ed6">emitNullTerminatedSymbolName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord/#a36361ab61c92cc509c46bcc75b8dd34a">llvm::objcopy::elf::IHexRecord::getChecksum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac52de24a1dd7695de94261e6ab8bb457">llvm::getObjCNamesIfSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#acedcd0c6ec24c3ce338800619f5d8262">llvm::ThreadSafeTrieRawHashMapBase::getTriePrefixAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader/#a0199559e6f0464acf4c2c30bcb041a03">llvm::TextCodeGenDataReader::hasFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp/#aee6196bb67ae710bbbd44101ea42fc62">mapNameAndUniqueName</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1e256b3e261a7e37851be3f91173e6c0">anonymous{VFABIDemangler.cpp}::tryParseISA</a>.</p>

</div>
</div>

### take\_until {#aa93bf2cc29b3a2ad5056bea30a373d52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::take_until (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(char)&gt; F)</td>
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

<p>Return the longest prefix of 'this' such that no character in the prefix satisfies the given predicate.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a24d07ee06f50c285b723a97222619ff0">find_if</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffnode/#a8f6028cdd89adeb15d6755814af79718">anonymous{StandardInstrumentations.cpp}::DotCfgDiffNode::getBodyContent</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a47366639c363a94f62304e26e09cfb18">anonymous{StandardInstrumentations.cpp}::makeHTMLReady</a> and <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#aa7b40dda7a09e0c055d6138b404d0789">llvm::DebugCounter::parseChunks</a>.</p>

</div>
</div>

### take\_while {#a34a27457ad5d68f631c788807c4ff52c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::take_while (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(char)&gt; F)</td>
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

<p>Return the longest prefix of 'this' such that every character in the prefix satisfies the given predicate.</p>

<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#afe4ee2901ac2ae201e839a7972038a1c">find_if_not</a>, <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

### trim {#ab9990397f97b40d5d8564e000d00174a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::trim (char Char)</td>
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

<p>Return string with consecutive <span class="doxyComputerOutput">Char</span> characters starting from the left and right removed.</p>

<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a8265efd805e4ce0c9d3c18e78194324c">ltrim</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/textapireader/#a91cc2902b5c82e2313c928a08a54597c">llvm::MachO::TextAPIReader::canRead</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerimpl/#a207bb91d248449b19dfdc6b62172b1e4">llvm::RuntimeDyldCheckerImpl::check</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a6e3f70a5f3d1222550716fb9db632c6a">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcheckerexpreval/#a83c754c0b8d462edcbfec5424e5a64ae">llvm::RuntimeDyldCheckerExprEval::evaluate</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a01226a387955cebb0a2a163395a8a527">llvm::DataExtractor::getFixedLengthString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#acefd73b7cd23506659faf02fd0957914">llvm::MachO::parseAliasList</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a7d176c2f7da2816d871ca9dbecd13b7e">llvm::Pattern::parseNumericSubstitutionBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a93e1f93d537243a559abd940ec1b6f53">parseReplacementItem</a>.</p>

</div>
</div>

### trim {#a0c5126dde83d4cc3f8edaf6ac288b35e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::StringRef::trim (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars=" \t\n\v\f\r")</td>
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

<p>Return string with consecutive characters in <span class="doxyComputerOutput">Chars</span> starting from the left and right removed.</p>

<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>


<p>References <a href="#a8265efd805e4ce0c9d3c18e78194324c">ltrim</a> and <a href="#a95fff1cbaf3b1b5b51870a60df57a6e8">StringRef</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
