---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxil/constantbuffer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConstantBuffer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::dxil::ConstantBuffer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">Target/DirectX/DXILResource.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase">ResourceBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a699c74f00854219d83192420b99dad31">ConstantBuffer</a> (uint32_t I, hlsl::FrontendResource R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c344faf8b770f6f9a5d8f2928001621">setSize</a> (CBufferDataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e5db2b88327eea27f1cae82e7cfadf">write</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5aa155ac9277b1d1532e32ef6d7ca4d">print</a> (raw_ostream &amp;O) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f75cc910cf3eea935a5fa2eaeaa0a01">CBufferSizeInBytes</a> = 0</td>
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


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConstantBuffer() {#a699c74f00854219d83192420b99dad31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantBuffer::ConstantBuffer (uint32_t I, <a href="/web-llvm/docs/api/classes/llvm/hlsl/frontendresource">hlsl::FrontendResource</a> R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#a2874d434a66abce2c42f7e4b7a11385a">llvm::dxil::ResourceBase::ResourceBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### print() {#aa5aa155ac9277b1d1532e32ef6d7ca4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantBuffer::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5b1b4e94f62050dd1bccb48141ef4b9">llvm::left_justify</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#a91186dfab4404265941441cd399c122d">llvm::dxil::ResourceBase::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#a267ec91f5e1629ab79e6072f219ede70">llvm::dxil::ResourceBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#a69a9b348ed3b108a4203796b3b969daa">llvm::dxil::ResourceBase::printElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#a85a9f3992a986b8eeb53734efe446bd0">llvm::dxil::ResourceBase::printKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1c6d735dfe8fc13a113405c1dda2991e">llvm::right_justify</a>.</p>

</div>
</div>

### setSize() {#a6c344faf8b770f6f9a5d8f2928001621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantBuffer::setSize (<a href="/web-llvm/docs/api/classes/llvm/dxil/cbufferdatalayout">CBufferDataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#a3ea9d188b8371ec24f799f69b23d271d">llvm::dxil::ResourceBase::GV</a>.</p>

</div>
</div>

### write() {#aa3e5db2b88327eea27f1cae82e7cfadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * ConstantBuffer::write ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#a3ea9d188b8371ec24f799f69b23d271d">llvm::dxil::ResourceBase::GV</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#aed1823c584ef7b7a15606d92eb4e2907">llvm::dxil::ResourceBase::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CBufferSizeInBytes {#a0f75cc910cf3eea935a5fa2eaeaa0a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxil::ConstantBuffer::CBufferSizeInBytes = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>

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
