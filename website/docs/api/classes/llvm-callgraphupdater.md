---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/callgraphupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CallGraphUpdater` Class Reference

<p>Wrapper to unify "old style" <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> and "new style" <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CallGraphUpdater { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">llvm/Transforms/Utils/CallGraphUpdater.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf207c249d5794e98ce3af84899084fb">CallGraphUpdater</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#acf207c249d5794e98ce3af84899084fb">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74348fa9965bac055506a423cb9135d0">~CallGraphUpdater</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6cf8d3b5860ad0bd100b0a30da27e7f">initialize</a> (LazyCallGraph &amp;LCG, LazyCallGraph::SCC &amp;SCC, CGSCCAnalysisManager &amp;AM, CGSCCUpdateResult &amp;UR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializers for usage outside of a CGSCC pass, inside a CGSCC pass in the old and new pass manager (PM). <a href="#aa6cf8d3b5860ad0bd100b0a30da27e7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adecede763aee9d37e00fee2c2328ac7e">finalize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#adecede763aee9d37e00fee2c2328ac7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300122a2a53b922943eff21c4039ad73">removeFunction</a> (Function &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <span class="doxyComputerOutput">Fn</span> from the call graph. <a href="#a300122a2a53b922943eff21c4039ad73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf8126709349339746d58096776d4f3">reanalyzeFunction</a> (Function &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After an CGSCC pass changes a function in ways that affect the call graph, this method can be called to update it. <a href="#a7bf8126709349339746d58096776d4f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08fe25aef5a7fa6ebb858ee29125ce9a">registerOutlinedFunction</a> (Function &amp;OriginalFn, Function &amp;NewFn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a new function was created by outlining, this method can be called to update the call graph for the new function. <a href="#a08fe25aef5a7fa6ebb858ee29125ce9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3153d95e005c433416597836e80331d2">replaceFunctionWith</a> (Function &amp;OldFn, Function &amp;NewFn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace <span class="doxyComputerOutput">OldFn</span> in the call graph (and SCC) with <span class="doxyComputerOutput">NewFn</span>. <a href="#a3153d95e005c433416597836e80331d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0cf5c0b5a1d8c365a33ddc00b85f17a">ReplacedFunctions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Containers for functions which we did replace or want to delete when <span class="doxyComputerOutput">finalize</span> is called. <a href="#ac0cf5c0b5a1d8c365a33ddc00b85f17a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca49f7ebd7ac4e8ced644f79e58bbd9c">DeadFunctions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b07505f348a1dde8deb3c5a67746931">DeadFunctionsInComdats</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06c6aef16eb3c6129d6ceeba9730837a">LCG</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a06c6aef16eb3c6129d6ceeba9730837a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af466284b2c0bf46b340b1c8896cc3aa8">SCC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db5c7f9b2ff853895c5d65966706750">AM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/cgsccupdateresult">CGSCCUpdateResult</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed53a195e61b3ac1183b947735d74fee">UR</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab512360d69465acb8bee3d296e04fd87">FAM</a> = nullptr</td>
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

<p>Wrapper to unify "old style" <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> and "new style" <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a>.</p>


<p>This simplifies the interface and the call sites, e.g., new and old pass manager passes can share the same code.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallGraphUpdater() {#acf207c249d5794e98ce3af84899084fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallGraphUpdater::CallGraphUpdater ()</td>
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

<p>}</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CallGraphUpdater() {#a74348fa9965bac055506a423cb9135d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallGraphUpdater::~CallGraphUpdater ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>


<p>Reference <a href="#adecede763aee9d37e00fee2c2328ac7e">finalize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalize() {#adecede763aee9d37e00fee2c2328ac7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallGraphUpdater::finalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>


<p>Finalizer that will trigger actions like function removal from the CG.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callgraphupdater-cpp">CallGraphUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad1d412633e05b10c6b4be309b010a13f">llvm::filterDeadComdatFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a74348fa9965bac055506a423cb9135d0">~CallGraphUpdater</a>.</p>

</div>
</div>

### initialize() {#aa6cf8d3b5860ad0bd100b0a30da27e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallGraphUpdater::initialize (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; LCG, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> &amp; SCC, <a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/structs/llvm/cgsccupdateresult">CGSCCUpdateResult</a> &amp; UR)</td>
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

<p>Initializers for usage outside of a CGSCC pass, inside a CGSCC pass in the old and new pass manager (PM).</p>


<p>{</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributorcgsccpass/#a305cbdd90350f05f5ee772811d596ded">llvm::AttributorCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightcgsccpass/#a1725467ef5883a44e7777d681c6a4d32">llvm::AttributorLightCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a>.</p>

</div>
</div>

### reanalyzeFunction() {#a7bf8126709349339746d58096776d4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraphUpdater::reanalyzeFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After an CGSCC pass changes a function in ways that affect the call graph, this method can be called to update it.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callgraphupdater-cpp">CallGraphUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2e739fb4907159062aacbbafea669592">llvm::updateCGAndAnalysisManagerForCGSCCPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a30e276f415c0b092317585c37160f9ce">runAttributorOnFunctions</a>.</p>

</div>
</div>

### registerOutlinedFunction() {#a08fe25aef5a7fa6ebb858ee29125ce9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraphUpdater::registerOutlinedFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OriginalFn, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; NewFn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a new function was created by outlining, this method can be called to update the call graph for the new function.</p>


<p>Note that the old one still needs to be re-analyzed or manually updated.</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callgraphupdater-cpp">CallGraphUpdater.cpp</a>.</p>

</div>
</div>

### removeFunction() {#a300122a2a53b922943eff21c4039ad73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraphUpdater::removeFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove <span class="doxyComputerOutput">Fn</span> from the call graph.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callgraphupdater-cpp">CallGraphUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a0020cbf9c3df714558a9b20a6267bd29">llvm::Function::deleteBody</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a8dade004a4e4da60bc0f49eb51176ef4">llvm::GlobalObject::hasComdat</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a687973de03d041e04b50a76d19d4fd36">llvm::GlobalValue::setLinkage</a>.</p>


<p>Referenced by <a href="#a3153d95e005c433416597836e80331d2">replaceFunctionWith</a>.</p>

</div>
</div>

### replaceFunctionWith() {#a3153d95e005c433416597836e80331d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraphUpdater::replaceFunctionWith (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OldFn, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; NewFn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace <span class="doxyComputerOutput">OldFn</span> in the call graph (and SCC) with <span class="doxyComputerOutput">NewFn</span>.</p>


<p>The uses outside the call graph and the function <span class="doxyComputerOutput">OldFn</span> are not modified. Note that <span class="doxyComputerOutput">OldFn</span> is also removed from the call graph (</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a300122a2a53b922943eff21c4039ad73">removeFunction</a>).</p></dd>
</dl>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callgraphupdater-cpp">CallGraphUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constant/#a960620248182018e566b095f06a605df">llvm::Constant::removeDeadConstantUsers</a> and <a href="#a300122a2a53b922943eff21c4039ad73">removeFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a30e276f415c0b092317585c37160f9ce">runAttributorOnFunctions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AM {#a3db5c7f9b2ff853895c5d65966706750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGSCCAnalysisManager* llvm::CallGraphUpdater::AM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>

</div>
</div>

### DeadFunctions {#aca49f7ebd7ac4e8ced644f79e58bbd9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Function *, 16&gt; llvm::CallGraphUpdater::DeadFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>

</div>
</div>

### DeadFunctionsInComdats {#a3b07505f348a1dde8deb3c5a67746931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Function *, 16&gt; llvm::CallGraphUpdater::DeadFunctionsInComdats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>

</div>
</div>

### FAM {#ab512360d69465acb8bee3d296e04fd87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAnalysisManager* llvm::CallGraphUpdater::FAM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>

</div>
</div>

### LCG {#a06c6aef16eb3c6129d6ceeba9730837a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph* llvm::CallGraphUpdater::LCG = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>


<p>New PM variables {</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>

</div>
</div>

### ReplacedFunctions {#ac0cf5c0b5a1d8c365a33ddc00b85f17a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Function *, 16&gt; llvm::CallGraphUpdater::ReplacedFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Containers for functions which we did replace or want to delete when <span class="doxyComputerOutput">finalize</span> is called.</p>


<p>This can happen explicitly or as part of the destructor. Dead functions in comdat sections are tracked separately because a function with discardable linakage in a COMDAT should only be dropped if the entire COMDAT is dropped, see git ac07703842cf. {</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>

</div>
</div>

### SCC {#af466284b2c0bf46b340b1c8896cc3aa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph::SCC* llvm::CallGraphUpdater::SCC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>

</div>
</div>

### UR {#aed53a195e61b3ac1183b947735d74fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGSCCUpdateResult* llvm::CallGraphUpdater::UR = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callgraphupdater-h">CallGraphUpdater.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callgraphupdater-cpp">CallGraphUpdater.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
