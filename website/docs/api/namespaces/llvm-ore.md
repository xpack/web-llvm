---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/ore
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `ore` Namespace Reference

<p>Add a small namespace to avoid name clashes with the classes used in the streaming interface. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::ore { ... }
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ca06dfbc998afac005414d8e9b7c234">NV</a> = <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument">DiagnosticInfoOptimizationBase::Argument</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72cb73bfe4871811e430a53bdf1234ed">setIsVerbose</a> = <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/setisverbose">DiagnosticInfoOptimizationBase::setIsVerbose</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d0744ef97ceb024c603e0e5a1c3533e">setExtraArgs</a> = <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/setextraargs">DiagnosticInfoOptimizationBase::setExtraArgs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70cfc1b4acc7116371c94b360dfb2dac">MNV</a> = <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfomiroptimization/machineargument">DiagnosticInfoMIROptimization::MachineArgument</a></td>
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

<p>Add a small namespace to avoid name clashes with the classes used in the streaming interface.</p>


<p>Extend <a href="/web-llvm/docs/api/namespaces/llvm/ore">llvm::ore</a>:: with MI-specific helper names.</p>


<p>We want these to be short for better write/readability.</p>


<div class="doxySectionDef">

## Typedefs

### MNV {#a70cfc1b4acc7116371c94b360dfb2dac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ore::MNV =  DiagnosticInfoMIROptimization::MachineArgument</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">MachineOptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

### NV {#a5ca06dfbc998afac005414d8e9b7c234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ore::NV =  DiagnosticInfoOptimizationBase::Argument</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

### setExtraArgs {#a9d0744ef97ceb024c603e0e5a1c3533e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ore::setExtraArgs =  DiagnosticInfoOptimizationBase::setExtraArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

### setIsVerbose {#a72cb73bfe4871811e430a53bdf1234ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ore::setIsVerbose =  DiagnosticInfoOptimizationBase::setIsVerbose</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">MachineOptimizationRemarkEmitter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
