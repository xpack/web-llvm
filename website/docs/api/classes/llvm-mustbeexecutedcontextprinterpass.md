---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mustbeexecutedcontextprinterpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MustBeExecutedContextPrinterPass` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MustBeExecutedContextPrinterPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">llvm/Analysis/MustExecute.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a14dfad84d1b9977dfc94f5130e33d">MustBeExecutedContextPrinterPass</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b1a19034ac7bbb0481e54e850fc431a">run</a> (Module &amp;M, ModuleAnalysisManager &amp;AM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a550ffef9105f930b9a93093d3adb73eb">OS</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac163e54e7e1a1067a40b1e8ddde130ab">isRequired</a> ()</td>
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


<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MustBeExecutedContextPrinterPass() {#a74a14dfad84d1b9977dfc94f5130e33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MustBeExecutedContextPrinterPass::MustBeExecutedContextPrinterPass (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a1b1a19034ac7bbb0481e54e850fc431a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses MustBeExecutedContextPrinterPass::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> and <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a8cbad11b160003ae7f4ebb06bc25d981">llvm::MustBeExecutedContextExplorer::range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OS {#a550ffef9105f930b9a93093d3adb73eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::MustBeExecutedContextPrinterPass::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isRequired() {#ac163e54e7e1a1067a40b1e8ddde130ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MustBeExecutedContextPrinterPass::isRequired ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
