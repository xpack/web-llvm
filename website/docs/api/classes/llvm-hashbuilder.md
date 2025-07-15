---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hashbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HashBuilder` Class Template Reference

<p>Interface to help hash various types through a hasher type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename HasherT, llvm::endianness Endianness&gt;
class llvm::HashBuilder&lt;HasherT, Endianness&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">llvm/Support/HashBuilder.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilderbase">HashBuilderBase&lt;HasherT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Declares the hasher member, and functions forwarding directly to the hasher. <a href="/web-llvm/docs/api/classes/llvm/hashbuilderbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a770b706b2dcfbb64c717a1cbe9418874">HasAddHashT</a> = decltype(addHash(std::declval&lt; <a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp; &gt;(), std::declval&lt; T &amp; &gt;()))</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adcce0ed276b7f972d77f8b095bd0093b">HasByteSwapT</a> = decltype(<a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">support::endian::byte_swap</a>( std::declval&lt; T &amp; &gt;(), <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::endianness::little</a>))</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT, llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3790ea10d4f6d2364d6b1fb2bddfbf4e">HashBuilder</a> (HasherT &amp;Hasher)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... ArgTypes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af8733fcc0780d8e7f05a7428721159ec">HashBuilder</a> (ArgTypes &amp;&amp;...Args)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91945efc8e44a3f170402a1b1a2316fe">add</a> (T Value) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/hashbuilder-detail/ishashabledata">hashbuilder_detail::IsHashableData</a>&lt; T &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement hashing for hashable data types, e.g. integral or enum values. <a href="#a91945efc8e44a3f170402a1b1a2316fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e8f681c61a2745facd1cb55855fe402">add</a> (ArrayRef&lt; T &gt; Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support hashing <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a></span>. <a href="#a8e8f681c61a2745facd1cb55855fe402">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT, llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1815b02e7fafbe2f603c7893bd131666">add</a> (StringRef Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support hashing <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></span>. <a href="#a1815b02e7fafbe2f603c7893bd131666">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a10e1cde5bdf37faed1fafd171aa33619">add</a> (const T &amp;Value) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#abf1ad174f29a434886594433ce8a787f">is_detected</a>&lt; <a href="#a770b706b2dcfbb64c717a1cbe9418874">HasAddHashT</a>, T &gt;::value &amp;&amp;!<a href="/web-llvm/docs/api/structs/llvm/hashbuilder-detail/ishashabledata">hashbuilder_detail::IsHashableData</a>&lt; T &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement hashing for user-defined <span class="doxyComputerOutput">struct</span>s. <a href="#a10e1cde5bdf37faed1fafd171aa33619">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4c3f8c5c42740075dea32797798473f">add</a> (const std::pair&lt; T1, T2 &gt; &amp;Value)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d71f0c32204f6a2f72915b7ad28d215">add</a> (const std::tuple&lt; Ts... &gt; &amp;Arg)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a94d5635dcb6728b77fc7ae9157abb4">add</a> (const Ts &amp;...Args) -&gt; std::enable_if_t&lt;(sizeof...(Ts) &gt; 1), <a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A convenenience variadic helper. <a href="#a3a94d5635dcb6728b77fc7ae9157abb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ForwardIteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac10ca9284dac49b244037588df79ca2">addRange</a> (ForwardIteratorT First, ForwardIteratorT Last)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RangeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a499eab6d3ce4ac7f7342621c39b950ef">addRange</a> (const RangeT &amp;Range)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ForwardIteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e1c3c0190de95c6a73e63dcb02f3f97">addRangeElements</a> (ForwardIteratorT First, ForwardIteratorT Last)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RangeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a44f68de74fc37dcfba02bab2f044cca4">addRangeElements</a> (const RangeT &amp;Range)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2f0e0694a40550ad8156ff89999df152">adjustForEndiannessAndAdd</a> (const T &amp;Value) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#abf1ad174f29a434886594433ce8a787f">is_detected</a>&lt; <a href="#adcce0ed276b7f972d77f8b095bd0093b">HasByteSwapT</a>, T &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjust <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for the target endianness and add it to the hash. <a href="#a2f0e0694a40550ad8156ff89999df152">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ForwardIteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12329287391db2113bfc3f64c8549fdc">addRangeElementsImpl</a> (ForwardIteratorT First, ForwardIteratorT Last, std::forward_iterator_tag)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6773e7544a444016ffa6885be69b42ae">addRangeElementsImpl</a> (T *First, T *Last, std::forward_iterator_tag) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/hashbuilder-detail/ishashabledata">hashbuilder_detail::IsHashableData</a>&lt; T &gt;::value &amp;&amp;Endianness==<a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::endianness::native</a>, <a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a> &amp; &gt;</td>
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

<p>Interface to help hash various types through a hasher type.</p>


<p>Via provided specializations of <span class="doxyComputerOutput">add</span>, <span class="doxyComputerOutput">addRange</span>, and <span class="doxyComputerOutput">addRangeElements</span> functions, various types (e.g. <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a></span>, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></span>, etc.) can be hashed without requiring any knowledge of hashed types from the hasher type.</p>


<p>The only method expected from the templated hasher type <span class="doxyComputerOutput">HasherT</span> is:</p>


<ul class="doxyList ">
<li>void <a href="/web-llvm/docs/api/classes/llvm/hashbuilderbase/#ae3ff56a4d35e4dd4630e8abdb80d1bb9">update(ArrayRef&lt;uint8_t&gt; Data)</a></li>
</ul>

<p>Additionally, the following methods will be forwarded to the hasher type:</p>


<ul class="doxyList ">
<li>decltype(std::declval&lt;HasherT &amp;&gt;().<a href="/web-llvm/docs/api/classes/llvm/hashbuilderbase/#a6e5cbc4cd359a97743ffbfa4abc13d73">final()</a>) <a href="/web-llvm/docs/api/classes/llvm/hashbuilderbase/#a6e5cbc4cd359a97743ffbfa4abc13d73">final()</a></li>
<li>decltype(std::declval&lt;HasherT &amp;&gt;().<a href="/web-llvm/docs/api/classes/llvm/hashbuilderbase/#aad2f567a2782a06b3116aed7e92047fd">result()</a>) <a href="/web-llvm/docs/api/classes/llvm/hashbuilderbase/#aad2f567a2782a06b3116aed7e92047fd">result()</a></li>
</ul>

<p>From a user point of view, the interface provides the following:</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">template&lt;typename T&gt; add(const T &amp;<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</span> The <span class="doxyComputerOutput">add</span> function implements hashing of various types.</li>
<li><span class="doxyComputerOutput">template &lt;typename ItT&gt; void addRange(ItT First, ItT Last)</span> The <span class="doxyComputerOutput">addRange</span> function is designed to aid hashing a range of values. It explicitly adds the size of the range in the hash.</li>
<li><span class="doxyComputerOutput">template &lt;typename ItT&gt; void addRangeElements(ItT First, ItT Last)</span> The <span class="doxyComputerOutput">addRangeElements</span> function is also designed to aid hashing a range of values. In contrast to <span class="doxyComputerOutput">addRange</span>, it <b>ignores</b> the size of the range, behaving as if elements were added one at a time with <span class="doxyComputerOutput">add</span>.</li>
</ul>

<p>User-defined <span class="doxyComputerOutput">struct</span> types can participate in this interface by providing an <span class="doxyComputerOutput">addHash</span> templated function. See the associated template specialization for details.</p>


<p>This interface does not impose requirements on the hasher <span class="doxyComputerOutput">update(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt; Data)</span> method. We want to avoid collisions for variable-size types; for example for</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add({1});</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add({2, 3});</span></span></div>

</div>


<p>and</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add({1, 2});</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add({3});</span></span></div>

</div>


<p>. Thus, specializations of <span class="doxyComputerOutput">add</span> and <span class="doxyComputerOutput">addHash</span> for variable-size types must not assume that the hasher type considers the size as part of the hash; they must explicitly add the size to the hash. See for example specializations for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a></span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></span>.</p>


<p>Additionally, since types are eventually forwarded to the hasher's <span class="doxyComputerOutput">void update(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt;)</span> method, endianness plays a role in the hash computation (for example when computing <span class="doxyComputerOutput">add((int)123)</span>). Specifiying a non-<span class="doxyComputerOutput">native</span> <span class="doxyComputerOutput">Endianness</span> template parameter allows to compute stable hash across platforms with different endianness.</p>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### HasAddHashT {#a770b706b2dcfbb64c717a1cbe9418874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HashBuilder&lt; HasherT, Endianness &gt;::HasAddHashT = 
      decltype(addHash(std::declval&lt;HashBuilder &amp;&gt;(), std::declval&lt;T &amp;&gt;()))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### HasByteSwapT {#adcce0ed276b7f972d77f8b095bd0093b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HashBuilder&lt; HasherT, Endianness &gt;::HasByteSwapT =  decltype(support::endian::byte_swap(
      std::declval&lt;T &amp;&gt;(), llvm::endianness::little))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HashBuilder() {#a3790ea10d4f6d2364d6b1fb2bddfbf4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT, llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HashBuilder&lt; HasherT, Endianness &gt;::HashBuilder (HasherT &amp; Hasher)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### HashBuilder() {#af8733fcc0780d8e7f05a7428721159ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... ArgTypes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HashBuilder&lt; HasherT, Endianness &gt;::HashBuilder (ArgTypes &amp;&amp;... Args)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a91945efc8e44a3f170402a1b1a2316fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; hashbuilder_detail::IsHashableData&lt; T &gt;::value, HashBuilder &amp; &gt; llvm::HashBuilder&lt; HasherT, Endianness &gt;::add (T Value)</td>
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

<p>Implement hashing for hashable data types, e.g. integral or enum values.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>Referenced by <a href="#a8e8f681c61a2745facd1cb55855fe402">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::add</a>, <a href="#ab4c3f8c5c42740075dea32797798473f">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::add</a>, <a href="#a7d71f0c32204f6a2f72915b7ad28d215">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::add</a>, <a href="#a3a94d5635dcb6728b77fc7ae9157abb4">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::add</a>, <a href="#a1815b02e7fafbe2f603c7893bd131666">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::add</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#af825651dbfebd80aeaca895edd9629a5">llvm::VersionTuple::addHash</a>, <a href="#aac10ca9284dac49b244037588df79ca2">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::addRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a22834e90a038045330c1385f188104f5">computeFullStackId</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a59956a56d1a2c15842922d6c2ba8de18">computeStackId</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6a4b5ed3aee26b7c67700b5e0fbc4d2f">llvm::hash_value</a>.</p>

</div>
</div>

### add() {#a8e8f681c61a2745facd1cb55855fe402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashBuilder &amp; llvm::HashBuilder&lt; HasherT, Endianness &gt;::add (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; Value)</td>
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

<p>Support hashing <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a></span>.</p>


<p><span class="doxyComputerOutput">Value.size()</span> is taken into account to ensure cases like</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add({1});</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add({2, 3});</span></span></div>

</div>


<p>and</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add({1, 2});</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add({3});</span></span></div>

</div>


<p>do not collide.</p>


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### add() {#a1815b02e7fafbe2f603c7893bd131666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT, llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashBuilder &amp; llvm::HashBuilder&lt; HasherT, Endianness &gt;::add (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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

<p>Support hashing <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></span>.</p>


<p><span class="doxyComputerOutput">Value.size()</span> is taken into account to ensure cases like</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add(</span><span class="doxyHighlightStringLiteral">"a"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add(</span><span class="doxyHighlightStringLiteral">"bc"</span><span class="doxyHighlight">);</span></span></div>

</div>


<p>and</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add(</span><span class="doxyHighlightStringLiteral">"ab"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">builder.add(</span><span class="doxyHighlightStringLiteral">"c"</span><span class="doxyHighlight">);</span></span></div>

</div>


<p>do not collide.</p>


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### add() {#a10e1cde5bdf37faed1fafd171aa33619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; is_detected&lt; HasAddHashT, T &gt;::value &amp;&amp;!hashbuilder_detail::IsHashableData&lt; T &gt;::value, HashBuilder &amp; &gt; llvm::HashBuilder&lt; HasherT, Endianness &gt;::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Value)</td>
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

<p>Implement hashing for user-defined <span class="doxyComputerOutput">struct</span>s.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> user-define <span class="doxyComputerOutput">struct</span> can participate in hashing via <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a></span> by providing a <span class="doxyComputerOutput">addHash</span> templated function.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">template</span><span class="doxyHighlight"> &lt;</span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> HasherT, llvm::endianness Endianness&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> addHash(<a href="#a3790ea10d4f6d2364d6b1fb2bddfbf4e">HashBuilder&lt;HasherT, Endianness&gt;</a> &amp;HBuilder,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> UserDefinedStruct &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#a066e2a31a13d6520e52ae1944f194662">Value</a>);</span></span></div>

</div>


<p>For example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">SimpleStruct {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">template</span><span class="doxyHighlight"> &lt;</span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> HasherT, llvm::endianness Endianness&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> addHash(<a href="#a3790ea10d4f6d2364d6b1fb2bddfbf4e">HashBuilder&lt;HasherT, Endianness&gt;</a> &amp;HBuilder,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> SimpleStruct &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#a066e2a31a13d6520e52ae1944f194662">Value</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  HBuilder.add(<a href="/web-llvm/docs/api/namespaces/llvm/#a066e2a31a13d6520e52ae1944f194662">Value</a>.c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  HBuilder.add(<a href="/web-llvm/docs/api/namespaces/llvm/#a066e2a31a13d6520e52ae1944f194662">Value</a>.i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>To avoid endianness issues, specializations of <span class="doxyComputerOutput">addHash</span> should generally rely on exising <span class="doxyComputerOutput">add</span>, <span class="doxyComputerOutput">addRange</span>, and <span class="doxyComputerOutput">addRangeElements</span> functions. If directly using <span class="doxyComputerOutput">update</span>, an implementation must correctly handle endianness.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">__attribute__ ((packed)) StructWithFastHash {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// If possible, we want to hash both `I` and `C` in a single</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// `update` call for performance concerns.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">template</span><span class="doxyHighlight"> &lt;</span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> HasherT, llvm::endianness Endianness&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> addHash(HashBuilder&lt;HasherT, Endianness&gt; &amp;HBuilder,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> StructWithFastHash &amp;Value) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (Endianness == <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::endianness::native</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      HBuilder.update(<a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">ArrayRef</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">reinterpret_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight">uint8_t *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(&amp;Value), </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(Value)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Rely on existing `add` methods to handle endianness.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      HBuilder.add(<a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">Value</a>.I);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      HBuilder.add(<a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">Value</a>.C);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>To avoid collisions, specialization of <span class="doxyComputerOutput">addHash</span> for variable-size types must take the size into account.</p>


<p>For example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">CustomContainer {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">private</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a8d87e69e124542d3338b631934cdbea9aaa56a2e65d8106aef3c61e4f6bf94fdb">Elements</a>[100];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  CustomContainer(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>) : <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>(<a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> = 0; <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> != <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>; ++<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a8d87e69e124542d3338b631934cdbea9aaa56a2e65d8106aef3c61e4f6bf94fdb">Elements</a>[<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>] = <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">template</span><span class="doxyHighlight"> &lt;</span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> HasherT, llvm::endianness Endianness&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> addHash(HashBuilder&lt;HasherT, Endianness&gt; &amp;HBuilder,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> CustomContainer &amp;Value) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (Endianness == <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::endianness::native</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      HBuilder.update(<a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">ArrayRef</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">reinterpret_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight">uint8_t *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(&amp;<a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">Value</a>.Size),</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(<a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">Value</a>.Size) + <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">Value</a>.Size * </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(<a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">Value</a>.Elements[0])));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// `addRange` will take care of encoding the size.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      HBuilder.addRange(&amp;<a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">Value</a>.Elements[0], &amp;<a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">Value</a>.Elements[0] +</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5">Value</a>.Size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### add() {#ab4c3f8c5c42740075dea32797798473f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashBuilder &amp; llvm::HashBuilder&lt; HasherT, Endianness &gt;::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a>, T2 &gt; &amp; Value)</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### add() {#a7d71f0c32204f6a2f72915b7ad28d215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashBuilder &amp; llvm::HashBuilder&lt; HasherT, Endianness &gt;::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::tuple&lt; Ts... &gt; &amp; Arg)</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### add() {#a3a94d5635dcb6728b77fc7ae9157abb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt;(sizeof...(Ts) &gt; 1), HashBuilder &amp; &gt; llvm::HashBuilder&lt; HasherT, Endianness &gt;::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Ts &amp;... Args)</td>
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

<p>A convenenience variadic helper.</p>


<p>It simply iterates over its arguments, in order.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a91945efc8e44a3f170402a1b1a2316fe">add</a>(Arg1, Arg2);</span></span></div>

</div>


<p>is equivalent to</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a91945efc8e44a3f170402a1b1a2316fe">add</a>(Arg1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a91945efc8e44a3f170402a1b1a2316fe">add</a>(Arg2)</span></span></div>

</div>


<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### addRange() {#aac10ca9284dac49b244037588df79ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ForwardIteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashBuilder &amp; llvm::HashBuilder&lt; HasherT, Endianness &gt;::addRange (ForwardIteratorT First, ForwardIteratorT Last)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>Referenced by <a href="#a499eab6d3ce4ac7f7342621c39b950ef">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::addRange</a>.</p>

</div>
</div>

### addRange() {#a499eab6d3ce4ac7f7342621c39b950ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RangeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashBuilder &amp; llvm::HashBuilder&lt; HasherT, Endianness &gt;::addRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RangeT &amp; Range)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### addRangeElements() {#a4e1c3c0190de95c6a73e63dcb02f3f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ForwardIteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashBuilder &amp; llvm::HashBuilder&lt; HasherT, Endianness &gt;::addRangeElements (ForwardIteratorT First, ForwardIteratorT Last)</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>Referenced by <a href="#aac10ca9284dac49b244037588df79ca2">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::addRange</a> and <a href="#a44f68de74fc37dcfba02bab2f044cca4">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::addRangeElements</a>.</p>

</div>
</div>

### addRangeElements() {#a44f68de74fc37dcfba02bab2f044cca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RangeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashBuilder &amp; llvm::HashBuilder&lt; HasherT, Endianness &gt;::addRangeElements (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RangeT &amp; Range)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### adjustForEndiannessAndAdd() {#a2f0e0694a40550ad8156ff89999df152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; is_detected&lt; HasByteSwapT, T &gt;::value, HashBuilder &amp; &gt; llvm::HashBuilder&lt; HasherT, Endianness &gt;::adjustForEndiannessAndAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Value)</td>
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

<p>Adjust <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for the target endianness and add it to the hash.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>Referenced by <a href="#a91945efc8e44a3f170402a1b1a2316fe">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::add</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRangeElementsImpl() {#a12329287391db2113bfc3f64c8549fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ForwardIteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashBuilder &amp; llvm::HashBuilder&lt; HasherT, Endianness &gt;::addRangeElementsImpl (ForwardIteratorT First, ForwardIteratorT Last, std::forward_iterator_tag)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### addRangeElementsImpl() {#a6773e7544a444016ffa6885be69b42ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; hashbuilder_detail::IsHashableData&lt; T &gt;::value &amp;&amp;Endianness==llvm::endianness::native, HashBuilder &amp; &gt; llvm::HashBuilder&lt; HasherT, Endianness &gt;::addRangeElementsImpl (T * First, T * Last, std::forward_iterator_tag)</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
