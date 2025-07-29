---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/json/object
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Object` Class

<p>An <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> is a JSON object, which maps strings to heterogenous JSON values. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::json::Object { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">llvm/Support/JSON.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2246aeaddd6561a5bc1c77da55bac7">key_type</a> = <a href="/web-llvm/docs/api/classes/llvm/json/objectkey">ObjectKey</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320516d4d69003069a672105e5291592">mapped_type</a> = <a href="/web-llvm/docs/api/classes/llvm/json/value">Value</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54946964154863ee9d72ae3a93f9313e">value_type</a> = <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#ab3749c7aa991a9067aa4d209d0f9191f">Storage::value_type</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92074ca3e4c1899f06f9ef8604c3a5b1">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a214e872d61db2ea8cb023f127cafd0b9">Storage::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb7262f91edce91fc0bdca2481e2c13">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a5784c312872bef21d9344dae0a0e8fc0">Storage::const_iterator</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ea4214bed6cdf3203a70fa09bcd3653">Storage</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/json/objectkey">ObjectKey</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value">Value</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">llvm::DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe481447fa5d95f2d457756298ce834">Object</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d34716580469e690935408fd46a6f9f">Object</a> (std::initializer_list&lt; KV &gt; Properties)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/json/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d15411ab47688cffc60b35fc3ac61f">operator[]</a> (const ObjectKey &amp;K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/json/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ced3ad5b975e5d68b1b59e2507bcdf1">operator[]</a> (ObjectKey &amp;&amp;K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a92074ca3e4c1899f06f9ef8604c3a5b1">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5a7994ab4957eee62931021db01da9b">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aceb7262f91edce91fc0bdca2481e2c13">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86def88ae5dc7b724821f5725fd59d5d">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a92074ca3e4c1899f06f9ef8604c3a5b1">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a050dd56fad728a67a714efd3c4a0e2eb">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aceb7262f91edce91fc0bdca2481e2c13">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102411ced3987c1f0cf8013b7ef5026f">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b09f559211430be9ee926fa86773004">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8a6c98c75ed064679b3425ce33093ed">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af079fdf056d554914fd304ef98f8f090">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="#a92074ca3e4c1899f06f9ef8604c3a5b1">iterator</a>, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58f5841f3f528cfd0fc3a9924d63124">insert</a> (KV E)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8506070467079c20e5ec2000024d2da9">try_emplace</a> (const ObjectKey &amp;K, Ts &amp;&amp;... Args) -&gt; std::pair&lt; <a href="#a92074ca3e4c1899f06f9ef8604c3a5b1">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a637396afa09c1f3f7626d60b3aa19240">try_emplace</a> (ObjectKey &amp;&amp;K, Ts &amp;&amp;... Args) -&gt; std::pair&lt; <a href="#a92074ca3e4c1899f06f9ef8604c3a5b1">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79967a3d0250496b6ac71df995ed08b4">erase</a> (StringRef K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900afe6f23ebe05db73dc4fa175f37c9">erase</a> (iterator I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a92074ca3e4c1899f06f9ef8604c3a5b1">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e8e6c0e26ba215e430a71a6623e943">find</a> (StringRef K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aceb7262f91edce91fc0bdca2481e2c13">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa591a85e1b815de9c08b256a4bf19e0f">find</a> (StringRef K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/json/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a> (StringRef K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf992ab02343f4058e5dde610672ec3">get</a> (StringRef K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::nullptr_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b78215b9f3701d021d4886bd2ae86c">getNull</a> (StringRef K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0526d84cc07e657c9c6d132ec8e7df7c">getBoolean</a> (StringRef K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; double &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a2a7cb5c36f68e071c0b37709604aa">getNumber</a> (StringRef K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f43eed548c5843a034256d003962856">getInteger</a> (StringRef K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f5a1fac6edc9441441ce993e57dcafe">getString</a> (StringRef K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/object">json::Object</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c141439987df1fc2d6f0282a755cdcf">getObject</a> (StringRef K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/json/object">json::Object</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ad059e421596b5563cd660c0248755">getObject</a> (StringRef K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/array">json::Array</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34ffda50683057ddb8601e6f68d51d5">getArray</a> (StringRef K) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/json/array">json::Array</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a428b5ff93027bf8d04120406c5c929e8">getArray</a> (StringRef K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">Storage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab78df8d7908d32d0eab660a2a96c1e7">M</a></td>
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

<p>An <a href="/web-llvm/docs/api/classes/llvm/json/object">Object</a> is a JSON object, which maps strings to heterogenous JSON values.</p>


<p>It simulates <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap&lt;ObjectKey, Value&gt;</a>. <a href="/web-llvm/docs/api/classes/llvm/json/objectkey">ObjectKey</a> is a maybe-owned string.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#aceb7262f91edce91fc0bdca2481e2c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::json::Object::const_iterator =  Storage::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### iterator {#a92074ca3e4c1899f06f9ef8604c3a5b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::json::Object::iterator =  Storage::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### key\_type {#a5d2246aeaddd6561a5bc1c77da55bac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::json::Object::key_type =  ObjectKey</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### mapped\_type {#a320516d4d69003069a672105e5291592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::json::Object::mapped_type =  Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### value\_type {#a54946964154863ee9d72ae3a93f9313e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::json::Object::value_type =  Storage::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### Storage {#a7ea4214bed6cdf3203a70fa09bcd3653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::json::Object::Storage =  DenseMap&lt;ObjectKey, Value, llvm::DenseMapInfo&lt;StringRef&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Object() {#affe481447fa5d95f2d457756298ce834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::json::Object::Object ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### Object() {#a0d34716580469e690935408fd46a6f9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::json::Object::Object (std::initializer_list&lt; <a href="/web-llvm/docs/api/structs/llvm/json/object/kv">KV</a> &gt; Properties)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a8506070467079c20e5ec2000024d2da9">try_emplace</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a11d15411ab47688cffc60b35fc3ac61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value &amp; llvm::json::Object::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/objectkey">ObjectKey</a> &amp; K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a8506070467079c20e5ec2000024d2da9">try_emplace</a>.</p>

</div>
</div>

### operator\[\]() {#a2ced3ad5b975e5d68b1b59e2507bcdf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value &amp; llvm::json::Object::operator[] (<a href="/web-llvm/docs/api/classes/llvm/json/objectkey">ObjectKey</a> &amp;&amp; K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a8506070467079c20e5ec2000024d2da9">try_emplace</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#aa5a7994ab4957eee62931021db01da9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::json::Object::begin ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### begin() {#a86def88ae5dc7b724821f5725fd59d5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::json::Object::begin ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### clear() {#af079fdf056d554914fd304ef98f8f090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::Object::clear ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### empty() {#a9b09f559211430be9ee926fa86773004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::json::Object::empty ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### end() {#a050dd56fad728a67a714efd3c4a0e2eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::json::Object::end ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Referenced by <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a> and <a href="#afcf992ab02343f4058e5dde610672ec3">get</a>.</p>

</div>
</div>

### end() {#a102411ced3987c1f0cf8013b7ef5026f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::json::Object::end ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### erase() {#a79967a3d0250496b6ac71df995ed08b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::json::Object::erase (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### erase() {#a900afe6f23ebe05db73dc4fa175f37c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::json::Object::erase (<a href="#a92074ca3e4c1899f06f9ef8604c3a5b1">iterator</a> I)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### find() {#ae4e8e6c0e26ba215e430a71a6623e943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::json::Object::find (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Referenced by <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a> and <a href="#afcf992ab02343f4058e5dde610672ec3">get</a>.</p>

</div>
</div>

### find() {#aa591a85e1b815de9c08b256a4bf19e0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::json::Object::find (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### get() {#a599e72831bd4fc884bdcf32c0ca5f8e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::json::Object::get (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>References <a href="#a050dd56fad728a67a714efd3c4a0e2eb">end</a>, <a href="#ae4e8e6c0e26ba215e430a71a6623e943">find</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a428b5ff93027bf8d04120406c5c929e8">getArray</a>, <a href="#af34ffda50683057ddb8601e6f68d51d5">getArray</a>, <a href="#a0526d84cc07e657c9c6d132ec8e7df7c">getBoolean</a>, <a href="#a6f43eed548c5843a034256d003962856">getInteger</a>, <a href="#a80b78215b9f3701d021d4886bd2ae86c">getNull</a>, <a href="#a39a2a7cb5c36f68e071c0b37709604aa">getNumber</a>, <a href="#a32ad059e421596b5563cd660c0248755">getObject</a>, <a href="#a3c141439987df1fc2d6f0282a755cdcf">getObject</a> and <a href="#a3f5a1fac6edc9441441ce993e57dcafe">getString</a>.</p>

</div>
</div>

### get() {#afcf992ab02343f4058e5dde610672ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::json::Object::get (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>References <a href="#a050dd56fad728a67a714efd3c4a0e2eb">end</a>, <a href="#ae4e8e6c0e26ba215e430a71a6623e943">find</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getArray() {#af34ffda50683057ddb8601e6f68d51d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const json::Array * llvm::json::Object::getArray (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#a454eefb23874609b98aa35d4d8cbfd38">anonymous{TextStubV5.cpp}::collectFromArray</a>.</p>

</div>
</div>

### getArray() {#a428b5ff93027bf8d04120406c5c929e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">json::Array * llvm::json::Object::getArray (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a>.</p>

</div>
</div>

### getBoolean() {#a0526d84cc07e657c9c6d132ec8e7df7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; llvm::json::Object::getBoolean (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a>.</p>

</div>
</div>

### getInteger() {#a6f43eed548c5843a034256d003962856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int64_t &gt; llvm::json::Object::getInteger (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#abbe5a3bb0b3fa7550dc6cda8bf451e1c">anonymous{TextStubV5.cpp}::StubParser::getSwiftVersion</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#ac42c700535f05d4689644c1b5e6d5067">anonymous{TextStubV5.cpp}::StubParser::getVersion</a>.</p>

</div>
</div>

### getNull() {#a80b78215b9f3701d021d4886bd2ae86c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::nullptr_t &gt; llvm::json::Object::getNull (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a>.</p>

</div>
</div>

### getNumber() {#a39a2a7cb5c36f68e071c0b37709604aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; double &gt; llvm::json::Object::getNumber (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a>.</p>

</div>
</div>

### getObject() {#a3c141439987df1fc2d6f0282a755cdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const json::Object * llvm::json::Object::getObject (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a87d247041800a391e58d7e42c6286219">llvm::MachO::getInterfaceFileFromJSON</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#aaf9c0aea9c22aa6396990a3c9b72beb2">anonymous{TextStubV5.cpp}::StubParser::getSymbolSection</a>.</p>

</div>
</div>

### getObject() {#a32ad059e421596b5563cd660c0248755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">json::Object * llvm::json::Object::getObject (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a>.</p>

</div>
</div>

### getString() {#a3f5a1fac6edc9441441ce993e57dcafe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; llvm::StringRef &gt; llvm::json::Object::getString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a>.</p>


<p>Reference <a href="#a599e72831bd4fc884bdcf32c0ca5f8e4">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#a29b48d84adc69c4ec316b2f4643c2e83">anonymous{TextStubV5.cpp}::StubParser::getNameSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#acb60bd8130621f33fdc8f14cc5faf7bc">anonymous{TextStubV5.cpp}::StubParser::getPackedVersion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#a841ed7fbb14a5ba056989d1e19eef248">anonymous{TextStubV5.cpp}::StubParser::getTargetsSection</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#a7b701ffbdb1940d66dc5f254c3bc16ae">anonymous{TextStubV5.cpp}::StubParser::getUmbrellaSection</a>.</p>

</div>
</div>

### insert() {#ae58f5841f3f528cfd0fc3a9924d63124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Object::iterator, bool &gt; llvm::json::Object::insert (<a href="/web-llvm/docs/api/structs/llvm/json/object/kv">KV</a> E)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="#a8506070467079c20e5ec2000024d2da9">try_emplace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### size() {#ae8a6c98c75ed064679b3425ce33093ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::json::Object::size ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

### try\_emplace() {#a8506070467079c20e5ec2000024d2da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::json::Object::try_emplace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/json/objectkey">ObjectKey</a> &amp; K, Ts &amp;&amp;... Args)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>


<p>Referenced by <a href="#ae58f5841f3f528cfd0fc3a9924d63124">insert</a>, <a href="#a0d34716580469e690935408fd46a6f9f">Object</a>, <a href="#a11d15411ab47688cffc60b35fc3ac61f">operator[]</a>, <a href="#a2ced3ad5b975e5d68b1b59e2507bcdf1">operator[]</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#acc7f16c0553ca0c637b42907ff64b9f5">llvm::DWARFVerifier::summarize</a>.</p>

</div>
</div>

### try\_emplace() {#a637396afa09c1f3f7626d60b3aa19240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::json::Object::try_emplace (<a href="/web-llvm/docs/api/classes/llvm/json/objectkey">ObjectKey</a> &amp;&amp; K, Ts &amp;&amp;... Args)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### M {#aab78df8d7908d32d0eab660a2a96c1e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Storage llvm::json::Object::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">JSON.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/json-cpp">JSON.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
