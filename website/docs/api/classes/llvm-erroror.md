---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/erroror
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ErrorOr` Class Template Reference

<p>Represents either an error or a value T. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T&gt;
class llvm::ErrorOr&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">llvm/Support/ErrorOr.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a044d928a33e6a9f4c2276ac7aa035459">storage_type</a> = std::conditional_t&lt; isRef, wrap, T &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8880f821ec5d10ad8e88c603705c3be0">wrap</a> = std::reference_wrapper&lt; std::remove_reference_t&lt; T &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3eccc0bc7e67ac25de29d2e68ff92c8a">reference</a> = std::remove_reference_t&lt; T &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a445cf33ba57f80a2797050201ac33929">const_reference</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::remove_reference_t&lt; T &gt; &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8c7d06391f9e80621f125f992b9effbe">pointer</a> = std::remove_reference_t&lt; T &gt; *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aea54df9ca310a40cad0a314a43240d20">const_pointer</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::remove_reference_t&lt; T &gt; *</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7efd4fdaf2b3305e13c1358dff404193">ErrorOr</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class E&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2cad52048a7d41edabe8c195f17d96f4">ErrorOr</a> (E ErrorCode, std::enable_if_t&lt; std::is_error_code_enum&lt; E &gt;::value||std::is_error_condition_enum&lt; E &gt;::value, void * &gt;=nullptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0b9b6eb49cc512af35f805069a24dfa7">ErrorOr</a> (std::error_code EC)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0c88a3150a8205e8cda5adfd39764e56">ErrorOr</a> (OtherT &amp;&amp;Val, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *=nullptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a20081c99e138c9642200e57357ce3030">ErrorOr</a> (const ErrorOr &amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a85c93f60d48db111d6c1268fea22e8a5">ErrorOr</a> (const ErrorOr&lt; OtherT &gt; &amp;Other, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *=nullptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#abca6cf2d304e0f62ab618356a4ae73a7">ErrorOr</a> (const ErrorOr&lt; OtherT &gt; &amp;Other, std::enable_if_t&lt;!std::is_convertible_v&lt; OtherT, const T &amp; &gt; &gt; *=nullptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a56e3928f88902bab6f3c04488ff5fbd4">ErrorOr</a> (ErrorOr &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a791904015531439ae55a4de9c2e201ce">ErrorOr</a> (ErrorOr&lt; OtherT &gt; &amp;&amp;Other, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *=nullptr)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac588a4604a42c9158bfc57eecbf275be">ErrorOr</a> (ErrorOr&lt; OtherT &gt; &amp;&amp;Other, std::enable_if_t&lt;!std::is_convertible_v&lt; OtherT, T &gt; &gt; *=nullptr)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a776812c4ac335832e0799b1318bc4eba">~ErrorOr</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b5cabc7f13c789f90d75c6ed2399092">operator=</a> (const ErrorOr &amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add58e99c48b004cc71fcc70ab9cfd9a5">operator=</a> (ErrorOr &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a912f09c878488673ca05dd079bbec829">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return false if there is an error. <a href="#a912f09c878488673ca05dd079bbec829">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab0035295464e86743b6ecc4ddcd427b">operator-&gt;</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acb7e39d04666f982b8a409e7ab804959">operator-&gt;</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">reference</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a727e57603b3724522121b7846147afa3">operator*</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_reference</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a346afb86492b1e9cf12667aec43bd134">operator*</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">reference</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7903f14c3b4fb5b4f9f9fa8b4ee0b4eb">get</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_reference</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06487cfa60a884310d4c65ac6cbe7e71">get</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8300c72908f1845c931951ed4b2a2375">getError</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a97178cfc81620d4eeaa571edd020fd92">copyConstruct</a> (const ErrorOr&lt; OtherT &gt; &amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8d3c723de722be4e4f6bc1e8177daa3">copyAssign</a> (const ErrorOr&lt; OtherT &gt; &amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46b4be20cbf54384f068fa6b78280648">moveConstruct</a> (ErrorOr&lt; OtherT &gt; &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OtherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6083afd8d2655f1719b4c3ac47a131fd">moveAssign</a> (ErrorOr&lt; OtherT &gt; &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a90f66105099f0ed2c6f3674adc24a135">toPointer</a> (pointer Val)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d34a6d4bbb0db7ab59e78740b4b2342">toPointer</a> (const_pointer Val) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1921c707d14a7911c84d95ba1f8d465b">toPointer</a> (wrap *Val)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">const_pointer</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed034fa4094dd4ce6fe56e47fcb1c954">toPointer</a> (const wrap *Val) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a044d928a33e6a9f4c2276ac7aa035459">storage_type</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acfeeaf590cee5e4801cfd2cba39f7777">getStorage</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a044d928a33e6a9f4c2276ac7aa035459">storage_type</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3997507294d7b188ad693c0350cb35ad">getStorage</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::error_code *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26d3744060f5d43db4e502b6f8556013">getErrorStorage</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::error_code *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa893712b59e4fa470c98c2cf7567d00b">getErrorStorage</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/alignedchararrayunion">AlignedCharArrayUnion</a>&lt; <a href="#a044d928a33e6a9f4c2276ac7aa035459">storage_type</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9376d92779bc32f11940ef7f6d3d8dc">TStorage</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/alignedchararrayunion">AlignedCharArrayUnion</a>&lt; std::error_code &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1676886b24c4de180e2bc5a1c4b58e7e">ErrorStorage</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/erroror">llvm::ErrorOr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35459fe8922a7733aed5ab174e0858ad"></a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5827ef4cff7d4f0840d1bfe4d47861fd">HasError</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T1&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae1b3d98e78336413907df7e74897d571">compareThisIfSameType</a> (const T1 &amp;a, const T1 &amp;b)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T1, class T2&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1cae9de8fedc4c8a647340ea31b80e4f">compareThisIfSameType</a> (const T1 &amp;a, const T2 &amp;b)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a545f0e0462d6760341aa0726d29edda8">isRef</a> = std::is_reference_v&lt;T&gt;</td>
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

<p>Represents either an error or a value T.</p>


<p>ErrorOr&lt;T&gt; is a pointer-like class that represents the result of an operation. The result is either an error, or a value of type T. This is designed to emulate the usage of returning a pointer where nullptr indicates failure. However instead of just knowing that the operation failed, we also have an error_code and optional user data that describes why it failed.</p>


<p>It is used like the following.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a7efd4fdaf2b3305e13c1358dff404193">ErrorOr&lt;Buffer&gt;</a> getBuffer();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> buffer = getBuffer();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (error_code ec = buffer.getError())</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">buffer-&gt;write(</span><span class="doxyHighlightStringLiteral">"adena"</span><span class="doxyHighlight">);</span></span></div>

</div>


<p>Implicit conversion to bool returns true if there is a usable value. The unary * and -&gt; operators provide pointer like access to the value. Accessing the value when there is an error has undefined behavior.</p>


<p>When T is a reference type the behavior is slightly different. The reference is held in a std::reference_wrapper&lt;std::remove_reference&lt;T&gt;::type&gt;, and there is special handling to make operator -&gt; work as if T was not a reference.</p>


<p>T cannot be a rvalue reference.</p>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### storage\_type {#a044d928a33e6a9f4c2276ac7aa035459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ErrorOr&lt; T &gt;::storage_type =  std::conditional_t&lt;isRef, wrap, T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### const\_pointer {#aea54df9ca310a40cad0a314a43240d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ErrorOr&lt; T &gt;::const_pointer =  const std::remove_reference_t&lt;T&gt; *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### const\_reference {#a445cf33ba57f80a2797050201ac33929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ErrorOr&lt; T &gt;::const_reference =  const std::remove_reference_t&lt;T&gt; &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### pointer {#a8c7d06391f9e80621f125f992b9effbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ErrorOr&lt; T &gt;::pointer =  std::remove_reference_t&lt;T&gt; *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### reference {#a3eccc0bc7e67ac25de29d2e68ff92c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ErrorOr&lt; T &gt;::reference =  std::remove_reference_t&lt;T&gt; &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### wrap {#a8880f821ec5d10ad8e88c603705c3be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ErrorOr&lt; T &gt;::wrap =  std::reference_wrapper&lt;std::remove_reference_t&lt;T&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ErrorOr {#a7efd4fdaf2b3305e13c1358dff404193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>Reference <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>.</p>


<p>Referenced by <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>, <a href="#a20081c99e138c9642200e57357ce3030">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>, <a href="#a85c93f60d48db111d6c1268fea22e8a5">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>, <a href="#abca6cf2d304e0f62ab618356a4ae73a7">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>, <a href="#a56e3928f88902bab6f3c04488ff5fbd4">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>, <a href="#a791904015531439ae55a4de9c2e201ce">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>, <a href="#ac588a4604a42c9158bfc57eecbf275be">llvm::ErrorOr&lt; T &gt;::ErrorOr</a>, <a href="#a06487cfa60a884310d4c65ac6cbe7e71">llvm::ErrorOr&lt; T &gt;::get</a>, <a href="#a7b5cabc7f13c789f90d75c6ed2399092">llvm::ErrorOr&lt; T &gt;::operator=</a> and <a href="#add58e99c48b004cc71fcc70ab9cfd9a5">llvm::ErrorOr&lt; T &gt;::operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ErrorOr() {#a2cad52048a7d41edabe8c195f17d96f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class E&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::ErrorOr (<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> ErrorCode, std::enable_if_t&lt; std::is_error_code_enum&lt; <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> &gt;::value||std::is_error_condition_enum&lt; <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> &gt;::value, void * &gt;)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

### ErrorOr() {#a0b9b6eb49cc512af35f805069a24dfa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::ErrorOr (std::error_code EC)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

### ErrorOr() {#a0c88a3150a8205e8cda5adfd39764e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::ErrorOr (OtherT &amp;&amp; Val, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### ErrorOr() {#a20081c99e138c9642200e57357ce3030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::ErrorOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a> &amp; Other)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### ErrorOr() {#a85c93f60d48db111d6c1268fea22e8a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::ErrorOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; OtherT &gt; &amp; Other, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### ErrorOr() {#abca6cf2d304e0f62ab618356a4ae73a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::ErrorOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; OtherT &gt; &amp; Other, std::enable_if_t&lt;!std::is_convertible_v&lt; OtherT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; &gt; &gt; *)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### ErrorOr() {#a56e3928f88902bab6f3c04488ff5fbd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::ErrorOr (<a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a> &amp;&amp; Other)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### ErrorOr() {#a791904015531439ae55a4de9c2e201ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::ErrorOr (<a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; OtherT &gt; &amp;&amp; Other, std::enable_if_t&lt; std::is_convertible_v&lt; OtherT, T &gt; &gt; *)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### ErrorOr() {#ac588a4604a42c9158bfc57eecbf275be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::ErrorOr (<a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; OtherT &gt; &amp;&amp; Other, std::enable_if_t&lt;!std::is_convertible_v&lt; OtherT, T &gt; &gt; *)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ErrorOr() {#a776812c4ac335832e0799b1318bc4eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::~ErrorOr ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a912f09c878488673ca05dd079bbec829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; T &gt;::operator bool ()</td>
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

<p>Return false if there is an error.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### operator-&gt;() {#aab0035295464e86743b6ecc4ddcd427b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::ErrorOr&lt; T &gt;::operator-&gt; ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### operator-&gt;() {#acb7e39d04666f982b8a409e7ab804959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pointer llvm::ErrorOr&lt; T &gt;::operator-&gt; ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### operator\*() {#a727e57603b3724522121b7846147afa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::ErrorOr&lt; T &gt;::operator* ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### operator\*() {#a346afb86492b1e9cf12667aec43bd134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference llvm::ErrorOr&lt; T &gt;::operator* ()</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### operator=() {#a7b5cabc7f13c789f90d75c6ed2399092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr &amp; llvm::ErrorOr&lt; T &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a> &amp; Other)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator=() {#add58e99c48b004cc71fcc70ab9cfd9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr &amp; llvm::ErrorOr&lt; T &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a> &amp;&amp; Other)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#a7903f14c3b4fb5b4f9f9fa8b4ee0b4eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::ErrorOr&lt; T &gt;::get ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#a12fb918c70f7885e7a8286a74548d860">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a18b55d565c6a0be0a063486e7c905cef">llvm::LTOModule::createFromFile</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a8c515c45d2e7357a98e076263ff9ee68">llvm::LTOModule::createFromOpenFileSlice</a>, <a href="/web-llvm/docs/api/classes/llvm/specialcaselist/#a5e125454a7bbe1568bddd90a3045bade">llvm::SpecialCaseList::createInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedbcf5909f70207a579202cbbbaa4893">llvm::DiffFilesWithTolerance</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a23cbef0272f92b38f3f6654ce8af1cfb">anonymous{DlltoolDriver.cpp}::doIdentify</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a80f5931fdc6db3599ee4309f5a62b917">doList</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac226baa3ffd0f255a8d2b6d978b81b2">llvm::getLazyIRFileModule</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#af8c1c55aabd3c2fe773936a5aeec05c8">llvm::LTOModule::isBitcodeFile</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/lineconsumer/#a48d140d0cd7e4ecf51e1192d6dc9910d">anonymous{GCOV.cpp}::LineConsumer::LineConsumer</a>, <a href="/web-llvm/docs/api/groups/llvmccorememorybuffers/#ga882a7aff0ee42d8def45505c07cb1588">LLVMCreateMemoryBufferWithContentsOfFile</a>, <a href="/web-llvm/docs/api/groups/llvmccorememorybuffers/#ga471f90956bfd49f4a5ecb522cfd6c1f5">LLVMCreateMemoryBufferWithSTDIN</a>, <a href="/web-llvm/docs/api/groups/llvmcbitreader/#ga1af45a3355d75b61ece499ee8965dcf5">LLVMGetBitcodeModuleInContext2</a>, <a href="/web-llvm/docs/api/groups/llvmcbitreader/#ga4a0ce3a2d9e26acbefa41a1bd7d1a225">LLVMParseBitcodeInContext2</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a50b4341d651ea41cb74546557170ebaa">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a3cc6f8b4a312834f3683fa1a90bda0ed">llvm::gsym::GsymReader::openFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9a2a0bea39c1731326a7e3504cba4da">llvm::parseAssemblyFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp/#aff85bfef450fa1ae5ee06c97367f94e4">parseAssemblyFileWithIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f23ddc70c8c903ce27bcef2e37f9d59">llvm::parseIRFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a65a056610f168d74a85291f1c00c6d7a">llvm::parseSummaryIndexAssemblyFile</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbcontext/#ae52c2cbdae2397ce1b4b36ab405efeaf">llvm::pdb::PDBContext::PDBContext</a>.</p>

</div>
</div>

### get() {#a06487cfa60a884310d4c65ac6cbe7e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference llvm::ErrorOr&lt; T &gt;::get ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>References <a href="#a7efd4fdaf2b3305e13c1358dff404193">llvm::ErrorOr&lt; T &gt;::ErrorOr</a> and <a href="#a06487cfa60a884310d4c65ac6cbe7e71">llvm::ErrorOr&lt; T &gt;::get</a>.</p>


<p>Referenced by <a href="#a06487cfa60a884310d4c65ac6cbe7e71">llvm::ErrorOr&lt; T &gt;::get</a>.</p>

</div>
</div>

### getError() {#a8300c72908f1845c931951ed4b2a2375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::ErrorOr&lt; T &gt;::getError ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#a933d031a629f7261df21829fbea78f94">llvm::LTOCodeGenerator::compileOptimized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a12fb918c70f7885e7a8286a74548d860">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a18b55d565c6a0be0a063486e7c905cef">llvm::LTOModule::createFromFile</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a8c515c45d2e7357a98e076263ff9ee68">llvm::LTOModule::createFromOpenFileSlice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#afdcc3a66137dcf1fb3dbdc7adaedc26c">llvm::objcopy::coff::createGnuDebugLinkSectionContents</a>, <a href="/web-llvm/docs/api/classes/llvm/specialcaselist/#a5e125454a7bbe1568bddd90a3045bade">llvm::SpecialCaseList::createInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae465be28151991b2345f467899ddb5e5">llvm::remarks::createYAMLParserFromMeta</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedbcf5909f70207a579202cbbbaa4893">llvm::DiffFilesWithTolerance</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a5edc743f072765fe8146c1f597d4bb37">llvm::vfs::RedirectingFileSystem::dir_begin</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a23cbef0272f92b38f3f6654ce8af1cfb">anonymous{DlltoolDriver.cpp}::doIdentify</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a80f5931fdc6db3599ee4309f5a62b917">doList</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac72192305c89532b4469f8533b6ecf5b">llvm::codegen::getBBSectionsMode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a03bfd76bddfe1a42326e93dc3c131c8c">llvm::object::Archive::Child::getBuffer</a>, <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aabc893bb91367b69e0edf27249081a78">llvm::NewArchiveMember::getFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac226baa3ffd0f255a8d2b6d978b81b2">llvm::getLazyIRFileModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7fed2696a3bda04b9f93d8b986758b3">llvm::getModuleSummaryIndexForFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1df6c429f484cbf4fd21a5d306f53671">llvm::libDriverMain</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/lineconsumer/#a48d140d0cd7e4ecf51e1192d6dc9910d">anonymous{GCOV.cpp}::LineConsumer::LineConsumer</a>, <a href="/web-llvm/docs/api/groups/llvmccorememorybuffers/#ga882a7aff0ee42d8def45505c07cb1588">LLVMCreateMemoryBufferWithContentsOfFile</a>, <a href="/web-llvm/docs/api/groups/llvmccorememorybuffers/#ga471f90956bfd49f4a5ecb522cfd6c1f5">LLVMCreateMemoryBufferWithSTDIN</a>, <a href="/web-llvm/docs/api/groups/llvmcbitreader/#ga1af45a3355d75b61ece499ee8965dcf5">LLVMGetBitcodeModuleInContext2</a>, <a href="/web-llvm/docs/api/groups/llvmcbitreader/#ga4a0ce3a2d9e26acbefa41a1bd7d1a225">LLVMParseBitcodeInContext2</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#ae1d1df29b280e901fe36cd22e7072f95">loadPdbFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a3cc6f8b4a312834f3683fa1a90bda0ed">llvm::gsym::GsymReader::openFile</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolrewriter/rewritemapparser/#a73f3ae9cac7a4557bd5c1e311548cd26">llvm::SymbolRewriter::RewriteMapParser::parse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9a2a0bea39c1731326a7e3504cba4da">llvm::parseAssemblyFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp/#aff85bfef450fa1ae5ee06c97367f94e4">parseAssemblyFileWithIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f23ddc70c8c903ce27bcef2e37f9d59">llvm::parseIRFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a65a056610f168d74a85291f1c00c6d7a">llvm::parseSummaryIndexAssemblyFile</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a041113ae9c86afaf78aca845b270af82">llvm::vfs::RedirectingFileSystem::status</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7c58f347a240684b93eb7ee8bfd6824">llvm::streamFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### copyAssign() {#ac8d3c723de722be4e4f6bc1e8177daa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ErrorOr&lt; T &gt;::copyAssign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; OtherT &gt; &amp; Other)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### copyConstruct() {#a97178cfc81620d4eeaa571edd020fd92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ErrorOr&lt; T &gt;::copyConstruct (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; OtherT &gt; &amp; Other)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### getErrorStorage() {#a26d3744060f5d43db4e502b6f8556013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code * llvm::ErrorOr&lt; T &gt;::getErrorStorage ()</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### getErrorStorage() {#aa893712b59e4fa470c98c2cf7567d00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::error_code * llvm::ErrorOr&lt; T &gt;::getErrorStorage ()</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### getStorage() {#acfeeaf590cee5e4801cfd2cba39f7777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">storage_type * llvm::ErrorOr&lt; T &gt;::getStorage ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### getStorage() {#a3997507294d7b188ad693c0350cb35ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const storage_type * llvm::ErrorOr&lt; T &gt;::getStorage ()</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### moveAssign() {#a6083afd8d2655f1719b4c3ac47a131fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ErrorOr&lt; T &gt;::moveAssign (<a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; OtherT &gt; &amp;&amp; Other)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### moveConstruct() {#a46b4be20cbf54384f068fa6b78280648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OtherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ErrorOr&lt; T &gt;::moveConstruct (<a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; OtherT &gt; &amp;&amp; Other)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### toPointer() {#a90f66105099f0ed2c6f3674adc24a135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::ErrorOr&lt; T &gt;::toPointer (pointer Val)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### toPointer() {#a4d34a6d4bbb0db7ab59e78740b4b2342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pointer llvm::ErrorOr&lt; T &gt;::toPointer (const_pointer Val)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### toPointer() {#a1921c707d14a7911c84d95ba1f8d465b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::ErrorOr&lt; T &gt;::toPointer (wrap * Val)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### toPointer() {#aed034fa4094dd4ce6fe56e47fcb1c954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pointer llvm::ErrorOr&lt; T &gt;::toPointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> wrap * Val)</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ErrorStorage {#a1676886b24c4de180e2bc5a1c4b58e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AlignedCharArrayUnion&lt;std::error_code&gt; llvm::ErrorOr&lt; T &gt;::ErrorStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### TStorage {#ae9376d92779bc32f11940ef7f6d3d8dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AlignedCharArrayUnion&lt;storage_type&gt; llvm::ErrorOr&lt; T &gt;::TStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a35459fe8922a7733aed5ab174e0858ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::ErrorOr llvm::ErrorOr&lt; T &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### HasError {#a5827ef4cff7d4f0840d1bfe4d47861fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ErrorOr&lt; T &gt;::HasError</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### compareThisIfSameType() {#ae1b3d98e78336413907df7e74897d571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T1&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ErrorOr&lt; T &gt;::compareThisIfSameType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &amp; a, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &amp; b)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

### compareThisIfSameType() {#a1cae9de8fedc4c8a647340ea31b80e4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T1, class T2&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ErrorOr&lt; T &gt;::compareThisIfSameType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a> &amp; a, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T2 &amp; b)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### isRef {#a545f0e0462d6760341aa0726d29edda8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ErrorOr&lt; T &gt;::isRef = std::is_reference_v&lt;T&gt;</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">ErrorOr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
