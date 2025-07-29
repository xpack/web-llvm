---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/moduleinlinerpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ModuleInlinerPass` Class

<p>The module inliner pass for the new pass manager. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ModuleInlinerPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">llvm/Transforms/IPO/ModuleInliner.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e6c07945bdbd25d2c8b0255a63663e">ModuleInlinerPass</a> (InlineParams Params=getInlineParams(), InliningAdvisorMode Mode=InliningAdvisorMode::Default, ThinOrFullLTOPhase LTOPhase=ThinOrFullLTOPhase::None)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb981cb8865a526a79cabb5e74d1034">ModuleInlinerPass</a> (ModuleInlinerPass &amp;&amp;Arg)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7155781c9a6aafef322de28d9bc4c86">run</a> (Module &amp;, ModuleAnalysisManager &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72417bf5ee762b3f95f4cfb313dc1a8">getAdvisor</a> (const ModuleAnalysisManager &amp;MAM, FunctionAnalysisManager &amp;FAM, Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70bc92f9ad15e9c94b58a91fca1294cb">OwnedAdvisor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada52c92221a96ca4fe4dea9b1fe9195c">Params</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a239c4ac35d6028bfacaed4018d0488fa">InliningAdvisorMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5ba4e933858b12867b0c4b2089e72e">Mode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad111ca20f0c9a230a513ca519ef3d778">LTOPhase</a></td>
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

<p>The module inliner pass for the new pass manager.</p>


<p>This pass wires together the inlining utilities and the inline cost analysis into a module pass. Different from SCC inliner, it considers every call in every function in the whole module and tries to inline if profitable. With this module level inliner, it is possible to evaluate more heuristics in the module level such like PriorityInlineOrder. It can be tuned with a number of parameters to control what cost model is used and what tradeoffs are made when making the decision.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ModuleInlinerPass() {#a27e6c07945bdbd25d2c8b0255a63663e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ModuleInlinerPass::ModuleInlinerPass (<a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a> Params=<a href="/web-llvm/docs/api/namespaces/llvm/#aba7063dea024346c7b70099c63703f50">getInlineParams</a>(), <a href="/web-llvm/docs/api/namespaces/llvm/#a239c4ac35d6028bfacaed4018d0488fa">InliningAdvisorMode</a> Mode=<a href="/web-llvm/docs/api/namespaces/llvm/#a239c4ac35d6028bfacaed4018d0488faa7a1920d61156abc05a60135aefe8bc67">InliningAdvisorMode::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> LTOPhase=<a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a6adf97f83acf6453d4a6a4b1070f3754">ThinOrFullLTOPhase::None</a>)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a239c4ac35d6028bfacaed4018d0488faa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="#adfb981cb8865a526a79cabb5e74d1034">ModuleInlinerPass</a>.</p>

</div>
</div>

### ModuleInlinerPass() {#adfb981cb8865a526a79cabb5e74d1034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ModuleInlinerPass::ModuleInlinerPass (<a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass">ModuleInlinerPass</a> &amp;&amp; Arg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a> and <a href="#a27e6c07945bdbd25d2c8b0255a63663e">ModuleInlinerPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#ab7155781c9a6aafef322de28d9bc4c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses ModuleInlinerPass::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/moduleinliner-cpp">ModuleInliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysis/#a4dd66bb1f3a24ebaf94d2f204a700e4a">llvm::CtxProfAnalysis::collectIndirectCallPromotionList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/moduleinliner-cpp/#a6e6ccf80a7fe29b98a4cad16d4a4fc59">CtxProfPromoteAlwaysInline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#af70fa833673e4ac07c323a4a94e7ba93">llvm::InlineAdvisor::getAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#afac5b39bcbb90d660f83d9b4bd8c6d95">llvm::CallBase::getCaller</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7acaa9d2987b3c0842cc1a758bfcb0d0">llvm::getInlineOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinefunctioninfo/#afee77c39305987451e9495b749863d07">llvm::InlineFunctionInfo::InlinedCallSites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp/#a12a3c37c6bd2a94f388aafe4e68462f1">inlineHistoryIncludes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#af481ee3f81ad12db32ea0df13ec4b0d0">isKnownLibFunction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#ab2cc3a8b2ee3d65fd980f63923fa2880">llvm::InlineAdvisor::onPassEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#adb8650aeef845449ba752a76a4237559">llvm::InlineAdvisor::onPassExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23c23396eb61a7a78555e926700dbf47">llvm::promoteCallWithIfThenElse</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a444e3e622a00db2be6dcaf46cef996f5">llvm::setInlineRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getAdvisor() {#aa72417bf5ee762b3f95f4cfb313dc1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAdvisor &amp; ModuleInlinerPass::getAdvisor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/moduleinliner-cpp">ModuleInliner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LTOPhase {#ad111ca20f0c9a230a513ca519ef3d778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ThinOrFullLTOPhase llvm::ModuleInlinerPass::LTOPhase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a>.</p>

</div>
</div>

### Mode {#a5f5ba4e933858b12867b0c4b2089e72e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InliningAdvisorMode llvm::ModuleInlinerPass::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a>.</p>

</div>
</div>

### OwnedAdvisor {#a70bc92f9ad15e9c94b58a91fca1294cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InlineAdvisor&gt; llvm::ModuleInlinerPass::OwnedAdvisor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a>.</p>

</div>
</div>

### Params {#ada52c92221a96ca4fe4dea9b1fe9195c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InlineParams llvm::ModuleInlinerPass::Params</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/moduleinliner-h">ModuleInliner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/moduleinliner-cpp">ModuleInliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
