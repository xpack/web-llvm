---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/atomicexpandpass-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AtomicExpandPass.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlfunctionalextras-h">llvm/ADT/STLFunctionalExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instsimplifyfolder-h">llvm/Analysis/InstSimplifyFolder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/atomicexpand-h">llvm/CodeGen/AtomicExpand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/atomicexpandutils-h">llvm/CodeGen/AtomicExpandUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/memorymodelrelaxationannotations-h">llvm/IR/MemoryModelRelaxationAnnotations.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/atomicordering-h">llvm/Support/AtomicOrdering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/loweratomic-h">llvm/Transforms/Utils/LowerAtomic.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-atomicexpandpass-cpp-">anonymous{AtomicExpandPass.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-atomicexpandpass-cpp-/atomicexpandimpl">AtomicExpandImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-atomicexpandpass-cpp-/atomicexpandlegacy">AtomicExpandLegacy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-atomicexpandpass-cpp-/replacementirbuilder">ReplacementIRBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-atomicexpandpass-cpp-/partwordmaskvalues">PartwordMaskValues</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b5dd836d681863bc1cf1ab9fdcd3a90">INITIALIZE_PASS_BEGIN</a> (AtomicExpandLegacy, DEBUG_TYPE, "Expand Atomic instructions", false, false) INITIALIZE_PASS_END(AtomicExpandLegacy</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Expand Atomic static false unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa54574a2cf0b638d4fee2b8ed962058a">getAtomicOpSize</a> (LoadInst *LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc002905dbfe76b18e8ec1cea25cee6">getAtomicOpSize</a> (StoreInst *SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ac978d44f5d426d300a400142708b5">getAtomicOpSize</a> (AtomicRMWInst *RMWI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d6de2bddc669af3e9b358e46e38e9e">getAtomicOpSize</a> (AtomicCmpXchgInst *CASI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9315c94e4cd695aceef039966a2beba">copyMetadataForAtomic</a> (Instruction &amp;Dest, const Instruction &amp;Source)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy metadata that's safe to preserve when widening atomics. <a href="#ae9315c94e4cd695aceef039966a2beba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Inst&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#addb0d67f88876ee143acca486e03c53d">atomicSizeSupported</a> (const TargetLowering *TLI, Inst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b7c4ad8be280f28707e920e5f3a41e">createCmpXchgInstFun</a> (IRBuilderBase &amp;Builder, Value *Addr, Value *Loaded, Value *NewVal, Align AddrAlign, AtomicOrdering MemOpOrder, SyncScope::ID SSID, Value *&amp;Success, Value *&amp;NewLoaded, Instruction *MetadataSrc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static PartwordMaskValues</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f4e9b64d7a612f2b8236f0d147f591">createMaskInstrs</a> (IRBuilderBase &amp;Builder, Instruction *I, Type *ValueType, Value *Addr, Align AddrAlign, unsigned MinWordSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a helper function which builds instructions to provide values necessary for partword atomic operations. <a href="#a44f4e9b64d7a612f2b8236f0d147f591">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8078ce258348e8fd9d2e16bead13e770">extractMaskedValue</a> (IRBuilderBase &amp;Builder, Value *WideWord, const PartwordMaskValues &amp;PMV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae621284e39538e26bdef3fa0904db7fe">insertMaskedValue</a> (IRBuilderBase &amp;Builder, Value *WideWord, Value *Updated, const PartwordMaskValues &amp;PMV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f139ee1c3fc1e3029eaf08d4e67d9a9">performMaskedAtomicOp</a> (AtomicRMWInst::BinOp Op, IRBuilderBase &amp;Builder, Value *Loaded, Value *Shifted_Inc, Value *Inc, const PartwordMaskValues &amp;PMV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit IR to implement a masked version of a given atomicrmw operation. <a href="#a1f139ee1c3fc1e3029eaf08d4e67d9a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6312845f74f9bb3101268e4598ae05a5">canUseSizedAtomicCall</a> (unsigned Size, Align Alignment, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1937512c312e6e175b1367b551a4a3">GetRMWLibcall</a> (AtomicRMWInst::BinOp Op)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Expand Atomic</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Expand Atomic</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f675ccd5eaa6039694b250aa35ab57">false</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"atomic-expand"</td>
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

### atomicSizeSupported() {#addb0d67f88876ee143acca486e03c53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Inst&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool atomicSizeSupported (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TLI, Inst * I)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="#aa54574a2cf0b638d4fee2b8ed962058a">getAtomicOpSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab4f441f058eb21d972cd86d45089fc01">llvm::TargetLoweringBase::getMaxAtomicSizeInBitsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### canUseSizedAtomicCall() {#a6312845f74f9bb3101268e4598ae05a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canUseSizedAtomicCall (unsigned Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 1711 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### copyMetadataForAtomic() {#ae9315c94e4cd695aceef039966a2beba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void copyMetadataForAtomic (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Dest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Source)</td>
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

<p>Copy metadata that's safe to preserve when widening atomics.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a>.</p>


<p>Referenced by <a href="#a93b7c4ad8be280f28707e920e5f3a41e">createCmpXchgInstFun</a>.</p>

</div>
</div>

### createCmpXchgInstFun() {#a93b7c4ad8be280f28707e920e5f3a41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createCmpXchgInstFun (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Loaded, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewVal, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> AddrAlign, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> MemOpOrder, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; Success, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; NewLoaded, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MetadataSrc)</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae9315c94e4cd695aceef039966a2beba">copyMetadataForAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a199f6765de1f6b1a242aac556528f3b3">llvm::IRBuilderBase::CreateAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a7ce03ab5b2a6006ebcdfe804e4c8f1a1">llvm::AtomicCmpXchgInst::getStrongestFailureOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>.</p>

</div>
</div>

### createMaskInstrs() {#a44f4e9b64d7a612f2b8236f0d147f591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PartwordMaskValues createMaskInstrs (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValueType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> AddrAlign, unsigned MinWordSize)</td>
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

<p>This is a helper function which builds instructions to provide values necessary for partword atomic operations.</p>


<p>It takes an incoming address, Addr, and <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a>, and constructs the address, shift-amounts and masks needed to work with a larger value of size WordSize.</p>


<p>AlignedAddr: Addr rounded down to a multiple of WordSize</p>


<p>ShiftAmt: Number of bits to right-shift a WordSize value loaded from AlignAddr for it to have the same value as if <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> was loaded from Addr.</p>


<p>Mask: <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to mask with the value loaded from AlignAddr to include only the part that would've been loaded from Addr.</p>


<p>Inv_Mask: The inverse of Mask.</p>


<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### extractMaskedValue() {#a8078ce258348e8fd9d2e16bead13e770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * extractMaskedValue (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * WideWord, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PartwordMaskValues &amp; PMV)</td>
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



<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#a1f139ee1c3fc1e3029eaf08d4e67d9a9">performMaskedAtomicOp</a>.</p>

</div>
</div>

### getAtomicOpSize() {#aa54574a2cf0b638d4fee2b8ed962058a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expand Atomic static false unsigned getAtomicOpSize (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="#aa54574a2cf0b638d4fee2b8ed962058a">getAtomicOpSize</a>.</p>


<p>Referenced by <a href="#addb0d67f88876ee143acca486e03c53d">atomicSizeSupported</a> and <a href="#aa54574a2cf0b638d4fee2b8ed962058a">getAtomicOpSize</a>.</p>

</div>
</div>

### getAtomicOpSize() {#accc002905dbfe76b18e8ec1cea25cee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getAtomicOpSize (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

### getAtomicOpSize() {#a48ac978d44f5d426d300a400142708b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getAtomicOpSize (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> * RMWI)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#ae55438e0a802a1a20d6dcabf71b552ad">llvm::AtomicRMWInst::getValOperand</a>.</p>

</div>
</div>

### getAtomicOpSize() {#a11d6de2bddc669af3e9b358e46e38e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getAtomicOpSize (<a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> * CASI)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a39126826c171851bae4062b25b48e74e">llvm::AtomicCmpXchgInst::getCompareOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

### GetRMWLibcall() {#aff1937512c312e6e175b1367b551a4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; RTLIB::Libcall &gt; GetRMWLibcall (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> Op)</td>
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



<p>Definition at line 1767 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0794c42b44989f9d9f1454d79ca0dd88">llvm::AtomicRMWInst::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a497e8f347648b1b2823ee0338c95f65f">llvm::AtomicRMWInst::BAD_BINOP</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a08ef06068dcd583c2476568dda59b324">llvm::AtomicRMWInst::FAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd">llvm::AtomicRMWInst::FMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18">llvm::AtomicRMWInst::FMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a92f66d4bc04fc8514bee80509f3e78d4">llvm::AtomicRMWInst::FSub</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b">llvm::AtomicRMWInst::Nand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5db6ca0c3e18acd87290f22ccb2ce564">llvm::AtomicRMWInst::Sub</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615ad3ed1a8c334bc3a50d59aaa57ee9e9f3">llvm::AtomicRMWInst::UDecWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a9334c9815ddc2b25804c6c03b68cc39b">llvm::AtomicRMWInst::UIncWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0f94e2ef083268e45d22a220f92567a4">llvm::AtomicRMWInst::USubCond</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a7bf1abb23eccced685c706917aff605c">llvm::AtomicRMWInst::USubSat</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e">llvm::AtomicRMWInst::Xor</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a2b5dd836d681863bc1cf1ab9fdcd3a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (AtomicExpandLegacy, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Expand Atomic instructions", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### insertMaskedValue() {#ae621284e39538e26bdef3fa0904db7fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * insertMaskedValue (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * WideWord, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Updated, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PartwordMaskValues &amp; PMV)</td>
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



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>.</p>


<p>Referenced by <a href="#a1f139ee1c3fc1e3029eaf08d4e67d9a9">performMaskedAtomicOp</a>.</p>

</div>
</div>

### performMaskedAtomicOp() {#a1f139ee1c3fc1e3029eaf08d4e67d9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * performMaskedAtomicOp (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> Op, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Loaded, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shifted_Inc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Inc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PartwordMaskValues &amp; PMV)</td>
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

<p>Emit IR to implement a masked version of a given atomicrmw operation.</p>


<p>(That is, only the bits under the Mask should be affected by the operation)</p>


<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0794c42b44989f9d9f1454d79ca0dd88">llvm::AtomicRMWInst::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9af7e2dd206cc24d4690e1d2a996c43e">llvm::buildAtomicRMWValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="#a8078ce258348e8fd9d2e16bead13e770">extractMaskedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a08ef06068dcd583c2476568dda59b324">llvm::AtomicRMWInst::FAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd">llvm::AtomicRMWInst::FMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18">llvm::AtomicRMWInst::FMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a92f66d4bc04fc8514bee80509f3e78d4">llvm::AtomicRMWInst::FSub</a>, <a href="#ae621284e39538e26bdef3fa0904db7fe">insertMaskedValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b">llvm::AtomicRMWInst::Nand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5db6ca0c3e18acd87290f22ccb2ce564">llvm::AtomicRMWInst::Sub</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615ad3ed1a8c334bc3a50d59aaa57ee9e9f3">llvm::AtomicRMWInst::UDecWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a9334c9815ddc2b25804c6c03b68cc39b">llvm::AtomicRMWInst::UIncWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0f94e2ef083268e45d22a220f92567a4">llvm::AtomicRMWInst::USubCond</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a7bf1abb23eccced685c706917aff605c">llvm::AtomicRMWInst::USubSat</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e">llvm::AtomicRMWInst::Xor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>

</div>
</div>

### false {#a27f675ccd5eaa6039694b250aa35ab57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expand Atomic false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>

</div>
</div>

### instructions {#a1bcc06b1cb86bd0ea08f33323190bdaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expand Atomic instructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a6396da6d0b65cef8693b0aedd06f31e3">llvm::SystemZTTIImpl::adjustInliningThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#afe664f8e39ffc3ae37c49342e39d7423">llvm::coro::Shape::analyze</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ac66a7135ed298f43f06fedd02fd33f74">llvm::X86TTIImpl::areInlineCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#acc600a6141b4b54703a4ead9c72a3012">bitTrackingDCE</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a85511f1d0a02c18e6c6dd590344664a4">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::buildGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#a293951aa7455af46ccbbc68bdfbf7556">canTRE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#aa39f65efac3a51f3001285439ea997be">anonymous{Debugify.cpp}::checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a8b8a65f41fa956162c7877cb20bc53b9">checkFunctionMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a13dafea5ca0652a4011dd613a8f02494">collectDbgVariableIntrinsics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad9d4e85b3abfbf1a3dd8a7fd45057cce">llvm::CollectDebugInfoForCloning</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/typesanitizer-cpp/#a8fe9c2e5d8a275393677c1c46c5f0596">collectMemAccessInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#aa9145488452fa21d947ebb7f908f344b">collectPreserveStaticOffsetCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afee39cae7ff99ef86d9f4ed0ee4282f0">llvm::coro::collectSpillsAndAllocasFromInsts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/annotation2metadata-cpp/#ae04cce04aef5dad8bb4c7b8d0a07f145">convertAnnotation2Metadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#ae108e4dbbaf43d863f88674e0a37efcd">createSCCNodeSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad3bf571f4743d886275638484d6a3389">llvm::coro::doRematerializations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/dce-cpp/#a1f59e7fcf1a99e84e5f442a9deb1c887">eliminateDeadCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a01efda615d7f206d097e0280ab2fbaa7">eraseDebugIntrinsicsWithNonLocalRefs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandreductions-cpp-/#ae32d63d2aee7169e45cf696b040ccb66">anonymous{ExpandReductions.cpp}::expandReductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/makeguardsexplicit-cpp/#aeee7951092aa5ce8f95ecb2f03d42893">explicifyGuards</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#af03b866cfd7aa23da26179050622de5a">functionWillReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#ad7483d245bba8b6658b4dbd429f14313">getEdgeKind</a>, <a href="/web-llvm/docs/api/classes/llvm/genericuniformityanalysisimpl/#a54862d3efc343fea75e78d7a9908dfd9">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregularizer-cpp/#a70c9d5004bb64ce7c4ed2dab4acda63b">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#aa3f63c5f611bcbbc920d49245a3b76ac">insertCallAtAllFunctionExitPoints</a>, <a href="/web-llvm/docs/api/structs/anonymous-corocleanup-cpp-/lowerer/#ae8263688979f1e86bc684abf99f43d61">anonymous{CoroCleanup.cpp}::Lowerer::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroearly-cpp-/lowerer/#ad856ac9052abe36a0ca7e8909fd18f1b">anonymous{CoroEarly.cpp}::Lowerer::lowerEarlyIntrinsics</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-metarenamer-cpp-/#a064884ce5c1dfc88005ee86608f6630e">anonymous{MetaRenamer.cpp}::MetaRenameOnlyInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a721f6a9227830f0254a70a740f43f24f">llvm::MLInlineAdvisor::MLInlineAdvisor</a>, <a href="/web-llvm/docs/api/classes/anonymous-mustexecute-cpp-/mustexecuteannotatedwriter/#a5b34c31c5be4ebfbfd92dd26bfbfbcc8">anonymous{MustExecute.cpp}::MustExecuteAnnotatedWriter::MustExecuteAnnotatedWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-mustexecute-cpp-/mustexecuteannotatedwriter/#ae51e275dafe1a9e854c2cba79f8d6b15">anonymous{MustExecute.cpp}::MustExecuteAnnotatedWriter::MustExecuteAnnotatedWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a9b0882cc5c77313d5279c49c6e96eead">llvm::InstDeleterIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/structs/anonymous-stacksafetyanalysis-cpp-/functioninfo/#af9f11ba532b8f285d372eb15ec138632">anonymous{StackSafetyAnalysis.cpp}::FunctionInfo&lt; CalleeTy &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a77b275a78beac200ef1f703d2a5fbb7d">llvm::ScalarEvolution::print</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfo/#a138eb4d1f72b7808b5cfc34c64440007">llvm::StackSafetyGlobalInfo::print</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-delinearization-cpp-/#a5c53d773e653f349a53c8796896bfaed">anonymous{Delinearization.cpp}::printDelinearization</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a8a7021d757eccab56a01319353ebe04f">processDbgDeclares</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/legalizebuffercontenttypesvisitor/#a4f0d3bce52d233ad9bc73ee19c049119">anonymous{AMDGPULowerBufferFatPointers.cpp}::LegalizeBufferContentTypesVisitor::processFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a55cdba34485b0a468674e0df377c8677">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::processFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/storefatptrsasintsvisitor/#aa3fda38fb3f6f474b98450eec17d480d">anonymous{AMDGPULowerBufferFatPointers.cpp}::StoreFatPtrsAsIntsVisitor::processFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a370b5637d8494d95fb8867b813fa71d8">anonymous{OpenMPOpt.cpp}::OpenMPOpt::registerAAsForFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroelide-cpp/#a5d9225a91194b62b22073916440c9f23">removeTailCallAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39e8a80eb7f64212557e64bfafec9d57">llvm::replaceCreatedSSACopys</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a275ed8c2ebcd61ba635dbf7c119e7ed2">llvm::coro::BaseCloner::replaceEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#a10ae65e3c5a7ffa45ad8a1ba47c98b5a">rescheduleLexographically</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers/#a00d87849a4eb6524d910ab07f0fd968f">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-functionattrs-cpp-/attributeinferer/#a322a5409ce5be2c9d2045f16b8439048">anonymous{FunctionAttrs.cpp}::AttributeInferer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-stacksafetyanalysis-cpp-/stacksafetylocalanalysis/#aaed4fd903e016ae19555330092b0e3fc">anonymous{StackSafetyAnalysis.cpp}::StackSafetyLocalAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aliassetsprinterpass/#a3a8a27458f2832e65ace0c61bb035be7">llvm::AliasSetsPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpulowerkernelattributespass/#af67c40d9973225a0cdd48e2c13ffe9d2">llvm::AMDGPULowerKernelAttributesPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/assumebuilderpass/#aca0fa8f3093912d8045361e2f6b79cac">llvm::AssumeBuilderPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dsepass/#a29b9f8c28e2ba0531f66bd82e8c5a32e">llvm::DSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memderefprinterpass/#a9643b91d2f4e79487e5b260eb11fef74">llvm::MemDerefPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mustbeexecutedcontextprinterpass/#a1b1a19034ac7bbb0481e54e850fc431a">llvm::MustBeExecutedContextPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/paevalpass/#a7f0dda30879f62ea4eefdc53cfbb0e1d">llvm::PAEvalPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacklifetimeprinterpass/#a7d1ec1183162820291a3dcc9a0e81d45">llvm::StackLifetimePrinterPass::run</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuattributor-cpp-/#a54acd54cc3db43b11d42ebf210d08cf7">anonymous{AMDGPUAttributor.cpp}::runImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-objcarcexpand-cpp-/#a709dbe85480f7e0e85807121725c1485">anonymous{ObjCARCExpand.cpp}::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#aca9bbb9fc2968bbb644730c5c2567409">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aca9bbb9fc2968bbb644730c5c2567409">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/annotationremarks-cpp/#ae33ca40f926442c4264c507f4d32c85e">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a9b4d59167080364585ba7ca223922adb">runNVVMIntrRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrshiftexpand-cpp-/avrshiftexpand/#a25192a5e79d3f5ef39a4b3d4a7da9fd9">anonymous{AVRShiftExpand.cpp}::AVRShiftExpand::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-interleavedaccesspass-cpp-/interleavedaccessimpl/#a57458b96a1b67f927f7a6e552338a81e">anonymous{InterleavedAccessPass.cpp}::InterleavedAccessImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-irnormalizer-cpp-/irnormalizer/#a6ff04883b7477c97a6150fb1528c5f2d">anonymous{IRNormalizer.cpp}::IRNormalizer::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvelaneinterleavingpass-cpp-/mvelaneinterleaving/#a6d679dfc2baa424f4dfe87212d2c8ca9">anonymous{MVELaneInterleavingPass.cpp}::MVELaneInterleaving::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxatomiclower-cpp-/nvptxatomiclower/#a707795edc1a2d6427fa4ba627e4b3d7a">anonymous{NVPTXAtomicLower.cpp}::NVPTXAtomicLower::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemztdc-cpp-/systemztdcpass/#a297c01ed88bcbeaac178adb0ff9e497f">anonymous{SystemZTDC.cpp}::SystemZTDCPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#ad69716246dabb743839cafceb902ef46">llvm::RewriteStatepointsForGC::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a984df453a762468ca683f6e83cf50e17">runPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-hwaddresssanitizer-cpp-/hwaddresssanitizer/#abe3ea5f5ad2a17b7552318e8ffb3b0bb">anonymous{HWAddressSanitizer.cpp}::HWAddressSanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a09a156bd41fe293ee8743b4beca76960">stripDeadDebugInfoImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/stripgcrelocates-cpp/#a5d9143fec81c7c1bea9330ccc664f45c">stripGCRelocates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a2bf12026ed9de594d2117077b422c24d">stripNonValidDataFromBody</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a32c765cabc6bab63ba8691a789db738b">stripTBAA</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a4e3cc8f7cd934d5e7dee1cc7e3c1392e">usesMSVCFloatingPoint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"atomic-expand"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp">AtomicExpandPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
