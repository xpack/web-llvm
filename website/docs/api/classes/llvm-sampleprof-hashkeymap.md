---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/hashkeymap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HashKeyMap` Class Template Reference

<p>This class is a wrapper to associative container <a href="/web-llvm/docs/api/classes/mapt">MapT&lt;KeyT, ValueT&gt;</a> using the hash value of the original key as the new key. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;
class llvm::sampleprof::HashKeyMap&lt;MapT, KeyT, ValueT, MapTArgs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">llvm/ProfileData/HashKeyMap.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/mapt">MapT</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06a5cec02f610e8b3d87123f5a4a47a6">base_type</a> = <a href="/web-llvm/docs/api/classes/mapt">MapT</a>&lt; decltype(<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">hash_value</a>(KeyT())), ValueT, MapTArgs... &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aabc742fe1a2b1267b3d600b76b45b8dc">key_type</a> = decltype(<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">hash_value</a>(KeyT()))</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad943e8a478f860c5398f57c8b1544936">original_key_type</a> = KeyT</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b065bcf14e5a8573b4bab40feefd3fe">mapped_type</a> = ValueT</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78379c9f2de5b2d16a278ec5543851fa">value_type</a> = typename base_type::value_type</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b3ce75cf09c26ff4a7c487ef9cd394d">iterator</a> = typename base_type::iterator</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5cb3c755a7378693b4859d32770536b">const_iterator</a> = typename base_type::const_iterator</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a0b065bcf14e5a8573b4bab40feefd3fe">mapped_type</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad4515fc1c5334a69fc0362771d9b3e68">operator[]</a> (const original_key_type &amp;Key)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a52911d4b0f950d7f5ff31f412c9776">try_emplace</a> (const key_type &amp;Hash, const original_key_type &amp;Key, Ts &amp;&amp;...Args) -&gt; std::pair&lt; <a href="#a3b3ce75cf09c26ff4a7c487ef9cd394d">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c3ab43caf0a8e8d3e5a30e7824a71e6">try_emplace</a> (const original_key_type &amp;Key, Ts &amp;&amp;...Args) -&gt; std::pair&lt; <a href="#a3b3ce75cf09c26ff4a7c487ef9cd394d">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0cd84a4064f062d03e23fd5c68422378">emplace</a> (Ts &amp;&amp;...Args) -&gt; std::pair&lt; <a href="#a3b3ce75cf09c26ff4a7c487ef9cd394d">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a3b3ce75cf09c26ff4a7c487ef9cd394d">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae4b75fa9a69ea101d484665ded779afa">find</a> (const original_key_type &amp;Key)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#af5cb3c755a7378693b4859d32770536b">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6277d8f9b5bb8e19f432fd621eb4c947">find</a> (const original_key_type &amp;Key) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a0b065bcf14e5a8573b4bab40feefd3fe">mapped_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae87951ebd30b00076d2c8a29b103c3cd">lookup</a> (const original_key_type &amp;Key) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adfbb1f4f1712feb4ce2c124a11200de7">count</a> (const original_key_type &amp;Key) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acfbdb4d1307c9f38b1446f317dae4ed7">erase</a> (const original_key_type &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a3b3ce75cf09c26ff4a7c487ef9cd394d">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6c1be806b57dc7aa233a16a86da2b29">erase</a> (const_iterator It)</td>
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

<p>This class is a wrapper to associative container <a href="/web-llvm/docs/api/classes/mapt">MapT&lt;KeyT, ValueT&gt;</a> using the hash value of the original key as the new key.</p>


<p>This greatly improves the performance of insert and query operations especially when hash values of keys are available a priori, and reduces memory usage if KeyT has a large size. All keys with the same hash value are considered equivalent (i.e. hash collision is silently ignored). Given such feature this class should only be used where it does not affect compilation correctness, for example, when loading a sample profile. The original key is not stored, so if the user needs to preserve it, it should be stored in the mapped type. Assuming the hashing algorithm is uniform, we use the formula 1 - Permute(n, k) / n ^ k where n is the universe size and k is number of elements chosen at random to calculate the probability of collision. With 1,000,000 entries the probability is negligible: 1 - (2^64)!/((2^64-1000000)!*(2^64)^1000000) ~= 3*10^-8. Source: <a href="https://en.wikipedia.org/wiki/Birthday_problem">https://en.wikipedia.org/wiki/Birthday_problem</a></p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/mapt"&gt;MapT&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The underlying associative container type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KeyT</td>
<td class="doxyParamItemDescription"><p>The original key type, which requires the implementation of llvm::hash_value(KeyT).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ValueT</td>
<td class="doxyParamItemDescription"><p>The original mapped type, which has the same requirement as the underlying container.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MapTArgs</td>
<td class="doxyParamItemDescription"><p>Additional template parameters passed to the underlying container.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### base\_type {#a06a5cec02f610e8b3d87123f5a4a47a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::base_type =  MapT&lt;decltype(hash_value(KeyT())), ValueT, MapTArgs...&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>

</div>
</div>

### const\_iterator {#af5cb3c755a7378693b4859d32770536b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::const_iterator =  typename base_type::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>

</div>
</div>

### iterator {#a3b3ce75cf09c26ff4a7c487ef9cd394d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::iterator =  typename base_type::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>

</div>
</div>

### key\_type {#aabc742fe1a2b1267b3d600b76b45b8dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::key_type =  decltype(hash_value(KeyT()))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>

</div>
</div>

### mapped\_type {#a0b065bcf14e5a8573b4bab40feefd3fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::mapped_type =  ValueT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>

</div>
</div>

### original\_key\_type {#ad943e8a478f860c5398f57c8b1544936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::original_key_type =  KeyT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>

</div>
</div>

### value\_type {#a78379c9f2de5b2d16a278ec5543851fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::value_type =  typename base_type::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#ad4515fc1c5334a69fc0362771d9b3e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mapped_type &amp; llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad943e8a478f860c5398f57c8b1544936">original_key_type</a> &amp; Key)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="#a3a52911d4b0f950d7f5ff31f412c9776">llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::try_emplace</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### count() {#adfbb1f4f1712feb4ce2c124a11200de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::count (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad943e8a478f860c5398f57c8b1544936">original_key_type</a> &amp; Key)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">llvm::sampleprof::hash_value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### emplace() {#a0cd84a4064f062d03e23fd5c68422378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::emplace (Ts &amp;&amp;... Args)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<p>Reference <a href="#a3a52911d4b0f950d7f5ff31f412c9776">llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::try_emplace</a>.</p>

</div>
</div>

### erase() {#acfbdb4d1307c9f38b1446f317dae4ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::erase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad943e8a478f860c5398f57c8b1544936">original_key_type</a> &amp; Ctx)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<p>Reference <a href="#ae4b75fa9a69ea101d484665ded779afa">llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::find</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap/#afed5e84b531a10e3daec958bd50cc9f9">llvm::sampleprof::SampleProfileMap::erase</a>.</p>

</div>
</div>

### erase() {#af6c1be806b57dc7aa233a16a86da2b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::erase (<a href="#af5cb3c755a7378693b4859d32770536b">const_iterator</a> It)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>

</div>
</div>

### find() {#ae4b75fa9a69ea101d484665ded779afa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad943e8a478f860c5398f57c8b1544936">original_key_type</a> &amp; Key)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">llvm::sampleprof::hash_value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>


<p>Referenced by <a href="#acfbdb4d1307c9f38b1446f317dae4ed7">llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap/#a1cdf9b220ee713c505287c0f2c6969c0">llvm::sampleprof::SampleProfileMap::find</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap/#abd28c02774d02fa8f76f6b47ca6eb3de">llvm::sampleprof::SampleProfileMap::find</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a2590274bcc6c09009ed10feb5455243d">llvm::sampleprof::FunctionSamples::findFunctionSamplesAt</a>.</p>

</div>
</div>

### find() {#a6277d8f9b5bb8e19f432fd621eb4c947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad943e8a478f860c5398f57c8b1544936">original_key_type</a> &amp; Key)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">llvm::sampleprof::hash_value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### lookup() {#ae87951ebd30b00076d2c8a29b103c3cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename, typename, typename... &gt; typename MapT, typename KeyT, typename ValueT, typename... MapTArgs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mapped_type llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad943e8a478f860c5398f57c8b1544936">original_key_type</a> &amp; Key)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">llvm::sampleprof::hash_value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### try\_emplace() {#a3a52911d4b0f950d7f5ff31f412c9776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::try_emplace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aabc742fe1a2b1267b3d600b76b45b8dc">key_type</a> &amp; Hash, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad943e8a478f860c5398f57c8b1544936">original_key_type</a> &amp; Key, Ts &amp;&amp;... Args)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">llvm::sampleprof::hash_value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>


<p>Referenced by <a href="#a0cd84a4064f062d03e23fd5c68422378">llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::emplace</a>, <a href="#ad4515fc1c5334a69fc0362771d9b3e68">llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::operator[]</a> and <a href="#a7c3ab43caf0a8e8d3e5a30e7824a71e6">llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::try_emplace</a>.</p>

</div>
</div>

### try\_emplace() {#a7c3ab43caf0a8e8d3e5a30e7824a71e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::try_emplace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad943e8a478f860c5398f57c8b1544936">original_key_type</a> &amp; Key, Ts &amp;&amp;... Args)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">llvm::sampleprof::hash_value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="#a3a52911d4b0f950d7f5ff31f412c9776">llvm::sampleprof::HashKeyMap&lt; MapT, KeyT, ValueT, MapTArgs &gt;::try_emplace</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/hashkeymap-h">HashKeyMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
