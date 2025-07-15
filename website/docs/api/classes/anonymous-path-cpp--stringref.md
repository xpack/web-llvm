---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-path-cpp-/stringref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StringRef` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> - Represent a constant reference to a string, i.e. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{Path.cpp}::StringRef { ... }
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
<td class="doxyMemberIndexItemType" align="left" valign="top">iterator_range&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char * &gt;</td>
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
<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this' but with only the first <span class="doxyComputerOutput">N</span> elements remaining. <a href="#aa28286a33491b5d9a936fb6ae853baee">More...</a></p>
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
<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this' but with only the last <span class="doxyComputerOutput">N</span> elements remaining. <a href="#a9fe565cb0cc832480a9a9ed312dc2962">More...</a></p>
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
<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this' but with the first <span class="doxyComputerOutput">N</span> elements dropped. <a href="#a3fb2867a1e9fa36e135d9ee4dffb0167">More...</a></p>
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
<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this' but with the last <span class="doxyComputerOutput">N</span> elements dropped. <a href="#ae2705fd641fb3d1eefa2691b5117cf22">More...</a></p>
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
<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this', but with all characters satisfying the given predicate dropped from the beginning of the string. <a href="#adb414d662ce914329570f0ff92602336">More...</a></p>
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
<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this', but with all characters not satisfying the given predicate dropped from the beginning of the string. <a href="#a53315344f92e70843fb54b6b7769de67">More...</a></p>
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
<p>Returns true if this <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> has the given prefix and removes that prefix. <a href="#a8a7fac667f8ae35285b8b53d9f2dd9dc">More...</a></p>
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
<p>Returns true if this <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> has the given prefix, ignoring case, and removes that prefix. <a href="#ae94101ab936805840acecc874e70c190">More...</a></p>
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
<p>Returns true if this <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> has the given suffix and removes that suffix. <a href="#a14180977794bfc2a37dbffeef3ca20de">More...</a></p>
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
<p>Returns true if this <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> has the given suffix, ignoring case, and removes that suffix. <a href="#ac5fd848165f133bf149f8f27618ce313">More...</a></p>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> - Represent a constant reference to a string, i.e.</p>


<p>a character array and a length, which need not be null terminated.</p>


<p>This class does not own the string data, it is expected to be used in situations where the character data resides in some other buffer, whose lifetime extends past that of the <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a>. For this reason, it is not in general safe to store a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a>.</p>


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


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a987811f4399e448a9e1223ee373c1e00">buildFixItLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#ad696038e18d6965dc078902075026d9b">checkIfSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a030478956c379ec2bb71550cb0526fb6">CommaSeparateAndAddOccurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-path-cpp-/#aa97df12f81288d1870f96204ed9b65c0">anonymous{Path.cpp}::filename_pos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad583c842b8bb943986245cd3dca82e46">getInstrStrFromOpNo</a>, <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp/#adcb30e528bc3886c2c12b92c1474f3da">getTypeNamePrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#aa64729fa8ec00ec0d62c3b353aff5be0">locateCStrings</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ae071c2a56ff28186d5476e562811b2f7">lookupLLVMIntrinsicByName</a>, <a href="/web-llvm/docs/api/structs/prefixmatcher/#a06d7229c302f7f9a6e42ad1afdc957c9">PrefixMatcher::match</a>, <a href="/web-llvm/docs/api/classes/anonymous-aggressiveinstcombine-cpp-/strncmpinliner/#ac9d71bcb73b24374e675d3ac3b8f5e8b">anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner::optimizeStrNCmp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-path-cpp-/#ab211f83596c98e0036e9bfd81b28e67c">anonymous{Path.cpp}::parent_path_end</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a89eeee4c3ec5d281810e8ac7572ddee4">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a7a8526125b46eeca9eb066fedddefa6f">anonymous{PPCAsmParser.cpp}::PPCAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a8e11393a870b05fc975c383371854ed5">ParseLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#a461ad47a3815838631b7aec404b99d21">parseRefinementStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#a9d20e2079dcd9a868d4b3af67510647b">printSourceLine</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-path-cpp-/#adcc7a3ee32e009943363aac6387302cb">anonymous{Path.cpp}::root_dir_start</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/riscvisautils-cpp/#ae0834ffd88d8197c3afbc8c356cfb27a">singleLetterExtensionRank</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp/#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp/#aed916c3e798f8216e719e7509db44dff">splitUstar</a>.</p>

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
<td class="doxyMemberName">llvm::StringRef::StringRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">data</a> LLVM_LIFETIME_BOUND, size_t length)</td>
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


<p>Complexity: O(<a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<ul class="doxyList ">
<li>Chars, or npos if not found.</li>
</ul>

<p>Note: O(<a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>

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


<p>Complexity: O(<a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<ul class="doxyList ">
<li>Chars, or npos if not found.</li>
</ul>

<p>Note: O(<a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>

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
<td class="doxyMemberName">size_t llvm::StringRef::find_if (function_ref&lt; bool(char)&gt; F, size_t From=0)</td>
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
<td class="doxyMemberName">size_t llvm::StringRef::find_if_not (function_ref&lt; bool(char)&gt; F, size_t From=0)</td>
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
<td class="doxyMemberName">StringRef::size_type StringRef::find_last_not_of (char C, size_t From=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
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
<td class="doxyMemberName">StringRef::size_type StringRef::find_last_not_of (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars, size_t From=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
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


<p>Complexity: O(<a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<ul class="doxyList ">
<li>Chars, or npos if not found.</li>
</ul>

<p>Note: O(<a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>

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
<td class="doxyMemberName">size_t llvm::StringRef::find_last_of (char C, size_t From=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
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
<td class="doxyMemberName">StringRef::size_type StringRef::find_last_of (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars, size_t From=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
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


<p>Complexity: O(<a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<ul class="doxyList ">
<li>C, or npos if not found.</li>
</ul>

<p>Note: O(<a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">size()</a> + Chars.size())</p>


<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/support/stringref-cpp">StringRef.cpp</a>.</p>

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
<td class="doxyMemberName">size_t llvm::StringRef::rfind (char C, size_t From=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
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
<td class="doxyMemberName">size_t StringRef::rfind_insensitive (char C, size_t From=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> has the given suffix and removes that suffix.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> has the given suffix, ignoring case, and removes that suffix.</p>

<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> has the given prefix and removes that prefix.</p>

<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> has the given prefix, ignoring case, and removes that prefix.</p>

<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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

<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this' but with the last <span class="doxyComputerOutput">N</span> elements dropped.</p>

<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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

<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this' but with the first <span class="doxyComputerOutput">N</span> elements dropped.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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
<td class="doxyMemberName">StringRef llvm::StringRef::drop_until (function_ref&lt; bool(char)&gt; F)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this', but with all characters not satisfying the given predicate dropped from the beginning of the string.</p>

<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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
<td class="doxyMemberName">StringRef llvm::StringRef::drop_while (function_ref&lt; bool(char)&gt; F)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this', but with all characters satisfying the given predicate dropped from the beginning of the string.</p>

<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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
<td class="doxyMemberName">StringRef llvm::StringRef::substr (size_t Start, size_t N=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">npos</a>)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this' but with only the last <span class="doxyComputerOutput">N</span> elements remaining.</p>


<p>If <span class="doxyComputerOutput">N</span> is greater than the length of the string, the entire string is returned.</p>


<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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

<p>Return a <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> equal to 'this' but with only the first <span class="doxyComputerOutput">N</span> elements remaining.</p>


<p>If <span class="doxyComputerOutput">N</span> is greater than the length of the string, the entire string is returned.</p>


<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">StringRef.h</a>.</p>

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
<td class="doxyMemberName">StringRef llvm::StringRef::take_until (function_ref&lt; bool(char)&gt; F)</td>
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
<td class="doxyMemberName">StringRef llvm::StringRef::take_while (function_ref&lt; bool(char)&gt; F)</td>
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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
