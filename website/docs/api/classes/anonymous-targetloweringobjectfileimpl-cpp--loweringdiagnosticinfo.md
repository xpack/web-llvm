---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-targetloweringobjectfileimpl-cpp-/loweringdiagnosticinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoweringDiagnosticInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{TargetLoweringObjectFileImpl.cpp}::LoweringDiagnosticInfo { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24560fc01788f8a4cdf330812fe27b84">LoweringDiagnosticInfo</a> (const Twine &amp;DiagMsg, DiagnosticSeverity Severity=DS_Error)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392fb0b804fbc08728a357c3ee89c341">print</a> (DiagnosticPrinter &amp;DP) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print using the given <span class="doxyComputerOutput">DP</span> a user-friendly message. <a href="#a392fb0b804fbc08728a357c3ee89c341">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677d71e493260b951aca1480f1edff1d">Msg</a></td>
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


<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoweringDiagnosticInfo() {#a24560fc01788f8a4cdf330812fe27b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{TargetLoweringObjectFileImpl.cpp}::LoweringDiagnosticInfo::LoweringDiagnosticInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; DiagMsg, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5c">DiagnosticSeverity</a> Severity=DS_Error)</td>
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



<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a76b8cea6950959f7799660a3a7d1caa5">llvm::DiagnosticInfo::DiagnosticInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a91c4cbc2dd5c5fc64aeda5851e2248d2">llvm::DK_Lowering</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5caa73815097c71f15fe54ab447a7ff00ba">llvm::DS_Error</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### print() {#a392fb0b804fbc08728a357c3ee89c341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{TargetLoweringObjectFileImpl.cpp}::LoweringDiagnosticInfo::print (<a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter">DiagnosticPrinter</a> &amp; DP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print using the given <span class="doxyComputerOutput">DP</span> a user-friendly message.</p>


<p>This is the default message that will be printed to the user. It is used when the frontend does not directly take advantage of the information contained in fields of the subclasses. The printed message must not end with '.' nor start with a severity keyword.</p>


<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Msg {#a677d71e493260b951aca1480f1edff1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Twine&amp; anonymous{TargetLoweringObjectFileImpl.cpp}::LoweringDiagnosticInfo::Msg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
