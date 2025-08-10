---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxil/resourcetypeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ResourceTypeInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::dxil::ResourceTypeInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">llvm/Analysis/DXILResource.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf457766a07abc5ca724686c63d00126">ResourceTypeInfo</a> (TargetExtType *HandleTy, const dxil::ResourceClass RC, const dxil::ResourceKind Kind, bool GloballyCoherent=false, bool HasCounter=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b3fb191bd5001c762954cfde0545052">ResourceTypeInfo</a> (TargetExtType *HandleTy, bool GloballyCoherent=false, bool HasCounter=false)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf1075c62d7cd8c671f61399f8beb3c">operator==</a> (const ResourceTypeInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43b52d59119d7b57121e995e1b276e77">operator!=</a> (const ResourceTypeInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> (const ResourceTypeInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ab6a445f6fbe43cf40fb65f4c0c54b6">getHandleTy</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643353cc59fa74e91cb3212e25475f58">createElementStruct</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15b9fe5fbc7cddb8c5bd3510a1fbec19">isUAV</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2854da2d6e1e5a85f4abdae5319ddc35">isCBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f38896d47f03dde9704d64b669c135e">isSampler</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ffe17eb014d8227e03af37547ebf39">isStruct</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e1156c776fa816c593792d6c8ec269">isTyped</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a5cab0c30ec1984c6ea9bdd405c289">isFeedback</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17adf49affc0de9924726dd25a7e3a0e">isMultiSample</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo">UAVInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa803b031c7da886b70562ff8e2e69c8d">getUAV</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e3e0c36e81ef726cac1dabc009592e">getCBufferSize</a> (const DataLayout &amp;DL) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a3b63a4b583ba49e5fcbc73a7cfb3575b">dxil::SamplerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213bbc1c7f27d2677965150f90ad5a02">getSamplerType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/structinfo">StructInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8224e6835e29d5e23c3b04a30dec18c">getStruct</a> (const DataLayout &amp;DL) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/typedinfo">TypedInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e4b5d1b12d30d8c969d9171c55ef39">getTyped</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a5ff21e02ed34dd47eeaa9f5a806112ce">dxil::SamplerFeedbackType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7083f943b0d625ac39d20deaca1e863">getFeedbackType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e1d0d1e01c55065a6220f084512668">getMultiSampleCount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687">dxil::ResourceClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a019b4eed93ea6b85c916c8957b04e3fb">getResourceClass</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">dxil::ResourceKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae124b03835afbb3cabde8b8cc0bb9b70">getResourceKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82fac9c786623a6f9aa1a7dcf4b923aa">setGloballyCoherent</a> (bool V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2782513889eba2d5fb385b6e43548f87">setHasCounter</a> (bool V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6519f459201ab6e1833c32363d02615">print</a> (raw_ostream &amp;OS, const DataLayout &amp;DL) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91730b93f44ef04b697fc37aca2685b8">HandleTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b85600daf60eba207deb4e4848fec8e">GloballyCoherent</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d50ed850dfb8c1c86e757c0dbb03dc9">HasCounter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687">dxil::ResourceClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2781256078d0143112183a5504d77d90">RC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">dxil::ResourceKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926e32ada8ed03e87d9aa97a5609c49a">Kind</a></td>
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


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ResourceTypeInfo() {#abf457766a07abc5ca724686c63d00126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTypeInfo::ResourceTypeInfo (<a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> * HandleTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687">dxil::ResourceClass</a> RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">dxil::ResourceKind</a> Kind, bool GloballyCoherent=false, bool HasCounter=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687ab71ecf0b186ac1b938e15483f792b7db">llvm::dxil::SRV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a6902d76cea698982754404da77e5e08a">llvm::dxil::UAV</a>.</p>


<p>Referenced by <a href="#a43b52d59119d7b57121e995e1b276e77">operator!=</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a>, <a href="#adcf1075c62d7cd8c671f61399f8beb3c">operator==</a> and <a href="#a6b3fb191bd5001c762954cfde0545052">ResourceTypeInfo</a>.</p>

</div>
</div>

### ResourceTypeInfo() {#a6b3fb191bd5001c762954cfde0545052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dxil::ResourceTypeInfo::ResourceTypeInfo (<a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> * HandleTy, bool GloballyCoherent=false, bool HasCounter=false)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#abf457766a07abc5ca724686c63d00126">ResourceTypeInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a43b52d59119d7b57121e995e1b276e77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dxil::ResourceTypeInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">ResourceTypeInfo</a> &amp; RHS)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="#abf457766a07abc5ca724686c63d00126">ResourceTypeInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#a14aad51a5df94f2532795cbd9fbedd71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceTypeInfo::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">ResourceTypeInfo</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="#a13e3e0c36e81ef726cac1dabc009592e">getCBufferSize</a>, <a href="#ad7083f943b0d625ac39d20deaca1e863">getFeedbackType</a>, <a href="#a08e1d0d1e01c55065a6220f084512668">getMultiSampleCount</a>, <a href="#a213bbc1c7f27d2677965150f90ad5a02">getSamplerType</a>, <a href="#ab8224e6835e29d5e23c3b04a30dec18c">getStruct</a>, <a href="#a39e4b5d1b12d30d8c969d9171c55ef39">getTyped</a>, <a href="#aa803b031c7da886b70562ff8e2e69c8d">getUAV</a>, <a href="#a2854da2d6e1e5a85f4abdae5319ddc35">isCBuffer</a>, <a href="#a66a5cab0c30ec1984c6ea9bdd405c289">isFeedback</a>, <a href="#a17adf49affc0de9924726dd25a7e3a0e">isMultiSample</a>, <a href="#a1f38896d47f03dde9704d64b669c135e">isSampler</a>, <a href="#ad5ffe17eb014d8227e03af37547ebf39">isStruct</a>, <a href="#a20e1156c776fa816c593792d6c8ec269">isTyped</a>, <a href="#a15b9fe5fbc7cddb8c5bd3510a1fbec19">isUAV</a> and <a href="#abf457766a07abc5ca724686c63d00126">ResourceTypeInfo</a>.</p>

</div>
</div>

### operator==() {#adcf1075c62d7cd8c671f61399f8beb3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceTypeInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">ResourceTypeInfo</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="#abf457766a07abc5ca724686c63d00126">ResourceTypeInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createElementStruct() {#a643353cc59fa74e91cb3212e25475f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * ResourceTypeInfo::createElementStruct ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a06a59eef30545f33a5df0fea71dcaf2e">llvm::dxil::FeedbackTexture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a43ae21351e78d50ee79f0146ed43caf7">llvm::dxil::FeedbackTexture2DArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#a5634ba9e7272ebd109acdfac6823f6c0">formatTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#aa783c34713ae5a1d11196520b2195b22">getResourceKindName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a8fc1460bf51b8b7bd628c575d831ad91">llvm::dxil::RTAccelerationStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a61247dae2236d3488fc521b1b1e4f6f1">llvm::dxil::TBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31adc7f989aa32631adaea4eb6a609b0de4">llvm::dxil::Texture1D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a9506a77553ace6035c9096f86b0a5e8d">llvm::dxil::Texture1DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31aa6e2bae752d3bf4e34cb392bca789995">llvm::dxil::Texture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5452f0008bbc07c796bb4ac7d284928d">llvm::dxil::Texture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a89c915587e16bcf8963be7cf41a0d9fd">llvm::dxil::Texture3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a0a152d9f3e1df14068c5857fb3352505">llvm::dxil::TextureCube</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab134787bfc1bdfe2d470e04468c1aa72">llvm::dxil::TextureCubeArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a842e49a58fb3eba4e42a8dadad77745b">llvm::to_underlying</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a>.</p>

</div>
</div>

### getCBufferSize() {#a13e3e0c36e81ef726cac1dabc009592e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ResourceTypeInfo::getCBufferSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="#a2854da2d6e1e5a85f4abdae5319ddc35">isCBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### getFeedbackType() {#ad7083f943b0d625ac39d20deaca1e863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil::SamplerFeedbackType ResourceTypeInfo::getFeedbackType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a66a5cab0c30ec1984c6ea9bdd405c289">isFeedback</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### getHandleTy() {#a5ab6a445f6fbe43cf40fb65f4c0c54b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetExtType * llvm::dxil::ResourceTypeInfo::getHandleTy ()</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a4d5937fb63dff47c2112c8032650019b">calculateGEPOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a83ab43e08fac8e86c8bf333048ed60e2">createTypedBufferLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#ab8ffe62be4273e6e7903125e60943b0d">createTypedBufferStore</a>.</p>

</div>
</div>

### getMultiSampleCount() {#a08e1d0d1e01c55065a6220f084512668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ResourceTypeInfo::getMultiSampleCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a17adf49affc0de9924726dd25a7e3a0e">isMultiSample</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### getResourceClass() {#a019b4eed93ea6b85c916c8957b04e3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil::ResourceClass llvm::dxil::ResourceTypeInfo::getResourceClass ()</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a0b48396e87e416debd788f0948eee89d">prettyPrintResources</a>.</p>

</div>
</div>

### getResourceKind() {#ae124b03835afbb3cabde8b8cc0bb9b70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil::ResourceKind llvm::dxil::ResourceTypeInfo::getResourceKind ()</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a5f96cb150ec8f59c2799d902cf4a3f6a">createLoadIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a8ac476789127304744e70130f40fa079">createStoreIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>.</p>

</div>
</div>

### getSamplerType() {#a213bbc1c7f27d2677965150f90ad5a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil::SamplerType ResourceTypeInfo::getSamplerType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a1f38896d47f03dde9704d64b669c135e">isSampler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### getStruct() {#ab8224e6835e29d5e23c3b04a30dec18c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTypeInfo::StructInfo ResourceTypeInfo::getStruct (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad5ffe17eb014d8227e03af37547ebf39">isStruct</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### getTyped() {#a39e4b5d1b12d30d8c969d9171c55ef39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTypeInfo::TypedInfo ResourceTypeInfo::getTyped ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#a5f57c8b4798ae6bf7967c81335f9413e">getTypedElementType</a>, <a href="#a20e1156c776fa816c593792d6c8ec269">isTyped</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#a0085f60dd9c826335e451604af12c2b3">toDXILElementType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a7798652700f5ca1003d76faa77ccfaa9">getFormatName</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### getUAV() {#aa803b031c7da886b70562ff8e2e69c8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTypeInfo::UAVInfo ResourceTypeInfo::getUAV ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#a7718bcb1f986a6ba334e0d4bbba1129f">isROV</a> and <a href="#a15b9fe5fbc7cddb8c5bd3510a1fbec19">isUAV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### isCBuffer() {#a2854da2d6e1e5a85f4abdae5319ddc35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceTypeInfo::isCBuffer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#a13e3e0c36e81ef726cac1dabc009592e">getCBufferSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a7798652700f5ca1003d76faa77ccfaa9">getFormatName</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### isFeedback() {#a66a5cab0c30ec1984c6ea9bdd405c289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceTypeInfo::isFeedback ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a06a59eef30545f33a5df0fea71dcaf2e">llvm::dxil::FeedbackTexture2D</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a43ae21351e78d50ee79f0146ed43caf7">llvm::dxil::FeedbackTexture2DArray</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#ad7083f943b0d625ac39d20deaca1e863">getFeedbackType</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### isMultiSample() {#a17adf49affc0de9924726dd25a7e3a0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceTypeInfo::isMultiSample ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#a08e1d0d1e01c55065a6220f084512668">getMultiSampleCount</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### isSampler() {#a1f38896d47f03dde9704d64b669c135e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceTypeInfo::isSampler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a7798652700f5ca1003d76faa77ccfaa9">getFormatName</a>, <a href="#a213bbc1c7f27d2677965150f90ad5a02">getSamplerType</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### isStruct() {#ad5ffe17eb014d8227e03af37547ebf39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceTypeInfo::isStruct ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a7798652700f5ca1003d76faa77ccfaa9">getFormatName</a>, <a href="#ab8224e6835e29d5e23c3b04a30dec18c">getStruct</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### isTyped() {#a20e1156c776fa816c593792d6c8ec269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceTypeInfo::isTyped ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a06a59eef30545f33a5df0fea71dcaf2e">llvm::dxil::FeedbackTexture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a43ae21351e78d50ee79f0146ed43caf7">llvm::dxil::FeedbackTexture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a8fc1460bf51b8b7bd628c575d831ad91">llvm::dxil::RTAccelerationStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a61247dae2236d3488fc521b1b1e4f6f1">llvm::dxil::TBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31adc7f989aa32631adaea4eb6a609b0de4">llvm::dxil::Texture1D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a9506a77553ace6035c9096f86b0a5e8d">llvm::dxil::Texture1DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31aa6e2bae752d3bf4e34cb392bca789995">llvm::dxil::Texture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5452f0008bbc07c796bb4ac7d284928d">llvm::dxil::Texture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a89c915587e16bcf8963be7cf41a0d9fd">llvm::dxil::Texture3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a0a152d9f3e1df14068c5857fb3352505">llvm::dxil::TextureCube</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab134787bfc1bdfe2d470e04468c1aa72">llvm::dxil::TextureCubeArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a4d5937fb63dff47c2112c8032650019b">calculateGEPOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a7798652700f5ca1003d76faa77ccfaa9">getFormatName</a>, <a href="#a39e4b5d1b12d30d8c969d9171c55ef39">getTyped</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### isUAV() {#a15b9fe5fbc7cddb8c5bd3510a1fbec19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceTypeInfo::isUAV ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a6902d76cea698982754404da77e5e08a">llvm::dxil::UAV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a43c26462d608e19ba26f5425e5435127">llvm::dxil::ResourceBindingInfo::getAnnotateProps</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="#aa803b031c7da886b70562ff8e2e69c8d">getUAV</a>, <a href="#a14aad51a5df94f2532795cbd9fbedd71">operator&lt;</a> and <a href="#af6519f459201ab6e1833c32363d02615">print</a>.</p>

</div>
</div>

### print() {#af6519f459201ab6e1833c32363d02615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceTypeInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/typedinfo/#a4504b3a027b16534569d46afa637c1bb">llvm::dxil::ResourceTypeInfo::TypedInfo::ElementCount</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/typedinfo/#aece1edf692f952783c46dc7563b4f60d">llvm::dxil::ResourceTypeInfo::TypedInfo::ElementTy</a>, <a href="#a13e3e0c36e81ef726cac1dabc009592e">getCBufferSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#a51f631ba724559ca64e2258718e4fe0d">getElementTypeName</a>, <a href="#ad7083f943b0d625ac39d20deaca1e863">getFeedbackType</a>, <a href="#a08e1d0d1e01c55065a6220f084512668">getMultiSampleCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#a3ceb60a6c28ad3574d23723dfa61a8f2">getResourceClassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#aa783c34713ae5a1d11196520b2195b22">getResourceKindName</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#ae94995a4ec2f4ca53306e285f1cec43e">getSamplerFeedbackTypeName</a>, <a href="#a213bbc1c7f27d2677965150f90ad5a02">getSamplerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp/#ab80d2460c17624fab2d9f6e292a18daa">getSamplerTypeName</a>, <a href="#ab8224e6835e29d5e23c3b04a30dec18c">getStruct</a>, <a href="#a39e4b5d1b12d30d8c969d9171c55ef39">getTyped</a>, <a href="#aa803b031c7da886b70562ff8e2e69c8d">getUAV</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo/#a2ecfd4b2d178515321dc0e838733f9a5">llvm::dxil::ResourceTypeInfo::UAVInfo::GloballyCoherent</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo/#acc42675a7ccc6a57238abf1373d0a8bc">llvm::dxil::ResourceTypeInfo::UAVInfo::HasCounter</a>, <a href="#a2854da2d6e1e5a85f4abdae5319ddc35">isCBuffer</a>, <a href="#a66a5cab0c30ec1984c6ea9bdd405c289">isFeedback</a>, <a href="#a17adf49affc0de9924726dd25a7e3a0e">isMultiSample</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/uavinfo/#a5aeeeaedc9cc6822700f491570ab6068">llvm::dxil::ResourceTypeInfo::UAVInfo::IsROV</a>, <a href="#a1f38896d47f03dde9704d64b669c135e">isSampler</a>, <a href="#ad5ffe17eb014d8227e03af37547ebf39">isStruct</a>, <a href="#a20e1156c776fa816c593792d6c8ec269">isTyped</a>, <a href="#a15b9fe5fbc7cddb8c5bd3510a1fbec19">isUAV</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a763a932e166ac85a6d2d1606e8649993">Struct</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#ae91cb2487ec1305b31571bb8187dbf68">llvm::dxil::ResourceBindingInfo::print</a>.</p>

</div>
</div>

### setGloballyCoherent() {#a82fac9c786623a6f9aa1a7dcf4b923aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::ResourceTypeInfo::setGloballyCoherent (bool V)</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### setHasCounter() {#a2782513889eba2d5fb385b6e43548f87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxil::ResourceTypeInfo::setHasCounter (bool V)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GloballyCoherent {#a7b85600daf60eba207deb4e4848fec8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dxil::ResourceTypeInfo::GloballyCoherent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### HandleTy {#a91730b93f44ef04b697fc37aca2685b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetExtType* llvm::dxil::ResourceTypeInfo::HandleTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### HasCounter {#a8d50ed850dfb8c1c86e757c0dbb03dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dxil::ResourceTypeInfo::HasCounter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### Kind {#a926e32ada8ed03e87d9aa97a5609c49a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil::ResourceKind llvm::dxil::ResourceTypeInfo::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### RC {#a2781256078d0143112183a5504d77d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil::ResourceClass llvm::dxil::ResourceTypeInfo::RC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
