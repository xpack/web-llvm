---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonblockranges/instrindexmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstrIndexMap` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonBlockRanges::InstrIndexMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">Target/Hexagon/HexagonBlockRanges.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04aed01f583320c91f305dcb8bbee36">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0573722c851dd8e2fd4bf1468f66313">InstrIndexMap</a> (MachineBasicBlock &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adab5a1f825e30f33ac209ddd0c11bba9">getInstr</a> (IndexType Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825be59a5a6d9036398e5fbc096e4c20">getIndex</a> (MachineInstr *MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51cfad5f9dc05280cd998a3ef76c0ec9">getBlock</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7085a311776097c887efdf4653d50462">getPrevIndex</a> (IndexType Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682ee592460d7a33e7448c87c136d0aa">getNextIndex</a> (IndexType Idx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b68cca827f2ca38674ab66bbd007172">replaceInstr</a> (MachineInstr *OldMI, MachineInstr *NewMI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5934b9053bb427b199b63f5deb6dde6d">First</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f90b39d64006f65ffb1a2dd4da13d9e">Last</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99755d436cee79a95da636479ef6955e">Block</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc2e28b8f96bd901f3a18d6817ab3d85">Map</a></td>
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


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#ae04aed01f583320c91f305dcb8bbee36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/instrindexmap">InstrIndexMap</a> &amp; Map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>Reference <a href="#ad0573722c851dd8e2fd4bf1468f66313">InstrIndexMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstrIndexMap() {#ad0573722c851dd8e2fd4bf1468f66313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonBlockRanges::InstrIndexMap::InstrIndexMap (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76ae5936d5e6ec85f7faa7a42b40008783d">llvm::HexagonBlockRanges::IndexType::First</a>, <a href="#a5934b9053bb427b199b63f5deb6dde6d">First</a>, <a href="#a825be59a5a6d9036398e5fbc096e4c20">getIndex</a>, <a href="#a7f90b39d64006f65ffb1a2dd4da13d9e">Last</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76af51a19e2bdd0598f566d27e90b554c22">llvm::HexagonBlockRanges::IndexType::None</a>.</p>


<p>Referenced by <a href="#ae04aed01f583320c91f305dcb8bbee36">operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBlock() {#a51cfad5f9dc05280cd998a3ef76c0ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock &amp; llvm::HexagonBlockRanges::InstrIndexMap::getBlock ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonblockranges/#a4271a72d1e29d700427b7cb039771a5f">llvm::HexagonBlockRanges::computeDeadMap</a>.</p>

</div>
</div>

### getIndex() {#a825be59a5a6d9036398e5fbc096e4c20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonBlockRanges::IndexType HexagonBlockRanges::InstrIndexMap::getIndex (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76af51a19e2bdd0598f566d27e90b554c22">llvm::HexagonBlockRanges::IndexType::None</a>.</p>


<p>Referenced by <a href="#ad0573722c851dd8e2fd4bf1468f66313">InstrIndexMap</a>.</p>

</div>
</div>

### getInstr() {#adab5a1f825e30f33ac209ddd0c11bba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * HexagonBlockRanges::InstrIndexMap::getInstr (<a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getNextIndex() {#a682ee592460d7a33e7448c87c136d0aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonBlockRanges::IndexType HexagonBlockRanges::InstrIndexMap::getNextIndex (<a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76a1b7a0dcb5cb1c69fbc86f7d7b89a95bd">llvm::HexagonBlockRanges::IndexType::Entry</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76a8dfa0bea6fb1d85fb8cbbdf79a6a4903">llvm::HexagonBlockRanges::IndexType::Exit</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76ae5936d5e6ec85f7faa7a42b40008783d">llvm::HexagonBlockRanges::IndexType::First</a>, <a href="#a7f90b39d64006f65ffb1a2dd4da13d9e">Last</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76af51a19e2bdd0598f566d27e90b554c22">llvm::HexagonBlockRanges::IndexType::None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonblockranges/#a4271a72d1e29d700427b7cb039771a5f">llvm::HexagonBlockRanges::computeDeadMap</a>.</p>

</div>
</div>

### getPrevIndex() {#a7085a311776097c887efdf4653d50462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonBlockRanges::IndexType HexagonBlockRanges::InstrIndexMap::getPrevIndex (<a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76a1b7a0dcb5cb1c69fbc86f7d7b89a95bd">llvm::HexagonBlockRanges::IndexType::Entry</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76a8dfa0bea6fb1d85fb8cbbdf79a6a4903">llvm::HexagonBlockRanges::IndexType::Exit</a>, <a href="#a5934b9053bb427b199b63f5deb6dde6d">First</a>, <a href="#a7f90b39d64006f65ffb1a2dd4da13d9e">Last</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76af51a19e2bdd0598f566d27e90b554c22">llvm::HexagonBlockRanges::IndexType::None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonblockranges/#a4271a72d1e29d700427b7cb039771a5f">llvm::HexagonBlockRanges::computeDeadMap</a>.</p>

</div>
</div>

### replaceInstr() {#a2b68cca827f2ca38674ab66bbd007172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonBlockRanges::InstrIndexMap::replaceInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OldMI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * NewMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### First {#a5934b9053bb427b199b63f5deb6dde6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexType llvm::HexagonBlockRanges::InstrIndexMap::First</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>Referenced by <a href="#a7085a311776097c887efdf4653d50462">getPrevIndex</a> and <a href="#ad0573722c851dd8e2fd4bf1468f66313">InstrIndexMap</a>.</p>

</div>
</div>

### Last {#a7f90b39d64006f65ffb1a2dd4da13d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexType llvm::HexagonBlockRanges::InstrIndexMap::Last</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>Referenced by <a href="#a682ee592460d7a33e7448c87c136d0aa">getNextIndex</a>, <a href="#a7085a311776097c887efdf4653d50462">getPrevIndex</a> and <a href="#ad0573722c851dd8e2fd4bf1468f66313">InstrIndexMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Block {#a99755d436cee79a95da636479ef6955e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock&amp; llvm::HexagonBlockRanges::InstrIndexMap::Block</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>

</div>
</div>

### Map {#adc2e28b8f96bd901f3a18d6817ab3d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;IndexType,MachineInstr*&gt; llvm::HexagonBlockRanges::InstrIndexMap::Map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
