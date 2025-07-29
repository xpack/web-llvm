---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/formatv-object
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `formatv_object` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename Tuple&gt;
class llvm::formatv_object&lt;Tuple&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/formatv-object-base">formatv_object_base</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Tuple&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a974591deeb830e3934264cf6b34fefbe">formatv_object</a> (StringRef Fmt, Tuple &amp;&amp;Params, bool Validate)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Tuple&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa2b5769d941dbf30c32568d432162952">formatv_object</a> (formatv_object const &amp;rhs)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Tuple&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3b24fb21aee12344fdaba1a14e3d7459">formatv_object</a> (formatv_object &amp;&amp;rhs)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Tuple&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Tuple</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb0e56be471de647a1dee0dc057e9061">Parameters</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Tuple&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/support/detail/format-adapter">support::detail::format_adapter</a> *, std::tuple_size&lt; Tuple &gt;::value &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab976c07fe3f3fab551eb4611647193f6">ParameterPointers</a></td>
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


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### formatv\_object() {#a974591deeb830e3934264cf6b34fefbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Tuple&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatv_object&lt; Tuple &gt;::formatv_object (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Fmt, Tuple &amp;&amp; Params, bool Validate)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base/#a454b6b825ab87db9fd04519ef66825dd">llvm::formatv_object_base::Fmt</a>, <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base/#a5ecf8eb658bde7495b1e140fc67668d4">llvm::formatv_object_base::formatv_object_base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base/#a03e52ddd60b2a1047b17ad0c5c5122dc">llvm::formatv_object_base::Validate</a>.</p>


<p>Referenced by <a href="#a3b24fb21aee12344fdaba1a14e3d7459">llvm::formatv_object&lt; Tuple &gt;::formatv_object</a> and <a href="#aa2b5769d941dbf30c32568d432162952">llvm::formatv_object&lt; Tuple &gt;::formatv_object</a>.</p>

</div>
</div>

### formatv\_object() {#aa2b5769d941dbf30c32568d432162952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Tuple&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatv_object&lt; Tuple &gt;::formatv_object (<a href="/web-llvm/docs/api/classes/llvm/formatv-object">formatv_object</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; rhs)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>Reference <a href="#a974591deeb830e3934264cf6b34fefbe">llvm::formatv_object&lt; Tuple &gt;::formatv_object</a>.</p>

</div>
</div>

### formatv\_object() {#a3b24fb21aee12344fdaba1a14e3d7459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Tuple&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatv_object&lt; Tuple &gt;::formatv_object (<a href="/web-llvm/docs/api/classes/llvm/formatv-object">formatv_object</a> &amp;&amp; rhs)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base/#a9c3d07d59e6f327f85e31c78a38db685">llvm::formatv_object_base::Adapters</a>, <a href="#a974591deeb830e3934264cf6b34fefbe">llvm::formatv_object&lt; Tuple &gt;::formatv_object</a>, <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base/#a5ecf8eb658bde7495b1e140fc67668d4">llvm::formatv_object_base::formatv_object_base</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ParameterPointers {#ab976c07fe3f3fab551eb4611647193f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Tuple&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;support::detail::format_adapter *, std::tuple_size&lt;Tuple&gt;::value&gt; llvm::formatv_object&lt; Tuple &gt;::ParameterPointers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>

</div>
</div>

### Parameters {#abb0e56be471de647a1dee0dc057e9061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Tuple&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Tuple llvm::formatv_object&lt; Tuple &gt;::Parameters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">FormatVariadic.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
