---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diagnosticinfomiroptimization
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DiagnosticInfoMIROptimization` Class

<p>Common features for diagnostics dealing with optimization remarks that are used by machine passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DiagnosticInfoMIROptimization { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">llvm/CodeGen/MachineOptimizationRemarkEmitter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase">DiagnosticInfoOptimizationBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common features for diagnostics dealing with optimization remarks that are used by both IR and MIR passes. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremark">MachineOptimizationRemark</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for applied optimization remarks. <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremark/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis">MachineOptimizationRemarkAnalysis</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for optimization analysis remarks. <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkmissed">MachineOptimizationRemarkMissed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for missed-optimization remarks. <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkmissed/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8ba0921d348dc62437d2fd3ce00061">DiagnosticInfoMIROptimization</a> (enum DiagnosticKind Kind, const char *PassName, StringRef RemarkName, const DiagnosticLocation &amp;Loc, const MachineBasicBlock *MBB)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a82317fc0f135219be046148d75411e">getBlock</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657f8360b04745d945471371adc1b7bb">MBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084632ed540762f5c6f1d79abde726c7">classof</a> (const DiagnosticInfo *DI)</td>
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

<p>Common features for diagnostics dealing with optimization remarks that are used by machine passes.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">MachineOptimizationRemarkEmitter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DiagnosticInfoMIROptimization() {#a4d8ba0921d348dc62437d2fd3ce00061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoMIROptimization::DiagnosticInfoMIROptimization (enum <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">MachineOptimizationRemarkEmitter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#ae3a4821cc4da0f7c13aee43edf840e07">llvm::DiagnosticInfoOptimizationBase::DiagnosticInfoOptimizationBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfowithlocationbase/#a6110498f7c9d287585d8fe1d51999c64">llvm::DiagnosticInfoWithLocationBase::getFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremark/#ac23eab1baee9b460a0288c92e4526af3">llvm::MachineOptimizationRemark::MachineOptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#ae27db372034ab8b6712c9bbb80d299c5">llvm::MachineOptimizationRemarkAnalysis::MachineOptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#a23badf68951303c8ef0664e24f181100">llvm::MachineOptimizationRemarkAnalysis::MachineOptimizationRemarkAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkmissed/#a9c71a8a0dda8332ca7321c7ab5420e9a">llvm::MachineOptimizationRemarkMissed::MachineOptimizationRemarkMissed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBlock() {#a3a82317fc0f135219be046148d75411e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock * llvm::DiagnosticInfoMIROptimization::getBlock ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">MachineOptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MBB {#a657f8360b04745d945471371adc1b7bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::DiagnosticInfoMIROptimization::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">MachineOptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a084632ed540762f5c6f1d79abde726c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoMIROptimization::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> * DI)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">MachineOptimizationRemarkEmitter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a9a0080fe6649135b91c5d3590be8f336">llvm::DK_FirstMachineRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a287b1ee4491e6ca4641731593b76e295">llvm::DK_LastMachineRemark</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">MachineOptimizationRemarkEmitter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
