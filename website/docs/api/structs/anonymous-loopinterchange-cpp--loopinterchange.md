---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-loopinterchange-cpp-/loopinterchange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoopInterchange` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{LoopInterchange.cpp}::LoopInterchange { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a333b7cd864b9e60832e1b4244bd94253">LoopInterchange</a> (ScalarEvolution *SE, LoopInfo *LI, DependenceInfo *DI, DominatorTree *DT, std::unique_ptr&lt; CacheCost &gt; &amp;CC, OptimizationRemarkEmitter *ORE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0da7e9ab23b615c993418c11b91281">run</a> (Loop *L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a377904340b53c8545eb81eb92022c4f4">run</a> (LoopNest &amp;LN)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b6ed04555e8c7e6c82f019960537a1">isComputableLoopNest</a> (ArrayRef&lt; Loop * &gt; LoopList)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36ddc49228f8cf6ea22991daf2b26b0">selectLoopForInterchange</a> (ArrayRef&lt; Loop * &gt; LoopList)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a> (SmallVectorImpl&lt; Loop * &gt; &amp;LoopList)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5342eefdd06826f163b13f40992ce8e4">processLoop</a> (Loop *InnerLoop, Loop *OuterLoop, unsigned InnerLoopId, unsigned OuterLoopId, std::vector&lt; std::vector&lt; char &gt; &gt; &amp;DependencyMatrix, const DenseMap&lt; const Loop *, unsigned &gt; &amp;CostMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3304839957bc26746737074f95a4de30">SE</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29952ea32b55903dd08e308be73398b2">LI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac953cc1ba8957a84cc3537923782c2">DI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa197f2c7579e17b4e1c2eae7b48d1be8">DT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95eec28fcd78be0ea3050e6e779e6bb4">CC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6026004148d714281827c9516135a0f">ORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to emit optimization remarks. <a href="#ad6026004148d714281827c9516135a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopInterchange() {#a333b7cd864b9e60832e1b4244bd94253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopInterchange.cpp}::LoopInterchange::LoopInterchange (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> * DI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/cachecost">CacheCost</a> &gt; &amp; CC, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>References <a href="#a95eec28fcd78be0ea3050e6e779e6bb4">CC</a>, <a href="#a6ac953cc1ba8957a84cc3537923782c2">DI</a>, <a href="#aa197f2c7579e17b4e1c2eae7b48d1be8">DT</a>, <a href="#a29952ea32b55903dd08e308be73398b2">LI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#ad6026004148d714281827c9516135a0f">ORE</a> and <a href="#a3304839957bc26746737074f95a4de30">SE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isComputableLoopNest() {#ac8b6ed04555e8c7e6c82f019960537a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopInterchange.cpp}::LoopInterchange::isComputableLoopNest (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt; LoopList)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a3304839957bc26746737074f95a4de30">SE</a>.</p>


<p>Referenced by <a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a>.</p>

</div>
</div>

### processLoop() {#a5342eefdd06826f163b13f40992ce8e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopInterchange.cpp}::LoopInterchange::processLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * InnerLoop, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OuterLoop, unsigned InnerLoopId, unsigned OuterLoopId, std::vector&lt; std::vector&lt; char &gt; &gt; &amp; DependencyMatrix, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, unsigned &gt; &amp; CostMap)</td>
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



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a168af47de1295ee31c30d2eac4c191ed">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::canInterchangeLoops</a>, <a href="#a95eec28fcd78be0ea3050e6e779e6bb4">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="#aa197f2c7579e17b4e1c2eae7b48d1be8">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a30e47ae014eb35bea24e45097c2bd731">llvm::formLCSSARecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a615131659002c10601eef598d42d025e">llvm::Loop::getStartLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangeprofitability/#a47fea7bb15b60858facd3b9535780d11">anonymous{LoopInterchange.cpp}::LoopInterchangeProfitability::isProfitable</a>, <a href="#a29952ea32b55903dd08e308be73398b2">LI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ad6026004148d714281827c9516135a0f">ORE</a>, <a href="#a3304839957bc26746737074f95a4de30">SE</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#aebda974c30b92d0f6ffca66705d27f35">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::transform</a>.</p>


<p>Referenced by <a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a>.</p>

</div>
</div>

### processLoopList() {#a2a08cef5ef885ecb702cabcedb86c95e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopInterchange.cpp}::LoopInterchange::processLoopList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt; &amp; LoopList)</td>
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



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#a95eec28fcd78be0ea3050e6e779e6bb4">CC</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a6ac953cc1ba8957a84cc3537923782c2">DI</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ab48af53a5000ecede46c76dabb4578d2">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a4cda46bdec29ace64dfd3dff3e55bbf3">hasSupportedLoopDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a6fdefa5e30cfe78c973990812d4a8900">interChangeDependencies</a>, <a href="#ac8b6ed04555e8c7e6c82f019960537a1">isComputableLoopNest</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ad6026004148d714281827c9516135a0f">ORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#adcd261211472362965c5b1bc5a3efebe">populateDependencyMatrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a8799fc92f6ff3fd86b6a60183ddceb5d">printDepMatrix</a>, <a href="#a5342eefdd06826f163b13f40992ce8e4">processLoop</a>, <a href="#a3304839957bc26746737074f95a4de30">SE</a>, <a href="#af36ddc49228f8cf6ea22991daf2b26b0">selectLoopForInterchange</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#acf0da7e9ab23b615c993418c11b91281">run</a> and <a href="#a377904340b53c8545eb81eb92022c4f4">run</a>.</p>

</div>
</div>

### run() {#acf0da7e9ab23b615c993418c11b91281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopInterchange.cpp}::LoopInterchange::run (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ada6d2508cfa150fd7974bef2dc21c40f">populateWorklist</a> and <a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a>.</p>

</div>
</div>

### run() {#a377904340b53c8545eb81eb92022c4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopInterchange.cpp}::LoopInterchange::run (<a href="/web-llvm/docs/api/classes/llvm/loopnest">LoopNest</a> &amp; LN)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a2b8c1f7e00ee579ae55bad5bb1b44b31">llvm::LoopNest::getLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### selectLoopForInterchange() {#af36ddc49228f8cf6ea22991daf2b26b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LoopInterchange.cpp}::LoopInterchange::selectLoopForInterchange (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt; LoopList)</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CC {#a95eec28fcd78be0ea3050e6e779e6bb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CacheCost&gt; anonymous{LoopInterchange.cpp}::LoopInterchange::CC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>Referenced by <a href="#a333b7cd864b9e60832e1b4244bd94253">LoopInterchange</a>, <a href="#a5342eefdd06826f163b13f40992ce8e4">processLoop</a> and <a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a>.</p>

</div>
</div>

### DI {#a6ac953cc1ba8957a84cc3537923782c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DependenceInfo* anonymous{LoopInterchange.cpp}::LoopInterchange::DI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>Referenced by <a href="#a333b7cd864b9e60832e1b4244bd94253">LoopInterchange</a> and <a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a>.</p>

</div>
</div>

### DT {#aa197f2c7579e17b4e1c2eae7b48d1be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{LoopInterchange.cpp}::LoopInterchange::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>Referenced by <a href="#a333b7cd864b9e60832e1b4244bd94253">LoopInterchange</a> and <a href="#a5342eefdd06826f163b13f40992ce8e4">processLoop</a>.</p>

</div>
</div>

### LI {#a29952ea32b55903dd08e308be73398b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{LoopInterchange.cpp}::LoopInterchange::LI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>Referenced by <a href="#a333b7cd864b9e60832e1b4244bd94253">LoopInterchange</a> and <a href="#a5342eefdd06826f163b13f40992ce8e4">processLoop</a>.</p>

</div>
</div>

### ORE {#ad6026004148d714281827c9516135a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* anonymous{LoopInterchange.cpp}::LoopInterchange::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interface to emit optimization remarks.</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>Referenced by <a href="#a333b7cd864b9e60832e1b4244bd94253">LoopInterchange</a>, <a href="#a5342eefdd06826f163b13f40992ce8e4">processLoop</a> and <a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a>.</p>

</div>
</div>

### SE {#a3304839957bc26746737074f95a4de30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* anonymous{LoopInterchange.cpp}::LoopInterchange::SE = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a>.</p>


<p>Referenced by <a href="#ac8b6ed04555e8c7e6c82f019960537a1">isComputableLoopNest</a>, <a href="#a333b7cd864b9e60832e1b4244bd94253">LoopInterchange</a>, <a href="#a5342eefdd06826f163b13f40992ce8e4">processLoop</a> and <a href="#a2a08cef5ef885ecb702cabcedb86c95e">processLoopList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp">LoopInterchange.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
