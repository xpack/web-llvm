---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/moduleinlinerwrapperpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ModuleInlinerWrapperPass` Class

<p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> pass, wrapping the inliner pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ModuleInlinerWrapperPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">llvm/Transforms/IPO/Inliner.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff89291a71c595f474b9fc7c99860170">ModuleInlinerWrapperPass</a> (InlineParams Params=getInlineParams(), bool MandatoryFirst=true, InlineContext IC={}, InliningAdvisorMode Mode=InliningAdvisorMode::Default, unsigned MaxDevirtIterations=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f8d4f410aa14d89b5abb81d9282ee0">ModuleInlinerWrapperPass</a> (ModuleInlinerWrapperPass &amp;&amp;Arg)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a302bbe2963bced6cb8460b94f89dd0be">run</a> (Module &amp;, ModuleAnalysisManager &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39796adfa25411560f31295c81b9a148">getPM</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow adding more CGSCC passes, besides inlining. <a href="#a39796adfa25411560f31295c81b9a148">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b62feb6bba2102fd3de281a7bb39643">addModulePass</a> (T Pass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a module pass that runs before the CGSCC passes. <a href="#a2b62feb6bba2102fd3de281a7bb39643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a93cb37ea001cb028e60644bac5823e8f">addLateModulePass</a> (T Pass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a module pass that runs after the CGSCC passes. <a href="#a93cb37ea001cb028e60644bac5823e8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab518c48fbbea8ebc75e5d48c3291b6d5">printPipeline</a> (raw_ostream &amp;OS, function_ref&lt; StringRef(StringRef)&gt; MapClassName2PassName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f71f71deb53c96db29abb6b9b11902">Params</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/inlinecontext">InlineContext</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a245ff5816064895254d903b2b0cdcefe">IC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a239c4ac35d6028bfacaed4018d0488fa">InliningAdvisorMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55a17f4cc2ccd0da53a181b369225111">Mode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c039e5512d01f40ccc5cb809fa3464">MaxDevirtIterations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a4ded4558d2b58dcdd7a1736aa69a8bc4">CGSCCPassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb00294ba5f1a00ce63a90fbf2e40c6">PM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22982a39a83bda31dfc79d28092394a6">MPM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05433284a1e8905daed75bd6bf3cf6be">AfterCGMPM</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> pass, wrapping the inliner pass.</p>


<p>This works in conjunction with the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysis">InlineAdvisorAnalysis</a> to facilitate inlining decisions taking into account module-wide state, that need to keep track of inter-inliner pass runs, for a given module. An <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> is configured and kept alive for the duration of the <a href="#a302bbe2963bced6cb8460b94f89dd0be">ModuleInlinerWrapperPass::run</a>.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ModuleInlinerWrapperPass() {#aff89291a71c595f474b9fc7c99860170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleInlinerWrapperPass::ModuleInlinerWrapperPass (<a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a> Params=<a href="/web-llvm/docs/api/namespaces/llvm/#aba7063dea024346c7b70099c63703f50">getInlineParams</a>(), bool MandatoryFirst=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/structs/llvm/inlinecontext">InlineContext</a> IC={}, <a href="/web-llvm/docs/api/namespaces/llvm/#a239c4ac35d6028bfacaed4018d0488fa">InliningAdvisorMode</a> Mode=<a href="/web-llvm/docs/api/namespaces/llvm/#a239c4ac35d6028bfacaed4018d0488faa7a1920d61156abc05a60135aefe8bc67">InliningAdvisorMode::Default</a>, unsigned MaxDevirtIterations=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp/#a52008b14ac463a4009ec7debf64144d2">EnablePostSCCAdvisorPrinting</a>.</p>


<p>Referenced by <a href="#ad3f8d4f410aa14d89b5abb81d9282ee0">ModuleInlinerWrapperPass</a>.</p>

</div>
</div>

### ModuleInlinerWrapperPass() {#ad3f8d4f410aa14d89b5abb81d9282ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ModuleInlinerWrapperPass::ModuleInlinerWrapperPass (<a href="/web-llvm/docs/api/classes/llvm/moduleinlinerwrapperpass">ModuleInlinerWrapperPass</a> &amp;&amp; Arg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>


<p>Reference <a href="#aff89291a71c595f474b9fc7c99860170">ModuleInlinerWrapperPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLateModulePass() {#a93cb37ea001cb028e60644bac5823e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ModuleInlinerWrapperPass::addLateModulePass (T Pass)</td>
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

<p>Add a module pass that runs after the CGSCC passes.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### addModulePass() {#a2b62feb6bba2102fd3de281a7bb39643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ModuleInlinerWrapperPass::addModulePass (T Pass)</td>
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

<p>Add a module pass that runs before the CGSCC passes.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a08240a2eba496a292cec022c5093f621">llvm::PassBuilder::buildInlinerPipeline</a>.</p>

</div>
</div>

### getPM() {#a39796adfa25411560f31295c81b9a148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGSCCPassManager &amp; llvm::ModuleInlinerWrapperPass::getPM ()</td>
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

<p>Allow adding more CGSCC passes, besides inlining.</p>


<p>This should be called before run is called, as part of pass pipeline building.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>

</div>
</div>

### printPipeline() {#ab518c48fbbea8ebc75e5d48c3291b6d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleInlinerWrapperPass::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; MapClassName2PassName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>, definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>

</div>
</div>

### run() {#a302bbe2963bced6cb8460b94f89dd0be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses ModuleInlinerWrapperPass::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>, definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AfterCGMPM {#a05433284a1e8905daed75bd6bf3cf6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager llvm::ModuleInlinerWrapperPass::AfterCGMPM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>

</div>
</div>

### IC {#a245ff5816064895254d903b2b0cdcefe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InlineContext llvm::ModuleInlinerWrapperPass::IC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>

</div>
</div>

### MaxDevirtIterations {#a16c039e5512d01f40ccc5cb809fa3464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::ModuleInlinerWrapperPass::MaxDevirtIterations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>

</div>
</div>

### Mode {#a55a17f4cc2ccd0da53a181b369225111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InliningAdvisorMode llvm::ModuleInlinerWrapperPass::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>

</div>
</div>

### MPM {#a22982a39a83bda31dfc79d28092394a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePassManager llvm::ModuleInlinerWrapperPass::MPM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>

</div>
</div>

### Params {#a06f71f71deb53c96db29abb6b9b11902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InlineParams llvm::ModuleInlinerWrapperPass::Params</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>

</div>
</div>

### PM {#adcb00294ba5f1a00ce63a90fbf2e40c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGSCCPassManager llvm::ModuleInlinerWrapperPass::PM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">Inliner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
