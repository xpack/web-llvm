---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `UnifyLoopExits.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/unifyloopexits-h">llvm/Transforms/Utils/UnifyLoopExits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">llvm/Analysis/DomTreeUpdater.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/utils-h">llvm/Transforms/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/controlflowutils-h">llvm/Transforms/Utils/ControlFlowUtils.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-unifyloopexits-cpp-">anonymous{UnifyLoopExits.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-unifyloopexits-cpp-/unifyloopexitslegacypass">UnifyLoopExitsLegacyPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af789701014d452a6764baa46d6afa7e0">INITIALIZE_PASS_BEGIN</a> (UnifyLoopExitsLegacyPass, "unify-loop-exits", "Fixup each natural loop to have a single exit block", false, false) INITIALIZE_PASS_END(UnifyLoopExitsLegacyPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unify loop <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> each natural loop to have a single exit static false void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaff4f2206ebf29a0a8e629835ca1973">restoreSSA</a> (const DominatorTree &amp;DT, const Loop *L, SmallVectorImpl&lt; BasicBlock * &gt; &amp;Incoming, BasicBlock *LoopExitBlock)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91d961bc77edfba4fb721c6637c0c6ed">unifyLoopExits</a> (DominatorTree &amp;DT, LoopInfo &amp;LI, Loop *L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef10c1e2da67a156642c39ae5ceb33ca">runImpl</a> (LoopInfo &amp;LI, DominatorTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc03799e313e0e756a4051a35d26b1e3">MaxBooleansInControlFlowHub</a>("max-booleans-in-control-flow-hub", cl::init(32), cl::Hidden, cl::desc("Set the maximum number of outgoing blocks for using a boolean " "value to record the exiting block in the ControlFlowHub."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unify loop</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00410754617181d2a4693f9763c488ea">exits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unify loop <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> each natural loop to have a single exit</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4741a07a0e5675f89cfed122008e0a76">block</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unify loop <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> each natural loop to have a single exit</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889d7f30f6c65b4b325c18f14f4272c3">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"unify-loop-exits"</td>
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

### INITIALIZE\_PASS\_BEGIN() {#af789701014d452a6764baa46d6afa7e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (UnifyLoopExitsLegacyPass, "unify-loop-exits", "Fixup each natural loop to have a single exit block", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp">UnifyLoopExits.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### restoreSSA() {#aaaff4f2206ebf29a0a8e629835ca1973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unify loop Fixup each natural loop to have a single exit static false void restoreSSA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Incoming, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopExitBlock)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp">UnifyLoopExits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> and <a href="#aaaff4f2206ebf29a0a8e629835ca1973">restoreSSA</a>.</p>


<p>Referenced by <a href="#aaaff4f2206ebf29a0a8e629835ca1973">restoreSSA</a> and <a href="#a91d961bc77edfba4fb721c6637c0c6ed">unifyLoopExits</a>.</p>

</div>
</div>

### runImpl() {#aef10c1e2da67a156642c39ae5ceb33ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool runImpl (<a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp">UnifyLoopExits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a8a10d542acf3418b2a5bfefb351829c0">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopsInPreorder</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a> and <a href="#a91d961bc77edfba4fb721c6637c0c6ed">unifyLoopExits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-unifyloopexits-cpp-/unifyloopexitslegacypass/#a414a4f7334ec69f73a1b1cbe9de8f52a">anonymous{UnifyLoopExits.cpp}::UnifyLoopExitsLegacyPass::runOnFunction</a>.</p>

</div>
</div>

### unifyLoopExits() {#a91d961bc77edfba4fb721c6637c0c6ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool unifyLoopExits (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp">UnifyLoopExits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/#aef132a79cbc9fc2395fe9696dd654f8e">llvm::ControlFlowHub::addBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/#a14e3b2ee272be893fb7d474a5530705c">llvm::ControlFlowHub::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#acc03799e313e0e756a4051a35d26b1e3">MaxBooleansInControlFlowHub</a>, <a href="#aaaff4f2206ebf29a0a8e629835ca1973">restoreSSA</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a1f08f2925fec05b265e540d29066b9c8">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::verify</a> and <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a17a8f7aba5cca5c7f9faa779a3c4bc37">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::verify</a>.</p>


<p>Referenced by <a href="#aef10c1e2da67a156642c39ae5ceb33ca">runImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### block {#a4741a07a0e5675f89cfed122008e0a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unify loop Fixup each natural loop to have a single exit block</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp">UnifyLoopExits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a27aafcff5a8ed8f91ea6b53ac93a0fbf">_rpmalloc_aligned_reallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a0a241af7d6b9c4eb88bc5480f3fa10d1">_rpmalloc_allocate_from_heap_fallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6cc5147be3d12c47a533a9cd14e36801">_rpmalloc_deallocate_defer_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a6c1102ef8a3812f1098cad573ea7794e">_rpmalloc_deallocate_direct_small_or_medium</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a9942f9f958830d9f83ecf67b85de3ea4">_rpmalloc_reallocate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#aa776faada2c6d5b7edda58a3a1d701c4">_rpmalloc_span_finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a64debeb0ce94e6048da7c8fad19b1d31">_rpmalloc_span_initialize_new</a>, <a href="/web-llvm/docs/api/classes/llvm/spirv/convergenceregionanalyzer/#aad660d1ec071e1945c2b96bfe4c3704b">llvm::SPIRV::ConvergenceRegionAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/classes/llvm/genericssacontext/#a7b38e4e9aa6fc7cbfaca50399fae5778">llvm::GenericSSAContext&lt; Function &gt;::appendBlockDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/genericssacontext/#a11d0bd29c71e5e0f4f886d9a5d038f6d">llvm::GenericSSAContext&lt; Function &gt;::appendBlockDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/genericssacontext/#a0af40690ef913f659af917ec7e5d42b3">llvm::GenericSSAContext&lt; Function &gt;::appendBlockTerms</a>, <a href="/web-llvm/docs/api/classes/llvm/genericssacontext/#a4848ac5fdb1eb954bb63b84200386e0b">llvm::GenericSSAContext&lt; Function &gt;::appendBlockTerms</a>, <a href="/web-llvm/docs/api/classes/llvm/bcblockraii/#a9ba7c80549bd92ba1fd19a9e769778bd">llvm::BCBlockRAII::BCBlockRAII</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#ae806b06af6fd96ce3036e82a66a972fc">blake3_compress_in_place</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a3e2dd97881e59bb3ebf430b782fd03fb">blake3_compress_in_place_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a5f1cca60c3c099efd97cafcc542eb4e7">blake3_compress_in_place_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#aefa24b59e3f43932466c584ff493fab2">blake3_compress_in_place_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c/#aff9ac9dc003026e4bef488ddaa2d4beb">blake3_compress_in_place_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#aa7ad14d63d0421eb5638eac60a4faff2">blake3_compress_xof</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a8c9bce27c4efaff2266c650c111ac5e5">blake3_compress_xof_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a9b4b1cdf0d88ad62854fd20cc10c1558">blake3_compress_xof_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#ae6d20f2ff68c8e935e628a486b9d842b">blake3_compress_xof_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c/#aab2f2721e67a4f038a36304fe6bac2bb">blake3_compress_xof_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c/#ab9db1c5b05bdca5437891512850ef529">blake3_hash4_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ac8dde7c610d47213bd49d710016f9476">free_list_pop</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovblock/#a1676ff1758dd5d5b69de46336cc186b0">llvm::GCOVBlock::getCyclesCount</a>, <a href="/web-llvm/docs/api/classes/llvm/genericuniformityanalysisimpl/#a9871d6f69d777f1be8a101e229dfdd6a">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::initialize</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantexpressions/#gaa025b4042992fcb4ee0a8495cebb32ba">LLVM_ATTRIBUTE_C_DEPRECATED</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructionterminator/#ga56edf2c7af4012a3a4eea565ae1cd84b">LLVMSetSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0fb8691f907fe586830601d486049e6e">make_output</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#ab18874614dade172d2726abc3e88d480">parent_output</a>, <a href="/web-llvm/docs/api/classes/llvm/genericssacontext/#a662a00e83eaad4940874eaa0840ac142">llvm::GenericSSAContext&lt; Function &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/genericuniformityanalysisimpl/#aaa981d51f7c517dff299c1aec5a433e9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#ae572e25a23de1a9793b4e5b1ec0550b1">rpaligned_calloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a5627c7b5f1dc087ce096df1c787b5ecf">rpcalloc</a>.</p>

</div>
</div>

### exits {#a00410754617181d2a4693f9763c488ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unify loop exits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp">UnifyLoopExits.cpp</a>.</p>

</div>
</div>

### false {#a889d7f30f6c65b4b325c18f14f4272c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unify loop Fixup each natural loop to have a single exit false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp">UnifyLoopExits.cpp</a>.</p>

</div>
</div>

### MaxBooleansInControlFlowHub {#acc03799e313e0e756a4051a35d26b1e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxBooleansInControlFlowHub("max-booleans-in-control-flow-hub", cl::init(32), cl::Hidden, cl::desc("Set the maximum number of outgoing blocks for using a boolean " "value to record the exiting block in the ControlFlowHub."))</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp">UnifyLoopExits.cpp</a>.</p>


<p>Referenced by <a href="#a91d961bc77edfba4fb721c6637c0c6ed">unifyLoopExits</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"unify-loop-exits"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp">UnifyLoopExits.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
