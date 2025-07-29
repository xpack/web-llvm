---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineregion
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineRegion` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MachineRegion { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">llvm/CodeGen/MachineRegionInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regionbase">RegionBase&lt;Tr&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A single entry single exit <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="/web-llvm/docs/api/classes/llvm/regionbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d64ce76e0b7eb3e270176ce2bda8c2e">MachineRegion</a> (MachineBasicBlock *Entry, MachineBasicBlock *Exit, MachineRegionInfo *RI, MachineDominatorTree *DT, MachineRegion *Parent=nullptr)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5393822b0a24ef8f502545f961e04e92">~MachineRegion</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4a7fc96dfd57fc010f366befa598b92">operator==</a> (const MachineRegionNode &amp;RN) const</td>
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


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineRegion() {#a9d64ce76e0b7eb3e270176ce2bda8c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegion::MachineRegion (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Entry, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Exit, <a href="/web-llvm/docs/api/classes/llvm/machineregioninfo">MachineRegionInfo</a> * RI, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/machineregion">MachineRegion</a> * Parent=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregioninfo-cpp">MachineRegionInfo.cpp</a>.</p>


<p>References <a href="#a9d64ce76e0b7eb3e270176ce2bda8c2e">MachineRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/regionbase/#aaeb673bce3fe39f6a04bcc5cb93c83c8">llvm::RegionBase&lt; RegionTraits&lt; MachineFunction &gt; &gt;::RegionBase</a>.</p>


<p>Referenced by <a href="#a9d64ce76e0b7eb3e270176ce2bda8c2e">MachineRegion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineRegion() {#a5393822b0a24ef8f502545f961e04e92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegion::~MachineRegion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#ab4a7fc96dfd57fc010f366befa598b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegion::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregionnode">MachineRegionNode</a> &amp; RN)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregioninfo-cpp">MachineRegionInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
