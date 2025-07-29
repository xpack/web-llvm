---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diagnosticinfoinstrumentation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DiagnosticInfoInstrumentation` Class

<p>Diagnostic information for IR instrumentation reporting. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DiagnosticInfoInstrumentation { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0702308df4e060d6b19e770b7fb610">DiagnosticInfoInstrumentation</a> (const Twine &amp;DiagMsg, DiagnosticSeverity Severity=DS_Warning)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6e4f68e6123d6831ad5e59f11ba365">print</a> (DiagnosticPrinter &amp;DP) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print using the given <span class="doxyComputerOutput">DP</span> a user-friendly message. <a href="#aae6e4f68e6123d6831ad5e59f11ba365">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316cfbc4918ff10b0e3b94a57c67efa8">Msg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d7aa93771cd3ac7eec07d5339ff4050">classof</a> (const DiagnosticInfo *DI)</td>
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

<p>Diagnostic information for IR instrumentation reporting.</p>

<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DiagnosticInfoInstrumentation() {#a5c0702308df4e060d6b19e770b7fb610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticInfoInstrumentation::DiagnosticInfoInstrumentation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; DiagMsg, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5c">DiagnosticSeverity</a> Severity=<a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">DS_Warning</a>)</td>
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



<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a76b8cea6950959f7799660a3a7d1caa5">llvm::DiagnosticInfo::DiagnosticInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a23fc35f8f953c8d5963ab9e650f79bb0">llvm::DK_Instrumentation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">llvm::DS_Warning</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### print() {#aae6e4f68e6123d6831ad5e59f11ba365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagnosticInfoInstrumentation::print (<a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter">DiagnosticPrinter</a> &amp; DP)</td>
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

<p>Print using the given <span class="doxyComputerOutput">DP</span> a user-friendly message.</p>


<p>This is the default message that will be printed to the user. It is used when the frontend does not directly take advantage of the information contained in fields of the subclasses. The printed message must not end with '.' nor start with a severity keyword.</p>


<p>Declaration at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnosticinfo-cpp">DiagnosticInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Msg {#a316cfbc4918ff10b0e3b94a57c67efa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Twine&amp; llvm::DiagnosticInfoInstrumentation::Msg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a0d7aa93771cd3ac7eec07d5339ff4050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticInfoInstrumentation::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> * DI)</td>
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



<p>Definition at line 1037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">DiagnosticInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a76b8cea6950959f7799660a3a7d1caa5">llvm::DiagnosticInfo::DiagnosticInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a23fc35f8f953c8d5963ab9e650f79bb0">llvm::DK_Instrumentation</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a6ee6158fd6a3b235dbb41acfe4f9930f">llvm::DiagnosticInfo::getKind</a>.</p>

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
