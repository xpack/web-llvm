---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/legacylegalizeactionstep
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LegacyLegalizeActionStep` Struct

<p>The result of a query. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LegacyLegalizeActionStep { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">llvm/CodeGen/GlobalISel/LegacyLegalizerInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59c5d038e9d30b7bb637d8ee35d2fbd">LegacyLegalizeActionStep</a> (LegacyLegalizeActions::LegacyLegalizeAction Action, unsigned TypeIdx, const LLT NewType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523026e4b795d5ad8bb103e4afa3aa50">operator==</a> (const LegacyLegalizeActionStep &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695d326dc57441ca67a0c3615ce5f7a5">Action</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The action to take or the final answer. <a href="#a695d326dc57441ca67a0c3615ce5f7a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ddfd76b191675a3ad824342af338b07">TypeIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If describing an action, the type index to change. Otherwise zero. <a href="#a9ddfd76b191675a3ad824342af338b07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd040e0a1122b2f96b2e93b4f71616aa">NewType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If describing an action, the new type for TypeIdx. Otherwise <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>{}. <a href="#afd040e0a1122b2f96b2e93b4f71616aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The result of a query.</p>


<p>It either indicates a final answer of Legal or Unsupported or describes an action that must be taken to make an operation more legal.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LegacyLegalizeActionStep() {#ae59c5d038e9d30b7bb637d8ee35d2fbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LegacyLegalizeActionStep::LegacyLegalizeActionStep (<a href="/web-llvm/docs/api/namespaces/llvm/legacylegalizeactions/#ad25716c86372dafbf624b34891685078">LegacyLegalizeActions::LegacyLegalizeAction</a> Action, unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NewType)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>References <a href="#a695d326dc57441ca67a0c3615ce5f7a5">Action</a>, <a href="#afd040e0a1122b2f96b2e93b4f71616aa">NewType</a> and <a href="#a9ddfd76b191675a3ad824342af338b07">TypeIdx</a>.</p>


<p>Referenced by <a href="#a523026e4b795d5ad8bb103e4afa3aa50">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a523026e4b795d5ad8bb103e4afa3aa50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegacyLegalizeActionStep::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legacylegalizeactionstep">LegacyLegalizeActionStep</a> &amp; RHS)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>References <a href="#a695d326dc57441ca67a0c3615ce5f7a5">Action</a>, <a href="#ae59c5d038e9d30b7bb637d8ee35d2fbd">LegacyLegalizeActionStep</a>, <a href="#afd040e0a1122b2f96b2e93b4f71616aa">NewType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a9ddfd76b191675a3ad824342af338b07">TypeIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Action {#a695d326dc57441ca67a0c3615ce5f7a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegacyLegalizeActions::LegacyLegalizeAction llvm::LegacyLegalizeActionStep::Action</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The action to take or the final answer.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#ae59c5d038e9d30b7bb637d8ee35d2fbd">LegacyLegalizeActionStep</a>, <a href="/web-llvm/docs/api/structs/llvm/legalizeactionstep/#aa24f30dfb027fd8d99607a723476154d">llvm::LegalizeActionStep::LegalizeActionStep</a> and <a href="#a523026e4b795d5ad8bb103e4afa3aa50">operator==</a>.</p>

</div>
</div>

### NewType {#afd040e0a1122b2f96b2e93b4f71616aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::LegacyLegalizeActionStep::NewType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If describing an action, the new type for TypeIdx. Otherwise <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>{}.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#ae59c5d038e9d30b7bb637d8ee35d2fbd">LegacyLegalizeActionStep</a> and <a href="#a523026e4b795d5ad8bb103e4afa3aa50">operator==</a>.</p>

</div>
</div>

### TypeIdx {#a9ddfd76b191675a3ad824342af338b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LegacyLegalizeActionStep::TypeIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If describing an action, the type index to change. Otherwise zero.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#ae59c5d038e9d30b7bb637d8ee35d2fbd">LegacyLegalizeActionStep</a> and <a href="#a523026e4b795d5ad8bb103e4afa3aa50">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
