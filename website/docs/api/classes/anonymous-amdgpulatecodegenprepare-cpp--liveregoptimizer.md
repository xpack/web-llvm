---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LiveRegOptimizer` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9653facb49118990716581dab9178113">LiveRegOptimizer</a> (Module &amp;Mod, const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379666f1f08149bf9e4dabcb430aee93">calculateConvertType</a> (Type *OriginalType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the and <span class="doxyComputerOutput">return</span> the type to convert to given a problematic <span class="doxyComputerOutput">OriginalType</span>. <a href="#a379666f1f08149bf9e4dabcb430aee93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f832cfa0e0121c6fd066c0f3b25f5f">convertToOptType</a> (Instruction *V, BasicBlock::iterator &amp;InstPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the virtual register defined by <span class="doxyComputerOutput">V</span> to the compatible vector of legal type. <a href="#ac8f832cfa0e0121c6fd066c0f3b25f5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7587e2867090ef850ef2bda4ac192e48">convertFromOptType</a> (Type *ConvertType, Instruction *V, BasicBlock::iterator &amp;InstPt, BasicBlock *InsertBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert the virtual register defined by <span class="doxyComputerOutput">V</span> back to the original type <span class="doxyComputerOutput">ConvertType</span>, stripping away the MSBs in cases where there was an imperfect fit (e.g. <a href="#a7587e2867090ef850ef2bda4ac192e48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa50432deded202fb241ca2c204e8137a">optimizeLiveType</a> (Instruction *I, SmallVectorImpl&lt; WeakTrackingVH &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check for problematic PHI nodes or cross-bb values based on the value defined by <span class="doxyComputerOutput">I</span>, and coerce to legal types if necessary. <a href="#aa50432deded202fb241ca2c204e8137a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ef0473fe81ed643d4fe2e64c6a5b3e">shouldReplace</a> (Type *ITy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c1eaa09f1b68c1bb7f7500cc22dd8c">Mod</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6308533b4bba2194380969804801879c">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd4e792da2ca6ca7932c09073ccb431">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f2a6ddc93879cb7197f2de2825adb0a">ConvertToScalar</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The scalar type to convert to. <a href="#a2f2a6ddc93879cb7197f2de2825adb0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a104691e82727fe41466046f99f52ed5d">Visited</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of visited Instructions. <a href="#a104691e82727fe41466046f99f52ed5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulatecodegenprepare-cpp-/#ac1fa0ca4e558fee27e6605bc3d0cf1e5">ValueToValueMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5627dd13dbb9a34b9c1628792114a764">ValMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> -&gt; Converted <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a5627dd13dbb9a34b9c1628792114a764">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulatecodegenprepare-cpp-/#ac1fa0ca4e558fee27e6605bc3d0cf1e5">ValueToValueMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40f811fdcbfc69946bc40aa772313d5">BBUseValMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of containing conversions from Optimal <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> -&gt; Original <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> per BB. <a href="#ae40f811fdcbfc69946bc40aa772313d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LiveRegOptimizer() {#a9653facb49118990716581dab9178113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::LiveRegOptimizer (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### calculateConvertType() {#a379666f1f08149bf9e4dabcb430aee93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * LiveRegOptimizer::calculateConvertType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OriginalType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the and <span class="doxyComputerOutput">return</span> the type to convert to given a problematic <span class="doxyComputerOutput">OriginalType</span>.</p>


<p>In some instances, we may widen the type (e.g. v2i8 -&gt; i32).</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>.</p>


<p>Referenced by <a href="#ac8f832cfa0e0121c6fd066c0f3b25f5f">convertToOptType</a> and <a href="#aa50432deded202fb241ca2c204e8137a">optimizeLiveType</a>.</p>

</div>
</div>

### convertFromOptType() {#a7587e2867090ef850ef2bda4ac192e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LiveRegOptimizer::convertFromOptType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ConvertType, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &amp; InstPt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the virtual register defined by <span class="doxyComputerOutput">V</span> back to the original type <span class="doxyComputerOutput">ConvertType</span>, stripping away the MSBs in cases where there was an imperfect fit (e.g.</p>


<p>v2i32 -&gt; v7i8)</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>.</p>


<p>Referenced by <a href="#aa50432deded202fb241ca2c204e8137a">optimizeLiveType</a>.</p>

</div>
</div>

### convertToOptType() {#ac8f832cfa0e0121c6fd066c0f3b25f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * LiveRegOptimizer::convertToOptType (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &amp; InstPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert the virtual register defined by <span class="doxyComputerOutput">V</span> to the compatible vector of legal type.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a379666f1f08149bf9e4dabcb430aee93">calculateConvertType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aa50432deded202fb241ca2c204e8137a">optimizeLiveType</a>.</p>

</div>
</div>

### optimizeLiveType() {#aa50432deded202fb241ca2c204e8137a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRegOptimizer::optimizeLiveType (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check for problematic PHI nodes or cross-bb values based on the value defined by <span class="doxyComputerOutput">I</span>, and coerce to legal types if necessary.</p>


<p>For problematic PHI node, we coerce all incoming values in a single invocation.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="#a379666f1f08149bf9e4dabcb430aee93">calculateConvertType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="#a7587e2867090ef850ef2bda4ac192e48">convertFromOptType</a>, <a href="#ac8f832cfa0e0121c6fd066c0f3b25f5f">convertToOptType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a7004354fbee1c8cd74ed9001915e1db5">llvm::SmallPtrSetImpl&lt; PtrType &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ac8ef0473fe81ed643d4fe2e64c6a5b3e">shouldReplace</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#a557548c855dbdd51ce1657f5d5cdf995">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::run</a>.</p>

</div>
</div>

### shouldReplace() {#ac8ef0473fe81ed643d4fe2e64c6a5b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::shouldReplace (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ITy)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681af54ec6880362512f9fec982cd4ce39fb">llvm::TargetLoweringBase::TypeLegal</a>.</p>


<p>Referenced by <a href="#aa50432deded202fb241ca2c204e8137a">optimizeLiveType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BBUseValMap {#ae40f811fdcbfc69946bc40aa772313d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BasicBlock *, ValueToValueMap&gt; anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::BBUseValMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of containing conversions from Optimal <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> -&gt; Original <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> per BB.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>

</div>
</div>

### ConvertToScalar {#a2f2a6ddc93879cb7197f2de2825adb0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* const anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::ConvertToScalar</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The scalar type to convert to.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DL {#a6308533b4bba2194380969804801879c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>

</div>
</div>

### Mod {#a48c1eaa09f1b68c1bb7f7500cc22dd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::Mod</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>

</div>
</div>

### ST {#afbd4e792da2ca6ca7932c09073ccb431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>

</div>
</div>

### ValMap {#a5627dd13dbb9a34b9c1628792114a764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueToValueMap anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::ValMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> -&gt; Converted <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>

</div>
</div>

### Visited {#a104691e82727fe41466046f99f52ed5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 4&gt; anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of visited Instructions.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulatecodegenprepare-cpp">AMDGPULateCodeGenPrepare.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
