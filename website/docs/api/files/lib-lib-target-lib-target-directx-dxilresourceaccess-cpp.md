---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DXILResourceAccess.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-h">DXILResourceAccess.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directx-h">DirectX.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">llvm/Analysis/DXILResource.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "llvm/IR/IntrinsicsDirectX.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-dxilresourceaccess-cpp-">anonymous{DXILResourceAccess.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dxilresourceaccess-cpp-/dxilresourceaccesslegacy">DXILResourceAccessLegacy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d5937fb63dff47c2112c8032650019b">calculateGEPOffset</a> (GetElementPtrInst *GEP, Value *PrevOffset, dxil::ResourceTypeInfo &amp;RTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ffe62be4273e6e7903125e60943b0d">createTypedBufferStore</a> (IntrinsicInst *II, StoreInst *SI, Value *Offset, dxil::ResourceTypeInfo &amp;RTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd0c855866eb615f85011fb3685dab7">createRawStore</a> (IntrinsicInst *II, StoreInst *SI, Value *Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac476789127304744e70130f40fa079">createStoreIntrinsic</a> (IntrinsicInst *II, StoreInst *SI, Value *Offset, dxil::ResourceTypeInfo &amp;RTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ab43e08fac8e86c8bf333048ed60e2">createTypedBufferLoad</a> (IntrinsicInst *II, LoadInst *LI, Value *Offset, dxil::ResourceTypeInfo &amp;RTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55693c3374f66a0794daf3c1dbd00974">createRawLoad</a> (IntrinsicInst *II, LoadInst *LI, Value *Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f96cb150ec8f59c2799d902cf4a3f6a">createLoadIntrinsic</a> (IntrinsicInst *II, LoadInst *LI, Value *Offset, dxil::ResourceTypeInfo &amp;RTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c671e8273bc99e266f62322b29a157">replaceAccess</a> (IntrinsicInst *II, dxil::ResourceTypeInfo &amp;RTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e57a32db7a34deb4c8eb088e60ef239">transformResourcePointers</a> (Function &amp;F, DXILResourceTypeMap &amp;DRTM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6832a78dbbad6c47769e155eed09a550">INITIALIZE_PASS_BEGIN</a> (DXILResourceAccessLegacy, DEBUG_TYPE, "DXIL Resource Access", false, false) INITIALIZE_PASS_END(DXILResourceAccessLegacy</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DXIL Resource</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4fa2b9065093d32736f78ea43a8c8a">Access</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DXIL Resource</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033dff311a619830656a18269413198a">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"dxil-resource-access"</td>
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

### calculateGEPOffset() {#a4d5937fb63dff47c2112c8032650019b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * calculateGEPOffset (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PrevOffset, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RTI)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a5ab6a445f6fbe43cf40fb65f4c0c54b6">llvm::dxil::ResourceTypeInfo::getHandleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a4b50ac2e68c066aa61e2052a8c78aa37">llvm::TargetExtType::getTypeParameter</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a20e1156c776fa816c593792d6c8ec269">llvm::dxil::ResourceTypeInfo::isTyped</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a5d6e37f3d036496321824378223ad718a8009351707fa969013ab5d9126bab03e">Scaled</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a05d674becc60ba4ef8cd4dd4d38ac27a">llvm::APInt::udiv</a>.</p>


<p>Referenced by <a href="#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>.</p>

</div>
</div>

### createLoadIntrinsic() {#a5f96cb150ec8f59c2799d902cf4a3f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createLoadIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RTI)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="#a55693c3374f66a0794daf3c1dbd00974">createRawLoad</a>, <a href="#a83ab43e08fac8e86c8bf333048ed60e2">createTypedBufferLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a06a59eef30545f33a5df0fea71dcaf2e">llvm::dxil::FeedbackTexture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a43ae21351e78d50ee79f0146ed43caf7">llvm::dxil::FeedbackTexture2DArray</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ae124b03835afbb3cabde8b8cc0bb9b70">llvm::dxil::ResourceTypeInfo::getResourceKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a8fc1460bf51b8b7bd628c575d831ad91">llvm::dxil::RTAccelerationStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a61247dae2236d3488fc521b1b1e4f6f1">llvm::dxil::TBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31adc7f989aa32631adaea4eb6a609b0de4">llvm::dxil::Texture1D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a9506a77553ace6035c9096f86b0a5e8d">llvm::dxil::Texture1DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31aa6e2bae752d3bf4e34cb392bca789995">llvm::dxil::Texture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5452f0008bbc07c796bb4ac7d284928d">llvm::dxil::Texture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a89c915587e16bcf8963be7cf41a0d9fd">llvm::dxil::Texture3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a0a152d9f3e1df14068c5857fb3352505">llvm::dxil::TextureCube</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab134787bfc1bdfe2d470e04468c1aa72">llvm::dxil::TextureCubeArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a> and <a href="#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>.</p>

</div>
</div>

### createRawLoad() {#a55693c3374f66a0794daf3c1dbd00974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createRawLoad (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1fb6e8365dbf4ef3a7426ff3d531ff87">llvm::IRBuilderBase::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>.</p>


<p>Referenced by <a href="#a5f96cb150ec8f59c2799d902cf4a3f6a">createLoadIntrinsic</a>.</p>

</div>
</div>

### createRawStore() {#afbd0c855866eb615f85011fb3685dab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createRawStore (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad0243f1634f75e231041023ffaa8501a">llvm::IRBuilderBase::getVoidTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a8ac476789127304744e70130f40fa079">createStoreIntrinsic</a>.</p>

</div>
</div>

### createStoreIntrinsic() {#a8ac476789127304744e70130f40fa079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createStoreIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RTI)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="#afbd0c855866eb615f85011fb3685dab7">createRawStore</a>, <a href="#ab8ffe62be4273e6e7903125e60943b0d">createTypedBufferStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a06a59eef30545f33a5df0fea71dcaf2e">llvm::dxil::FeedbackTexture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a43ae21351e78d50ee79f0146ed43caf7">llvm::dxil::FeedbackTexture2DArray</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ae124b03835afbb3cabde8b8cc0bb9b70">llvm::dxil::ResourceTypeInfo::getResourceKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a8fc1460bf51b8b7bd628c575d831ad91">llvm::dxil::RTAccelerationStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a61247dae2236d3488fc521b1b1e4f6f1">llvm::dxil::TBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31adc7f989aa32631adaea4eb6a609b0de4">llvm::dxil::Texture1D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a9506a77553ace6035c9096f86b0a5e8d">llvm::dxil::Texture1DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31aa6e2bae752d3bf4e34cb392bca789995">llvm::dxil::Texture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5452f0008bbc07c796bb4ac7d284928d">llvm::dxil::Texture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a89c915587e16bcf8963be7cf41a0d9fd">llvm::dxil::Texture3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a0a152d9f3e1df14068c5857fb3352505">llvm::dxil::TextureCube</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab134787bfc1bdfe2d470e04468c1aa72">llvm::dxil::TextureCubeArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa3168bc53fc117710cec207cc6f60518">llvm::ARMTargetLowering::lowerInterleavedStore</a> and <a href="#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>.</p>

</div>
</div>

### createTypedBufferLoad() {#a83ab43e08fac8e86c8bf333048ed60e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createTypedBufferLoad (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RTI)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a5ab6a445f6fbe43cf40fb65f4c0c54b6">llvm::dxil::ResourceTypeInfo::getHandleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1fb6e8365dbf4ef3a7426ff3d531ff87">llvm::IRBuilderBase::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a4b50ac2e68c066aa61e2052a8c78aa37">llvm::TargetExtType::getTypeParameter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>.</p>


<p>Referenced by <a href="#a5f96cb150ec8f59c2799d902cf4a3f6a">createLoadIntrinsic</a>.</p>

</div>
</div>

### createTypedBufferStore() {#ab8ffe62be4273e6e7903125e60943b0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createTypedBufferStore (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RTI)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a5ab6a445f6fbe43cf40fb65f4c0c54b6">llvm::dxil::ResourceTypeInfo::getHandleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1fb6e8365dbf4ef3a7426ff3d531ff87">llvm::IRBuilderBase::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a4b50ac2e68c066aa61e2052a8c78aa37">llvm::TargetExtType::getTypeParameter</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad0243f1634f75e231041023ffaa8501a">llvm::IRBuilderBase::getVoidTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a763a932e166ac85a6d2d1606e8649993">Struct</a>.</p>


<p>Referenced by <a href="#a8ac476789127304744e70130f40fa079">createStoreIntrinsic</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a6832a78dbbad6c47769e155eed09a550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (DXILResourceAccessLegacy, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "DXIL Resource Access", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### replaceAccess() {#af2c671e8273bc99e266f62322b29a157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceAccess (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RTI)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="#adb4fa2b9065093d32736f78ea43a8c8a">Access</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="#a4d5937fb63dff47c2112c8032650019b">calculateGEPOffset</a>, <a href="#a5f96cb150ec8f59c2799d902cf4a3f6a">createLoadIntrinsic</a>, <a href="#a8ac476789127304744e70130f40fa079">createStoreIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="#a4e57a32db7a34deb4c8eb088e60ef239">transformResourcePointers</a>.</p>

</div>
</div>

### transformResourcePointers() {#a4e57a32db7a34deb4c8eb088e60ef239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool transformResourcePointers (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypemap">DXILResourceTypeMap</a> &amp; DRTM)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxilresourceaccess/#a1d78f24c9cef5813c0cb9aea5b00b183">llvm::DXILResourceAccess::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-dxilresourceaccess-cpp-/dxilresourceaccesslegacy/#aa702425859c9ca8980ea163501ec5523">anonymous{DXILResourceAccess.cpp}::DXILResourceAccessLegacy::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Access {#adb4fa2b9065093d32736f78ea43a8c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DXIL Resource Access</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf61ff0bb1056be6cebafe0f38de1b132">llvm::dwarf::AccessibilityString</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#abf272d6373fcbf3a99b862031412616f">llvm::logicalview::LVElement::accessibilityString</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/baseclassrecord/#a346a1dc263707412f27160bc1873e2cf">llvm::codeview::BaseClassRecord::BaseClassRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#a60735e0d022845d03d123916bb48e1e8">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::canCheckPtrAtRT</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuattributor-cpp-/amdgpuinformationcache/#ab4d9bb05e4f4d98be538317f6f6676e5">anonymous{AMDGPUAttributor.cpp}::AMDGPUInformationCache::checkConstForAddrSpaceCastFromPrivate</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#add290ed56a35aadf648ebccf66491f0f">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::createCheckForAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/datamemberrecord/#ae7dce66175118fdd560ff15b07ff2ede">llvm::codeview::DataMemberRecord::DataMemberRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumeratorrecord/#a8e02c629594e3f8fe9d44918e1824101">llvm::codeview::EnumeratorRecord::EnumeratorRecord</a>, <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a0100a0bf4251ceebee66a03626dcb39b">llvm::AA::PointerInfo::State::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a8046d863469d9c33287fa4a673d00571">foreachMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aa7af9ba14be54f02b7d9f9ba0ddd8e02">llvm::logicalview::LVElement::getAccessibilityCode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#aecfb2afc99cffa8880ec262d026a5038">anonymous{FunctionAttrs.cpp}::getArgmentAccessInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-stacksafetyanalysis-cpp-/stacksafetydataflowanalysis/#a47a85d062f858b280db44bdeb77902b7">anonymous{StackSafetyAnalysis.cpp}::StackSafetyDataFlowAnalysis&lt; CalleeTy &gt;::getArgumentAccessRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp/#a2ef27606df20d46db5a3b4f58604ccba">getFD</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#ac340403e4c2fd9116b74b7c2eb95633f">llvm::MemoryDepChecker::getInstructionsForAccess</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-typerecordmapping-cpp-/#a6e24199be7ad39f6ae05ce0b9ee14f31">anonymous{TypeRecordMapping.cpp}::getMemberAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#aa38dcf9a1b93414e7bd1b956a1d04895">anonymous{MemProfiler.cpp}::MemProfiler::instrumentFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#a0208b6206a644a8b7f20ed1a11bf7c17">anonymous{MemProfiler.cpp}::MemProfiler::instrumentMop</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#a7421c242cf99bb3c1709262edadc96ff">anonymous{MemProfiler.cpp}::MemProfiler::isInterestingMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ade6253c0c19609ec9c632e60e08896fb">mayLoopAccessLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloopidiomrecognition-cpp/#abeee69852204fbee049fd520bdedbaae">mayLoopAccessLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/memberattributes/#ae063a76c88555b3bd28ddb2e4084af59">llvm::codeview::MemberAttributes::MemberAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/memberattributes/#a86a64d9059de3e2f5cc66648fe6ef94d">llvm::codeview::MemberAttributes::MemberAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuattributor-cpp-/amdgpuinformationcache/#a37898eb0ae472c290fda31a00e0c1e11">anonymous{AMDGPUAttributor.cpp}::AMDGPUInformationCache::needsQueuePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/onemethodrecord/#ad88a5f32b30f32f997ecb970ba78447b">llvm::codeview::OneMethodRecord::OneMethodRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a41461f685c104525ad436905851e4ef9">llvm::sys::fs::openFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a9dd05e067933397282c8f2b12374e26e">llvm::sys::fs::openNativeFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#af813ac1290df3ad2f9c1e5640d79cf07">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a3ee48c8b3820d7921735c05689074899">llvm::logicalview::LVLogicalVisitor::printMemberAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a65aa4de0a6a0f21de4233170c7b012d5">llvm::raw_fd_ostream::raw_fd_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#ad93786127ef2bc2f4431394c24c9eea6">llvm::raw_fd_ostream::raw_fd_ostream</a>, <a href="#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#ad208209f7eed8f99f1b06f30d6177647">anonymous{StackSafetyAnalysis.cpp}::resolveAllCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a0fc2ef38053866b74f92789d9635449d">llvm::logicalview::LVElement::setAccessibilityCode</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aa12608a227b11a23e59f0406e6a17fc7">llvm::logicalview::LVElement::setAccessibilityCode</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/staticdatamemberrecord/#a6b232bd21695ca03ca019c39bc548c86">llvm::codeview::StaticDataMemberRecord::StaticDataMemberRecord</a>, <a href="/web-llvm/docs/api/structs/anonymous-memoryssa-cpp-/upwardsmemoryquery/#aea0cf8bd5bfb12b0fe0a58ee3df0f183">anonymous{MemorySSA.cpp}::UpwardsMemoryQuery::UpwardsMemoryQuery</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/virtualbaseclassrecord/#a939229d2e171f9e8981a161419ce9b86">llvm::codeview::VirtualBaseClassRecord::VirtualBaseClassRecord</a>.</p>

</div>
</div>

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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>

</div>
</div>

### false {#a033dff311a619830656a18269413198a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DXIL Resource false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"dxil-resource-access"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp">DXILResourceAccess.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
