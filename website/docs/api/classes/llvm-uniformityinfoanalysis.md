---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/uniformityinfoanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `UniformityInfoAnalysis` Class

<p>Analysis pass which computes <a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::UniformityInfoAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">llvm/Analysis/UniformityAnalysis.h</a>"
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34df09ec156bc64763f3b8b86480fa2">Result</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide the result typedef for this analysis pass. <a href="#af34df09ec156bc64763f3b8b86480fa2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8aad6f3b254e32f560836dd25a317a0">run</a> (Function &amp;F, FunctionAnalysisManager &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the analysis pass over a function and produce a dominator tree. <a href="#af8aad6f3b254e32f560836dd25a317a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ccbdfbb662575b899cefafddc87eba">AnalysisInfoMixin&lt; UniformityInfoAnalysis &gt;</a></td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a087485c47529857cb251be0f732bd801">Key</a></td>
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

<p>Analysis pass which computes <a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a>.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">UniformityAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Result {#af34df09ec156bc64763f3b8b86480fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::UniformityInfoAnalysis::Result =  UniformityInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide the result typedef for this analysis pass.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">UniformityAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#af8aad6f3b254e32f560836dd25a317a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::UniformityInfo UniformityInfoAnalysis::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run the analysis pass over a function and produce a dominator tree.</p>

<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">UniformityAnalysis.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulatecodegenpreparepass/#a5a4ff24504b852091b900d036f556885">llvm::AMDGPULateCodeGenPreparePass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AnalysisInfoMixin&lt; UniformityInfoAnalysis &gt; {#a54ccbdfbb662575b899cefafddc87eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::UniformityInfoAnalysis::AnalysisInfoMixin&lt; UniformityInfoAnalysis &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">UniformityAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### Key {#a087485c47529857cb251be0f732bd801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisKey UniformityInfoAnalysis::Key</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">UniformityAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/uniformityanalysis-h">UniformityAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/uniformityanalysis-cpp">UniformityAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
