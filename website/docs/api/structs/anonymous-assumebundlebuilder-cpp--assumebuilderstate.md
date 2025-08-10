---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AssumeBuilderState` Struct

<p>This class contain all knowledge that have been gather while building an llvm.assume and the function to manipulate it. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad886c9b221cb58d34773ae1ed4d1de13">MapKey</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, Attribute::AttrKind &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb042df2c65c8ffdbd2ad3f4ef776a0">AssumeBuilderState</a> (Module *M, Instruction *I=nullptr, AssumptionCache *AC=nullptr, DominatorTree *DT=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba1e9ea5dd5dfc2b1559cb6cef8b4854">tryToPreserveWithoutAddingAssume</a> (RetainedKnowledge RK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a336ed98852175e7e955e9217080bd596">isKnowledgeWorthPreserving</a> (RetainedKnowledge RK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201cb1ede84e08442e7433b7b3eaed69">addKnowledge</a> (RetainedKnowledge RK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa411f806557fdaf4af309b7c541757d2">addAttribute</a> (Attribute Attr, Value *WasOn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f30a0c0c861405e3eeb6f37c364256">addCall</a> (const CallBase *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumeinst">AssumeInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadca3692ce40afeb83b7765b2d7dfc9c">build</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65edce9c8505e3d3b9c0d90794458288">addAccessedPtr</a> (Instruction *MemInst, Value *Pointer, Type *AccType, MaybeAlign MA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b26cb5a9ef4ba045eb41d823d5452fd">addInstruction</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f5fabd5b5284966c165b333edc224b">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt; <a href="#ad886c9b221cb58d34773ae1ed4d1de13">MapKey</a>, uint64_t, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65f222afb3a675224b4c9f831c8dac4d">AssumedKnowledgeMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de43e66fb4557fb1bc404baf26921ea">InstBeingModified</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fe30b4d2b60208cb9144dad2c633061">AC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c0db381044a9677d7c01b42ba94aad4">DT</a> = nullptr</td>
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

<p>This class contain all knowledge that have been gather while building an llvm.assume and the function to manipulate it.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MapKey {#ad886c9b221cb58d34773ae1ed4d1de13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::MapKey =  std::pair&lt;Value *, Attribute::AttrKind&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AssumeBuilderState() {#aaeb042df2c65c8ffdbd2ad3f4ef776a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::AssumeBuilderState (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC=nullptr, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT=nullptr)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="#a3fe30b4d2b60208cb9144dad2c633061">AC</a>, <a href="#a3c0db381044a9677d7c01b42ba94aad4">DT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0de43e66fb4557fb1bc404baf26921ea">InstBeingModified</a> and <a href="#aa0f5fabd5b5284966c165b333edc224b">M</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae6e6df995a78f3f11ddd275c0c8aa840">llvm::buildAssumeFromInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a855f472cab89fb74cbc7075b164d78f0">llvm::buildAssumeFromKnowledge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5df9c7cb06c08a066a30482d77cc1d9">llvm::salvageKnowledge</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a21fa9fb3ba25eaa02fae01f428ef2fdf">llvm::simplifyRetainedKnowledge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAccessedPtr() {#a65edce9c8505e3d3b9c0d90794458288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAccessedPtr (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MemInst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Pointer, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccType, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> MA)</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="#a201cb1ede84e08442e7433b7b3eaed69">addKnowledge</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#abcbe492bce3ccc16e0bbb50292576c5c">llvm::Module::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acfcd22eb38dbfe1acbf138754297437a">llvm::DataLayout::getTypeStoreSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b03ed78a8e299bde6d26a8793cd4e06">llvm::NullPointerIsDefined</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a> and <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a06846474be3ab85f8d30c388faf3b116">llvm::MaybeAlign::valueOrOne</a>.</p>


<p>Referenced by <a href="#a5b26cb5a9ef4ba045eb41d823d5452fd">addInstruction</a>.</p>

</div>
</div>

### addAttribute() {#aa411f806557fdaf4af309b7c541757d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * WasOn)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="#a201cb1ede84e08442e7433b7b3eaed69">addKnowledge</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a6fea074fd9120ff82abd8f9e0036a12a">llvm::Attribute::getKindAsEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a1db9b109e0e28e38eb43086b679dc271">llvm::Attribute::getValueAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a142250c7b671591390912db907532036">llvm::Attribute::isIntAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a0571df3e57128211e09cba4544aa9ca7">llvm::Attribute::isStringAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#ab6fc71def3a243f7c93d39db21344240">llvm::Attribute::isTypeAttribute</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#ab3399afc79b7612b8471c010d3f3638e">anonymous{AssumeBundleBuilder.cpp}::isUsefullToPreserve</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a12da95fe38123989367507860f4fe328">llvm::ShouldPreserveAllAttributes</a>.</p>


<p>Referenced by <a href="#a80f30a0c0c861405e3eeb6f37c364256">addCall</a>.</p>

</div>
</div>

### addCall() {#a80f30a0c0c861405e3eeb6f37c364256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="#aa411f806557fdaf4af309b7c541757d2">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a1cf553641e8527095ae4c8ec88a2cd92">llvm::AttributeList::getFnAttrs</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ada7a173c40ca7ac048a4b7099ceb71c0">llvm::AttributeList::getParamAttrs</a>.</p>


<p>Referenced by <a href="#a5b26cb5a9ef4ba045eb41d823d5452fd">addInstruction</a>.</p>

</div>
</div>

### addInstruction() {#a5b26cb5a9ef4ba045eb41d823d5452fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="#a65edce9c8505e3d3b9c0d90794458288">addAccessedPtr</a>, <a href="#a80f30a0c0c861405e3eeb6f37c364256">addCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### addKnowledge() {#a201cb1ede84e08442e7433b7b3eaed69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addKnowledge (<a href="/web-llvm/docs/api/structs/llvm/retainedknowledge">RetainedKnowledge</a> RK)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a3b64a97b9157b9bd9a1d924cae66254b">llvm::RetainedKnowledge::ArgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a65f222afb3a675224b4c9f831c8dac4d">AssumedKnowledgeMap</a>, <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a054a26c551d4de8f1af4d75a7a67a42a">llvm::RetainedKnowledge::AttrKind</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-assumebundlebuilder-cpp-/#ae3d9d3b5408e22143d8aee0d684454c4">anonymous{AssumeBundleBuilder.cpp}::canonicalizedKnowledge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="#a336ed98852175e7e955e9217080bd596">isKnowledgeWorthPreserving</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#ac28513e2e067144d291d2d8f0301b61a">Lookup</a>, <a href="#aa0f5fabd5b5284966c165b333edc224b">M</a>, <a href="#aba1e9ea5dd5dfc2b1559cb6cef8b4854">tryToPreserveWithoutAddingAssume</a> and <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a99ac6afa72b262e95ceb85328c6cb5c6">llvm::RetainedKnowledge::WasOn</a>.</p>


<p>Referenced by <a href="#a65edce9c8505e3d3b9c0d90794458288">addAccessedPtr</a>, <a href="#aa411f806557fdaf4af309b7c541757d2">addAttribute</a> and <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0d8e70094baa4fcc5eb68b59de54dc92">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeRange</a>.</p>

</div>
</div>

### build() {#aadca3692ce40afeb83b7765b2d7dfc9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumeInst * anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::build ()</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="#a65f222afb3a675224b4c9f831c8dac4d">AssumedKnowledgeMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a9f1de7d65958c48ef95760927081625c">llvm::Attribute::getNameFromAttrKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="#aa0f5fabd5b5284966c165b333edc224b">M</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a5aace8653ce3726ef07194dcf6bce2bf">llvm::DebugCounter::shouldExecute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0d8e70094baa4fcc5eb68b59de54dc92">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeRange</a>.</p>

</div>
</div>

### isKnowledgeWorthPreserving() {#a336ed98852175e7e955e9217080bd596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::isKnowledgeWorthPreserving (<a href="/web-llvm/docs/api/structs/llvm/retainedknowledge">RetainedKnowledge</a> RK)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a3b64a97b9157b9bd9a1d924cae66254b">llvm::RetainedKnowledge::ArgValue</a>, <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a054a26c551d4de8f1af4d75a7a67a42a">llvm::RetainedKnowledge::AttrKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7ae600e148910c49a1772ce51754141c">llvm::Value::getSingleUndroppableUse</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="#a0de43e66fb4557fb1bc404baf26921ea">InstBeingModified</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#ac2d5f8ba4215304f89a401248abed393">llvm::Attribute::isIntAttrKind</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>, <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a99ac6afa72b262e95ceb85328c6cb5c6">llvm::RetainedKnowledge::WasOn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a845142f96a84f067cb6bf639e37980d0">llvm::wouldInstructionBeTriviallyDead</a>.</p>


<p>Referenced by <a href="#a201cb1ede84e08442e7433b7b3eaed69">addKnowledge</a>.</p>

</div>
</div>

### tryToPreserveWithoutAddingAssume() {#aba1e9ea5dd5dfc2b1559cb6cef8b4854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::tryToPreserveWithoutAddingAssume (<a href="/web-llvm/docs/api/structs/llvm/retainedknowledge">RetainedKnowledge</a> RK)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af36ce2c8e7a209b35ea79a00f0621852a1db3cb6d53ab5e73d0d8b9e1afaa26ce">llvm::ABA_Argument</a>, <a href="#a3fe30b4d2b60208cb9144dad2c633061">AC</a>, <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo/#af823d55c0067f516522508d1a38b2992">llvm::CallBase::BundleOpInfo::Begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a3c0db381044a9677d7c01b42ba94aad4">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ade489c0f3b2b272cfcf0bb8f011399">llvm::getKnowledgeForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="#a0de43e66fb4557fb1bc404baf26921ea">InstBeingModified</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f7c11444c9e7d7c1036ae1f049f4cee">llvm::isValidAssumeForContext</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a> and <a href="/web-llvm/docs/api/structs/llvm/retainedknowledge/#a99ac6afa72b262e95ceb85328c6cb5c6">llvm::RetainedKnowledge::WasOn</a>.</p>


<p>Referenced by <a href="#a201cb1ede84e08442e7433b7b3eaed69">addKnowledge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AC {#a3fe30b4d2b60208cb9144dad2c633061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::AC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#aaeb042df2c65c8ffdbd2ad3f4ef776a0">AssumeBuilderState</a> and <a href="#aba1e9ea5dd5dfc2b1559cb6cef8b4854">tryToPreserveWithoutAddingAssume</a>.</p>

</div>
</div>

### AssumedKnowledgeMap {#a65f222afb3a675224b4c9f831c8dac4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallMapVector&lt;MapKey, uint64_t, 8&gt; anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::AssumedKnowledgeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a201cb1ede84e08442e7433b7b3eaed69">addKnowledge</a> and <a href="#aadca3692ce40afeb83b7765b2d7dfc9c">build</a>.</p>

</div>
</div>

### DT {#a3c0db381044a9677d7c01b42ba94aad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#aaeb042df2c65c8ffdbd2ad3f4ef776a0">AssumeBuilderState</a> and <a href="#aba1e9ea5dd5dfc2b1559cb6cef8b4854">tryToPreserveWithoutAddingAssume</a>.</p>

</div>
</div>

### InstBeingModified {#a0de43e66fb4557fb1bc404baf26921ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::InstBeingModified = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#aaeb042df2c65c8ffdbd2ad3f4ef776a0">AssumeBuilderState</a>, <a href="#a336ed98852175e7e955e9217080bd596">isKnowledgeWorthPreserving</a> and <a href="#aba1e9ea5dd5dfc2b1559cb6cef8b4854">tryToPreserveWithoutAddingAssume</a>.</p>

</div>
</div>

### M {#aa0f5fabd5b5284966c165b333edc224b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a>.</p>


<p>Referenced by <a href="#a201cb1ede84e08442e7433b7b3eaed69">addKnowledge</a>, <a href="#aaeb042df2c65c8ffdbd2ad3f4ef776a0">AssumeBuilderState</a> and <a href="#aadca3692ce40afeb83b7765b2d7dfc9c">build</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/assumebundlebuilder-cpp">AssumeBundleBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
