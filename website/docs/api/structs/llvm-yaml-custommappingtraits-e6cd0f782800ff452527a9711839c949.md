---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/custommappingtraits-e6cd0f782800ff452527a9711839c949
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CustomMappingTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::CustomMappingTraits&lt;std::map&lt; uint64_t, WholeProgramDevirtResolution &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">llvm/IR/ModuleSummaryIndexYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2394e82dace4aa52c8852567306ade54">inputOne</a> (IO &amp;io, StringRef Key, std::map&lt; uint64_t, WholeProgramDevirtResolution &gt; &amp;V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249daf5101a60965d5b142fbb314b4bb">output</a> (IO &amp;io, std::map&lt; uint64_t, WholeProgramDevirtResolution &gt; &amp;V)</td>
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


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### inputOne() {#a2394e82dace4aa52c8852567306ade54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::CustomMappingTraits&lt; std::map&lt; uint64_t, WholeProgramDevirtResolution &gt; &gt;::inputOne (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; io, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, std::map&lt; uint64_t, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> &gt; &amp; V)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a930906994b5dc96a35696936fe705c15">llvm::yaml::IO::setError</a>.</p>

</div>
</div>

### output() {#a249daf5101a60965d5b142fbb314b4bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::CustomMappingTraits&lt; std::map&lt; uint64_t, WholeProgramDevirtResolution &gt; &gt;::output (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; io, std::map&lt; uint64_t, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> &gt; &amp; V)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a41972fe6f3fab862543b7b835a714f9b">llvm::utostr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
