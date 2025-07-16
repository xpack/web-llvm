---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/optimizationremarkanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OptimizationRemarkAnalysis` Class Reference

<p>Diagnostic information for optimization analysis remarks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::OptimizationRemarkAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization">DiagnosticInfoIROptimization</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common features for diagnostics dealing with optimization remarks that are used by IR passes. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisaliasing">OptimizationRemarkAnalysisAliasing</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for optimization analysis remarks related to pointer aliasing. <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisaliasing/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisfpcommute">OptimizationRemarkAnalysisFPCommute</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for optimization analysis remarks related to floating-point non-commutativity. <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisfpcommute/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4fa4fd4a389f0d81f5f413d21b2c4c4">OptimizationRemarkAnalysis</a> (const char *PassName, StringRef RemarkName, const DiagnosticLocation &amp;Loc, const Value *CodeRegion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic. <a href="#ab4fa4fd4a389f0d81f5f413d21b2c4c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48bdcbaf3e1f8e4e09c3507ce7d0afd6">OptimizationRemarkAnalysis</a> (const char *PassName, StringRef Prepend, const OptimizationRemarkAnalysis &amp;Orig)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is ctor variant allows a pass to build an optimization remark from an existing remark. <a href="#a48bdcbaf3e1f8e4e09c3507ce7d0afd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d0a9378ede1f0821eb273c8e797df06">OptimizationRemarkAnalysis</a> (const char *PassName, StringRef RemarkName, const Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as above but <span class="doxyComputerOutput">Inst</span> is used to derive code region and debug location. <a href="#a7d0a9378ede1f0821eb273c8e797df06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a799ad8c42497bd62234ffd72ca97f3">OptimizationRemarkAnalysis</a> (const char *PassName, StringRef RemarkName, const Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as above but <span class="doxyComputerOutput">F</span> is used to derive code region and debug location. <a href="#a1a799ad8c42497bd62234ffd72ca97f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917b13e15387aa72cbd54f48929bcedb">OptimizationRemarkAnalysis</a> (enum DiagnosticKind Kind, const char *PassName, const Function &amp;Fn, const DiagnosticLocation &amp;Loc, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3c742fcad66bf2ca0afe6d1b58b6c8b">OptimizationRemarkAnalysis</a> (enum DiagnosticKind Kind, const char *PassName, StringRef RemarkName, const DiagnosticLocation &amp;Loc, const Value *CodeRegion)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2660f622d95de1b020358761ad6ede4f">OptimizationRemarkAnalysis</a> (const char *PassName, const Function &amp;Fn, const DiagnosticLocation &amp;Loc, const Twine &amp;Msg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is deprecated now and only used by the function API below. <a href="#a2660f622d95de1b020358761ad6ede4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1ed99116e727b8a7af8cf48889e7b6">isEnabled</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa6a70f38583335812228b905db94bb7">shouldAlwaysPrint</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee3821d74ed7dd644c0bfc518728a6f6">classof</a> (const DiagnosticInfo *DI)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17011a05879d3698f829ff869dc9a88">AlwaysPrint</a> = ""</td>
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

<p>Diagnostic information for optimization analysis remarks.</p>

<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OptimizationRemarkAnalysis() {#ab4fa4fd4a389f0d81f5f413d21b2c4c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkAnalysis::OptimizationRemarkAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CodeRegion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic.</p>


<p>If this name matches the regular expression given in -Rpass-analysis=, then the diagnostic will be emitted. <span class="doxyComputerOutput">RemarkName</span> is a textual identifier for the remark (single-word, camel-case). <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the debug location and <span class="doxyComputerOutput">CodeRegion</span> is the region that the optimization operates on (currently only block is supported).</p>


<p>Declaration at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a27ed101669b84c58dbf9363fe96bdf64">llvm::DK_OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>


<p>Referenced by <a href="#a48bdcbaf3e1f8e4e09c3507ce7d0afd6">OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisaliasing/#a316fb21374c6a171a407d9d5d64e37be">llvm::OptimizationRemarkAnalysisAliasing::OptimizationRemarkAnalysisAliasing</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysisfpcommute/#a8314f3ba49d1ebaea8d778518d4320c5">llvm::OptimizationRemarkAnalysisFPCommute::OptimizationRemarkAnalysisFPCommute</a>.</p>

</div>
</div>

### OptimizationRemarkAnalysis() {#a48bdcbaf3e1f8e4e09c3507ce7d0afd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prepend, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis">OptimizationRemarkAnalysis</a> &amp; Orig)</td>
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

<p>This is ctor variant allows a pass to build an optimization remark from an existing remark.</p>


<p>This is useful when a transformation pass (e.g LV) wants to emit a remark (<span class="doxyComputerOutput">Orig</span>) generated by one of its analyses (e.g. LAA) as its own analysis remark. The string <span class="doxyComputerOutput">Prepend</span> will be emitted before the original message.</p>


<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="#ab4fa4fd4a389f0d81f5f413d21b2c4c4">OptimizationRemarkAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a>.</p>

</div>
</div>

### OptimizationRemarkAnalysis() {#a7d0a9378ede1f0821eb273c8e797df06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkAnalysis::OptimizationRemarkAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as above but <span class="doxyComputerOutput">Inst</span> is used to derive code region and debug location.</p>

<p>Declaration at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a27ed101669b84c58dbf9363fe96bdf64">llvm::DK_OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstrbundle-cpp/#af44c9b089359803924e0b92bea3b6d03">getDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>

</div>
</div>

### OptimizationRemarkAnalysis() {#a1a799ad8c42497bd62234ffd72ca97f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkAnalysis::OptimizationRemarkAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as above but <span class="doxyComputerOutput">F</span> is used to derive code region and debug location.</p>

<p>Declaration at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a27ed101669b84c58dbf9363fe96bdf64">llvm::DK_OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp/#a5d8f62cfa2011e0d61f677f2baf45f8d">getFirstFunctionBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a859931f9f18bb9556861a9568be49d1e">getSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### OptimizationRemarkAnalysis() {#a917b13e15387aa72cbd54f48929bcedb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis (enum <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a>.</p>

</div>
</div>

### OptimizationRemarkAnalysis() {#ad3c742fcad66bf2ca0afe6d1b58b6c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkAnalysis::OptimizationRemarkAnalysis (enum <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CodeRegion)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### OptimizationRemarkAnalysis() {#a2660f622d95de1b020358761ad6ede4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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

<p>This is deprecated now and only used by the function API below.</p>


<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic. If this name matches the regular expression given in -Rpass-analysis=, then the diagnostic will be emitted. <span class="doxyComputerOutput">Fn</span> is the function where the diagnostic is being emitted. <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the location information to use in the diagnostic. If line table information is available, the diagnostic will include the source code location. <span class="doxyComputerOutput">Msg</span> is the message to show. Note that this class does not copy this message, so this reference must be valid for the whole life time of the diagnostic.</p>


<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isEnabled() {#a0f1ed99116e727b8a7af8cf48889e7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OptimizationRemarkAnalysis::isEnabled ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#ae68c6c41365eb4602d037a38616cf33f">DiagnosticInfoOptimizationBase::isEnabled</a>.</p></dd>
</dl>


<p>Declaration at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#ae41647cc74ff350acbad9b809ec7da0b">llvm::LLVMContext::getDiagHandlerPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfowithlocationbase/#a6110498f7c9d287585d8fe1d51999c64">llvm::DiagnosticInfoWithLocationBase::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a51e48dc15ff1e5851f1ac88b2f959ff3">llvm::DiagnosticInfoOptimizationBase::getPassName</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#a9491283253671daad4d7d6cebbba3df2">llvm::DiagnosticHandler::isAnalysisRemarkEnabled</a> and <a href="#aaa6a70f38583335812228b905db94bb7">shouldAlwaysPrint</a>.</p>

</div>
</div>

### shouldAlwaysPrint() {#aaa6a70f38583335812228b905db94bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationRemarkAnalysis::shouldAlwaysPrint ()</td>
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



<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="#aa17011a05879d3698f829ff869dc9a88">AlwaysPrint</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a51e48dc15ff1e5851f1ac88b2f959ff3">llvm::DiagnosticInfoOptimizationBase::getPassName</a>.</p>


<p>Referenced by <a href="#a0f1ed99116e727b8a7af8cf48889e7b6">isEnabled</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aee3821d74ed7dd644c0bfc518728a6f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationRemarkAnalysis::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> * DI)</td>
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



<p>Definition at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a27ed101669b84c58dbf9363fe96bdf64">llvm::DK_OptimizationRemarkAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### AlwaysPrint {#aa17011a05879d3698f829ff869dc9a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * OptimizationRemarkAnalysis::AlwaysPrint = ""</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a7e1e58ca451be96cbbff94a01658c988">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::fail</a>, <a href="#aaa6a70f38583335812228b905db94bb7">shouldAlwaysPrint</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#abcf8c2b35316773f1ab0ba70aeb2a6de">llvm::LoopVectorizeHints::vectorizeAnalysisPassName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
