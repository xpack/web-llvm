---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/passbuilder/pipelineelement
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PipelineElement` Struct Reference

<p>A struct to capture parsed pass pipeline names. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::PassBuilder::PipelineElement { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb1708cb51004835e249145921d1a62">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/passbuilder/pipelineelement">PipelineElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b8e6e043cf4f540f8ee434f361fed8a">InnerPipeline</a></td>
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

<p>A struct to capture parsed pass pipeline names.</p>


<p>A pipeline is defined as a series of names, each of which may in itself recursively contain a nested pipeline. A name is either the name of a pass (e.g. "instcombine") or the name of a pipeline type (e.g. "cgscc"). If the name is the name of a pass, the InnerPipeline is empty, since passes cannot contain inner pipelines. See <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a9ca0e57e6445ab2fe568e53ba29cc0fd">parsePassPipeline()</a> for a more detailed description of the textual pipeline format.</p>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### InnerPipeline {#a4b8e6e043cf4f540f8ee434f361fed8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PipelineElement&gt; llvm::PassBuilder::PipelineElement::InnerPipeline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

### Name {#afeb1708cb51004835e249145921d1a62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PassBuilder::PipelineElement::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">PassBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
