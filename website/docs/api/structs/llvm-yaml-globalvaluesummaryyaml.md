---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/globalvaluesummaryyaml
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `GlobalValueSummaryYaml` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::GlobalValueSummaryYaml { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">llvm/IR/ModuleSummaryIndexYAML.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71ce14719eb5c9f441e4fc1a001e0aa">Linkage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64bdb29f384891db3498d06d6b7eec9f">Visibility</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d8af8f642d2cdb94686e687d5e1047">NotEligibleToImport</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6d4894339a93f90fcefea2059d268c">Live</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cbdd1728e7e151c65cdb2288cefef50">IsLocal</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9c77eb6de642f596b0cc7143c05a7db">CanAutoHide</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e2f46bd052c42845da95574f78d87b">ImportType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479b9a866a6f2f7aca334b96957413b7">Aliasee</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31882f875f3ff90ff55fdb2b1f98002e">Refs</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a955f1fb97047a22c912e88783b6c03bc">TypeTests</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab617343113f6b5bfa120eab86a229195">TypeTestAssumeVCalls</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a3383bcf8a3a114147403001c1b2b00">TypeCheckedLoadVCalls</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0630a33ac5ad82a661df6912a38b5e65">TypeTestAssumeConstVCalls</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70f5ab7d8a468ff3ba6078f8385e1eb5">TypeCheckedLoadConstVCalls</a> = {}</td>
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


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Aliasee {#a479b9a866a6f2f7aca334b96957413b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::yaml::GlobalValueSummaryYaml::Aliasee</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### CanAutoHide {#ad9c77eb6de642f596b0cc7143c05a7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::GlobalValueSummaryYaml::CanAutoHide</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### ImportType {#a43e2f46bd052c42845da95574f78d87b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::GlobalValueSummaryYaml::ImportType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### IsLocal {#a9cbdd1728e7e151c65cdb2288cefef50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::GlobalValueSummaryYaml::IsLocal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### Linkage {#ac71ce14719eb5c9f441e4fc1a001e0aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::GlobalValueSummaryYaml::Linkage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### Live {#acc6d4894339a93f90fcefea2059d268c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::GlobalValueSummaryYaml::Live</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### NotEligibleToImport {#a16d8af8f642d2cdb94686e687d5e1047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::GlobalValueSummaryYaml::NotEligibleToImport</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### Refs {#a31882f875f3ff90ff55fdb2b1f98002e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; llvm::yaml::GlobalValueSummaryYaml::Refs = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### TypeCheckedLoadConstVCalls {#a70f5ab7d8a468ff3ba6078f8385e1eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionSummary::ConstVCall&gt; llvm::yaml::GlobalValueSummaryYaml::TypeCheckedLoadConstVCalls = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### TypeCheckedLoadVCalls {#a2a3383bcf8a3a114147403001c1b2b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionSummary::VFuncId&gt; llvm::yaml::GlobalValueSummaryYaml::TypeCheckedLoadVCalls = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### TypeTestAssumeConstVCalls {#a0630a33ac5ad82a661df6912a38b5e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionSummary::ConstVCall&gt; llvm::yaml::GlobalValueSummaryYaml::TypeTestAssumeConstVCalls = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### TypeTestAssumeVCalls {#ab617343113f6b5bfa120eab86a229195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionSummary::VFuncId&gt; llvm::yaml::GlobalValueSummaryYaml::TypeTestAssumeVCalls = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### TypeTests {#a955f1fb97047a22c912e88783b6c03bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; llvm::yaml::GlobalValueSummaryYaml::TypeTests = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

### Visibility {#a64bdb29f384891db3498d06d6b7eec9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::GlobalValueSummaryYaml::Visibility</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindexyaml-h">ModuleSummaryIndexYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
