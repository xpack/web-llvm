---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-memprofiler-cpp-/modulememprofiler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ModuleMemProfiler` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{MemProfiler.cpp}::ModuleMemProfiler { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9fbf5b3bd987ab4cc2131ae251dca6">ModuleMemProfiler</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd23674e615de45594d59ae63168ac5">instrumentModule</a> (Module &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2095b06c01e2e10b3d264dab9a078b8e">TargetTriple</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofiler-cpp-/shadowmapping">ShadowMapping</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51c3690c9f0e717d36476edabf88e8b">Mapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6bf40baac1ba4196d2efc378208d188">MemProfCtorFunction</a> = nullptr</td>
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


<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp">MemProfiler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ModuleMemProfiler() {#aef9fbf5b3bd987ab4cc2131ae251dca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemProfiler.cpp}::ModuleMemProfiler::ModuleMemProfiler (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp">MemProfiler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### instrumentModule() {#addd23674e615de45594d59ae63168ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleMemProfiler::instrumentModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp">MemProfiler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac030f6d03b674c2d132fd54fb60c9f26">llvm::appendToGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a2a1656d1f4ddeb386daf49396b178ab3">ClInsertVersionCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a61a95dc82ae09814a35f56fcc56cad5b">createMemprofDefaultOptionsVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a18fdc21778e3249102bca86808f4ef78">createMemprofHistogramFlagVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd35d43ef05edd633413fa4cfa802c0e">llvm::createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofiler-cpp-/#a25e178fd0357943af89097c8fc90a29a">anonymous{MemProfiler.cpp}::getCtorAndDtorPriority</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a4eb4495b700219216c8a74a535c0f2cf">LLVM_MEM_PROFILER_VERSION</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a55bb7390f2ac340eeb9f64a749ceea49">MemProfInitName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a8f5515f5bed91743d73975f54ba5ce03">MemProfModuleCtorName</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a08573aee06bc659699346285506370cc">MemProfVersionCheckNamePrefix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mapping {#ad51c3690c9f0e717d36476edabf88e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShadowMapping anonymous{MemProfiler.cpp}::ModuleMemProfiler::Mapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp">MemProfiler.cpp</a>.</p>

</div>
</div>

### MemProfCtorFunction {#af6bf40baac1ba4196d2efc378208d188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{MemProfiler.cpp}::ModuleMemProfiler::MemProfCtorFunction = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp">MemProfiler.cpp</a>.</p>

</div>
</div>

### TargetTriple {#a2095b06c01e2e10b3d264dab9a078b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple anonymous{MemProfiler.cpp}::ModuleMemProfiler::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp">MemProfiler.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp">MemProfiler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
