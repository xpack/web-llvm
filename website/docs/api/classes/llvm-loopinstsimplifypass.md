---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopinstsimplifypass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoopInstSimplifyPass` Class

<p>Performs <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Inst Simplify <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopInstSimplifyPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopinstsimplify-h">llvm/Transforms/Scalar/LoopInstSimplify.h</a>"
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e829edc978ccb3a88ff5532faf75879">run</a> (Loop &amp;L, LoopAnalysisManager &amp;AM, LoopStandardAnalysisResults &amp;AR, LPMUpdater &amp;U)</td>
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

<p>Performs <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Inst Simplify <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopinstsimplify-h">LoopInstSimplify.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### run() {#a3e829edc978ccb3a88ff5532faf75879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses LoopInstSimplifyPass::run (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults">LoopStandardAnalysisResults</a> &amp; AR, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopinstsimplify-h">LoopInstSimplify.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp">LoopInstSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a902b4712394a3b3450893634b3302893">llvm::LoopStandardAnalysisResults::AC</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#aaa96df870a1b3d7ffc56bec3eb0b0cff">llvm::LoopStandardAnalysisResults::DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac7294ba4e105807674fe3a394437fcc1">llvm::getLoopPassPreservedAnalyses</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#aa09379aa4435be95eb717dd9b5d8b4c5">llvm::LoopStandardAnalysisResults::LI</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a1cfb392c267da10531478c2f42baa603">llvm::LoopStandardAnalysisResults::MSSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a9e363c1eaf112166372e2d52704981fb">llvm::LoopStandardAnalysisResults::TLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a88b10d37f671e58cf138ac84a8257c17">llvm::MemorySSA::verifyMemorySSA</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopinstsimplify-h">LoopInstSimplify.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp">LoopInstSimplify.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
