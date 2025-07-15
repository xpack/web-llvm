---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msgpack/docnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocNode` Class Reference

<p>A node in a MsgPack <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::msgpack::DocNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">llvm/BinaryFormat/MsgPackDocument.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-msgpackdocumentyaml-cpp-/scalardocnode">ScalarDocNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">ArrayDocNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> that is an array. <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> that is a map. <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &gt; <a href="#a4c045ba223a97b258ea4a6e1e76b7727">MapTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &gt; <a href="#ad07796bcfea70271f5cf0ee66cf568b4">ArrayTy</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af099df7fdeb0a2166422c07f49d6bc2e">operator&lt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparison operator, used for map keys. <a href="#af099df7fdeb0a2166422c07f49d6bc2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae006229abbf967ac3621ff55449bec97">operator==</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equality operator. <a href="#ae006229abbf967ac3621ff55449bec97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da5bccd57f0fae730723500f95a27d1">operator!=</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inequality operator. <a href="#a2da5bccd57f0fae730723500f95a27d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a> ()</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40014dd3e48978775e958a55d7a066f2">DocNode</a> (const KindAndDocument *KindAndDoc)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add2f7af8865179511cd97536891b2a9b">operator=</a> (const char *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience assignment operators. <a href="#add2f7af8865179511cd97536891b2a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b9b31645cb2a12ab5c315725ba367b1">operator=</a> (StringRef Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae799c9c9dda75bf386ee714a0db638a8">operator=</a> (MemoryBufferRef Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85f28c20e0b68d334f63d60d21ab7109">operator=</a> (bool Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f88e6587461103193f66c63999b6b36">operator=</a> (int Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31b00a8fa469faa012f219a7f9466a1">operator=</a> (unsigned Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091cbf7795bca9759a7f6aa86c692dfc">operator=</a> (int64_t Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0312cc6e961a6b29ea43d313e17f3009">operator=</a> (uint64_t Val)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78440e992da7b87645bb9c7cdb1b6525">isMap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7baf73f31a4531f8214a287c9c107fcc">isArray</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5d944e39d3c2e6fd1506cbd0233b0a">isScalar</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae42f124309dd69121f263493140d42e9">isString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe1ba2052b98cee8a31531493c21f559">isEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4f91a68659f7a8c187d90a4df0dbef">getInt</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa6a49447da74e0bada4f145edd396b">getUInt</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4af140c3e423107e247c5006c1bf77">getBool</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8be6946946420c6d24fc9ea15517710">getFloat</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa277de8aa2d01d1433cd7f89313eff2d">getInt</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cfe6dfec5382df543e9b7bdde2f1c7d">getUInt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa662b79ae64dc169fd355a7663a74b4e">getBool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab03e3e668e37afc0a9c943a484a341cc">getFloat</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c069948272b8ae450480529a12de56">getString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86803dfd1becb1430368f0b11abd59b0">getBinary</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">ArrayDocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e993c73d12663a129d46cd3e1fb1b5">getArray</a> (bool Convert=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">ArrayDocNode</a> for an array node. <a href="#a83e993c73d12663a129d46cd3e1fb1b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01acd23f4e4e583c9eaf2c03923b157e">getMap</a> (bool Convert=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a> for a map node. <a href="#a01acd23f4e4e583c9eaf2c03923b157e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9126e4f825db5a1bb881098b9159279">toString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this node to a string, assuming it is scalar. <a href="#ab9126e4f825db5a1bb881098b9159279">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a2160ffa04d67291e2827a29994a3b9">fromString</a> (StringRef S, StringRef Tag="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> and use it to set this <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> (assuming scalar). <a href="#a0a2160ffa04d67291e2827a29994a3b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea49aa48058a9188cbf2d71b72ded5b4">convertToArray</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3c173357bac77f0b59ada24f440dab">convertToMap</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb061766f4e001718ae4251934a2e0c">Int</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202099b1cc31ee4232aaba6c6915cc04">UInt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a84205a3d702965fcd2311b8682cab">Bool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb051a27faf2e7374888d7daf2dbf5e0">Float</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11eead64fd1638c3aae26c25443c7179">Raw</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad07796bcfea70271f5cf0ee66cf568b4">ArrayTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603b51266c0e0421d37f7cc6cd6fb20b">Array</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4c045ba223a97b258ea4a6e1e76b7727">MapTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc097d224c8c39ed85b9a938e11a36e">Map</a></td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">llvm::msgpack::DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c3b4521d1be8034bdd593069d878d81"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac19bb66fedc4f2a731ecf6b665c66558">Document</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/msgpack/kindanddocument">KindAndDocument</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e01898e88fcecbfd6a3d3f450fa800f">KindAndDoc</a></td>
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

<p>A node in a MsgPack <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>.</p>


<p>This is a simple copyable and passable-by-value type that does not own any memory.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ArrayTy {#ad07796bcfea70271f5cf0ee66cf568b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;DocNode&gt; llvm::msgpack::DocNode::ArrayTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### MapTy {#a4c045ba223a97b258ea4a6e1e76b7727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::map&lt;DocNode, DocNode&gt; llvm::msgpack::DocNode::MapTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator!= {#a2da5bccd57f0fae730723500f95a27d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp; Lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp; Rhs</td>
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

<p>Inequality operator.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>.</p>

</div>
</div>

### operator&lt; {#af099df7fdeb0a2166422c07f49d6bc2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp; Lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp; Rhs</td>
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

<p>Comparison operator, used for map keys.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a6ce976e8f061b2b5cfe4d0c50c3405dd">llvm::msgpack::Binary</a>, <a href="#a19a84205a3d702965fcd2311b8682cab">Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a>, <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>, <a href="#acb051a27faf2e7374888d7daf2dbf5e0">Float</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">llvm::msgpack::Float</a>, <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>, <a href="#acbb061766f4e001718ae4251934a2e0c">Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a>, <a href="#abe1ba2052b98cee8a31531493c21f559">isEmpty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4da8b7eb2c3f2007cf8238334401ef51">llvm::msgpack::Nil</a>, <a href="#a11eead64fd1638c3aae26c25443c7179">Raw</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>, <a href="#a202099b1cc31ee4232aaba6c6915cc04">UInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### operator== {#ae006229abbf967ac3621ff55449bec97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp; Lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> &amp; Rhs</td>
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

<p>Equality operator.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DocNode() {#a0b25c4da6f9e05dd69ef15f988c426a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::DocNode::DocNode ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a321c0ea44e257246ee630eb346be23fa">llvm::msgpack::ArrayDocNode::ArrayDocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a4eab7452ad80d10e271598239cd1ee1c">llvm::msgpack::ArrayDocNode::back</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a9faaea1483f0af67b2925acda7f638b5">llvm::msgpack::MapDocNode::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a27c125345231b036f832814134ea95b4">llvm::msgpack::MapDocNode::find</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a42a79d432d9684765f8d3bcd3ed6a5e7">llvm::msgpack::MapDocNode::MapDocNode</a>, <a href="#a2da5bccd57f0fae730723500f95a27d1">operator!=</a>, <a href="#af099df7fdeb0a2166422c07f49d6bc2e">operator&lt;</a>, <a href="#a85f28c20e0b68d334f63d60d21ab7109">operator=</a>, <a href="#add2f7af8865179511cd97536891b2a9b">operator=</a>, <a href="#a4f88e6587461103193f66c63999b6b36">operator=</a>, <a href="#a091cbf7795bca9759a7f6aa86c692dfc">operator=</a>, <a href="#ae799c9c9dda75bf386ee714a0db638a8">operator=</a>, <a href="#a3b9b31645cb2a12ab5c315725ba367b1">operator=</a>, <a href="#a0312cc6e961a6b29ea43d313e17f3009">operator=</a>, <a href="#ad31b00a8fa469faa012f219a7f9466a1">operator=</a>, <a href="#ae006229abbf967ac3621ff55449bec97">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a9df88e85c1ec39c1604e13c22e38f3ef">llvm::msgpack::ArrayDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#aeda90977a3a2d3a4ebf597cbd7b29694">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#ad0438521060cc6dfd4b8b72efe3001e0">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a43d0afd4345b22cc90030df145e32140">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#ab551a82cec3f48431086a831936b7b3e">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a84e54eb8048e5f3b4eca3f8e129fd598">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a1b037777503503f8a729ae8004625673">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a969a25cab20bacfc1d698c1980a6b858">llvm::msgpack::ArrayDocNode::push_back</a> and <a href="/web-llvm/docs/api/structs/anonymous-msgpackdocumentyaml-cpp-/scalardocnode/#a2e240b31940358d89a17fe15ae402220">anonymous{MsgPackDocumentYAML.cpp}::ScalarDocNode::ScalarDocNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DocNode() {#a40014dd3e48978775e958a55d7a066f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::msgpack::DocNode::DocNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/msgpack/kindanddocument">KindAndDocument</a> * KindAndDoc)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#add2f7af8865179511cd97536891b2a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; llvm::msgpack::DocNode::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Val)</td>
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

<p>Convenience assignment operators.</p>


<p>This only works if the destination <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> has an associated <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>, i.e. it was not constructed using the default constructor. The string one does not copy, so the string must remain valid for the lifetime of the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> fromString to avoid that restriction.</p>


<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Reference <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>.</p>

</div>
</div>

### operator=() {#a3b9b31645cb2a12ab5c315725ba367b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; DocNode::operator= (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>, <a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>.</p>

</div>
</div>

### operator=() {#ae799c9c9dda75bf386ee714a0db638a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; DocNode::operator= (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>, <a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>.</p>

</div>
</div>

### operator=() {#a85f28c20e0b68d334f63d60d21ab7109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; DocNode::operator= (bool Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>, <a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>.</p>

</div>
</div>

### operator=() {#a4f88e6587461103193f66c63999b6b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; DocNode::operator= (int Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>, <a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>.</p>

</div>
</div>

### operator=() {#ad31b00a8fa469faa012f219a7f9466a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; DocNode::operator= (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>, <a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>.</p>

</div>
</div>

### operator=() {#a091cbf7795bca9759a7f6aa86c692dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; DocNode::operator= (int64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>, <a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>.</p>

</div>
</div>

### operator=() {#a0312cc6e961a6b29ea43d313e17f3009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNode &amp; DocNode::operator= (uint64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>


<p>References <a href="#a0b25c4da6f9e05dd69ef15f988c426a3">DocNode</a>, <a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fromString() {#a0a2160ffa04d67291e2827a29994a3b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef DocNode::fromString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Tag="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> and use it to set this <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> (assuming scalar).</p>


<p>If it is a string, copy the string into the <a href="/web-llvm/docs/api/classes/llvm/msgpack/document">Document</a>'s strings list so we do not rely on S having a lifetime beyond this call. Tag is "" or a YAML tag.</p>


<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aed4af140c3e423107e247c5006c1bf77">getBool</a>, <a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a>, <a href="#ad8be6946946420c6d24fc9ea15517710">getFloat</a>, <a href="#a8b4f91a68659f7a8c187d90a4df0dbef">getInt</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>, <a href="#a0fa6a49447da74e0bada4f145edd396b">getUInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### getArray() {#a83e993c73d12663a129d46cd3e1fb1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayDocNode &amp; llvm::msgpack::DocNode::getArray (bool Convert=false)</td>
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

<p>Get an <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode">ArrayDocNode</a> for an array node.</p>


<p>If Convert, convert the node to an array node if necessary.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4410ec34d9e6c1a68100ca0ce033fb17">llvm::msgpack::Array</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#ae84e80460e1a14732ae49e64b8bbf9f6">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernel</a>.</p>

</div>
</div>

### getBinary() {#a86803dfd1becb1430368f0b11abd59b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBufferRef llvm::msgpack::DocNode::getBinary ()</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a6ce976e8f061b2b5cfe4d0c50c3405dd">llvm::msgpack::Binary</a>, <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a> and <a href="#a11eead64fd1638c3aae26c25443c7179">Raw</a>.</p>

</div>
</div>

### getBool() {#aed4af140c3e423107e247c5006c1bf77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool &amp; llvm::msgpack::DocNode::getBool ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a19a84205a3d702965fcd2311b8682cab">Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a> and <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>.</p>


<p>Referenced by <a href="#a0a2160ffa04d67291e2827a29994a3b9">fromString</a>.</p>

</div>
</div>

### getBool() {#aa662b79ae64dc169fd355a7663a74b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::DocNode::getBool ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a19a84205a3d702965fcd2311b8682cab">Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a> and <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>.</p>

</div>
</div>

### getDocument() {#afb24ac524a469733ad7e1cd3f1de9dc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Document * llvm::msgpack::DocNode::getDocument ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a2877b4f51a65483c451edd59a4704df6">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#ae8b78bc8c92db11a11ca0cf7f7fc6f90">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitKernelAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a161232fcda35d33312029e1d80015b77">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelLanguage</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a2dea266109363b32fed08d85efa46523">llvm::msgpack::MapDocNode::find</a>, <a href="#a0a2160ffa04d67291e2827a29994a3b9">fromString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-msgpackdocumentyaml-cpp-/scalardocnode/#a3eeed73cd2b23e69e57d250ffece67d1">anonymous{MsgPackDocumentYAML.cpp}::ScalarDocNode::getYAMLTag</a>, <a href="#a85f28c20e0b68d334f63d60d21ab7109">operator=</a>, <a href="#a4f88e6587461103193f66c63999b6b36">operator=</a>, <a href="#a091cbf7795bca9759a7f6aa86c692dfc">operator=</a>, <a href="#ae799c9c9dda75bf386ee714a0db638a8">operator=</a>, <a href="#a3b9b31645cb2a12ab5c315725ba367b1">operator=</a>, <a href="#a0312cc6e961a6b29ea43d313e17f3009">operator=</a>, <a href="#ad31b00a8fa469faa012f219a7f9466a1">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a9df88e85c1ec39c1604e13c22e38f3ef">llvm::msgpack::ArrayDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#aeda90977a3a2d3a4ebf597cbd7b29694">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#ad0438521060cc6dfd4b8b72efe3001e0">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a43d0afd4345b22cc90030df145e32140">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#ab551a82cec3f48431086a831936b7b3e">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a84e54eb8048e5f3b4eca3f8e129fd598">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a1b037777503503f8a729ae8004625673">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a969a25cab20bacfc1d698c1980a6b858">llvm::msgpack::ArrayDocNode::push_back</a> and <a href="#ab9126e4f825db5a1bb881098b9159279">toString</a>.</p>

</div>
</div>

### getFloat() {#ad8be6946946420c6d24fc9ea15517710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double &amp; llvm::msgpack::DocNode::getFloat ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acb051a27faf2e7374888d7daf2dbf5e0">Float</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">llvm::msgpack::Float</a> and <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>.</p>


<p>Referenced by <a href="#a0a2160ffa04d67291e2827a29994a3b9">fromString</a>.</p>

</div>
</div>

### getFloat() {#ab03e3e668e37afc0a9c943a484a341cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::msgpack::DocNode::getFloat ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acb051a27faf2e7374888d7daf2dbf5e0">Float</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">llvm::msgpack::Float</a> and <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>.</p>

</div>
</div>

### getInt() {#a8b4f91a68659f7a8c187d90a4df0dbef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t &amp; llvm::msgpack::DocNode::getInt ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>, <a href="#acbb061766f4e001718ae4251934a2e0c">Int</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a>.</p>


<p>Referenced by <a href="#a0a2160ffa04d67291e2827a29994a3b9">fromString</a>.</p>

</div>
</div>

### getInt() {#aa277de8aa2d01d1433cd7f89313eff2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::msgpack::DocNode::getInt ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>, <a href="#acbb061766f4e001718ae4251934a2e0c">Int</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a>.</p>

</div>
</div>

### getKind() {#a3ed9efe27c6b7fcf2faef82736f3617a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::msgpack::DocNode::getKind ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a321c0ea44e257246ee630eb346be23fa">llvm::msgpack::ArrayDocNode::ArrayDocNode</a>, <a href="#a83e993c73d12663a129d46cd3e1fb1b5">getArray</a>, <a href="#a86803dfd1becb1430368f0b11abd59b0">getBinary</a>, <a href="#aed4af140c3e423107e247c5006c1bf77">getBool</a>, <a href="#aa662b79ae64dc169fd355a7663a74b4e">getBool</a>, <a href="#ad8be6946946420c6d24fc9ea15517710">getFloat</a>, <a href="#ab03e3e668e37afc0a9c943a484a341cc">getFloat</a>, <a href="#a8b4f91a68659f7a8c187d90a4df0dbef">getInt</a>, <a href="#aa277de8aa2d01d1433cd7f89313eff2d">getInt</a>, <a href="#a01acd23f4e4e583c9eaf2c03923b157e">getMap</a>, <a href="#aa5c069948272b8ae450480529a12de56">getString</a>, <a href="#a0fa6a49447da74e0bada4f145edd396b">getUInt</a>, <a href="#a9cfe6dfec5382df543e9b7bdde2f1c7d">getUInt</a>, <a href="/web-llvm/docs/api/structs/anonymous-msgpackdocumentyaml-cpp-/scalardocnode/#a3eeed73cd2b23e69e57d250ffece67d1">anonymous{MsgPackDocumentYAML.cpp}::ScalarDocNode::getYAMLTag</a>, <a href="#a7baf73f31a4531f8214a287c9c107fcc">isArray</a>, <a href="#abe1ba2052b98cee8a31531493c21f559">isEmpty</a>, <a href="#a78440e992da7b87645bb9c7cdb1b6525">isMap</a>, <a href="#ae42f124309dd69121f263493140d42e9">isString</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a42a79d432d9684765f8d3bcd3ed6a5e7">llvm::msgpack::MapDocNode::MapDocNode</a>, <a href="#af099df7fdeb0a2166422c07f49d6bc2e">operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a> and <a href="#ab9126e4f825db5a1bb881098b9159279">toString</a>.</p>

</div>
</div>

### getMap() {#a01acd23f4e4e583c9eaf2c03923b157e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapDocNode &amp; llvm::msgpack::DocNode::getMap (bool Convert=false)</td>
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

<p>Get a <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">MapDocNode</a> for a map node.</p>


<p>If Convert, convert the node to a map node if necessary.</p>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a46f3ea056caa3126b91f3f70beea068c">llvm::msgpack::Map</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-utility-cpp-/kernelinforeader/#aa4be56491fd1f1bfc2d12285da64e4a0">anonymous{Utility.cpp}::KernelInfoReader::processNote</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/v3/metadataverifier/#ae75dbe908959d6ab2501bcef46e70410">llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verify</a>.</p>

</div>
</div>

### getString() {#aa5c069948272b8ae450480529a12de56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::msgpack::DocNode::getString ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>, <a href="#a11eead64fd1638c3aae26c25443c7179">Raw</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>.</p>

</div>
</div>

### getUInt() {#a0fa6a49447da74e0bada4f145edd396b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t &amp; llvm::msgpack::DocNode::getUInt ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>, <a href="#a202099b1cc31ee4232aaba6c6915cc04">UInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>


<p>Referenced by <a href="#a0a2160ffa04d67291e2827a29994a3b9">fromString</a>.</p>

</div>
</div>

### getUInt() {#a9cfe6dfec5382df543e9b7bdde2f1c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::msgpack::DocNode::getUInt ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>, <a href="#a202099b1cc31ee4232aaba6c6915cc04">UInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### isArray() {#a7baf73f31a4531f8214a287c9c107fcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::DocNode::isArray ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4410ec34d9e6c1a68100ca0ce033fb17">llvm::msgpack::Array</a> and <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>.</p>


<p>Referenced by <a href="#ace5d944e39d3c2e6fd1506cbd0233b0a">isScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

### isEmpty() {#abe1ba2052b98cee8a31531493c21f559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::DocNode::isEmpty ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6ace2c8aed9c2fa0cfbed56cbda4d8bf07">llvm::msgpack::Empty</a> and <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>.</p>


<p>Referenced by <a href="#af099df7fdeb0a2166422c07f49d6bc2e">operator&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a>.</p>

</div>
</div>

### isMap() {#a78440e992da7b87645bb9c7cdb1b6525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::DocNode::isMap ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a46f3ea056caa3126b91f3f70beea068c">llvm::msgpack::Map</a>.</p>


<p>Referenced by <a href="#ace5d944e39d3c2e6fd1506cbd0233b0a">isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aa1132fee67332a4c0a707984b97f9b52">llvm::msgpack::Document::readFromBlob</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/v3/metadataverifier/#ae75dbe908959d6ab2501bcef46e70410">llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verify</a>.</p>

</div>
</div>

### isScalar() {#ace5d944e39d3c2e6fd1506cbd0233b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::DocNode::isScalar ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="#a7baf73f31a4531f8214a287c9c107fcc">isArray</a> and <a href="#a78440e992da7b87645bb9c7cdb1b6525">isMap</a>.</p>

</div>
</div>

### isString() {#ae42f124309dd69121f263493140d42e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::DocNode::isString ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>References <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>.</p>

</div>
</div>

### toString() {#ab9126e4f825db5a1bb881098b9159279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string DocNode::toString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert this node to a string, assuming it is scalar.</p>


<p>Convert this <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">DocNode</a> to a string, assuming it is scalar.</p>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a>.</p>


<p>References <a href="#a19a84205a3d702965fcd2311b8682cab">Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27226c864bac7454a8504f8edb15d95b">llvm::msgpack::Boolean</a>, <a href="#acb051a27faf2e7374888d7daf2dbf5e0">Float</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a22ae0e2b89e5e3d477f988cc36d3272b">llvm::msgpack::Float</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#afb24ac524a469733ad7e1cd3f1de9dc5">getDocument</a>, <a href="#a3ed9efe27c6b7fcf2faef82736f3617a">getKind</a>, <a href="#acbb061766f4e001718ae4251934a2e0c">Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a1686a6c336b71b36d77354cea19a8b52">llvm::msgpack::Int</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4da8b7eb2c3f2007cf8238334401ef51">llvm::msgpack::Nil</a>, <a href="#a11eead64fd1638c3aae26c25443c7179">Raw</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>, <a href="#a202099b1cc31ee4232aaba6c6915cc04">UInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### convertToArray() {#aea49aa48058a9188cbf2d71b72ded5b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocNode::convertToArray ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>

</div>
</div>

### convertToMap() {#a3b3c173357bac77f0b59ada24f440dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocNode::convertToMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Array {#a603b51266c0e0421d37f7cc6cd6fb20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayTy* llvm::msgpack::DocNode::Array</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a4eab7452ad80d10e271598239cd1ee1c">llvm::msgpack::ArrayDocNode::back</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#afb82966fbf1e09d5ee6235eb2e7e394c">llvm::msgpack::ArrayDocNode::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a424d291ef3b070f70969b1f220db4580">llvm::msgpack::ArrayDocNode::end</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a9df88e85c1ec39c1604e13c22e38f3ef">llvm::msgpack::ArrayDocNode::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a969a25cab20bacfc1d698c1980a6b858">llvm::msgpack::ArrayDocNode::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#aea55f8d3f2ce25ead106e0ff9bc8f28f">llvm::msgpack::ArrayDocNode::size</a>.</p>

</div>
</div>

### Bool {#a19a84205a3d702965fcd2311b8682cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::msgpack::DocNode::Bool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="#aed4af140c3e423107e247c5006c1bf77">getBool</a>, <a href="#aa662b79ae64dc169fd355a7663a74b4e">getBool</a>, <a href="#af099df7fdeb0a2166422c07f49d6bc2e">operator&lt;</a> and <a href="#ab9126e4f825db5a1bb881098b9159279">toString</a>.</p>

</div>
</div>

### Float {#acb051a27faf2e7374888d7daf2dbf5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::msgpack::DocNode::Float</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="#ad8be6946946420c6d24fc9ea15517710">getFloat</a>, <a href="#ab03e3e668e37afc0a9c943a484a341cc">getFloat</a>, <a href="#af099df7fdeb0a2166422c07f49d6bc2e">operator&lt;</a> and <a href="#ab9126e4f825db5a1bb881098b9159279">toString</a>.</p>

</div>
</div>

### Int {#acbb061766f4e001718ae4251934a2e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::msgpack::DocNode::Int</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="#a8b4f91a68659f7a8c187d90a4df0dbef">getInt</a>, <a href="#aa277de8aa2d01d1433cd7f89313eff2d">getInt</a>, <a href="#af099df7fdeb0a2166422c07f49d6bc2e">operator&lt;</a> and <a href="#ab9126e4f825db5a1bb881098b9159279">toString</a>.</p>

</div>
</div>

### Map {#adcc097d224c8c39ed85b9a938e11a36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapTy* llvm::msgpack::DocNode::Map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a1f0767ec1c79e32931f71bc67b7e3b5b">llvm::msgpack::MapDocNode::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#aa782c90a40bee89192e839c1cfe2026d">llvm::msgpack::MapDocNode::end</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a9faaea1483f0af67b2925acda7f638b5">llvm::msgpack::MapDocNode::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a3d89a18fb5a460f0bfd7d703088e40b5">llvm::msgpack::MapDocNode::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#ac76af25be2986958c8175ddc7b85ad29">llvm::msgpack::MapDocNode::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a27c125345231b036f832814134ea95b4">llvm::msgpack::MapDocNode::find</a> and <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a3d82d52907b09b2e4f9c657b17487bb8">llvm::msgpack::MapDocNode::size</a>.</p>

</div>
</div>

### Raw {#a11eead64fd1638c3aae26c25443c7179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::msgpack::DocNode::Raw</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="#a86803dfd1becb1430368f0b11abd59b0">getBinary</a>, <a href="#aa5c069948272b8ae450480529a12de56">getString</a>, <a href="#af099df7fdeb0a2166422c07f49d6bc2e">operator&lt;</a> and <a href="#ab9126e4f825db5a1bb881098b9159279">toString</a>.</p>

</div>
</div>

### UInt {#a202099b1cc31ee4232aaba6c6915cc04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::msgpack::DocNode::UInt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>


<p>Referenced by <a href="#a0fa6a49447da74e0bada4f145edd396b">getUInt</a>, <a href="#a9cfe6dfec5382df543e9b7bdde2f1c7d">getUInt</a>, <a href="#af099df7fdeb0a2166422c07f49d6bc2e">operator&lt;</a> and <a href="#ab9126e4f825db5a1bb881098b9159279">toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

###  {#a2c3b4521d1be8034bdd593069d878d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::msgpack::DocNode llvm::msgpack::DocNode</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Document {#ac19bb66fedc4f2a731ecf6b665c66558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::msgpack::DocNode::Document</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

### KindAndDoc {#a9e01898e88fcecbfd6a3d3f450fa800f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const KindAndDocument* llvm::msgpack::DocNode::KindAndDoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/msgpackdocument-h">MsgPackDocument.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocument-cpp">MsgPackDocument.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/msgpackdocumentyaml-cpp">MsgPackDocumentYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
