---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diagnosticinfowithlocationbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DiagnosticInfoWithLocationBase` Class

<p>Common features for diagnostics with an associated location. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DiagnosticInfoWithLocationBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the base abstract class for diagnostic reporting in the backend. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfogenericwithloc">DiagnosticInfoGenericWithLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomisexpect">DiagnosticInfoMisExpect</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for MisExpect analysis. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomisexpect/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinforegallocfailure">DiagnosticInfoRegAllocFailure</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinforesourcelimit">DiagnosticInfoResourceLimit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for stack size etc. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforesourcelimit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticinfounsupported">DiagnosticInfoUnsupported</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Diagnostic information for unsupported feature in backend. <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfounsupported/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca991454271008ccddc187789d107d34">DiagnosticInfoWithLocationBase</a> (enum DiagnosticKind Kind, enum DiagnosticSeverity Severity, const Function &amp;Fn, const DiagnosticLocation &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Fn</span> is the function where the diagnostic is being emitted. <a href="#aca991454271008ccddc187789d107d34">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f57e00a00cc775d475ab2379a235340">isLocationAvailable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if location information is available for this diagnostic. <a href="#a2f57e00a00cc775d475ab2379a235340">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f8e30e4b79049f59395eb471b4ddcf4">getLocationStr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a string with the location information for this diagnostic in the format "file:line:col". <a href="#a1f8e30e4b79049f59395eb471b4ddcf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad21d4d693a4adddaf2bf7ba9f94402a2">getLocation</a> (StringRef &amp;RelativePath, unsigned &amp;Line, unsigned &amp;Column) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return location information for this diagnostic in three parts: the relative source file path, line number and column. <a href="#ad21d4d693a4adddaf2bf7ba9f94402a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b9e5f6f3d61864b963d98d3ad9539e">getAbsolutePath</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the absolute path tot the file. <a href="#a29b9e5f6f3d61864b963d98d3ad9539e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6110498f7c9d287585d8fe1d51999c64">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628401653ef2b454704309c444fc84de">getLocation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f75b022565b3e91e71ca01b3f2a0218">anchor</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd5f0e470e0c46841498790a8ce9aaa">Fn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> where this diagnostic is triggered. <a href="#a0fd5f0e470e0c46841498790a8ce9aaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7219e8c28200f871cc28ea9c319b78">Loc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug location where this diagnostic is triggered. <a href="#a6a7219e8c28200f871cc28ea9c319b78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Common features for diagnostics with an associated location.</p>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DiagnosticInfoWithLocationBase() {#aca991454271008ccddc187789d107d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoWithLocationBase::DiagnosticInfoWithLocationBase (enum <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a> Kind, enum <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5c">DiagnosticSeverity</a> Severity, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticlocation">DiagnosticLocation</a> &amp; Loc)</td>
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

<p><span class="doxyComputerOutput">Fn</span> is the function where the diagnostic is being emitted.</p>


<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span> is the location information to use in the diagnostic.</p>


<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a76b8cea6950959f7799660a3a7d1caa5">llvm::DiagnosticInfo::DiagnosticInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfogenericwithloc/#adb0e8785e40b71eddad9534c26e1c80e">llvm::DiagnosticInfoGenericWithLoc::DiagnosticInfoGenericWithLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomisexpect/#abdd6bad61c38d00ca2dceda536cd15f9">llvm::DiagnosticInfoMisExpect::DiagnosticInfoMisExpect</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#ae3a4821cc4da0f7c13aee43edf840e07">llvm::DiagnosticInfoOptimizationBase::DiagnosticInfoOptimizationBase</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforegallocfailure/#a65894464e2ca592db70001e29ac4f1b0">llvm::DiagnosticInfoRegAllocFailure::DiagnosticInfoRegAllocFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforegallocfailure/#afcf067b152ba85f0862dd7473495d4d1">llvm::DiagnosticInfoRegAllocFailure::DiagnosticInfoRegAllocFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforesourcelimit/#af3dd4de995a10037f970994df29a3b76">llvm::DiagnosticInfoResourceLimit::DiagnosticInfoResourceLimit</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfounsupported/#ab82f478e5b0e08fa976b37c5aaa3c554">llvm::DiagnosticInfoUnsupported::DiagnosticInfoUnsupported</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAbsolutePath() {#a29b9e5f6f3d61864b963d98d3ad9539e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string DiagnosticInfoWithLocationBase::getAbsolutePath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the absolute path tot the file.</p>

<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>

</div>
</div>

### getFunction() {#a6110498f7c9d287585d8fe1d51999c64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function &amp; llvm::DiagnosticInfoWithLocationBase::getFunction ()</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a301d0e866440a41b832972c897f2dc5c">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomiroptimization/#a4d8ba0921d348dc62437d2fd3ce00061">llvm::DiagnosticInfoMIROptimization::DiagnosticInfoMIROptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremark/#a39d9cdb595768f3e86c3f86f4ba33c00">llvm::MachineOptimizationRemark::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#a21c55fb64c1decb01f6dfe60ba7b6c1d">llvm::MachineOptimizationRemarkAnalysis::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkmissed/#a22479d91f2c90bb3032810dfa2864527">llvm::MachineOptimizationRemarkMissed::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a551a7d26da872a1e686a9d0d4a72d49b">llvm::OptimizationRemark::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a0f1ed99116e727b8a7af8cf48889e7b6">llvm::OptimizationRemarkAnalysis::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#aafff42ca513f5f2e742201442cb299ef">llvm::OptimizationRemarkMissed::isEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforegallocfailure/#a8697e07f38b6ce60ebb0492efb8ddba9">llvm::DiagnosticInfoRegAllocFailure::print</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfounsupported/#a12864403c3efdae1dac8ca322dedf9ba">llvm::DiagnosticInfoUnsupported::print</a>.</p>

</div>
</div>

### getLocation() {#ad21d4d693a4adddaf2bf7ba9f94402a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagnosticInfoWithLocationBase::getLocation (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; RelativePath, unsigned &amp; Line, unsigned &amp; Column)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return location information for this diagnostic in three parts: the relative source file path, line number and column.</p>

<p>Declaration at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization/#a301d0e866440a41b832972c897f2dc5c">llvm::DiagnosticInfoIROptimization::DiagnosticInfoIROptimization</a>.</p>

</div>
</div>

### getLocation() {#a628401653ef2b454704309c444fc84de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticLocation llvm::DiagnosticInfoWithLocationBase::getLocation ()</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="#a1f8e30e4b79049f59395eb471b4ddcf4">getLocationStr</a>.</p>

</div>
</div>

### getLocationStr() {#a1f8e30e4b79049f59395eb471b4ddcf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string DiagnosticInfoWithLocationBase::getLocationStr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a string with the location information for this diagnostic in the format "file:line:col".</p>


<p>If location information is not available, it returns "&lt;unknown&gt;:0:0".</p>


<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>


<p>References <a href="#a628401653ef2b454704309c444fc84de">getLocation</a> and <a href="#a2f57e00a00cc775d475ab2379a235340">isLocationAvailable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfogenericwithloc/#a52692f9e6675a6a2679a1b89aa3dc3f7">llvm::DiagnosticInfoGenericWithLoc::print</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfomisexpect/#a95f7403f5fd2fbe7130d4fe99aca077d">llvm::DiagnosticInfoMisExpect::print</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#a6ad2c89e20662a91116db4c738b4f1fe">llvm::DiagnosticInfoOptimizationBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforegallocfailure/#a8697e07f38b6ce60ebb0492efb8ddba9">llvm::DiagnosticInfoRegAllocFailure::print</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforesourcelimit/#a22cfc8a1cda1e0b86deb2750c0819d00">llvm::DiagnosticInfoResourceLimit::print</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfounsupported/#a12864403c3efdae1dac8ca322dedf9ba">llvm::DiagnosticInfoUnsupported::print</a>.</p>

</div>
</div>

### isLocationAvailable() {#a2f57e00a00cc775d475ab2379a235340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoWithLocationBase::isLocationAvailable ()</td>
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

<p>Return true if location information is available for this diagnostic.</p>

<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>Referenced by <a href="#a1f8e30e4b79049f59395eb471b4ddcf4">getLocationStr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a7f75b022565b3e91e71ca01b3f2a0218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagnosticInfoWithLocationBase::anchor ()</td>
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



<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Fn {#a0fd5f0e470e0c46841498790a8ce9aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function&amp; llvm::DiagnosticInfoWithLocationBase::Fn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> where this diagnostic is triggered.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>

</div>
</div>

### Loc {#a6a7219e8c28200f871cc28ea9c319b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticLocation llvm::DiagnosticInfoWithLocationBase::Loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug location where this diagnostic is triggered.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>

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
