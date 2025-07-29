---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/arm/parsedbranchprotection
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ParsedBranchProtection` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::ARM::ParsedBranchProtection { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">llvm/TargetParser/ARMTargetParserCommon.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e5e7202ba1a7a8355419862f8547284">Scope</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f55e978885a211453af3d8a13e7734">Key</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53a0bdd73a8ea02d5beedd5a13830a7">BranchTargetEnforcement</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80541d2dcd95a13077fed311763401c">BranchProtectionPAuthLR</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0319e2db9148f8b1957b7f6a0bef54c1">GuardedControlStack</a></td>
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


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">ARMTargetParserCommon.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### BranchProtectionPAuthLR {#ad80541d2dcd95a13077fed311763401c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::ParsedBranchProtection::BranchProtectionPAuthLR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">ARMTargetParserCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#abe6ae134b151b2a3091884f7e3b049e7">llvm::ARM::parseBranchProtection</a>.</p>

</div>
</div>

### BranchTargetEnforcement {#ac53a0bdd73a8ea02d5beedd5a13830a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::ParsedBranchProtection::BranchTargetEnforcement</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">ARMTargetParserCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#abe6ae134b151b2a3091884f7e3b049e7">llvm::ARM::parseBranchProtection</a>.</p>

</div>
</div>

### GuardedControlStack {#a0319e2db9148f8b1957b7f6a0bef54c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::ParsedBranchProtection::GuardedControlStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">ARMTargetParserCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#abe6ae134b151b2a3091884f7e3b049e7">llvm::ARM::parseBranchProtection</a>.</p>

</div>
</div>

### Key {#a06f55e978885a211453af3d8a13e7734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::ARM::ParsedBranchProtection::Key</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">ARMTargetParserCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#abe6ae134b151b2a3091884f7e3b049e7">llvm::ARM::parseBranchProtection</a>.</p>

</div>
</div>

### Scope {#a5e5e7202ba1a7a8355419862f8547284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::ARM::ParsedBranchProtection::Scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">ARMTargetParserCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#abe6ae134b151b2a3091884f7e3b049e7">llvm::ARM::parseBranchProtection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparsercommon-h">ARMTargetParserCommon.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
