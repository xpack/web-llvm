---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/retainedknowledge
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RetainedKnowledge` Struct Reference

<p>Represent one information held inside an operand bundle of an llvm.assume. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RetainedKnowledge { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">llvm/Analysis/AssumeBundleQueries.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc93b51f6b1c4ea5ac926d9b28e38e70">operator==</a> (RetainedKnowledge Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94e146b3c708ec72472ad81e9370cff0">operator!=</a> (RetainedKnowledge Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aece4000222328082a903cdbda2648c10">operator&lt;</a> (RetainedKnowledge Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is only intended for use in std::min/std<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">max</a> between attribute that only differ in ArgValue. <a href="#aece4000222328082a903cdbda2648c10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ce2f6504c38f2148b3a8d41e283f1c">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a054a26c551d4de8f1af4d75a7a67a42a">AttrKind</a> = <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">Attribute::None</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b64a97b9157b9bd9a1d924cae66254b">ArgValue</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ac6afa72b262e95ceb85328c6cb5c6">WasOn</a> = nullptr</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge">RetainedKnowledge</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5831cbb744aa662c00d3cb9e56a1dad3">none</a> ()</td>
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

<p>Represent one information held inside an operand bundle of an llvm.assume.</p>


<p>AttrKind is the property that holds. WasOn if not null is that <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for which AttrKind holds. ArgValue is optionally an argument of the attribute. For example if we know that P has an alignment of at least four:</p>


<ul class="doxyList ">
<li>AttrKind will be Attribute::Alignment.</li>
<li>WasOn will be P.</li>
<li>ArgValue will be 4.</li>
</ul>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator bool() {#a35ce2f6504c38f2148b3a8d41e283f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RetainedKnowledge::operator bool ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a>.</p>


<p>References <a href="#a054a26c551d4de8f1af4d75a7a67a42a">AttrKind</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a>.</p>

</div>
</div>

### operator!=() {#a94e146b3c708ec72472ad81e9370cff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RetainedKnowledge::operator!= (<a href="/web-llvm/docs/api/structs/llvm/retainedknowledge">RetainedKnowledge</a> Other)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator&lt;() {#aece4000222328082a903cdbda2648c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RetainedKnowledge::operator&lt; (<a href="/web-llvm/docs/api/structs/llvm/retainedknowledge">RetainedKnowledge</a> Other)</td>
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

<p>This is only intended for use in std::min/std<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">max</a> between attribute that only differ in ArgValue.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a>.</p>


<p>References <a href="#a3b64a97b9157b9bd9a1d924cae66254b">ArgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a054a26c551d4de8f1af4d75a7a67a42a">AttrKind</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a99ac6afa72b262e95ceb85328c6cb5c6">WasOn</a>.</p>

</div>
</div>

### operator==() {#adc93b51f6b1c4ea5ac926d9b28e38e70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RetainedKnowledge::operator== (<a href="/web-llvm/docs/api/structs/llvm/retainedknowledge">RetainedKnowledge</a> Other)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a>.</p>


<p>References <a href="#a3b64a97b9157b9bd9a1d924cae66254b">ArgValue</a>, <a href="#a054a26c551d4de8f1af4d75a7a67a42a">AttrKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a99ac6afa72b262e95ceb85328c6cb5c6">WasOn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ArgValue {#a3b64a97b9157b9bd9a1d924cae66254b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::RetainedKnowledge::ArgValue = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a201cb1ede84e08442e7433b7b3eaed69">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addKnowledge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#ae3d9d3b5408e22143d8aee0d684454c4">anonymous{AssumeBundleBuilder.cpp}::canonicalizedKnowledge</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0879506ce04a79b173daca40d1967e35">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::dropRedundantKnowledge</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#a3e49ed1824b63334071840d20aab03ba">isDereferenceableAndAlignedPointer</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a336ed98852175e7e955e9217080bd596">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::isKnowledgeWorthPreserving</a>, <a href="#aece4000222328082a903cdbda2648c10">operator&lt;</a>, <a href="#adc93b51f6b1c4ea5ac926d9b28e38e70">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### AttrKind {#a054a26c551d4de8f1af4d75a7a67a42a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind llvm::RetainedKnowledge::AttrKind = <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">Attribute::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a201cb1ede84e08442e7433b7b3eaed69">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addKnowledge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#ae3d9d3b5408e22143d8aee0d684454c4">anonymous{AssumeBundleBuilder.cpp}::canonicalizedKnowledge</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0879506ce04a79b173daca40d1967e35">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::dropRedundantKnowledge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95c64b72ee738c969f87befc9b66ee30">llvm::getKnowledgeFromUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a336ed98852175e7e955e9217080bd596">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::isKnowledgeWorthPreserving</a>, <a href="#a35ce2f6504c38f2148b3a8d41e283f1c">operator bool</a>, <a href="#aece4000222328082a903cdbda2648c10">operator&lt;</a>, <a href="#adc93b51f6b1c4ea5ac926d9b28e38e70">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### WasOn {#a99ac6afa72b262e95ceb85328c6cb5c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::RetainedKnowledge::WasOn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a201cb1ede84e08442e7433b7b3eaed69">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addKnowledge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#ae3d9d3b5408e22143d8aee0d684454c4">anonymous{AssumeBundleBuilder.cpp}::canonicalizedKnowledge</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0879506ce04a79b173daca40d1967e35">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::dropRedundantKnowledge</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a336ed98852175e7e955e9217080bd596">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::isKnowledgeWorthPreserving</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0d8e70094baa4fcc5eb68b59de54dc92">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeRange</a>, <a href="#aece4000222328082a903cdbda2648c10">operator&lt;</a>, <a href="#adc93b51f6b1c4ea5ac926d9b28e38e70">operator==</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aba1e9ea5dd5dfc2b1559cb6cef8b4854">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::tryToPreserveWithoutAddingAssume</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### none() {#a5831cbb744aa662c00d3cb9e56a1dad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetainedKnowledge llvm::RetainedKnowledge::none ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5ade489c0f3b2b272cfcf0bb8f011399">llvm::getKnowledgeForValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95c64b72ee738c969f87befc9b66ee30">llvm::getKnowledgeFromUse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a21fa9fb3ba25eaa02fae01f428ef2fdf">llvm::simplifyRetainedKnowledge</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">AssumeBundleQueries.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
