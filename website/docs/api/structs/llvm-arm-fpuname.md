---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/arm/fpuname
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FPUName` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::ARM::FPUName { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">llvm/TargetParser/ARMTargetParser.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a77090956d8fde91064aa5a775eb364">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7ec47cecec400dff032e3b34a3630129">FPUKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312e74cf4ce9e778aaf3f1bcc7ead76d">ID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/arm/#a43b54cec9a9179040fc3e98b4a763fc3">FPUVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9421e38dee3194c89006ecf3f0c18228">FPUVer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/arm/#a61003d3f7c772d4d60bfb9ed9e3c5427">NeonSupportLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa5260cbae9c072c87aecfdcc40896ce">NeonSupport</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad67c067d2f90e51b2412f3c1117661b3">FPURestriction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725739d3acc705903464c90d0fb7772c">Restriction</a></td>
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


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">ARMTargetParser.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### FPUVer {#a9421e38dee3194c89006ecf3f0c18228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPUVersion llvm::ARM::FPUName::FPUVer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">ARMTargetParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp/#adae37657f827f24d47e8d69bc6a32b2b">findDoublePrecisionFPU</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp/#a40651a426e93c95af35349e804ff01e8">findSinglePrecisionFPU</a>.</p>

</div>
</div>

### ID {#a312e74cf4ce9e778aaf3f1bcc7ead76d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPUKind llvm::ARM::FPUName::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">ARMTargetParser.h</a>.</p>

</div>
</div>

### Name {#a9a77090956d8fde91064aa5a775eb364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::ARM::FPUName::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">ARMTargetParser.h</a>.</p>

</div>
</div>

### NeonSupport {#aaa5260cbae9c072c87aecfdcc40896ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NeonSupportLevel llvm::ARM::FPUName::NeonSupport</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">ARMTargetParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp/#adae37657f827f24d47e8d69bc6a32b2b">findDoublePrecisionFPU</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp/#a40651a426e93c95af35349e804ff01e8">findSinglePrecisionFPU</a>.</p>

</div>
</div>

### Restriction {#a725739d3acc705903464c90d0fb7772c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPURestriction llvm::ARM::FPUName::Restriction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">ARMTargetParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp/#adae37657f827f24d47e8d69bc6a32b2b">findDoublePrecisionFPU</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp/#a40651a426e93c95af35349e804ff01e8">findSinglePrecisionFPU</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">ARMTargetParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
