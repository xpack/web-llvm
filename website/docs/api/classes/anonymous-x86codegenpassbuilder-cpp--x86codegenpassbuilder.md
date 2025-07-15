---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86codegenpassbuilder-cpp-/x86codegenpassbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86CodeGenPassBuilder` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{X86CodeGenPassBuilder.cpp}::X86CodeGenPassBuilder { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder">CodeGenPassBuilder&lt;DerivedT, TargetMachineT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class provides access to building LLVM's passes. <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae761fd3095513a1031a7dc568d9f7f0d">X86CodeGenPassBuilder</a> (X86TargetMachine &amp;TM, const CGPassBuilderOption &amp;Opts, PassInstrumentationCallbacks *PIC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7f7ad17088208d38e76da3923176eb">addPreISel</a> (AddIRPass &amp;addPass) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5337449b1ff094f49c6e74e3032d62c4">addAsmPrinter</a> (AddMachinePass &amp;, CreateMCStreamer) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe84e25a51bebfa491736b36531c077a">addInstSelector</a> (AddMachinePass &amp;) const</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86codegenpassbuilder-cpp">X86CodeGenPassBuilder.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86CodeGenPassBuilder() {#ae761fd3095513a1031a7dc568d9f7f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86CodeGenPassBuilder.cpp}::X86CodeGenPassBuilder::X86CodeGenPassBuilder (<a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/cgpassbuilderoption">CGPassBuilderOption</a> &amp; Opts, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> * PIC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86codegenpassbuilder-cpp">X86CodeGenPassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a94d7ce2e38cb6acae735d6edb74c8fa7">llvm::CodeGenPassBuilder&lt; X86CodeGenPassBuilder, X86TargetMachine &gt;::CodeGenPassBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a8b37f13bb1431bc3965bbdfc110a5fb1">llvm::CodeGenPassBuilder&lt; X86CodeGenPassBuilder, X86TargetMachine &gt;::PIC</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; X86CodeGenPassBuilder, X86TargetMachine &gt;::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAsmPrinter() {#a5337449b1ff094f49c6e74e3032d62c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86CodeGenPassBuilder.cpp}::X86CodeGenPassBuilder::addAsmPrinter (AddMachinePass &amp; addPass, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a738a8c97344f7d78bfb36623251608ad">CreateMCStreamer</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86codegenpassbuilder-cpp">X86CodeGenPassBuilder.cpp</a>.</p>

</div>
</div>

### addInstSelector() {#abe84e25a51bebfa491736b36531c077a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{X86CodeGenPassBuilder.cpp}::X86CodeGenPassBuilder::addInstSelector (AddMachinePass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86codegenpassbuilder-cpp">X86CodeGenPassBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; X86CodeGenPassBuilder, X86TargetMachine &gt;::TM</a>.</p>

</div>
</div>

### addPreISel() {#a6b7f7ad17088208d38e76da3923176eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86CodeGenPassBuilder.cpp}::X86CodeGenPassBuilder::addPreISel (AddIRPass &amp; addPass)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86codegenpassbuilder-cpp">X86CodeGenPassBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86codegenpassbuilder-cpp">X86CodeGenPassBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
