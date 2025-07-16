---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smallstring
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SmallString` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> - A <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> is just a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with methods and accessors that make it work better as a string (e.g. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;unsigned InternalLen&gt;
class llvm::SmallString&lt;InternalLen&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;T, N&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a 'vector' (really, a variable-sized array), optimized for the case when the array is small. <a href="/web-llvm/docs/api/classes/llvm/smallvector/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5a87b6df67deb0ab86a26be681811eed">SmallString</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default ctor - Initialize to empty. <a href="#a5a87b6df67deb0ab86a26be681811eed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a323c9b7cc38fba25a59541b4c9336c62">SmallString</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#a323c9b7cc38fba25a59541b4c9336c62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af5506265736f3dd65b69c378a216aa6a">SmallString</a> (std::initializer_list&lt; StringRef &gt; Refs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize by concatenating a list of StringRefs. <a href="#af5506265736f3dd65b69c378a216aa6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ItTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac364a1bda29082a5d72c80f79256a677">SmallString</a> (ItTy S, ItTy E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize with a range. <a href="#ac364a1bda29082a5d72c80f79256a677">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## String Assignment Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa43ee1aca8e227bc01f1d8074d8742f">assign</a> (StringRef RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#aaa43ee1aca8e227bc01f1d8074d8742f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a58c641ba5b6900af15d20bb4faee9365">assign</a> (std::initializer_list&lt; StringRef &gt; Refs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign from a list of StringRefs. <a href="#a58c641ba5b6900af15d20bb4faee9365">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## String Concatenation Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac22cf1a1c08b7ccaefc51508536312a4">append</a> (StringRef RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#ac22cf1a1c08b7ccaefc51508536312a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a971504411945012a55fb2b0896bd8bd1">append</a> (std::initializer_list&lt; StringRef &gt; Refs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append from a list of StringRefs. <a href="#a971504411945012a55fb2b0896bd8bd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## String Comparison Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76161f70e45106ec0f5eb486b511d5be">equals</a> (StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for string equality. <a href="#a76161f70e45106ec0f5eb486b511d5be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab2316bb8a6ff1ce90efe6cff6d32c3f3">equals_insensitive</a> (StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for string equality, ignoring case. <a href="#ab2316bb8a6ff1ce90efe6cff6d32c3f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab92cd5fe523c73c94aafcd295688606c">compare</a> (StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>compare - Compare two strings; the result is negative, zero, or positive if this string is lexicographically less than, equal to, or greater than the <span class="doxyComputerOutput">RHS</span>. <a href="#ab92cd5fe523c73c94aafcd295688606c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac66bfad9caed191bc784a03cf248ef0c">compare_insensitive</a> (StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>compare_insensitive - Compare two strings, ignoring case. <a href="#ac66bfad9caed191bc784a03cf248ef0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5dc6cbb11edaab17e562193d8ab71ac">compare_numeric</a> (StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>compare_numeric - Compare two strings, treating sequences of digits as numbers. <a href="#ab5dc6cbb11edaab17e562193d8ab71ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## String Predicates Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9e30dda46fe2b20cf00b33ee9efb3c4">starts_with</a> (StringRef Prefix) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>starts_with - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string starts with the given <span class="doxyComputerOutput">Prefix</span>. <a href="#ab9e30dda46fe2b20cf00b33ee9efb3c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f1b0c312b24ebd6db62d9612a466f46">ends_with</a> (StringRef Suffix) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ends_with - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string ends with the given <span class="doxyComputerOutput">Suffix</span>. <a href="#a6f1b0c312b24ebd6db62d9612a466f46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## String Searching Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6be1163dc11ad30299eba8628e991a46">find</a> (char C, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find - Search for the first character <span class="doxyComputerOutput">C</span> in the string. <a href="#a6be1163dc11ad30299eba8628e991a46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7238e22196b4867a29efb8136ce3e2d2">find</a> (StringRef Str, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the first string <span class="doxyComputerOutput">Str</span> in the string. <a href="#a7238e22196b4867a29efb8136ce3e2d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a80b83aa3cd0b6442a32176b58205d98f">rfind</a> (char C, size_t From=StringRef::npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the last character <span class="doxyComputerOutput">C</span> in the string. <a href="#a80b83aa3cd0b6442a32176b58205d98f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0941cbbd2c07ccf0158dbe7db2885674">rfind</a> (StringRef Str) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for the last string <span class="doxyComputerOutput">Str</span> in the string. <a href="#a0941cbbd2c07ccf0158dbe7db2885674">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae6c79a45fa092aef544c31e4d0eccabf">find_first_of</a> (char C, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the first character in the string that is <span class="doxyComputerOutput">C</span>, or npos if not found. <a href="#ae6c79a45fa092aef544c31e4d0eccabf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b57dd47c8dd51ab940377d19626dd56">find_first_of</a> (StringRef Chars, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the first character in the string that is in <span class="doxyComputerOutput">Chars</span>, or npos if not found. <a href="#a1b57dd47c8dd51ab940377d19626dd56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af9d527e5f895e2b6711438706bfc8edd">find_first_not_of</a> (char C, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the first character in the string that is not <span class="doxyComputerOutput">C</span> or npos if not found. <a href="#af9d527e5f895e2b6711438706bfc8edd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abedeac3aa58a765a33e8a146a8d86e4d">find_first_not_of</a> (StringRef Chars, size_t From=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the first character in the string that is not in the string <span class="doxyComputerOutput">Chars</span>, or npos if not found. <a href="#abedeac3aa58a765a33e8a146a8d86e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4094843dd73069778eb645198365211c">find_last_of</a> (char C, size_t From=StringRef::npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the last character in the string that is <span class="doxyComputerOutput">C</span>, or npos if not found. <a href="#a4094843dd73069778eb645198365211c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d61e42dd3a2c362b5b81e8a49e2db72">find_last_of</a> (StringRef Chars, size_t From=StringRef::npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the last character in the string that is in <span class="doxyComputerOutput">C</span>, or npos if not found. <a href="#a3d61e42dd3a2c362b5b81e8a49e2db72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Helpful Algorithms Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac88d0051f2b3b1fa8501b4daeea7b1f5">count</a> (char C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of occurrences of <span class="doxyComputerOutput">C</span> in the string. <a href="#ac88d0051f2b3b1fa8501b4daeea7b1f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a791bf972fa4fd4d85e7398901b1ea0ec">count</a> (StringRef Str) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of non-overlapped occurrences of <span class="doxyComputerOutput">Str</span> in the string. <a href="#a791bf972fa4fd4d85e7398901b1ea0ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Substring Operations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abab69c8e9372f6a5283db4a059b8d5a0">substr</a> (size_t Start, size_t N=StringRef::npos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the substring from [Start, Start + N). <a href="#abab69c8e9372f6a5283db4a059b8d5a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c3a261582207f6db4cd6d83732e9ac0">slice</a> (size_t Start, size_t End) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the substring from [Start, End). <a href="#a7c3a261582207f6db4cd6d83732e9ac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5dd7241878be5eed07736eb156bb10b">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Explicit conversion to <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#af5dd7241878be5eed07736eb156bb10b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade4b8410fbe0406fc61d1db65d1cfa12">c_str</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa5c7dae1699bd5bf5b900a50fb710566">operator StringRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implicit conversion to <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#aa5c7dae1699bd5bf5b900a50fb710566">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab9d50c6284d5976200ef42a076d3fb02">operator std::string</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a49652a7746515f815c7d4d2572caf2d6">operator=</a> (StringRef RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaebf85b8ceed858f6323120dc8e3e058">operator+=</a> (StringRef RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned InternalLen&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa385d89f74b94cb8e26ac58030b9cdc7">operator+=</a> (char C)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> - A <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> is just a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with methods and accessors that make it work better as a string (e.g.</p>


<p>operator+ etc).</p>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SmallString() {#a5a87b6df67deb0ab86a26be681811eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallString&lt; InternalLen &gt;::SmallString ()</td>
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

<p>Default ctor - Initialize to empty.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### SmallString() {#a323c9b7cc38fba25a59541b4c9336c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallString&lt; InternalLen &gt;::SmallString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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

<p>Initialize from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### SmallString() {#af5506265736f3dd65b69c378a216aa6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallString&lt; InternalLen &gt;::SmallString (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Refs)</td>
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

<p>Initialize by concatenating a list of StringRefs.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### SmallString() {#ac364a1bda29082a5d72c80f79256a677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ItTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallString&lt; InternalLen &gt;::SmallString (ItTy S, ItTy E)</td>
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

<p>Initialize with a range.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## String Assignment

### assign {#aaa43ee1aca8e227bc01f1d8074d8742f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallString&lt; InternalLen &gt;::assign (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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

<p>Assign from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aa1382b606ff796c22a7416ba7f6b856b">llvm::cl::ExpansionContext::findConfigFile</a>, <a href="#a49652a7746515f815c7d4d2572caf2d6">llvm::SmallString&lt; 0 &gt;::operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#af5cd2f517db910af1c9fd3c0cb03161c">llvm::cl::ExpansionContext::readConfigFile</a>.</p>

</div>
</div>

### assign {#a58c641ba5b6900af15d20bb4faee9365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallString&lt; InternalLen &gt;::assign (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Refs)</td>
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

<p>Assign from a list of StringRefs.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## String Concatenation

### append {#ac22cf1a1c08b7ccaefc51508536312a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallString&lt; InternalLen &gt;::append (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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

<p>Append from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>


<p>Referenced by <a href="#a58c641ba5b6900af15d20bb4faee9365">llvm::SmallString&lt; 0 &gt;::assign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd95c4fd57b9c1804bc70a37ac24574">llvm::createCFAOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad301df8bf0c11d0c17113d3c221025d8">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af7b1b04b85a4e865d887cbf6f5889a10">createDefCFAOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/classes/llvm/object/record/#a68447fd5872ee1b7ff3b7bd7d39e0077">llvm::object::Record::getContinuousData</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a84ea0567e15790f68c421dada011ec5f">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/unittest/#aa3aa8b23b1c244615ed10c125922fc05">llvm::unittest::getInputFileDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a061144e3e490f8917de9c53163ef8c01">llvm::OpenMPIRBuilder::getOrCreateSrcLocStr</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a0fec1667ac50cd92d5de25da9c53f704">llvm::GCNTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetmachine/#a42f92645ffc7ba5f2dac57ec1caf08a5">llvm::R600TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a866133bf888d0b8bbce2275845511edb">llvm::TargetLoweringObjectFile::getSymbolWithGlobalValueBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#ae507b357fbb69fc2cb019831c4d66dd8">llvm::sys::unicode::nameToGeneratedCodePoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a9496c295025807ea2778038622f3ba2e">llvm::sys::unicode::nameToHangulCodePoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a2bfecff239f87c7bd19f128186b428a2">llvm::sys::path::native</a>, <a href="#aaebf85b8ceed858f6323120dc8e3e058">llvm::SmallString&lt; 0 &gt;::operator+=</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#abba3a1b37c8d40cefcab729ee016441d">parseBackslash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac12e315180fb16cb5874fb41526ca453">llvm::codegen::setFunctionAttributes</a> and <a href="#af5506265736f3dd65b69c378a216aa6a">llvm::SmallString&lt; 0 &gt;::SmallString</a>.</p>

</div>
</div>

### append {#a971504411945012a55fb2b0896bd8bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallString&lt; InternalLen &gt;::append (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Refs)</td>
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

<p>Append from a list of StringRefs.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## String Comparison

### compare {#ab92cd5fe523c73c94aafcd295688606c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallString&lt; InternalLen &gt;::compare (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### compare\_insensitive {#ac66bfad9caed191bc784a03cf248ef0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallString&lt; InternalLen &gt;::compare_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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

<p>compare_insensitive - Compare two strings, ignoring case.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### compare\_numeric {#ab5dc6cbb11edaab17e562193d8ab71ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallString&lt; InternalLen &gt;::compare_numeric (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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

<p>compare_numeric - Compare two strings, treating sequences of digits as numbers.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### equals {#a76161f70e45106ec0f5eb486b511d5be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallString&lt; InternalLen &gt;::equals (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for string equality.</p>


<p>This is more efficient than <a href="#ab92cd5fe523c73c94aafcd295688606c">compare()</a> when the relative ordering of inequal strings isn't needed.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### equals\_insensitive {#ab2316bb8a6ff1ce90efe6cff6d32c3f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallString&lt; InternalLen &gt;::equals_insensitive (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## String Predicates

### ends\_with {#a6f1b0c312b24ebd6db62d9612a466f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallString&lt; InternalLen &gt;::ends_with (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix)</td>
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

<p>ends_with - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string ends with the given <span class="doxyComputerOutput">Suffix</span>.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### starts\_with {#ab9e30dda46fe2b20cf00b33ee9efb3c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallString&lt; InternalLen &gt;::starts_with (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
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

<p>starts_with - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this string starts with the given <span class="doxyComputerOutput">Prefix</span>.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## String Searching

### find {#a6be1163dc11ad30299eba8628e991a46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::find (char C, size_t From=0)</td>
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

<p>find - Search for the first character <span class="doxyComputerOutput">C</span> in the string.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- The index of the first occurrence of <span class="doxyComputerOutput">C</span>, or npos if not found.</p></dd>
</dl>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### find {#a7238e22196b4867a29efb8136ce3e2d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::find (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, size_t From=0)</td>
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

<p>Search for the first string <span class="doxyComputerOutput">Str</span> in the string.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the first occurrence of <span class="doxyComputerOutput">Str</span>, or npos if not found.</p></dd>
</dl>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### find\_first\_not\_of {#af9d527e5f895e2b6711438706bfc8edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::find_first_not_of (char C, size_t From=0)</td>
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

<p>Find the first character in the string that is not <span class="doxyComputerOutput">C</span> or npos if not found.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### find\_first\_not\_of {#abedeac3aa58a765a33e8a146a8d86e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::find_first_not_of (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars, size_t From=0)</td>
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

<p>Find the first character in the string that is not in the string <span class="doxyComputerOutput">Chars</span>, or npos if not found.</p>


<p>Complexity: O(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size()</a> + Chars.size())</p>


<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### find\_first\_of {#ae6c79a45fa092aef544c31e4d0eccabf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::find_first_of (char C, size_t From=0)</td>
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


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### find\_first\_of {#a1b57dd47c8dd51ab940377d19626dd56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::find_first_of (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars, size_t From=0)</td>
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

<p>Find the first character in the string that is in <span class="doxyComputerOutput">Chars</span>, or npos if not found.</p>


<p>Complexity: O(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size()</a> + Chars.size())</p>


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### find\_last\_of {#a4094843dd73069778eb645198365211c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::find_last_of (char C, size_t From=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">StringRef::npos</a>)</td>
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

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### find\_last\_of {#a3d61e42dd3a2c362b5b81e8a49e2db72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::find_last_of (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Chars, size_t From=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">StringRef::npos</a>)</td>
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

<p>Find the last character in the string that is in <span class="doxyComputerOutput">C</span>, or npos if not found.</p>


<p>Complexity: O(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size()</a> + Chars.size())</p>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### rfind {#a80b83aa3cd0b6442a32176b58205d98f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::rfind (char C, size_t From=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">StringRef::npos</a>)</td>
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


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### rfind {#a0941cbbd2c07ccf0158dbe7db2885674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::rfind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>Search for the last string <span class="doxyComputerOutput">Str</span> in the string.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The index of the last occurrence of <span class="doxyComputerOutput">Str</span>, or npos if not found.</p></dd>
</dl>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Helpful Algorithms

### count {#ac88d0051f2b3b1fa8501b4daeea7b1f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::count (char C)</td>
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

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### count {#a791bf972fa4fd4d85e7398901b1ea0ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallString&lt; InternalLen &gt;::count (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>Return the number of non-overlapped occurrences of <span class="doxyComputerOutput">Str</span> in the string.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Substring Operations

### c\_str {#ade4b8410fbe0406fc61d1db65d1cfa12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::SmallString&lt; InternalLen &gt;::c_str ()</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a59364db4f35eb6929a72d9589afa2718">llvm::DotCfgChangeReporter::genHTML</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a68866f040b091698a4a3bf9c744e263e">llvm::object::XCOFFObjectFile::getSectionFileOffsetToRawData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp/#a5193c36762bd45216d0e979c04df5d49">getVFSEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a8561a3cb89ee3981d033ad4f4074bd07">llvm::DotCfgChangeReporter::registerCallbacks</a> and <a href="/web-llvm/docs/api/groups/set/#gacacf298ae33051bd387434c4ebdd2be7">llvm::ThinLTOCodeGenerator::writeGeneratedObject</a>.</p>

</div>
</div>

### operator std::string {#ab9d50c6284d5976200ef42a076d3fb02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallString&lt; InternalLen &gt;::operator std::string ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### operator StringRef {#aa5c7dae1699bd5bf5b900a50fb710566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallString&lt; InternalLen &gt;::operator StringRef ()</td>
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

<p>Implicit conversion to <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### operator+= {#aaebf85b8ceed858f6323120dc8e3e058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString &amp; llvm::SmallString&lt; InternalLen &gt;::operator+= (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### operator+= {#aa385d89f74b94cb8e26ac58030b9cdc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString &amp; llvm::SmallString&lt; InternalLen &gt;::operator+= (char C)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### operator= {#a49652a7746515f815c7d4d2572caf2d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString &amp; llvm::SmallString&lt; InternalLen &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### slice {#a7c3a261582207f6db4cd6d83732e9ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::SmallString&lt; InternalLen &gt;::slice (size_t Start, size_t End)</td>
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
<td class="doxyParamItemDescription"><p>The index following the last character to include in the substring. If this is npos, or less than <span class="doxyComputerOutput">Start</span>, or exceeds the number of characters remaining in the string, the string suffix (starting with <span class="doxyComputerOutput">Start</span>) will be returned.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

### str {#af5dd7241878be5eed07736eb156bb10b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::SmallString&lt; InternalLen &gt;::str ()</td>
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

<p>Explicit conversion to <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>


<p>Referenced by <a href="#ab92cd5fe523c73c94aafcd295688606c">llvm::SmallString&lt; 0 &gt;::compare</a>, <a href="#ac66bfad9caed191bc784a03cf248ef0c">llvm::SmallString&lt; 0 &gt;::compare_insensitive</a>, <a href="#ab5dc6cbb11edaab17e562193d8ab71ac">llvm::SmallString&lt; 0 &gt;::compare_numeric</a>, <a href="#ac88d0051f2b3b1fa8501b4daeea7b1f5">llvm::SmallString&lt; 0 &gt;::count</a>, <a href="#a791bf972fa4fd4d85e7398901b1ea0ec">llvm::SmallString&lt; 0 &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd95c4fd57b9c1804bc70a37ac24574">llvm::createCFAOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad301df8bf0c11d0c17113d3c221025d8">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af7b1b04b85a4e865d887cbf6f5889a10">createDefCFAOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7d36cf8691cdd5195631e8bbd8d38fc2">llvm::MCStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a32519abee87d93f315f9da6cbeed31cf">emitPPA1Name</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="#a6f1b0c312b24ebd6db62d9612a466f46">llvm::SmallString&lt; 0 &gt;::ends_with</a>, <a href="#a76161f70e45106ec0f5eb486b511d5be">llvm::SmallString&lt; 0 &gt;::equals</a>, <a href="#ab2316bb8a6ff1ce90efe6cff6d32c3f3">llvm::SmallString&lt; 0 &gt;::equals_insensitive</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diasession-cpp/#a07bfb89b80e6e5f6236d958d2b463d2a">ErrorFromHResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="#a6be1163dc11ad30299eba8628e991a46">llvm::SmallString&lt; 0 &gt;::find</a>, <a href="#a7238e22196b4867a29efb8136ce3e2d2">llvm::SmallString&lt; 0 &gt;::find</a>, <a href="#af9d527e5f895e2b6711438706bfc8edd">llvm::SmallString&lt; 0 &gt;::find_first_not_of</a>, <a href="#abedeac3aa58a765a33e8a146a8d86e4d">llvm::SmallString&lt; 0 &gt;::find_first_not_of</a>, <a href="#ae6c79a45fa092aef544c31e4d0eccabf">llvm::SmallString&lt; 0 &gt;::find_first_of</a>, <a href="#a1b57dd47c8dd51ab940377d19626dd56">llvm::SmallString&lt; 0 &gt;::find_first_of</a>, <a href="#a4094843dd73069778eb645198365211c">llvm::SmallString&lt; 0 &gt;::find_last_of</a>, <a href="#a3d61e42dd3a2c362b5b81e8a49e2db72">llvm::SmallString&lt; 0 &gt;::find_last_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79c3f6c8d0e321d8b23f365e485bfde7">llvm::findVCToolChainViaSetupConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a061144e3e490f8917de9c53163ef8c01">llvm::OpenMPIRBuilder::getOrCreateSrcLocStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a18eabcf596deec54ada617114b818baf">llvm::lto::getThinLTOOutputFile</a>, <a href="#aa5c7dae1699bd5bf5b900a50fb710566">llvm::SmallString&lt; 0 &gt;::operator StringRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#af5cd2f517db910af1c9fd3c0cb03161c">llvm::cl::ExpansionContext::readConfigFile</a>, <a href="#a80b83aa3cd0b6442a32176b58205d98f">llvm::SmallString&lt; 0 &gt;::rfind</a>, <a href="#a0941cbbd2c07ccf0158dbe7db2885674">llvm::SmallString&lt; 0 &gt;::rfind</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a9ad2ee389fa99a4c02f610183530735c">llvm::VFABI::setVectorVariantNames</a>, <a href="#a7c3a261582207f6db4cd6d83732e9ac0">llvm::SmallString&lt; 0 &gt;::slice</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#acdaf5010e3f77d9d6e8ae04f5e0248e8">solveTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a2fad224b57541514de4fb5be6eb2e7f1">splitCodeGen</a>, <a href="#ab9e30dda46fe2b20cf00b33ee9efb3c4">llvm::SmallString&lt; 0 &gt;::starts_with</a>, <a href="#abab69c8e9372f6a5283db4a059b8d5a0">llvm::SmallString&lt; 0 &gt;::substr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aff28c3d477d3a7870ec643381f186ed4">llvm::cl::TokenizeGNUCommandLine</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#aaa5adc2409ac3c78b33d4813ff31ae6e">tokenizeWindowsCommandLineImpl</a>.</p>

</div>
</div>

### substr {#abab69c8e9372f6a5283db4a059b8d5a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned InternalLen&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::SmallString&lt; InternalLen &gt;::substr (size_t Start, size_t N=<a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">StringRef::npos</a>)</td>
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
<td class="doxyParamItemDescription"><p>The number of characters to included in the substring. If <span class="doxyComputerOutput">N</span> exceeds the number of characters remaining in the string, the string suffix (starting with <span class="doxyComputerOutput">Start</span>) will be returned.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">SmallString.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
