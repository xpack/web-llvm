---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-sanitizercoverage-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{SanitizerCoverage.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{SanitizerCoverage.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage">ModuleSanitizerCoverage</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions">SanitizerCoverageOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d96f8f65b0da1c5084227ecdd876b16">getOptions</a> (int LegacyCoverageLevel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions">SanitizerCoverageOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9b8d17833329a87ee81549b43f366e7">OverrideFromCL</a> (SanitizerCoverageOptions Options)</td>
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


<div class="doxySectionDef">

## Functions

### getOptions() {#a6d96f8f65b0da1c5084227ecdd876b16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SanitizerCoverageOptions anonymous{SanitizerCoverage.cpp}::getOptions (int LegacyCoverageLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#a09606541d39f43887258e83b257e34c1">llvm::SanitizerCoverageOptions::CoverageType</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#aaaab818a4cdbca694e6eb690d7a257f1">llvm::SanitizerCoverageOptions::IndirectCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#a6fbd9e46b04866c157520732aaaa99beaa742a77dbd1705b1b3e1a612279029d8">llvm::SanitizerCoverageOptions::SCK_BB</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#a6fbd9e46b04866c157520732aaaa99beafdefa46197f678fbe938c38ee20befd1">llvm::SanitizerCoverageOptions::SCK_Edge</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#a6fbd9e46b04866c157520732aaaa99bea626aea6d83c51734a35fe969a0c86c5f">llvm::SanitizerCoverageOptions::SCK_Function</a> and <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#a6fbd9e46b04866c157520732aaaa99bea8d35016762982753aec6d7aed4be8142">llvm::SanitizerCoverageOptions::SCK_None</a>.</p>


<p>Referenced by <a href="#ab9b8d17833329a87ee81549b43f366e7">OverrideFromCL</a>.</p>

</div>
</div>

### OverrideFromCL() {#ab9b8d17833329a87ee81549b43f366e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SanitizerCoverageOptions anonymous{SanitizerCoverage.cpp}::OverrideFromCL (<a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions">SanitizerCoverageOptions</a> Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ac078e1f43f3af7259e65cd9f8589426d">ClCMPTracing</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a4dc8e5eb0681178753ad8ff7a760c6ca">ClCollectCF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a087e8fce1446a6c0f47996d66fb5883f">ClCoverageLevel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a42bcf9fefae825ca049233fc33561405">ClCreatePCTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#acb75b19a8e0e6197cecf82daab10bf20">ClDIVTracing</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a5d736bf277e14e3b7f72c7165e4e03f6">ClGatedCallbacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a98abe00eff5ce2fcbe03bdda7349d513">ClGEPTracing</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#acbe6559fbc44f1ff3e08e466b891ace4">ClInline8bitCounters</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a18ebc56bdf72b97446301ce4b8a3da7d">ClInlineBoolFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a03c575f46d699d5b0fa6d17896382e21">ClLoadTracing</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#aaa46a35f0a2abc392c67dfc56b9a6c40">ClPruneBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a0fd283a9e17437965355254fbe12065e">ClStackDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a8e1562d65b3653cbfcea640f097cff39">ClStoreTracing</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#aa48daee972cdb91cc0749f31ca89eae7">ClTracePC</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a95896110981e827a9a6a943995e8c600">ClTracePCGuard</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#a09606541d39f43887258e83b257e34c1">llvm::SanitizerCoverageOptions::CoverageType</a>, <a href="#a6d96f8f65b0da1c5084227ecdd876b16">getOptions</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#aaaab818a4cdbca694e6eb690d7a257f1">llvm::SanitizerCoverageOptions::IndirectCalls</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
