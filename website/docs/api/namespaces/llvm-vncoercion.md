---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/vncoercion
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `VNCoercion` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::VNCoercion { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10eb6aece68a8127f273e6a2dc0fc79">canCoerceMustAliasedValueToLoad</a> (Value *StoredVal, Type *LoadTy, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if CoerceAvailableValueToLoadType would succeed if it was called. <a href="#af10eb6aece68a8127f273e6a2dc0fc79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a351251756a2dcf559089f626d9241131">coerceAvailableValueToLoadType</a> (Value *StoredVal, Type *LoadedTy, IRBuilderBase &amp;IRB, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we saw a store of a value to memory, and then a load from a must-aliased pointer of a different type, try to coerce the stored value to the loaded type. <a href="#a351251756a2dcf559089f626d9241131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e6f143ee9c14b9498e4f43b97c2525">analyzeLoadFromClobberingStore</a> (Type *LoadTy, Value *LoadPtr, StoreInst *DepSI, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines whether a value for the pointer LoadPtr can be extracted from the store at DepSI. <a href="#a54e6f143ee9c14b9498e4f43b97c2525">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9534d3bff0727cc904e6bbc1064d2e2f">analyzeLoadFromClobberingLoad</a> (Type *LoadTy, Value *LoadPtr, LoadInst *DepLI, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines whether a value for the pointer LoadPtr can be extracted from the load at DepLI. <a href="#a9534d3bff0727cc904e6bbc1064d2e2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c3af18d8706c2d91fd7e2f88424336">analyzeLoadFromClobberingMemInst</a> (Type *LoadTy, Value *LoadPtr, MemIntrinsic *DepMI, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines whether a value for the pointer LoadPtr can be extracted from the memory intrinsic at DepMI. <a href="#ab7c3af18d8706c2d91fd7e2f88424336">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0786ad18996fdeb6bb0e33c3bfa4ce82">getValueForLoad</a> (Value *SrcVal, unsigned Offset, Type *LoadTy, Instruction *InsertPt, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If analyzeLoadFromClobberingStore/Load returned an offset, this function can be used to actually perform the extraction of the bits from the store. <a href="#a0786ad18996fdeb6bb0e33c3bfa4ce82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79e8ff1687364a4f9ac11f6dc1c4ce2d">getConstantValueForLoad</a> (Constant *SrcVal, unsigned Offset, Type *LoadTy, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b72d403292d9dddd1ef1ce3e8bc394c">getMemInstValueForLoad</a> (MemIntrinsic *SrcInst, unsigned Offset, Type *LoadTy, Instruction *InsertPt, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If analyzeLoadFromClobberingMemInst returned an offset, this function can be used to actually perform the extraction of the bits from the memory intrinsic. <a href="#a6b72d403292d9dddd1ef1ce3e8bc394c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b66161f15587adee19725b89fec713">getConstantMemInstValueForLoad</a> (MemIntrinsic *SrcInst, unsigned Offset, Type *LoadTy, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba537117d2f8896a17f972d29824ee13">isFirstClassAggregateOrScalableType</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cdc82521ee78a15e2ca179d740a5049">analyzeLoadFromClobberingWrite</a> (Type *LoadTy, Value *LoadPtr, Value *WritePtr, uint64_t WriteSizeInBits, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is called when we have a memdep query of a load that ends up being a clobbering memory write (store, memset, memcpy, memmove). <a href="#a1cdc82521ee78a15e2ca179d740a5049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ab95f8d1cfe32b5c75a4d4d666d89c">getStoreValueForLoadHelper</a> (Value *SrcVal, unsigned Offset, Type *LoadTy, IRBuilderBase &amp;Builder, const DataLayout &amp;DL)</td>
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

### analyzeLoadFromClobberingLoad() {#a9534d3bff0727cc904e6bbc1064d2e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::VNCoercion::analyzeLoadFromClobberingLoad (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LoadPtr, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * DepLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function determines whether a value for the pointer LoadPtr can be extracted from the load at DepLI.</p>


<p>This function is called when we have a memdep query of a load that ends up being clobbered by another load.</p>


<p>On success, it returns the offset into DepLI that extraction would start. On failure, it returns -1.</p>


<p>See if the other load can feed into the second load.</p>


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="#a1cdc82521ee78a15e2ca179d740a5049">analyzeLoadFromClobberingWrite</a>, <a href="#af10eb6aece68a8127f273e6a2dc0fc79">canCoerceMustAliasedValueToLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2a394517076e7dd2bdcd7dde33dfcb7d">llvm::Type::isArrayTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a81eef9d7336f7ee43be79630d8e8ec86">llvm::Type::isStructTy</a>.</p>

</div>
</div>

### analyzeLoadFromClobberingMemInst() {#ab7c3af18d8706c2d91fd7e2f88424336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::VNCoercion::analyzeLoadFromClobberingMemInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LoadPtr, <a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> * DepMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function determines whether a value for the pointer LoadPtr can be extracted from the memory intrinsic at DepMI.</p>


<p>On success, it returns the offset into DepMI that extraction would start. On failure, it returns -1.</p>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="#a1cdc82521ee78a15e2ca179d740a5049">analyzeLoadFromClobberingWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad95650d790f6f9d252cf0cd0e0094368">llvm::ConstantFoldLoadFromConstPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#aaebde92913b64b73fa77dd6e8767d9d9">llvm::MemTransferBase&lt; BaseCL &gt;::getSource</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#aec2d700d8b1e57f830a673c39a1f30dc">llvm::GlobalVariable::hasDefinitiveInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#aa859e108741fa64681b63f0c0c672512">llvm::GlobalVariable::isConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### analyzeLoadFromClobberingStore() {#a54e6f143ee9c14b9498e4f43b97c2525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::VNCoercion::analyzeLoadFromClobberingStore (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LoadPtr, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * DepSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function determines whether a value for the pointer LoadPtr can be extracted from the store at DepSI.</p>


<p>This function is called when we have a memdep query of a load that ends up being a clobbering store.</p>


<p>On success, it returns the offset into DepSI that extraction would start. On failure, it returns -1.</p>


<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="#a1cdc82521ee78a15e2ca179d740a5049">analyzeLoadFromClobberingWrite</a>, <a href="#af10eb6aece68a8127f273e6a2dc0fc79">canCoerceMustAliasedValueToLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#aefb15964facf7f35f22a6e8a7fb67285">llvm::StoreInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a89caf38fb409b0217360689351f3b457">llvm::StoreInst::getValueOperand</a> and <a href="#aba537117d2f8896a17f972d29824ee13">isFirstClassAggregateOrScalableType</a>.</p>

</div>
</div>

### analyzeLoadFromClobberingWrite() {#a1cdc82521ee78a15e2ca179d740a5049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::VNCoercion::analyzeLoadFromClobberingWrite (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LoadPtr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * WritePtr, uint64_t WriteSizeInBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>This function is called when we have a memdep query of a load that ends up being a clobbering memory write (store, memset, memcpy, memmove).</p>


<p>This means that the write <em>may</em> provide bits used by the load but we can't be sure because the pointers don't must-alias.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> this case to see if there is anything more we can do before we give up. This returns -1 if we have to give up, or a byte number in the stored value of the piece that feeds the load.</p>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ac5d9eb48038aa973017317279eadf5">llvm::GetPointerBaseWithConstantOffset</a> and <a href="#aba537117d2f8896a17f972d29824ee13">isFirstClassAggregateOrScalableType</a>.</p>


<p>Referenced by <a href="#a9534d3bff0727cc904e6bbc1064d2e2f">analyzeLoadFromClobberingLoad</a>, <a href="#ab7c3af18d8706c2d91fd7e2f88424336">analyzeLoadFromClobberingMemInst</a> and <a href="#a54e6f143ee9c14b9498e4f43b97c2525">analyzeLoadFromClobberingStore</a>.</p>

</div>
</div>

### canCoerceMustAliasedValueToLoad() {#af10eb6aece68a8127f273e6a2dc0fc79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VNCoercion::canCoerceMustAliasedValueToLoad (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StoredVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if CoerceAvailableValueToLoadType would succeed if it was called.</p>


<p>Return true if coerceAvailableValueToLoadType will succeed.</p>


<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aba537117d2f8896a17f972d29824ee13">isFirstClassAggregateOrScalableType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a8536986ed6c44fce15dba30748428d2c">llvm::Type::isTargetExtTy</a>.</p>


<p>Referenced by <a href="#a9534d3bff0727cc904e6bbc1064d2e2f">analyzeLoadFromClobberingLoad</a>, <a href="#a54e6f143ee9c14b9498e4f43b97c2525">analyzeLoadFromClobberingStore</a> and <a href="#a351251756a2dcf559089f626d9241131">coerceAvailableValueToLoadType</a>.</p>

</div>
</div>

### coerceAvailableValueToLoadType() {#a351251756a2dcf559089f626d9241131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::VNCoercion::coerceAvailableValueToLoadType (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StoredVal, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadedTy, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Helper, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we saw a store of a value to memory, and then a load from a must-aliased pointer of a different type, try to coerce the stored value to the loaded type.</p>


<p>If we saw a store of a value to memory, and then a load from a must-aliased pointer of a different type, try to coerce the stored value.</p>


<p>LoadedTy is the type of the load we want to replace. IRB is <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> used to insert new instructions.</p>


<p>If we can't do it, return null.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af10eb6aece68a8127f273e6a2dc0fc79">canCoerceMustAliasedValueToLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e655fd99a56d50b071fc26d8db5fd5b">llvm::ConstantFoldConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ade4ee38419ac3921c718b634571033e4">llvm::IRBuilderBase::CreateTruncOrBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#afb486f9022a26e1cc53ff189710dbde5">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGE</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="#a6b72d403292d9dddd1ef1ce3e8bc394c">getMemInstValueForLoad</a> and <a href="#a0786ad18996fdeb6bb0e33c3bfa4ce82">getValueForLoad</a>.</p>

</div>
</div>

### getConstantMemInstValueForLoad() {#aa4b66161f15587adee19725b89fec713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::VNCoercion::getConstantMemInstValueForLoad (<a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> * SrcInst, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f2a6934eba2671f2fe2a121f2e9e4e9">llvm::ConstantFoldLoadFromConst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad95650d790f6f9d252cf0cd0e0094368">llvm::ConstantFoldLoadFromConstPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#aaebde92913b64b73fa77dd6e8767d9d9">llvm::MemTransferBase&lt; BaseCL &gt;::getSource</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8c55d8510ad4b7cb957d8f5a7cd6944e">llvm::APInt::getSplat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getConstantValueForLoad() {#a79e8ff1687364a4f9ac11f6dc1c4ce2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::VNCoercion::getConstantValueForLoad (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * SrcVal, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f2a6934eba2671f2fe2a121f2e9e4e9">llvm::ConstantFoldLoadFromConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getMemInstValueForLoad() {#a6b72d403292d9dddd1ef1ce3e8bc394c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::VNCoercion::getMemInstValueForLoad (<a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> * SrcInst, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If analyzeLoadFromClobberingMemInst returned an offset, this function can be used to actually perform the extraction of the bits from the memory intrinsic.</p>


<p>This function is called when we have a memdep query of a load that ends up being a clobbering mem intrinsic.</p>


<p>It inserts instructions to do so at InsertPt, and returns the extracted value.</p>


<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a351251756a2dcf559089f626d9241131">coerceAvailableValueToLoadType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad95650d790f6f9d252cf0cd0e0094368">llvm::ConstantFoldLoadFromConstPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0032ae544ae429aaf1053767da90426d">llvm::IRBuilderBase::CreateZExtOrBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#aaebde92913b64b73fa77dd6e8767d9d9">llvm::MemTransferBase&lt; BaseCL &gt;::getSource</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue/#ac96558c87ecbcc96f020a0efcaade750">llvm::gvn::AvailableValue::MaterializeAdjustedValue</a>.</p>

</div>
</div>

### getStoreValueForLoadHelper() {#a43ab95f8d1cfe32b5c75a4d4d666d89c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::VNCoercion::getStoreValueForLoadHelper (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ade4ee38419ac3921c718b634571033e4">llvm::IRBuilderBase::CreateTruncOrBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a0786ad18996fdeb6bb0e33c3bfa4ce82">getValueForLoad</a>.</p>

</div>
</div>

### getValueForLoad() {#a0786ad18996fdeb6bb0e33c3bfa4ce82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::VNCoercion::getValueForLoad (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SrcVal, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LoadTy, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If analyzeLoadFromClobberingStore/Load returned an offset, this function can be used to actually perform the extraction of the bits from the store.</p>


<p>It inserts instructions to do so at InsertPt, and returns the extracted value.</p>


<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a351251756a2dcf559089f626d9241131">coerceAvailableValueToLoadType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a43ab95f8d1cfe32b5c75a4d4d666d89c">getStoreValueForLoadHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue/#ac96558c87ecbcc96f020a0efcaade750">llvm::gvn::AvailableValue::MaterializeAdjustedValue</a>.</p>

</div>
</div>

### isFirstClassAggregateOrScalableType() {#aba537117d2f8896a17f972d29824ee13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VNCoercion::isFirstClassAggregateOrScalableType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 12 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a54e6f143ee9c14b9498e4f43b97c2525">analyzeLoadFromClobberingStore</a>, <a href="#a1cdc82521ee78a15e2ca179d740a5049">analyzeLoadFromClobberingWrite</a> and <a href="#af10eb6aece68a8127f273e6a2dc0fc79">canCoerceMustAliasedValueToLoad</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/vncoercion-cpp">VNCoercion.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
