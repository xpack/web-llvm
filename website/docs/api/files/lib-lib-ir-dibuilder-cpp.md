---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/dibuilder-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DIBuilder.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">llvm/IR/DIBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">llvm/ADT/APSInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a> (DIScope *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If N is compile unit return NULL otherwise return N. <a href="#a5db83448daa843198df6b3ee1cea066c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af012955ffa86a4774541d3e9acd23d12">createImportedModule</a> (LLVMContext &amp;C, dwarf::Tag Tag, DIScope *Context, Metadata *NS, DIFile *File, unsigned Line, StringRef Name, DINodeArray Elements, SmallVectorImpl&lt; TrackingMDNodeRef &gt; &amp;ImportedModules)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata">ConstantAsMetadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91844752a109d8486027ab038e8f1d36">getConstantOrNull</a> (Constant *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ditemplatevalueparameter">DITemplateValueParameter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac565d17a6ef8e7639ce88d6be474d08b">createTemplateValueParameterHelper</a> (LLVMContext &amp;VMContext, unsigned Tag, DIScope *Context, StringRef Name, DIType *Ty, bool IsDefault, Metadata *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3acad1d2d3a16b66adc99bc4cfdd9efe">createTypeWithFlags</a> (const DIType *Ty, DINode::DIFlags FlagsToSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed9b2e89b42ead2f8dbda271333152c">checkGlobalVariableScope</a> (DIScope *Context)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ad252830f022d82e560f5447107d07">createLocalVariable</a> (LLVMContext &amp;VMContext, SmallVectorImpl&lt; TrackingMDNodeRef &gt; &amp;PreservedNodes, DIScope *Context, StringRef Name, unsigned ArgNo, DIFile *File, unsigned LineNo, DIType *Ty, bool AlwaysPreserve, DINode::DIFlags Flags, uint32_t AlignInBits, DINodeArray Annotations=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a859931f9f18bb9556861a9568be49d1e">getSubprogram</a> (bool IsDistinct, Ts &amp;&amp;...Args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad269a2105e7a19e6a7eac9d3399d7917">initIRBuilder</a> (IRBuilder&lt;&gt; &amp;Builder, const DILocation *DL, InsertPosition InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> for inserting dbg.declare and dbg.value intrinsics. <a href="#ad269a2105e7a19e6a7eac9d3399d7917">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ee8b40336e0c147c85f2520ada223c">getDbgIntrinsicValueImpl</a> (LLVMContext &amp;VMContext, Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2607e2337fc3a69c867344fc4e3d209b">getDeclareIntrin</a> (Module &amp;M)</td>
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

### checkGlobalVariableScope() {#a7ed9b2e89b42ead2f8dbda271333152c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkGlobalVariableScope (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context)</td>
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



<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a9cb4bcf5ce38d7b765c6f915f66f4bcf">llvm::DIBuilder::createGlobalVariableExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a0836d7f22fd1d8bd8d2fd97da17bc9ba">llvm::DIBuilder::createTempGlobalVariableFwdDecl</a>.</p>

</div>
</div>

### createImportedModule() {#af012955ffa86a4774541d3e9acd23d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIImportedEntity * createImportedModule (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * NS, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, DINodeArray Elements, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a> &gt; &amp; ImportedModules)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga79b2014998173c73f1643a12d125f57d">LLVMDIBuilderCreateImportedModuleFromAlias</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0fb25118742415266bc77ba402c0be3e">LLVMDIBuilderCreateImportedModuleFromModule</a> and <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4bd7b93a5adab9a1c2e0115d6fd27aaa">LLVMDIBuilderCreateImportedModuleFromNamespace</a>.</p>

</div>
</div>

### createLocalVariable() {#a08ad252830f022d82e560f5447107d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalVariable * createLocalVariable (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; VMContext, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0b32d680d9bfed0636f7297d89583e27">TrackingMDNodeRef</a> &gt; &amp; PreservedNodes, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned LineNo, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, bool AlwaysPreserve, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> Flags, uint32_t AlignInBits, DINodeArray Annotations=nullptr)</td>
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



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ae6081972b0560d0f16bd503654924b1b">llvm::DIBuilder::createAutoVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#afa7c4efcb5c40c8527c13759f10ef5ed">llvm::DIBuilder::createParameterVariable</a>.</p>

</div>
</div>

### createTemplateValueParameterHelper() {#ac565d17a6ef8e7639ce88d6be474d08b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DITemplateValueParameter * createTemplateValueParameterHelper (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; VMContext, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, bool IsDefault, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a9282142c56014690597e4209fa3c4725">llvm::DIBuilder::createTemplateParameterPack</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a093b77c3612cbef1a9b29e680006f982">llvm::DIBuilder::createTemplateTemplateParameter</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#af7403e1a803ce258b0087e5faef340d7">llvm::DIBuilder::createTemplateValueParameter</a>.</p>

</div>
</div>

### createTypeWithFlags() {#a3acad1d2d3a16b66adc99bc4cfdd9efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIType * createTypeWithFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DINode::DIFlags</a> FlagsToSet)</td>
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



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#af8e7c85da0c37b1a8a5099d7a01f03a8">llvm::MDNode::replaceWithUniqued</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a3bc8816adbffd7e286400bb7367058d6">llvm::DIBuilder::createArtificialType</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a0061aafefff3c780f2b55c3772d94c3c">llvm::DIBuilder::createObjectPointerType</a>.</p>

</div>
</div>

### getConstantOrNull() {#a91844752a109d8486027ab038e8f1d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantAsMetadata * getConstantOrNull (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a23995c2ddd74a9abcc31d939e0643779">llvm::DIBuilder::createStaticMemberType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#af7403e1a803ce258b0087e5faef340d7">llvm::DIBuilder::createTemplateValueParameter</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a24655d8cf9e92a91d8b51101f64553c5">llvm::DIBuilder::createVariantMemberType</a>.</p>

</div>
</div>

### getDbgIntrinsicValueImpl() {#ad5ee8b40336e0c147c85f2520ada223c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getDbgIntrinsicValueImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; VMContext, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a> and <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a214637beca449d58d4313a69a9ba32af">llvm::DIBuilder::insertDeclare</a>.</p>

</div>
</div>

### getDeclareIntrin() {#a2607e2337fc3a69c867344fc4e3d209b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * getDeclareIntrin (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a214637beca449d58d4313a69a9ba32af">llvm::DIBuilder::insertDeclare</a>.</p>

</div>
</div>

### getNonCompileUnitScope() {#a5db83448daa843198df6b3ee1cea066c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIScope * getNonCompileUnitScope (<a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * N)</td>
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

<p>If N is compile unit return NULL otherwise return N.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a7ed9b2e89b42ead2f8dbda271333152c">checkGlobalVariableScope</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a0b8b82d8ef44a362f7be889d56121944">llvm::DIBuilder::createBitFieldMemberType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a280c57f61faff3e28571c62b3e4558e2">llvm::DIBuilder::createClassType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a28497d68ae2a721d43823c87919cfac5">llvm::DIBuilder::createEnumerationType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#af5b51afb7d6bdbb81b30eb5e121c1efb">llvm::DIBuilder::createForwardDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a57d91109bab556ea565fe8dd35f1d30c">llvm::DIBuilder::createFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5b9cc4f1d1803b0b793267544900a44f">llvm::DIBuilder::createLexicalBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adbf77460ca5103d4d0b2708b013a1b88">llvm::DIBuilder::createMemberType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ab37a47c83ecb05b68a904e49a7f69f68">llvm::DIBuilder::createMethod</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#affeea0b69c510392c5015ea861393738">llvm::DIBuilder::createModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a4fec0fd637f104b5c3cab3ffdbe3b3aa">llvm::DIBuilder::createNameSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a3b7af05053d96eafcdd3e06b41ba6749">llvm::DIBuilder::createObjCIVar</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ad47dddfcbfe0d635de4712fad2e7f900">llvm::DIBuilder::createReplaceableCompositeType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a7327bb62e5803d0eb1f8239d4d4509a9">llvm::DIBuilder::createSetType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a23995c2ddd74a9abcc31d939e0643779">llvm::DIBuilder::createStaticMemberType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#afe762b489a1c62e1d3baf58b330e6652">llvm::DIBuilder::createStructType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a3ae4713be3cb6c59e31f8e83d02ee7e3">llvm::DIBuilder::createTempFunctionFwdDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a88e594333479ba5f47d695a163a72846">llvm::DIBuilder::createTemplateAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a0d9a1f42764491af27b361ae59c694b1">llvm::DIBuilder::createTypedef</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5d7a72e4269b08b6a786c6950c014bc4">llvm::DIBuilder::createUnionType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a24655d8cf9e92a91d8b51101f64553c5">llvm::DIBuilder::createVariantMemberType</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ad99e6c0300816ba0fd1ebbc4a8cbd3da">llvm::DIBuilder::createVariantPart</a>.</p>

</div>
</div>

### getSubprogram() {#a859931f9f18bb9556861a9568be49d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * getSubprogram (bool IsDistinct, Ts &amp;&amp;... Args)</td>
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



<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a57d91109bab556ea565fe8dd35f1d30c">llvm::DIBuilder::createFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ab37a47c83ecb05b68a904e49a7f69f68">llvm::DIBuilder::createMethod</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforegallocfailure/#a65894464e2ca592db70001e29ac4f1b0">llvm::DiagnosticInfoRegAllocFailure::DiagnosticInfoRegAllocFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforegallocfailure/#afcf067b152ba85f0862dd7473495d4d1">llvm::DiagnosticInfoRegAllocFailure::DiagnosticInfoRegAllocFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinforesourcelimit/#af3dd4de995a10037f970994df29a3b76">llvm::DiagnosticInfoResourceLimit::DiagnosticInfoResourceLimit</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/remarkgenerator/#afa50ad465c63aba4cc83c1e37248a860">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::emitRemarks</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafddfbdaa9a85beba597ca456f2085251">LLVMGetSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremark/#a3891f0f63dbc838b810554621a2b621d">llvm::OptimizationRemark::OptimizationRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkanalysis/#a1a799ad8c42497bd62234ffd72ca97f3">llvm::OptimizationRemarkAnalysis::OptimizationRemarkAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkmissed/#a06e5af98c78a206608155e558697d011">llvm::OptimizationRemarkMissed::OptimizationRemarkMissed</a>.</p>

</div>
</div>

### initIRBuilder() {#ad269a2105e7a19e6a7eac9d3399d7917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt)</td>
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

<p>Initialize <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> for inserting dbg.declare and dbg.value intrinsics.</p>


<p>This abstracts over the various ways to specify an insert position.</p>


<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp">DIBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/insertposition/#a85d3be01e87a0909859f543e00c5929a">llvm::InsertPosition::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a214637beca449d58d4313a69a9ba32af">llvm::DIBuilder::insertDeclare</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adb6aff41bfe64d206d563112993cfb01">llvm::DIBuilder::insertLabel</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
