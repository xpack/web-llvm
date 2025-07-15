---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/abstractmanglingparser/namestate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NameState` Struct Reference

<p>Holds some extra information about a &lt;name&gt; that is being parsed. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct AbstractManglingParser::NameState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">llvm/Demangle/ItaniumDemangle.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea3bdd076ba31ca6e06cb40948f11da">NameState</a> (AbstractManglingParser *Enclosing)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d879e40930e72c6173c3846c7532220">CtorDtorConversion</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cbd863f8c3ce436ff907d6d8ebfba21">EndsWithTemplateArgs</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16e7c8207657635dc4567fa53bf675e">CVQualifiers</a> = <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7adc7b331ccab83e31a327816731dc82f2">QualNone</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8ed">FunctionRefQual</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8fbdf60e6b213206626e6052532695">ReferenceQualifier</a> = <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8eda74a742e365bc15a3ee3b9a2a4b0e79f3">FrefQualNone</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75550d9a0d2fed7ad3316d3ddb24f4f1">ForwardTemplateRefsBegin</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1403a1c9219dd4e4e7c57f1a7dfcf076">HasExplicitObjectParameter</a> = false</td>
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

<p>Holds some extra information about a &lt;name&gt; that is being parsed.</p>


<p>This information is only pertinent if the &lt;name&gt; refers to an &lt;encoding&gt;.</p>


<p>Definition at line 2922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NameState() {#a5ea3bdd076ba31ca6e06cb40948f11da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::NameState (<a href="/web-llvm/docs/api/structs/abstractmanglingparser">AbstractManglingParser</a> * Enclosing)</td>
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



<p>Definition at line 2930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#aa493f84f85dacf77dc2ecc4486d3cefe">AbstractManglingParser&lt; Derived, Alloc &gt;::AbstractManglingParser</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a229ec0a06959ee93e9e5f24e3682b086">AbstractManglingParser&lt; Derived, Alloc &gt;::ForwardTemplateRefs</a>, <a href="#a75550d9a0d2fed7ad3316d3ddb24f4f1">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::ForwardTemplateRefsBegin</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CtorDtorConversion {#a2d879e40930e72c6173c3846c7532220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::CtorDtorConversion = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2923 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>.</p>

</div>
</div>

### CVQualifiers {#aa16e7c8207657635dc4567fa53bf675e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Qualifiers AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::CVQualifiers = <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7adc7b331ccab83e31a327816731dc82f2">QualNone</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>.</p>

</div>
</div>

### EndsWithTemplateArgs {#a1cbd863f8c3ce436ff907d6d8ebfba21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::EndsWithTemplateArgs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2924 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>.</p>

</div>
</div>

### ForwardTemplateRefsBegin {#a75550d9a0d2fed7ad3316d3ddb24f4f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::ForwardTemplateRefsBegin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2927 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a5ea3bdd076ba31ca6e06cb40948f11da">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::NameState</a>.</p>

</div>
</div>

### HasExplicitObjectParameter {#a1403a1c9219dd4e4e7c57f1a7dfcf076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::HasExplicitObjectParameter = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2928 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>.</p>

</div>
</div>

### ReferenceQualifier {#aac8fbdf60e6b213206626e6052532695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionRefQual AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::ReferenceQualifier = <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8eda74a742e365bc15a3ee3b9a2a4b0e79f3">FrefQualNone</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2926 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
