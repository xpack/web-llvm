---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/looptermfoldpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopTermFoldPass` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LoopTermFoldPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looptermfold-h">llvm/Transforms/Scalar/LoopTermFold.h</a>"
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abefaee9143bf56e20b254a2f9a1bae56">run</a> (Loop &amp;L, LoopAnalysisManager &amp;AM, LoopStandardAnalysisResults &amp;AR, LPMUpdater &amp;U)</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looptermfold-h">LoopTermFold.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### run() {#abefaee9143bf56e20b254a2f9a1bae56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses LoopTermFoldPass::run (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults">LoopStandardAnalysisResults</a> &amp; AR, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looptermfold-h">LoopTermFold.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp">LoopTermFold.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#a1258a1ff55557c27684010ebd7283712">llvm::PreservedAnalyses::all</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#aaa96df870a1b3d7ffc56bec3eb0b0cff">llvm::LoopStandardAnalysisResults::DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac7294ba4e105807674fe3a394437fcc1">llvm::getLoopPassPreservedAnalyses</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#aa09379aa4435be95eb717dd9b5d8b4c5">llvm::LoopStandardAnalysisResults::LI</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a1cfb392c267da10531478c2f42baa603">llvm::LoopStandardAnalysisResults::MSSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a124376878e24aef4252795ba9fea420f">llvm::LoopStandardAnalysisResults::SE</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a9e363c1eaf112166372e2d52704981fb">llvm::LoopStandardAnalysisResults::TLI</a> and <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a3444a9359f5f17f1694f82c41d5fd574">llvm::LoopStandardAnalysisResults::TTI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looptermfold-h">LoopTermFold.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp">LoopTermFold.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
