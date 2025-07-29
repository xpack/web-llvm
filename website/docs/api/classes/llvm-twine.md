---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/twine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Twine` Class

<p><a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> - A lightweight data structure for efficiently representing the concatenation of temporary values as strings. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Twine { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeKind : unsigned char { <a href="#ae98be8710494469d6c40efaa61f89f44">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> - Represent the type of an argument. <a href="#ae98be8710494469d6c40efaa61f89f44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d767c332b69290b84781826d816a710">Twine</a> (NodeKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a nullary twine; the kind must be NullKind or EmptyKind. <a href="#a5d767c332b69290b84781826d816a710">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af86483a2bfb7dc26eacb86488b46c6d8">Twine</a> (const Twine &amp;LHS, const Twine &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a binary twine. <a href="#af86483a2bfb7dc26eacb86488b46c6d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf27712ee42508bb500f473d9d258f74">Twine</a> (Child LHS, NodeKind LHSKind, Child RHS, NodeKind RHSKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a twine from explicit values. <a href="#adf27712ee42508bb500f473d9d258f74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fbefc78d12a82458bd8a3b016c8dc94">isNull</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for the null twine. <a href="#a5fbefc78d12a82458bd8a3b016c8dc94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764ac6dbb0f4fdb8c7e744bd09cc5484">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for the empty twine. <a href="#a764ac6dbb0f4fdb8c7e744bd09cc5484">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a966a551ccd5958d6ca432fcb7fa52655">isNullary</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a nullary twine (null or empty). <a href="#a966a551ccd5958d6ca432fcb7fa52655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2b8aefc03e80aaab8dcfa19a8744ab">isUnary</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a unary twine. <a href="#a6a2b8aefc03e80aaab8dcfa19a8744ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f08fde31fe5e8984dd95085d51f56d">isBinary</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a binary twine. <a href="#ac9f08fde31fe5e8984dd95085d51f56d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ab357dbd1e7d169f20a93a9dc0e131">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a valid twine (satisfying the invariants on order and number of arguments). <a href="#a65ab357dbd1e7d169f20a93a9dc0e131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa878d8038894389c43b36df25a0e516e">getLHSKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> of the left-hand side. <a href="#aa878d8038894389c43b36df25a0e516e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c8acd1ef9ad9b6f301c8d48dd91d67">getRHSKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> of the right-hand side. <a href="#a28c8acd1ef9ad9b6f301c8d48dd91d67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f70d5da0ff35b1686470bc7956700a4">printOneChild</a> (raw_ostream &amp;OS, Child Ptr, NodeKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print one child from a twine. <a href="#a8f70d5da0ff35b1686470bc7956700a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4599c742db5cbdbadbd1258364970ea">printOneChildRepr</a> (raw_ostream &amp;OS, Child Ptr, NodeKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the representation of one child from a twine. <a href="#ad4599c742db5cbdbadbd1258364970ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Child</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb891383e43c1064e26b523b292c8689">LHS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LHS - The prefix in the concatenation, which may be uninitialized for Null or Empty kinds. <a href="#aeb891383e43c1064e26b523b292c8689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Child</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae799adb19e8a234d6a2634f70ccfad8c">RHS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RHS - The suffix in the concatenation, which may be uninitialized for Null or Empty kinds. <a href="#ae799adb19e8a234d6a2634f70ccfad8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39d183b8ea7fbfac7c027c94fda039b7">LHSKind</a> = EmptyKind</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LHSKind - The <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> of the left hand side,. <a href="#a39d183b8ea7fbfac7c027c94fda039b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c747d63733ac13b5ee02cd326cbb88b">RHSKind</a> = EmptyKind</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RHSKind - The <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> of the right hand side,. <a href="#a3c747d63733ac13b5ee02cd326cbb88b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04fc8d246b44aea58511a60ccf88b907">Twine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from an empty string. <a href="#a04fc8d246b44aea58511a60ccf88b907">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9366070d62421e89bb75f41e5184e4cc">Twine</a> (const Twine &amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb94cb6089a1aa378b284c42b2f8a504">Twine</a> (const char *Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from a C string. <a href="#afb94cb6089a1aa378b284c42b2f8a504">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7574a0d1443ab5ae315498557470e9e5">Twine</a> (std::nullptr_t)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete the implicit conversion from nullptr as <a href="#afb94cb6089a1aa378b284c42b2f8a504">Twine(const char *)</a> cannot take nullptr. <a href="#a7574a0d1443ab5ae315498557470e9e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de201eba7873af3b9627cab31592097">Twine</a> (const std::string &amp;Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from an std::string. <a href="#a5de201eba7873af3b9627cab31592097">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d6233e48dd5ffcded847d3ebdda1c1">Twine</a> (const std::string_view &amp;Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from an std::string_view by converting it to a pointer and length. <a href="#aa7d6233e48dd5ffcded847d3ebdda1c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6364bc823d46db1d7a006e079b5f155">Twine</a> (const StringRef &amp;Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#ad6364bc823d46db1d7a006e079b5f155">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab43bcb9fdc325d66d8fe22ad756477">Twine</a> (const StringLiteral &amp;Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from a <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a>. <a href="#aaab43bcb9fdc325d66d8fe22ad756477">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3def23ed26890cbbda3b1d0455f50af3">Twine</a> (const SmallVectorImpl&lt; char &gt; &amp;Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from a <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>. <a href="#a3def23ed26890cbbda3b1d0455f50af3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08489a31d550540c34690735cf712975">Twine</a> (const formatv_object_base &amp;Fmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from a <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base">formatv_object_base</a>. <a href="#a08489a31d550540c34690735cf712975">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed0bbf74f6c5deb651b86e2a5dbe3c21">Twine</a> (char Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from a char. <a href="#aed0bbf74f6c5deb651b86e2a5dbe3c21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f7644a7851a64e48d5b62eca24653f">Twine</a> (signed char Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from a signed char. <a href="#a91f7644a7851a64e48d5b62eca24653f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb5ccf7ec8569cb3f16fdbfd1f7a7c9">Twine</a> (unsigned char Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct from an unsigned char. <a href="#a5eb5ccf7ec8569cb3f16fdbfd1f7a7c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5757eac3d5247ac8a9082a8ab255a55c">Twine</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as an unsigned decimal integer. <a href="#a5757eac3d5247ac8a9082a8ab255a55c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb99044d44bdf1ad73e29ce34438c13c">Twine</a> (int Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as a signed decimal integer. <a href="#acb99044d44bdf1ad73e29ce34438c13c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a711f18b3fe88b4abd108cd48432fda">Twine</a> (const unsigned long &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as an unsigned decimal integer. <a href="#a3a711f18b3fe88b4abd108cd48432fda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e78b9960f64015c905bd426ba716f79">Twine</a> (const long &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as a signed decimal integer. <a href="#a8e78b9960f64015c905bd426ba716f79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af447c6577fd3e018855343c9e45355d7">Twine</a> (const unsigned long long &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as an unsigned decimal integer. <a href="#af447c6577fd3e018855343c9e45355d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c34a97a353f188c0de330a60d572248">Twine</a> (const long long &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as a signed decimal integer. <a href="#a2c34a97a353f188c0de330a60d572248">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ab4e2404f4eed28fd60cc29a7053c2">Twine</a> (const char *LHS, const StringRef &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct as the concatenation of a C string and a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#a66ab4e2404f4eed28fd60cc29a7053c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba6d9549c0ddfa25919915044a81eaf3">Twine</a> (const StringRef &amp;LHS, const char *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct as the concatenation of a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> and a C string. <a href="#aba6d9549c0ddfa25919915044a81eaf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124f1edb1e79a98868c6db0393d7bc34">operator=</a> (const Twine &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Since the intended use of twines is as temporary objects, assignments when concatenating might cause undefined behavior or stack corruptions. <a href="#a124f1edb1e79a98868c6db0393d7bc34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b5b664c92a03c2a098d2effaa48dc18">createNull</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a 'null' string, which is an empty string that always concatenates to form another empty string. <a href="#a8b5b664c92a03c2a098d2effaa48dc18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Predicate Operations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a771462b870698fdc4c2484b78ce96f6d">isTriviallyEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this twine is trivially empty; a false return value does not necessarily mean the twine is empty. <a href="#a771462b870698fdc4c2484b78ce96f6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca739b83d7e5d8adf1b073499099816">isSingleStringLiteral</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this twine is guaranteed to refer to single string literal. <a href="#a7ca739b83d7e5d8adf1b073499099816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c57e3289e5e2f8023da85a982eeff09">isSingleStringRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this twine can be dynamically accessed as a single <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> value with <a href="#adaab019f83b94914fff161592767f663">getSingleStringRef()</a>. <a href="#a2c57e3289e5e2f8023da85a982eeff09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## String Operations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529bd775f25e1c6ea4a96b34a5d8bde6">concat</a> (const Twine &amp;Suffix) const</td>
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

## Output & Conversion. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c1c1093a7749409c70838678514cc7c">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the twine contents as a std::string. <a href="#a4c1c1093a7749409c70838678514cc7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2cc7378ca67e19c45648f7800686933">toVector</a> (SmallVectorImpl&lt; char &gt; &amp;Out) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the concatenated string into the given <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> or <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>. <a href="#ae2cc7378ca67e19c45648f7800686933">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaab019f83b94914fff161592767f663">getSingleStringRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This returns the twine as a single <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#adaab019f83b94914fff161592767f663">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac521760e9a45f304a4cbe46ed4fff845">toStringRef</a> (SmallVectorImpl&lt; char &gt; &amp;Out) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This returns the twine as a single <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> if it can be represented as such. <a href="#ac521760e9a45f304a4cbe46ed4fff845">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d968bc337af0be1f18813553a046df6">toNullTerminatedStringRef</a> (SmallVectorImpl&lt; char &gt; &amp;Out) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This returns the twine as a single null terminated <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> if it can be represented as such. <a href="#a5d968bc337af0be1f18813553a046df6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5879f1eb58da7b477f75f9a980ebf145">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the concatenated string represented by this twine to the stream <span class="doxyComputerOutput">OS</span>. <a href="#a5879f1eb58da7b477f75f9a980ebf145">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61bf259f7bf14d45f68e145f121e1891">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the concatenated string represented by this twine to stderr. <a href="#a61bf259f7bf14d45f68e145f121e1891">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee549d9c78d0c653646407ae1f09b88">printRepr</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the representation of this twine to the stream <span class="doxyComputerOutput">OS</span>. <a href="#a8ee549d9c78d0c653646407ae1f09b88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3748b109893adeac3a84c62f072ffab">dumpRepr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the representation of this twine to stderr. <a href="#af3748b109893adeac3a84c62f072ffab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Numeric Conversions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">utohexstr</a> (const uint64_t &amp;Val)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> - A lightweight data structure for efficiently representing the concatenation of temporary values as strings.</p>


<p>A <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> is a kind of rope, it represents a concatenated string using a binary-tree, where the string is the preorder of the nodes. Since the <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> can be efficiently rendered into a buffer when its result is used, it avoids the cost of generating temporary values for intermediate string results – particularly in cases when the <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> result is never required. By explicitly tracking the type of leaf nodes, we can also avoid the creation of temporary strings for conversions operations (such as appending an integer to a string).</p>


<p>A <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> is not intended for use directly and should not be stored, its implementation relies on the ability to store pointers to temporary stack objects which may be deallocated at the end of a statement. Twines should only be used as const references in arguments, when an API wishes to accept possibly-concatenated strings.</p>


<p>Twines support a special 'null' value, which always concatenates to form itself, and renders as an empty string. This can be returned from APIs to effectively nullify any concatenations performed on the result.</p>


<p><b>Implementation</b></p>


<p>Given the nature of a <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a>, it is not possible for the <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a>'s concatenation method to construct interior nodes; the result must be represented inside the returned value. For this reason a <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> object actually holds two values, the left- and right-hand sides of a concatenation. We also have nullary <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> objects, which are effectively sentinel values that represent empty strings.</p>


<p>Thus, a <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> can effectively have zero, one, or two children. The</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>isNullary(),</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>isUnary(), and</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>isBinary() predicates exist <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> testing the number of <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">children</a>.</p></dd>
</dl>


<p>We maintain a number of invariants on <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> objects (FIXME: Why):</p>


<ul class="doxyList ">
<li>Nullary twines are always represented with their Kind on the left-hand side, and the Empty kind on the right-hand side.</li>
<li>Unary twines are always represented with the value on the left-hand side, and the Empty kind on the right-hand side.</li>
<li>If a <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> has another <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> as a child, that child should always be binary (otherwise it could have been folded into the parent).</li>
</ul>

<p>These invariants are check by</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>isValid().</p></dd>
</dl>


<p><b>Efficiency</b> Considerations</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> is designed to yield efficient and small code for common situations. For this reason, the <a href="#a529bd775f25e1c6ea4a96b34a5d8bde6">concat()</a> method is inlined so that concatenations of leaf nodes can be optimized into stores directly into a single stack allocated object.</p>


<p>In practice, not all compilers can be trusted to optimize <a href="#a529bd775f25e1c6ea4a96b34a5d8bde6">concat()</a> fully, so we provide two additional methods (and accompanying operator+ overloads) to guarantee that particularly important cases (cstring plus <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>) codegen as desired.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### NodeKind {#ae98be8710494469d6c40efaa61f89f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Twine::NodeKind : unsigned char</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> - Represent the type of an argument.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NullKind<a id="ae98be8710494469d6c40efaa61f89f44a25cc4e556b1991bb2d781374bea78c72"></a></td>
<td class="doxyEnumItemDescription">An empty string; the result of concatenating anything with it is also empty</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EmptyKind<a id="ae98be8710494469d6c40efaa61f89f44a2722f0ad343b43acc4335c3823428618"></a></td>
<td class="doxyEnumItemDescription">The empty string</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TwineKind<a id="ae98be8710494469d6c40efaa61f89f44a17cf013e9864f909375f0210c9fd40fc"></a></td>
<td class="doxyEnumItemDescription">A pointer to a <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> instance</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CStringKind<a id="ae98be8710494469d6c40efaa61f89f44a41681d6acfb1efc27b661dc62378f2ff"></a></td>
<td class="doxyEnumItemDescription">A pointer to a C string instance</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StdStringKind<a id="ae98be8710494469d6c40efaa61f89f44a62b9ed32b53038968b2e206289832dfe"></a></td>
<td class="doxyEnumItemDescription">A pointer to an std::string instance</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PtrAndLengthKind<a id="ae98be8710494469d6c40efaa61f89f44abe6c861ad89c6a19aaab973b510d2b2a"></a></td>
<td class="doxyEnumItemDescription">A Pointer and Length representation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StringLiteralKind<a id="ae98be8710494469d6c40efaa61f89f44a64de35f9294cc76c43485980410a32d2"></a></td>
<td class="doxyEnumItemDescription">A pointer and length representation that's also null-terminated</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FormatvObjectKind<a id="ae98be8710494469d6c40efaa61f89f44ad53cacfe1963ed207dbbfaaea7ce2b35"></a></td>
<td class="doxyEnumItemDescription">A pointer to a <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base">formatv_object_base</a> instance</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CharKind<a id="ae98be8710494469d6c40efaa61f89f44a13a8222fc2df927d9df193c1eda9beaa"></a></td>
<td class="doxyEnumItemDescription">A char value, to render as a character</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DecUIKind<a id="ae98be8710494469d6c40efaa61f89f44a544ded0201243d379b553d88a9ec68e5"></a></td>
<td class="doxyEnumItemDescription">An unsigned int value, to render as an unsigned decimal integer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DecIKind<a id="ae98be8710494469d6c40efaa61f89f44a91abda31eeee29c110c314df684522bf"></a></td>
<td class="doxyEnumItemDescription">An int value, to render as a signed decimal integer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DecULKind<a id="ae98be8710494469d6c40efaa61f89f44a8c468f8e17b1994dafb5b2da77dcdc26"></a></td>
<td class="doxyEnumItemDescription">A pointer to an unsigned long value, to render as an unsigned decimal integer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DecLKind<a id="ae98be8710494469d6c40efaa61f89f44aa1faab5524049b668399fbb0b2131e70"></a></td>
<td class="doxyEnumItemDescription">A pointer to a long value, to render as a signed decimal integer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DecULLKind<a id="ae98be8710494469d6c40efaa61f89f44a6b5b8228745d115187223d799ae3ea46"></a></td>
<td class="doxyEnumItemDescription">A pointer to an unsigned long long value, to render as an unsigned decimal integer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DecLLKind<a id="ae98be8710494469d6c40efaa61f89f44ab17435a7a66ba9c05c3950885dd559bd"></a></td>
<td class="doxyEnumItemDescription">A pointer to a long long value, to render as a signed decimal integer</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UHexKind<a id="ae98be8710494469d6c40efaa61f89f44a12e3438550f4922c4948ac770f48ea34"></a></td>
<td class="doxyEnumItemDescription">A pointer to a uint64_t value, to render as an unsigned hexadecimal integer</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Twine() {#a5d767c332b69290b84781826d816a710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> Kind)</td>
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

<p>Construct a nullary twine; the kind must be NullKind or EmptyKind.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine() {#af86483a2bfb7dc26eacb86488b46c6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; RHS)</td>
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

<p>Construct a binary twine.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine() {#adf27712ee42508bb500f473d9d258f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (Child LHS, <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> LHSKind, Child RHS, <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> RHSKind)</td>
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

<p>Construct a twine from explicit values.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getLHSKind() {#aa878d8038894389c43b36df25a0e516e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeKind llvm::Twine::getLHSKind ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> of the left-hand side.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### getRHSKind() {#a28c8acd1ef9ad9b6f301c8d48dd91d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeKind llvm::Twine::getRHSKind ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> of the right-hand side.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### isBinary() {#ac9f08fde31fe5e8984dd95085d51f56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Twine::isBinary ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a binary twine.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### isEmpty() {#a764ac6dbb0f4fdb8c7e744bd09cc5484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Twine::isEmpty ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for the empty twine.</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### isNull() {#a5fbefc78d12a82458bd8a3b016c8dc94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Twine::isNull ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for the null twine.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### isNullary() {#a966a551ccd5958d6ca432fcb7fa52655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Twine::isNullary ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a nullary twine (null or empty).</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### isUnary() {#a6a2b8aefc03e80aaab8dcfa19a8744ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Twine::isUnary ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a unary twine.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### isValid() {#a65ab357dbd1e7d169f20a93a9dc0e131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Twine::isValid ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a valid twine (satisfying the invariants on order and number of arguments).</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### printOneChild() {#a8f70d5da0ff35b1686470bc7956700a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Twine::printOneChild (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, Child Ptr, <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print one child from a twine.</p>

<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a>.</p>

</div>
</div>

### printOneChildRepr() {#ad4599c742db5cbdbadbd1258364970ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Twine::printOneChildRepr (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, Child Ptr, <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the representation of one child from a twine.</p>

<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LHS {#aeb891383e43c1064e26b523b292c8689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Child llvm::Twine::LHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LHS - The prefix in the concatenation, which may be uninitialized for Null or Empty kinds.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### LHSKind {#a39d183b8ea7fbfac7c027c94fda039b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeKind llvm::Twine::LHSKind = EmptyKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LHSKind - The <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> of the left hand side,.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>getLHSKind().</p></dd>
</dl>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### RHS {#ae799adb19e8a234d6a2634f70ccfad8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Child llvm::Twine::RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RHS - The suffix in the concatenation, which may be uninitialized for Null or Empty kinds.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### RHSKind {#a3c747d63733ac13b5ee02cd326cbb88b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeKind llvm::Twine::RHSKind = EmptyKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RHSKind - The <a href="/web-llvm/docs/api/structs/nodekind">NodeKind</a> of the right hand side,.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>getRHSKind().</p></dd>
</dl>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Constructors

### createNull {#a8b5b664c92a03c2a098d2effaa48dc18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Twine llvm::Twine::createNull ()</td>
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

<p>Create a 'null' string, which is an empty string that always concatenates to form another empty string.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="#a04fc8d246b44aea58511a60ccf88b907">Twine</a>.</p>

</div>
</div>

### operator= {#a124f1edb1e79a98868c6db0393d7bc34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Twine &amp; llvm::Twine::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp;)</td>
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

<p>Since the intended use of twines is as temporary objects, assignments when concatenating might cause undefined behavior or stack corruptions.</p>

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#a04fc8d246b44aea58511a60ccf88b907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine ()</td>
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

<p>Construct from an empty string.</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a529bd775f25e1c6ea4a96b34a5d8bde6">concat</a>, <a href="#a8b5b664c92a03c2a098d2effaa48dc18">createNull</a> and <a href="#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">utohexstr</a>.</p>

</div>
</div>

### Twine {#a9366070d62421e89bb75f41e5184e4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp;)</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#afb94cb6089a1aa378b284c42b2f8a504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str)</td>
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

<p>Construct from a C string.</p>


<p>We take care here to optimize "" into the empty twine – this will be optimized out for string constants. This allows <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> arguments have default "" values, without introducing unnecessary string constants.</p>


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### Twine {#a7574a0d1443ab5ae315498557470e9e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (std::nullptr_t)</td>
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

<p>Delete the implicit conversion from nullptr as <a href="#afb94cb6089a1aa378b284c42b2f8a504">Twine(const char *)</a> cannot take nullptr.</p>

<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#a5de201eba7873af3b9627cab31592097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Str)</td>
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

<p>Construct from an std::string.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### Twine {#aa7d6233e48dd5ffcded847d3ebdda1c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string_view &amp; Str)</td>
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

<p>Construct from an std::string_view by converting it to a pointer and length.</p>


<p>This handles string_views on a pure API basis, and avoids storing one (or a pointer to one) inside a <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a>, which avoids problems when mixing code compiled under various C++ standards.</p>


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### Twine {#ad6364bc823d46db1d7a006e079b5f155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Str)</td>
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

<p>Construct from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### Twine {#aaab43bcb9fdc325d66d8fe22ad756477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> &amp; Str)</td>
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

<p>Construct from a <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a>.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### Twine {#a3def23ed26890cbbda3b1d0455f50af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str)</td>
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

<p>Construct from a <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>.</p>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### Twine {#a08489a31d550540c34690735cf712975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base">formatv_object_base</a> &amp; Fmt)</td>
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

<p>Construct from a <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base">formatv_object_base</a>.</p>

<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### Twine {#aed0bbf74f6c5deb651b86e2a5dbe3c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (char Val)</td>
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

<p>Construct from a char.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#a91f7644a7851a64e48d5b62eca24653f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (signed char Val)</td>
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

<p>Construct from a signed char.</p>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#a5eb5ccf7ec8569cb3f16fdbfd1f7a7c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (unsigned char Val)</td>
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

<p>Construct from an unsigned char.</p>

<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#a5757eac3d5247ac8a9082a8ab255a55c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (unsigned Val)</td>
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

<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as an unsigned decimal integer.</p>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#acb99044d44bdf1ad73e29ce34438c13c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (int Val)</td>
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

<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as a signed decimal integer.</p>

<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#a3a711f18b3fe88b4abd108cd48432fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned long &amp; Val)</td>
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

<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as an unsigned decimal integer.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#a8e78b9960f64015c905bd426ba716f79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> long &amp; Val)</td>
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

<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as a signed decimal integer.</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#af447c6577fd3e018855343c9e45355d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned long long &amp; Val)</td>
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

<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as an unsigned decimal integer.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#a2c34a97a353f188c0de330a60d572248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> long long &amp; Val)</td>
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

<p>Construct a twine to print <span class="doxyComputerOutput">Val</span> as a signed decimal integer.</p>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### Twine {#a66ab4e2404f4eed28fd60cc29a7053c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; RHS)</td>
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

<p>Construct as the concatenation of a C string and a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### Twine {#aba6d9549c0ddfa25919915044a81eaf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Twine::Twine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RHS)</td>
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

<p>Construct as the concatenation of a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> and a C string.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Predicate Operations

### isSingleStringLiteral {#a7ca739b83d7e5d8adf1b073499099816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Twine::isSingleStringLiteral ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this twine is guaranteed to refer to single string literal.</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>

</div>
</div>

### isSingleStringRef {#a2c57e3289e5e2f8023da85a982eeff09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Twine::isSingleStringRef ()</td>
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

<p>Return true if this twine can be dynamically accessed as a single <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> value with <a href="#adaab019f83b94914fff161592767f663">getSingleStringRef()</a>.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Referenced by <a href="#adaab019f83b94914fff161592767f663">getSingleStringRef</a> and <a href="#ac521760e9a45f304a4cbe46ed4fff845">toStringRef</a>.</p>

</div>
</div>

### isTriviallyEmpty {#a771462b870698fdc4c2484b78ce96f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Twine::isTriviallyEmpty ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this twine is trivially empty; a false return value does not necessarily mean the twine is empty.</p>

<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1b070d2edba351e90bf5a08b656895a5">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#abfbfa4b8157b753fa4ea370e8ffc8177">llvm::MCContext::getELFSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aec55174841f8aa80f2d1c3f56c4165af">llvm::MCContext::getWasmSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## String Operations

### concat {#a529bd775f25e1c6ea4a96b34a5d8bde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Twine llvm::Twine::concat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Suffix)</td>
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



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="#a04fc8d246b44aea58511a60ccf88b907">Twine</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a9313c0181a7f6ea6097163d55a4a7694">LiveDebugValues::ValueIDNum::asString</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a5a25bb817d51790574c718d2a39bfafc">llvm::SystemZAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a90b631351c27f8d64f1788ec334d7b4c">llvm::COFF::encodeSectionName</a> and <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#afe9d19d27dd82ae73f86937cb41c3d8b">LiveDebugValues::MLocTracker::LocIdxToName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Output & Conversion.

### dump {#a61bf259f7bf14d45f68e145f121e1891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Twine::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the concatenated string represented by this twine to stderr.</p>

<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a5879f1eb58da7b477f75f9a980ebf145">print</a>.</p>

</div>
</div>

### dumpRepr {#af3748b109893adeac3a84c62f072ffab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Twine::dumpRepr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the representation of this twine to stderr.</p>

<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a8ee549d9c78d0c653646407ae1f09b88">printRepr</a>.</p>

</div>
</div>

### getSingleStringRef {#adaab019f83b94914fff161592767f663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Twine::getSingleStringRef ()</td>
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

<p>This returns the twine as a single <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>This method is only valid if <a href="#a2c57e3289e5e2f8023da85a982eeff09">isSingleStringRef()</a> is true.</p>


<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2c57e3289e5e2f8023da85a982eeff09">isSingleStringRef</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ac521760e9a45f304a4cbe46ed4fff845">toStringRef</a>.</p>

</div>
</div>

### print {#a5879f1eb58da7b477f75f9a980ebf145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Twine::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the concatenated string represented by this twine to the stream <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a>.</p>


<p>Referenced by <a href="#a61bf259f7bf14d45f68e145f121e1891">dump</a> and <a href="#ae2cc7378ca67e19c45648f7800686933">toVector</a>.</p>

</div>
</div>

### printRepr {#a8ee549d9c78d0c653646407ae1f09b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Twine::printRepr (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the representation of this twine to the stream <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a>.</p>


<p>Referenced by <a href="#af3748b109893adeac3a84c62f072ffab">dumpRepr</a>.</p>

</div>
</div>

### str {#a4c1c1093a7749409c70838678514cc7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Twine::str ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the twine contents as a std::string.</p>

<p>Declaration at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="#ac521760e9a45f304a4cbe46ed4fff845">toStringRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a579d9746f682510cdf39fa41ec15f1e4">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::annotateValueSites</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a9313c0181a7f6ea6097163d55a4a7694">LiveDebugValues::ValueIDNum::asString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a071f65a20661e8049db465eae188ec72">llvm::IndexedInstrProfReader::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfb4003f85c99f6a1f08b3eb8e6c2f24">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#aa192c95c53dffca890dcffcae58795f0">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#a1e1abb9a350cc753be1d650c8f638d02">llvm::vfs::InMemoryFileSystem::dir_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/overlayfilesystem/#a1d54f01610acbc6fea338e2fb536b332">llvm::vfs::OverlayFileSystem::dir_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bcb59321c16a818145d3612817405d1">llvm::dumpDotGraphToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgmst/#af6d53cb002b3fe8f7c4b7a7c3323e4c0">llvm::CFGMST&lt; Edge, BBInfo &gt;::dumpEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a5a25bb817d51790574c718d2a39bfafc">llvm::SystemZAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase/#a3aa88beff46b705033cfc09293ba298a">anonymous{BitcodeReader.cpp}::BitcodeReaderBase::error</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d46d39efe0be42a72faf3e6db59de3f">anonymous{MIParser.cpp}::MIParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0219c7f9cad07740ec0c2d18dac6e946">llvm::MIRParserImpl::error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp/#a6234057413147a09e2c1a0301ed7d452">formatPax</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#abfbfa4b8157b753fa4ea370e8ffc8177">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acdf08ebc749ce91001ea768a16da0605">llvm::SourceMgr::GetMessage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a050c6067c2ae7c978f8d5100535e7188">llvm::getVacantFunctionName</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aec55174841f8aa80f2d1c3f56c4165af">llvm::MCContext::getWasmSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a7cfdf685d3e6d53df20862a50ccea04c">llvm::DotCfgChangeReporter::handleFunctionCompare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#afe9d19d27dd82ae73f86937cb41c3d8b">LiveDebugValues::MLocTracker::LocIdxToName</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversal-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp/#aee6196bb67ae710bbbd44101ea42fc62">mapNameAndUniqueName</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/owneddatasection/#a33aa4c4dba6ab5ab068d0fb53e1bc08b">llvm::objcopy::elf::OwnedDataSection::OwnedDataSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/dxcontainer-cpp/#a5886aa63fbfc1a912ed38486a3db7131">parseFailed</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fa39647aed67bc62e126a8d8812900f">llvm::prepareTempFiles</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a2552b5ad0f8384773bd8c70dc002b0c6">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::readCounters</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a8e9af968db2378a07e8ccc04d6e100b5">anonymous{MachineVerifier.cpp}::MachineVerifier::report</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66fc8969d714a36fb8b4918753d1b973">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#aa2f5ef2d522fb80de283a23d5bed6d86">llvm::LoopVectorizeHints::setAlreadyVectorized</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a693592fa7e2d0950e30d14f38c333f9b">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::setBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a2bd1c53f9607876b22c6fd3ec1e28a50">llvm::VPBlockBase::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a242fb01fcd9fab0be0f487b67fd94a0a">llvm::VPlan::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="#a5d968bc337af0be1f18813553a046df6">toNullTerminatedStringRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddgprinter-cpp/#a71e8ed869925000e787e5006af42d440">writeDDGToDotFile</a>.</p>

</div>
</div>

### toNullTerminatedStringRef {#a5d968bc337af0be1f18813553a046df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Twine::toNullTerminatedStringRef (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This returns the twine as a single null terminated <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> if it can be represented as such.</p>


<p>Otherwise the twine is written into the given <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> and a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> to the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>'s data is returned.</p>


<p>The returned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>'s size does not include the null terminator.</p>


<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a4c1c1093a7749409c70838678514cc7c">str</a> and <a href="#ae2cc7378ca67e19c45648f7800686933">toVector</a>.</p>

</div>
</div>

### toStringRef {#ac521760e9a45f304a4cbe46ed4fff845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Twine::toStringRef (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Out)</td>
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

<p>This returns the twine as a single <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> if it can be represented as such.</p>


<p>Otherwise the twine is written into the given <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> and a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> to the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>'s data is returned.</p>


<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="#adaab019f83b94914fff161592767f663">getSingleStringRef</a>, <a href="#a2c57e3289e5e2f8023da85a982eeff09">isSingleStringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#ae2cc7378ca67e19c45648f7800686933">toVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1b070d2edba351e90bf5a08b656895a5">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4c89d112b2f04f66826428c19d11301b">llvm::DwarfCompileUnit::createBaseTypeDIEs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/mangler-cpp/#a608b7db33905c3d2bd010323d0da431a">getNameWithPrefixImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4cb6ea02c3dec9abe04c03e501c60f75">llvm::WritableMemoryBuffer::getNewUninitMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/stringsaver/#a7f24e6f171c4fa23feb067e1a5885b89">llvm::StringSaver::save</a>, <a href="/web-llvm/docs/api/classes/llvm/uniquestringsaver/#ab1d26a0bd554591bd9d67412671c24dd">llvm::UniqueStringSaver::save</a> and <a href="#a4c1c1093a7749409c70838678514cc7c">str</a>.</p>

</div>
</div>

### toVector {#ae2cc7378ca67e19c45648f7800686933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Twine::toVector (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append the concatenated string into the given <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a> or <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>.</p>

<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a>.</p>


<p>Reference <a href="#a5879f1eb58da7b477f75f9a980ebf145">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#a189e6cc46ddc7ca69bddd7f1a757a736">llvm::MCAsmParser::addErrorSuffix</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#ac01074de42130f7440672e8b2ba920e3">llvm::vfs::InMemoryFileSystem::addSymbolicLink</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a5edc743f072765fe8146c1f597d4bb37">llvm::vfs::RedirectingFileSystem::dir_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a90b631351c27f8d64f1788ec334d7b4c">llvm::COFF::encodeSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#afe58695435b93e0599ed2f77e877a0aa">llvm::MCAsmParser::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a0a4a25ca3fa9ef5bb3246ca2162f4f96">llvm::vfs::RedirectingFileSystem::exists</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a716fd28e6537ab39f3d930edfb00dc66">llvm::vfs::RedirectingFileSystem::getRealPath</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a68866f040b091698a4a3bf9c744e263e">llvm::object::XCOFFObjectFile::getSectionFileOffsetToRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a927f391dc40ec58157bc3456784ab726">llvm::vfs::RedirectingFileSystem::isLocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a756f82cf24e75f443c6f032253d84dba">llvm::vfs::RedirectingFileSystem::openFileForRead</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a041113ae9c86afaf78aca845b270af82">llvm::vfs::RedirectingFileSystem::status</a>, <a href="#a5d968bc337af0be1f18813553a046df6">toNullTerminatedStringRef</a> and <a href="#ac521760e9a45f304a4cbe46ed4fff845">toStringRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Numeric Conversions

### utohexstr {#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Twine llvm::Twine::utohexstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t &amp; Val)</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a>.</p>


<p>Reference <a href="#a04fc8d246b44aea58511a60ccf88b907">Twine</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#abdb9058a51e2fb5fd61d203dcdfd551a">llvm::AppleAcceleratorTable::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/blockcoverageinference/#a0091b4d3d6e228e4b82c8cdb56363754">llvm::BlockCoverageInference::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/abbrev/#a0b9212db2d5fa1d5401e9b5c036abd17">llvm::DWARFDebugNames::Abbrev::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex/#a6a576c0df9fdee3ab02b174cba3cc169">llvm::DWARFDebugNames::NameIndex::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry/#aeb639b3c403a927db9dd576cd989339d">llvm::DWARFDebugNames::Entry::dumpParentIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a258100c512356fe24a12a14fc7ad9d78">llvm::DWARFYAML::emitDebugRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1bcc04bcd84245c861201c01d2cc1a4c">llvm::AsmPrinter::emitDwarfDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a5a25bb817d51790574c718d2a39bfafc">llvm::SystemZAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af00b13d92054d7b6f7c8b4561f46685b">llvm::BTFTypeBase::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypeenum64/#aeeff33f4503f3e3724197047123252d1">llvm::BTFTypeEnum64::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypeint/#a223d1876a944b2ee9c675f502651a8a1">llvm::BTFTypeInt::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypestruct/#a261288152d81e6ee565d7c68d175624e">llvm::BTFTypeStruct::emitType</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6c8bb3c922ce45c595377546d41f1222">llvm::objcopy::elf::ASCIIHexWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#a5b9da0f3636f00c8eb9dca28bf21e606">llvm::objcopy::elf::BinaryWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#a96ec94d70c19707787f756fa97cc3467">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#abbad376da1ca0cfd01c2e5effa9fad42">fixupIndexV4</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aec2829b5961eb9e3db39ab8340a361dd">fixupIndexV5</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a98e19eaf03c9744a18996776d77d0ee1">llvm::object::ELFFile&lt; ELFT &gt;::getEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a73d59676cde66e2b3b227b524b35f891">getGlobalSymtabLocAndSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a81ef70b0779ce0c0e0f41c320c1f355a">llvm::object::XCOFFObjectFile::getImportFileTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a328dcddbae94eecadd48eb5d7986e2cb">llvm::object::getLoaderSecSymNameInStrTbl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#acd35d32e09260ea392203103e472465c">llvm::object::XCOFFObjectFile::getRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a9800b5c811f6cb665c2c118d1ceccb54">llvm::object::XCOFFObjectFile::getSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ae1123dddef9e813facbc60595e9427f8">llvm::object::ELFFile&lt; ELFT &gt;::getSectionContentsAsArray</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a68866f040b091698a4a3bf9c744e263e">llvm::object::XCOFFObjectFile::getSectionFileOffsetToRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a1b21b0b6b92569afb3b677c440ecb3b6">llvm::object::ELFFile&lt; ELFT &gt;::getSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a464c7849464818cb8c8f45b84d375f8c">llvm::object::ELFFile&lt; ELFT &gt;::getSegmentContents</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a928be9f8ad2d5fda0dc77b3e55fa352d">llvm::object::XCOFFObjectFile::getStringTableEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a20ac73b763595fb7dd3d76f6a221408c">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDefinitions</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a6d7f36df9f1e78161aa1117443ec74e1">llvm::object::ELFFile&lt; ELFT &gt;::getVersionDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a1a0331e763d1ccb3e64db8de4d9791c8">handleArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a0b01026129dcc250501775442ac4b2e5">llvm::object::XCOFFSymbolRef::isFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportentry/#a0ec56e47067ae8d2239c5da9d6ae8418">llvm::object::ExportEntry::moveNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry/#a4a875fa809c0df5dff3223d539ae4c7c">llvm::object::MachOBindEntry::moveNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machorebaseentry/#aa36d5eb1318336e34265a7c2cc87b604">llvm::object::MachORebaseEntry::moveNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a5d91616c8a62b5988aa2570be36c7912">llvm::object::ELFFile&lt; ELF32LE &gt;::notes_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a472b2e829986b644129759fb3249df7c">llvm::object::ELFFile&lt; ELF32LE &gt;::notes_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#aeb88a873af45ca9f6207336e0b468856">llvm::ELFAttributeParser::parseAttributeList</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a02d8a789e50e085fa66aac9180bb03f3">llvm::ELFAttributeParser::parseSubsection</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbits/#a0d9c0e9003a093505555e8051a6c7c91">llvm::DemandedBits::print</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#abbc181f7d08ad3f2e82a96f055dc77ff">llvm::object::WasmSymbol::print</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a163b3801bc893a415f20cc091f7a246a">llvm::MipsAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aaf013089b3c23b831d93d1bd97440809">llvm::logicalview::LVElement::printLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a23f075e7a28f48f0f37a416bda54c16a">llvm::MCSectionELF::printSwitchToSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#a685264b0f25cd162e8b4e85365aee004">llvm::object::ELFFile&lt; ELF32LE &gt;::program_headers</a>, <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingreader-cpp-/versionedcovmapfuncrecordreader/#a7e1679b2628896a1b7e2299c92776503">anonymous{CoverageMappingReader.cpp}::VersionedCovMapFuncRecordReader&lt; Version, IntPtrT, Endian &gt;::readFunctionRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#a817b6babbfd3e8ca145b869d93903f26">readULEB128As</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#adeb534d315c9a390fc59cdef8e9f261a">llvm::object::XCOFFObjectFile::relocations</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ab64e03f049c8588f24e0ec69a568aef9">llvm::object::ELFFile&lt; ELFT &gt;::sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#a85f505b1020d2df805bc40316a26e73b">llvm::symbolize::toHex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#abf0867b6082e1e0408b1b5d8301f27e2">llvm::object::ELFFile&lt; ELFT &gt;::toMappedAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#af405cf94e28aca3f12c108ff0b858aee">llvm::AMDGPUPALMetadata::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#a664a6fc223b56ef4fec7642360062ae0">llvm::objcopy::macho::MachOWriter::write</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/xcoff/xcoffwriter/#af3adedc8850f537a3ba8e71bba9d9934">llvm::objcopy::xcoff::XCOFFWriter::write</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">Twine.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/twine-cpp">Twine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
