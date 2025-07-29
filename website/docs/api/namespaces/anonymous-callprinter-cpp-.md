---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-callprinter-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{CallPrinter.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{CallPrinter.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphviewer">CallGraphViewer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphdotprinter">CallGraphDOTPrinter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf50017de920c87b011ed76428eab4cd">doCallGraphDOTPrinting</a> (Module &amp;M, function_ref&lt; BlockFrequencyInfo *(Function &amp;)&gt; LookupBFI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a911cc9863fc00bdf515bf3203add8a25">viewCallGraph</a> (Module &amp;M, function_ref&lt; BlockFrequencyInfo *(Function &amp;)&gt; LookupBFI)</td>
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

### doCallGraphDOTPrinting() {#abf50017de920c87b011ed76428eab4cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CallPrinter.cpp}::doCallGraphDOTPrinting (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; LookupBFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp/#a9a03a260dfca52e2248b46fd6f2e6a90">CallGraphDotFilenamePrefix</a>, <a href="#abf50017de920c87b011ed76428eab4cd">doCallGraphDOTPrinting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a6118bd1b7164f1f8f02470a5cb6a538b">llvm::sys::fs::OF_Text</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a45fc498e695e5b2061ab5e6ec8e604a1">llvm::WriteGraph</a>.</p>


<p>Referenced by <a href="#abf50017de920c87b011ed76428eab4cd">doCallGraphDOTPrinting</a> and <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphdotprinter/#a2ab234950b299930fe1a4d5b9f68e55a">anonymous{CallPrinter.cpp}::CallGraphDOTPrinter::runOnModule</a>.</p>

</div>
</div>

### viewCallGraph() {#a911cc9863fc00bdf515bf3203add8a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CallPrinter.cpp}::viewCallGraph (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; LookupBFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#a4c2c0688a7c4cf69903603fddd539b45">llvm::DefaultDOTGraphTraits::getGraphName</a>, <a href="#a911cc9863fc00bdf515bf3203add8a25">viewCallGraph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8635363d4287c93f64c55ad5567fcf0">llvm::ViewGraph</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-callprinter-cpp-/callgraphviewer/#a0ab22936fc8a48301af3e72a814bdd7c">anonymous{CallPrinter.cpp}::CallGraphViewer::runOnModule</a> and <a href="#a911cc9863fc00bdf515bf3203add8a25">viewCallGraph</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
