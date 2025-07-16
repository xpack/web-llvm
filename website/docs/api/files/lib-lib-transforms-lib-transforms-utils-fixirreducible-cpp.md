---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `FixIrreducible.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/fixirreducible-h">llvm/Transforms/Utils/FixIrreducible.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cycleanalysis-h">llvm/Analysis/CycleAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">llvm/Analysis/DomTreeUpdater.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/utils-h">llvm/Transforms/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/controlflowutils-h">llvm/Transforms/Utils/ControlFlowUtils.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-fixirreducible-cpp-">anonymous{FixIrreducible.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-fixirreducible-cpp-/fixirreducible">FixIrreducible</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e827d2427f074f00ef13822890ca20">INITIALIZE_PASS_BEGIN</a> (FixIrreducible, "fix-irreducible", "Convert irreducible control-flow into natural loops", false, false) INITIALIZE_PASS_END(FixIrreducible</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a86b29362e5d8fbb0d516610e4f988b5e">fix</a> Convert <a href="#a5be285cef1cd1bde84856a9672ef48c0">irreducible</a> control flow into natural static false void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547e6acb76d014207c771774f809696a">reconnectChildLoops</a> (LoopInfo &amp;LI, Loop *ParentLoop, Loop *NewLoop, BasicBlock *OldHeader)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e621d4f38dd96314d6a1250d475951f">updateLoopInfo</a> (LoopInfo &amp;LI, Cycle &amp;C, ArrayRef&lt; BasicBlock * &gt; GuardBlocks)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad914c82e07de4044a3314a5d03c5b85a">fixIrreducible</a> (Cycle &amp;C, CycleInfo &amp;CI, DominatorTree &amp;DT, LoopInfo *LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ef8dedf48f2174b2722fdc1d262dad">FixIrreducibleImpl</a> (Function &amp;F, CycleInfo &amp;CI, DominatorTree &amp;DT, LoopInfo *LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a86b29362e5d8fbb0d516610e4f988b5e">fix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be285cef1cd1bde84856a9672ef48c0">irreducible</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a86b29362e5d8fbb0d516610e4f988b5e">fix</a> Convert <a href="#a5be285cef1cd1bde84856a9672ef48c0">irreducible</a> control flow into natural</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e87214588b88fb4aad766771aa467b">loops</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a86b29362e5d8fbb0d516610e4f988b5e">fix</a> Convert <a href="#a5be285cef1cd1bde84856a9672ef48c0">irreducible</a> control flow into natural</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768e2cb5858b48ea9ffb8c00f80b8197">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"fix-irreducible"</td>
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

### fixIrreducible() {#ad914c82e07de4044a3314a5d03c5b85a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool fixIrreducible (<a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb65a469d6a946a06be1765b1d8b5b4">CycleInfo</a> &amp; CI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp">FixIrreducible.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo/#a153679add0de628fdec2583dfd0769f2">llvm::GenericCycleInfo&lt; ContextT &gt;::addBlockToCycle</a>, <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/#aef132a79cbc9fc2395fe9696dd654f8e">llvm::ControlFlowHub::addBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a9c50882381abd28ec385bec769b8928b">llvm::SetVector&lt; T, Vector, Set, N &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/#a14e3b2ee272be893fb7d474a5530705c">llvm::ControlFlowHub::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo/#a553e81871c23e0e1a1048884dc38df39">llvm::GenericCycleInfo&lt; ContextT &gt;::print</a>, <a href="#a9e621d4f38dd96314d6a1250d475951f">updateLoopInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a1f08f2925fec05b265e540d29066b9c8">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::verify</a>.</p>


<p>Referenced by <a href="#ab8ef8dedf48f2174b2722fdc1d262dad">FixIrreducibleImpl</a>.</p>

</div>
</div>

### FixIrreducibleImpl() {#ab8ef8dedf48f2174b2722fdc1d262dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FixIrreducibleImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb65a469d6a946a06be1765b1d8b5b4">CycleInfo</a> &amp; CI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI)</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp">FixIrreducible.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad914c82e07de4044a3314a5d03c5b85a">fixIrreducible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2436f015662138f27cf2be735ad740e3">llvm::hasOnlySimpleTerminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo/#a1d952f103899496db10f31e9ab5661b4">llvm::GenericCycleInfo&lt; ContextT &gt;::toplevel_cycles</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo/#a0bdd1c5ece7d11c39a095191fd9746ac">llvm::GenericCycleInfo&lt; ContextT &gt;::verify</a> and <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a17a8f7aba5cca5c7f9faa779a3c4bc37">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::verify</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/fixirreduciblepass/#a61707c67652fa7e327bb8ac607164e09">llvm::FixIrreduciblePass::run</a> and <a href="/web-llvm/docs/api/structs/anonymous-fixirreducible-cpp-/fixirreducible/#a8d14bed3c1d3c5f9cd62aa160cc02d70">anonymous{FixIrreducible.cpp}::FixIrreducible::runOnFunction</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a67e827d2427f074f00ef13822890ca20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (FixIrreducible, "fix-irreducible", "Convert <a href="#a5be285cef1cd1bde84856a9672ef48c0">irreducible</a> control-flow into natural loops", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp">FixIrreducible.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### reconnectChildLoops() {#a547e6acb76d014207c771774f809696a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fix Convert irreducible control flow into natural static false void reconnectChildLoops (<a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * ParentLoop, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * NewLoop, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OldHeader)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp">FixIrreducible.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a547e6acb76d014207c771774f809696a">reconnectChildLoops</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a547e6acb76d014207c771774f809696a">reconnectChildLoops</a> and <a href="#a9e621d4f38dd96314d6a1250d475951f">updateLoopInfo</a>.</p>

</div>
</div>

### updateLoopInfo() {#a9e621d4f38dd96314d6a1250d475951f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateLoopInfo (<a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; GuardBlocks)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp">FixIrreducible.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a1e4ac7b073d744d43f3cb1a3660c03c3">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::addTopLevelLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a5a0ae49bf720341774a25029fd23bf59">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::AllocateLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a97de9fb6fdce68e4e31300fcf0e5a20c">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::changeLoopFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a>, <a href="#a547e6acb76d014207c771774f809696a">reconnectChildLoops</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a2896fd505fc6356f4ad5b53bb5001a39">llvm::LoopBase&lt; BlockT, LoopT &gt;::verifyLoop</a>.</p>


<p>Referenced by <a href="#ad914c82e07de4044a3314a5d03c5b85a">fixIrreducible</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#a768e2cb5858b48ea9ffb8c00f80b8197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fix Convert irreducible control flow into natural false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp">FixIrreducible.cpp</a>.</p>

</div>
</div>

### irreducible {#a5be285cef1cd1bde84856a9672ef48c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fix irreducible</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp">FixIrreducible.cpp</a>.</p>

</div>
</div>

### loops {#ab9e87214588b88fb4aad766771aa467b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fix Convert irreducible control flow into natural loops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp">FixIrreducible.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"fix-irreducible"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp">FixIrreducible.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
