---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/lohinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LOHInfo` Struct Reference

<p>State tracked per register. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct LOHInfo { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5">MCLOHType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0965ae588ba0cc9e5771339308611f9c">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"Best" type of LOH possible. <a href="#a0965ae588ba0cc9e5771339308611f9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7411c64a5c36e7dbe3536f81a5036878">IsCandidate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Possible LOH candidate. <a href="#a7411c64a5c36e7dbe3536f81a5036878">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6fb6984a6a36ff23c2f654d7432781">OneUser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Found exactly one user (yet). <a href="#a3b6fb6984a6a36ff23c2f654d7432781">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453908066162ea515d123e1a555f84be">MultiUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Found multiple users. <a href="#a453908066162ea515d123e1a555f84be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8684aa539f7587aa0584669e61f16a3">MI0</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>First instruction involved in the LOH. <a href="#af8684aa539f7587aa0584669e61f16a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8622219f1ae97a2925ad94e3d358c679">MI1</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Second instruction involved in the LOH (if any). <a href="#a8622219f1ae97a2925ad94e3d358c679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65017a46ee187d10ea5a8499e64a8766">LastADRP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Last ADRP in same register. <a href="#a65017a46ee187d10ea5a8499e64a8766">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>State tracked per register.</p>


<p>The main algorithm walks backwards over a basic block maintaining this datastructure for each tracked general purpose register.</p>


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### IsCandidate {#a7411c64a5c36e7dbe3536f81a5036878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LOHInfo::IsCandidate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Possible LOH candidate.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a125ac2ddb35b7776daf1ed49fc6a5ad6">handleMiddleInst</a>.</p>

</div>
</div>

### LastADRP {#a65017a46ee187d10ea5a8499e64a8766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* LOHInfo::LastADRP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Last ADRP in same register.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a125ac2ddb35b7776daf1ed49fc6a5ad6">handleMiddleInst</a>.</p>

</div>
</div>

### MI0 {#af8684aa539f7587aa0584669e61f16a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* LOHInfo::MI0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>First instruction involved in the LOH.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>

</div>
</div>

### MI1 {#a8622219f1ae97a2925ad94e3d358c679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr* LOHInfo::MI1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Second instruction involved in the LOH (if any).</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a125ac2ddb35b7776daf1ed49fc6a5ad6">handleMiddleInst</a>.</p>

</div>
</div>

### MultiUsers {#a453908066162ea515d123e1a555f84be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LOHInfo::MultiUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Found multiple users.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>.</p>

</div>
</div>

### OneUser {#a3b6fb6984a6a36ff23c2f654d7432781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LOHInfo::OneUser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Found exactly one user (yet).</p>

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a125ac2ddb35b7776daf1ed49fc6a5ad6">handleMiddleInst</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a4bee2d3457dd2d22962d67c658644125">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::runOnMachineFunction</a>.</p>

</div>
</div>

### Type {#a0965ae588ba0cc9e5771339308611f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCLOHType LOHInfo::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>"Best" type of LOH possible.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a125ac2ddb35b7776daf1ed49fc6a5ad6">handleMiddleInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
