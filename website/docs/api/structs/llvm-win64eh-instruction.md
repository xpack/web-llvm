---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/win64eh/instruction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Instruction` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::Win64EH::Instruction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">llvm/MC/MCWin64EH.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6162447a68b07ae0c7ac50e0b2152c57">PushNonVol</a> (MCSymbol *L, unsigned Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae298191528a9da3e5cee7ca83be92ef6">Alloc</a> (MCSymbol *L, unsigned Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6259bc5c7b25a62271edf4c462d30c91">PushMachFrame</a> (MCSymbol *L, bool Code)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd5a7e265ee374819dc4039e2fae01e">SaveNonVol</a> (MCSymbol *L, unsigned Reg, unsigned Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a240406f5d649c95da66daf851f871c01">SaveXMM</a> (MCSymbol *L, unsigned Reg, unsigned Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">WinEH::Instruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef7a47bd8f81f98a227fd2b620677aac">SetFPReg</a> (MCSymbol *L, unsigned Reg, unsigned Off)</td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### Alloc() {#ae298191528a9da3e5cee7ca83be92ef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinEH::Instruction llvm::Win64EH::Instruction::Alloc (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad9bb2bc90c804c28497604ae91e27bd7">llvm::MCStreamer::emitWinCFIAllocStack</a>.</p>

</div>
</div>

### PushMachFrame() {#a6259bc5c7b25a62271edf4c462d30c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinEH::Instruction llvm::Win64EH::Instruction::PushMachFrame (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, bool Code)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabb99442c04b0287262dcb4395886bd7e">llvm::Win64EH::UOP_PushMachFrame</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4c579bc3d70f8f348c3ddf8224a31220">llvm::MCStreamer::emitWinCFIPushFrame</a>.</p>

</div>
</div>

### PushNonVol() {#a6162447a68b07ae0c7ac50e0b2152c57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinEH::Instruction llvm::Win64EH::Instruction::PushNonVol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaae7e62281f7ac9af9a2305acf345e30c">llvm::Win64EH::UOP_PushNonVol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a1d0c21ad8ad54697f00aab2c37d77e25">llvm::MCStreamer::emitWinCFIPushReg</a>.</p>

</div>
</div>

### SaveNonVol() {#acdd5a7e265ee374819dc4039e2fae01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinEH::Instruction llvm::Win64EH::Instruction::SaveNonVol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Reg, unsigned Offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea4e13ff9dd4e7826d85bbdd2671d1aa24">llvm::Win64EH::UOP_SaveNonVol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea20d9d4f8ad4a32c577c3c3af202df151">llvm::Win64EH::UOP_SaveNonVolBig</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9a30cc0783819b780c3e357162b90aec">llvm::MCStreamer::emitWinCFISaveReg</a>.</p>

</div>
</div>

### SaveXMM() {#a240406f5d649c95da66daf851f871c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinEH::Instruction llvm::Win64EH::Instruction::SaveXMM (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Reg, unsigned Offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea7e9f984ddcbc105b772e19e4b095cffc">llvm::Win64EH::UOP_SaveXMM128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea91d84d5df0879f33b1770710b7705c7d">llvm::Win64EH::UOP_SaveXMM128Big</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5755faab671780e6c1abcaa95f05fe0b">llvm::MCStreamer::emitWinCFISaveXMM</a>.</p>

</div>
</div>

### SetFPReg() {#aef7a47bd8f81f98a227fd2b620677aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinEH::Instruction llvm::Win64EH::Instruction::SetFPReg (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * L, unsigned Reg, unsigned Off)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea6a008a4f48e5b08f2f1ea75159e5fee3">llvm::Win64EH::UOP_SetFPReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acd1f092159870d525f916e3296341d92">llvm::MCStreamer::emitWinCFISetFrame</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
