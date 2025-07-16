---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dxbc/psv/v0/resourcebindinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ResourceBindInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::dxbc::PSV::v0::ResourceBindInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">llvm/BinaryFormat/DXContainer.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v2/resourcebindinfo">ResourceBindInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acec2dd66ed6991c4cbbe9e7364893dcc">swapBytes</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#a77b9940b9167ea2e78639b1e12892e3b">ResourceType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923f4538a2768e33b30e6bfda5b5a37c">Type</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67931fe6d83e4878a495a847f301d55e">Space</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ed27603668df25640fcfe8de9a1d28">LowerBound</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454d819d3a4c1a3e2981d614d74dceca">UpperBound</a></td>
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


<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### swapBytes() {#acec2dd66ed6991c4cbbe9e7364893dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxbc::PSV::v0::ResourceBindInfo::swapBytes ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>References <a href="#ad9ed27603668df25640fcfe8de9a1d28">LowerBound</a>, <a href="#a67931fe6d83e4878a495a847f301d55e">Space</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>, <a href="#a923f4538a2768e33b30e6bfda5b5a37c">Type</a> and <a href="#a454d819d3a4c1a3e2981d614d74dceca">UpperBound</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v2/resourcebindinfo/#a02d5cb26d17bda1914510120d3cb9eed">llvm::dxbc::PSV::v2::ResourceBindInfo::swapBytes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LowerBound {#ad9ed27603668df25640fcfe8de9a1d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxbc::PSV::v0::ResourceBindInfo::LowerBound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5cb422d9af45ce1249f0a09b1805d16a/#ab48301a67608f48551f5bccb93cf4402">llvm::yaml::MappingTraits&lt; DXContainerYAML::ResourceBindInfo &gt;::mapping</a> and <a href="#acec2dd66ed6991c4cbbe9e7364893dcc">swapBytes</a>.</p>

</div>
</div>

### Space {#a67931fe6d83e4878a495a847f301d55e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxbc::PSV::v0::ResourceBindInfo::Space</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5cb422d9af45ce1249f0a09b1805d16a/#ab48301a67608f48551f5bccb93cf4402">llvm::yaml::MappingTraits&lt; DXContainerYAML::ResourceBindInfo &gt;::mapping</a> and <a href="#acec2dd66ed6991c4cbbe9e7364893dcc">swapBytes</a>.</p>

</div>
</div>

### Type {#a923f4538a2768e33b30e6bfda5b5a37c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceType llvm::dxbc::PSV::v0::ResourceBindInfo::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5cb422d9af45ce1249f0a09b1805d16a/#ab48301a67608f48551f5bccb93cf4402">llvm::yaml::MappingTraits&lt; DXContainerYAML::ResourceBindInfo &gt;::mapping</a> and <a href="#acec2dd66ed6991c4cbbe9e7364893dcc">swapBytes</a>.</p>

</div>
</div>

### UpperBound {#a454d819d3a4c1a3e2981d614d74dceca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxbc::PSV::v0::ResourceBindInfo::UpperBound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5cb422d9af45ce1249f0a09b1805d16a/#ab48301a67608f48551f5bccb93cf4402">llvm::yaml::MappingTraits&lt; DXContainerYAML::ResourceBindInfo &gt;::mapping</a> and <a href="#acec2dd66ed6991c4cbbe9e7364893dcc">swapBytes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
