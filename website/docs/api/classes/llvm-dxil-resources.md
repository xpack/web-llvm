---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxil/resources
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Resources` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::dxil::Resources { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">Target/DirectX/DXILResource.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f9fb5f5e06551dff3698b7d07de852">collect</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87bafd9a99b84743b04303b76e1763eb">hasUAVs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b258c14fec4519676f1ca9c51516ad">writeUAVs</a> (Module &amp;M) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb0a0862be18e7a3f204477d1c37262">printUAVs</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3c0f21d561d7cb2b2b9858f1b8744ae">hasCBuffers</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d5b4cdb8c489feec505196bcb942db">writeCBuffers</a> (Module &amp;M) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeccc967338a23aaf0392de3d0b84bdd3">printCBuffers</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b95a0d2a4c6eefd6d056269bd93ac1">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetable">ResourceTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dxil/uavresource">UAVResource</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8eac612d496edc1565288ffa123143f">UAVs</a> = {"hlsl.uavs"}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetable">ResourceTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dxil/constantbuffer">ConstantBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68882a8d076e70cff87cbdb5d6198c1a">CBuffers</a> = {"hlsl.cbufs"}</td>
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


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### collect() {#ae7f9fb5f5e06551dff3698b7d07de852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Resources::collect (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>

</div>
</div>

### dump() {#a00b95a0d2a4c6eefd6d056269bd93ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Resources::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aeccc967338a23aaf0392de3d0b84bdd3">printCBuffers</a> and <a href="#adcb0a0862be18e7a3f204477d1c37262">printUAVs</a>.</p>

</div>
</div>

### hasCBuffers() {#af3c0f21d561d7cb2b2b9858f1b8744ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dxil::Resources::hasCBuffers ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a0b48396e87e416debd788f0948eee89d">prettyPrintResources</a>.</p>

</div>
</div>

### hasUAVs() {#a87bafd9a99b84743b04303b76e1763eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dxil::Resources::hasUAVs ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a0b48396e87e416debd788f0948eee89d">prettyPrintResources</a>.</p>

</div>
</div>

### printCBuffers() {#aeccc967338a23aaf0392de3d0b84bdd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Resources::printCBuffers (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a451513f65fe632b0369c9f016117263f">llvm::Metadata::print</a>.</p>


<p>Referenced by <a href="#a00b95a0d2a4c6eefd6d056269bd93ac1">dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a0b48396e87e416debd788f0948eee89d">prettyPrintResources</a>.</p>

</div>
</div>

### printUAVs() {#adcb0a0862be18e7a3f204477d1c37262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Resources::printUAVs (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a451513f65fe632b0369c9f016117263f">llvm::Metadata::print</a>.</p>


<p>Referenced by <a href="#a00b95a0d2a4c6eefd6d056269bd93ac1">dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#a0b48396e87e416debd788f0948eee89d">prettyPrintResources</a>.</p>

</div>
</div>

### writeCBuffers() {#ad7d5b4cdb8c489feec505196bcb942db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * Resources::writeCBuffers (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>.</p>

</div>
</div>

### writeUAVs() {#a31b258c14fec4519676f1ca9c51516ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * Resources::writeUAVs (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CBuffers {#a68882a8d076e70cff87cbdb5d6198c1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTable&lt;ConstantBuffer&gt; llvm::dxil::Resources::CBuffers = {"hlsl.cbufs"}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### UAVs {#ad8eac612d496edc1565288ffa123143f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceTable&lt;UAVResource&gt; llvm::dxil::Resources::UAVs = {"hlsl.uavs"}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresource-h">DXILResource.h</a>.</p>

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
