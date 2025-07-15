---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loadandstorepromoter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoadAndStorePromoter` Class Reference

<p>Helper class for promoting a collection of loads and stores into SSA Form using the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoadAndStorePromoter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">llvm/Transforms/Utils/SSAUpdater.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/basicloadandstorepromoter">BasicLoadAndStorePromoter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A basic LoadAndStorePromoter that does not remove store nodes. <a href="/web-llvm/docs/api/classes/basicloadandstorepromoter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper">PGOCounterPromoterHelper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper class to promote one counter RMW operation in the loop into register update. <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/looppromoter">LoopPromoter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4040326a09f994f2b5481cf5c8da82">LoadAndStorePromoter</a> (ArrayRef&lt; const Instruction * &gt; Insts, SSAUpdater &amp;S, StringRef Name=StringRef())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2784430c58fb232b79f7d2db18beaf">~LoadAndStorePromoter</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1da68baf80229b2d8af34499eb1c73f">run</a> (const SmallVectorImpl&lt; Instruction * &gt; &amp;Insts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This does the promotion. <a href="#ac1da68baf80229b2d8af34499eb1c73f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0559a676152aa1421ed8ff6a4dfde66b">doExtraRewritesBeforeFinalDeletion</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook is invoked after all the stores are found and inserted as available values. <a href="#a0559a676152aa1421ed8ff6a4dfde66b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8323f250fbb2b45a78080ae308a15977">replaceLoadWithValue</a> (LoadInst *LI, Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clients can choose to implement this to get notified right before a load is RAUW'd another value. <a href="#a8323f250fbb2b45a78080ae308a15977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a012fcb5ec538c2210ad15e8afcf061ed">instructionDeleted</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called before each instruction is deleted. <a href="#a012fcb5ec538c2210ad15e8afcf061ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded1d51669c3499f8333ad933f68ec23">updateDebugInfo</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to update debug info associated with the instruction. <a href="#aded1d51669c3499f8333ad933f68ec23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1b74c8b9813e189733f6c5a63495e6">shouldDelete</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return false if a sub-class wants to keep one of the loads/stores after the SSA construction. <a href="#aee1b74c8b9813e189733f6c5a63495e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00281405f1913aecc88b8aee6b79205b">getValueToUseForAlloca</a> (Instruction *AI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value to use for the point in the code that the alloca is positioned. <a href="#a00281405f1913aecc88b8aee6b79205b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbfdd1721b153d96672de12d3ec06637">SSA</a></td>
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

<p>Helper class for promoting a collection of loads and stores into SSA Form using the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a>.</p>


<p>This handles complexities that <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> doesn't, such as multiple loads and stores in one block.</p>


<p>Clients of this class are expected to subclass this and implement the virtual methods.</p>


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoadAndStorePromoter() {#a5a4040326a09f994f2b5481cf5c8da82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadAndStorePromoter::LoadAndStorePromoter (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; Insts, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="#adbfdd1721b153d96672de12d3ec06637">SSA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/basicloadandstorepromoter/#a3ded06351ad4d9d097e68d88bb46ba30">BasicLoadAndStorePromoter::BasicLoadAndStorePromoter</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/looppromoter/#a87b154d8853b7d1fa59b6ecf9b007820">anonymous{LICM.cpp}::LoopPromoter::LoopPromoter</a> and <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper/#aa4eed4e5be9976241f4a6ed5e591da62">anonymous{InstrProfiling.cpp}::PGOCounterPromoterHelper::PGOCounterPromoterHelper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LoadAndStorePromoter() {#acd2784430c58fb232b79f7d2db18beaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::LoadAndStorePromoter::~LoadAndStorePromoter ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doExtraRewritesBeforeFinalDeletion() {#a0559a676152aa1421ed8ff6a4dfde66b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::LoadAndStorePromoter::doExtraRewritesBeforeFinalDeletion ()</td>
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

<p>This hook is invoked after all the stores are found and inserted as available values.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<p>Referenced by <a href="#ac1da68baf80229b2d8af34499eb1c73f">run</a>.</p>

</div>
</div>

### getValueToUseForAlloca() {#a00281405f1913aecc88b8aee6b79205b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Value * llvm::LoadAndStorePromoter::getValueToUseForAlloca (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * AI)</td>
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

<p>Return the value to use for the point in the code that the alloca is positioned.</p>


<p>This will only be used if an Alloca is included in Insts, otherwise the value of a uninitialized load will be assumed to be poison.</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<p>Referenced by <a href="#ac1da68baf80229b2d8af34499eb1c73f">run</a>.</p>

</div>
</div>

### instructionDeleted() {#a012fcb5ec538c2210ad15e8afcf061ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::LoadAndStorePromoter::instructionDeleted (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Called before each instruction is deleted.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ac1da68baf80229b2d8af34499eb1c73f">run</a>.</p>

</div>
</div>

### replaceLoadWithValue() {#a8323f250fbb2b45a78080ae308a15977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::LoadAndStorePromoter::replaceLoadWithValue (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Clients can choose to implement this to get notified right before a load is RAUW'd another value.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<p>Referenced by <a href="#ac1da68baf80229b2d8af34499eb1c73f">run</a>.</p>

</div>
</div>

### run() {#ac1da68baf80229b2d8af34499eb1c73f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoadAndStorePromoter::run (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Insts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This does the promotion.</p>


<p>Insts is a list of loads and stores to promote, and Name is the basename for the PHIs to insert. After this is complete, the loads and stores are removed from the code.</p>


<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#a0e09f111089ae4fffb14fa1b22816483">llvm::TinyPtrVector&lt; EltTy &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#ae26163705e85102ac61fc88f0392a217">llvm::TinyPtrVector&lt; EltTy &gt;::clear</a>, <a href="#a0559a676152aa1421ed8ff6a4dfde66b">doExtraRewritesBeforeFinalDeletion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#a9dc659b723e6725130ad354ed821d400">llvm::TinyPtrVector&lt; EltTy &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#aa8dc0937a5c524026865ef2a68d3c4f1">llvm::TinyPtrVector&lt; EltTy &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a00281405f1913aecc88b8aee6b79205b">getValueToUseForAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a012fcb5ec538c2210ad15e8afcf061ed">instructionDeleted</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="#a8323f250fbb2b45a78080ae308a15977">replaceLoadWithValue</a>, <a href="#aee1b74c8b9813e189733f6c5a63495e6">shouldDelete</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#aac784c7664f3f6b8076756c6fb0eed74">llvm::TinyPtrVector&lt; EltTy &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="#adbfdd1721b153d96672de12d3ec06637">SSA</a>, <a href="#aded1d51669c3499f8333ad933f68ec23">updateDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoter/#aba67c0c1aba6c8fcf674792830b73704">anonymous{InstrProfiling.cpp}::PGOCounterPromoter::run</a>.</p>

</div>
</div>

### shouldDelete() {#aee1b74c8b9813e189733f6c5a63495e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::LoadAndStorePromoter::shouldDelete (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Return false if a sub-class wants to keep one of the loads/stores after the SSA construction.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ac1da68baf80229b2d8af34499eb1c73f">run</a>.</p>

</div>
</div>

### updateDebugInfo() {#aded1d51669c3499f8333ad933f68ec23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::LoadAndStorePromoter::updateDebugInfo (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Called to update debug info associated with the instruction.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ac1da68baf80229b2d8af34499eb1c73f">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### SSA {#adbfdd1721b153d96672de12d3ec06637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SSAUpdater&amp; llvm::LoadAndStorePromoter::SSA</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper/#afb93c0389fa161c51b25541def502b89">anonymous{InstrProfiling.cpp}::PGOCounterPromoterHelper::doExtraRewritesBeforeFinalDeletion</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/looppromoter/#afdbe575a191d9f3b5b6cef8212745dc0">anonymous{LICM.cpp}::LoopPromoter::insertStoresInLoopExitBlocks</a>, <a href="#a5a4040326a09f994f2b5481cf5c8da82">LoadAndStorePromoter</a>, <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper/#aa4eed4e5be9976241f4a6ed5e591da62">anonymous{InstrProfiling.cpp}::PGOCounterPromoterHelper::PGOCounterPromoterHelper</a> and <a href="#ac1da68baf80229b2d8af34499eb1c73f">run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdater-h">SSAUpdater.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
