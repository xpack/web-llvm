---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diagnosticinfoiroptimization
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DiagnosticInfoIROptimization` Class

<p>Common features for diagnostics dealing with optimization remarks that are used by IR passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DiagnosticInfoIROptimization { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationfailure">DiagnosticInfoOptimizationFailure</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for optimization failures. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationfailure/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremark">OptimizationRemark</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for applied optimization remarks. <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis">OptimizationRemarkAnalysis</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for optimization analysis remarks. <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed">OptimizationRemarkMissed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for missed-optimization remarks. <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94b851bbca9f77b7fed2a087827a9408">DiagnosticInfoIROptimization</a> (enum DiagnosticKind Kind, enum DiagnosticSeverity Severity, const char *PassName, StringRef RemarkName, const Function &amp;Fn, const DiagnosticLocation &amp;Loc, const Value *CodeRegion=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic. <a href="#a94b851bbca9f77b7fed2a087827a9408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a301d0e866440a41b832972c897f2dc5c">DiagnosticInfoIROptimization</a> (const char *PassName, StringRef Prepend, const DiagnosticInfoIROptimization &amp;Orig)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is ctor variant allows a pass to build an optimization remark from an existing remark. <a href="#a301d0e866440a41b832972c897f2dc5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa192c95c53dffca890dcffcae58795f0">DiagnosticInfoIROptimization</a> (enum DiagnosticKind Kind, enum DiagnosticSeverity Severity, const char *PassName, const Function &amp;Fn, const DiagnosticLocation &amp;Loc, const Twine &amp;Msg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legacy interface. <a href="#aa192c95c53dffca890dcffcae58795f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00d3946a9c004327b33936ede9618118">getCodeRegion</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b28bba6f443cc0fd8cba791072a808b">anchor</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68fa9b3e4b38d52c318f3e2fc3c512fd">CodeRegion</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The IR value (currently basic block) that the optimization operates on. <a href="#a68fa9b3e4b38d52c318f3e2fc3c512fd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af14b0513d57cd4672ed3a71ed073a543">classof</a> (const DiagnosticInfo *DI)</td>
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

<p>Common features for diagnostics dealing with optimization remarks that are used by IR passes.</p>

<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DiagnosticInfoIROptimization() {#a94b851bbca9f77b7fed2a087827a9408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization (enum <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> Kind, enum <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5c">DiagnosticSeverity</a> Severity, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CodeRegion=nullptr)</td>
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

<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic.</p>


<p><span class="doxyComputerOutput">RemarkName</span> is a textual identifier for the remark (single-word, camel-case). <span class="doxyComputerOutput">Fn</span> is the function where the diagnostic is being emitted. <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the location information to use in the diagnostic. If line table information is available, the diagnostic will include the source code location. <span class="doxyComputerOutput">CodeRegion</span> is IR value (currently basic block) that the optimization operates on. This is currently used to provide run-time hotness information with PGO.</p>


<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#ae3a4821cc4da0f7c13aee43edf840e07">llvm::DiagnosticInfoOptimizationBase::DiagnosticInfoOptimizationBase</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>


<p>Referenced by <a href="#a301d0e866440a41b832972c897f2dc5c">DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationfailure/#a11b5ef0c89ca056e53c24affefe7d3cc">llvm::DiagnosticInfoOptimizationFailure::DiagnosticInfoOptimizationFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationfailure/#a6d8ea12445d709e8958b961e10b8e9b0">llvm::DiagnosticInfoOptimizationFailure::DiagnosticInfoOptimizationFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a940829469e382e9dea15a5c8645a8387">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a3891f0f63dbc838b810554621a2b621d">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a2ad3eae0e100b9e6eca74ee28144ba1d">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a48bdcbaf3e1f8e4e09c3507ce7d0afd6">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#ab4fa4fd4a389f0d81f5f413d21b2c4c4">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a1a799ad8c42497bd62234ffd72ca97f3">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a7d0a9378ede1f0821eb273c8e797df06">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a917b13e15387aa72cbd54f48929bcedb">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#ad3c742fcad66bf2ca0afe6d1b58b6c8b">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a95945fd7efc21c965b5bce7cb8a5685c">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a06e5af98c78a206608155e558697d011">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a23879092a3f056766816230baa431981">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a>.</p>

</div>
</div>

### DiagnosticInfoIROptimization() {#a301d0e866440a41b832972c897f2dc5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prepend, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization">DiagnosticInfoIROptimization</a> &amp; Orig)</td>
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


<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#ab3ae6473bab457dfb88ec9210629760e">llvm::DiagnosticInfoOptimizationBase::Args</a>, <a href="#a94b851bbca9f77b7fed2a087827a9408">DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#ae3a4821cc4da0f7c13aee43edf840e07">llvm::DiagnosticInfoOptimizationBase::DiagnosticInfoOptimizationBase</a>, <a href="#a00d3946a9c004327b33936ede9618118">getCodeRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfowithlocationbase/#a6110498f7c9d287585d8fe1d51999c64">llvm::DiagnosticInfoWithLocationBase::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfowithlocationbase/#ad21d4d693a4adddaf2bf7ba9f94402a2">llvm::DiagnosticInfoWithLocationBase::getLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a442499cb808b8d5b55eec9087eaf3f3f">llvm::DiagnosticInfo::getSeverity</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>

</div>
</div>

### DiagnosticInfoIROptimization() {#aa192c95c53dffca890dcffcae58795f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization (enum <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> Kind, enum <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5c">DiagnosticSeverity</a> Severity, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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

<p>Legacy interface.</p>


<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic. <span class="doxyComputerOutput">Fn</span> is the function where the diagnostic is being emitted. <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the location information to use in the diagnostic. If line table information is available, the diagnostic will include the source code location. <span class="doxyComputerOutput">Msg</span> is the message to show. Note that this class does not copy this message, so this reference must be valid for the whole life time of the diagnostic.</p>


<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#ae3a4821cc4da0f7c13aee43edf840e07">llvm::DiagnosticInfoOptimizationBase::DiagnosticInfoOptimizationBase</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCodeRegion() {#a00d3946a9c004327b33936ede9618118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::DiagnosticInfoIROptimization::getCodeRegion ()</td>
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



<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="#a301d0e866440a41b832972c897f2dc5c">DiagnosticInfoIROptimization</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a2b28bba6f443cc0fd8cba791072a808b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagnosticInfoIROptimization::anchor ()</td>
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



<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CodeRegion {#a68fa9b3e4b38d52c318f3e2fc3c512fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* llvm::DiagnosticInfoIROptimization::CodeRegion = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The IR value (currently basic block) that the optimization operates on.</p>


<p>This is currently used to provide run-time hotness information with PGO.</p>


<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#af14b0513d57cd4672ed3a71ed073a543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoIROptimization::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> * DI)</td>
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



<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594ad21f1ad0ee8344122ab612c3a84c4ab8">llvm::DK_FirstRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a593e413dd08602726f04e60e38539035">llvm::DK_LastRemark</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
