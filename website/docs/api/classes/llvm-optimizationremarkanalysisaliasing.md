---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/optimizationremarkanalysisaliasing
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OptimizationRemarkAnalysisAliasing` Class

<p>Diagnostic information for optimization analysis remarks related to pointer aliasing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::OptimizationRemarkAnalysisAliasing { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316fb21374c6a171a407d9d5d64e37be">OptimizationRemarkAnalysisAliasing</a> (const char *PassName, StringRef RemarkName, const DiagnosticLocation &amp;Loc, const Value *CodeRegion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic. <a href="#a316fb21374c6a171a407d9d5d64e37be">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac00a89f94e316966e5a13fbe4708f5c0">OptimizationRemarkAnalysisAliasing</a> (const char *PassName, const Function &amp;Fn, const DiagnosticLocation &amp;Loc, const Twine &amp;Msg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is deprecated now and only used by the function API below. <a href="#ac00a89f94e316966e5a13fbe4708f5c0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e897ee9a15f3738826383b62e404ac">anchor</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2338406255a9c20b814ba6b5fab689d">classof</a> (const DiagnosticInfo *DI)</td>
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

<p>Diagnostic information for optimization analysis remarks related to pointer aliasing.</p>

<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OptimizationRemarkAnalysisAliasing() {#a316fb21374c6a171a407d9d5d64e37be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationRemarkAnalysisAliasing::OptimizationRemarkAnalysisAliasing (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CodeRegion)</td>
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


<p>If this name matches the regular expression given in -Rpass-analysis=, then the diagnostic will be emitted. <span class="doxyComputerOutput">RemarkName</span> is a textual identifier for the remark (single-word, camel-case). <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the debug location and <span class="doxyComputerOutput">CodeRegion</span> is the region that the optimization operates on (currently only block is supported). The front-end will append its own message related to options that address pointer aliasing legality.</p>


<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a330a17a4ee40b2e3030ee04bbd2d35b2">llvm::DK_OptimizationRemarkAnalysisAliasing</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#ab4fa4fd4a389f0d81f5f413d21b2c4c4">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a3b9b11107e5d9c73301e16d839f6c7d7">llvm::DiagnosticInfoOptimizationBase::PassName</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a54f8e0c579b9530254084bbb00a0e727">llvm::DiagnosticInfoOptimizationBase::RemarkName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### OptimizationRemarkAnalysisAliasing() {#ac00a89f94e316966e5a13fbe4708f5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationRemarkAnalysisAliasing::OptimizationRemarkAnalysisAliasing (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * PassName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
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


<p><span class="doxyComputerOutput">PassName</span> is the name of the pass emitting this diagnostic. If this name matches the regular expression given in -Rpass-analysis=, then the diagnostic will be emitted. <span class="doxyComputerOutput">Fn</span> is the function where the diagnostic is being emitted. <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the location information to use in the diagnostic. If line table information is available, the diagnostic will include the source code location. <span class="doxyComputerOutput">Msg</span> is the message to show. The front-end will append its own message related to options that address pointer aliasing legality. Note that this class does not copy this message, so this reference must be valid for the whole life time of the diagnostic.</p>


<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a77e897ee9a15f3738826383b62e404ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OptimizationRemarkAnalysisAliasing::anchor ()</td>
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



<p>Declaration at line 969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#af2338406255a9c20b814ba6b5fab689d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationRemarkAnalysisAliasing::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> * DI)</td>
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



<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a330a17a4ee40b2e3030ee04bbd2d35b2">llvm::DK_OptimizationRemarkAnalysisAliasing</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

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
