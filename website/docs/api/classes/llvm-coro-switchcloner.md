---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coro/switchcloner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SwitchCloner` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::coro::SwitchCloner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">Transforms/Coroutines/CoroCloner.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coro/basecloner">BaseCloner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a0f607ea14257093cd8eaeb09f0ddc">SwitchCloner</a> (Function &amp;OrigF, const Twine &amp;Suffix, coro::Shape &amp;Shape, CloneKind FKind, TargetTransformInfo &amp;TTI, const MetadataSetTy &amp;CommonDebugInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a cloner for a switch lowering. <a href="#ac1a0f607ea14257093cd8eaeb09f0ddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402d5de6c6250d90988f455ada737600">create</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the body of the original function into a resume function of some sort. <a href="#a402d5de6c6250d90988f455ada737600">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e4793514f814a12dc765fc5cdefb996">createClone</a> (Function &amp;OrigF, const Twine &amp;Suffix, coro::Shape &amp;Shape, CloneKind FKind, TargetTransformInfo &amp;TTI, const MetadataSetTy &amp;CommonDebugInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clone for a switch lowering. <a href="#a4e4793514f814a12dc765fc5cdefb996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### SwitchCloner() {#ac1a0f607ea14257093cd8eaeb09f0ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coro::SwitchCloner::SwitchCloner (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OrigF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Suffix, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4">CloneKind</a> FKind, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a91897d2d0da113b016f14ae110586ab1">MetadataSetTy</a> &amp; CommonDebugInfo)</td>
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

<p>Create a cloner for a switch lowering.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#ae598844a9d1a8837d0d222b44935d697">llvm::coro::BaseCloner::BaseCloner</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a38506d5e7b2f1915b1578ba729c1ca89">llvm::coro::BaseCloner::CommonDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#aa92eee9e4cc8d96f072ac2887d82eb6e">llvm::coro::BaseCloner::FKind</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a567c0d086b740b39c9bfd703e0cf2908">llvm::coro::BaseCloner::OrigF</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a7288c19a015ef21ca88686272daa99bd">llvm::coro::BaseCloner::Shape</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#aa8abf978b13ebdb39f3fa271d7c49bf5">llvm::coro::BaseCloner::Suffix</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a6472b6d2ecf3c53f5e7ddc8cf0a803bb">llvm::coro::BaseCloner::TTI</a>.</p>


<p>Referenced by <a href="#a4e4793514f814a12dc765fc5cdefb996">createClone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### create() {#a402d5de6c6250d90988f455ada737600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void coro::SwitchCloner::create ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone the body of the original function into a resume function of some sort.</p>

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>, definition at line 1127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a1e5d0f79e5f4e6b854642ab34a378517">llvm::coro::BaseCloner::ActiveSuspend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a452dcc29fd5e19bda874218e10a8945c">createCloneDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#aa92eee9e4cc8d96f072ac2887d82eb6e">llvm::coro::BaseCloner::FKind</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a89388e76a59ed9ad1d493b03f212bb3d">llvm::coro::BaseCloner::NewF</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a567c0d086b740b39c9bfd703e0cf2908">llvm::coro::BaseCloner::OrigF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#abf799de7147065c0e7f525e1b6009dde">llvm::coro::replaceCoroFree</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a7288c19a015ef21ca88686272daa99bd">llvm::coro::BaseCloner::Shape</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#aa8abf978b13ebdb39f3fa271d7c49bf5">llvm::coro::BaseCloner::Suffix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4a2c249a520c88badf6f400e74f26ce424">llvm::coro::SwitchCleanup</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a817ca8bc950897f8f548f58d746d03d2">llvm::coro::BaseCloner::VMap</a>.</p>


<p>Referenced by <a href="#a4e4793514f814a12dc765fc5cdefb996">createClone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createClone() {#a4e4793514f814a12dc765fc5cdefb996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::coro::SwitchCloner::createClone (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OrigF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Suffix, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad5c7ebab0ec481424c33db8902c652f4">CloneKind</a> FKind, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a91897d2d0da113b016f14ae110586ab1">MetadataSetTy</a> &amp; CommonDebugInfo)</td>
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

<p>Create a clone for a switch lowering.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocloner-h">CoroCloner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a38506d5e7b2f1915b1578ba729c1ca89">llvm::coro::BaseCloner::CommonDebugInfo</a>, <a href="#a402d5de6c6250d90988f455ada737600">create</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#aa92eee9e4cc8d96f072ac2887d82eb6e">llvm::coro::BaseCloner::FKind</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#ac98805013f6c223eac46908a5798cc14">llvm::coro::BaseCloner::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a567c0d086b740b39c9bfd703e0cf2908">llvm::coro::BaseCloner::OrigF</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a7288c19a015ef21ca88686272daa99bd">llvm::coro::BaseCloner::Shape</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#aa8abf978b13ebdb39f3fa271d7c49bf5">llvm::coro::BaseCloner::Suffix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>, <a href="#ac1a0f607ea14257093cd8eaeb09f0ddc">SwitchCloner</a> and <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a6472b6d2ecf3c53f5e7ddc8cf0a803bb">llvm::coro::BaseCloner::TTI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af34178528cc721dfa273965733da1f37">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::split</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
