---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxil/resourcebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ResourceBase` Class



## Declaration

<div class="doxyDeclaration">
class llvm::dxil::ResourceBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">Target/DirectX/DXILResource.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer">ConstantBuffer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource">UAVResource</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2874d434a66abce2c42f7e4b7a11385a">ResourceBase</a> (uint32_t I, hlsl::FrontendResource R)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed1823c584ef7b7a15606d92eb4e2907">write</a> (LLVMContext &amp;Ctx, MutableArrayRef&lt; Metadata * &gt; Entries) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267ec91f5e1629ab79e6072f219ede70">print</a> (raw_ostream &amp;O, StringRef IDPrefix, StringRef BindingPrefix) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e0d839adb4de710f40e0054743259e">ID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea9d188b8371ec24f799f69b23d271d">GV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91186dfab4404265941441cd399c122d">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad33d5fb64a75b89019a287f221fc28">Space</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621c858e3c9436cc2263a89ac99798d9">LowerBound</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9bb2d6d2a36015ec49fd56ed8197f8">RangeSize</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae274da6189f1bc6b2ff2c2d67b64a7d1">getKindName</a> (dxil::ResourceKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a9f3992a986b8eeb53734efe446bd0">printKind</a> (dxil::ResourceKind Kind, unsigned Alignment, raw_ostream &amp;OS, bool SRV=false, bool HasCounter=false, uint32_t SampleCount=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065af75e944be913f76b8552b144bdde">getElementTypeName</a> (dxil::ElementType CompType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a9b348ed3b108a4203796b3b969daa">printElementType</a> (dxil::ResourceKind Kind, dxil::ElementType CompType, unsigned Alignment, raw_ostream &amp;OS)</td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### ResourceBase() {#a2874d434a66abce2c42f7e4b7a11385a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceBase::ResourceBase (uint32_t I, <a href="/web-llvm/docs/api/classes/llvm/hlsl/frontendresource">hlsl::FrontendResource</a> R)</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#ad625ba253f12b49a01ced02c4190e22b">getGlobalVariable</a>, <a href="#a3ea9d188b8371ec24f799f69b23d271d">GV</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a07e0d839adb4de710f40e0054743259e">ID</a>, <a href="#a621c858e3c9436cc2263a89ac99798d9">LowerBound</a>, <a href="#a91186dfab4404265941441cd399c122d">Name</a>, <a href="#a8f9bb2d6d2a36015ec49fd56ed8197f8">RangeSize</a> and <a href="#a5ad33d5fb64a75b89019a287f221fc28">Space</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer/#a699c74f00854219d83192420b99dad31">llvm::dxil::ConstantBuffer::ConstantBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource/#aa32cb01d11c274c0a8d5cf24ca71957a">llvm::dxil::UAVResource::UAVResource</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### print() {#a267ec91f5e1629ab79e6072f219ede70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceBase::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDPrefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BindingPrefix)</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="#a07e0d839adb4de710f40e0054743259e">ID</a>, <a href="#a621c858e3c9436cc2263a89ac99798d9">LowerBound</a>, <a href="#a8f9bb2d6d2a36015ec49fd56ed8197f8">RangeSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c6d735dfe8fc13a113405c1dda2991e">llvm::right_justify</a>, <a href="#a5ad33d5fb64a75b89019a287f221fc28">Space</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer/#aa5aa155ac9277b1d1532e32ef6d7ca4d">llvm::dxil::ConstantBuffer::print</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource/#af9035aed5f290d442ad6506208184b2a">llvm::dxil::UAVResource::print</a>.</p>

</div>
</div>

### write() {#aed1823c584ef7b7a15606d92eb4e2907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceBase::write (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Entries)</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="#a3ea9d188b8371ec24f799f69b23d271d">GV</a>, <a href="#a07e0d839adb4de710f40e0054743259e">ID</a>, <a href="#a621c858e3c9436cc2263a89ac99798d9">LowerBound</a>, <a href="#a91186dfab4404265941441cd399c122d">Name</a>, <a href="#a8f9bb2d6d2a36015ec49fd56ed8197f8">RangeSize</a> and <a href="#a5ad33d5fb64a75b89019a287f221fc28">Space</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer/#aa3e5db2b88327eea27f1cae82e7cfadf">llvm::dxil::ConstantBuffer::write</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource/#a76bbe32350914cebb70fa8b6fe82d7eb">llvm::dxil::UAVResource::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### GV {#a3ea9d188b8371ec24f799f69b23d271d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* llvm::dxil::ResourceBase::GV</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="#a2874d434a66abce2c42f7e4b7a11385a">ResourceBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer/#a6c344faf8b770f6f9a5d8f2928001621">llvm::dxil::ConstantBuffer::setSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer/#aa3e5db2b88327eea27f1cae82e7cfadf">llvm::dxil::ConstantBuffer::write</a>, <a href="#aed1823c584ef7b7a15606d92eb4e2907">write</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource/#a76bbe32350914cebb70fa8b6fe82d7eb">llvm::dxil::UAVResource::write</a>.</p>

</div>
</div>

### ID {#a07e0d839adb4de710f40e0054743259e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxil::ResourceBase::ID</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="#a267ec91f5e1629ab79e6072f219ede70">print</a>, <a href="#a2874d434a66abce2c42f7e4b7a11385a">ResourceBase</a> and <a href="#aed1823c584ef7b7a15606d92eb4e2907">write</a>.</p>

</div>
</div>

### LowerBound {#a621c858e3c9436cc2263a89ac99798d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxil::ResourceBase::LowerBound</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="#a267ec91f5e1629ab79e6072f219ede70">print</a>, <a href="#a2874d434a66abce2c42f7e4b7a11385a">ResourceBase</a> and <a href="#aed1823c584ef7b7a15606d92eb4e2907">write</a>.</p>

</div>
</div>

### Name {#a91186dfab4404265941441cd399c122d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::dxil::ResourceBase::Name</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer/#aa5aa155ac9277b1d1532e32ef6d7ca4d">llvm::dxil::ConstantBuffer::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource/#af9035aed5f290d442ad6506208184b2a">llvm::dxil::UAVResource::print</a>, <a href="#a2874d434a66abce2c42f7e4b7a11385a">ResourceBase</a> and <a href="#aed1823c584ef7b7a15606d92eb4e2907">write</a>.</p>

</div>
</div>

### RangeSize {#a8f9bb2d6d2a36015ec49fd56ed8197f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxil::ResourceBase::RangeSize</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="#a267ec91f5e1629ab79e6072f219ede70">print</a>, <a href="#a2874d434a66abce2c42f7e4b7a11385a">ResourceBase</a> and <a href="#aed1823c584ef7b7a15606d92eb4e2907">write</a>.</p>

</div>
</div>

### Space {#a5ad33d5fb64a75b89019a287f221fc28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxil::ResourceBase::Space</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="#a267ec91f5e1629ab79e6072f219ede70">print</a>, <a href="#a2874d434a66abce2c42f7e4b7a11385a">ResourceBase</a> and <a href="#aed1823c584ef7b7a15606d92eb4e2907">write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### getElementTypeName() {#a065af75e944be913f76b8552b144bdde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ResourceBase::getElementTypeName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0">dxil::ElementType</a> CompType)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a56d8353718e6fdc78b8d69078a2cdb94">llvm::dxil::F16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a44ad4ef5a76e6aa6fb3e3fa079a54fda">llvm::dxil::F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a1ad5f6f3069070ec4cbbdc94d5e61e0e">llvm::dxil::F64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0aa18c217c4f2a811afcaaf5052945e31b">llvm::dxil::I1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0abcd774f891b5f9df7099f3ea75dadf8d">llvm::dxil::I16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0ad878ea6016bfe01729548bf442de5a8b">llvm::dxil::I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0ae7e62f6928f76df671b5a0379793fab6">llvm::dxil::I64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0ad49746d0d706d396a09cdbd533adbb49">llvm::dxil::PackedS8x32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a07b9bfc15d832cb058af7943f3f1eb58">llvm::dxil::PackedU8x32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a8d29a0d0f0055807a1679a8eed993384">llvm::dxil::SNormF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a90315c4523113b9931857bb2c2342cd9">llvm::dxil::SNormF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a394dc44928458a185fc05d5558bef66a">llvm::dxil::SNormF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0aef9ef3ebca4d2b64b6ec83808bafa5f2">llvm::dxil::U16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0ac8bd5bedff8ef192d39a962afc0e19ee">llvm::dxil::U32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a31d65cccd6593e4101db93fb878abcaa">llvm::dxil::U64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a04c1fb3a9689c66612d74f6c2acb7ff7">llvm::dxil::UNormF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a6812f7bb99b7c468860b2346e1b61867">llvm::dxil::UNormF32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a1b1a9cb50b4bffe8e5eafb4c21090823">llvm::dxil::UNormF64</a>.</p>


<p>Referenced by <a href="#a69a9b348ed3b108a4203796b3b969daa">printElementType</a>.</p>

</div>
</div>

### getKindName() {#ae274da6189f1bc6b2ff2c2d67b64a7d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ResourceBase::getKindName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">dxil::ResourceKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a06a59eef30545f33a5df0fea71dcaf2e">llvm::dxil::FeedbackTexture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a43ae21351e78d50ee79f0146ed43caf7">llvm::dxil::FeedbackTexture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a8fc1460bf51b8b7bd628c575d831ad91">llvm::dxil::RTAccelerationStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a61247dae2236d3488fc521b1b1e4f6f1">llvm::dxil::TBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31adc7f989aa32631adaea4eb6a609b0de4">llvm::dxil::Texture1D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a9506a77553ace6035c9096f86b0a5e8d">llvm::dxil::Texture1DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31aa6e2bae752d3bf4e34cb392bca789995">llvm::dxil::Texture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5452f0008bbc07c796bb4ac7d284928d">llvm::dxil::Texture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a89c915587e16bcf8963be7cf41a0d9fd">llvm::dxil::Texture3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a0a152d9f3e1df14068c5857fb3352505">llvm::dxil::TextureCube</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab134787bfc1bdfe2d470e04468c1aa72">llvm::dxil::TextureCubeArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a>.</p>


<p>Referenced by <a href="#a85a9f3992a986b8eeb53734efe446bd0">printKind</a>.</p>

</div>
</div>

### printElementType() {#a69a9b348ed3b108a4203796b3b969daa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceBase::printElementType (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">dxil::ResourceKind</a> Kind, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0">dxil::ElementType</a> CompType, unsigned Alignment, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="#a065af75e944be913f76b8552b144bdde">getElementTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c6d735dfe8fc13a113405c1dda2991e">llvm::right_justify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer/#aa5aa155ac9277b1d1532e32ef6d7ca4d">llvm::dxil::ConstantBuffer::print</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource/#af9035aed5f290d442ad6506208184b2a">llvm::dxil::UAVResource::print</a>.</p>

</div>
</div>

### printKind() {#a85a9f3992a986b8eeb53734efe446bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceBase::printKind (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">dxil::ResourceKind</a> Kind, unsigned Alignment, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool SRV=false, bool HasCounter=false, uint32_t SampleCount=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="#ae274da6189f1bc6b2ff2c2d67b64a7d1">getKindName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c6d735dfe8fc13a113405c1dda2991e">llvm::right_justify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687ab71ecf0b186ac1b938e15483f792b7db">llvm::dxil::SRV</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer/#aa5aa155ac9277b1d1532e32ef6d7ca4d">llvm::dxil::ConstantBuffer::print</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource/#af9035aed5f290d442ad6506208184b2a">llvm::dxil::UAVResource::print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
