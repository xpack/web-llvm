---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopunrollandjampass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoopUnrollAndJamPass` Class

<p>A simple loop rotation transformation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopUnrollAndJamPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollandjampass-h">llvm/Transforms/Scalar/LoopUnrollAndJamPass.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeece1a2fcecd3182bf6bc0cf3bff9fc1">LoopUnrollAndJamPass</a> (int OptLevel=2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceae0aba9cc69bf89d3241d61190b9ec">run</a> (LoopNest &amp;L, LoopAnalysisManager &amp;AM, LoopStandardAnalysisResults &amp;AR, LPMUpdater &amp;U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd06c53da7f7208659305a477f5af8c">OptLevel</a></td>
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

<p>A simple loop rotation transformation.</p>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollandjampass-h">LoopUnrollAndJamPass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopUnrollAndJamPass() {#aeece1a2fcecd3182bf6bc0cf3bff9fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopUnrollAndJamPass::LoopUnrollAndJamPass (int OptLevel=2)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollandjampass-h">LoopUnrollAndJamPass.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#aceae0aba9cc69bf89d3241d61190b9ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses LoopUnrollAndJamPass::run (<a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> &amp; L, <a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults">LoopStandardAnalysisResults</a> &amp; AR, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollandjampass-h">LoopUnrollAndJamPass.h</a>, definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#abd7da877be8576011299f4fcaaf299be">llvm::LoopStandardAnalysisResults::AA</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a902b4712394a3b3450893634b3302893">llvm::LoopStandardAnalysisResults::AC</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#aaa96df870a1b3d7ffc56bec3eb0b0cff">llvm::LoopStandardAnalysisResults::DT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac7294ba4e105807674fe3a394437fcc1">llvm::getLoopPassPreservedAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#accc0fffa89a787bcc12e5db7a603006c">llvm::LoopNest::getParent</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#aa09379aa4435be95eb717dd9b5d8b4c5">llvm::LoopStandardAnalysisResults::LI</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a124376878e24aef4252795ba9fea420f">llvm::LoopStandardAnalysisResults::SE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a3444a9359f5f17f1694f82c41d5fd574">llvm::LoopStandardAnalysisResults::TTI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OptLevel {#a6fd06c53da7f7208659305a477f5af8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::LoopUnrollAndJamPass::OptLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollandjampass-h">LoopUnrollAndJamPass.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollandjampass-h">LoopUnrollAndJamPass.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp">LoopUnrollAndJamPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
