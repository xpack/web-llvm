---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-objcarccontract-cpp-/objcarccontract
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ObjCARCContract` Class Reference

<p>Late ARC optimizations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ObjCARCContract.cpp}::ObjCARCContract { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a570e40ac0ef6ab8c6da15e3670a50371">init</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b6cfbee1f1d7c9f17eb52722c89564d">run</a> (Function &amp;F, AAResults *AA, DominatorTree *DT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a5a18d67ed34c256cc2a666d9b2ce5e">hasCFGChanged</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a741117ce671a025330b97e5604cf4d00">tryToPeepholeInstruction</a> (Function &amp;F, Instruction *Inst, inst_iterator &amp;Iter, bool &amp;TailOkForStoreStrong, const DenseMap&lt; BasicBlock *, ColorVector &gt; &amp;BlockColors)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we eliminated Inst. <a href="#a741117ce671a025330b97e5604cf4d00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f0fde9cd5b3738974c06d706cba0a7a">optimizeRetainCall</a> (Function &amp;F, Instruction *Retain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn objc_retain into objc_retainAutoreleasedReturnValue if the operand is a return value. <a href="#a9f0fde9cd5b3738974c06d706cba0a7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a45dc49e811f4701890d20a462bd46">contractAutorelease</a> (Function &amp;F, Instruction *Autorelease, ARCInstKind Class)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge an autorelease with a retain into a fused call. <a href="#ae3a45dc49e811f4701890d20a462bd46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebaa7a1552e9e558ba84e8f8c41e78d2">tryToContractReleaseIntoStoreStrong</a> (Instruction *Release, inst_iterator &amp;Iter, const DenseMap&lt; BasicBlock *, ColorVector &gt; &amp;BlockColors)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to merge an objc_release with a store, load, and objc_retain to form an objc_storeStrong. <a href="#aebaa7a1552e9e558ba84e8f8c41e78d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac93441ebcef865bff0fad2d1f650a165">Changed</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063e9c6432635c82aaaea4b1e188b387">CFGChanged</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e218f690b3ac45c120f4926f4390a13">AA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d86c226d6b6635742d79e9a7bb2ca5">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/provenanceanalysis">ProvenanceAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4ba6cf634c0ebc116e4d46210739167">PA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcarc/arcruntimeentrypoints">ARCRuntimeEntryPoints</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c6ae7f033213dbf824528d819fd4321">EP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcarc/bundledretainclaimrvs">BundledRetainClaimRVs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076cc92802ae4830a9655e1e098811b3">BundledInsts</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3a74c90f201291adc48f60f9b98344e">Run</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A flag indicating whether this optimization pass should run. <a href="#aa3a74c90f201291adc48f60f9b98344e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44cb0da724be23e39cd769ad7bb0b739">RVInstMarker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The inline asm string to insert between calls and RetainRV calls to make the optimization work on targets which need it. <a href="#a44cb0da724be23e39cd769ad7bb0b739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd807d0971ac37d2cf2a3465a905a41">StoreStrongCalls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of inserted objc_storeStrong calls. <a href="#a9fd807d0971ac37d2cf2a3465a905a41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Late ARC optimizations.</p>


<p>These change the IR in a way that makes it difficult to be analyzed by ObjCARCOpt, so it's run late.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### hasCFGChanged() {#a4a5a18d67ed34c256cc2a666d9b2ce5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCContract.cpp}::ObjCARCContract::hasCFGChanged ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### init() {#a570e40ac0ef6ab8c6da15e3670a50371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjCARCContract::init (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#ae66979a0bd797acd1ecb566a721fd73a">llvm::objcarc::getRVInstMarker</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a255df46f4454af8706323670d5e7f7b6">llvm::objcarc::ModuleHasARC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontractlegacypass/#ab643320efd2f4aacb0288787aa68ad5a">anonymous{ObjCARCContract.cpp}::ObjCARCContractLegacyPass::runOnFunction</a>.</p>

</div>
</div>

### run() {#a6b6cfbee1f1d7c9f17eb52722c89564d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjCARCContract::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a2d071e661a02790177ba05f62c7c27d1">llvm::BasicBlock::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3a97fed79c86bf242b0f090e1cb2e6">llvm::colorEHFunclets</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a6771e7364c5ab8a6354f744fe5bbc62b">llvm::objcarc::EnableARCOpts</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a7110df32902106ee880a19371b45d763">llvm::objcarc::getEquivalentPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca414c43a6d42c13998208463637a20d">llvm::PHINode::getIncomingValueNumForOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/use/#a541187eb976df2189b40b3f62ed2cee0">llvm::Use::getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a928f57745ef3ec4a823afdf7100a70ad">llvm::PHINode::getOperandNumForIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aefba9af2f61452f20f4c947b4c2e5f4e">llvm::objcarc::hasAttachedCallOpBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a49a219f3fe3d7a6cc07c49a1ea766d6d">llvm::inst_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a945cded5463e0ccd3cf5a6ac80542a94">llvm::inst_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5309dbf19ec5ccffe3072c6087e106d3">llvm::isScopedEHPersonality</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#acff66a4cb0efaafb728848edf097c75f">llvm::CallInst::setTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a413abcab8dbc3900fc2fde96a5d8fca6">llvm::Value::use_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad86469939d2a8bdd4169be9403b89f5a">llvm::Value::use_end</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontractlegacypass/#ab643320efd2f4aacb0288787aa68ad5a">anonymous{ObjCARCContract.cpp}::ObjCARCContractLegacyPass::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### contractAutorelease() {#ae3a45dc49e811f4701890d20a462bd46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjCARCContract::contractAutorelease (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Autorelease, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2">ARCInstKind</a> Class)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge an autorelease with a retain into a fused call.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### optimizeRetainCall() {#a9f0fde9cd5b3738974c06d706cba0a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjCARCContract::optimizeRetainCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Retain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Turn objc_retain into objc_retainAutoreleasedReturnValue if the operand is a return value.</p>


<p>We do this late so we do not disrupt the dataflow analysis in ObjCARCOpt.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### tryToContractReleaseIntoStoreStrong() {#aebaa7a1552e9e558ba84e8f8c41e78d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ObjCARCContract::tryToContractReleaseIntoStoreStrong (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Release, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c27cc387928f22d241825cf0fb67ade">inst_iterator</a> &amp; Iter, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#ac16c24df0637600996c9c6081da170a2">ColorVector</a> &gt; &amp; BlockColors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to merge an objc_release with a store, load, and objc_retain to form an objc_storeStrong.</p>


<p>An objc_storeStrong:</p>


<p>objc_storeStrong(i8** old_ptr, i8* new_value)</p>


<p>is equivalent to the following IR sequence:</p>


<p>; Load old value. old_value = load i8** old_ptr (1)</p>


<p>; Increment the new value and then release the old value. This must occur ; in order in case old_value releases new_value in its destructor causing ; us to potentially have a dangling ptr. tail call i8* @objc_retain(i8* new_value) (2) tail call void @objc_release(i8* old_value) (3)</p>


<p>; Store the new_value into old_ptr store i8* new_value, i8** old_ptr (4)</p>


<p>The safety of this optimization is based around the following considerations:</p>


<ol class="doxyList" type="1">
<li>We are forming the store strong at the store. Thus to perform this optimization it must be safe to move the retain, load, and release to (4).</li>
<li>We need to make sure that any re-orderings of (1), (2), (3), (4) are safe.</li>
</ol>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### tryToPeepholeInstruction() {#a741117ce671a025330b97e5604cf4d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ObjCARCContract::tryToPeepholeInstruction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c27cc387928f22d241825cf0fb67ade">inst_iterator</a> &amp; Iter, bool &amp; TailOkForStoreStrong, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#ac16c24df0637600996c9c6081da170a2">ColorVector</a> &gt; &amp; BlockColors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we eliminated Inst.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a9e218f690b3ac45c120f4926f4390a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* anonymous{ObjCARCContract.cpp}::ObjCARCContract::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### BundledInsts {#a076cc92802ae4830a9655e1e098811b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BundledRetainClaimRVs* anonymous{ObjCARCContract.cpp}::ObjCARCContract::BundledInsts = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### CFGChanged {#a063e9c6432635c82aaaea4b1e188b387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCContract.cpp}::ObjCARCContract::CFGChanged</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### Changed {#ac93441ebcef865bff0fad2d1f650a165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCContract.cpp}::ObjCARCContract::Changed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### DT {#ac8d86c226d6b6635742d79e9a7bb2ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{ObjCARCContract.cpp}::ObjCARCContract::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### EP {#a0c6ae7f033213dbf824528d819fd4321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARCRuntimeEntryPoints anonymous{ObjCARCContract.cpp}::ObjCARCContract::EP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### PA {#af4ba6cf634c0ebc116e4d46210739167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProvenanceAnalysis anonymous{ObjCARCContract.cpp}::ObjCARCContract::PA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### Run {#aa3a74c90f201291adc48f60f9b98344e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCContract.cpp}::ObjCARCContract::Run</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A flag indicating whether this optimization pass should run.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### RVInstMarker {#a44cb0da724be23e39cd769ad7bb0b739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MDString* anonymous{ObjCARCContract.cpp}::ObjCARCContract::RVInstMarker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The inline asm string to insert between calls and RetainRV calls to make the optimization work on targets which need it.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

### StoreStrongCalls {#a9fd807d0971ac37d2cf2a3465a905a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;CallInst *, 8&gt; anonymous{ObjCARCContract.cpp}::ObjCARCContract::StoreStrongCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of inserted objc_storeStrong calls.</p>


<p>If at the end of walking the function we have found no alloca instructions, these calls can be marked "tail".</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarccontract-cpp">ObjCARCContract.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
