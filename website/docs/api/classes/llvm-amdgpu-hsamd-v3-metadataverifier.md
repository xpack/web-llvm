---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpu/hsamd/v3/metadataverifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MetadataVerifier` Class

<p>Verifier for <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> HSA metadata. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPU::HSAMD::V3::MetadataVerifier { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">llvm/BinaryFormat/AMDGPUMetadataVerifier.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630cfa151ed689889684f89f3d96b763">MetadataVerifier</a> (bool Strict)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/v3/metadataverifier">MetadataVerifier</a>, specifying whether it will operate in <span class="doxyComputerOutput">Strict</span> mode. <a href="#a630cfa151ed689889684f89f3d96b763">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae75dbe908959d6ab2501bcef46e70410">verify</a> (msgpack::DocNode &amp;HSAMetadataRoot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify given HSA metadata. <a href="#ae75dbe908959d6ab2501bcef46e70410">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb326324bd6393f795b5abd681bc7ccb">verifyScalar</a> (msgpack::DocNode &amp;Node, msgpack::Type SKind, function_ref&lt; bool(msgpack::DocNode &amp;)&gt; verifyValue={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e942fe73bc359667dfefa1ea2639749">verifyInteger</a> (msgpack::DocNode &amp;Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe2b60f0d6ffa1d1310e0fb4f2e3cd8">verifyArray</a> (msgpack::DocNode &amp;Node, function_ref&lt; bool(msgpack::DocNode &amp;)&gt; verifyNode, std::optional&lt; size_t &gt; Size=std::nullopt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88594a59dad785e3019da38793988639">verifyEntry</a> (msgpack::MapDocNode &amp;MapNode, StringRef Key, bool Required, function_ref&lt; bool(msgpack::DocNode &amp;)&gt; verifyNode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4272cca24a6430995110f7dae8dadecb">verifyScalarEntry</a> (msgpack::MapDocNode &amp;MapNode, StringRef Key, bool Required, msgpack::Type SKind, function_ref&lt; bool(msgpack::DocNode &amp;)&gt; verifyValue={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77c82cc66abbb283390e1e9983de2362">verifyIntegerEntry</a> (msgpack::MapDocNode &amp;MapNode, StringRef Key, bool Required)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7305a512e55d80b14d67b050431b598">verifyKernelArgs</a> (msgpack::DocNode &amp;Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac022879a4cb7c5771214426978c948d0">verifyKernel</a> (msgpack::DocNode &amp;Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ab0e642057a60ae65e6f996677bef7">Strict</a></td>
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

<p>Verifier for <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> HSA metadata.</p>


<p>Operates in two modes:</p>


<p>In strict mode, metadata must already be well-typed.</p>


<p>In non-strict mode, metadata is coerced into expected types when possible.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MetadataVerifier() {#a630cfa151ed689889684f89f3d96b763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPU::HSAMD::V3::MetadataVerifier::MetadataVerifier (bool Strict)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/v3/metadataverifier">MetadataVerifier</a>, specifying whether it will operate in <span class="doxyComputerOutput">Strict</span> mode.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### verify() {#ae75dbe908959d6ab2501bcef46e70410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verify (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp; HSAMetadataRoot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify given HSA metadata.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True when successful, false when metadata is invalid.</p></dd>
</dl>


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a01acd23f4e4e583c9eaf2c03923b157e">llvm::msgpack::DocNode::getMap</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#a78440e992da7b87645bb9c7cdb1b6525">llvm::msgpack::DocNode::isMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### verifyArray() {#aafe2b60f0d6ffa1d1310e0fb4f2e3cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verifyArray (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp; Node, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;)&gt; verifyNode, std::optional&lt; size_t &gt; Size=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a>.</p>

</div>
</div>

### verifyEntry() {#a88594a59dad785e3019da38793988639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verifyEntry (<a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a> &amp; MapNode, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, bool Required, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;)&gt; verifyNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a>.</p>

</div>
</div>

### verifyInteger() {#a8e942fe73bc359667dfefa1ea2639749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verifyInteger (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp; Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a>.</p>

</div>
</div>

### verifyIntegerEntry() {#a77c82cc66abbb283390e1e9983de2362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verifyIntegerEntry (<a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a> &amp; MapNode, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, bool Required)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a>.</p>

</div>
</div>

### verifyKernel() {#ac022879a4cb7c5771214426978c948d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verifyKernel (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp; Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a>.</p>

</div>
</div>

### verifyKernelArgs() {#ae7305a512e55d80b14d67b050431b598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verifyKernelArgs (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp; Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a>.</p>

</div>
</div>

### verifyScalar() {#adb326324bd6393f795b5abd681bc7ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verifyScalar (<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp; Node, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6">msgpack::Type</a> SKind, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;)&gt; verifyValue={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a>.</p>

</div>
</div>

### verifyScalarEntry() {#a4272cca24a6430995110f7dae8dadecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::verifyScalarEntry (<a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a> &amp; MapNode, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, bool Required, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6">msgpack::Type</a> SKind, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;)&gt; verifyValue={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Strict {#aa6ab0e642057a60ae65e6f996677bef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::HSAMD::V3::MetadataVerifier::Strict</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/amdgpumetadataverifier-h">AMDGPUMetadataVerifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/binaryformat/amdgpumetadataverifier-cpp">AMDGPUMetadataVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
