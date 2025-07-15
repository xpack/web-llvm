---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-itaniummanglingcanonicalizer-cpp-/foldingsetnodeidbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FoldingSetNodeIDBuilder` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{ItaniumManglingCanonicalizer.cpp}::FoldingSetNodeIDBuilder { ... }
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5769c1ee9e18afe85c96630a9dc144e">operator()</a> (const Node *P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80c0e5858306bc383a0d29891859ef18">operator()</a> (std::string_view Str)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8036d86a9c26a961d233dd9d9ddc8957">operator()</a> (T V) -&gt; std::enable_if_t&lt; std::is_integral_v&lt; T &gt;||std::is_enum_v&lt; T &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21bd9c6a098db6f747cbea4fb6eedcc3">operator()</a> (itanium_demangle::NodeArray A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">llvm::FoldingSetNodeID</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158e52ff9d0f9535e917ee58ae9a4799">ID</a></td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator()() {#aa5769c1ee9e18afe85c96630a9dc144e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumManglingCanonicalizer.cpp}::FoldingSetNodeIDBuilder::operator() (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/node">Node</a> * P)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<p>References <a href="#a158e52ff9d0f9535e917ee58ae9a4799">ID</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### operator()() {#a80c0e5858306bc383a0d29891859ef18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumManglingCanonicalizer.cpp}::FoldingSetNodeIDBuilder::operator() (std::string_view Str)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<p>Reference <a href="#a158e52ff9d0f9535e917ee58ae9a4799">ID</a>.</p>

</div>
</div>

### operator()() {#a8036d86a9c26a961d233dd9d9ddc8957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_integral_v&lt; T &gt;||std::is_enum_v&lt; T &gt; &gt; anonymous{ItaniumManglingCanonicalizer.cpp}::FoldingSetNodeIDBuilder::operator() (T V)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<p>Reference <a href="#a158e52ff9d0f9535e917ee58ae9a4799">ID</a>.</p>

</div>
</div>

### operator()() {#a21bd9c6a098db6f747cbea4fb6eedcc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ItaniumManglingCanonicalizer.cpp}::FoldingSetNodeIDBuilder::operator() (itanium_demangle::NodeArray A)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a158e52ff9d0f9535e917ee58ae9a4799">ID</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ID {#a158e52ff9d0f9535e917ee58ae9a4799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FoldingSetNodeID&amp; anonymous{ItaniumManglingCanonicalizer.cpp}::FoldingSetNodeIDBuilder::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a>.</p>


<p>Referenced by <a href="#aa5769c1ee9e18afe85c96630a9dc144e">operator()</a>, <a href="#a21bd9c6a098db6f747cbea4fb6eedcc3">operator()</a>, <a href="#a80c0e5858306bc383a0d29891859ef18">operator()</a> and <a href="#a8036d86a9c26a961d233dd9d9ddc8957">operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp">ItaniumManglingCanonicalizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
