---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coro/basecloner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BaseCloner` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::coro::BaseCloner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">Transforms/Coroutines/CoroCloner.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner">SwitchCloner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1749810b383132afa1a064ac81d538">BaseCloner</a> (Function &amp;OrigF, const Twine &amp;Suffix, coro::Shape &amp;Shape, CloneKind FKind, TargetTransformInfo &amp;TTI, const MetadataSetTy &amp;CommonDebugInfo)</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a> (Function &amp;OrigF, const Twine &amp;Suffix, coro::Shape &amp;Shape, Function *NewF, AnyCoroSuspendInst *ActiveSuspend, TargetTransformInfo &amp;TTI, const MetadataSetTy &amp;CommonDebugInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a cloner for a continuation lowering. <a href="#ae598844a9d1a8837d0d222b44935d697">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ce94f781e9c2b7a048ea49fb857959">~BaseCloner</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac98805013f6c223eac46908a5798cc14">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb266590cdac3ed6480244efcd5899c">create</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the body of the original function into a resume function of some sort. <a href="#acfb266590cdac3ed6480244efcd5899c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f899602a4006892760f56f26f0da449">isSwitchDestroyFunction</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a275ed8c2ebcd61ba635dbf7c119e7ed2">replaceEntryBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2039a88cc5cd331c4012e856dde33eed">deriveNewFramePointer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Derive the value of the new frame pointer. <a href="#a2039a88cc5cd331c4012e856dde33eed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accee5b18a5d340c2e2aa6ec426df1778">replaceRetconOrAsyncSuspendUses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace uses of the active llvm.coro.suspend.retcon/async call with the arguments to the continuation function. <a href="#accee5b18a5d340c2e2aa6ec426df1778">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297393e7eadf926c84fff5c68e7d6818">replaceCoroSuspends</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c1ae62749eee27ce4004984448899e0">replaceCoroEnds</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec280addacac6912b1860f98ac682d9">replaceSwiftErrorOps</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d6e16608b64f29f9a4d1483507317b5">salvageDebugInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614a737e40ceece782633b5cabbeab49">handleFinalSuspend</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567c0d086b740b39c9bfd703e0cf2908">OrigF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8abf978b13ebdb39f3fa271d7c49bf5">Suffix</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4">CloneKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa92eee9e4cc8d96f072ac2887d82eb6e">FKind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1ffcc2d4d7f478062b9bf40cee18db">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6472b6d2ecf3c53f5e7ddc8cf0a803bb">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a91897d2d0da113b016f14ae110586ab1">MetadataSetTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38506d5e7b2f1915b1578ba729c1ca89">CommonDebugInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817ca8bc950897f8f548f58d746d03d2">VMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c3567cc47523e331dfcadc14d09550b">NewFramePtr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anycorosuspendinst">AnyCoroSuspendInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5d0f79e5f4e6b854642ab34a378517">ActiveSuspend</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The active suspend instruction; meaningful only for continuation and async ABIs. <a href="#a1e5d0f79e5f4e6b854642ab34a378517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a> (Function &amp;OrigF, const Twine &amp;Suffix, coro::Shape &amp;Shape, Function *NewF, AnyCoroSuspendInst *ActiveSuspend, TargetTransformInfo &amp;TTI, const MetadataSetTy &amp;CommonDebugInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clone for a continuation lowering. <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BaseCloner() {#a4a1749810b383132afa1a064ac81d538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coro::BaseCloner::BaseCloner (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OrigF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Suffix, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4">CloneKind</a> FKind, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a91897d2d0da113b016f14ae110586ab1">MetadataSetTy</a> &amp; CommonDebugInfo)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>References <a href="#abb1ffcc2d4d7f478062b9bf40cee18db">Builder</a>, <a href="#a38506d5e7b2f1915b1578ba729c1ca89">CommonDebugInfo</a>, <a href="#aa92eee9e4cc8d96f072ac2887d82eb6e">FKind</a>, <a href="#a567c0d086b740b39c9bfd703e0cf2908">OrigF</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a>, <a href="#aa8abf978b13ebdb39f3fa271d7c49bf5">Suffix</a> and <a href="#a6472b6d2ecf3c53f5e7ddc8cf0a803bb">TTI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### BaseCloner() {#ae598844a9d1a8837d0d222b44935d697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coro::BaseCloner::BaseCloner (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OrigF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Suffix, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * NewF, <a href="/web-llvm/docs/api/classes/llvm/anycorosuspendinst">AnyCoroSuspendInst</a> * ActiveSuspend, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a91897d2d0da113b016f14ae110586ab1">MetadataSetTy</a> &amp; CommonDebugInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a cloner for a continuation lowering.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>References <a href="#a1e5d0f79e5f4e6b854642ab34a378517">ActiveSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#abb1ffcc2d4d7f478062b9bf40cee18db">Builder</a>, <a href="#a38506d5e7b2f1915b1578ba729c1ca89">CommonDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4af11580a0250ef12842e64f487810cc70">llvm::coro::Continuation</a>, <a href="#aa92eee9e4cc8d96f072ac2887d82eb6e">FKind</a>, <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>, <a href="#a567c0d086b740b39c9bfd703e0cf2908">OrigF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a>, <a href="#aa8abf978b13ebdb39f3fa271d7c49bf5">Suffix</a> and <a href="#a6472b6d2ecf3c53f5e7ddc8cf0a803bb">TTI</a>.</p>


<p>Referenced by <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#ac1a0f607ea14257093cd8eaeb09f0ddc">llvm::coro::SwitchCloner::SwitchCloner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BaseCloner() {#a26ce94f781e9c2b7a048ea49fb857959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::coro::BaseCloner::~BaseCloner ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### create() {#acfb266590cdac3ed6480244efcd5899c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::BaseCloner::create ()</td>
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

<p>Clone the body of the original function into a resume function of some sort.</p>

<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a1e5d0f79e5f4e6b854642ab34a378517">ActiveSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a2c299a4357972cc32be0eda57abda580">addAsyncContextAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a7c497627acf5128770bd9fa245b44fbd">addFramePointerAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a0e09834bc2b325fc2f777641292396e1">addSwiftSelfAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="#abb1ffcc2d4d7f478062b9bf40cee18db">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af97d9ff977792ae671987a9a95f942f2">llvm::CloneFunctionBodyInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9d39db97de33dc64cd40be3d37fc8ed9">llvm::CloneFunctionMetadataInto</a>, <a href="#a38506d5e7b2f1915b1578ba729c1ca89">CommonDebugInfo</a>, <a href="#a2039a88cc5cd331c4012e856dde33eed">deriveNewFramePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="#a614a737e40ceece782633b5cabbeab49">handleFinalSuspend</a>, <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>, <a href="#a3c3567cc47523e331dfcadc14d09550b">NewFramePtr</a>, <a href="#a567c0d086b740b39c9bfd703e0cf2908">OrigF</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="#a7c1ae62749eee27ce4004984448899e0">replaceCoroEnds</a>, <a href="#a297393e7eadf926c84fff5c68e7d6818">replaceCoroSuspends</a>, <a href="#a275ed8c2ebcd61ba635dbf7c119e7ed2">replaceEntryBlock</a>, <a href="#accee5b18a5d340c2e2aa6ec426df1778">replaceRetconOrAsyncSuspendUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a236935b2df66a03a0a54350a6b9b84bc">replaceSwiftErrorOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da89b60f3b4ad8c1e0ddb9a31b57cb13f9">llvm::RF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aefa2c3fc2c37f5db1dd777fad4e0d33ec7e">llvm::CallInst::TCK_MustTail</a>, <a href="#a6472b6d2ecf3c53f5e7ddc8cf0a803bb">TTI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a4d1d15c0a00a9b9391977c8f482e0428">updateScopeLine</a> and <a href="#a817ca8bc950897f8f548f58d746d03d2">VMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a402d5de6c6250d90988f455ada737600">llvm::coro::SwitchCloner::create</a> and <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a>.</p>

</div>
</div>

### getFunction() {#ac98805013f6c223eac46908a5798cc14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::coro::BaseCloner::getFunction ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>.</p>


<p>Referenced by <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a4e4793514f814a12dc765fc5cdefb996">llvm::coro::SwitchCloner::createClone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### deriveNewFramePointer() {#a2039a88cc5cd331c4012e856dde33eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * coro::BaseCloner::deriveNewFramePointer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Derive the value of the new frame pointer.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="#a1e5d0f79e5f4e6b854642ab34a378517">ActiveSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#abb1ffcc2d4d7f478062b9bf40cee18db">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeac1775aaace95748849e1216a09f028fc">InlineInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a> and <a href="#a817ca8bc950897f8f548f58d746d03d2">VMap</a>.</p>


<p>Referenced by <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>.</p>

</div>
</div>

### handleFinalSuspend() {#a614a737e40ceece782633b5cabbeab49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::BaseCloner::handleFinalSuspend ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abb1ffcc2d4d7f478062b9bf40cee18db">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="#a9f899602a4006892760f56f26f0da449">isSwitchDestroyFunction</a>, <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>, <a href="#a3c3567cc47523e331dfcadc14d09550b">NewFramePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchfieldindex/#aef925686aca6c6970964fea2c25bf242a012dd1dc85c718e8159980fa4273d9e6">llvm::coro::Shape::SwitchFieldIndex::Resume</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a> and <a href="#a817ca8bc950897f8f548f58d746d03d2">VMap</a>.</p>


<p>Referenced by <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>.</p>

</div>
</div>

### isSwitchDestroyFunction() {#a9f899602a4006892760f56f26f0da449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::coro::BaseCloner::isSwitchDestroyFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4af11580a0250ef12842e64f487810cc70">llvm::coro::Continuation</a>, <a href="#aa92eee9e4cc8d96f072ac2887d82eb6e">FKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4a2c249a520c88badf6f400e74f26ce424">llvm::coro::SwitchCleanup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4ae58f565eb9e7a17b331c3eda53da8fc2">llvm::coro::SwitchResume</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4af04bd27f8437836c71e2e1504acc18c8">llvm::coro::SwitchUnwind</a>.</p>


<p>Referenced by <a href="#a614a737e40ceece782633b5cabbeab49">handleFinalSuspend</a> and <a href="#a297393e7eadf926c84fff5c68e7d6818">replaceCoroSuspends</a>.</p>

</div>
</div>

### replaceCoroEnds() {#a7c1ae62749eee27ce4004984448899e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::BaseCloner::replaceCoroEnds ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a3c3567cc47523e331dfcadc14d09550b">NewFramePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab289568caaa6647ee577a06e6e12499a">replaceCoroEnd</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a> and <a href="#a817ca8bc950897f8f548f58d746d03d2">VMap</a>.</p>


<p>Referenced by <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>.</p>

</div>
</div>

### replaceCoroSuspends() {#a297393e7eadf926c84fff5c68e7d6818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::BaseCloner::replaceCoroSuspends ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="#a1e5d0f79e5f4e6b854642ab34a378517">ActiveSuspend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#abb1ffcc2d4d7f478062b9bf40cee18db">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a9f899602a4006892760f56f26f0da449">isSwitchDestroyFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a> and <a href="#a817ca8bc950897f8f548f58d746d03d2">VMap</a>.</p>


<p>Referenced by <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>.</p>

</div>
</div>

### replaceEntryBlock() {#a275ed8c2ebcd61ba635dbf7c119e7ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::BaseCloner::replaceEntryBlock ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="#a1e5d0f79e5f4e6b854642ab34a378517">ActiveSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#abb1ffcc2d4d7f478062b9bf40cee18db">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a1a70f2c359aadd76a72aaaede16aca4a">llvm::DominatorTree::isReachableFromEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a>, <a href="#aa8abf978b13ebdb39f3fa271d7c49bf5">Suffix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a> and <a href="#a817ca8bc950897f8f548f58d746d03d2">VMap</a>.</p>


<p>Referenced by <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>.</p>

</div>
</div>

### replaceRetconOrAsyncSuspendUses() {#accee5b18a5d340c2e2aa6ec426df1778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::BaseCloner::replaceRetconOrAsyncSuspendUses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace uses of the active llvm.coro.suspend.retcon/async call with the arguments to the continuation function.</p>


<p>This assumes that the builder has a meaningful insertion point.</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="#a1e5d0f79e5f4e6b854642ab34a378517">ActiveSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#abb1ffcc2d4d7f478062b9bf40cee18db">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a> and <a href="#a817ca8bc950897f8f548f58d746d03d2">VMap</a>.</p>


<p>Referenced by <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>.</p>

</div>
</div>

### replaceSwiftErrorOps() {#a0ec280addacac6912b1860f98ac682d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::BaseCloner::replaceSwiftErrorOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a236935b2df66a03a0a54350a6b9b84bc">replaceSwiftErrorOps</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a> and <a href="#a817ca8bc950897f8f548f58d746d03d2">VMap</a>.</p>

</div>
</div>

### salvageDebugInfo() {#a1d6e16608b64f29f9a4d1483507317b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::BaseCloner::salvageDebugInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a13dafea5ca0652a4011dd613a8f02494">collectDbgVariableIntrinsics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b2a153b655ed78a07468297eb4c6256">llvm::for_each</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9e0d7431e635bbbf753602d214d89f0e">llvm::Triple::isArch64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affedc93ead6b25c57a7196d32ff11e89">llvm::isPotentiallyReachable</a>, <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>, <a href="#a567c0d086b740b39c9bfd703e0cf2908">OrigF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ActiveSuspend {#a1e5d0f79e5f4e6b854642ab34a378517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnyCoroSuspendInst* llvm::coro::BaseCloner::ActiveSuspend = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The active suspend instruction; meaningful only for continuation and async ABIs.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a402d5de6c6250d90988f455ada737600">llvm::coro::SwitchCloner::create</a>, <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a>, <a href="#a2039a88cc5cd331c4012e856dde33eed">deriveNewFramePointer</a>, <a href="#a297393e7eadf926c84fff5c68e7d6818">replaceCoroSuspends</a>, <a href="#a275ed8c2ebcd61ba635dbf7c119e7ed2">replaceEntryBlock</a> and <a href="#accee5b18a5d340c2e2aa6ec426df1778">replaceRetconOrAsyncSuspendUses</a>.</p>

</div>
</div>

### Builder {#abb1ffcc2d4d7f478062b9bf40cee18db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder llvm::coro::BaseCloner::Builder</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#a4a1749810b383132afa1a064ac81d538">BaseCloner</a>, <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="#a2039a88cc5cd331c4012e856dde33eed">deriveNewFramePointer</a>, <a href="#a614a737e40ceece782633b5cabbeab49">handleFinalSuspend</a>, <a href="#a297393e7eadf926c84fff5c68e7d6818">replaceCoroSuspends</a>, <a href="#a275ed8c2ebcd61ba635dbf7c119e7ed2">replaceEntryBlock</a> and <a href="#accee5b18a5d340c2e2aa6ec426df1778">replaceRetconOrAsyncSuspendUses</a>.</p>

</div>
</div>

### CommonDebugInfo {#a38506d5e7b2f1915b1578ba729c1ca89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MetadataSetTy&amp; llvm::coro::BaseCloner::CommonDebugInfo</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#a4a1749810b383132afa1a064ac81d538">BaseCloner</a>, <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a4e4793514f814a12dc765fc5cdefb996">llvm::coro::SwitchCloner::createClone</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#ac1a0f607ea14257093cd8eaeb09f0ddc">llvm::coro::SwitchCloner::SwitchCloner</a>.</p>

</div>
</div>

### FKind {#aa92eee9e4cc8d96f072ac2887d82eb6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CloneKind llvm::coro::BaseCloner::FKind</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#a4a1749810b383132afa1a064ac81d538">BaseCloner</a>, <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a402d5de6c6250d90988f455ada737600">llvm::coro::SwitchCloner::create</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a4e4793514f814a12dc765fc5cdefb996">llvm::coro::SwitchCloner::createClone</a>, <a href="#a9f899602a4006892760f56f26f0da449">isSwitchDestroyFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#ac1a0f607ea14257093cd8eaeb09f0ddc">llvm::coro::SwitchCloner::SwitchCloner</a>.</p>

</div>
</div>

### NewF {#a89388e76a59ed9ad1d493b03f212bb3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::coro::BaseCloner::NewF = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a402d5de6c6250d90988f455ada737600">llvm::coro::SwitchCloner::create</a>, <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a>, <a href="#a2039a88cc5cd331c4012e856dde33eed">deriveNewFramePointer</a>, <a href="#ac98805013f6c223eac46908a5798cc14">getFunction</a>, <a href="#a614a737e40ceece782633b5cabbeab49">handleFinalSuspend</a>, <a href="#a275ed8c2ebcd61ba635dbf7c119e7ed2">replaceEntryBlock</a>, <a href="#accee5b18a5d340c2e2aa6ec426df1778">replaceRetconOrAsyncSuspendUses</a>, <a href="#a0ec280addacac6912b1860f98ac682d9">replaceSwiftErrorOps</a> and <a href="#a1d6e16608b64f29f9a4d1483507317b5">salvageDebugInfo</a>.</p>

</div>
</div>

### NewFramePtr {#a3c3567cc47523e331dfcadc14d09550b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::coro::BaseCloner::NewFramePtr = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="#a614a737e40ceece782633b5cabbeab49">handleFinalSuspend</a> and <a href="#a7c1ae62749eee27ce4004984448899e0">replaceCoroEnds</a>.</p>

</div>
</div>

### OrigF {#a567c0d086b740b39c9bfd703e0cf2908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; llvm::coro::BaseCloner::OrigF</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#a4a1749810b383132afa1a064ac81d538">BaseCloner</a>, <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a402d5de6c6250d90988f455ada737600">llvm::coro::SwitchCloner::create</a>, <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a4e4793514f814a12dc765fc5cdefb996">llvm::coro::SwitchCloner::createClone</a>, <a href="#a1d6e16608b64f29f9a4d1483507317b5">salvageDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#ac1a0f607ea14257093cd8eaeb09f0ddc">llvm::coro::SwitchCloner::SwitchCloner</a>.</p>

</div>
</div>

### Shape {#a7288c19a015ef21ca88686272daa99bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">coro::Shape&amp; llvm::coro::BaseCloner::Shape</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#a4a1749810b383132afa1a064ac81d538">BaseCloner</a>, <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a402d5de6c6250d90988f455ada737600">llvm::coro::SwitchCloner::create</a>, <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a4e4793514f814a12dc765fc5cdefb996">llvm::coro::SwitchCloner::createClone</a>, <a href="#a2039a88cc5cd331c4012e856dde33eed">deriveNewFramePointer</a>, <a href="#a614a737e40ceece782633b5cabbeab49">handleFinalSuspend</a>, <a href="#a7c1ae62749eee27ce4004984448899e0">replaceCoroEnds</a>, <a href="#a297393e7eadf926c84fff5c68e7d6818">replaceCoroSuspends</a>, <a href="#a275ed8c2ebcd61ba635dbf7c119e7ed2">replaceEntryBlock</a>, <a href="#accee5b18a5d340c2e2aa6ec426df1778">replaceRetconOrAsyncSuspendUses</a>, <a href="#a0ec280addacac6912b1860f98ac682d9">replaceSwiftErrorOps</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#ac1a0f607ea14257093cd8eaeb09f0ddc">llvm::coro::SwitchCloner::SwitchCloner</a>.</p>

</div>
</div>

### Suffix {#aa8abf978b13ebdb39f3fa271d7c49bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Twine&amp; llvm::coro::BaseCloner::Suffix</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#a4a1749810b383132afa1a064ac81d538">BaseCloner</a>, <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a402d5de6c6250d90988f455ada737600">llvm::coro::SwitchCloner::create</a>, <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a4e4793514f814a12dc765fc5cdefb996">llvm::coro::SwitchCloner::createClone</a>, <a href="#a275ed8c2ebcd61ba635dbf7c119e7ed2">replaceEntryBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#ac1a0f607ea14257093cd8eaeb09f0ddc">llvm::coro::SwitchCloner::SwitchCloner</a>.</p>

</div>
</div>

### TTI {#a6472b6d2ecf3c53f5e7ddc8cf0a803bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo&amp; llvm::coro::BaseCloner::TTI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#a4a1749810b383132afa1a064ac81d538">BaseCloner</a>, <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="#a0db1d0e9931350a1fe08aa96d5b5eafc">createClone</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a4e4793514f814a12dc765fc5cdefb996">llvm::coro::SwitchCloner::createClone</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#ac1a0f607ea14257093cd8eaeb09f0ddc">llvm::coro::SwitchCloner::SwitchCloner</a>.</p>

</div>
</div>

### VMap {#a817ca8bc950897f8f548f58d746d03d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueToValueMapTy llvm::coro::BaseCloner::VMap</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>Referenced by <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/switchcloner/#a402d5de6c6250d90988f455ada737600">llvm::coro::SwitchCloner::create</a>, <a href="#a2039a88cc5cd331c4012e856dde33eed">deriveNewFramePointer</a>, <a href="#a614a737e40ceece782633b5cabbeab49">handleFinalSuspend</a>, <a href="#a7c1ae62749eee27ce4004984448899e0">replaceCoroEnds</a>, <a href="#a297393e7eadf926c84fff5c68e7d6818">replaceCoroSuspends</a>, <a href="#a275ed8c2ebcd61ba635dbf7c119e7ed2">replaceEntryBlock</a>, <a href="#accee5b18a5d340c2e2aa6ec426df1778">replaceRetconOrAsyncSuspendUses</a> and <a href="#a0ec280addacac6912b1860f98ac682d9">replaceSwiftErrorOps</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createClone() {#a0db1d0e9931350a1fe08aa96d5b5eafc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::coro::BaseCloner::createClone (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OrigF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Suffix, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * NewF, <a href="/web-llvm/docs/api/classes/llvm/anycorosuspendinst">AnyCoroSuspendInst</a> * ActiveSuspend, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a91897d2d0da113b016f14ae110586ab1">MetadataSetTy</a> &amp; CommonDebugInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a clone for a continuation lowering.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>References <a href="#a1e5d0f79e5f4e6b854642ab34a378517">ActiveSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="#ae598844a9d1a8837d0d222b44935d697">BaseCloner</a>, <a href="#a38506d5e7b2f1915b1578ba729c1ca89">CommonDebugInfo</a>, <a href="#acfb266590cdac3ed6480244efcd5899c">create</a>, <a href="#ac98805013f6c223eac46908a5798cc14">getFunction</a>, <a href="#a89388e76a59ed9ad1d493b03f212bb3d">NewF</a>, <a href="#a567c0d086b740b39c9bfd703e0cf2908">OrigF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="#a7288c19a015ef21ca88686272daa99bd">Shape</a>, <a href="#aa8abf978b13ebdb39f3fa271d7c49bf5">Suffix</a> and <a href="#a6472b6d2ecf3c53f5e7ddc8cf0a803bb">TTI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#adc7bbccb30409488c60813454af8c81d">llvm::coro::AnyRetconABI::splitCoroutine</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ae51f7f2d35223ec01d09e205c757a4df">llvm::coro::AsyncABI::splitCoroutine</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
