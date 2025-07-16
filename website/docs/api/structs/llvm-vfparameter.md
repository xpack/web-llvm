---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vfparameter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VFParameter` Struct Reference

<p>Encapsulates information needed to describe a parameter. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VFParameter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">llvm/IR/VFABIDemangler.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7830a41f82d37336f5fe8d9d76638745">operator==</a> (const VFParameter &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a967df74e8d0246a66ca1a27ba50daa8a">ParamPos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39">VFParamKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c8f86edc9db58476d6b16903cd403ac">ParamKind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f4f41d21dba4ac5064e0b93224a4bf">LinearStepOrPos</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f0b487dcd5db6130afd9ad8c46c091">Alignment</a> = <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>()</td>
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

<p>Encapsulates information needed to describe a parameter.</p>


<p>The description of the parameter is not linked directly to OpenMP or any other vector function description. This structure is extendible to handle other paradigms that describe vector functions and their parameters.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#a7830a41f82d37336f5fe8d9d76638745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VFParameter::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/vfparameter">VFParameter</a> &amp; Other)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>References <a href="#a94f0b487dcd5db6130afd9ad8c46c091">Alignment</a>, <a href="#a55f4f41d21dba4ac5064e0b93224a4bf">LinearStepOrPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a8c8f86edc9db58476d6b16903cd403ac">ParamKind</a> and <a href="#a967df74e8d0246a66ca1a27ba50daa8a">ParamPos</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Alignment {#a94f0b487dcd5db6130afd9ad8c46c091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::VFParameter::Alignment = <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Referenced by <a href="#a7830a41f82d37336f5fe8d9d76638745">operator==</a>.</p>

</div>
</div>

### LinearStepOrPos {#a55f4f41d21dba4ac5064e0b93224a4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::VFParameter::LinearStepOrPos = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Referenced by <a href="#a7830a41f82d37336f5fe8d9d76638745">operator==</a>.</p>

</div>
</div>

### ParamKind {#a8c8f86edc9db58476d6b16903cd403ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VFParamKind llvm::VFParameter::ParamKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Referenced by <a href="#a7830a41f82d37336f5fe8d9d76638745">operator==</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>.</p>

</div>
</div>

### ParamPos {#a967df74e8d0246a66ca1a27ba50daa8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VFParameter::ParamPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Referenced by <a href="#a7830a41f82d37336f5fe8d9d76638745">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
