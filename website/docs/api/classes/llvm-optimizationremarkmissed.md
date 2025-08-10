---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/optimizationremarkmissed
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OptimizationRemarkMissed` Class

<p>Diagnostic information for missed-optimization remarks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::OptimizationRemarkMissed { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95945fd7efc21c965b5bce7cb8a5685c">OptimizationRemarkMissed</a> (const char *PassName, StringRef RemarkName, const DiagnosticLocation &amp;Loc, const Value *CodeRegion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic. <a href="#a95945fd7efc21c965b5bce7cb8a5685c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23879092a3f056766816230baa431981">OptimizationRemarkMissed</a> (const char *PassName, StringRef RemarkName, const Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as above but <span class="doxyComputerOutput">Inst</span> is used to derive code region and debug location. <a href="#a23879092a3f056766816230baa431981">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e5af98c78a206608155e558697d011">OptimizationRemarkMissed</a> (const char *PassName, StringRef RemarkName, const Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as above but <span class="doxyComputerOutput">F</span> is used to derive code region and debug location. <a href="#a06e5af98c78a206608155e558697d011">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59ef75e3f0cc1593be8b4acbc9d537b">OptimizationRemarkMissed</a> (const char *PassName, const Function &amp;Fn, const DiagnosticLocation &amp;Loc, const Twine &amp;Msg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is deprecated now and only used by the function API below. <a href="#af59ef75e3f0cc1593be8b4acbc9d537b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafff42ca513f5f2e742201442cb299ef">isEnabled</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9cc0f46c85213e36675582b4aec4ce">classof</a> (const DiagnosticInfo *DI)</td>
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

<p>Diagnostic information for missed-optimization remarks.</p>

<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OptimizationRemarkMissed() {#a95945fd7efc21c965b5bce7cb8a5685c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkMissed::OptimizationRemarkMissed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CodeRegion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic.</p>


<p>If this name matches the regular expression given in -Rpass-missed=, then the diagnostic will be emitted. <span class="doxyComputerOutput">RemarkName</span> is a textual identifier for the remark (single-word, camel-case). <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the debug location and <span class="doxyComputerOutput">CodeRegion</span> is the region that the optimization operates on (currently only block is supported).</p>


<p>Declaration at line 815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a60172d67189a80dd366981444c7e6fe9">llvm::DK_OptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>

</div>
</div>

### OptimizationRemarkMissed() {#a23879092a3f056766816230baa431981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkMissed::OptimizationRemarkMissed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as above but <span class="doxyComputerOutput">Inst</span> is used to derive code region and debug location.</p>

<p>Declaration at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a60172d67189a80dd366981444c7e6fe9">llvm::DK_OptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstrbundle-cpp/#af44c9b089359803924e0b92bea3b6d03">getDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>

</div>
</div>

### OptimizationRemarkMissed() {#a06e5af98c78a206608155e558697d011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkMissed::OptimizationRemarkMissed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as above but <span class="doxyComputerOutput">F</span> is used to derive code region and debug location.</p>

<p>Declaration at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a94b851bbca9f77b7fed2a087827a9408">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a60172d67189a80dd366981444c7e6fe9">llvm::DK_OptimizationRemarkMissed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp/#a5d8f62cfa2011e0d61f677f2baf45f8d">getFirstFunctionBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a859931f9f18bb9556861a9568be49d1e">getSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### OptimizationRemarkMissed() {#af59ef75e3f0cc1593be8b4acbc9d537b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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


<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic. If this name matches the regular expression given in -Rpass-missed=, then the diagnostic will be emitted. <span class="doxyComputerOutput">Fn</span> is the function where the diagnostic is being emitted. <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the location information to use in the diagnostic. If line table information is available, the diagnostic will include the source code location. <span class="doxyComputerOutput">Msg</span> is the message to show. Note that this class does not copy this message, so this reference must be valid for the whole life time of the diagnostic.</p>


<p>Definition at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isEnabled() {#aafff42ca513f5f2e742201442cb299ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OptimizationRemarkMissed::isEnabled ()</td>
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


<p>Declaration at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#ae41647cc74ff350acbad9b809ec7da0b">llvm::LLVMContext::getDiagHandlerPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfowithlocationbase/#a6110498f7c9d287585d8fe1d51999c64">llvm::DiagnosticInfoWithLocationBase::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a51e48dc15ff1e5851f1ac88b2f959ff3">llvm::DiagnosticInfoOptimizationBase::getPassName</a> and <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#aa7f8497579cb50322178c9b6e1daacaa">llvm::DiagnosticHandler::isMissedOptRemarkEnabled</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aac9cc0f46c85213e36675582b4aec4ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationRemarkMissed::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> * DI)</td>
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



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a60172d67189a80dd366981444c7e6fe9">llvm::DK_OptimizationRemarkMissed</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

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
