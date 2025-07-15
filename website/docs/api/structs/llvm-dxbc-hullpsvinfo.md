---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dxbc/hullpsvinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `HullPSVInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::dxbc::HullPSVInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">llvm/BinaryFormat/DXContainer.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30b1ad207b06f03ca27a2093ed469815">swapBytes</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af984dc292371e17cdef6b41720983872">InputControlPointCount</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98602553bb248b228689a255134c59ce">OutputControlPointCount</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8b809e555302b775b636809a9fe683">TessellatorDomain</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13393193076b82684fa8179dc1d50381">TessellatorOutputPrimitive</a></td>
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


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### swapBytes() {#a30b1ad207b06f03ca27a2093ed469815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dxbc::HullPSVInfo::swapBytes ()</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>References <a href="#af984dc292371e17cdef6b41720983872">InputControlPointCount</a>, <a href="#a98602553bb248b228689a255134c59ce">OutputControlPointCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>, <a href="#afd8b809e555302b775b636809a9fe683">TessellatorDomain</a> and <a href="#a13393193076b82684fa8179dc1d50381">TessellatorOutputPrimitive</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### InputControlPointCount {#af984dc292371e17cdef6b41720983872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxbc::HullPSVInfo::InputControlPointCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#aef40b4410af614b5a4771ef2dfc5df47">llvm::DXContainerYAML::PSVInfo::mapInfoForVersion</a> and <a href="#a30b1ad207b06f03ca27a2093ed469815">swapBytes</a>.</p>

</div>
</div>

### OutputControlPointCount {#a98602553bb248b228689a255134c59ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxbc::HullPSVInfo::OutputControlPointCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#aef40b4410af614b5a4771ef2dfc5df47">llvm::DXContainerYAML::PSVInfo::mapInfoForVersion</a> and <a href="#a30b1ad207b06f03ca27a2093ed469815">swapBytes</a>.</p>

</div>
</div>

### TessellatorDomain {#afd8b809e555302b775b636809a9fe683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxbc::HullPSVInfo::TessellatorDomain</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#aef40b4410af614b5a4771ef2dfc5df47">llvm::DXContainerYAML::PSVInfo::mapInfoForVersion</a> and <a href="#a30b1ad207b06f03ca27a2093ed469815">swapBytes</a>.</p>

</div>
</div>

### TessellatorOutputPrimitive {#a13393193076b82684fa8179dc1d50381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dxbc::HullPSVInfo::TessellatorOutputPrimitive</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#aef40b4410af614b5a4771ef2dfc5df47">llvm::DXContainerYAML::PSVInfo::mapInfoForVersion</a> and <a href="#a30b1ad207b06f03ca27a2093ed469815">swapBytes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">DXContainer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
