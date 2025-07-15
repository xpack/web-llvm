---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/coro/anonymous-spillutils-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{SpillUtils.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::coro::anonymous{SpillUtils.cpp} { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-">anonymous{SpillUtils.cpp}</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 8 &gt; <a href="#afd069871b8d1f9222fe06728bd936f74">VisitedBlocksSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31a9c4b578592db083f5535e321d567">isCoroutineStructureIntrinsic</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a9d2c7b181232afcc8b318215640d0">isSuspendReachableFrom</a> (BasicBlock *From, VisitedBlocksSet &amp;VisitedOrFreeBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does control flow starting at the given block ever reach a suspend instruction before reaching a block in VisitedOrFreeBBs? <a href="#a77a9d2c7b181232afcc8b318215640d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1034debe467e168b688e5630170d9093">isLocalAlloca</a> (CoroAllocaAllocInst *AI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is the given alloca "local", i.e. <a href="#a1034debe467e168b688e5630170d9093">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36764d140de2314a0f15b203f0556112">lowerNonLocalAlloca</a> (CoroAllocaAllocInst *AI, const coro::Shape &amp;Shape, SmallVectorImpl&lt; Instruction * &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn the given coro.alloca.alloc call into a dynamic allocation. <a href="#a36764d140de2314a0f15b203f0556112">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc5ca2a4ef6009dc69a410d60c7eeaf">splitBeforeCatchSwitch</a> (CatchSwitchInst *CatchSwitch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452155536772ef01d3c028f7284ecd2b">collectFrameAlloca</a> (AllocaInst *AI, const coro::Shape &amp;Shape, const SuspendCrossingInfo &amp;Checker, SmallVectorImpl&lt; AllocaInfo &gt; &amp;Allocas, const DominatorTree &amp;DT)</td>
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

## Typedefs

### VisitedBlocksSet {#afd069871b8d1f9222fe06728bd936f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallPtrSet&lt;BasicBlock *, 8&gt; llvm::coro::anonymous{SpillUtils.cpp}::VisitedBlocksSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/spillutils-cpp">SpillUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### collectFrameAlloca() {#a452155536772ef01d3c028f7284ecd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::coro::anonymous{SpillUtils.cpp}::collectFrameAlloca (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo">SuspendCrossingInfo</a> &amp; Checker, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coro/allocainfo">AllocaInfo</a> &gt; &amp; Allocas, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/spillutils-cpp">SpillUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a4e554c60419835fc3c74b91b28ca31c8">llvm::coro::Shape::ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#a452155536772ef01d3c028f7284ecd2b">collectFrameAlloca</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a5fd0aa934908c837c6d78097a2fd667b">llvm::coro::Shape::CoroSuspends</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a565f546ad95bd3a9bbe9a1e5040803f0">llvm::Instruction::hasMetadata</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchloweringstorage/#a6af0b7b0e5d0e8f4b8b4f4199a885204">llvm::coro::Shape::SwitchLoweringStorage::PromiseAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a> and <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#abe8f7906a8618f90e2a75109a778054a">llvm::coro::Shape::SwitchLowering</a>.</p>


<p>Referenced by <a href="#a452155536772ef01d3c028f7284ecd2b">collectFrameAlloca</a>.</p>

</div>
</div>

### isCoroutineStructureIntrinsic() {#ad31a9c4b578592db083f5535e321d567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::coro::anonymous{SpillUtils.cpp}::isCoroutineStructureIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/spillutils-cpp">SpillUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#ad31a9c4b578592db083f5535e321d567">isCoroutineStructureIntrinsic</a>.</p>


<p>Referenced by <a href="#ad31a9c4b578592db083f5535e321d567">isCoroutineStructureIntrinsic</a>.</p>

</div>
</div>

### isLocalAlloca() {#a1034debe467e168b688e5630170d9093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::coro::anonymous{SpillUtils.cpp}::isLocalAlloca (<a href="/web-llvm/docs/api/classes/llvm/coroallocaallocinst">CoroAllocaAllocInst</a> * AI)</td>
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

<p>Is the given alloca "local", i.e.</p>


<p>bounded in lifetime to not cross a suspend point?</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/spillutils-cpp">SpillUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a1034debe467e168b688e5630170d9093">isLocalAlloca</a>, <a href="#a77a9d2c7b181232afcc8b318215640d0">isSuspendReachableFrom</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a1034debe467e168b688e5630170d9093">isLocalAlloca</a>.</p>

</div>
</div>

### isSuspendReachableFrom() {#a77a9d2c7b181232afcc8b318215640d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::coro::anonymous{SpillUtils.cpp}::isSuspendReachableFrom (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="#afd069871b8d1f9222fe06728bd936f74">VisitedBlocksSet</a> &amp; VisitedOrFreeBBs)</td>
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

<p>Does control flow starting at the given block ever reach a suspend instruction before reaching a block in VisitedOrFreeBBs?</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/spillutils-cpp">SpillUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a64f8e14ffe5fb52d552fcb9058286ad3">llvm::coro::isSuspendBlock</a>, <a href="#a77a9d2c7b181232afcc8b318215640d0">isSuspendReachableFrom</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#a1034debe467e168b688e5630170d9093">isLocalAlloca</a> and <a href="#a77a9d2c7b181232afcc8b318215640d0">isSuspendReachableFrom</a>.</p>

</div>
</div>

### lowerNonLocalAlloca() {#a36764d140de2314a0f15b203f0556112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::coro::anonymous{SpillUtils.cpp}::lowerNonLocalAlloca (<a href="/web-llvm/docs/api/classes/llvm/coroallocaallocinst">CoroAllocaAllocInst</a> * AI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; DeadInsts)</td>
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

<p>Turn the given coro.alloca.alloc call into a dynamic allocation.</p>


<p>This happens during the all-instructions iteration, so it must not delete the call.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/spillutils-cpp">SpillUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a78fa8f84df72aa178f82c9421b0cf387">llvm::coro::Shape::emitAlloc</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#acad2aaa7f484c978bb790533eec90ac4">llvm::coro::Shape::emitDealloc</a>, <a href="/web-llvm/docs/api/classes/llvm/coroallocaallocinst/#a60e1555c971882d5ac4b9fb75227e644">llvm::CoroAllocaAllocInst::getSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a36764d140de2314a0f15b203f0556112">lowerNonLocalAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a36764d140de2314a0f15b203f0556112">lowerNonLocalAlloca</a>.</p>

</div>
</div>

### splitBeforeCatchSwitch() {#aedc5ca2a4ef6009dc69a410d60c7eeaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::coro::anonymous{SpillUtils.cpp}::splitBeforeCatchSwitch (<a href="/web-llvm/docs/api/classes/llvm/catchswitchinst">CatchSwitchInst</a> * CatchSwitch)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/spillutils-cpp">SpillUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cleanuppadinst/#afa8a6a49b80d4ca3bd0881fe4383c511">llvm::CleanupPadInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst/#a7e19664720f1c4693b788b018d08758c">llvm::CleanupReturnInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a74d56dd1a8531d108c9b4883bfff61a6">llvm::CatchSwitchInst::getParentPad</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a> and <a href="#aedc5ca2a4ef6009dc69a410d60c7eeaf">splitBeforeCatchSwitch</a>.</p>


<p>Referenced by <a href="#aedc5ca2a4ef6009dc69a410d60c7eeaf">splitBeforeCatchSwitch</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/spillutils-cpp">SpillUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
