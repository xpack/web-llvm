---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoopInterchangeTransform` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform">LoopInterchangeTransform</a> interchanges the loop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LoopInterchange.cpp}::LoopInterchangeTransform { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa980e2e89e08b91f18721d108a0cf5d3">LoopInterchangeTransform</a> (Loop *Outer, Loop *Inner, ScalarEvolution *SE, LoopInfo *LI, DominatorTree *DT, const LoopInterchangeLegality &amp;LIL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebda974c30b92d0f6ffca66705d27f35">transform</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interchange OuterLoop and InnerLoop. <a href="#aebda974c30b92d0f6ffca66705d27f35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41caf6254221316cf74145aacc3da9a">restructureLoops</a> (Loop *NewInner, Loop *NewOuter, BasicBlock *OrigInnerPreHeader, BasicBlock *OrigOuterPreHeader)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a>, after interchanging. <a href="#ac41caf6254221316cf74145aacc3da9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adccaa5c939a209e01dd4e628b3ca35a1">removeChildLoop</a> (Loop *OuterLoop, Loop *InnerLoop)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13a276c564fd0c1292ed486b86d78da">adjustLoopLinks</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d764593cae052fed1d1aa98135e53ce">adjustLoopBranches</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14dcaef641661d7e73c71173862e0bc9">OuterLoop</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac98a907d5bf492b5fe36797a0f96e9de">InnerLoop</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ae9bb78e0d9ec34e347d58be46461a">SE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scev analysis. <a href="#a70ae9bb78e0d9ec34e347d58be46461a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3e43113d5b9f3f8fd6c278c2811f72">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72078495824ea42ff32cd4755e007653">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality">LoopInterchangeLegality</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4756ef0d9e61c93dba37220498c37cc">LIL</a></td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform">LoopInterchangeTransform</a> interchanges the loop.</p>

<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopInterchangeTransform() {#aa980e2e89e08b91f18721d108a0cf5d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::LoopInterchangeTransform (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * Outer, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * Inner, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality">LoopInterchangeLegality</a> &amp; LIL)</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### removeChildLoop() {#adccaa5c939a209e01dd4e628b3ca35a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopInterchangeTransform::removeChildLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OuterLoop, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * InnerLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ac41caf6254221316cf74145aacc3da9a">restructureLoops</a>.</p>

</div>
</div>

### restructureLoops() {#ac41caf6254221316cf74145aacc3da9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopInterchangeTransform::restructureLoops (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * NewInner, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * NewOuter, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OrigInnerPreHeader, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OrigOuterPreHeader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a>, after interchanging.</p>


<p>NewInner and NewOuter refer to the new inner and outer loop after interchanging: NewInner is the original outer loop and NewOuter is the original inner loop.</p>


<p>Before interchanging, we have the following structure Outer preheader</p>


<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ab0a5e875687fec396caa916b3950e0a3">llvm::LoopBase&lt; BlockT, LoopT &gt;::addBlockEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#af2f81059dc7566164b018aac6555eb1a">llvm::LoopBase&lt; BlockT, LoopT &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae34bcd53f75fab0c03b509ecccb4cfaf">llvm::LoopBase&lt; BlockT, LoopT &gt;::getParentLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a16165c1e5da45acaa086c3a54a188d34">llvm::LoopBase&lt; BlockT, LoopT &gt;::isInnermost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1b9dddb31a33eea763f49038e9cf7d63">llvm::LoopBase&lt; BlockT, LoopT &gt;::removeBlockFromLoop</a>, <a href="#adccaa5c939a209e01dd4e628b3ca35a1">removeChildLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#afd824d78def66604189ab07c6266572d">llvm::LoopBase&lt; BlockT, LoopT &gt;::removeChildLoop</a>.</p>

</div>
</div>

### transform() {#aebda974c30b92d0f6ffca66705d27f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopInterchangeTransform::transform ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interchange OuterLoop and InnerLoop.</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6ea260be710ac7b61309534308da3147">llvm::Instruction::mayHaveSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-loopinterchange-cpp-/loopinterchange/#a5342eefdd06826f163b13f40992ce8e4">anonymous{LoopInterchange.cpp}::LoopInterchange::processLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### adjustLoopBranches() {#a4d764593cae052fed1d1aa98135e53ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopInterchangeTransform::adjustLoopBranches ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>

</div>
</div>

### adjustLoopLinks() {#ad13a276c564fd0c1292ed486b86d78da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopInterchangeTransform::adjustLoopLinks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DT {#a72078495824ea42ff32cd4755e007653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>

</div>
</div>

### InnerLoop {#ac98a907d5bf492b5fe36797a0f96e9de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::InnerLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>

</div>
</div>

### LI {#a0f3e43113d5b9f3f8fd6c278c2811f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>

</div>
</div>

### LIL {#ad4756ef0d9e61c93dba37220498c37cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopInterchangeLegality&amp; anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::LIL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>

</div>
</div>

### OuterLoop {#a14dcaef641661d7e73c71173862e0bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::OuterLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>

</div>
</div>

### SE {#a70ae9bb78e0d9ec34e347d58be46461a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scev analysis.</p>

<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
