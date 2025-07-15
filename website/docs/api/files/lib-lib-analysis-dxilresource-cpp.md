---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/dxilresource-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DXILResource.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">llvm/Analysis/DXILResource.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "llvm/IR/IntrinsicsDirectX.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ceb60a6c28ad3574d23723dfa61a8f2">getResourceClassName</a> (ResourceClass RC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa783c34713ae5a1d11196520b2195b22">getResourceKindName</a> (ResourceKind RK)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f631ba724559ca64e2258718e4fe0d">getElementTypeName</a> (ElementType ET)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab80d2460c17624fab2d9f6e292a18daa">getSamplerTypeName</a> (SamplerType ST)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae94995a4ec2f4ca53306e285f1cec43e">getSamplerFeedbackTypeName</a> (SamplerFeedbackType SFT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0">dxil::ElementType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0085f60dd9c826335e451604af12c2b3">toDXILElementType</a> (Type *Ty, bool IsSigned)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5634ba9e7272ebd109acdfac6823f6c0">formatTypeName</a> (SmallString&lt; 64 &gt; &amp;Dest, StringRef Name, bool isWriteable, bool isROV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7718bcb1f986a6ba334e0d4bbba1129f">isROV</a> (dxil::ResourceKind Kind, TargetExtType *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f57c8b4798ae6bf7967c81335f9413e">getTypedElementType</a> (dxil::ResourceKind Kind, TargetExtType *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"dxil-resource"</td>
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

### formatTypeName() {#a5634ba9e7272ebd109acdfac6823f6c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void formatTypeName (<a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 64 &gt; &amp; Dest, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool isWriteable, bool isROV)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="#a7718bcb1f986a6ba334e0d4bbba1129f">isROV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a643353cc59fa74e91cb3212e25475f58">llvm::dxil::ResourceTypeInfo::createElementStruct</a>.</p>

</div>
</div>

### getElementTypeName() {#a51f631ba724559ca64e2258718e4fe0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getElementTypeName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0">ElementType</a> ET)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#af6519f459201ab6e1833c32363d02615">llvm::dxil::ResourceTypeInfo::print</a>.</p>

</div>
</div>

### getResourceClassName() {#a3ceb60a6c28ad3574d23723dfa61a8f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getResourceClassName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687">ResourceClass</a> RC)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#af6519f459201ab6e1833c32363d02615">llvm::dxil::ResourceTypeInfo::print</a>.</p>

</div>
</div>

### getResourceKindName() {#aa783c34713ae5a1d11196520b2195b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getResourceKindName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">ResourceKind</a> RK)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a643353cc59fa74e91cb3212e25475f58">llvm::dxil::ResourceTypeInfo::createElementStruct</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#af6519f459201ab6e1833c32363d02615">llvm::dxil::ResourceTypeInfo::print</a>.</p>

</div>
</div>

### getSamplerFeedbackTypeName() {#ae94995a4ec2f4ca53306e285f1cec43e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getSamplerFeedbackTypeName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a5ff21e02ed34dd47eeaa9f5a806112ce">SamplerFeedbackType</a> SFT)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#af6519f459201ab6e1833c32363d02615">llvm::dxil::ResourceTypeInfo::print</a>.</p>

</div>
</div>

### getSamplerTypeName() {#ab80d2460c17624fab2d9f6e292a18daa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getSamplerTypeName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a3b63a4b583ba49e5fcbc73a7cfb3575b">SamplerType</a> ST)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#af6519f459201ab6e1833c32363d02615">llvm::dxil::ResourceTypeInfo::print</a>.</p>

</div>
</div>

### getTypedElementType() {#a5f57c8b4798ae6bf7967c81335f9413e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Type *, bool &gt; getTypedElementType (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">dxil::ResourceKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> * Ty)</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a06a59eef30545f33a5df0fea71dcaf2e">llvm::dxil::FeedbackTexture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a43ae21351e78d50ee79f0146ed43caf7">llvm::dxil::FeedbackTexture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a8fc1460bf51b8b7bd628c575d831ad91">llvm::dxil::RTAccelerationStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a61247dae2236d3488fc521b1b1e4f6f1">llvm::dxil::TBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31adc7f989aa32631adaea4eb6a609b0de4">llvm::dxil::Texture1D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a9506a77553ace6035c9096f86b0a5e8d">llvm::dxil::Texture1DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31aa6e2bae752d3bf4e34cb392bca789995">llvm::dxil::Texture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5452f0008bbc07c796bb4ac7d284928d">llvm::dxil::Texture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a89c915587e16bcf8963be7cf41a0d9fd">llvm::dxil::Texture3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a0a152d9f3e1df14068c5857fb3352505">llvm::dxil::TextureCube</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab134787bfc1bdfe2d470e04468c1aa72">llvm::dxil::TextureCubeArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a39e4b5d1b12d30d8c969d9171c55ef39">llvm::dxil::ResourceTypeInfo::getTyped</a>.</p>

</div>
</div>

### isROV() {#a7718bcb1f986a6ba334e0d4bbba1129f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isROV (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">dxil::ResourceKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> * Ty)</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a06a59eef30545f33a5df0fea71dcaf2e">llvm::dxil::FeedbackTexture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a43ae21351e78d50ee79f0146ed43caf7">llvm::dxil::FeedbackTexture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a8fc1460bf51b8b7bd628c575d831ad91">llvm::dxil::RTAccelerationStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a61247dae2236d3488fc521b1b1e4f6f1">llvm::dxil::TBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31adc7f989aa32631adaea4eb6a609b0de4">llvm::dxil::Texture1D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a9506a77553ace6035c9096f86b0a5e8d">llvm::dxil::Texture1DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31aa6e2bae752d3bf4e34cb392bca789995">llvm::dxil::Texture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5452f0008bbc07c796bb4ac7d284928d">llvm::dxil::Texture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a89c915587e16bcf8963be7cf41a0d9fd">llvm::dxil::Texture3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a0a152d9f3e1df14068c5857fb3352505">llvm::dxil::TextureCube</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab134787bfc1bdfe2d470e04468c1aa72">llvm::dxil::TextureCubeArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a>.</p>


<p>Referenced by <a href="#a5634ba9e7272ebd109acdfac6823f6c0">formatTypeName</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#aa803b031c7da886b70562ff8e2e69c8d">llvm::dxil::ResourceTypeInfo::getUAV</a>.</p>

</div>
</div>

### toDXILElementType() {#a0085f60dd9c826335e451604af12c2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil::ElementType toDXILElementType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool IsSigned)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a39e4b5d1b12d30d8c969d9171c55ef39">llvm::dxil::ResourceTypeInfo::getTyped</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"dxil-resource"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
