---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/simpleloopunswitchpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SimpleLoopUnswitchPass` Class Reference

<p>This pass transforms loops that contain branches or switches on loop- invariant conditions to have multiple loops. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SimpleLoopUnswitchPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">llvm/Transforms/Scalar/SimpleLoopUnswitch.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed6976cf8c41b6edc04bdc7514ab34c">SimpleLoopUnswitchPass</a> (bool NonTrivial=false, bool Trivial=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7088b7b5c8bd069497f13e3e1990eff">run</a> (Loop &amp;L, LoopAnalysisManager &amp;AM, LoopStandardAnalysisResults &amp;AR, LPMUpdater &amp;U)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a200a7ffd107aee97365d96726a222fc0">printPipeline</a> (raw_ostream &amp;OS, function_ref&lt; StringRef(StringRef)&gt; MapClassName2PassName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c54dc434be2c8dce52bac93cb12383e">NonTrivial</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a380570856b42abd7bec8beb65986d3dd">Trivial</a></td>
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

<p>This pass transforms loops that contain branches or switches on loop- invariant conditions to have multiple loops.</p>


<p>For example, it turns the left into the right code:</p>


<p>for (...) if (lic) A for (...) if (lic) A; B; C B else C for (...) A; C</p>


<p>This can increase the size of the code exponentially (doubling it every time a loop is unswitched) so we only unswitch if the resultant code will be smaller than a threshold.</p>


<p>This pass expects LICM to be run before it to hoist invariant conditions out of the loop, to make the unswitching opportunity obvious.</p>


<p>There is a taxonomy of unswitching that we use to classify different forms of this transformaiton:</p>


<ul class="doxyList ">
<li>Trival unswitching: this is when the condition can be unswitched without cloning any code from inside the loop. A non-trivial unswitch requires code duplication.</li>
<li>Full unswitching: this is when the branch or switch is completely moved from inside the loop to outside the loop. Partial unswitching removes the branch from the clone of the loop but must leave a (somewhat simplified) branch in the original loop. While theoretically partial unswitching can be done for switches, the requirements are extreme - we need the loop invariant input to the switch to be sufficient to collapse to a single successor in each clone.</li>
</ul>

<p>This pass always does trivial, full unswitching for both branches and switches. For branches, it also always does trivial, partial unswitching.</p>


<p>If enabled (via the constructor's <span class="doxyComputerOutput">NonTrivial</span> parameter), this pass will additionally do non-trivial, full unswitching for branches and switches, and will do non-trivial, partial unswitching for branches.</p>


<p>Because partial unswitching of switches is extremely unlikely to be possible in practice and significantly complicates the implementation, this pass does not currently implement that in any mode.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">SimpleLoopUnswitch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SimpleLoopUnswitchPass() {#a0ed6976cf8c41b6edc04bdc7514ab34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SimpleLoopUnswitchPass::SimpleLoopUnswitchPass (bool NonTrivial=false, bool Trivial=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">SimpleLoopUnswitch.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printPipeline() {#a200a7ffd107aee97365d96726a222fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SimpleLoopUnswitchPass::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; MapClassName2PassName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">SimpleLoopUnswitch.h</a>, definition at line 3718 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>Reference <a href="#a200a7ffd107aee97365d96726a222fc0">printPipeline</a>.</p>


<p>Referenced by <a href="#a200a7ffd107aee97365d96726a222fc0">printPipeline</a>.</p>

</div>
</div>

### run() {#ae7088b7b5c8bd069497f13e3e1990eff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses SimpleLoopUnswitchPass::run (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults">LoopStandardAnalysisResults</a> &amp; AR, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">SimpleLoopUnswitch.h</a>, definition at line 3682 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#abd7da877be8576011299f4fcaaf299be">llvm::LoopStandardAnalysisResults::AA</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a902b4712394a3b3450893634b3302893">llvm::LoopStandardAnalysisResults::AC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a0fbd3535a2ca32937aebf75738e854fb">llvm::LoopStandardAnalysisResults::BFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#aaa96df870a1b3d7ffc56bec3eb0b0cff">llvm::LoopStandardAnalysisResults::DT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac7294ba4e105807674fe3a394437fcc1">llvm::getLoopPassPreservedAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#aa09379aa4435be95eb717dd9b5d8b4c5">llvm::LoopStandardAnalysisResults::LI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a1cfb392c267da10531478c2f42baa603">llvm::LoopStandardAnalysisResults::MSSA</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a124376878e24aef4252795ba9fea420f">llvm::LoopStandardAnalysisResults::SE</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#a3444a9359f5f17f1694f82c41d5fd574">llvm::LoopStandardAnalysisResults::TTI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a1f08f2925fec05b265e540d29066b9c8">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::verify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a88b10d37f671e58cf138ac84a8257c17">llvm::MemorySSA::verifyMemorySSA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NonTrivial {#a7c54dc434be2c8dce52bac93cb12383e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SimpleLoopUnswitchPass::NonTrivial</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">SimpleLoopUnswitch.h</a>.</p>

</div>
</div>

### Trivial {#a380570856b42abd7bec8beb65986d3dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SimpleLoopUnswitchPass::Trivial</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">SimpleLoopUnswitch.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/simpleloopunswitch-h">SimpleLoopUnswitch.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp">SimpleLoopUnswitch.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
