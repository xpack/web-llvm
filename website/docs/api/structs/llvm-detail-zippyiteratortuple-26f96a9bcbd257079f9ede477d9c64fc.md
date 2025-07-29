---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/zippyiteratortuple-26f96a9bcbd257079f9ede477d9c64fc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ZippyIteratorTuple` Struct Template

<p>Partial specialization for non-const tuple storage. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;template&lt; typename... &gt; class ItType, typename... Args, std::size_t... Ns&gt;
struct llvm::detail::ZippyIteratorTuple&lt;ItType, std::tuple&lt; Args... &gt;, std::index_sequence&lt; Ns... &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7d3e2c33cbff348e064dca39d7880e6">type</a> = ItType&lt; decltype(<a href="/web-llvm/docs/api/namespaces/llvm/#a1d927e3bff8edf86442c52cc36a35cc8">adl_begin</a>( std::get&lt; Ns &gt;(declval&lt; std::tuple&lt; Args... &gt; &amp; &gt;())))... &gt;</td>
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

<p>Partial specialization for non-const tuple storage.</p>

<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### type {#ac7d3e2c33cbff348e064dca39d7880e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;template&lt; typename... &gt; class ItType, typename... Args, std::size_t... Ns&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::ZippyIteratorTuple&lt; ItType, std::tuple&lt; Args... &gt;, std::index_sequence&lt; Ns... &gt; &gt;::type =  ItType&lt;decltype(adl_begin(
      std::get&lt;Ns&gt;(declval&lt;std::tuple&lt;Args...&gt; &amp;&gt;())))...&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
