---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coro/baseabi
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BaseABI` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::coro::BaseABI { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">llvm/Transforms/Coroutines/ABI.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi">AnyRetconABI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi">AsyncABI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coro/switchabi">SwitchABI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6716df1df6e22677adf4dd402ddac6c">BaseABI</a> (Function &amp;F, coro::Shape &amp;S, std::function&lt; bool(Instruction &amp;)&gt; IsMaterializable)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0780477c53f508b2ee5b639ce46e317">~BaseABI</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab762c35e1833d804f81c7264855359ac">init</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab47fb8dadd631b1c67a285b16607e4c5">buildCoroutineFrame</a> (bool OptimizeFrame)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5353355cfc3a50209e26d5b237c1e81d">splitCoroutine</a> (Function &amp;F, coro::Shape &amp;Shape, SmallVectorImpl&lt; Function * &gt; &amp;Clones, TargetTransformInfo &amp;TTI)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5128305f9a3ef54320d10266e529489c">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae208c041056adf7cd77a649cadfb07c1">Shape</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350ba487cfc141b796c12f38ea7a9355">IsMaterializable</a></td>
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


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BaseABI() {#aa6716df1df6e22677adf4dd402ddac6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coro::BaseABI::BaseABI (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; S, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)&gt; IsMaterializable)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>


<p>References <a href="#a5128305f9a3ef54320d10266e529489c">F</a>, <a href="#a350ba487cfc141b796c12f38ea7a9355">IsMaterializable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#ae208c041056adf7cd77a649cadfb07c1">Shape</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#a2ec9880cc137df3cad8acc0008bedac0">llvm::coro::AnyRetconABI::AnyRetconABI</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ab07d9e24205fc3b764b2148da0df9562">llvm::coro::AsyncABI::AsyncABI</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchabi/#aa9276e26302ee6aa34a2ad9370459aaf">llvm::coro::SwitchABI::SwitchABI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BaseABI() {#ad0780477c53f508b2ee5b639ce46e317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::coro::BaseABI::~BaseABI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildCoroutineFrame() {#ab47fb8dadd631b1c67a285b16607e4c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::BaseABI::buildCoroutineFrame (bool OptimizeFrame)</td>
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



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>, definition at line 2069 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afee39cae7ff99ef86d9f4ed0ee4282f0">llvm::coro::collectSpillsAndAllocasFromInsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aee11dcf213f8b5c3fecab6894b0b6517">llvm::coro::collectSpillsFromArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#af6a9c51da634a8036f03c22a6036caaf">llvm::coro::collectSpillsFromDbgInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad3bf571f4743d886275638484d6a3389">llvm::coro::doRematerializations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a49cc8ffa2bb7e7ced148a4acb2d9ea87">dumpAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a6f0999556f0dc8e0fb4ccec5b3e121a1">dumpSpills</a>, <a href="#a5128305f9a3ef54320d10266e529489c">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="#a350ba487cfc141b796c12f38ea7a9355">IsMaterializable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a36b39e8a1384a23b9899d2c9e2e08e72">lowerLocalAllocas</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="#ae208c041056adf7cd77a649cadfb07c1">Shape</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>.</p>

</div>
</div>

### init() {#ab762c35e1833d804f81c7264855359ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::coro::BaseABI::init ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>

</div>
</div>

### splitCoroutine() {#a5353355cfc3a50209e26d5b237c1e81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::coro::BaseABI::splitCoroutine (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; Clones, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>


<p>References <a href="#a5128305f9a3ef54320d10266e529489c">F</a> and <a href="#ae208c041056adf7cd77a649cadfb07c1">Shape</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### F {#a5128305f9a3ef54320d10266e529489c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; llvm::coro::BaseABI::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#a2ec9880cc137df3cad8acc0008bedac0">llvm::coro::AnyRetconABI::AnyRetconABI</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ab07d9e24205fc3b764b2148da0df9562">llvm::coro::AsyncABI::AsyncABI</a>, <a href="#aa6716df1df6e22677adf4dd402ddac6c">BaseABI</a>, <a href="#ab47fb8dadd631b1c67a285b16607e4c5">buildCoroutineFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#adc7bbccb30409488c60813454af8c81d">llvm::coro::AnyRetconABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ae51f7f2d35223ec01d09e205c757a4df">llvm::coro::AsyncABI::splitCoroutine</a>, <a href="#a5353355cfc3a50209e26d5b237c1e81d">splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchabi/#a21cb9b1f8d82f56bd100b1d4dade6b95">llvm::coro::SwitchABI::splitCoroutine</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchabi/#aa9276e26302ee6aa34a2ad9370459aaf">llvm::coro::SwitchABI::SwitchABI</a>.</p>

</div>
</div>

### IsMaterializable {#a350ba487cfc141b796c12f38ea7a9355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;bool(Instruction &amp;I)&gt; llvm::coro::BaseABI::IsMaterializable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#a2ec9880cc137df3cad8acc0008bedac0">llvm::coro::AnyRetconABI::AnyRetconABI</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ab07d9e24205fc3b764b2148da0df9562">llvm::coro::AsyncABI::AsyncABI</a>, <a href="#aa6716df1df6e22677adf4dd402ddac6c">BaseABI</a>, <a href="#ab47fb8dadd631b1c67a285b16607e4c5">buildCoroutineFrame</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchabi/#aa9276e26302ee6aa34a2ad9370459aaf">llvm::coro::SwitchABI::SwitchABI</a>.</p>

</div>
</div>

### Shape {#ae208c041056adf7cd77a649cadfb07c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">coro::Shape&amp; llvm::coro::BaseABI::Shape</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a>.</p>


<p>Referenced by <a href="#aa6716df1df6e22677adf4dd402ddac6c">BaseABI</a>, <a href="#ab47fb8dadd631b1c67a285b16607e4c5">buildCoroutineFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#a4813065b259c6f6a34961b286913f06c">llvm::coro::AnyRetconABI::init</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#a0e13625e0e7050810ddce7303907d866">llvm::coro::AsyncABI::init</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchabi/#a141a2b1da2e0366d7f88ce6af6779430">llvm::coro::SwitchABI::init</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#adc7bbccb30409488c60813454af8c81d">llvm::coro::AnyRetconABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ae51f7f2d35223ec01d09e205c757a4df">llvm::coro::AsyncABI::splitCoroutine</a>, <a href="#a5353355cfc3a50209e26d5b237c1e81d">splitCoroutine</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchabi/#a21cb9b1f8d82f56bd100b1d4dade6b95">llvm::coro::SwitchABI::splitCoroutine</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">ABI.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
