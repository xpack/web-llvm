---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/diagnostichandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DiagnosticHandler` Struct

<p>This is the base class for diagnostic handling in LLVM. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DiagnosticHandler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">llvm/IR/DiagnosticHandler.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-ltocodegenerator-cpp-/ltodiagnostichandler">LTODiagnosticHandler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/ltollvmdiagnostichandler">LTOLLVMDiagnosticHandler</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d9f9fb9d6c947611fd905b718e4bbb">DiagnosticHandlerTy</a> = void(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> *DI, void *Context)</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6e022215e80ad4239efc983aaee8a5b">DiagnosticHandler</a> (void *DiagContext=nullptr)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e81378d53445fb3e402412c7cefe5f">~DiagnosticHandler</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c46bc0e22cefe4cf855cd9606d0da23">handleDiagnostics</a> (const DiagnosticInfo &amp;DI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override handleDiagnostics to provide custom implementation. <a href="#a2c46bc0e22cefe4cf855cd9606d0da23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9491283253671daad4d7d6cebbba3df2">isAnalysisRemarkEnabled</a> (StringRef PassName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if analysis remarks are enabled, override to provide different implementation. <a href="#a9491283253671daad4d7d6cebbba3df2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f8497579cb50322178c9b6e1daacaa">isMissedOptRemarkEnabled</a> (StringRef PassName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if missed optimization remarks are enabled, override to provide different implementation. <a href="#aa7f8497579cb50322178c9b6e1daacaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d19acbb7c39a4b3c8f818e5b467cf2">isPassedOptRemarkEnabled</a> (StringRef PassName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if passed optimization remarks are enabled, override to provide different implementation. <a href="#a03d19acbb7c39a4b3c8f818e5b467cf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab057d53fef7c0851c7313dc26b2aa4eb">isAnyRemarkEnabled</a> (StringRef PassName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if any type of remarks are enabled for this pass. <a href="#ab057d53fef7c0851c7313dc26b2aa4eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af662db5655d89ac3be06ce86545444bf">isAnyRemarkEnabled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if any type of remarks are enabled for any pass. <a href="#af662db5655d89ac3be06ce86545444bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7684b73722b2498ef87c5dde6f0e629">DiagnosticContext</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf730d8650d2442a713d16c63e8110a5">HasErrors</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a57d9f9fb9d6c947611fd905b718e4bbb">DiagnosticHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7bf9538a2db14248d9770b4b8165439">DiagHandlerCallback</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DiagHandlerCallback is settable from the C API and base implementation of <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> will call it from <a href="#a2c46bc0e22cefe4cf855cd9606d0da23">handleDiagnostics()</a>. <a href="#ae7bf9538a2db14248d9770b4b8165439">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is the base class for diagnostic handling in LLVM.</p>


<p>The handleDiagnostics method must be overriden by the subclasses to handle diagnostic. The *RemarkEnabled methods can be overriden to control which remarks are enabled.</p>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DiagnosticHandlerTy {#a57d9f9fb9d6c947611fd905b718e4bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DiagnosticHandler::DiagnosticHandlerTy =  void (*)(const DiagnosticInfo *DI, void *Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DiagnosticHandler() {#ab6e022215e80ad4239efc983aaee8a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DiagnosticHandler::DiagnosticHandler (void * DiagContext=nullptr)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>.</p>


<p>Reference <a href="#aa7684b73722b2498ef87c5dde6f0e629">DiagnosticContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DiagnosticHandler() {#a35e81378d53445fb3e402412c7cefe5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::DiagnosticHandler::~DiagnosticHandler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### handleDiagnostics() {#a2c46bc0e22cefe4cf855cd9606d0da23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::DiagnosticHandler::handleDiagnostics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> &amp; DI)</td>
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


<p>Return true if it handles diagnostics reporting properly otherwise return false to make <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aad03ef5cfbe6e7cad076d9e45ba06592">LLVMContext::diagnose()</a> to print the message with a prefix based on the severity.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>.</p>


<p>References <a href="#ae7bf9538a2db14248d9770b4b8165439">DiagHandlerCallback</a> and <a href="#aa7684b73722b2498ef87c5dde6f0e629">DiagnosticContext</a>.</p>

</div>
</div>

### isAnalysisRemarkEnabled() {#a9491283253671daad4d7d6cebbba3df2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DiagnosticHandler::isAnalysisRemarkEnabled (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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

<p>Return true if analysis remarks are enabled, override to provide different implementation.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a> and <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt/#a6ee605ba56cc22e4f4279cac6eb4ef0d">anonymous{DiagnosticHandler.cpp}::PassRemarksOpt::Pattern</a>.</p>


<p>Referenced by <a href="#ab057d53fef7c0851c7313dc26b2aa4eb">isAnyRemarkEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkanalysis/#a21c55fb64c1decb01f6dfe60ba7b6c1d">llvm::MachineOptimizationRemarkAnalysis::isEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a0f1ed99116e727b8a7af8cf48889e7b6">llvm::OptimizationRemarkAnalysis::isEnabled</a>.</p>

</div>
</div>

### isAnyRemarkEnabled() {#ab057d53fef7c0851c7313dc26b2aa4eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticHandler::isAnyRemarkEnabled (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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

<p>Return true if any type of remarks are enabled for this pass.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>.</p>


<p>References <a href="#a9491283253671daad4d7d6cebbba3df2">isAnalysisRemarkEnabled</a>, <a href="#aa7f8497579cb50322178c9b6e1daacaa">isMissedOptRemarkEnabled</a>, <a href="#a03d19acbb7c39a4b3c8f818e5b467cf2">isPassedOptRemarkEnabled</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>

</div>
</div>

### isAnyRemarkEnabled() {#af662db5655d89ac3be06ce86545444bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DiagnosticHandler::isAnyRemarkEnabled ()</td>
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

<p>Return true if any type of remarks are enabled for any pass.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt/#a6ee605ba56cc22e4f4279cac6eb4ef0d">anonymous{DiagnosticHandler.cpp}::PassRemarksOpt::Pattern</a>.</p>

</div>
</div>

### isMissedOptRemarkEnabled() {#aa7f8497579cb50322178c9b6e1daacaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DiagnosticHandler::isMissedOptRemarkEnabled (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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

<p>Return true if missed optimization remarks are enabled, override to provide different implementation.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a> and <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt/#a6ee605ba56cc22e4f4279cac6eb4ef0d">anonymous{DiagnosticHandler.cpp}::PassRemarksOpt::Pattern</a>.</p>


<p>Referenced by <a href="#ab057d53fef7c0851c7313dc26b2aa4eb">isAnyRemarkEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkmissed/#a22479d91f2c90bb3032810dfa2864527">llvm::MachineOptimizationRemarkMissed::isEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#aafff42ca513f5f2e742201442cb299ef">llvm::OptimizationRemarkMissed::isEnabled</a>.</p>

</div>
</div>

### isPassedOptRemarkEnabled() {#a03d19acbb7c39a4b3c8f818e5b467cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DiagnosticHandler::isPassedOptRemarkEnabled (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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

<p>Return true if passed optimization remarks are enabled, override to provide different implementation.</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a> and <a href="/web-llvm/docs/api/structs/anonymous-diagnostichandler-cpp-/passremarksopt/#a6ee605ba56cc22e4f4279cac6eb4ef0d">anonymous{DiagnosticHandler.cpp}::PassRemarksOpt::Pattern</a>.</p>


<p>Referenced by <a href="#ab057d53fef7c0851c7313dc26b2aa4eb">isAnyRemarkEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremark/#a39d9cdb595768f3e86c3f86f4ba33c00">llvm::MachineOptimizationRemark::isEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a551a7d26da872a1e686a9d0d4a72d49b">llvm::OptimizationRemark::isEnabled</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DiagHandlerCallback {#ae7bf9538a2db14248d9770b4b8165439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticHandlerTy llvm::DiagnosticHandler::DiagHandlerCallback = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DiagHandlerCallback is settable from the C API and base implementation of <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> will call it from <a href="#a2c46bc0e22cefe4cf855cd9606d0da23">handleDiagnostics()</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> derived class of <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> should not use callback but implement <a href="#a2c46bc0e22cefe4cf855cd9606d0da23">handleDiagnostics()</a>.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>.</p>


<p>Referenced by <a href="#a2c46bc0e22cefe4cf855cd9606d0da23">handleDiagnostics</a>.</p>

</div>
</div>

### DiagnosticContext {#aa7684b73722b2498ef87c5dde6f0e629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::DiagnosticHandler::DiagnosticContext = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>.</p>


<p>Referenced by <a href="#ab6e022215e80ad4239efc983aaee8a5b">DiagnosticHandler</a> and <a href="#a2c46bc0e22cefe4cf855cd9606d0da23">handleDiagnostics</a>.</p>

</div>
</div>

### HasErrors {#acf730d8650d2442a713d16c63e8110a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DiagnosticHandler::HasErrors = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnostichandler-h">DiagnosticHandler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/diagnostichandler-cpp">DiagnosticHandler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
