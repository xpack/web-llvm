---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coro/asyncabi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AsyncABI` Class



## Declaration

<div class="doxyDeclaration">
class llvm::coro::AsyncABI { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">llvm/Transforms/Coroutines/ABI.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coro/baseabi">BaseABI</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab07d9e24205fc3b764b2148da0df9562">AsyncABI</a> (Function &amp;F, coro::Shape &amp;S, std::function&lt; bool(Instruction &amp;)&gt; IsMaterializable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e13625e0e7050810ddce7303907d866">init</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae51f7f2d35223ec01d09e205c757a4df">splitCoroutine</a> (Function &amp;F, coro::Shape &amp;Shape, SmallVectorImpl&lt; Function * &gt; &amp;Clones, TargetTransformInfo &amp;TTI) override</td>
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


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AsyncABI() {#ab07d9e24205fc3b764b2148da0df9562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coro::AsyncABI::AsyncABI (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; S, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)&gt; IsMaterializable)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#aa6716df1df6e22677adf4dd402ddac6c">llvm::coro::BaseABI::BaseABI</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#a5128305f9a3ef54320d10266e529489c">llvm::coro::BaseABI::F</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#a350ba487cfc141b796c12f38ea7a9355">llvm::coro::BaseABI::IsMaterializable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### init() {#a0e13625e0e7050810ddce7303907d866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::AsyncABI::init ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#ae208c041056adf7cd77a649cadfb07c1">llvm::coro::BaseABI::Shape</a>.</p>

</div>
</div>

### splitCoroutine() {#ae51f7f2d35223ec01d09e205c757a4df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::AsyncABI::splitCoroutine (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; Clones, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>, definition at line 1725 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4af11580a0250ef12842e64f487810cc70">llvm::coro::Continuation</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a83cf0b7088dc0d66ca9f5ecac7350e4c">llvm::IRBuilderBase::CreateBitOrPointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a0db1d0e9931350a1fe08aa96d5b5eafc">llvm::coro::BaseCloner::createClone</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a452dcc29fd5e19bda874218e10a8945c">createCloneDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5945995573939aabe8aa3ccea099b219">llvm::IRBuilderBase::CreateConstInBoundsGEP1_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa0d499612ac66539c8daf29c8eb142a5">llvm::coro::createMustTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa6536556982b7e6e2e5884e471f3ce6b">llvm::IRBuilderBase::CreateRetVoid</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#a5128305f9a3ef54320d10266e529489c">llvm::coro::BaseABI::F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a64f8c7400de58c117c5af250f000675f">FramePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/trackingvh/#a3249c6d006cdfe254ce0e6c808260bfb">llvm::TrackingVH&lt; ValueTy &gt;::getValPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendasyncinst/#a605ed14ca54fecd8f58d5eed17028600adea642c56a7c4aa607d2901d060b240c">llvm::CoroSuspendAsyncInst::MustTailCallFuncArg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#af678f41709f265e2589f247e883aa738">replaceAsyncResumeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#ae208c041056adf7cd77a649cadfb07c1">llvm::coro::BaseABI::Shape</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
