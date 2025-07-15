---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-machineverifier-cpp-/machineverifier/reportederrors
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ReportedErrors` Class Reference

<p>A class to track the number of reported error and to guarantee that only one error is reported at one time. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MachineVerifier.cpp}::MachineVerifier::ReportedErrors { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc462b72b32cc5bfcc3d4477c4da6258">ReportedErrors</a> (bool AbortOnError)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf085f7b9a8edc32ca99f8da3f2b32ca">~ReportedErrors</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f2d25f87ecdfe6dffbceb048e3df43">increment</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Increment the number of reported errors. <a href="#a14f2d25f87ecdfe6dffbceb048e3df43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f8b6890783b18e95281fff1fbd1904">hasError</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d692707842ef54279f151e9d8fed01">NumReported</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf40fe1cd773121b315b1ed037731b00">AbortOnError</a></td>
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

<p>A class to track the number of reported error and to guarantee that only one error is reported at one time.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ReportedErrors() {#acc462b72b32cc5bfcc3d4477c4da6258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineVerifier.cpp}::MachineVerifier::ReportedErrors::ReportedErrors (bool AbortOnError)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AbortOnError</td>
<td class="doxyParamItemDescription"><p>– If set, abort after printing the first error.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ReportedErrors() {#adf085f7b9a8edc32ca99f8da3f2b32ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineVerifier.cpp}::MachineVerifier::ReportedErrors::~ReportedErrors ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#ad1f8b6890783b18e95281fff1fbd1904">hasError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machineverifier-cpp-/#aa359ce154187f8c7b4f08e5820f3c0ef">anonymous{MachineVerifier.cpp}::ReportedErrorsLock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasError() {#ad1f8b6890783b18e95281fff1fbd1904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::ReportedErrors::hasError ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if an error was reported.</p></dd>
</dl>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>Referenced by <a href="#a14f2d25f87ecdfe6dffbceb048e3df43">increment</a> and <a href="#adf085f7b9a8edc32ca99f8da3f2b32ca">~ReportedErrors</a>.</p>

</div>
</div>

### increment() {#a14f2d25f87ecdfe6dffbceb048e3df43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::ReportedErrors::increment ()</td>
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

<p>Increment the number of reported errors.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this is the first reported error.</p></dd>
</dl>


<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>


<p>References <a href="#ad1f8b6890783b18e95281fff1fbd1904">hasError</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machineverifier-cpp-/#aa359ce154187f8c7b4f08e5820f3c0ef">anonymous{MachineVerifier.cpp}::ReportedErrorsLock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AbortOnError {#acf40fe1cd773121b315b1ed037731b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineVerifier.cpp}::MachineVerifier::ReportedErrors::AbortOnError</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

### NumReported {#a69d692707842ef54279f151e9d8fed01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachineVerifier.cpp}::MachineVerifier::ReportedErrors::NumReported = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp">MachineVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
