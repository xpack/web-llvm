---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/gcrootlowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `GCRootLowering.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">llvm/CodeGen/GCMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">llvm/CodeGen/TargetFrameLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-gcrootlowering-cpp-">anonymous{GCRootLowering.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics">LowerIntrinsics</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics">LowerIntrinsics</a> - This pass rewrites calls to the llvm.gcread or llvm.gcwrite intrinsics, replacing them with simple loads and stores as directed by the <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a>. <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis">GCMachineCodeAnalysis</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis">GCMachineCodeAnalysis</a> - This is a target-independent pass over the machine function representation to identify safe points for the garbage collector in the machine code. <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a> (Function &amp;F, GCStrategy &amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lower barriers out of existence (if the associated <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> hasn't already done so...), and insert initializing stores to roots as a defensive measure. <a href="#a755b4fb8450994d9125dbcd317bc4fc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a8fc5324b2cf8a0a85f04893fada09">INITIALIZE_PASS_BEGIN</a> (LowerIntrinsics, "gc-lowering", "GC Lowering", false, false) FunctionPass *llvm</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca4a195657130ed6e1819daa858a9f4">CouldBecomeSafePoint</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CouldBecomeSafePoint - <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> to conservatively determine whether the instruction could introduce a safe point. <a href="#a6ca4a195657130ed6e1819daa858a9f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30fa2dcf27667bbd19dd20ccdac2ce96">InsertRootInitializers</a> (Function &amp;F, ArrayRef&lt; AllocaInst * &gt; Roots)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d1d920446ddefc1569ffbe2485a31e">INITIALIZE_PASS</a> (GCMachineCodeAnalysis, "gc-analysis", "Analyze Machine Code For Garbage Collection", false, false) GCMachineCodeAnalysis</td>
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

## Functions

### CouldBecomeSafePoint() {#a6ca4a195657130ed6e1819daa858a9f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CouldBecomeSafePoint (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>CouldBecomeSafePoint - <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> to conservatively determine whether the instruction could introduce a safe point.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp">GCRootLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a30fa2dcf27667bbd19dd20ccdac2ce96">InsertRootInitializers</a>.</p>

</div>
</div>

### DoLowering() {#a755b4fb8450994d9125dbcd317bc4fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DoLowering (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> &amp; S)</td>
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

<p>Lower barriers out of existence (if the associated <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> hasn't already done so...), and insert initializing stores to roots as a defensive measure.</p>


<p>Given we're going to report all roots live at all safepoints, we need to be able to ensure each root has been initialized by the point the first safepoint is reached. This really should have been done by the frontend, but the old API made this non-obvious, so we do a potentially redundant store just in case.</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp">GCRootLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a30fa2dcf27667bbd19dd20ccdac2ce96">InsertRootInitializers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a966eb231e7d4e572874d2cb49b18faea">llvm::Value::stripPointerCasts</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcloweringpass/#aa642143ff84b39a1e644a6435f69b643">llvm::GCLoweringPass::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/lowerintrinsics/#af8839af043a33c29a875d4dddb11a095">anonymous{GCRootLowering.cpp}::LowerIntrinsics::runOnFunction</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a46d1d920446ddefc1569ffbe2485a31e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (GCMachineCodeAnalysis, "gc-analysis", "Analyze <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> Code For Garbage Collection", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp">GCRootLowering.cpp</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#af6a8fc5324b2cf8a0a85f04893fada09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (LowerIntrinsics, "gc-lowering", "GC Lowering", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp">GCRootLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a10b0b5e5a7e5afb8037a4c2b006b7425">llvm::createGCLoweringPass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a74ce8276b89067e806f67c45a6d92575">INITIALIZE_PASS_END</a>.</p>

</div>
</div>

### InsertRootInitializers() {#a30fa2dcf27667bbd19dd20ccdac2ce96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InsertRootInitializers (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; Roots)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp">GCRootLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a6ca4a195657130ed6e1819daa858a9f4">CouldBecomeSafePoint</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
