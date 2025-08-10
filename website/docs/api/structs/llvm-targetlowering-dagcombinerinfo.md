---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetlowering/dagcombinerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DAGCombinerInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::TargetLowering::DAGCombinerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d178d0480903c77340513530c08f7e">DAGCombinerInfo</a> (SelectionDAG &amp;dag, CombineLevel level, bool cl, void *dc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac79f060cd8d4b63fc6d682c076cbeec0">isBeforeLegalize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06663f3ab188bef45b0f669c9f109df5">isBeforeLegalizeOps</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2030eb1014aca2732ca4ecfb9ae4b5a0">isAfterLegalizeDAG</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2337b8ef923079097d8c6de562503ffb">getDAGCombineLevel</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa571393f242ebc7da5682b7e85394d60">isCalledByLegalizer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3e1453357b1b1cd870a4ac3528f918">AddToWorklist</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff1fcbcf8e82995a72f1efd2d62ec11">CombineTo</a> (SDNode *N, ArrayRef&lt; SDValue &gt; To, bool AddTo=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf6bcad9fbd93aa99faf16377831feb">CombineTo</a> (SDNode *N, SDValue Res, bool AddTo=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed65892d0b297e512746d6ef74debb7">CombineTo</a> (SDNode *N, SDValue Res0, SDValue Res1, bool AddTo=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf156bc8dfc3e92cd63aee7192c3dea8">recursivelyDeleteUnusedNodes</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeecdb6a29a24d717a83fc1c948e00d98">CommitTargetLoweringOpt</a> (const TargetLoweringOpt &amp;TLO)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a037a95334e73e5362be577bd599f52a8">DC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68215eadc6b09f074264c05ee9b06ac8">Level</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0fcb9b8852da7e7864796bdac485bfe">CalledByLegalizer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf37bd7e831bdb2a5c9da8d63f843101">DAG</a></td>
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


<p>Definition at line 4228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DAGCombinerInfo() {#ac7d178d0480903c77340513530c08f7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLowering::DAGCombinerInfo::DAGCombinerInfo (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; dag, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7a">CombineLevel</a> level, bool cl, void * dc)</td>
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



<p>Definition at line 4236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="#ab0fcb9b8852da7e7864796bdac485bfe">CalledByLegalizer</a>, <a href="#acf37bd7e831bdb2a5c9da8d63f843101">DAG</a>, <a href="#a037a95334e73e5362be577bd599f52a8">DC</a> and <a href="#a68215eadc6b09f074264c05ee9b06ac8">Level</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddToWorklist() {#a9e3e1453357b1b1cd870a4ac3528f918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetLowering::DAGCombinerInfo::AddToWorklist (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 4245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>, definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a7c431da15318b73b5a0112e2d2d91f87">anonymous{DAGCombiner.cpp}::DAGCombiner::DAGCombiner</a>, <a href="#a037a95334e73e5362be577bd599f52a8">DC</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afab7e380356e4b22d23f87fa2f45daf9">combineBT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a24cdc31f225e6b17b30c139085b064">combineCVTPH2PS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a6a2af7640ee8f9e66287e024d0f6b8">combineMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9ac1db32c7172ebb71d45a6ece209b53">combineVEXTRACT_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae6535f37686895d8ab294ce06ffe2f15">combineX86GatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#ab360f775d124b3f4976cc31616c0e357">distributeOpThroughSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a98d5db97af4726044d334c4a21cc9bd2">llvm::AMDGPUTargetLowering::foldFreeOpFromSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd8034cb60968e67a0b01c4ae93ada12">PerformBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6913e341612419ecb5b860b6759b929c">llvm::AMDGPUTargetLowering::performFNegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57984ebd9271c38d02eb92b050f5bcee">PerformInsertEltCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a3e110576778e9ccf929885efddeea4aa">llvm::AMDGPUTargetLowering::performMulhsCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a09d46d8519c83130e03376d0d2e0008a">llvm::AMDGPUTargetLowering::performMulhuCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2a6ac5eb53f29d680d116a97de4e53a8">llvm::AMDGPUTargetLowering::splitBinaryBitConstantOpImpl</a>.</p>

</div>
</div>

### CombineTo() {#adff1fcbcf8e82995a72f1efd2d62ec11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue TargetLowering::DAGCombinerInfo::CombineTo (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; To, bool AddTo=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 4246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>, definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a7c431da15318b73b5a0112e2d2d91f87">anonymous{DAGCombiner.cpp}::DAGCombiner::DAGCombiner</a>, <a href="#a037a95334e73e5362be577bd599f52a8">DC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2ef9bba3be5001d1d80c474dd335dff7">combineADC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1b64f17c84bc615a735f48746a0740">combineBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a69c29dade9c2c83e9928f92e0e6452f0">combineCVTP2I_CVTTP2I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a24cdc31f225e6b17b30c139085b064">combineCVTPH2PS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2a2b06cd0043981c801d852ace83fded">combineMaskedLoadConstantMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad7c52d56e60df127f4f9a429a5455590">combineSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abb2988152a6f0b53e8da73bd75915365">combineX86AddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0185d63d243a248f5bc69dfc943c88a">combineX86INT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f4cf2e3dcecef6763caca7fd8949d76">combineX86SubCmpForFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a108b26123f976ad2ab078287e4be83ef">combineZext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8e48c97fe5cefbf70aa4e9fa0138c99d">PerformAddcSubcCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6c02410f9bb19b5b6eb61c9711ae4156">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2a5ac33b69bb7d7687d12dc0dffe9f08">performBRCONDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4a73ebacb24d087b199805b801f61507">performFlagSettingCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae57c77c91d8ca534534565c26afee2da">PerformMULCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae60d2a6d5da1fa05bb8e59e09fb72612">llvm::AMDGPUTargetLowering::performMulLoHiCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a963a08f31bbf8cb9396ff5214bc7ae26">PerformORCombineToBFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a72895c7f66e26be35e106221a2ab26ae">performSignExtendInRegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53300f43eec34fc01f85c153445e4a37">reduceMaskedLoadToScalarLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4340bab6e118d0614449e74a779b30c">tryCombineWhileLo</a>.</p>

</div>
</div>

### CombineTo() {#a7cf6bcad9fbd93aa99faf16377831feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue TargetLowering::DAGCombinerInfo::CombineTo (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Res, bool AddTo=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 4247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>, definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a7c431da15318b73b5a0112e2d2d91f87">anonymous{DAGCombiner.cpp}::DAGCombiner::DAGCombiner</a>, <a href="#a037a95334e73e5362be577bd599f52a8">DC</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### CombineTo() {#a9ed65892d0b297e512746d6ef74debb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue TargetLowering::DAGCombinerInfo::CombineTo (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Res0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Res1, bool AddTo=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 4248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>, definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a7c431da15318b73b5a0112e2d2d91f87">anonymous{DAGCombiner.cpp}::DAGCombiner::DAGCombiner</a>, <a href="#a037a95334e73e5362be577bd599f52a8">DC</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### CommitTargetLoweringOpt() {#aeecdb6a29a24d717a83fc1c948e00d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetLowering::DAGCombinerInfo::CommitTargetLoweringOpt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt">TargetLoweringOpt</a> &amp; TLO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 4252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>, definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a7c431da15318b73b5a0112e2d2d91f87">anonymous{DAGCombiner.cpp}::DAGCombiner::DAGCombiner</a> and <a href="#a037a95334e73e5362be577bd599f52a8">DC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af4aeb38e252532a5362ac68998d0af93">performTBISimplification</a>.</p>

</div>
</div>

### getDAGCombineLevel() {#a2337b8ef923079097d8c6de562503ffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CombineLevel llvm::TargetLowering::DAGCombinerInfo::getDAGCombineLevel ()</td>
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



<p>Definition at line 4242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="#a68215eadc6b09f074264c05ee9b06ac8">Level</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#afcd4be086e69b1f75ca347ec794dea3b">llvm::AMDGPUTargetLowering::combineFMinMaxLegacyImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### isAfterLegalizeDAG() {#a2030eb1014aca2732ca4ecfb9ae4b5a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::DAGCombinerInfo::isAfterLegalizeDAG ()</td>
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



<p>Definition at line 4241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7aa7fbaa966e5d5ac3bf03ba617b73bff5c">llvm::AfterLegalizeDAG</a> and <a href="#a68215eadc6b09f074264c05ee9b06ac8">Level</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa9fca969da56000134dc248f8d676e3a">combineExtractFromVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a42586d078a0c852f7571d5d4fb0daa04">llvm::VETargetLowering::combineSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7094504ff72e8db0894faac2216aa00a">llvm::VETargetLowering::combineSelectCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b92776e41d73c3b5d4f1c5712f212c7">combineShiftRightLogical</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#acbbd968d4e7364fbdbc6af715f0768e6">llvm::VETargetLowering::combineTRUNCATE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a611e5eca9f470030689ec3f7d71c8e20">combineVectorInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c93589d74f9163f56f3f1200bcf9ad6">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a700b0db686d16d5c35f6dcf63659fefb">PerformBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4b8e4441770569e02f67db99773afff0">performCSELCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08e1234497dd7fb39211e46523f02459">performDUPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a589928ae94c1e14b50e374c6a1146c60">llvm::ARMTargetLowering::PerformMVEExtCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a35a55a457bfc044d33bdeb4811532531">llvm::ARMTargetLowering::PerformMVETruncCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4798b448246e74d657035d49de0e648d">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abcaf1212adde88b8addaf1060c459819">performSetccMergeZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d8e109ce3c796c31524f5a06dd745ac">performSVEMulAddSubCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a48a325f68cd666c7ee8808c5e224192c">performTruncateCombine</a>.</p>

</div>
</div>

### isBeforeLegalize() {#ac79f060cd8d4b63fc6d682c076cbeec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::DAGCombinerInfo::isBeforeLegalize ()</td>
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



<p>Definition at line 4239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7aa9386e6e4a4c86dabf136bc0fc9f6cf3b">llvm::BeforeLegalizeTypes</a> and <a href="#a68215eadc6b09f074264c05ee9b06ac8">Level</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad1b9f6a1979dddff5b170976bfd53c52">CombineANDShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acb27133587f777e5b89572d1c62aeac9">combineBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0fb4a30e359345f1f6c967488cd37ab">combineCMov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ed3d44a545e6f543e76cf58245d1f19">combineINTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac13cf93d084e804ad88b2b1dbef0c618">combineINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a84473a3a9dca82077491c2b25bc82837">combineINTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a027102ec674270eecc2a1a6ec8588e44">combineOrCmpEqZeroToCtlzSrl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a38a4767fc581ef400cbef34ac25d9f6c">expandMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6e9a1f8a595e1e9b2bb022451203ccc2">legalizeScatterGatherIndexType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a683c927bf72b145ee57c5c91be458df5">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad951ca5aa57e9482c9d5edfcf7cd1e46">PerformADDECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afc0543ffe712dea27f610e198260fc8b">performANDSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aeeb9c744f747cad16a3508441ea4722f">performBitcastCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9930ac25c4e4a7ff566e6301bade01e7">llvm::SITargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a77e5d35ccfe68c41092edc168cfb393e">performFirstTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a076775accdfd3a4707279b9636a4986b">performLastTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad50cb0376d697cd4ca4f6469bd6bd25c">performMaskedGatherScatterCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae57c77c91d8ca534534565c26afee2da">PerformMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a7d7ccddfc054f29d7bac995d70adb6e8">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa26d28bee621b8087f1521482dc3b825">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a391272ef81598a4a25763b2f35809615">PerformShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad8eb465f75fcd8db9f348cbbb24194c1">PerformSHLSimplify</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af4aeb38e252532a5362ac68998d0af93">performTBISimplification</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a49ed4ed152a2f6e8533ccac1deb10ca0">performVecReduceBitwiseCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7010007dcac40b070c67842b07a3845b">PerformVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ade0519245a3e86cb20548e200f65863e">scalarizeExtEltFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4340bab6e118d0614449e74a779b30c">tryCombineWhileLo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a05f57690dd5d9df763d5b75d14bc47fd">tryConvertSVEWideCompare</a>.</p>

</div>
</div>

### isBeforeLegalizeOps() {#a06663f3ab188bef45b0f669c9f109df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::DAGCombinerInfo::isBeforeLegalizeOps ()</td>
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



<p>Definition at line 4240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa6d856e4879bb775617f8c3634773b7aa805f5e0d60c9ebc5b134bc9190569a50">llvm::AfterLegalizeVectorOps</a> and <a href="#a68215eadc6b09f074264c05ee9b06ac8">Level</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bd495ab23d43ebbe7e2d167103d8991">combineCastedMaskArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0fb4a30e359345f1f6c967488cd37ab">combineCMov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acfa813720f554bb68a6e8c5fdb870f4e">combineEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8dae5a29dc37de048a59e5bab5e30af2">combineFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0f13d1cf96cb32fba6d7ed4bd50ba5f">combineFMADDSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7a388b8e71542c8223c73a0d99691c71">combineFneg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ace3516d005e59a05c7b3ff975d063f23">combineINSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad7c52d56e60df127f4f9a429a5455590">combineSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c5c088223e73d71c8971f218db7985">combineToExtendBoolVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a321df2422ee45cfd96e738928fb178f7">combineXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a108b26123f976ad2ab078287e4be83ef">combineZext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a009e2b4ee04eedc57c666678f3e8ef1b">convertIntLogicToFPLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a830e51b63befaa067f822c088dd8833b">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa5a81f781f5f8796139dc49c03a44f02">performAddSubLongCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a14e0400deb65254122edb9e66d7bfcf7">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ada069dd931c50ac8a36e7da178768eeb">performBITREV_WCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#adf702ecb841f96bb48f48607543fe438">performCMovFPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a35eced9d40135070fe0e267898a9be26">llvm::HexagonTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4855642780c43259ecd18ea1bce3f0d3">performDivRemCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4765786a8a3de00320df895defc3250">performExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aab253557e698e63e5f05d8d9dd1d91f5">performExtractSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a3cb4731330867b7a71460d3f4daa752e">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a596ebebe073bb9a8568f898a4c2a06f6">performScalarToVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#add39487738bda59bdf85c85cb21b7e9a">performSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a6d21a959b41eb8c9bf28105d72fdbd43">performSHLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a24edd3104fd2ecba03dd7ca79104295d">performSHLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a72895c7f66e26be35e106221a2ab26ae">performSignExtendInRegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a5885643f7123cbe2d37a298d2551c9e1">performSRLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad19eb01bd287efda27e7bc5ba67cd144">performSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a9a5205b95660638f4c7d889f588251e7">performSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a267cdbd87c30830568cb74844b0e489c">performSVEAndCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af4aeb38e252532a5362ac68998d0af93">performTBISimplification</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac52bce44713165c831945178e1d5f696">performXorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa1aec95090eff4dcf6f51e0991ecc60e">tryCombineFixedPointConvert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adc515df450408045fd43835105d0c6ed">tryCombineLongOpWithDup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aaca8ed79bbc4fe36c9285bea57d72906">tryToReplaceScalarFPConversionWithSVE</a>.</p>

</div>
</div>

### isCalledByLegalizer() {#aa571393f242ebc7da5682b7e85394d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::DAGCombinerInfo::isCalledByLegalizer ()</td>
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



<p>Definition at line 4243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Reference <a href="#ab0fcb9b8852da7e7864796bdac485bfe">CalledByLegalizer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad1b9f6a1979dddff5b170976bfd53c52">CombineANDShift</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#afcd4be086e69b1f75ca347ec794dea3b">llvm::AMDGPUTargetLowering::combineFMinMaxLegacyImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a38a4767fc581ef400cbef34ac25d9f6c">expandMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a683c927bf72b145ee57c5c91be458df5">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae57c77c91d8ca534534565c26afee2da">PerformMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a391272ef81598a4a25763b2f35809615">PerformShiftCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7010007dcac40b070c67842b07a3845b">PerformVLDCombine</a>.</p>

</div>
</div>

### recursivelyDeleteUnusedNodes() {#abf156bc8dfc3e92cd63aee7192c3dea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLowering::DAGCombinerInfo::recursivelyDeleteUnusedNodes (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 4250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>, definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a7c431da15318b73b5a0112e2d2d91f87">anonymous{DAGCombiner.cpp}::DAGCombiner::DAGCombiner</a>, <a href="#a037a95334e73e5362be577bd599f52a8">DC</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a69c29dade9c2c83e9928f92e0e6452f0">combineCVTP2I_CVTTP2I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a24cdc31f225e6b17b30c139085b064">combineCVTPH2PS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0185d63d243a248f5bc69dfc943c88a">combineX86INT_TO_FP</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CalledByLegalizer {#ab0fcb9b8852da7e7864796bdac485bfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLowering::DAGCombinerInfo::CalledByLegalizer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#ac7d178d0480903c77340513530c08f7e">DAGCombinerInfo</a> and <a href="#aa571393f242ebc7da5682b7e85394d60">isCalledByLegalizer</a>.</p>

</div>
</div>

### DAG {#acf37bd7e831bdb2a5c9da8d63f843101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG&amp; llvm::TargetLowering::DAGCombinerInfo::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5425376fb8bb34c4f59a84a3ee70c790">AddCombineTo64bitMLAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af20aaa3827f50046072a07327167aee5">AddCombineTo64BitSMLAL16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a308239e88ecd5485cd72bf0f9ea300d7">AddCombineTo64bitUMAAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a37754d31c33565bdfd4903ab5e905a6a">AddCombineToVPADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5e2ad1fd4e6db82aeeb143564ecca7fd">AddCombineVUZPToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad1b9f6a1979dddff5b170976bfd53c52">CombineANDShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a04f37b0be46418aec20de01e0b389303">llvm::AMDGPUTargetLowering::combineFMinMaxLegacy</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#afcd4be086e69b1f75ca347ec794dea3b">llvm::AMDGPUTargetLowering::combineFMinMaxLegacyImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a38606383490cf2bbae95b6abec77ef5f">combineMADConstOne</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ab4702e14af79ed7cfb20ad593936460e">combineMulSelectConstOne</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a42586d078a0c852f7571d5d4fb0daa04">llvm::VETargetLowering::combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiisellowering-cpp/#a25b57e6a9269a29cbf98949ef2154842">combineSelectAndUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac23333bf0c5078b2f08c8e6e8509f0aa">combineSelectAndUse</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7094504ff72e8db0894faac2216aa00a">llvm::VETargetLowering::combineSelectCC</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#acbbd968d4e7364fbdbc6af715f0768e6">llvm::VETargetLowering::combineTRUNCATE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="#ac7d178d0480903c77340513530c08f7e">DAGCombinerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#ab360f775d124b3f4976cc31616c0e357">distributeOpThroughSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a98d5db97af4726044d334c4a21cc9bd2">llvm::AMDGPUTargetLowering::foldFreeOpFromSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6e9a1f8a595e1e9b2bb022451203ccc2">legalizeScatterGatherIndexType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aa435f2b01aca963d926bd31cd95e7f03">matchPERM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7ca64b74f25fc6b568b6446883e80379">PerformADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a683c927bf72b145ee57c5c91be458df5">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#af12579ae662d4b706778ef90b989d4fc">PerformADDCombineWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8e48c97fe5cefbf70aa4e9fa0138c99d">PerformAddcSubcCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9dbbe6acb79ab1e69a57634d58edcf4f">PerformAddeSubeCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afc2fb5809753e750c4245a785d06a754">performAddSubCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa5a81f781f5f8796139dc49c03a44f02">performAddSubLongCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6c02410f9bb19b5b6eb61c9711ae4156">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aec3ab4d2802494bdb8b2c3c5343f8254">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c93589d74f9163f56f3f1200bcf9ad6">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afc0543ffe712dea27f610e198260fc8b">performANDSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2c8bc97059759cb53b363069723311ef">llvm::AMDGPUTargetLowering::performAssertSZExtCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a9f32b61ceb023325bed9e826ade5d6e4">llvm::SparcTargetLowering::PerformBITCASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a51359c8ddfa214a514dbaab1b2ad2d29">PerformBITCASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aeeb9c744f747cad16a3508441ea4722f">performBitcastCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a700b0db686d16d5c35f6dcf63659fefb">PerformBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd8034cb60968e67a0b01c4ae93ada12">PerformBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a7f7b70914dc135fef1df446161972822">llvm::AMDGPUTargetLowering::performCtlz_CttzCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a960012b61a9977dc7c2d3af3943da953">llvm::AArch64TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8e96878324f2ca0f847e369f839cfd23">llvm::ARMTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a35eced9d40135070fe0e267898a9be26">llvm::HexagonTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a114238b6f08e91873cbd29bae3f069c3">llvm::LoongArchTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#a23c69653370af251e721680e01303967">llvm::MipsSETargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a6b3ae019ac2faf4a810a9b8fa80b747d">llvm::MipsTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9930ac25c4e4a7ff566e6301bade01e7">llvm::SITargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a0a91c61d0657477fe6583b566dca7fb7">llvm::X86TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08e1234497dd7fb39211e46523f02459">performDUPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a172a1f5983db0d10ae90c0d3f5beccdb">PerformExtractEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aefd957dcc1874b25b5b758324370d20d">performExtractVectorEltCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae0d935eaffbef9423e07ac82afb5eeb3">llvm::AMDGPUTargetLowering::performFAbsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2f6ed7bfd084f49c2369eec4c74495a3">performFADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a5d3cc5ce2199f840a6a9273c2285746e">PerformFADDCombineWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a77e5d35ccfe68c41092edc168cfb393e">performFirstTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4a73ebacb24d087b199805b801f61507">performFlagSettingCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6913e341612419ecb5b860b6759b929c">llvm::AMDGPUTargetLowering::performFNegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7fca4dc2eee895ba0f0cc33cd3ca6c4d">performFP_TO_INT_SATCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aed0a6ba299e2e585945210e2c39ac2ef">performFP_TO_INTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ade8c7b6c75d72baebf1ac6d244b9fca5">PerformHWLoopCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57984ebd9271c38d02eb92b050f5bcee">PerformInsertEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaece9d12c539bbab91aff76ea7e95096">PerformInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a42aa092f2811f72cad69b42cc2e4bb64">llvm::ARMTargetLowering::PerformIntrinsicCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af95a8dd3a4e9b403d57b68b5cbda46e6">performIntrinsicCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae4ec834dd7b4ce858321ecad900e9363">llvm::AMDGPUTargetLowering::performIntrinsicWOChainCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a076775accdfd3a4707279b9636a4986b">performLastTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4118089abb4cbadaf4b698cbbe05154f">PerformLOADCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5991e29bae68e989e978dc600f93b48e">performMemPairCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae57c77c91d8ca534534565c26afee2da">PerformMULCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ab049ba889709df922c683e1961c32ae9">llvm::AMDGPUTargetLowering::performMulCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a3e110576778e9ccf929885efddeea4aa">llvm::AMDGPUTargetLowering::performMulhsCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a09d46d8519c83130e03376d0d2e0008a">llvm::AMDGPUTargetLowering::performMulhuCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae60d2a6d5da1fa05bb8e59e09fb72612">llvm::AMDGPUTargetLowering::performMulLoHiCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a589928ae94c1e14b50e374c6a1146c60">llvm::ARMTargetLowering::PerformMVEExtCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a35a55a457bfc044d33bdeb4811532531">llvm::ARMTargetLowering::PerformMVETruncCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a33f99c1c02a48f20e7ec9d30d11d093c">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4798b448246e74d657035d49de0e648d">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a963a08f31bbf8cb9396ff5214bc7ae26">PerformORCombineToBFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a641b9fd791f4bf8e254fdddec43feb4c">PerformORCombineToSMULWBT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1d0f22bfc290fd2cb53c9486286359df">PerformPREDICATE_CASTCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad9d34da62b4146ef6290977107ea7ead">llvm::AMDGPUTargetLowering::performRcpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7bd1aee507cb5d38c758c9d8620fb629">PerformREMCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2d87a7cc93a308acb6482288fea2bd7c">PerformSELECTCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a66904f0583c44a66125515e02e4905b1">llvm::AMDGPUTargetLowering::performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae2780d9409416f3a9ba64201fd887888">PerformSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a7d7ccddfc054f29d7bac995d70adb6e8">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abcaf1212adde88b8addaf1060c459819">performSetccMergeZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a391272ef81598a4a25763b2f35809615">PerformShiftCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4a2c60919236f6bec42a5a1cd2e0fadb">llvm::AMDGPUTargetLowering::performShlCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad8eb465f75fcd8db9f348cbbb24194c1">PerformSHLSimplify</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a801abfb2be28ad60d1a5f79828e99a41">llvm::AMDGPUTargetLowering::performSraCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a89077a6acaf53615241018f1013dc349">llvm::AMDGPUTargetLowering::performSrlCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a111643e86a00d697a134123e45817e14">PerformSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a267cdbd87c30830568cb74844b0e489c">performSVEAndCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d8e109ce3c796c31524f5a06dd745ac">performSVEMulAddSubCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aafe4b0329b540edc331b00b6f669a636">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57a099df9c79ef37ef7f89374247ac0e">PerformVDUPLANECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a86a5f246076a9ff2cba6a1b9ff58c4bf">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a45e1707fbf027e87ccca3b9d17cd8c6b">performVectorExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#ac2921375cd7404c088320b75e5df53c6">performVectorExtendToFPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7e495837f173dea1e6919b589d315f67">performVectorShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a8a9e8cccbe98907e9c282728ab9ea7c0">performVectorTruncZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aba2bb778924793120e1a03fb10f0682a">performVFMADD_VLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a19d36e331487399aaac4f18bac0c7956">PerformVMOVhrCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab245ac37eac3c3ba9c6e8cfa310f4a46">PerformVMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aab5f933f6c91550090ecb2288acc64fd">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a87f35b3974b7d383ff5cd70bdfa090ab">PerformVQMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a3a9b8c53e20027bce86d1f1364150e7c">PerformVSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8ee8d90c02a1da62f94c6322a8f004cb">PerformVSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a99f918c3264972ed6aea09c675404952">PerformVSetCCToVCTPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3afeac5861ab518f4a52bb9d464a5da5">performVWADDSUBW_VLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#abbdb66ef7655ebae91e2bbfab4320f23">simplifyMul24</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2a6ac5eb53f29d680d116a97de4e53a8">llvm::AMDGPUTargetLowering::splitBinaryBitConstantOpImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4340bab6e118d0614449e74a779b30c">tryCombineWhileLo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#aa8d333c2eb8d0346da6128f38cf941b5">TryMULWIDECombine</a>.</p>

</div>
</div>

### DC {#a037a95334e73e5362be577bd599f52a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::TargetLowering::DAGCombinerInfo::DC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#a9e3e1453357b1b1cd870a4ac3528f918">AddToWorklist</a>, <a href="#adff1fcbcf8e82995a72f1efd2d62ec11">CombineTo</a>, <a href="#a7cf6bcad9fbd93aa99faf16377831feb">CombineTo</a>, <a href="#a9ed65892d0b297e512746d6ef74debb7">CombineTo</a>, <a href="#aeecdb6a29a24d717a83fc1c948e00d98">CommitTargetLoweringOpt</a>, <a href="#ac7d178d0480903c77340513530c08f7e">DAGCombinerInfo</a> and <a href="#abf156bc8dfc3e92cd63aee7192c3dea8">recursivelyDeleteUnusedNodes</a>.</p>

</div>
</div>

### Level {#a68215eadc6b09f074264c05ee9b06ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CombineLevel llvm::TargetLowering::DAGCombinerInfo::Level</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="#ac7d178d0480903c77340513530c08f7e">DAGCombinerInfo</a>, <a href="#a2337b8ef923079097d8c6de562503ffb">getDAGCombineLevel</a>, <a href="#a2030eb1014aca2732ca4ecfb9ae4b5a0">isAfterLegalizeDAG</a>, <a href="#ac79f060cd8d4b63fc6d682c076cbeec0">isBeforeLegalize</a> and <a href="#a06663f3ab188bef45b0f669c9f109df5">isBeforeLegalizeOps</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
