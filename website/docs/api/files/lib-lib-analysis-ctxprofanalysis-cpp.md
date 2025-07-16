---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/ctxprofanalysis-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CtxProfAnalysis.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">llvm/Analysis/CtxProfAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">llvm/IR/Analysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofreader-h">llvm/ProfileData/PGOCtxProfReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ProfilesTy, class ProfTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06c425cae4fdc2e2a65d456ec177907a">preorderVisit</a> (ProfilesTy &amp;Profiles, function_ref&lt; void(ProfTy &amp;)&gt; Visitor)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b2c87a52448d91bf5be603cc14acc5">UseCtxProfile</a>("use-ctx-profile", cl::init(""), cl::Hidden, cl::desc("Use the specified contextual profile file"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysisprinterpass/#a3af78ff7af591ecd49d28b8e6fa1ca79">CtxProfAnalysisPrinterPass::PrintMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36693c7cdeb67aeb1d3c0d36f091ebb8">PrintLevel</a>("ctx-profile-printer-level", cl::init(CtxProfAnalysisPrinterPass::PrintMode::YAML), cl::Hidden, cl::values(clEnumValN(CtxProfAnalysisPrinterPass::PrintMode::Everything, "everything", "print everything - most verbose"), clEnumValN(CtxProfAnalysisPrinterPass::PrintMode::YAML, "yaml", "just the yaml representation of the profile")), cl::desc("Verbosity level of the contextual profile printer pass."))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"ctx_prof"</td>
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

### preorderVisit() {#a06c425cae4fdc2e2a65d456ec177907a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ProfilesTy, class ProfTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void preorderVisit (ProfilesTy &amp; Profiles, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(ProfTy &amp;)&gt; Visitor)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pgocontextualprofile/#a33cb6013b6d9331d0af575039895b0ce">llvm::PGOContextualProfile::flatten</a> and <a href="/web-llvm/docs/api/classes/llvm/pgocontextualprofile/#a0aaa8bd4c2f0b4e66591869c1529d7e0">llvm::PGOContextualProfile::visit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### PrintLevel {#a36693c7cdeb67aeb1d3c0d36f091ebb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; CtxProfAnalysisPrinterPass::PrintMode &gt; PrintLevel("ctx-profile-printer-level", cl::init(CtxProfAnalysisPrinterPass::PrintMode::YAML), cl::Hidden, cl::values(clEnumValN(CtxProfAnalysisPrinterPass::PrintMode::Everything, "everything", "print everything - most verbose"), clEnumValN(CtxProfAnalysisPrinterPass::PrintMode::YAML, "yaml", "just the yaml representation of the profile")), cl::desc("Verbosity level of the contextual profile printer pass."))</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysisprinterpass/#a76448512581b028422c7d6c9dbfb7656">llvm::CtxProfAnalysisPrinterPass::CtxProfAnalysisPrinterPass</a>.</p>

</div>
</div>

### UseCtxProfile {#ae2b2c87a52448d91bf5be603cc14acc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; UseCtxProfile("use-ctx-profile", cl::init(""), cl::Hidden, cl::desc("Use the specified contextual profile file"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab53586b47722fa95d93ae8b06f734742">llvm::PassBuilder::buildModuleInlinerPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad6f258d31ffa2d2e4dfaf990ba596d0d">llvm::PassBuilder::buildModuleSimplificationPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ab7d260f2f928c81a2d225f2d1aafad0e">llvm::PassBuilder::buildThinLTODefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a2832cb00a6c94208b4a06696eeeabf99">llvm::PassBuilder::buildThinLTOPreLinkDefaultPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysis/#aeb0c1de723319e0dde2c8e263eb4c2ac">llvm::CtxProfAnalysis::CtxProfAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"ctx_prof"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
