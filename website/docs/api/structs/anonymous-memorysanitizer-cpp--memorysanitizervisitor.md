---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MemorySanitizerVisitor` Struct Reference

<p>This class does all the work for a given function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor&lt;SubClass, RetTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for instruction visitors. <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af325004ae92c674ff92089a8a066e1e5">ShadowAndOriginCombiner</a> = <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/combiner">Combiner</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba2a43205c3dc6d42ed940d6bbbbbfc8">OriginCombiner</a> = <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/combiner">Combiner</a>&lt; false &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a> (Function &amp;F, MemorySanitizer &amp;MS, const TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0974eac64f313142c02ae973aca6359e">instrumentWithCalls</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc7b613059ab8f04e165d430bb736bba">isInPrologue</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab630c4065f79030c5d9c17998be71fd3">updateOrigin</a> (Value *V, IRBuilder&lt;&gt; &amp;IRB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045f288bf4edf0fe84985782706d4bb9">originToIntptr</a> (IRBuilder&lt;&gt; &amp;IRB, Value *Origin)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9b426f332b379758b891f032f85d52">paintOrigin</a> (IRBuilder&lt;&gt; &amp;IRB, Value *Origin, Value *OriginPtr, TypeSize TS, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fill memory range with the given origin value. <a href="#a4d9b426f332b379758b891f032f85d52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c704ed1965bd5d0348f156a8e33506">storeOrigin</a> (IRBuilder&lt;&gt; &amp;IRB, Value *Addr, Value *Shadow, Value *Origin, Value *OriginPtr, Align Alignment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09cbf4fc467ebb29733bdb77d74e7d07">materializeStores</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac02a2e35e2ad7efcce4dace2ac96a3a6">shouldDisambiguateWarningLocation</a> (const DebugLoc &amp;DebugLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4e542bdcac1a2ab15b6e55991f07c8">insertWarningFn</a> (IRBuilder&lt;&gt; &amp;IRB, Value *Origin)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to insert a warning at IRB's current insert point. <a href="#a9f4e542bdcac1a2ab15b6e55991f07c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6b95606a7aa4afbc8a38114dd8da82">materializeOneCheck</a> (IRBuilder&lt;&gt; &amp;IRB, Value *ConvertedShadow, Value *Origin)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0efb7aefc1fd76a565c2ced7d2ff14cb">materializeInstructionChecks</a> (ArrayRef&lt; ShadowOriginAndInsertPoint &gt; InstructionChecks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f56283bd67f32b385c705520aabb932">materializeChecks</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4fd8682f807900cbed932926bceb717">insertKmsanPrologue</a> (IRBuilder&lt;&gt; &amp;IRB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer">MemorySanitizer</a> instrumentation to a function. <a href="#a8605e39e73fa355574fd811094481af4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the shadow type that corresponds to a given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a5699c4e4d29dcada27c885790cab89b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03dd63ac617c1242b7694a4b0ae4ed25">getShadowTy</a> (Type *OrigTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the shadow type that corresponds to a given <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#a03dd63ac617c1242b7694a4b0ae4ed25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a811a74b2e69c5460dca8303638cde95d">collapseStructShadow</a> (StructType *Struct, Value *Shadow, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract combined shadow of struct elements as a bool. <a href="#a811a74b2e69c5460dca8303638cde95d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c3a2326fd156c2d77da47edbe608c4">collapseArrayShadow</a> (ArrayType *Array, Value *Shadow, IRBuilder&lt;&gt; &amp;IRB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a> (Value *V, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a shadow value to it's flattened variant. <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a> (Value *V, IRBuilder&lt;&gt; &amp;IRB, const Twine &amp;name="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a4b725eeca6669bc2adb458eb5e08f">ptrToIntPtrType</a> (Type *PtrTy) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac784928dcbbc1b0691cc8da90970391d">getPtrToShadowPtrType</a> (Type *IntPtrTy, Type *ShadowTy) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d139c7ee04d81813f05083f784f67b">constToIntPtr</a> (Type *IntPtrTy, uint64_t C) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecd57a29db63344a976ec5830496e733">getShadowPtrOffset</a> (Value *Addr, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the integer shadow offset that corresponds to a given application address, whereby: <a href="#aecd57a29db63344a976ec5830496e733">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac05ca292709f88f6ba0ae241e0e84bf">getShadowOriginPtrUserspace</a> (Value *Addr, IRBuilder&lt;&gt; &amp;IRB, Type *ShadowTy, MaybeAlign Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the shadow and origin addresses corresponding to a given application address. <a href="#aac05ca292709f88f6ba0ae241e0e84bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... ArgsTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0683904b75a4218c8915db0ec157614d">createMetadataCall</a> (IRBuilder&lt;&gt; &amp;IRB, FunctionCallee Callee, ArgsTy... Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad271462ad31f06423e02d373ce962cf1">getShadowOriginPtrKernelNoVec</a> (Value *Addr, IRBuilder&lt;&gt; &amp;IRB, Type *ShadowTy, bool isStore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7480612cfe31fd07e5d1d5d45bf3c3b4">getShadowOriginPtrKernel</a> (Value *Addr, IRBuilder&lt;&gt; &amp;IRB, Type *ShadowTy, bool isStore)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Addr can be a ptr or &lt;N x ptr&gt;. <a href="#a7480612cfe31fd07e5d1d5d45bf3c3b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a> (Value *Addr, IRBuilder&lt;&gt; &amp;IRB, Type *ShadowTy, MaybeAlign Alignment, bool isStore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8b252988733827abdf7bd44a8c2138">getShadowPtrForArgument</a> (IRBuilder&lt;&gt; &amp;IRB, int ArgOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the shadow address for a given function argument. <a href="#aad8b252988733827abdf7bd44a8c2138">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8530b6c2036643438422b73afe11d7e3">getOriginPtrForArgument</a> (IRBuilder&lt;&gt; &amp;IRB, int ArgOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the origin address for a given function argument. <a href="#a8530b6c2036643438422b73afe11d7e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55223c498ad94e7e49c3789aba0becce">getShadowPtrForRetval</a> (IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the shadow address for a retval. <a href="#a55223c498ad94e7e49c3789aba0becce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac996b058186b94adf7a2ae509803265">getOriginPtrForRetval</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the origin address for a retval. <a href="#aac996b058186b94adf7a2ae509803265">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a> (Value *V, Value *SV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set SV to be the shadow value for V. <a href="#aa479d62de65c7074b376392e3a34d0bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> (Value *V, Value *Origin)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set Origin to be the origin value for V. <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a> (Type *OrigTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ec1ca1ec0a1c96cf7497aee1bf0c1d">getCleanShadow</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clean shadow value for a given value. <a href="#aa2ec1ca1ec0a1c96cf7497aee1bf0c1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8632acd057dcbe9f0d3e2de9d2f9247">getPoisonedShadow</a> (Type *ShadowTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a dirty shadow of a given shadow type. <a href="#aa8632acd057dcbe9f0d3e2de9d2f9247">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d77673586722d48008ce4203b061990">getPoisonedShadow</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a dirty shadow for a given value. <a href="#a1d77673586722d48008ce4203b061990">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clean (zero) origin. <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the shadow value for a given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a82680be7fe808dbee556123d6ea82240">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadbe423dda76243270cc066dc9b11cba">getShadow</a> (Instruction *I, int i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the shadow for i-th argument of the instruction I. <a href="#aadbe423dda76243270cc066dc9b11cba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the origin for a value. <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a79c772bc4522605d3c4aac853499b">getOrigin</a> (Instruction *I, int i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the origin for i-th argument of the instruction I. <a href="#ac6a79c772bc4522605d3c4aac853499b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a> (Value *Shadow, Value *Origin, Instruction *OrigIns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remember the place where a shadow check should be inserted. <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf3df1ea61f4ce9ffc1c31eebcadc1bc">insertShadowCheck</a> (Value *Val, Instruction *OrigIns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remember the place where a shadow check should be inserted. <a href="#acf3df1ea61f4ce9ffc1c31eebcadc1bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d1bfd631c79b182628a0d619402223">addReleaseOrdering</a> (AtomicOrdering a)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ecfbb98ae6069aa910e8aba30aca1d9">makeAddReleaseOrderingTable</a> (IRBuilder&lt;&gt; &amp;IRB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03caf3afb42be700767d2a267c8b4465">addAcquireOrdering</a> (AtomicOrdering a)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62bf64531735d133d60ced4e7a4d4e03">makeAddAcquireOrderingTable</a> (IRBuilder&lt;&gt; &amp;IRB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78793329d41f7e0ff3ab15f71b2f952c">visit</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a> (LoadInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instrument <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a>. <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dad5091fba05972dc72b125bf3be373">visitStoreInst</a> (StoreInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instrument <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a>. <a href="#a1dad5091fba05972dc72b125bf3be373">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab772f88fd07120f87cd319177cea148b">visitAtomicRMWInst</a> (AtomicRMWInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378277a0a96b34b3b5634b8ffc865c8a">visitAtomicCmpXchgInst</a> (AtomicCmpXchgInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a162e1f6cd54269b8c906eb54ee6fb">visitExtractElementInst</a> (ExtractElementInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe4a56f60e1964a3e0ce781600334de">visitInsertElementInst</a> (InsertElementInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a464dafaad1c67c6d167dd70c6326dde9">visitShuffleVectorInst</a> (ShuffleVectorInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f2a1b9c4998624686b30ca88c98668">visitSExtInst</a> (SExtInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6035ac9679b9449d97646f9c16d135">visitZExtInst</a> (ZExtInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1d4c8c600e51aaa27f230e05e3d553">visitTruncInst</a> (TruncInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a005fbd5468607e9616160e82a7665c14">visitBitCastInst</a> (BitCastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5bb05e9c2a806f7a3c21eace99b1d7c">visitPtrToIntInst</a> (PtrToIntInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cfc49213d6647056b0e487dc90450b6">visitIntToPtrInst</a> (IntToPtrInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d0de74b72099fdc4de7d7c5796ef38">visitFPToSIInst</a> (CastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832b7cd0e1d0392191a2c9528448834f">visitFPToUIInst</a> (CastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d83677a081e8f0e23fe11742d83830">visitSIToFPInst</a> (CastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a517a594e0e43f88e71496ad09f1a70b1">visitUIToFPInst</a> (CastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6fa84c0a2c67733d35ecdbfbeafafe">visitFPExtInst</a> (CastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a04183d7317af48f216ae837acac4d">visitFPTruncInst</a> (CastInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4ed8c796cc564c14664505603f6aac1">visitAnd</a> (BinaryOperator &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate shadow for bitwise AND. <a href="#af4ed8c796cc564c14664505603f6aac1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684df7f760d6dcbfea36c5bccb2cfccd">visitOr</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate origin for arbitrary operation. <a href="#ad27037edeacf67c4b3583aee7122ade2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52481b174cfe6444a5ae320b20c5bef9">VectorOrPrimitiveTypeSizeInBits</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39d5c919a484d17c9e12864d869c7f69">CreateShadowCast</a> (IRBuilder&lt;&gt; &amp;IRB, Value *V, Type *dstTy, bool Signed=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast between two shadow types, extending or truncating as necessary. <a href="#a39d5c919a484d17c9e12864d869c7f69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfaba717423054f99dee516c7673db49">CreateAppToShadowCast</a> (IRBuilder&lt;&gt; &amp;IRB, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast an application value to the type of its own shadow. <a href="#abfaba717423054f99dee516c7673db49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate shadow for arbitrary operation. <a href="#a1425e0956a85489ea4a81c949b952094">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af773d6ca5d9dfe3770599c12a08b49be">visitFNeg</a> (UnaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4b3d9a1db2a863f398981ea5c1d641">handleMulByConstant</a> (BinaryOperator &amp;I, Constant *ConstArg, Value *OtherArg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58a23d4603a99873024af3b84b576c5e">visitMul</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05f7153a6433bd6da07e4dd29a3a4717">visitFAdd</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f33b0169f8f0c1322c247a869396d17">visitFSub</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af1fe1215239f5bb00b2bbe7e90b725">visitFMul</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a08f21840973827bfcca10650f0d09">visitAdd</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe140f3e1fa65182ae3bf0969027e9dd">visitSub</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a9601fb2a0770ca9a67ea574a1537e6">visitXor</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06652627b90ae944abff9433688f500c">visitUDiv</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe22967a17fc281dc3afea0bc761fa0">visitSDiv</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50b8121d06f8634d836bfe8e780b11d">visitURem</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65251363b4be778d2a855cb6acba2666">visitSRem</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7e1408f8587eab5d7a6795a6e51588">visitFDiv</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e7a7377cca5083d3473b9aa9b0edb61">visitFRem</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a823e9b0883ae72e62421714cd8bbda4c">handleEqualityComparison</a> (ICmpInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instrument == and != comparisons. <a href="#a823e9b0883ae72e62421714cd8bbda4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac689bdce81e76d215f170f7eb3821be3">handleRelationalComparisonExact</a> (ICmpInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instrument relational comparisons. <a href="#ac689bdce81e76d215f170f7eb3821be3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091a19fb76439b9fff59f052e2648ee9">handleSignedRelationalComparison</a> (ICmpInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instrument signed relational comparisons. <a href="#a091a19fb76439b9fff59f052e2648ee9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3175c69e435331710c2f03107ef3e8ef">visitICmpInst</a> (ICmpInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d47532127ac3c3ed48866788d07385b">visitFCmpInst</a> (FCmpInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220983874e8efc856fac602c19e9aa2b">handleShift</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704a1fee76597843c068885f90df5aa3">visitShl</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9d49d21ac59052e3d17d7fa01228325">visitAShr</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa1fcb2e2013a57001fcc43f065bfe3d">visitLShr</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04fa6c52e825a7d994a3a5eeb1cc4549">handleFunnelShift</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f93e75a1bd79aad5f817f9980e02cb3">visitMemMoveInst</a> (MemMoveInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instrument llvm.memmove. <a href="#a5f93e75a1bd79aad5f817f9980e02cb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec582588d2e3296c8e411ebf91d528b0">visitMemCpyInst</a> (MemCpyInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instrument memcpy. <a href="#aec582588d2e3296c8e411ebf91d528b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3057161fac6ccf0d0f7a55a9ce5e8665">visitMemSetInst</a> (MemSetInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8c53c8908f3a0686e62be14257a280">visitVAStartInst</a> (VAStartInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2220b57cb00d5580de4912c5e86bcb2">visitVACopyInst</a> (VACopyInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa386f90ca7b1b24989ce41d70a0ce052">handleVectorStoreIntrinsic</a> (IntrinsicInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle vector store-like intrinsics. <a href="#aa386f90ca7b1b24989ce41d70a0ce052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a> (IntrinsicInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle vector load-like intrinsics. <a href="#a0215817db88ff4446c80bf413c754c47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9266376e710920a1bd7999ed9c8963">maybeHandleSimpleNomemIntrinsic</a> (IntrinsicInst &amp;I, unsigned int trailingFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle (SIMD arithmetic)-like intrinsics. <a href="#a9c9266376e710920a1bd7999ed9c8963">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f6e0279d635bf21ceda6349d4afa02">handleUnknownIntrinsicUnlogged</a> (IntrinsicInst &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Heuristically instrument unknown intrinsics. <a href="#ac5f6e0279d635bf21ceda6349d4afa02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077e9376af4a6c07ade5704887b2fd49">handleUnknownIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e1c3d3c4ed3b31cb4921817214d40b">handleInvariantGroup</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dabd1eec85a33a1d90cf9b9356a3c58">handleLifetimeStart</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2487c76cffea045469d6e95ea3a724b0">handleBswap</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fdafd5b5245a6f5f14c41c593d10b69">handleCountZeroes</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec2e744dff018b81c0eb2a7e9ea4e2b">handleVectorConvertIntrinsic</a> (IntrinsicInst &amp;I, int NumUsedElements, bool HasRoundingMode=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a160d793aacc4ffadcdf86eddbf401c69">Lower64ShadowExtend</a> (IRBuilder&lt;&gt; &amp;IRB, Value *S, Type *T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a174a52b2885896fbf86e1250573168dc">LowerElementShadowExtend</a> (IRBuilder&lt;&gt; &amp;IRB, Value *S, Type *T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e1c458e5c141b448867b728af11ae9">VariableShadowExtend</a> (IRBuilder&lt;&gt; &amp;IRB, Value *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c328e6af190112474f8c694ccb59dc">handleVectorShiftIntrinsic</a> (IntrinsicInst &amp;I, bool Variable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3f2bc12df17a7c061c315f7bfcf12e">getMMXVectorTy</a> (unsigned EltSizeInBits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac33a8706b2108c930e0f7befe6942e29">getSignedPackIntrinsic</a> (Intrinsic::ID id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaaee38930abb5a8c5d6ff71045eda30">handleVectorPackIntrinsic</a> (IntrinsicInst &amp;I, unsigned MMXEltSizeInBits=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850fb4fba9984eb18393c06aa6fe3a51">createDppMask</a> (unsigned Width, unsigned Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51a05a00df99aa3401385eb46a6e5ae1">findDppPoisonedOutput</a> (IRBuilder&lt;&gt; &amp;IRB, Value *S, unsigned SrcMask, unsigned DstMask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa28fe1a3de7cc0e732f5d7ee1dc5adbd">handleDppIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40a1fc4e57a69c562fb3d215eaa71280">convertBlendvToSelectMask</a> (IRBuilder&lt;&gt; &amp;IRB, Value *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03d3c26f38bacbd611de31932ef80b4">handleVectorSadIntrinsic</a> (IntrinsicInst &amp;I, bool IsMMX=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a1bcee02000668d052f9d696ada2e9">handleVectorPmaddIntrinsic</a> (IntrinsicInst &amp;I, unsigned MMXEltSizeInBits=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dedad065b777ac076ac9f2b3dc8c013">handleVectorComparePackedIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fc06177748e14bf8ef287dc4347dde3">handleVectorCompareScalarIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14778d7f19c6c8582a65cb2d05b541ce">handleVectorReduceIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae160aa4ec35fca7aaa0f75a8526cb3fb">handleVectorReduceOrIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8abeeb6d127be621e8ee8d9d667503b2">handleVectorReduceAndIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a310b77dacdbac9c6bfd285af705de5">handleStmxcsr</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac621d92c3438d32c257d3e193ed64c2">handleLdmxcsr</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512e6c35c0ac3187be4445bab50b766e">handleMaskedCompressStore</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5056eaa4a9d5c87c3566577a0736c47d">handleMaskedScatter</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3405abbd1975b05777dc44d9089f1ece">handleMaskedStore</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048c7023875711345d33899f3a59f3e2">handleAVXMaskedLoad</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422552f3cad093347a5f83d234925e9d">handleBmiIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a924a1686eaef2f0a0ded248edc2bdb6c">handlePclmulIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9ab401ce01af2ea722f41cfb8e4943">handleUnarySdSsIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27c11aacbd4098eca944c41583e759d0">handleVtestIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bde622b06aafdb9eb49069b756563ce">handleBinarySdSsIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add81ddc58cfd39fc90b163af92a71bca">handleRoundPdPsIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dff8a9ea4e4cf80ae780052b6361819">handleAbsIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac166d600b506872ca9d2d69c7f587c2d">handleIsFpClass</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9890e049561cd883603c6a483547b6b5">handleArithmeticWithOverflow</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fbb73043c2f82e97b7a704a91f47dc1">handleAVXHorizontalAddSubIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78bfa47c700608c53890cc25cd44a5b">handleNEONVectorStoreIntrinsic</a> (IntrinsicInst &amp;I, bool useLane)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle Arm NEON vector store intrinsics (vst{2,3,4}, vst1x_{2,3,4}, and vst{2,3,4}lane). <a href="#aa78bfa47c700608c53890cc25cd44a5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94631928dd87cd8134a31c5fb3168c70">handleIntrinsicByApplyingToShadow</a> (IntrinsicInst &amp;I, Intrinsic::ID shadowIntrinsicID, unsigned int trailingVerbatimArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle intrinsics by applying the intrinsic to the shadows. <a href="#a94631928dd87cd8134a31c5fb3168c70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af56d49d9b0002920b7190ddb0f3585ff">handleNEONVectorMultiplyIntrinsic</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b2c0b28c3d1ee4253d2aae4f9172d94">visitLibAtomicLoad</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe25be4a6081ab8cac7639e57970ec3c">visitLibAtomicStore</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1444d314e49ffb031f0abd54b3b7ceb">isAMustTailRetVal</a> (Value *RetVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357ae07ce43e35a35899d18f25ea005c">visitReturnInst</a> (ReturnInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88958577efd3c314497a72ea96c60eac">visitPHINode</a> (PHINode &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd41cd05155ed81f0ac16e8a478b860">getLocalVarIdptr</a> (AllocaInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d656b8ad508d9b36144ca1db4f95181">getLocalVarDescription</a> (AllocaInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e8c5cbc0a9f0269b50f08a187c2f78">poisonAllocaUserspace</a> (AllocaInst &amp;I, IRBuilder&lt;&gt; &amp;IRB, Value *Len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a965b050969c112696e764545b231e">poisonAllocaKmsan</a> (AllocaInst &amp;I, IRBuilder&lt;&gt; &amp;IRB, Value *Len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd39b18dfd59223eea65852ed04b338e">instrumentAlloca</a> (AllocaInst &amp;I, Instruction *InsPoint=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad360018df823d021f17fd6612acecacf">visitAllocaInst</a> (AllocaInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09992489ef0854c6f12d58bf250db0e4">visitSelectInst</a> (SelectInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a> (Instruction &amp;I, Value *B, Value *C, Value *D)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ebff796e583fc774c4b7ddd669735b">visitLandingPadInst</a> (LandingPadInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc330182e6404dbe33f4a58f24ee722c">visitCatchSwitchInst</a> (CatchSwitchInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af47d161cc73a6bddb356cc121c66322a">visitFuncletPadInst</a> (FuncletPadInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fd0cd313fa1a80f8aabf5a31cc67d34">visitGetElementPtrInst</a> (GetElementPtrInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a02eeff88a7467b6a84a310b3e9eee">visitExtractValueInst</a> (ExtractValueInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aead566fef3a7ebeb14cd72efb473079a">visitInsertValueInst</a> (InsertValueInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accd1cfbd692f327894828f50c24ad3b6">dumpInst</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e26c08a2b7611381a48e195e8a49b8d">visitResumeInst</a> (ResumeInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9caf4fd36aa8e31bd25af1576ee565">visitCleanupReturnInst</a> (CleanupReturnInst &amp;CRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0424da9b791eb2771ef16a9407e8a5cb">visitCatchReturnInst</a> (CatchReturnInst &amp;CRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5393f64ef6c65d1f090169819b68598">instrumentAsmArgument</a> (Value *Operand, Type *ElemTy, Instruction &amp;I, IRBuilder&lt;&gt; &amp;IRB, const DataLayout &amp;DL, bool isOutput)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a155073ec24bee89eeab846ccc4e7108e">getNumOutputArgs</a> (InlineAsm *IA, CallBase *CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of output arguments returned by pointers. <a href="#a155073ec24bee89eeab846ccc4e7108e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27c9f05f074b1acd44859e85c1212bc1">visitAsmInstruction</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a03aae53393e1535618f885dd8e113">visitFreezeInst</a> (FreezeInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232a0fe878bb0a5a47219195daadca39">visitInstruction</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23454d4124e41a388132c0de01d450ff">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer">MemorySanitizer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5287beec429ac02e5db213256dcd8776">ShadowPHINodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7317314e7a515a2b952b59ead684d49f">OriginPHINodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72ba6bf0adbad0f1134ed2e8a62b318">ShadowMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d20d8cd675fe8f162888d38bcc0ea99">OriginMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararghelper">VarArgHelper</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57aec2acd87151c727180e766c8f4dab">VAHelper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab431a36084a5700a1f4b518da053f419">TLI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4feeefbf4ec513bf876399ce4b84aad1">FnPrologueEnd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6f4541cb285cd7d00759c8ffddf9f69">Instructions</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61ccc8f79b82b8f106096534fddbdd03">InsertChecks</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2198d20c59c67c9de6b25fd45c9262ea">PoisonStack</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a8e97da337e78573f55cc8cf4c4500f">PoisonUndef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/shadoworiginandinsertpoint">ShadowOriginAndInsertPoint</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f569d5ad463a4c719f0e8d4d9d5ae8">InstrumentationList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f7bf4d0adbe765573bbbbbc89ddd626">LazyWarningDebugLocationCount</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4b8995820e03b05d6530e8cc2c0752">InstrumentLifetimeStart</a> = <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a9b9c616adc23214477236548737858c1">ClHandleLifetimeIntrinsics</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620d735c5fea0163960071e5a3e99a4a">AllocaSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53bb2da7b8d4e6eb90cd44d1e3556af7">LifetimeStartList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e17cdef6be3fbe65c97bed1a437f040">StoreList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6041f8f61469e7649e9f9ad33a5be8b6">SplittableBlocksCount</a> = 0</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a3c88ff7689bdb2a981cf1e8710273">getPclmulMask</a> (unsigned Width, bool OddElements)</td>
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

<p>This class does all the work for a given function.</p>


<p>Store and Load instructions store and load corresponding shadow and origin values. Most instructions propagate shadow from arguments to their return values. Certain instructions (most importantly, <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a>) test their argument shadow and print reports (with a runtime call) if it's non-zero.</p>


<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### OriginCombiner {#aba2a43205c3dc6d42ed940d6bbbbbfc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::OriginCombiner =  Combiner&lt;false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2539 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>

</div>
</div>

### ShadowAndOriginCombiner {#af325004ae92c674ff92089a8a066e1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::ShadowAndOriginCombiner =  Combiner&lt;true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2538 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemorySanitizerVisitor() {#aec3293074efad01a669018f6c46f3219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::MemorySanitizerVisitor (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer">MemorySanitizer</a> &amp; MS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#aff7a784ef2ba8136fb338f23bccc8c17">ClDisableChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a848e1ebd611f366583fc79c1c5ff2392">ClPoisonStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a8438c35f22f870c5e2cafe47130fecb5">ClPoisonUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#abb08ae2f213bc5b87540413de9b095a2">CreateVarArgHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="#a4feeefbf4ec513bf876399ce4b84aad1">FnPrologueEnd</a>, <a href="#a61ccc8f79b82b8f106096534fddbdd03">InsertChecks</a>, <a href="#ad4fd8682f807900cbed932926bceb717">insertKmsanPrologue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa241826e10b4a9bf77c3115e7160d3c7">llvm::IRBuilder</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a2198d20c59c67c9de6b25fd45c9262ea">PoisonStack</a>, <a href="#a2a8e97da337e78573f55cc8cf4c4500f">PoisonUndef</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec88b7682025edff7984c3b6c8da8ac9">llvm::removeUnreachableBlocks</a>, <a href="#ab431a36084a5700a1f4b518da053f419">TLI</a> and <a href="#a57aec2acd87151c727180e766c8f4dab">VAHelper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/combiner/#a6823477775469222f5d39f48ffee81e1">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::Combiner&lt; true &gt;::Combiner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAcquireOrdering() {#a03caf3afb42be700767d2a267c8b4465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::addAcquireOrdering (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> a)</td>
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



<p>Definition at line 2189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### addReleaseOrdering() {#a25d1bfd631c79b182628a0d619402223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::addReleaseOrdering (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> a)</td>
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



<p>Definition at line 2155 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### collapseArrayShadow() {#ae6c3a2326fd156c2d77da47edbe608c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::collapseArrayShadow (<a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a> * Array, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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



<p>Definition at line 1654 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a>.</p>


<p>Referenced by <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>.</p>

</div>
</div>

### collapseStructShadow() {#a811a74b2e69c5460dca8303638cde95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::collapseStructShadow (<a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * Struct, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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

<p>Extract combined shadow of struct elements as a bool.</p>

<p>Definition at line 1634 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a763a932e166ac85a6d2d1606e8649993">Struct</a>.</p>


<p>Referenced by <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>.</p>

</div>
</div>

### constToIntPtr() {#a06d139c7ee04d81813f05083f784f67b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::constToIntPtr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IntPtrTy, uint64_t C)</td>
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



<p>Definition at line 1718 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a06d139c7ee04d81813f05083f784f67b">constToIntPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a06d139c7ee04d81813f05083f784f67b">constToIntPtr</a>, <a href="#aac05ca292709f88f6ba0ae241e0e84bf">getShadowOriginPtrUserspace</a> and <a href="#aecd57a29db63344a976ec5830496e733">getShadowPtrOffset</a>.</p>

</div>
</div>

### convertBlendvToSelectMask() {#a40a1fc4e57a69c562fb3d215eaa71280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertBlendvToSelectMask (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * C)</td>
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



<p>Definition at line 3398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#abfaba717423054f99dee516c7673db49">CreateAppToShadowCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#adc6a2686b807c18e4a7f7fc58e68d423">llvm::IRBuilderBase::CreateAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1fb6e8365dbf4ef3a7426ff3d531ff87">llvm::IRBuilderBase::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>.</p>


<p>Referenced by <a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a>.</p>

</div>
</div>

### convertShadowToScalar() {#a48d6d1fbffc492921f07f8dc4fb3d875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertShadowToScalar (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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

<p>Convert a shadow value to it's flattened variant.</p>


<p>The resulting shadow may not necessarily have the same bit width as the input value, but it will always be comparable to zero.</p>


<p>Definition at line 1673 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#ae6c3a2326fd156c2d77da47edbe608c4">collapseArrayShadow</a>, <a href="#a811a74b2e69c5460dca8303638cde95d">collapseStructShadow</a>, <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a784d99f22cf1632638a2fa652e7723d1">llvm::IRBuilderBase::CreateOrReduce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a763a932e166ac85a6d2d1606e8649993">Struct</a>.</p>


<p>Referenced by <a href="#ae6c3a2326fd156c2d77da47edbe608c4">collapseArrayShadow</a>, <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>, <a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a>, <a href="#a27c11aacbd4098eca944c41583e759d0">handleVtestIntrinsic</a>, <a href="#a2a6b95606a7aa4afbc8a38114dd8da82">materializeOneCheck</a> and <a href="#a00c704ed1965bd5d0348f156a8e33506">storeOrigin</a>.</p>

</div>
</div>

### convertToBool() {#a6c2f0057515e3f4b8e14cfb9dcb789ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertToBool (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; name="")</td>
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



<p>Definition at line 1689 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>, <a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a13e877ef779ba7a0688081079f4f9b03">llvm::Type::getIntegerBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>


<p>Referenced by <a href="#a811a74b2e69c5460dca8303638cde95d">collapseStructShadow</a>, <a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>, <a href="#a0efb7aefc1fd76a565c2ced7d2ff14cb">materializeInstructionChecks</a>, <a href="#a2a6b95606a7aa4afbc8a38114dd8da82">materializeOneCheck</a> and <a href="#a00c704ed1965bd5d0348f156a8e33506">storeOrigin</a>.</p>

</div>
</div>

### CreateAppToShadowCast() {#abfaba717423054f99dee516c7673db49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::CreateAppToShadowCast (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Cast an application value to the type of its own shadow.</p>

<p>Definition at line 2586 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a> and <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>.</p>


<p>Referenced by <a href="#a40a1fc4e57a69c562fb3d215eaa71280">convertBlendvToSelectMask</a> and <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>.</p>

</div>
</div>

### createDppMask() {#a850fb4fba9984eb18393c06aa6fe3a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::createDppMask (unsigned Width, unsigned Mask)</td>
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



<p>Definition at line 3330 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a> and <a href="/web-llvm/docs/api/classes/llvm/constantint/#afe7d477c6022fe7123b90e3b39c58e69">llvm::ConstantInt::getBool</a>.</p>


<p>Referenced by <a href="#a51a05a00df99aa3401385eb46a6e5ae1">findDppPoisonedOutput</a>.</p>

</div>
</div>

### createMetadataCall() {#a0683904b75a4218c8915db0ec157614d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... ArgsTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::createMetadataCall (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> Callee, ArgsTy... Args)</td>
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



<p>Definition at line 1794 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">llvm::Triple::systemz</a>.</p>


<p>Referenced by <a href="#ad271462ad31f06423e02d373ce962cf1">getShadowOriginPtrKernelNoVec</a>.</p>

</div>
</div>

### CreateShadowCast() {#a39d5c919a484d17c9e12864d869c7f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::CreateShadowCast (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * dstTy, bool Signed=false)</td>
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

<p>Cast between two shadow types, extending or truncating as necessary.</p>

<p>Definition at line 2562 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a> and <a href="#a52481b174cfe6444a5ae320b20c5bef9">VectorOrPrimitiveTypeSizeInBits</a>.</p>


<p>Referenced by <a href="#a94631928dd87cd8134a31c5fb3168c70">handleIntrinsicByApplyingToShadow</a>, <a href="#a160d793aacc4ffadcdf86eddbf401c69">Lower64ShadowExtend</a> and <a href="#a174a52b2885896fbf86e1250573168dc">LowerElementShadowExtend</a>.</p>

</div>
</div>

### dumpInst() {#accd1cfbd692f327894828f50c24ad3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::dumpInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 5267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a077e9376af4a6c07ade5704887b2fd49">handleUnknownIntrinsic</a> and <a href="#a232a0fe878bb0a5a47219195daadca39">visitInstruction</a>.</p>

</div>
</div>

### findDppPoisonedOutput() {#a51a05a00df99aa3401385eb46a6e5ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::findDppPoisonedOutput (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, unsigned SrcMask, unsigned DstMask)</td>
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



<p>Definition at line 3341 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a850fb4fba9984eb18393c06aa6fe3a51">createDppMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac9843b4f9f9cb144c608c48785a394a8">llvm::IRBuilderBase::CreateIsNull</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a784d99f22cf1632638a2fa652e7723d1">llvm::IRBuilderBase::CreateOrReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#aa28fe1a3de7cc0e732f5d7ee1dc5adbd">handleDppIntrinsic</a>.</p>

</div>
</div>

### getCleanOrigin() {#ab66ea2a3c3ef79789f3bc37709c2cb61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getCleanOrigin ()</td>
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

<p>Create a clean (zero) origin.</p>

<p>Definition at line 1963 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a>, <a href="#aac621d92c3438d32c257d3e193ed64c2">handleLdmxcsr</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a8ec2e744dff018b81c0eb2a7e9ea4e2b">handleVectorConvertIntrinsic</a>, <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#a78793329d41f7e0ff3ab15f71b2f952c">visit</a>, <a href="#ad360018df823d021f17fd6612acecacf">visitAllocaInst</a>, <a href="#a27c9f05f074b1acd44859e85c1212bc1">visitAsmInstruction</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#acc330182e6404dbe33f4a58f24ee722c">visitCatchSwitchInst</a>, <a href="#a80a03aae53393e1535618f885dd8e113">visitFreezeInst</a>, <a href="#af47d161cc73a6bddb356cc121c66322a">visitFuncletPadInst</a>, <a href="#a232a0fe878bb0a5a47219195daadca39">visitInstruction</a>, <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>, <a href="#a54ebff796e583fc774c4b7ddd669735b">visitLandingPadInst</a>, <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a> and <a href="#a88958577efd3c314497a72ea96c60eac">visitPHINode</a>.</p>

</div>
</div>

### getCleanShadow() {#adafc284209e45c14f874dee849b2afd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getCleanShadow (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OrigTy)</td>
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



<p>Definition at line 1922 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a> and <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>.</p>


<p>Referenced by <a href="#a39d5c919a484d17c9e12864d869c7f69">CreateShadowCast</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a9890e049561cd883603c6a483547b6b5">handleArithmeticWithOverflow</a>, <a href="#a422552f3cad093347a5f83d234925e9d">handleBmiIntrinsic</a>, <a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a>, <a href="#a04fa6c52e825a7d994a3a5eeb1cc4549">handleFunnelShift</a>, <a href="#ac166d600b506872ca9d2d69c7f587c2d">handleIsFpClass</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a220983874e8efc856fac602c19e9aa2b">handleShift</a>, <a href="#a091a19fb76439b9fff59f052e2648ee9">handleSignedRelationalComparison</a>, <a href="#a7a310b77dacdbac9c6bfd285af705de5">handleStmxcsr</a>, <a href="#a8ec2e744dff018b81c0eb2a7e9ea4e2b">handleVectorConvertIntrinsic</a>, <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#ad5393f64ef6c65d1f090169819b68598">instrumentAsmArgument</a>, <a href="#a160d793aacc4ffadcdf86eddbf401c69">Lower64ShadowExtend</a>, <a href="#a174a52b2885896fbf86e1250573168dc">LowerElementShadowExtend</a>, <a href="#a09cbf4fc467ebb29733bdb77d74e7d07">materializeStores</a>, <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>, <a href="#a02e1c458e5c141b448867b728af11ae9">VariableShadowExtend</a>, <a href="#a78793329d41f7e0ff3ab15f71b2f952c">visit</a>, <a href="#ad360018df823d021f17fd6612acecacf">visitAllocaInst</a>, <a href="#a27c9f05f074b1acd44859e85c1212bc1">visitAsmInstruction</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#acc330182e6404dbe33f4a58f24ee722c">visitCatchSwitchInst</a>, <a href="#a80a03aae53393e1535618f885dd8e113">visitFreezeInst</a>, <a href="#af47d161cc73a6bddb356cc121c66322a">visitFuncletPadInst</a>, <a href="#a232a0fe878bb0a5a47219195daadca39">visitInstruction</a>, <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>, <a href="#a54ebff796e583fc774c4b7ddd669735b">visitLandingPadInst</a>, <a href="#abe25be4a6081ab8cac7639e57970ec3c">visitLibAtomicStore</a>, <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a>, <a href="#a88958577efd3c314497a72ea96c60eac">visitPHINode</a> and <a href="#a357ae07ce43e35a35899d18f25ea005c">visitReturnInst</a>.</p>

</div>
</div>

### getCleanShadow() {#aa2ec1ca1ec0a1c96cf7497aee1bf0c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getCleanShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Create a clean shadow value for a given value.</p>


<p>Clean shadow (all zeroes) means all bits of the value are defined (initialized).</p>


<p>Definition at line 1933 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Reference <a href="#aa2ec1ca1ec0a1c96cf7497aee1bf0c1d">getCleanShadow</a>.</p>


<p>Referenced by <a href="#aa2ec1ca1ec0a1c96cf7497aee1bf0c1d">getCleanShadow</a>.</p>

</div>
</div>

### getLocalVarDescription() {#a9d656b8ad508d9b36144ca1db4f95181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getLocalVarDescription (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I)</td>
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



<p>Definition at line 5105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#aa4ec1be5a80593697012bc67e2410e11">createPrivateConstGlobalForString</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a36a965b050969c112696e764545b231e">poisonAllocaKmsan</a> and <a href="#a00e8c5cbc0a9f0269b50f08a187c2f78">poisonAllocaUserspace</a>.</p>

</div>
</div>

### getLocalVarIdptr() {#a0fd41cd05155ed81f0ac16e8a478b860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getLocalVarIdptr (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I)</td>
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



<p>Definition at line 5097 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>.</p>


<p>Referenced by <a href="#a00e8c5cbc0a9f0269b50f08a187c2f78">poisonAllocaUserspace</a>.</p>

</div>
</div>

### getMMXVectorTy() {#abe3f2bc12df17a7c061c315f7bfcf12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getMMXVectorTy (unsigned EltSizeInBits)</td>
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



<p>Definition at line 3248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#acaaee38930abb5a8c5d6ff71045eda30">handleVectorPackIntrinsic</a> and <a href="#a60a1bcee02000668d052f9d696ada2e9">handleVectorPmaddIntrinsic</a>.</p>

</div>
</div>

### getNumOutputArgs() {#a155073ec24bee89eeab846ccc4e7108e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getNumOutputArgs (<a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> * IA, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
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

<p>Get the number of output arguments returned by pointers.</p>

<p>Definition at line 5327 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34aabfa616f81b4833fdf462b07aabfa53f">llvm::InlineAsm::isOutput</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>.</p>


<p>Referenced by <a href="#a27c9f05f074b1acd44859e85c1212bc1">visitAsmInstruction</a>.</p>

</div>
</div>

### getOrigin() {#ad9e803443a8b2a6d25a73a6b4b2d6560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getOrigin (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Get the origin for a value.</p>

<p>Definition at line 2088 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a1d20d8cd675fe8f162888d38bcc0ea99">OriginMap</a> and <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>.</p>


<p>Referenced by <a href="#ac6a79c772bc4522605d3c4aac853499b">getOrigin</a>, <a href="#a6dff8a9ea4e4cf80ae780052b6361819">handleAbsIntrinsic</a>, <a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a>, <a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a>, <a href="#a2487c76cffea045469d6e95ea3a724b0">handleBswap</a>, <a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a>, <a href="#a70e1c3d3c4ed3b31cb4921817214d40b">handleInvariantGroup</a>, <a href="#ac166d600b506872ca9d2d69c7f587c2d">handleIsFpClass</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a5056eaa4a9d5c87c3566577a0736c47d">handleMaskedScatter</a>, <a href="#a3405abbd1975b05777dc44d9089f1ece">handleMaskedStore</a>, <a href="#a1f4b3d9a1db2a863f398981ea5c1d641">handleMulByConstant</a>, <a href="#a924a1686eaef2f0a0ded248edc2bdb6c">handlePclmulIntrinsic</a>, <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>, <a href="#a091a19fb76439b9fff59f052e2648ee9">handleSignedRelationalComparison</a>, <a href="#a8ec2e744dff018b81c0eb2a7e9ea4e2b">handleVectorConvertIntrinsic</a>, <a href="#a8abeeb6d127be621e8ee8d9d667503b2">handleVectorReduceAndIntrinsic</a>, <a href="#a14778d7f19c6c8582a65cb2d05b541ce">handleVectorReduceIntrinsic</a>, <a href="#ae160aa4ec35fca7aaa0f75a8526cb3fb">handleVectorReduceOrIntrinsic</a>, <a href="#aa386f90ca7b1b24989ce41d70a0ce052">handleVectorStoreIntrinsic</a>, <a href="#acf3df1ea61f4ce9ffc1c31eebcadc1bc">insertShadowCheck</a>, <a href="#a09cbf4fc467ebb29733bdb77d74e7d07">materializeStores</a>, <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>, <a href="#a005fbd5468607e9616160e82a7665c14">visitBitCastInst</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#af4a162e1f6cd54269b8c906eb54ee6fb">visitExtractElementInst</a>, <a href="#a0cfc49213d6647056b0e487dc90450b6">visitIntToPtrInst</a>, <a href="#ac5bb05e9c2a806f7a3c21eace99b1d7c">visitPtrToIntInst</a>, <a href="#a357ae07ce43e35a35899d18f25ea005c">visitReturnInst</a>, <a href="#a22f2a1b9c4998624686b30ca88c98668">visitSExtInst</a>, <a href="#a3d1d4c8c600e51aaa27f230e05e3d553">visitTruncInst</a> and <a href="#aab6035ac9679b9449d97646f9c16d135">visitZExtInst</a>.</p>

</div>
</div>

### getOrigin() {#ac6a79c772bc4522605d3c4aac853499b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getOrigin (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, int i)</td>
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

<p>Get the origin for i-th argument of the instruction I.</p>

<p>Definition at line 2105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getOriginPtrForArgument() {#a8530b6c2036643438422b73afe11d7e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getOriginPtrForArgument (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, int ArgOffset)</td>
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

<p>Compute the origin address for a given function argument.</p>

<p>Definition at line 1887 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a> and <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>.</p>

</div>
</div>

### getOriginPtrForRetval() {#aac996b058186b94adf7a2ae509803265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getOriginPtrForRetval ()</td>
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

<p>Compute the origin address for a retval.</p>

<p>Definition at line 1902 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Reference <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a> and <a href="#a357ae07ce43e35a35899d18f25ea005c">visitReturnInst</a>.</p>

</div>
</div>

### getPoisonedShadow() {#aa8632acd057dcbe9f0d3e2de9d2f9247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getPoisonedShadow (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ShadowTy)</td>
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

<p>Create a dirty shadow of a given shadow type.</p>

<p>Definition at line 1936 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#a0900dacdc7ad8e3ea0cc92993c7fd422">llvm::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="#aa8632acd057dcbe9f0d3e2de9d2f9247">getPoisonedShadow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aa8632acd057dcbe9f0d3e2de9d2f9247">getPoisonedShadow</a>, <a href="#a1d77673586722d48008ce4203b061990">getPoisonedShadow</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a> and <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>.</p>

</div>
</div>

### getPoisonedShadow() {#a1d77673586722d48008ce4203b061990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getPoisonedShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Create a dirty shadow for a given value.</p>

<p>Definition at line 1955 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#aa8632acd057dcbe9f0d3e2de9d2f9247">getPoisonedShadow</a> and <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>.</p>

</div>
</div>

### getPtrToShadowPtrType() {#ac784928dcbbc1b0691cc8da90970391d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getPtrToShadowPtrType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IntPtrTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ShadowTy)</td>
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



<p>Definition at line 1708 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="#ac784928dcbbc1b0691cc8da90970391d">getPtrToShadowPtrType</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#ac784928dcbbc1b0691cc8da90970391d">getPtrToShadowPtrType</a> and <a href="#aac05ca292709f88f6ba0ae241e0e84bf">getShadowOriginPtrUserspace</a>.</p>

</div>
</div>

### getShadow() {#a82680be7fe808dbee556123d6ea82240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Get the shadow value for a given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>This function either returns the value set earlier with setShadow, or extracts if from ParamTLS (for function arguments).</p>


<p>Definition at line 1969 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a421c6b20238e6e6585270538188f15b9">llvm::AllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4910aab8d7c5528c1a3ac747856c3186">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="#a4feeefbf4ec513bf876399ce4b84aad1">FnPrologueEnd</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a8530b6c2036643438422b73afe11d7e3">getOriginPtrForArgument</a>, <a href="#aa8632acd057dcbe9f0d3e2de9d2f9247">getPoisonedShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#aad8b252988733827abdf7bd44a8c2138">getShadowPtrForArgument</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#adce9aed4162f58fbab5da93984822c3a">kParamTLSSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a2a8e97da337e78573f55cc8cf4c4500f">PoisonUndef</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a>, <a href="#af72ba6bf0adbad0f1134ed2e8a62b318">ShadowMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#aadbe423dda76243270cc066dc9b11cba">getShadow</a>, <a href="#a6dff8a9ea4e4cf80ae780052b6361819">handleAbsIntrinsic</a>, <a href="#a9890e049561cd883603c6a483547b6b5">handleArithmeticWithOverflow</a>, <a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a>, <a href="#a0bde622b06aafdb9eb49069b756563ce">handleBinarySdSsIntrinsic</a>, <a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a>, <a href="#a422552f3cad093347a5f83d234925e9d">handleBmiIntrinsic</a>, <a href="#a2487c76cffea045469d6e95ea3a724b0">handleBswap</a>, <a href="#a0fdafd5b5245a6f5f14c41c593d10b69">handleCountZeroes</a>, <a href="#aa28fe1a3de7cc0e732f5d7ee1dc5adbd">handleDppIntrinsic</a>, <a href="#a823e9b0883ae72e62421714cd8bbda4c">handleEqualityComparison</a>, <a href="#a04fa6c52e825a7d994a3a5eeb1cc4549">handleFunnelShift</a>, <a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a>, <a href="#a94631928dd87cd8134a31c5fb3168c70">handleIntrinsicByApplyingToShadow</a>, <a href="#a70e1c3d3c4ed3b31cb4921817214d40b">handleInvariantGroup</a>, <a href="#ac166d600b506872ca9d2d69c7f587c2d">handleIsFpClass</a>, <a href="#a512e6c35c0ac3187be4445bab50b766e">handleMaskedCompressStore</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a5056eaa4a9d5c87c3566577a0736c47d">handleMaskedScatter</a>, <a href="#a3405abbd1975b05777dc44d9089f1ece">handleMaskedStore</a>, <a href="#a1f4b3d9a1db2a863f398981ea5c1d641">handleMulByConstant</a>, <a href="#aa78bfa47c700608c53890cc25cd44a5b">handleNEONVectorStoreIntrinsic</a>, <a href="#a924a1686eaef2f0a0ded248edc2bdb6c">handlePclmulIntrinsic</a>, <a href="#ac689bdce81e76d215f170f7eb3821be3">handleRelationalComparisonExact</a>, <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>, <a href="#a220983874e8efc856fac602c19e9aa2b">handleShift</a>, <a href="#a091a19fb76439b9fff59f052e2648ee9">handleSignedRelationalComparison</a>, <a href="#aef9ab401ce01af2ea722f41cfb8e4943">handleUnarySdSsIntrinsic</a>, <a href="#a2dedad065b777ac076ac9f2b3dc8c013">handleVectorComparePackedIntrinsic</a>, <a href="#a3fc06177748e14bf8ef287dc4347dde3">handleVectorCompareScalarIntrinsic</a>, <a href="#a8ec2e744dff018b81c0eb2a7e9ea4e2b">handleVectorConvertIntrinsic</a>, <a href="#acaaee38930abb5a8c5d6ff71045eda30">handleVectorPackIntrinsic</a>, <a href="#a60a1bcee02000668d052f9d696ada2e9">handleVectorPmaddIntrinsic</a>, <a href="#a8abeeb6d127be621e8ee8d9d667503b2">handleVectorReduceAndIntrinsic</a>, <a href="#a14778d7f19c6c8582a65cb2d05b541ce">handleVectorReduceIntrinsic</a>, <a href="#ae160aa4ec35fca7aaa0f75a8526cb3fb">handleVectorReduceOrIntrinsic</a>, <a href="#ac03d3c26f38bacbd611de31932ef80b4">handleVectorSadIntrinsic</a>, <a href="#af1c328e6af190112474f8c694ccb59dc">handleVectorShiftIntrinsic</a>, <a href="#aa386f90ca7b1b24989ce41d70a0ce052">handleVectorStoreIntrinsic</a>, <a href="#a27c11aacbd4098eca944c41583e759d0">handleVtestIntrinsic</a>, <a href="#acf3df1ea61f4ce9ffc1c31eebcadc1bc">insertShadowCheck</a>, <a href="#a09cbf4fc467ebb29733bdb77d74e7d07">materializeStores</a>, <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>, <a href="#af4ed8c796cc564c14664505603f6aac1">visitAnd</a>, <a href="#a005fbd5468607e9616160e82a7665c14">visitBitCastInst</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#af4a162e1f6cd54269b8c906eb54ee6fb">visitExtractElementInst</a>, <a href="#a47a02eeff88a7467b6a84a310b3e9eee">visitExtractValueInst</a>, <a href="#afbe4a56f60e1964a3e0ce781600334de">visitInsertElementInst</a>, <a href="#aead566fef3a7ebeb14cd72efb473079a">visitInsertValueInst</a>, <a href="#a0cfc49213d6647056b0e487dc90450b6">visitIntToPtrInst</a>, <a href="#aec582588d2e3296c8e411ebf91d528b0">visitMemCpyInst</a>, <a href="#a5f93e75a1bd79aad5f817f9980e02cb3">visitMemMoveInst</a>, <a href="#a684df7f760d6dcbfea36c5bccb2cfccd">visitOr</a>, <a href="#ac5bb05e9c2a806f7a3c21eace99b1d7c">visitPtrToIntInst</a>, <a href="#a357ae07ce43e35a35899d18f25ea005c">visitReturnInst</a>, <a href="#a22f2a1b9c4998624686b30ca88c98668">visitSExtInst</a>, <a href="#a464dafaad1c67c6d167dd70c6326dde9">visitShuffleVectorInst</a>, <a href="#a3d1d4c8c600e51aaa27f230e05e3d553">visitTruncInst</a> and <a href="#aab6035ac9679b9449d97646f9c16d135">visitZExtInst</a>.</p>

</div>
</div>

### getShadow() {#aadbe423dda76243270cc066dc9b11cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadow (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, int i)</td>
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

<p>Get the shadow for i-th argument of the instruction I.</p>

<p>Definition at line 2083 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getShadowOriginPtr() {#a57a4c9ec10c3c1a796f9ca3363c5045f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ShadowTy, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment, bool isStore)</td>
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



<p>Definition at line 1867 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a7480612cfe31fd07e5d1d5d45bf3c3b4">getShadowOriginPtrKernel</a>, <a href="#aac05ca292709f88f6ba0ae241e0e84bf">getShadowOriginPtrUserspace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#aab5329eaa9a958adfa2c8de4d24e16cc">isStore</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a048c7023875711345d33899f3a59f3e2">handleAVXMaskedLoad</a>, <a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a>, <a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a>, <a href="#aac621d92c3438d32c257d3e193ed64c2">handleLdmxcsr</a>, <a href="#a512e6c35c0ac3187be4445bab50b766e">handleMaskedCompressStore</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a5056eaa4a9d5c87c3566577a0736c47d">handleMaskedScatter</a>, <a href="#a3405abbd1975b05777dc44d9089f1ece">handleMaskedStore</a>, <a href="#aa78bfa47c700608c53890cc25cd44a5b">handleNEONVectorStoreIntrinsic</a>, <a href="#a7a310b77dacdbac9c6bfd285af705de5">handleStmxcsr</a>, <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#aa386f90ca7b1b24989ce41d70a0ce052">handleVectorStoreIntrinsic</a>, <a href="#a09cbf4fc467ebb29733bdb77d74e7d07">materializeStores</a>, <a href="#a00e8c5cbc0a9f0269b50f08a187c2f78">poisonAllocaUserspace</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#a9b2c0b28c3d1ee4253d2aae4f9172d94">visitLibAtomicLoad</a>, <a href="#abe25be4a6081ab8cac7639e57970ec3c">visitLibAtomicStore</a> and <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a>.</p>

</div>
</div>

### getShadowOriginPtrKernel() {#a7480612cfe31fd07e5d1d5d45bf3c3b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrKernel (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ShadowTy, bool isStore)</td>
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

<p>Addr can be a ptr or &lt;N x ptr&gt;.</p>


<p>In both cases ShadowTy the shadow type of a single pointee. Returns &lt;shadow_ptr, origin_ptr&gt; or &lt;&lt;N x shadow_ptr&gt;, &lt;N x origin_ptr&gt;&gt;.</p>


<p>Definition at line 1834 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a>, <a href="#ad271462ad31f06423e02d373ce962cf1">getShadowOriginPtrKernelNoVec</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#aab5329eaa9a958adfa2c8de4d24e16cc">isStore</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>.</p>

</div>
</div>

### getShadowOriginPtrKernelNoVec() {#ad271462ad31f06423e02d373ce962cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrKernelNoVec (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ShadowTy, bool isStore)</td>
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



<p>Definition at line 1805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="#a0683904b75a4218c8915db0ec157614d">createMetadataCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#aab5329eaa9a958adfa2c8de4d24e16cc">isStore</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a7480612cfe31fd07e5d1d5d45bf3c3b4">getShadowOriginPtrKernel</a>.</p>

</div>
</div>

### getShadowOriginPtrUserspace() {#aac05ca292709f88f6ba0ae241e0e84bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Value *, Value * &gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrUserspace (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ShadowTy, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment)</td>
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

<p>Compute the shadow and origin addresses corresponding to a given application address.</p>


<p>Shadow = ShadowBase + Offset Origin = (OriginBase + Offset) &amp; ~3ULL Addr can be a ptr or &lt;N x ptr&gt;. In both cases ShadowTy the shadow type of a single pointee. Returns &lt;shadow_ptr, origin_ptr&gt; or &lt;&lt;N x shadow_ptr&gt;, &lt;N x origin_ptr&gt;&gt;.</p>


<p>Definition at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a06d139c7ee04d81813f05083f784f67b">constToIntPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="#ac784928dcbbc1b0691cc8da90970391d">getPtrToShadowPtrType</a>, <a href="#aecd57a29db63344a976ec5830496e733">getShadowPtrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="#a69a4b725eeca6669bc2adb458eb5e08f">ptrToIntPtrType</a>.</p>


<p>Referenced by <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a> and <a href="#ad5393f64ef6c65d1f090169819b68598">instrumentAsmArgument</a>.</p>

</div>
</div>

### getShadowPtrForArgument() {#aad8b252988733827abdf7bd44a8c2138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowPtrForArgument (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, int ArgOffset)</td>
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

<p>Compute the shadow address for a given function argument.</p>


<p>Shadow = ParamTLS+ArgOffset.</p>


<p>Definition at line 1879 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a> and <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>.</p>

</div>
</div>

### getShadowPtrForRetval() {#a55223c498ad94e7e49c3789aba0becce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowPtrForRetval (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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

<p>Compute the shadow address for a retval.</p>

<p>Definition at line 1897 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a> and <a href="#a357ae07ce43e35a35899d18f25ea005c">visitReturnInst</a>.</p>

</div>
</div>

### getShadowPtrOffset() {#aecd57a29db63344a976ec5830496e733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowPtrOffset (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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

<p>Returns the integer shadow offset that corresponds to a given application address, whereby:</p>



<pre><code>Offset = (Addr &amp; ~AndMask) ^ XorMask
Shadow = ShadowBase + Offset
Origin = (OriginBase + Offset) &amp; ~Alignment
</code></pre>


<p>Note: for efficiency, many shadow mappings only require use the XorMask and OriginBase; the AndMask and ShadowBase are often zero.</p>


<p>Definition at line 1737 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a06d139c7ee04d81813f05083f784f67b">constToIntPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="#a69a4b725eeca6669bc2adb458eb5e08f">ptrToIntPtrType</a>.</p>


<p>Referenced by <a href="#aac05ca292709f88f6ba0ae241e0e84bf">getShadowOriginPtrUserspace</a>.</p>

</div>
</div>

### getShadowTy() {#a5699c4e4d29dcada27c885790cab89b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowTy (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Compute the shadow type that corresponds to a given <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Reference <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>.</p>


<p>Referenced by <a href="#abfaba717423054f99dee516c7673db49">CreateAppToShadowCast</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a1d77673586722d48008ce4203b061990">getPoisonedShadow</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a03dd63ac617c1242b7694a4b0ae4ed25">getShadowTy</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="#a9890e049561cd883603c6a483547b6b5">handleArithmeticWithOverflow</a>, <a href="#a048c7023875711345d33899f3a59f3e2">handleAVXMaskedLoad</a>, <a href="#a422552f3cad093347a5f83d234925e9d">handleBmiIntrinsic</a>, <a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a>, <a href="#a0fdafd5b5245a6f5f14c41c593d10b69">handleCountZeroes</a>, <a href="#a94631928dd87cd8134a31c5fb3168c70">handleIntrinsicByApplyingToShadow</a>, <a href="#a512e6c35c0ac3187be4445bab50b766e">handleMaskedCompressStore</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a5056eaa4a9d5c87c3566577a0736c47d">handleMaskedScatter</a>, <a href="#aa78bfa47c700608c53890cc25cd44a5b">handleNEONVectorStoreIntrinsic</a>, <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>, <a href="#a2dedad065b777ac076ac9f2b3dc8c013">handleVectorComparePackedIntrinsic</a>, <a href="#a3fc06177748e14bf8ef287dc4347dde3">handleVectorCompareScalarIntrinsic</a>, <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#acaaee38930abb5a8c5d6ff71045eda30">handleVectorPackIntrinsic</a>, <a href="#a60a1bcee02000668d052f9d696ada2e9">handleVectorPmaddIntrinsic</a>, <a href="#ac03d3c26f38bacbd611de31932ef80b4">handleVectorSadIntrinsic</a>, <a href="#af1c328e6af190112474f8c694ccb59dc">handleVectorShiftIntrinsic</a>, <a href="#a27c11aacbd4098eca944c41583e759d0">handleVtestIntrinsic</a>, <a href="#a005fbd5468607e9616160e82a7665c14">visitBitCastInst</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#a0cfc49213d6647056b0e487dc90450b6">visitIntToPtrInst</a>, <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a>, <a href="#a88958577efd3c314497a72ea96c60eac">visitPHINode</a> and <a href="#ac5bb05e9c2a806f7a3c21eace99b1d7c">visitPtrToIntInst</a>.</p>

</div>
</div>

### getShadowTy() {#a03dd63ac617c1242b7694a4b0ae4ed25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowTy (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OrigTy)</td>
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

<p>Compute the shadow type that corresponds to a given <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>

<p>Definition at line 1603 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8ad67a33bae235fe3cca1c3e5a91ed2d">llvm::Type::isSized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>

</div>
</div>

### getSignedPackIntrinsic() {#ac33a8706b2108c930e0f7befe6942e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getSignedPackIntrinsic (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> id)</td>
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



<p>Definition at line 3258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#acaaee38930abb5a8c5d6ff71045eda30">handleVectorPackIntrinsic</a>.</p>

</div>
</div>

### handleAbsIntrinsic() {#a6dff8a9ea4e4cf80ae780052b6361819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleAbsIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 4012 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleArithmeticWithOverflow() {#a9890e049561cd883603c6a483547b6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleArithmeticWithOverflow (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 4029 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a20833e358e38f9a86074bb4cc72b0d14">llvm::IRBuilderBase::CreateInsertValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleAVXHorizontalAddSubIntrinsic() {#a6fbb73043c2f82e97b7a704a91f47dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleAVXHorizontalAddSubIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 4045 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a94631928dd87cd8134a31c5fb3168c70">handleIntrinsicByApplyingToShadow</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleAVXMaskedLoad() {#a048c7023875711345d33899f3a59f3e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleAVXMaskedLoad (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3850 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleAVXMaskedStore() {#abba654ce68a6aba9f7cbd731b0917877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleAVXMaskedStore (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3786 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad0243f1634f75e231041023ffaa8501a">llvm::IRBuilderBase::getVoidTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a4d9b426f332b379758b891f032f85d52">paintOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleBinarySdSsIntrinsic() {#a0bde622b06aafdb9eb49069b756563ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleBinarySdSsIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3977 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleBlendvIntrinsic() {#af57d015c7e57a42f4a73d6414d8d0453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleBlendvIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3408 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a40a1fc4e57a69c562fb3d215eaa71280">convertBlendvToSelectMask</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleBmiIntrinsic() {#a422552f3cad093347a5f83d234925e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleBmiIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3897 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleBswap() {#a2487c76cffea045469d6e95ea3a724b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleBswap (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3087 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleCASOrRMW() {#a01329a7b6a3dfa3ec5b7755e80b723f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleCASOrRMW (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 2290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#a378277a0a96b34b3b5634b8ffc865c8a">visitAtomicCmpXchgInst</a> and <a href="#ab772f88fd07120f87cd319177cea148b">visitAtomicRMWInst</a>.</p>

</div>
</div>

### handleCountZeroes() {#a0fdafd5b5245a6f5f14c41c593d10b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleCountZeroes (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3096 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aafd864f39fd28e235eea03ae424ab8e0">llvm::IRBuilderBase::CreateIsNotNull</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac9843b4f9f9cb144c608c48785a394a8">llvm::IRBuilderBase::CreateIsNull</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ad97fc23e85a854a19101bf8e861356aa">llvm::Constant::isZeroValue</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleDppIntrinsic() {#aa28fe1a3de7cc0e732f5d7ee1dc5adbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleDppIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3367 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#a51a05a00df99aa3401385eb46a6e5ae1">findDppPoisonedOutput</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleEqualityComparison() {#a823e9b0883ae72e62421714cd8bbda4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleEqualityComparison (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> &amp; I)</td>
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

<p>Instrument == and != comparisons.</p>


<p>Sometimes the comparison result is known even if some of the bits of the arguments are not.</p>


<p>Definition at line 2691 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8c75539a39f167f352b37ccdd788a7e4">llvm::IRBuilderBase::CreateICmpEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#a3175c69e435331710c2f03107ef3e8ef">visitICmpInst</a>.</p>

</div>
</div>

### handleFunnelShift() {#a04fa6c52e825a7d994a3a5eeb1cc4549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleFunnelShift (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 2858 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleIntegerDiv() {#a99029699685d64ef824bdbf6fd71754b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleIntegerDiv (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 2669 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#a9fe22967a17fc281dc3afea0bc761fa0">visitSDiv</a>, <a href="#a65251363b4be778d2a855cb6acba2666">visitSRem</a>, <a href="#a06652627b90ae944abff9433688f500c">visitUDiv</a> and <a href="#ac50b8121d06f8634d836bfe8e780b11d">visitURem</a>.</p>

</div>
</div>

### handleIntrinsicByApplyingToShadow() {#a94631928dd87cd8134a31c5fb3168c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleIntrinsicByApplyingToShadow (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> shadowIntrinsicID, unsigned int trailingVerbatimArgs)</td>
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

<p>Handle intrinsics by applying the intrinsic to the shadows.</p>


<p>The trailing arguments are passed verbatim to the intrinsic, though any uninitialized trailing arguments can also taint the shadow e.g., for an intrinsic with one trailing verbatim argument: out = intrinsic(var1, var2, opType) we compute: shadow[out] = intrinsic(shadow[var1], shadow[var2], opType) | shadow[opType]</p>


<p>Typically, shadowIntrinsicID will be specified by the caller to be I.getIntrinsicID(), but the caller can choose to replace it with another intrinsic of the same type.</p>


<p>CAUTION: this assumes that the intrinsic will handle arbitrary bit-patterns (for example, if the intrinsic accepts floats for var1, we require that it doesn't care if inputs are NaNs).</p>


<p>For example, this can be applied to the Arm NEON vector table intrinsics (tbl{1,2,3,4}).</p>


<p>The origin is approximated using setOriginForNaryOp.</p>


<p>Definition at line 4242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="#a39d5c919a484d17c9e12864d869c7f69">CreateShadowCast</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#a6fbb73043c2f82e97b7a704a91f47dc1">handleAVXHorizontalAddSubIntrinsic</a> and <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleInvariantGroup() {#a70e1c3d3c4ed3b31cb4921817214d40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleInvariantGroup (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3073 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleIsFpClass() {#ac166d600b506872ca9d2d69c7f587c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleIsFpClass (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 4022 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleLdmxcsr() {#aac621d92c3438d32c257d3e193ed64c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleLdmxcsr (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3551 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a61ccc8f79b82b8f106096534fddbdd03">InsertChecks</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleLifetimeStart() {#a0dabd1eec85a33a1d90cf9b9356a3c58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleLifetimeStart (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3078 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a21fe87bf00db76089c043fed6a23fb76">llvm::findAllocaForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a2c4b8995820e03b05d6530e8cc2c0752">InstrumentLifetimeStart</a>, <a href="#a53bb2da7b8d4e6eb90cd44d1e3556af7">LifetimeStartList</a> and <a href="#a2198d20c59c67c9de6b25fd45c9262ea">PoisonStack</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleMaskedCompressStore() {#a512e6c35c0ac3187be4445bab50b766e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMaskedCompressStore (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3605 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2001dcf6278f9e7e10b895d060d15abb">llvm::IRBuilderBase::CreateMaskedCompressStore</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleMaskedExpandLoad() {#a8cc553ff446a1ab299f2d3cd73e9a544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMaskedExpandLoad (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3572 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad878957c30eb65983e09b60edb0e1a1b">llvm::IRBuilderBase::CreateMaskedExpandLoad</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleMaskedGather() {#a759cdeca788eae085f33511a111de4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMaskedGather (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3628 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#afa922043d31aa2d3410fe0be8791b795">llvm::IRBuilderBase::CreateMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleMaskedLoad() {#a454e5d8d7e12243f5e63c713fdd488f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMaskedLoad (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3732 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a483f68557374e8fc58f8a294e7f1268e">llvm::IRBuilderBase::CreateMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7704bf68951054ffeb3efe605750e2d9">llvm::IRBuilderBase::CreateNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleMaskedScatter() {#a5056eaa4a9d5c87c3566577a0736c47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMaskedScatter (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3666 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aee07a8623893cdad858a3b5f77354375">llvm::IRBuilderBase::CreateMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleMaskedStore() {#a3405abbd1975b05777dc44d9089f1ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMaskedStore (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3698 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aad07e3e0fa03f6c780e13d924325d8d0">llvm::IRBuilderBase::CreateMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a4d9b426f332b379758b891f032f85d52">paintOrigin</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleMulByConstant() {#a1f4b3d9a1db2a863f398981ea5c1d641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMulByConstant (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * ConstArg, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OtherArg)</td>
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



<p>Definition at line 2616 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#acd530d0571f320d47d37e7ae51cf70ff">llvm::Constant::getAggregateElement</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#a58a23d4603a99873024af3b84b576c5e">visitMul</a>.</p>

</div>
</div>

### handleNEONVectorMultiplyIntrinsic() {#af56d49d9b0002920b7190ddb0f3585ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleNEONVectorMultiplyIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 4284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleNEONVectorStoreIntrinsic() {#aa78bfa47c700608c53890cc25cd44a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleNEONVectorStoreIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I, bool useLane)</td>
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

<p>Handle Arm NEON vector store intrinsics (vst{2,3,4}, vst1x_{2,3,4}, and vst{2,3,4}lane).</p>


<p>Arm NEON vector store intrinsics have the output address (pointer) as the last argument, with the initial arguments being the inputs (and lane number for vst{2,3,4}lane). They return void.</p>


<ul class="doxyList ">
<li>st4 interleaves the output e.g., st4 (inA, inB, inC, inD, outP) writes abcdabcdabcdabcd... into *outP</li>
<li>st1_x4 is non-interleaved e.g., st1_x4 (inA, inB, inC, inD, outP) writes aaaa...bbbb...cccc...dddd... into *outP</li>
<li>st4lane has arguments of (inA, inB, inC, inD, lane, outP) These instructions can all be instrumented with essentially the same MSan logic, simply by applying the corresponding intrinsic to the shadow.</li>
</ul>

<p>Definition at line 4140 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad0243f1634f75e231041023ffaa8501a">llvm::IRBuilderBase::getVoidTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handlePclmulIntrinsic() {#a924a1686eaef2f0a0ded248edc2bdb6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handlePclmulIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3929 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/combiner/#ae8b71818798cbd6a6e93e0fccbd39bfd">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::Combiner&lt; CombineShadow &gt;::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/combiner/#a554e0a120e27e722e0f2a96930041782">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::Combiner&lt; CombineShadow &gt;::Done</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a97a3c88ff7689bdb2a981cf1e8710273">getPclmulMask</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleRelationalComparisonExact() {#ac689bdce81e76d215f170f7eb3821be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleRelationalComparisonExact (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> &amp; I)</td>
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

<p>Instrument relational comparisons.</p>


<p>This function does exact shadow propagation for all relational comparisons of integers, pointers and vectors of those. FIXME: output seems suboptimal when one of the operands is a constant</p>


<p>Definition at line 2730 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#a3175c69e435331710c2f03107ef3e8ef">visitICmpInst</a>.</p>

</div>
</div>

### handleRoundPdPsIntrinsic() {#add81ddc58cfd39fc90b163af92a71bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleRoundPdPsIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3998 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleSelectLikeInst() {#a107ed4d1a9a7fc30bf59d4129235bada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleSelectLikeInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * C, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * D)</td>
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



<p>Definition at line 5176 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a>, <a href="#abfaba717423054f99dee516c7673db49">CreateAppToShadowCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#add2225af2af25968f26ed4cb0db94dbe">llvm::IRBuilderBase::CreateXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#aa8632acd057dcbe9f0d3e2de9d2f9247">getPoisonedShadow</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a> and <a href="#a09992489ef0854c6f12d58bf250db0e4">visitSelectInst</a>.</p>

</div>
</div>

### handleShadowOr() {#a1425e0956a85489ea4a81c949b952094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleShadowOr (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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

<p>Propagate shadow for arbitrary operation.</p>

<p>Definition at line 2597 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#af56d49d9b0002920b7190ddb0f3585ff">handleNEONVectorMultiplyIntrinsic</a>, <a href="#a091a19fb76439b9fff59f052e2648ee9">handleSignedRelationalComparison</a>, <a href="#a29a08f21840973827bfcca10650f0d09">visitAdd</a>, <a href="#a05f7153a6433bd6da07e4dd29a3a4717">visitFAdd</a>, <a href="#a8d47532127ac3c3ed48866788d07385b">visitFCmpInst</a>, <a href="#a2a7e1408f8587eab5d7a6795a6e51588">visitFDiv</a>, <a href="#a4af1fe1215239f5bb00b2bbe7e90b725">visitFMul</a>, <a href="#af773d6ca5d9dfe3770599c12a08b49be">visitFNeg</a>, <a href="#a2b6fa84c0a2c67733d35ecdbfbeafafe">visitFPExtInst</a>, <a href="#ab2d0de74b72099fdc4de7d7c5796ef38">visitFPToSIInst</a>, <a href="#a832b7cd0e1d0392191a2c9528448834f">visitFPToUIInst</a>, <a href="#af9a04183d7317af48f216ae837acac4d">visitFPTruncInst</a>, <a href="#a9e7a7377cca5083d3473b9aa9b0edb61">visitFRem</a>, <a href="#a8f33b0169f8f0c1322c247a869396d17">visitFSub</a>, <a href="#a8fd0cd313fa1a80f8aabf5a31cc67d34">visitGetElementPtrInst</a>, <a href="#a3175c69e435331710c2f03107ef3e8ef">visitICmpInst</a>, <a href="#a58a23d4603a99873024af3b84b576c5e">visitMul</a>, <a href="#ab0d83677a081e8f0e23fe11742d83830">visitSIToFPInst</a>, <a href="#afe140f3e1fa65182ae3bf0969027e9dd">visitSub</a>, <a href="#a517a594e0e43f88e71496ad09f1a70b1">visitUIToFPInst</a> and <a href="#a0a9601fb2a0770ca9a67ea574a1537e6">visitXor</a>.</p>

</div>
</div>

### handleShift() {#a220983874e8efc856fac602c19e9aa2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleShift (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2840 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#ae9d49d21ac59052e3d17d7fa01228325">visitAShr</a>, <a href="#aaa1fcb2e2013a57001fcc43f065bfe3d">visitLShr</a> and <a href="#a704a1fee76597843c068885f90df5aa3">visitShl</a>.</p>

</div>
</div>

### handleSignedRelationalComparison() {#a091a19fb76439b9fff59f052e2648ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleSignedRelationalComparison (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> &amp; I)</td>
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

<p>Instrument signed relational comparisons.</p>


<p>Handle sign bit tests: x&lt;0, x&gt;=0, x&lt;=-1, x&gt;-1 by propagating the highest bit of the shadow. Everything else is delegated to <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr()</a>.</p>


<p>Definition at line 2780 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac2bfef55549675e0ea117f29cd7309be">llvm::IRBuilderBase::CreateICmpSLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a662be1e66a5af621d46fa1c7a8aa1004">llvm::Constant::isAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae4b6abe77abf42fb02081a6cc41a0132">llvm::Constant::isNullValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#a3175c69e435331710c2f03107ef3e8ef">visitICmpInst</a>.</p>

</div>
</div>

### handleStmxcsr() {#a7a310b77dacdbac9c6bfd285af705de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleStmxcsr (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3538 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleUnarySdSsIntrinsic() {#aef9ab401ce01af2ea722f41cfb8e4943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleUnarySdSsIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3947 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleUnknownIntrinsic() {#a077e9376af4a6c07ade5704887b2fd49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleUnknownIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3061 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a6b56dfb9e6691acfd25fd5d3901bc17c">ClDumpStrictIntrinsics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#accd1cfbd692f327894828f50c24ad3b6">dumpInst</a>, <a href="#ac5f6e0279d635bf21ceda6349d4afa02">handleUnknownIntrinsicUnlogged</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleUnknownIntrinsicUnlogged() {#ac5f6e0279d635bf21ceda6349d4afa02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleUnknownIntrinsicUnlogged (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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

<p>Heuristically instrument unknown intrinsics.</p>


<p>The main purpose of this code is to do something reasonable with all random intrinsics we might encounter, most importantly - SIMD intrinsics. We recognize several classes of intrinsics by their argument types and ModRefBehaviour and apply special instrumentation when we are reasonably sure that we know what the intrinsic does.</p>


<p>We special-case intrinsics where this approach fails. See llvm.bswap handling as an example of that.</p>


<p>Definition at line 3034 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#aa386f90ca7b1b24989ce41d70a0ce052">handleVectorStoreIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a9c9266376e710920a1bd7999ed9c8963">maybeHandleSimpleNomemIntrinsic</a>.</p>


<p>Referenced by <a href="#a077e9376af4a6c07ade5704887b2fd49">handleUnknownIntrinsic</a>.</p>

</div>
</div>

### handleVectorComparePackedIntrinsic() {#a2dedad065b777ac076ac9f2b3dc8c013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorComparePackedIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3469 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorCompareScalarIntrinsic() {#a3fc06177748e14bf8ef287dc4347dde3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorCompareScalarIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3484 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a174a52b2885896fbf86e1250573168dc">LowerElementShadowExtend</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorConvertIntrinsic() {#a8ec2e744dff018b81c0eb2a7e9ea4e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorConvertIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I, int NumUsedElements, bool HasRoundingMode=false)</td>
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



<p>Definition at line 3132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorLoadIntrinsic() {#a0215817db88ff4446c80bf413c754c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorLoadIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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

<p>Handle vector load-like intrinsics.</p>


<p>Instrument intrinsics that look like a simple SIMD load: reads memory, has 1 pointer argument, returns a vector.</p>


<p>Definition at line 2960 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#ac5f6e0279d635bf21ceda6349d4afa02">handleUnknownIntrinsicUnlogged</a>.</p>

</div>
</div>

### handleVectorPackIntrinsic() {#acaaee38930abb5a8c5d6ff71045eda30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorPackIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I, unsigned MMXEltSizeInBits=0)</td>
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



<p>Definition at line 3294 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#abe3f2bc12df17a7c061c315f7bfcf12e">getMMXVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="#ac33a8706b2108c930e0f7befe6942e29">getSignedPackIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorPmaddIntrinsic() {#a60a1bcee02000668d052f9d696ada2e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorPmaddIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I, unsigned MMXEltSizeInBits=0)</td>
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



<p>Definition at line 3450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#abe3f2bc12df17a7c061c315f7bfcf12e">getMMXVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorReduceAndIntrinsic() {#a8abeeb6d127be621e8ee8d9d667503b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorReduceAndIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3524 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3cfdb164300aa232622852961a2eb7b5">llvm::IRBuilderBase::CreateAndReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a784d99f22cf1632638a2fa652e7723d1">llvm::IRBuilderBase::CreateOrReduce</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorReduceIntrinsic() {#a14778d7f19c6c8582a65cb2d05b541ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorReduceIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3496 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a784d99f22cf1632638a2fa652e7723d1">llvm::IRBuilderBase::CreateOrReduce</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorReduceOrIntrinsic() {#ae160aa4ec35fca7aaa0f75a8526cb3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorReduceOrIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3cfdb164300aa232622852961a2eb7b5">llvm::IRBuilderBase::CreateAndReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a784d99f22cf1632638a2fa652e7723d1">llvm::IRBuilderBase::CreateOrReduce</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorSadIntrinsic() {#ac03d3c26f38bacbd611de31932ef80b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorSadIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I, bool IsMMX=false)</td>
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



<p>Definition at line 3430 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorShiftIntrinsic() {#af1c328e6af190112474f8c694ccb59dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorShiftIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I, bool Variable)</td>
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



<p>Definition at line 3229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a160d793aacc4ffadcdf86eddbf401c69">Lower64ShadowExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a>, <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a> and <a href="#a02e1c458e5c141b448867b728af11ae9">VariableShadowExtend</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### handleVectorStoreIntrinsic() {#aa386f90ca7b1b24989ce41d70a0ce052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorStoreIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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

<p>Handle vector store-like intrinsics.</p>


<p>Instrument intrinsics that look like a simple SIMD store: writes memory, has 1 pointer argument and 1 vector argument, returns void.</p>


<p>Definition at line 2935 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#ac5f6e0279d635bf21ceda6349d4afa02">handleUnknownIntrinsicUnlogged</a>.</p>

</div>
</div>

### handleVtestIntrinsic() {#a27c11aacbd4098eca944c41583e759d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVtestIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 3964 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### insertKmsanPrologue() {#ad4fd8682f807900cbed932926bceb717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::insertKmsanPrologue (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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



<p>Definition at line 1526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af0a491fddfa0a73d2b9074b587ca337f">llvm::Triple::systemz</a>.</p>


<p>Referenced by <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a>.</p>

</div>
</div>

### insertShadowCheck() {#af6968bc7c8e7e0d6b3fcddb5a934a3c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::insertShadowCheck (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * OrigIns)</td>
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

<p>Remember the place where a shadow check should be inserted.</p>


<p>This location will be later instrumented with a check that will print a UMR warning in runtime if the shadow value is not 0.</p>


<p>Definition at line 2113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a61ccc8f79b82b8f106096534fddbdd03">InsertChecks</a>, <a href="#a46f569d5ad463a4c719f0e8d4d9d5ae8">InstrumentationList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a5aace8653ce3726ef07194dcf6bce2bf">llvm::DebugCounter::shouldExecute</a>.</p>


<p>Referenced by <a href="#a048c7023875711345d33899f3a59f3e2">handleAVXMaskedLoad</a>, <a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a>, <a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a>, <a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a>, <a href="#aac621d92c3438d32c257d3e193ed64c2">handleLdmxcsr</a>, <a href="#a512e6c35c0ac3187be4445bab50b766e">handleMaskedCompressStore</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a5056eaa4a9d5c87c3566577a0736c47d">handleMaskedScatter</a>, <a href="#a3405abbd1975b05777dc44d9089f1ece">handleMaskedStore</a>, <a href="#aa78bfa47c700608c53890cc25cd44a5b">handleNEONVectorStoreIntrinsic</a>, <a href="#a7a310b77dacdbac9c6bfd285af705de5">handleStmxcsr</a>, <a href="#a8ec2e744dff018b81c0eb2a7e9ea4e2b">handleVectorConvertIntrinsic</a>, <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#aa386f90ca7b1b24989ce41d70a0ce052">handleVectorStoreIntrinsic</a>, <a href="#acf3df1ea61f4ce9ffc1c31eebcadc1bc">insertShadowCheck</a>, <a href="#ad5393f64ef6c65d1f090169819b68598">instrumentAsmArgument</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#af4a162e1f6cd54269b8c906eb54ee6fb">visitExtractElementInst</a>, <a href="#afbe4a56f60e1964a3e0ce781600334de">visitInsertElementInst</a>, <a href="#a232a0fe878bb0a5a47219195daadca39">visitInstruction</a>, <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a>, <a href="#a357ae07ce43e35a35899d18f25ea005c">visitReturnInst</a> and <a href="#a1dad5091fba05972dc72b125bf3be373">visitStoreInst</a>.</p>

</div>
</div>

### insertShadowCheck() {#acf3df1ea61f4ce9ffc1c31eebcadc1bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::insertShadowCheck (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * OrigIns)</td>
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

<p>Remember the place where a shadow check should be inserted.</p>


<p>This location will be later instrumented with a check that will print a UMR warning in runtime if the value is not fully defined.</p>


<p>Definition at line 2138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a2622ac4e4855b9e0339799760c8e08e7">ClCheckConstantShadow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a> and <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>.</p>

</div>
</div>

### insertWarningFn() {#a9f4e542bdcac1a2ab15b6e55991f07c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::insertWarningFn (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin)</td>
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

<p>Helper function to insert a warning at IRB's current insert point.</p>

<p>Definition at line 1388 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a90a3242eeb2a7d1afbb5ab5bc5bfb20d">llvm::IRBuilderBase::getCurrentDebugLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a6da7de997f92fdb5d3e85f4f5b9af20e">llvm::CallBase::setCannotMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>, <a href="#ac02a2e35e2ad7efcce4dace2ac96a3a6">shouldDisambiguateWarningLocation</a> and <a href="#ab630c4065f79030c5d9c17998be71fd3">updateOrigin</a>.</p>


<p>Referenced by <a href="#a0efb7aefc1fd76a565c2ced7d2ff14cb">materializeInstructionChecks</a> and <a href="#a2a6b95606a7aa4afbc8a38114dd8da82">materializeOneCheck</a>.</p>

</div>
</div>

### instrumentAlloca() {#acd39b18dfd59223eea65852ed04b338e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::instrumentAlloca (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsPoint=nullptr)</td>
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



<p>Definition at line 5142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a55086d93549de64322f4d3e8f5dd4883">llvm::IRBuilderBase::CreateTypeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a36742c35a8fff5f74bb3d76c9c19dd47">llvm::IRBuilderBase::CreateZExtOrTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a36a965b050969c112696e764545b231e">poisonAllocaKmsan</a> and <a href="#a00e8c5cbc0a9f0269b50f08a187c2f78">poisonAllocaUserspace</a>.</p>


<p>Referenced by <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>.</p>

</div>
</div>

### instrumentAsmArgument() {#ad5393f64ef6c65d1f090169819b68598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::instrumentAsmArgument (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Operand, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, bool isOutput)</td>
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



<p>Definition at line 5291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4910aab8d7c5528c1a3ac747856c3186">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a55086d93549de64322f4d3e8f5dd4883">llvm::IRBuilderBase::CreateTypeSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#aac05ca292709f88f6ba0ae241e0e84bf">getShadowOriginPtrUserspace</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a27c9f05f074b1acd44859e85c1212bc1">visitAsmInstruction</a>.</p>

</div>
</div>

### instrumentWithCalls() {#a0974eac64f313142c02ae973aca6359e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::instrumentWithCalls (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 1222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a562f393ed86818bc632731f717a91b36">ClInstrumentationWithCallThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a6041f8f61469e7649e9f9ad33a5be8b6">SplittableBlocksCount</a>.</p>


<p>Referenced by <a href="#a2a6b95606a7aa4afbc8a38114dd8da82">materializeOneCheck</a> and <a href="#a00c704ed1965bd5d0348f156a8e33506">storeOrigin</a>.</p>

</div>
</div>

### isAMustTailRetVal() {#ad1444d314e49ffb031f0abd54b3b7ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::isAMustTailRetVal (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RetVal)</td>
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



<p>Definition at line 5039 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isInPrologue() {#afc7b613059ab8f04e165d430bb736bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::isInPrologue (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 1232 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a4feeefbf4ec513bf876399ce4b84aad1">FnPrologueEnd</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a78793329d41f7e0ff3ab15f71b2f952c">visit</a>.</p>

</div>
</div>

### Lower64ShadowExtend() {#a160d793aacc4ffadcdf86eddbf401c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::Lower64ShadowExtend (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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



<p>Definition at line 3199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="#a39d5c919a484d17c9e12864d869c7f69">CreateShadowCast</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>


<p>Referenced by <a href="#af1c328e6af190112474f8c694ccb59dc">handleVectorShiftIntrinsic</a>.</p>

</div>
</div>

### LowerElementShadowExtend() {#a174a52b2885896fbf86e1250573168dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::LowerElementShadowExtend (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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



<p>Definition at line 3209 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="#a39d5c919a484d17c9e12864d869c7f69">CreateShadowCast</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>.</p>


<p>Referenced by <a href="#a3fc06177748e14bf8ef287dc4347dde3">handleVectorCompareScalarIntrinsic</a>.</p>

</div>
</div>

### makeAddAcquireOrderingTable() {#a62bf64531735d133d60ced4e7a4d4e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::makeAddAcquireOrderingTable (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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



<p>Definition at line 2206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af3e0f4fa6020c4a1b19d21f32f42020c">llvm::acq_rel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a86a4fa105ff51b8c3be84734797d8144">llvm::acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af0ef8c72418989a4bb20243ccb61eeb0">llvm::consume</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ab8b693ee2fbb4c4173fa2725c110021b">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a81f32be24a2a62fc472cc43edc97e65b">llvm::relaxed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a14cede869a7aee57588ab47066432604">llvm::seq_cst</a>.</p>


<p>Referenced by <a href="#a9b2c0b28c3d1ee4253d2aae4f9172d94">visitLibAtomicLoad</a>.</p>

</div>
</div>

### makeAddReleaseOrderingTable() {#a9ecfbb98ae6069aa910e8aba30aca1d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::makeAddReleaseOrderingTable (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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



<p>Definition at line 2172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af3e0f4fa6020c4a1b19d21f32f42020c">llvm::acq_rel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a86a4fa105ff51b8c3be84734797d8144">llvm::acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9af0ef8c72418989a4bb20243ccb61eeb0">llvm::consume</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ab8b693ee2fbb4c4173fa2725c110021b">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a81f32be24a2a62fc472cc43edc97e65b">llvm::relaxed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a14cede869a7aee57588ab47066432604">llvm::seq_cst</a>.</p>


<p>Referenced by <a href="#abe25be4a6081ab8cac7639e57970ec3c">visitLibAtomicStore</a>.</p>

</div>
</div>

### materializeChecks() {#a0f56283bd67f32b385c705520aabb932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::materializeChecks ()</td>
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



<p>Definition at line 1501 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a46f569d5ad463a4c719f0e8d4d9d5ae8">InstrumentationList</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a0efb7aefc1fd76a565c2ced7d2ff14cb">materializeInstructionChecks</a>.</p>


<p>Referenced by <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>.</p>

</div>
</div>

### materializeInstructionChecks() {#a0efb7aefc1fd76a565c2ced7d2ff14cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::materializeInstructionChecks (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/shadoworiginandinsertpoint">ShadowOriginAndInsertPoint</a> &gt; InstructionChecks)</td>
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



<p>Definition at line 1449 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a2622ac4e4855b9e0339799760c8e08e7">ClCheckConstantShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp/#ab582deb65d0ec7f41efa6d8579daf0e1">Combine</a>, <a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="#a9f4e542bdcac1a2ab15b6e55991f07c8">insertWarningFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="#a2a6b95606a7aa4afbc8a38114dd8da82">materializeOneCheck</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a0f56283bd67f32b385c705520aabb932">materializeChecks</a>.</p>

</div>
</div>

### materializeOneCheck() {#a2a6b95606a7aa4afbc8a38114dd8da82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::materializeOneCheck (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ConvertedShadow, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin)</td>
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



<p>Definition at line 1420 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>, <a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a9f4e542bdcac1a2ab15b6e55991f07c8">insertWarningFn</a>, <a href="#a0974eac64f313142c02ae973aca6359e">instrumentWithCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aa62a4d0672bab180dd339cda25b23b2e">kNumberOfAccessSizes</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#a0cf7e80624365372e769be7d6c04d74b">TypeSizeToSizeIndex</a>.</p>


<p>Referenced by <a href="#a0efb7aefc1fd76a565c2ced7d2ff14cb">materializeInstructionChecks</a>.</p>

</div>
</div>

### materializeStores() {#a09cbf4fc467ebb29733bdb77d74e7d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::materializeStores ()</td>
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



<p>Definition at line 1349 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a7886b01e9761c33d2235cda57744417d">addReleaseOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a1e17cdef6be3fbe65c97bed1a437f040">StoreList</a> and <a href="#a00c704ed1965bd5d0348f156a8e33506">storeOrigin</a>.</p>


<p>Referenced by <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>.</p>

</div>
</div>

### maybeHandleSimpleNomemIntrinsic() {#a9c9266376e710920a1bd7999ed9c8963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::maybeHandleSimpleNomemIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I, unsigned int trailingFlags)</td>
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

<p>Handle (SIMD arithmetic)-like intrinsics.</p>


<p>Instrument intrinsics with any number of arguments of the same type [*], equal to the return type, plus a specified number of trailing flags of any type.</p>


<p>[*] The type should be simple (no aggregates or pointers; vectors are fine).</p>


<p>Caller guarantees that this intrinsic does not access memory.</p>


<p>Definition at line 3001 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad0709baa705ae62c4e09cdd47fb4b420">llvm::Type::isFPOrFPVectorTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>.</p>


<p>Referenced by <a href="#ac5f6e0279d635bf21ceda6349d4afa02">handleUnknownIntrinsicUnlogged</a> and <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### originToIntptr() {#a045f288bf4edf0fe84985782706d4bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::originToIntptr (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin)</td>
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



<p>Definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a454da6b23d63f4bb778f6249cc427b91">kOriginSize</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a4d9b426f332b379758b891f032f85d52">paintOrigin</a>.</p>

</div>
</div>

### paintOrigin() {#a4d9b426f332b379758b891f032f85d52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::paintOrigin (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OriginPtr, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> TS, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Fill memory range with the given origin value.</p>

<p>Definition at line 1258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1ac3f0b68c9c78c4f9e1eb09cd415db8">llvm::IRBuilderBase::CreateConstGEP1_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a55086d93549de64322f4d3e8f5dd4883">llvm::IRBuilderBase::CreateTypeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6b68047eda0d6d6eec5dd564ed1a22b8">llvm::IRBuilderBase::CreateUDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a454da6b23d63f4bb778f6249cc427b91">kOriginSize</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a045f288bf4edf0fe84985782706d4bb9">originToIntptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a32aaa22eb69c944393cd5a1c79fa0d35">llvm::SplitBlockAndInsertSimpleForLoop</a>.</p>


<p>Referenced by <a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a>, <a href="#a3405abbd1975b05777dc44d9089f1ece">handleMaskedStore</a> and <a href="#a00c704ed1965bd5d0348f156a8e33506">storeOrigin</a>.</p>

</div>
</div>

### poisonAllocaKmsan() {#a36a965b050969c112696e764545b231e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::poisonAllocaKmsan (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Len)</td>
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



<p>Definition at line 5133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="#a9d656b8ad508d9b36144ca1db4f95181">getLocalVarDescription</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="#a2198d20c59c67c9de6b25fd45c9262ea">PoisonStack</a>.</p>


<p>Referenced by <a href="#acd39b18dfd59223eea65852ed04b338e">instrumentAlloca</a>.</p>

</div>
</div>

### poisonAllocaUserspace() {#a00e8c5cbc0a9f0269b50f08a187c2f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::poisonAllocaUserspace (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Len)</td>
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



<p>Definition at line 5109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a56b93a7be228ba661a04962a9cef6c2a">ClPoisonStackPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#aedbb53489a0b0283aa6f1065bdc05004">ClPoisonStackWithCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a8d4d3c3c5a9ce85cd41923e734b24b2f">ClPrintStackNames</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4910aab8d7c5528c1a3ac747856c3186">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5ace7032cfd291cb3fb5d9338386760b">llvm::IRBuilderBase::getInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="#a9d656b8ad508d9b36144ca1db4f95181">getLocalVarDescription</a>, <a href="#a0fd41cd05155ed81f0ac16e8a478b860">getLocalVarIdptr</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="#a2198d20c59c67c9de6b25fd45c9262ea">PoisonStack</a>.</p>


<p>Referenced by <a href="#acd39b18dfd59223eea65852ed04b338e">instrumentAlloca</a>.</p>

</div>
</div>

### ptrToIntPtrType() {#a69a4b725eeca6669bc2adb458eb5e08f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::ptrToIntPtrType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * PtrTy)</td>
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



<p>Definition at line 1699 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#abf313eff420b7c6c8e322a2e9c53cd90">llvm::Type::isIntOrPtrTy</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="#a69a4b725eeca6669bc2adb458eb5e08f">ptrToIntPtrType</a>.</p>


<p>Referenced by <a href="#aac05ca292709f88f6ba0ae241e0e84bf">getShadowOriginPtrUserspace</a>, <a href="#aecd57a29db63344a976ec5830496e733">getShadowPtrOffset</a> and <a href="#a69a4b725eeca6669bc2adb458eb5e08f">ptrToIntPtrType</a>.</p>

</div>
</div>

### runOnFunction() {#a8605e39e73fa355574fd811094481af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::runOnFunction ()</td>
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

<p>Add <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/memorysanitizer">MemorySanitizer</a> instrumentation to a function.</p>

<p>Definition at line 1550 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="#a620d735c5fea0163960071e5a3e99a4a">AllocaSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="#a4feeefbf4ec513bf876399ce4b84aad1">FnPrologueEnd</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa6f4541cb285cd7d00759c8ffddf9f69">Instructions</a>, <a href="#acd39b18dfd59223eea65852ed04b338e">instrumentAlloca</a>, <a href="#a2c4b8995820e03b05d6530e8cc2c0752">InstrumentLifetimeStart</a>, <a href="#a53bb2da7b8d4e6eb90cd44d1e3556af7">LifetimeStartList</a>, <a href="#a0f56283bd67f32b385c705520aabb932">materializeChecks</a>, <a href="#a09cbf4fc467ebb29733bdb77d74e7d07">materializeStores</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a5287beec429ac02e5db213256dcd8776">ShadowPHINodes</a>, <a href="#a57aec2acd87151c727180e766c8f4dab">VAHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#a6352e72d11377a9c62f24434ae869bf0">llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a>.</p>

</div>
</div>

### setOrigin() {#a0e79f9f6217e29c2a32e0cb77ce33ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::setOrigin (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin)</td>
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

<p>Set Origin to be the origin value for V.</p>

<p>Definition at line 1914 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a> and <a href="#a1d20d8cd675fe8f162888d38bcc0ea99">OriginMap</a>.</p>


<p>Referenced by <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a6dff8a9ea4e4cf80ae780052b6361819">handleAbsIntrinsic</a>, <a href="#a048c7023875711345d33899f3a59f3e2">handleAVXMaskedLoad</a>, <a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a>, <a href="#a2487c76cffea045469d6e95ea3a724b0">handleBswap</a>, <a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a>, <a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a>, <a href="#a70e1c3d3c4ed3b31cb4921817214d40b">handleInvariantGroup</a>, <a href="#ac166d600b506872ca9d2d69c7f587c2d">handleIsFpClass</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a1f4b3d9a1db2a863f398981ea5c1d641">handleMulByConstant</a>, <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>, <a href="#a091a19fb76439b9fff59f052e2648ee9">handleSignedRelationalComparison</a>, <a href="#a8ec2e744dff018b81c0eb2a7e9ea4e2b">handleVectorConvertIntrinsic</a>, <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#a8abeeb6d127be621e8ee8d9d667503b2">handleVectorReduceAndIntrinsic</a>, <a href="#a14778d7f19c6c8582a65cb2d05b541ce">handleVectorReduceIntrinsic</a>, <a href="#ae160aa4ec35fca7aaa0f75a8526cb3fb">handleVectorReduceOrIntrinsic</a>, <a href="#a78793329d41f7e0ff3ab15f71b2f952c">visit</a>, <a href="#ad360018df823d021f17fd6612acecacf">visitAllocaInst</a>, <a href="#a27c9f05f074b1acd44859e85c1212bc1">visitAsmInstruction</a>, <a href="#a005fbd5468607e9616160e82a7665c14">visitBitCastInst</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#acc330182e6404dbe33f4a58f24ee722c">visitCatchSwitchInst</a>, <a href="#af4a162e1f6cd54269b8c906eb54ee6fb">visitExtractElementInst</a>, <a href="#a80a03aae53393e1535618f885dd8e113">visitFreezeInst</a>, <a href="#af47d161cc73a6bddb356cc121c66322a">visitFuncletPadInst</a>, <a href="#a232a0fe878bb0a5a47219195daadca39">visitInstruction</a>, <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>, <a href="#a0cfc49213d6647056b0e487dc90450b6">visitIntToPtrInst</a>, <a href="#a54ebff796e583fc774c4b7ddd669735b">visitLandingPadInst</a>, <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a>, <a href="#a88958577efd3c314497a72ea96c60eac">visitPHINode</a>, <a href="#ac5bb05e9c2a806f7a3c21eace99b1d7c">visitPtrToIntInst</a>, <a href="#a22f2a1b9c4998624686b30ca88c98668">visitSExtInst</a>, <a href="#a3d1d4c8c600e51aaa27f230e05e3d553">visitTruncInst</a> and <a href="#aab6035ac9679b9449d97646f9c16d135">visitZExtInst</a>.</p>

</div>
</div>

### setOriginForNaryOp() {#ad27037edeacf67c4b3583aee7122ade2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::setOriginForNaryOp (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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

<p>Propagate origin for arbitrary operation.</p>

<p>Definition at line 2542 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a9890e049561cd883603c6a483547b6b5">handleArithmeticWithOverflow</a>, <a href="#a0bde622b06aafdb9eb49069b756563ce">handleBinarySdSsIntrinsic</a>, <a href="#a422552f3cad093347a5f83d234925e9d">handleBmiIntrinsic</a>, <a href="#a0fdafd5b5245a6f5f14c41c593d10b69">handleCountZeroes</a>, <a href="#aa28fe1a3de7cc0e732f5d7ee1dc5adbd">handleDppIntrinsic</a>, <a href="#a823e9b0883ae72e62421714cd8bbda4c">handleEqualityComparison</a>, <a href="#a04fa6c52e825a7d994a3a5eeb1cc4549">handleFunnelShift</a>, <a href="#a94631928dd87cd8134a31c5fb3168c70">handleIntrinsicByApplyingToShadow</a>, <a href="#ac689bdce81e76d215f170f7eb3821be3">handleRelationalComparisonExact</a>, <a href="#a220983874e8efc856fac602c19e9aa2b">handleShift</a>, <a href="#aef9ab401ce01af2ea722f41cfb8e4943">handleUnarySdSsIntrinsic</a>, <a href="#a2dedad065b777ac076ac9f2b3dc8c013">handleVectorComparePackedIntrinsic</a>, <a href="#a3fc06177748e14bf8ef287dc4347dde3">handleVectorCompareScalarIntrinsic</a>, <a href="#acaaee38930abb5a8c5d6ff71045eda30">handleVectorPackIntrinsic</a>, <a href="#a60a1bcee02000668d052f9d696ada2e9">handleVectorPmaddIntrinsic</a>, <a href="#ac03d3c26f38bacbd611de31932ef80b4">handleVectorSadIntrinsic</a>, <a href="#af1c328e6af190112474f8c694ccb59dc">handleVectorShiftIntrinsic</a>, <a href="#a27c11aacbd4098eca944c41583e759d0">handleVtestIntrinsic</a>, <a href="#af4ed8c796cc564c14664505603f6aac1">visitAnd</a>, <a href="#a47a02eeff88a7467b6a84a310b3e9eee">visitExtractValueInst</a>, <a href="#afbe4a56f60e1964a3e0ce781600334de">visitInsertElementInst</a>, <a href="#aead566fef3a7ebeb14cd72efb473079a">visitInsertValueInst</a>, <a href="#a684df7f760d6dcbfea36c5bccb2cfccd">visitOr</a> and <a href="#a464dafaad1c67c6d167dd70c6326dde9">visitShuffleVectorInst</a>.</p>

</div>
</div>

### setShadow() {#aa479d62de65c7074b376392e3a34d0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::setShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SV)</td>
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

<p>Set SV to be the shadow value for V.</p>

<p>Definition at line 1908 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a> and <a href="#af72ba6bf0adbad0f1134ed2e8a62b318">ShadowMap</a>.</p>


<p>Referenced by <a href="#a6dff8a9ea4e4cf80ae780052b6361819">handleAbsIntrinsic</a>, <a href="#a9890e049561cd883603c6a483547b6b5">handleArithmeticWithOverflow</a>, <a href="#a048c7023875711345d33899f3a59f3e2">handleAVXMaskedLoad</a>, <a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a>, <a href="#a0bde622b06aafdb9eb49069b756563ce">handleBinarySdSsIntrinsic</a>, <a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a>, <a href="#a422552f3cad093347a5f83d234925e9d">handleBmiIntrinsic</a>, <a href="#a2487c76cffea045469d6e95ea3a724b0">handleBswap</a>, <a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a>, <a href="#a0fdafd5b5245a6f5f14c41c593d10b69">handleCountZeroes</a>, <a href="#aa28fe1a3de7cc0e732f5d7ee1dc5adbd">handleDppIntrinsic</a>, <a href="#a823e9b0883ae72e62421714cd8bbda4c">handleEqualityComparison</a>, <a href="#a04fa6c52e825a7d994a3a5eeb1cc4549">handleFunnelShift</a>, <a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a>, <a href="#a94631928dd87cd8134a31c5fb3168c70">handleIntrinsicByApplyingToShadow</a>, <a href="#a70e1c3d3c4ed3b31cb4921817214d40b">handleInvariantGroup</a>, <a href="#ac166d600b506872ca9d2d69c7f587c2d">handleIsFpClass</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a1f4b3d9a1db2a863f398981ea5c1d641">handleMulByConstant</a>, <a href="#aa78bfa47c700608c53890cc25cd44a5b">handleNEONVectorStoreIntrinsic</a>, <a href="#ac689bdce81e76d215f170f7eb3821be3">handleRelationalComparisonExact</a>, <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>, <a href="#a220983874e8efc856fac602c19e9aa2b">handleShift</a>, <a href="#a091a19fb76439b9fff59f052e2648ee9">handleSignedRelationalComparison</a>, <a href="#aef9ab401ce01af2ea722f41cfb8e4943">handleUnarySdSsIntrinsic</a>, <a href="#a2dedad065b777ac076ac9f2b3dc8c013">handleVectorComparePackedIntrinsic</a>, <a href="#a3fc06177748e14bf8ef287dc4347dde3">handleVectorCompareScalarIntrinsic</a>, <a href="#a8ec2e744dff018b81c0eb2a7e9ea4e2b">handleVectorConvertIntrinsic</a>, <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#acaaee38930abb5a8c5d6ff71045eda30">handleVectorPackIntrinsic</a>, <a href="#a60a1bcee02000668d052f9d696ada2e9">handleVectorPmaddIntrinsic</a>, <a href="#a8abeeb6d127be621e8ee8d9d667503b2">handleVectorReduceAndIntrinsic</a>, <a href="#a14778d7f19c6c8582a65cb2d05b541ce">handleVectorReduceIntrinsic</a>, <a href="#ae160aa4ec35fca7aaa0f75a8526cb3fb">handleVectorReduceOrIntrinsic</a>, <a href="#ac03d3c26f38bacbd611de31932ef80b4">handleVectorSadIntrinsic</a>, <a href="#af1c328e6af190112474f8c694ccb59dc">handleVectorShiftIntrinsic</a>, <a href="#a27c11aacbd4098eca944c41583e759d0">handleVtestIntrinsic</a>, <a href="#a78793329d41f7e0ff3ab15f71b2f952c">visit</a>, <a href="#ad360018df823d021f17fd6612acecacf">visitAllocaInst</a>, <a href="#af4ed8c796cc564c14664505603f6aac1">visitAnd</a>, <a href="#a27c9f05f074b1acd44859e85c1212bc1">visitAsmInstruction</a>, <a href="#a005fbd5468607e9616160e82a7665c14">visitBitCastInst</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#acc330182e6404dbe33f4a58f24ee722c">visitCatchSwitchInst</a>, <a href="#af4a162e1f6cd54269b8c906eb54ee6fb">visitExtractElementInst</a>, <a href="#a47a02eeff88a7467b6a84a310b3e9eee">visitExtractValueInst</a>, <a href="#a80a03aae53393e1535618f885dd8e113">visitFreezeInst</a>, <a href="#af47d161cc73a6bddb356cc121c66322a">visitFuncletPadInst</a>, <a href="#afbe4a56f60e1964a3e0ce781600334de">visitInsertElementInst</a>, <a href="#aead566fef3a7ebeb14cd72efb473079a">visitInsertValueInst</a>, <a href="#a232a0fe878bb0a5a47219195daadca39">visitInstruction</a>, <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>, <a href="#a0cfc49213d6647056b0e487dc90450b6">visitIntToPtrInst</a>, <a href="#a54ebff796e583fc774c4b7ddd669735b">visitLandingPadInst</a>, <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a>, <a href="#a684df7f760d6dcbfea36c5bccb2cfccd">visitOr</a>, <a href="#a88958577efd3c314497a72ea96c60eac">visitPHINode</a>, <a href="#ac5bb05e9c2a806f7a3c21eace99b1d7c">visitPtrToIntInst</a>, <a href="#a22f2a1b9c4998624686b30ca88c98668">visitSExtInst</a>, <a href="#a464dafaad1c67c6d167dd70c6326dde9">visitShuffleVectorInst</a>, <a href="#a3d1d4c8c600e51aaa27f230e05e3d553">visitTruncInst</a> and <a href="#aab6035ac9679b9449d97646f9c16d135">visitZExtInst</a>.</p>

</div>
</div>

### shouldDisambiguateWarningLocation() {#ac02a2e35e2ad7efcce4dace2ac96a3a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::shouldDisambiguateWarningLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DebugLoc)</td>
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



<p>Definition at line 1376 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#ab6bfda65820457c2a529896cc101e444">ClDisambiguateWarning</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a46f569d5ad463a4c719f0e8d4d9d5ae8">InstrumentationList</a>, <a href="#a0f7bf4d0adbe765573bbbbbc89ddd626">LazyWarningDebugLocationCount</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a9f4e542bdcac1a2ab15b6e55991f07c8">insertWarningFn</a>.</p>

</div>
</div>

### storeOrigin() {#a00c704ed1965bd5d0348f156a8e33506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::storeOrigin (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Origin, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OriginPtr, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Definition at line 1307 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae5d05ec2b9a60806746addff3f2a71a9">llvm::CallBase::addParamAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a2622ac4e4855b9e0339799760c8e08e7">ClCheckConstantShadow</a>, <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>, <a href="#a6c2f0057515e3f4b8e14cfb9dcb789ae">convertToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a0974eac64f313142c02ae973aca6359e">instrumentWithCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aa62a4d0672bab180dd339cda25b23b2e">kNumberOfAccessSizes</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a4d9b426f332b379758b891f032f85d52">paintOrigin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#a0cf7e80624365372e769be7d6c04d74b">TypeSizeToSizeIndex</a> and <a href="#ab630c4065f79030c5d9c17998be71fd3">updateOrigin</a>.</p>


<p>Referenced by <a href="#a09cbf4fc467ebb29733bdb77d74e7d07">materializeStores</a>.</p>

</div>
</div>

### updateOrigin() {#ab630c4065f79030c5d9c17998be71fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::updateOrigin (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
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



<p>Definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>


<p>Referenced by <a href="#a9f4e542bdcac1a2ab15b6e55991f07c8">insertWarningFn</a>, <a href="#a00c704ed1965bd5d0348f156a8e33506">storeOrigin</a> and <a href="#a9b2c0b28c3d1ee4253d2aae4f9172d94">visitLibAtomicLoad</a>.</p>

</div>
</div>

### VariableShadowExtend() {#a02e1c458e5c141b448867b728af11ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::VariableShadowExtend (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S)</td>
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



<p>Definition at line 3215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#af1c328e6af190112474f8c694ccb59dc">handleVectorShiftIntrinsic</a>.</p>

</div>
</div>

### VectorOrPrimitiveTypeSizeInBits() {#a52481b174cfe6444a5ae320b20c5bef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::VectorOrPrimitiveTypeSizeInBits (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 2552 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="#a39d5c919a484d17c9e12864d869c7f69">CreateShadowCast</a>.</p>

</div>
</div>

### visit() {#a78793329d41f7e0ff3ab15f71b2f952c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visit (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 2225 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa6f4541cb285cd7d00759c8ffddf9f69">Instructions</a>, <a href="#afc7b613059ab8f04e165d430bb736bba">isInPrologue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a>, <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a> and <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a5aace8653ce3726ef07194dcf6bce2bf">llvm::DebugCounter::shouldExecute</a>.</p>

</div>
</div>

### visitAdd() {#a29a08f21840973827bfcca10650f0d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAdd (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2665 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitAllocaInst() {#ad360018df823d021f17fd6612acecacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAllocaInst (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I)</td>
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



<p>Definition at line 5159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a620d735c5fea0163960071e5a3e99a4a">AllocaSet</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitAnd() {#af4ed8c796cc564c14664505603f6aac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAnd (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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

<p>Propagate shadow for bitwise AND.</p>


<p>This code is exact, i.e. if, for example, a bit in the left argument is defined and 0, then neither the value not definedness of the corresponding bit in B don't affect the resulting shadow.</p>


<p>Definition at line 2410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitAShr() {#ae9d49d21ac59052e3d17d7fa01228325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAShr (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2855 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a220983874e8efc856fac602c19e9aa2b">handleShift</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitAsmInstruction() {#a27c9f05f074b1acd44859e85c1212bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAsmInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 5352 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8d13199cbf4d080d3b5dcf330dad5d2c">llvm::CallBase::getCalledOperand</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="#a155073ec24bee89eeab846ccc4e7108e">getNumOutputArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aa9d39950dcbd9e1e6dac2b66db4324d4">llvm::CallBase::getParamElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad5393f64ef6c65d1f090169819b68598">instrumentAsmArgument</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>.</p>

</div>
</div>

### visitAtomicCmpXchgInst() {#a378277a0a96b34b3b5634b8ffc865c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAtomicCmpXchgInst (<a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> &amp; I)</td>
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



<p>Definition at line 2320 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a7886b01e9761c33d2235cda57744417d">addReleaseOrdering</a>, <a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitAtomicRMWInst() {#ab772f88fd07120f87cd319177cea148b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAtomicRMWInst (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> &amp; I)</td>
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



<p>Definition at line 2315 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a7886b01e9761c33d2235cda57744417d">addReleaseOrdering</a>, <a href="#a01329a7b6a3dfa3ec5b7755e80b723f9">handleCASOrRMW</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitBitCastInst() {#a005fbd5468607e9616160e82a7665c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitBitCastInst (<a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a> &amp; I)</td>
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



<p>Definition at line 2372 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitCallBase() {#adefa3ab29c92a0c9a23851fd393e5c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 4834 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#ace5f048c7137fe3364e809b3c34c3cca">ClHandleAsmConservative</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4910aab8d7c5528c1a3ac747856c3186">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a8530b6c2036643438422b73afe11d7e3">getOriginPtrForArgument</a>, <a href="#aac996b058186b94adf7a2ae509803265">getOriginPtrForRetval</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a7713a45c8983df00c3975444b94e69ae">llvm::CallBase::getParamAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a88cc5fa65ff17e62b49dc5fb4401f813">llvm::CallBase::getParamByValType</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#aad8b252988733827abdf7bd44a8c2138">getShadowPtrForArgument</a>, <a href="#a55223c498ad94e7e49c3789aba0becce">getShadowPtrForRetval</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a330471067c17061b7c2152d75102f24a">llvm::CallBase::hasRetAttr</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a018f0394a375233d538109968b76a05a">llvm::CallBase::isInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae4b6abe77abf42fb02081a6cc41a0132">llvm::Constant::isNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8ad67a33bae235fe3cca1c3e5a91ed2d">llvm::Type::isSized</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#adce9aed4162f58fbab5da93984822c3a">kParamTLSSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae63427c4d8f3c1ce48401b38ed9198f1">llvm::maybeMarkSanitizerLibraryCallNoBuiltin</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4cbb2344996abd4332716e76178ad4f4">llvm::CallBase::paramHasAttr</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a>, <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#ab431a36084a5700a1f4b518da053f419">TLI</a>, <a href="#a57aec2acd87151c727180e766c8f4dab">VAHelper</a>, <a href="#a27c9f05f074b1acd44859e85c1212bc1">visitAsmInstruction</a>, <a href="#a232a0fe878bb0a5a47219195daadca39">visitInstruction</a>, <a href="#a9b2c0b28c3d1ee4253d2aae4f9172d94">visitLibAtomicLoad</a> and <a href="#abe25be4a6081ab8cac7639e57970ec3c">visitLibAtomicStore</a>.</p>

</div>
</div>

### visitCatchReturnInst() {#a0424da9b791eb2771ef16a9407e8a5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCatchReturnInst (<a href="/web-llvm/docs/api/classes/llvm/catchreturninst">CatchReturnInst</a> &amp; CRI)</td>
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



<p>Definition at line 5286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### visitCatchSwitchInst() {#acc330182e6404dbe33f4a58f24ee722c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCatchSwitchInst (<a href="/web-llvm/docs/api/classes/llvm/catchswitchinst">CatchSwitchInst</a> &amp; I)</td>
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



<p>Definition at line 5230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitCleanupReturnInst() {#a2d9caf4fd36aa8e31bd25af1576ee565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCleanupReturnInst (<a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst">CleanupReturnInst</a> &amp; CRI)</td>
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



<p>Definition at line 5281 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### visitExtractElementInst() {#af4a162e1f6cd54269b8c906eb54ee6fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitExtractElementInst (<a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> &amp; I)</td>
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



<p>Definition at line 2326 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitExtractValueInst() {#a47a02eeff88a7467b6a84a310b3e9eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitExtractValueInst (<a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">ExtractValueInst</a> &amp; I)</td>
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



<p>Definition at line 5242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitFAdd() {#a05f7153a6433bd6da07e4dd29a3a4717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFAdd (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2662 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFCmpInst() {#a8d47532127ac3c3ed48866788d07385b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFCmpInst (<a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a> &amp; I)</td>
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



<p>Definition at line 2838 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFDiv() {#a2a7e1408f8587eab5d7a6795a6e51588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFDiv (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2684 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFMul() {#a4af1fe1215239f5bb00b2bbe7e90b725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFMul (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2664 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFNeg() {#af773d6ca5d9dfe3770599c12a08b49be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFNeg (<a href="/web-llvm/docs/api/classes/llvm/unaryoperator">UnaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2605 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFPExtInst() {#a2b6fa84c0a2c67733d35ecdbfbeafafe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFPExtInst (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> &amp; I)</td>
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



<p>Definition at line 2402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFPToSIInst() {#ab2d0de74b72099fdc4de7d7c5796ef38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFPToSIInst (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> &amp; I)</td>
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



<p>Definition at line 2398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFPToUIInst() {#a832b7cd0e1d0392191a2c9528448834f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFPToUIInst (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> &amp; I)</td>
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



<p>Definition at line 2399 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFPTruncInst() {#af9a04183d7317af48f216ae837acac4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFPTruncInst (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> &amp; I)</td>
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



<p>Definition at line 2403 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFreezeInst() {#a80a03aae53393e1535618f885dd8e113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFreezeInst (<a href="/web-llvm/docs/api/classes/llvm/freezeinst">FreezeInst</a> &amp; I)</td>
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



<p>Definition at line 5396 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitFRem() {#a9e7a7377cca5083d3473b9aa9b0edb61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFRem (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2685 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFSub() {#a8f33b0169f8f0c1322c247a869396d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFSub (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2663 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitFuncletPadInst() {#af47d161cc73a6bddb356cc121c66322a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitFuncletPadInst (<a href="/web-llvm/docs/api/classes/llvm/funcletpadinst">FuncletPadInst</a> &amp; I)</td>
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



<p>Definition at line 5235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitGetElementPtrInst() {#a8fd0cd313fa1a80f8aabf5a31cc67d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitGetElementPtrInst (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &amp; I)</td>
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



<p>Definition at line 5240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitICmpInst() {#a3175c69e435331710c2f03107ef3e8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitICmpInst (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> &amp; I)</td>
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



<p>Definition at line 2809 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#add57c0965797f1cd395cfb0f28be04b7">ClHandleICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a5d5b255beb6e29a70c776d2ad68c68ad">ClHandleICmpExact</a>, <a href="#a823e9b0883ae72e62421714cd8bbda4c">handleEqualityComparison</a>, <a href="#ac689bdce81e76d215f170f7eb3821be3">handleRelationalComparisonExact</a>, <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a>, <a href="#a091a19fb76439b9fff59f052e2648ee9">handleSignedRelationalComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### visitInsertElementInst() {#afbe4a56f60e1964a3e0ce781600334de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitInsertElementInst (<a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a> &amp; I)</td>
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



<p>Definition at line 2334 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitInsertValueInst() {#aead566fef3a7ebeb14cd72efb473079a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitInsertValueInst (<a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">InsertValueInst</a> &amp; I)</td>
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



<p>Definition at line 5254 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a20833e358e38f9a86074bb4cc72b0d14">llvm::IRBuilderBase::CreateInsertValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitInstruction() {#a232a0fe878bb0a5a47219195daadca39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 5402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0e33ca8e9058514c9b82a0e30478140d">ClDumpStrictInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#accd1cfbd692f327894828f50c24ad3b6">dumpInst</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8ad67a33bae235fe3cca1c3e5a91ed2d">llvm::Type::isSized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>


<p>Referenced by <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a> and <a href="#adc96f92f758d183ab0dac483952e3481">visitIntrinsicInst</a>.</p>

</div>
</div>

### visitIntrinsicInst() {#adc96f92f758d183ab0dac483952e3481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitIntrinsicInst (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 4288 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a6dff8a9ea4e4cf80ae780052b6361819">handleAbsIntrinsic</a>, <a href="#a9890e049561cd883603c6a483547b6b5">handleArithmeticWithOverflow</a>, <a href="#a6fbb73043c2f82e97b7a704a91f47dc1">handleAVXHorizontalAddSubIntrinsic</a>, <a href="#a048c7023875711345d33899f3a59f3e2">handleAVXMaskedLoad</a>, <a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a>, <a href="#a0bde622b06aafdb9eb49069b756563ce">handleBinarySdSsIntrinsic</a>, <a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a>, <a href="#a422552f3cad093347a5f83d234925e9d">handleBmiIntrinsic</a>, <a href="#a2487c76cffea045469d6e95ea3a724b0">handleBswap</a>, <a href="#a0fdafd5b5245a6f5f14c41c593d10b69">handleCountZeroes</a>, <a href="#aa28fe1a3de7cc0e732f5d7ee1dc5adbd">handleDppIntrinsic</a>, <a href="#a04fa6c52e825a7d994a3a5eeb1cc4549">handleFunnelShift</a>, <a href="#a94631928dd87cd8134a31c5fb3168c70">handleIntrinsicByApplyingToShadow</a>, <a href="#a70e1c3d3c4ed3b31cb4921817214d40b">handleInvariantGroup</a>, <a href="#ac166d600b506872ca9d2d69c7f587c2d">handleIsFpClass</a>, <a href="#aac621d92c3438d32c257d3e193ed64c2">handleLdmxcsr</a>, <a href="#a0dabd1eec85a33a1d90cf9b9356a3c58">handleLifetimeStart</a>, <a href="#a512e6c35c0ac3187be4445bab50b766e">handleMaskedCompressStore</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a5056eaa4a9d5c87c3566577a0736c47d">handleMaskedScatter</a>, <a href="#a3405abbd1975b05777dc44d9089f1ece">handleMaskedStore</a>, <a href="#af56d49d9b0002920b7190ddb0f3585ff">handleNEONVectorMultiplyIntrinsic</a>, <a href="#aa78bfa47c700608c53890cc25cd44a5b">handleNEONVectorStoreIntrinsic</a>, <a href="#a924a1686eaef2f0a0ded248edc2bdb6c">handlePclmulIntrinsic</a>, <a href="#add81ddc58cfd39fc90b163af92a71bca">handleRoundPdPsIntrinsic</a>, <a href="#a7a310b77dacdbac9c6bfd285af705de5">handleStmxcsr</a>, <a href="#aef9ab401ce01af2ea722f41cfb8e4943">handleUnarySdSsIntrinsic</a>, <a href="#a077e9376af4a6c07ade5704887b2fd49">handleUnknownIntrinsic</a>, <a href="#a2dedad065b777ac076ac9f2b3dc8c013">handleVectorComparePackedIntrinsic</a>, <a href="#a3fc06177748e14bf8ef287dc4347dde3">handleVectorCompareScalarIntrinsic</a>, <a href="#a8ec2e744dff018b81c0eb2a7e9ea4e2b">handleVectorConvertIntrinsic</a>, <a href="#acaaee38930abb5a8c5d6ff71045eda30">handleVectorPackIntrinsic</a>, <a href="#a60a1bcee02000668d052f9d696ada2e9">handleVectorPmaddIntrinsic</a>, <a href="#a8abeeb6d127be621e8ee8d9d667503b2">handleVectorReduceAndIntrinsic</a>, <a href="#a14778d7f19c6c8582a65cb2d05b541ce">handleVectorReduceIntrinsic</a>, <a href="#ae160aa4ec35fca7aaa0f75a8526cb3fb">handleVectorReduceOrIntrinsic</a>, <a href="#ac03d3c26f38bacbd611de31932ef80b4">handleVectorSadIntrinsic</a>, <a href="#af1c328e6af190112474f8c694ccb59dc">handleVectorShiftIntrinsic</a>, <a href="#a27c11aacbd4098eca944c41583e759d0">handleVtestIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a9c9266376e710920a1bd7999ed9c8963">maybeHandleSimpleNomemIntrinsic</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a>, <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a> and <a href="#a232a0fe878bb0a5a47219195daadca39">visitInstruction</a>.</p>

</div>
</div>

### visitIntToPtrInst() {#a0cfc49213d6647056b0e487dc90450b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitIntToPtrInst (<a href="/web-llvm/docs/api/classes/llvm/inttoptrinst">IntToPtrInst</a> &amp; I)</td>
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



<p>Definition at line 2391 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitLandingPadInst() {#a54ebff796e583fc774c4b7ddd669735b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitLandingPadInst (<a href="/web-llvm/docs/api/classes/llvm/landingpadinst">LandingPadInst</a> &amp; I)</td>
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



<p>Definition at line 5223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitLibAtomicLoad() {#a9b2c0b28c3d1ee4253d2aae4f9172d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitLibAtomicLoad (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 4779 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae9f2730f66215fdb82f4e41e45124811">llvm::IRBuilderBase::CreateMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="#a62bf64531735d133d60ced4e7a4d4e03">makeAddAcquireOrderingTable</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#abc10b887caad109288ffceb230493a85">llvm::CallBase::setArgOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#ab630c4065f79030c5d9c17998be71fd3">updateOrigin</a>.</p>


<p>Referenced by <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>.</p>

</div>
</div>

### visitLibAtomicStore() {#abe25be4a6081ab8cac7639e57970ec3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitLibAtomicStore (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 4813 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4910aab8d7c5528c1a3ac747856c3186">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a9ecfbb98ae6069aa910e8aba30aca1d9">makeAddReleaseOrderingTable</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#abc10b887caad109288ffceb230493a85">llvm::CallBase::setArgOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>.</p>

</div>
</div>

### visitLoadInst() {#ab57377826a403a4f8c41d7bb6d77f6b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitLoadInst (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
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

<p>Instrument <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a>.</p>


<p>Loads the corresponding shadow and (optionally) origin. Optionally, checks that the load address is fully defined.</p>


<p>Definition at line 2246 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a7af616ba2a31f5971eb4c842955aafa8">addAcquireOrdering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a0760acbb386bfe440e697587140561cc">kMinOriginAlignment</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitLShr() {#aaa1fcb2e2013a57001fcc43f065bfe3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitLShr (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2856 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a220983874e8efc856fac602c19e9aa2b">handleShift</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitMemCpyInst() {#aec582588d2e3296c8e411ebf91d528b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitMemCpyInst (<a href="/web-llvm/docs/api/classes/llvm/memcpyinst">MemCpyInst</a> &amp; I)</td>
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

<p>Instrument memcpy.</p>


<p>Similar to memmove: avoid copying shadow twice. This is somewhat unfortunate as it may slowdown small constant memcpys. FIXME: consider doing manual inline for small constant sizes and proper alignment.</p>


<p>Note: This also handles memcpy.inline, which promises no calls to external functions as an optimization. However, with instrumentation enabled this is difficult to promise; additionally, we know that the MSan runtime exists and provides __msan_memcpy(). Therefore, we assume that with instrumentation it's safe to turn memcpy.inline into a call to __msan_memcpy(). Should this be wrong, such as when implementing memcpy() itself, instrumentation should be disabled with the no_sanitize attribute.</p>


<p>Definition at line 2907 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>

</div>
</div>

### visitMemMoveInst() {#a5f93e75a1bd79aad5f817f9980e02cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitMemMoveInst (<a href="/web-llvm/docs/api/classes/llvm/memmoveinst">MemMoveInst</a> &amp; I)</td>
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

<p>Instrument llvm.memmove.</p>


<p>At this point we don't know if llvm.memmove will be inlined or not. If we don't instrument it and it gets inlined, our interceptor will not kick in and we will lose the memmove. If we instrument the call here, but it does not get inlined, we will memove the shadow twice: which is bad in case of overlapping regions. So, we simply lower the intrinsic to a call.</p>


<p>Similar situation exists for memcpy and memset.</p>


<p>Definition at line 2884 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>

</div>
</div>

### visitMemSetInst() {#a3057161fac6ccf0d0f7a55a9ce5e8665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitMemSetInst (<a href="/web-llvm/docs/api/classes/llvm/memsetinst">MemSetInst</a> &amp; I)</td>
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



<p>Definition at line 2917 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>

</div>
</div>

### visitMul() {#a58a23d4603a99873024af3b84b576c5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitMul (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2651 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1f4b3d9a1db2a863f398981ea5c1d641">handleMulByConstant</a>, <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitOr() {#a684df7f760d6dcbfea36c5bccb2cfccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitOr (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2432 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitPHINode() {#a88958577efd3c314497a72ea96c60eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitPHINode (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; I)</td>
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



<p>Definition at line 5081 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>, <a href="#a9088c1401ae05507648c2ecee8c9ccbc">PropagateShadow</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a>, <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a> and <a href="#a5287beec429ac02e5db213256dcd8776">ShadowPHINodes</a>.</p>

</div>
</div>

### visitPtrToIntInst() {#ac5bb05e9c2a806f7a3c21eace99b1d7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitPtrToIntInst (<a href="/web-llvm/docs/api/classes/llvm/ptrtointinst">PtrToIntInst</a> &amp; I)</td>
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



<p>Definition at line 2384 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a5699c4e4d29dcada27c885790cab89b3">getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitResumeInst() {#a8e26c08a2b7611381a48e195e8a49b8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitResumeInst (<a href="/web-llvm/docs/api/classes/llvm/resumeinst">ResumeInst</a> &amp; I)</td>
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



<p>Definition at line 5276 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### visitReturnInst() {#a357ae07ce43e35a35899d18f25ea005c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitReturnInst (<a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a> &amp; I)</td>
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



<p>Definition at line 5049 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="#a23454d4124e41a388132c0de01d450ff">F</a>, <a href="#adafc284209e45c14f874dee849b2afd5">getCleanShadow</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#aac996b058186b94adf7a2ae509803265">getOriginPtrForRetval</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a55223c498ad94e7e49c3789aba0becce">getShadowPtrForRetval</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#ae444dc007eb469ddb172d5780f447f07">isAMustTailRetVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a58600da67d1e0fa57a2a70cd3be51d6e">kShadowTLSAlignment</a> and <a href="#af1c581a1cb4c200427b83afa1c463c3f">MS</a>.</p>

</div>
</div>

### visitSDiv() {#a9fe22967a17fc281dc3afea0bc761fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitSDiv (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2678 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitSelectInst() {#a09992489ef0854c6f12d58bf250db0e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; I)</td>
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



<p>Definition at line 5167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitSExtInst() {#a22f2a1b9c4998624686b30ca88c98668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitSExtInst (<a href="/web-llvm/docs/api/classes/llvm/sextinst">SExtInst</a> &amp; I)</td>
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



<p>Definition at line 2354 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitShl() {#a704a1fee76597843c068885f90df5aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitShl (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2854 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a220983874e8efc856fac602c19e9aa2b">handleShift</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitShuffleVectorInst() {#a464dafaad1c67c6d167dd70c6326dde9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> &amp; I)</td>
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



<p>Definition at line 2344 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitSIToFPInst() {#ab0d83677a081e8f0e23fe11742d83830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitSIToFPInst (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> &amp; I)</td>
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



<p>Definition at line 2400 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitSRem() {#a65251363b4be778d2a855cb6acba2666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitSRem (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2680 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitStoreInst() {#a1dad5091fba05972dc72b125bf3be373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitStoreInst (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; I)</td>
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

<p>Instrument <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a>.</p>


<p>Stores the corresponding shadow and (optionally) origin. Optionally, checks that the store address is fully defined.</p>


<p>Definition at line 2284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#afc0f84e2f6fb17e5df5123d01f914e4b">ClCheckAccessAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a> and <a href="#a1e17cdef6be3fbe65c97bed1a437f040">StoreList</a>.</p>

</div>
</div>

### visitSub() {#afe140f3e1fa65182ae3bf0969027e9dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitSub (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2666 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitTruncInst() {#a3d1d4c8c600e51aaa27f230e05e3d553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitTruncInst (<a href="/web-llvm/docs/api/classes/llvm/truncinst">TruncInst</a> &amp; I)</td>
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



<p>Definition at line 2366 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### visitUDiv() {#a06652627b90ae944abff9433688f500c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitUDiv (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2677 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitUIToFPInst() {#a517a594e0e43f88e71496ad09f1a70b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitUIToFPInst (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> &amp; I)</td>
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



<p>Definition at line 2401 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitURem() {#ac50b8121d06f8634d836bfe8e780b11d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitURem (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2679 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a99029699685d64ef824bdbf6fd71754b">handleIntegerDiv</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitVACopyInst() {#ae2220b57cb00d5580de4912c5e86bcb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitVACopyInst (<a href="/web-llvm/docs/api/classes/llvm/vacopyinst">VACopyInst</a> &amp; I)</td>
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



<p>Definition at line 2929 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a57aec2acd87151c727180e766c8f4dab">VAHelper</a>.</p>

</div>
</div>

### visitVAStartInst() {#aca8c53c8908f3a0686e62be14257a280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitVAStartInst (<a href="/web-llvm/docs/api/classes/llvm/vastartinst">VAStartInst</a> &amp; I)</td>
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



<p>Definition at line 2927 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a57aec2acd87151c727180e766c8f4dab">VAHelper</a>.</p>

</div>
</div>

### visitXor() {#a0a9601fb2a0770ca9a67ea574a1537e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitXor (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 2667 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="#a1425e0956a85489ea4a81c949b952094">handleShadowOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### visitZExtInst() {#aab6035ac9679b9449d97646f9c16d135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitZExtInst (<a href="/web-llvm/docs/api/classes/llvm/zextinst">ZExtInst</a> &amp; I)</td>
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



<p>Definition at line 2360 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllocaSet {#a620d735c5fea0163960071e5a3e99a4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;AllocaInst *, 16&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::AllocaSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a> and <a href="#ad360018df823d021f17fd6612acecacf">visitAllocaInst</a>.</p>

</div>
</div>

### F {#a23454d4124e41a388132c0de01d450ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a850fb4fba9984eb18393c06aa6fe3a51">createDppMask</a>, <a href="#a9d656b8ad508d9b36144ca1db4f95181">getLocalVarDescription</a>, <a href="#a0fd41cd05155ed81f0ac16e8a478b860">getLocalVarIdptr</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#ad271462ad31f06423e02d373ce962cf1">getShadowOriginPtrKernelNoVec</a>, <a href="#a03dd63ac617c1242b7694a4b0ae4ed25">getShadowTy</a>, <a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a>, <a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a>, <a href="#a3405abbd1975b05777dc44d9089f1ece">handleMaskedStore</a>, <a href="#aa78bfa47c700608c53890cc25cd44a5b">handleNEONVectorStoreIntrinsic</a>, <a href="#acd39b18dfd59223eea65852ed04b338e">instrumentAlloca</a>, <a href="#a0f56283bd67f32b385c705520aabb932">materializeChecks</a>, <a href="#a0efb7aefc1fd76a565c2ced7d2ff14cb">materializeInstructionChecks</a>, <a href="#a2a6b95606a7aa4afbc8a38114dd8da82">materializeOneCheck</a>, <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a>, <a href="#a045f288bf4edf0fe84985782706d4bb9">originToIntptr</a>, <a href="#a4d9b426f332b379758b891f032f85d52">paintOrigin</a>, <a href="#a00c704ed1965bd5d0348f156a8e33506">storeOrigin</a>, <a href="#a27c9f05f074b1acd44859e85c1212bc1">visitAsmInstruction</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a> and <a href="#a357ae07ce43e35a35899d18f25ea005c">visitReturnInst</a>.</p>

</div>
</div>

### FnPrologueEnd {#a4feeefbf4ec513bf876399ce4b84aad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::FnPrologueEnd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#afc7b613059ab8f04e165d430bb736bba">isInPrologue</a>, <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a> and <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>.</p>

</div>
</div>

### InsertChecks {#a61ccc8f79b82b8f106096534fddbdd03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::InsertChecks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#aac621d92c3438d32c257d3e193ed64c2">handleLdmxcsr</a>, <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a> and <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a>.</p>

</div>
</div>

### Instructions {#aa6f4541cb285cd7d00759c8ffddf9f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 16&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::Instructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a> and <a href="#a78793329d41f7e0ff3ab15f71b2f952c">visit</a>.</p>

</div>
</div>

### InstrumentationList {#a46f569d5ad463a4c719f0e8d4d9d5ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ShadowOriginAndInsertPoint, 16&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::InstrumentationList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1183 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#af6968bc7c8e7e0d6b3fcddb5a934a3c3">insertShadowCheck</a>, <a href="#a0f56283bd67f32b385c705520aabb932">materializeChecks</a> and <a href="#ac02a2e35e2ad7efcce4dace2ac96a3a6">shouldDisambiguateWarningLocation</a>.</p>

</div>
</div>

### InstrumentLifetimeStart {#a2c4b8995820e03b05d6530e8cc2c0752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::InstrumentLifetimeStart = <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a9b9c616adc23214477236548737858c1">ClHandleLifetimeIntrinsics</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a0dabd1eec85a33a1d90cf9b9356a3c58">handleLifetimeStart</a> and <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>.</p>

</div>
</div>

### LazyWarningDebugLocationCount {#a0f7bf4d0adbe765573bbbbbc89ddd626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const DILocation *, int&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::LazyWarningDebugLocationCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ac02a2e35e2ad7efcce4dace2ac96a3a6">shouldDisambiguateWarningLocation</a>.</p>

</div>
</div>

### LifetimeStartList {#a53bb2da7b8d4e6eb90cd44d1e3556af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;IntrinsicInst *, AllocaInst *&gt;, 16&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::LifetimeStartList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1187 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a0dabd1eec85a33a1d90cf9b9356a3c58">handleLifetimeStart</a> and <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>.</p>

</div>
</div>

### MS {#af1c581a1cb4c200427b83afa1c463c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySanitizer&amp; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::MS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a06d139c7ee04d81813f05083f784f67b">constToIntPtr</a>, <a href="#a48d6d1fbffc492921f07f8dc4fb3d875">convertShadowToScalar</a>, <a href="#a0683904b75a4218c8915db0ec157614d">createMetadataCall</a>, <a href="#a39d5c919a484d17c9e12864d869c7f69">CreateShadowCast</a>, <a href="#ab66ea2a3c3ef79789f3bc37709c2cb61">getCleanOrigin</a>, <a href="#abe3f2bc12df17a7c061c315f7bfcf12e">getMMXVectorTy</a>, <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a8530b6c2036643438422b73afe11d7e3">getOriginPtrForArgument</a>, <a href="#aac996b058186b94adf7a2ae509803265">getOriginPtrForRetval</a>, <a href="#ac784928dcbbc1b0691cc8da90970391d">getPtrToShadowPtrType</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a57a4c9ec10c3c1a796f9ca3363c5045f">getShadowOriginPtr</a>, <a href="#a7480612cfe31fd07e5d1d5d45bf3c3b4">getShadowOriginPtrKernel</a>, <a href="#ad271462ad31f06423e02d373ce962cf1">getShadowOriginPtrKernelNoVec</a>, <a href="#aac05ca292709f88f6ba0ae241e0e84bf">getShadowOriginPtrUserspace</a>, <a href="#aad8b252988733827abdf7bd44a8c2138">getShadowPtrForArgument</a>, <a href="#a55223c498ad94e7e49c3789aba0becce">getShadowPtrForRetval</a>, <a href="#aecd57a29db63344a976ec5830496e733">getShadowPtrOffset</a>, <a href="#a03dd63ac617c1242b7694a4b0ae4ed25">getShadowTy</a>, <a href="#a048c7023875711345d33899f3a59f3e2">handleAVXMaskedLoad</a>, <a href="#abba654ce68a6aba9f7cbd731b0917877">handleAVXMaskedStore</a>, <a href="#af57d015c7e57a42f4a73d6414d8d0453">handleBlendvIntrinsic</a>, <a href="#aac621d92c3438d32c257d3e193ed64c2">handleLdmxcsr</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a3405abbd1975b05777dc44d9089f1ece">handleMaskedStore</a>, <a href="#aa78bfa47c700608c53890cc25cd44a5b">handleNEONVectorStoreIntrinsic</a>, <a href="#a107ed4d1a9a7fc30bf59d4129235bada">handleSelectLikeInst</a>, <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#ac03d3c26f38bacbd611de31932ef80b4">handleVectorSadIntrinsic</a>, <a href="#aa386f90ca7b1b24989ce41d70a0ce052">handleVectorStoreIntrinsic</a>, <a href="#ad4fd8682f807900cbed932926bceb717">insertKmsanPrologue</a>, <a href="#a9f4e542bdcac1a2ab15b6e55991f07c8">insertWarningFn</a>, <a href="#acd39b18dfd59223eea65852ed04b338e">instrumentAlloca</a>, <a href="#ad5393f64ef6c65d1f090169819b68598">instrumentAsmArgument</a>, <a href="#a0efb7aefc1fd76a565c2ced7d2ff14cb">materializeInstructionChecks</a>, <a href="#a2a6b95606a7aa4afbc8a38114dd8da82">materializeOneCheck</a>, <a href="#a09cbf4fc467ebb29733bdb77d74e7d07">materializeStores</a>, <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a>, <a href="#a045f288bf4edf0fe84985782706d4bb9">originToIntptr</a>, <a href="#a4d9b426f332b379758b891f032f85d52">paintOrigin</a>, <a href="#a36a965b050969c112696e764545b231e">poisonAllocaKmsan</a>, <a href="#a00e8c5cbc0a9f0269b50f08a187c2f78">poisonAllocaUserspace</a>, <a href="#a69a4b725eeca6669bc2adb458eb5e08f">ptrToIntPtrType</a>, <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>, <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a>, <a href="#ad27037edeacf67c4b3583aee7122ade2">setOriginForNaryOp</a>, <a href="#ac02a2e35e2ad7efcce4dace2ac96a3a6">shouldDisambiguateWarningLocation</a>, <a href="#a00c704ed1965bd5d0348f156a8e33506">storeOrigin</a>, <a href="#ab630c4065f79030c5d9c17998be71fd3">updateOrigin</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#a9b2c0b28c3d1ee4253d2aae4f9172d94">visitLibAtomicLoad</a>, <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a>, <a href="#aec582588d2e3296c8e411ebf91d528b0">visitMemCpyInst</a>, <a href="#a5f93e75a1bd79aad5f817f9980e02cb3">visitMemMoveInst</a>, <a href="#a3057161fac6ccf0d0f7a55a9ce5e8665">visitMemSetInst</a>, <a href="#a88958577efd3c314497a72ea96c60eac">visitPHINode</a> and <a href="#a357ae07ce43e35a35899d18f25ea005c">visitReturnInst</a>.</p>

</div>
</div>

### OriginMap {#a1d20d8cd675fe8f162888d38bcc0ea99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMap&lt;Value *, Value *&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::OriginMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a> and <a href="#a0e79f9f6217e29c2a32e0cb77ce33ab0">setOrigin</a>.</p>

</div>
</div>

### OriginPHINodes {#a7317314e7a515a2b952b59ead684d49f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PHINode *, 16&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::OriginPHINodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>

</div>
</div>

### PoisonStack {#a2198d20c59c67c9de6b25fd45c9262ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::PoisonStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a0dabd1eec85a33a1d90cf9b9356a3c58">handleLifetimeStart</a>, <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a>, <a href="#a36a965b050969c112696e764545b231e">poisonAllocaKmsan</a> and <a href="#a00e8c5cbc0a9f0269b50f08a187c2f78">poisonAllocaUserspace</a>.</p>

</div>
</div>

### PoisonUndef {#a2a8e97da337e78573f55cc8cf4c4500f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::PoisonUndef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a> and <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a>.</p>

</div>
</div>

### PropagateShadow {#a9088c1401ae05507648c2ecee8c9ccbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::PropagateShadow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#ad9e803443a8b2a6d25a73a6b4b2d6560">getOrigin</a>, <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a>, <a href="#a8cc553ff446a1ab299f2d3cd73e9a544">handleMaskedExpandLoad</a>, <a href="#a759cdeca788eae085f33511a111de4e8">handleMaskedGather</a>, <a href="#a454e5d8d7e12243f5e63c713fdd488f4">handleMaskedLoad</a>, <a href="#a0215817db88ff4446c80bf413c754c47">handleVectorLoadIntrinsic</a>, <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a>, <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#ab57377826a403a4f8c41d7bb6d77f6b3">visitLoadInst</a> and <a href="#a88958577efd3c314497a72ea96c60eac">visitPHINode</a>.</p>

</div>
</div>

### ShadowMap {#af72ba6bf0adbad0f1134ed2e8a62b318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMap&lt;Value *, Value *&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::ShadowMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a82680be7fe808dbee556123d6ea82240">getShadow</a> and <a href="#aa479d62de65c7074b376392e3a34d0bc">setShadow</a>.</p>

</div>
</div>

### ShadowPHINodes {#a5287beec429ac02e5db213256dcd8776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PHINode *, 16&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::ShadowPHINodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a> and <a href="#a88958577efd3c314497a72ea96c60eac">visitPHINode</a>.</p>

</div>
</div>

### SplittableBlocksCount {#a6041f8f61469e7649e9f9ad33a5be8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::SplittableBlocksCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a0974eac64f313142c02ae973aca6359e">instrumentWithCalls</a>.</p>

</div>
</div>

### StoreList {#a1e17cdef6be3fbe65c97bed1a437f040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StoreInst *, 16&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::StoreList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1188 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#a09cbf4fc467ebb29733bdb77d74e7d07">materializeStores</a> and <a href="#a1dad5091fba05972dc72b125bf3be373">visitStoreInst</a>.</p>

</div>
</div>

### TLI {#ab431a36084a5700a1f4b518da053f419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a> and <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>.</p>

</div>
</div>

### VAHelper {#a57aec2acd87151c727180e766c8f4dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;VarArgHelper&gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::VAHelper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Referenced by <a href="#aec3293074efad01a669018f6c46f3219">MemorySanitizerVisitor</a>, <a href="#a8605e39e73fa355574fd811094481af4">runOnFunction</a>, <a href="#adefa3ab29c92a0c9a23851fd393e5c0d">visitCallBase</a>, <a href="#ae2220b57cb00d5580de4912c5e86bcb2">visitVACopyInst</a> and <a href="#aca8c53c8908f3a0686e62be14257a280">visitVAStartInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getPclmulMask() {#a97a3c88ff7689bdb2a981cf1e8710273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; int, 8 &gt; anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getPclmulMask (unsigned Width, bool OddElements)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3913 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a924a1686eaef2f0a0ded248edc2bdb6c">handlePclmulIntrinsic</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp">MemorySanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
