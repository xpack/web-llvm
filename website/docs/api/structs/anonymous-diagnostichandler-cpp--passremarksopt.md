---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-diagnostichandler-cpp-/passremarksopt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PassRemarksOpt` Struct Reference

<p>Regular expression corresponding to the value given in one of the -pass-remarks* command line flags. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{DiagnosticHandler.cpp}::PassRemarksOpt { ... }
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f09c3ecb8bef88a80062363f80545b">operator=</a> (const std::string &amp;Val)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/regex">Regex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee605ba56cc22e4f4279cac6eb4ef0d">Pattern</a></td>
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

<p>Regular expression corresponding to the value given in one of the -pass-remarks* command line flags.</p>


<p>Passes whose name matches this regexp will emit a diagnostic when calling the associated diagnostic function (emitOptimizationRemark, emitOptimizationRemarkMissed or emitOptimizationRemarkAnalysis).</p>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator=() {#a23f09c3ecb8bef88a80062363f80545b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DiagnosticHandler.cpp}::PassRemarksOpt::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Val)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>


<p>References <a href="#a6ee605ba56cc22e4f4279cac6eb4ef0d">Pattern</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Pattern {#a6ee605ba56cc22e4f4279cac6eb4ef0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;Regex&gt; anonymous{DiagnosticHandler.cpp}::PassRemarksOpt::Pattern</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#a9491283253671daad4d7d6cebbba3df2">llvm::DiagnosticHandler::isAnalysisRemarkEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#af662db5655d89ac3be06ce86545444bf">llvm::DiagnosticHandler::isAnyRemarkEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#aa7f8497579cb50322178c9b6e1daacaa">llvm::DiagnosticHandler::isMissedOptRemarkEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler/#a03d19acbb7c39a4b3c8f818e5b467cf2">llvm::DiagnosticHandler::isPassedOptRemarkEnabled</a> and <a href="#a23f09c3ecb8bef88a80062363f80545b">operator=</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
