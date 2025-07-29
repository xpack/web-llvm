---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-ltocodegenerator-cpp-/ltodiagnostichandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LTODiagnosticHandler` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{LTOCodeGenerator.cpp}::LTODiagnosticHandler { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the base class for diagnostic handling in LLVM. <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc2413700a13057cda5200bcb940444c">LTODiagnosticHandler</a> (LTOCodeGenerator *CodeGenPtr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08be76d0743fdecc66ac5abe9d6f8e1">handleDiagnostics</a> (const DiagnosticInfo &amp;DI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override handleDiagnostics to provide custom implementation. <a href="#aa08be76d0743fdecc66ac5abe9d6f8e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator">LTOCodeGenerator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f23136dc5f1c596473a112df5663d02">CodeGenerator</a></td>
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


<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LTODiagnosticHandler() {#abc2413700a13057cda5200bcb940444c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LTOCodeGenerator.cpp}::LTODiagnosticHandler::LTODiagnosticHandler (<a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator">LTOCodeGenerator</a> * CodeGenPtr)</td>
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



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>Reference <a href="#a4f23136dc5f1c596473a112df5663d02">CodeGenerator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### handleDiagnostics() {#aa08be76d0743fdecc66ac5abe9d6f8e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LTOCodeGenerator.cpp}::LTODiagnosticHandler::handleDiagnostics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> &amp; DI)</td>
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

<p>Override handleDiagnostics to provide custom implementation.</p>


<p>Return true if it handles diagnostics reporting properly otherwise return false to make LLVMContext::diagnose() to print the message with a prefix based on the severity.</p>


<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>Reference <a href="#a4f23136dc5f1c596473a112df5663d02">CodeGenerator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CodeGenerator {#a4f23136dc5f1c596473a112df5663d02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LTOCodeGenerator* anonymous{LTOCodeGenerator.cpp}::LTODiagnosticHandler::CodeGenerator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>Referenced by <a href="#aa08be76d0743fdecc66ac5abe9d6f8e1">handleDiagnostics</a> and <a href="#abc2413700a13057cda5200bcb940444c">LTODiagnosticHandler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
