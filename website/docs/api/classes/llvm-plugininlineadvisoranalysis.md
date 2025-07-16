---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/plugininlineadvisoranalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PluginInlineAdvisorAnalysis` Class Reference

<p>Used for dynamically registering InlineAdvisors as plugins. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PluginInlineAdvisorAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/analysisinfomixin">AnalysisInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in that provides informational APIs needed for analysis passes. <a href="/web-llvm/docs/api/structs/llvm/analysisinfomixin/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> *(* <a href="#a93eea258d63139c33eb8c616cbf874d0">AdvisorFactory</a>)(Module &M, FunctionAnalysisManager &FAM, InlineParams Params, InlineContext IC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c259a023b8d44574a5726f7ff1f760d">PluginInlineAdvisorAnalysis</a> (AdvisorFactory Factory)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/plugininlineadvisoranalysis/result">Result</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b307241d77fee693b65e68353a8d286">run</a> (Module &amp;M, ModuleAnalysisManager &amp;MAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/plugininlineadvisoranalysis/result">Result</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c451730ff64747dd678febfd9a74f6f">getResult</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a93eea258d63139c33eb8c616cbf874d0">AdvisorFactory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a53db400cf8017551d8672d88d9ff33">Factory</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace1abfb5551903e801246b4d4f227e46">Key</a></td>
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

<p>Used for dynamically registering InlineAdvisors as plugins.</p>


<p>An advisor plugin adds a new advisor at runtime by registering an instance of <a href="/web-llvm/docs/api/classes/llvm/plugininlineadvisoranalysis">PluginInlineAdvisorAnalysis</a> in the current <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a>. For example, the following code dynamically registers a <a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvisor">DefaultInlineAdvisor</a>:</p>


<p>namespace {</p>


<p><a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> *defaultAdvisorFactory(<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;M, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp;FAM, <a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a> Params, <a href="/web-llvm/docs/api/structs/llvm/inlinecontext">InlineContext</a> IC) { return new DefaultInlineAdvisor(M, FAM, Params, IC); }</p>


<p>} // namespace</p>


<p>extern "C" LLVM_ATTRIBUTE_WEAK <a href="/web-llvm/docs/api/structs/llvm/passpluginlibraryinfo">llvm::PassPluginLibraryInfo</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passplugin-h/#aedb30b5365f0c854e71a27da0db8e172">llvmGetPassPluginInfo()</a> { return {LLVM_PLUGIN_API_VERSION, "DynamicDefaultAdvisor", LLVM_VERSION_STRING, [](<a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> &amp;PB) { PB.registerAnalysisRegistrationCallback( [](<a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp;MAM) { <a href="/web-llvm/docs/api/classes/llvm/plugininlineadvisoranalysis">PluginInlineAdvisorAnalysis</a> PA(defaultAdvisorFactory); MAM.registerPass([&amp;] { return PA; }); }); }}; }</p>


<p>A plugin must implement an <a href="#a93eea258d63139c33eb8c616cbf874d0">AdvisorFactory</a> and register it with a PluginInlineAdvisorAnlysis to the provided <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a>.</p>


<p>If such a plugin has been registered <a href="/web-llvm/docs/api/structs/llvm/inlineadvisoranalysis/result/#a64e2a53c670b4531950c994d84bc4e39">InlineAdvisorAnalysis::Result::tryCreate</a> will return the dynamically loaded advisor.</p>


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AdvisorFactory {#a93eea258d63139c33eb8c616cbf874d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef InlineAdvisor *(* llvm::PluginInlineAdvisorAnalysis::AdvisorFactory) (Module &amp;M, FunctionAnalysisManager &amp;FAM, InlineParams Params, InlineContext IC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PluginInlineAdvisorAnalysis() {#a7c259a023b8d44574a5726f7ff1f760d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PluginInlineAdvisorAnalysis::PluginInlineAdvisorAnalysis (<a href="#a93eea258d63139c33eb8c616cbf874d0">AdvisorFactory</a> Factory)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getResult() {#a4c451730ff64747dd678febfd9a74f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Result llvm::PluginInlineAdvisorAnalysis::getResult ()</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

### run() {#a9b307241d77fee693b65e68353a8d286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Result llvm::PluginInlineAdvisorAnalysis::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Factory {#a9a53db400cf8017551d8672d88d9ff33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AdvisorFactory llvm::PluginInlineAdvisorAnalysis::Factory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Key {#ace1abfb5551903e801246b4d4f227e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisKey PluginInlineAdvisorAnalysis::Key</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
