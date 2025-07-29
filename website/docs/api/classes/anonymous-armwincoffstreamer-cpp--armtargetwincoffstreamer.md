---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMTargetWinCOFFStreamer` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer">ARMTargetStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5e47cdb6b79545371ed6176cd82911">ARMTargetWinCOFFStreamer</a> (llvm::MCStreamer &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594c8ef9e4cb028240dd4f66909aaeed">emitARMWinCFIAllocStack</a> (unsigned Size, bool Wide) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ea9e0acb4e8fab83e69caaa8f7b463">emitARMWinCFISaveRegMask</a> (unsigned Mask, bool Wide) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ad2ae6ed7aeea271d21de265110d73">emitARMWinCFISaveSP</a> (unsigned Reg) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34106951b54d5291cc435db0817b4ae7">emitARMWinCFISaveFRegs</a> (unsigned First, unsigned Last) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0242acadfe2f06ccb04d5b34674f311">emitARMWinCFISaveLR</a> (unsigned Offset) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a5b841afcea044cefa812e4cd4b30d5">emitARMWinCFIPrologEnd</a> (bool Fragment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65400bd926ed5e6d68088ee140af543d">emitARMWinCFINop</a> (bool Wide) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c29f346d739538a5d4d77e4f3820cdf">emitARMWinCFIEpilogStart</a> (unsigned Condition) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab470d8aa53480de68554a22812342ca7">emitARMWinCFIEpilogEnd</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a500230f7718f64e6e7fb171d38ef2372">emitARMWinCFICustom</a> (unsigned Opcode) override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b77364c8aa77b4f1f006f9ce7a4c14">emitARMWinUnwindCode</a> (unsigned UnwindCode, int Reg, int Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac86e91aaecdc60e2c17b6df2f60ab9">InEpilogCFI</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc4e5cff88f7011bbcf5303414c0543f">CurrentEpilog</a> = nullptr</td>
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


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMTargetWinCOFFStreamer() {#a5f5e47cdb6b79545371ed6176cd82911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::ARMTargetWinCOFFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">llvm::MCStreamer</a> &amp; S)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a25f600d55ab2c40ef824e52fc51c7940">llvm::ARMTargetStreamer::ARMTargetStreamer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac1ee5ea7ae4ec8d5b6ecbb3070b34e20">llvm::createARMObjectTargetWinCOFFStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitARMWinCFIAllocStack() {#a594c8ef9e4cb028240dd4f66909aaeed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIAllocStack (unsigned Size, bool Wide)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea3380a84eb648ca0ee05c138bb4e59c48">llvm::Win64EH::UOP_AllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94">llvm::Win64EH::UOP_AllocLarge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166">llvm::Win64EH::UOP_AllocSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea60b7e4a0be5c03d2ec6fadf011036552">llvm::Win64EH::UOP_WideAllocHuge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eac65a3d732455e48352266b753b1a90e6">llvm::Win64EH::UOP_WideAllocLarge</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2b7d6e82d9ab706a4ed67f4214efefe5">llvm::Win64EH::UOP_WideAllocMedium</a>.</p>

</div>
</div>

### emitARMWinCFICustom() {#a500230f7718f64e6e7fb171d38ef2372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFICustom (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea459472d4a0e3cd23f8448702e0f84325">llvm::Win64EH::UOP_Custom</a>.</p>

</div>
</div>

### emitARMWinCFIEpilogEnd() {#ab470d8aa53480de68554a22812342ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIEpilogEnd ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#abc5baba59c735eeb15bdef969b458794ae91e8abe0e8b6cf6fffe4fae46d1d01e">Epilog</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a7364f28eaaef25fb43890373f3792a01">llvm::WinEH::FrameInfo::EpilogMap</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a22c0c4f7c23db94945872dfe14fa32bc">llvm::WinEH::FrameInfo::Function</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a35cb7e6f64b7406816d5bc30cfc5d27a">llvm::WinEH::Instruction::Operation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea2c1e73f96a3eb49c02ea5e2c23582c60">llvm::Win64EH::UOP_EndNop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7">llvm::Win64EH::UOP_Nop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea122a936a6e1d854afed8b6ecc54faec0">llvm::Win64EH::UOP_WideEndNop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea055da35948045301bbb791b59fda7948">llvm::Win64EH::UOP_WideNop</a>.</p>

</div>
</div>

### emitARMWinCFIEpilogStart() {#a3c29f346d739538a5d4d77e4f3820cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIEpilogStart (unsigned Condition)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a7364f28eaaef25fb43890373f3792a01">llvm::WinEH::FrameInfo::EpilogMap</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>.</p>

</div>
</div>

### emitARMWinCFINop() {#a65400bd926ed5e6d68088ee140af543d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFINop (bool Wide)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7">llvm::Win64EH::UOP_Nop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea055da35948045301bbb791b59fda7948">llvm::Win64EH::UOP_WideNop</a>.</p>

</div>
</div>

### emitARMWinCFIPrologEnd() {#a0a5b841afcea044cefa812e4cd4b30d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFIPrologEnd (bool Fragment)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a3776ac8b64dde3227ee94d7901096cfb">llvm::WinEH::FrameInfo::Fragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a10bcb4d81ba20e479977a46859383c93">llvm::WinEH::FrameInfo::Instructions</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo/#a61dd603885e6fe75a133f68362c82c2d">llvm::WinEH::FrameInfo::PrologEnd</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd">llvm::Win64EH::UOP_End</a>.</p>

</div>
</div>

### emitARMWinCFISaveFRegs() {#a34106951b54d5291cc435db0817b4ae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFISaveFRegs (unsigned First, unsigned Last)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea35a232904dcd802033ea03851f7838b2">llvm::Win64EH::UOP_SaveFRegD0D15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eaf6e5478d3596267b0b6340a415e93f45">llvm::Win64EH::UOP_SaveFRegD16D31</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eab3bc8467e0977cc0f9426032256c5540">llvm::Win64EH::UOP_SaveFRegD8D15</a>.</p>

</div>
</div>

### emitARMWinCFISaveLR() {#ae0242acadfe2f06ccb04d5b34674f311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFISaveLR (unsigned Offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eabe9ce7cc4dc6542d11f840cc8e51a6f6">llvm::Win64EH::UOP_SaveLR</a>.</p>

</div>
</div>

### emitARMWinCFISaveRegMask() {#ac7ea9e0acb4e8fab83e69caaa8f7b463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFISaveRegMask (unsigned Mask, bool Wide)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea727048e9b2c0d090a5797b13e1c5c827">llvm::Win64EH::UOP_SaveRegMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea16cfe12e38096341a1a273a904ef0d31">llvm::Win64EH::UOP_SaveRegsR4R7LR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21eae14d06b7d47c095bd18678232bfd5148">llvm::Win64EH::UOP_WideSaveRegMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea444955343875efc999ae15232dca1d16">llvm::Win64EH::UOP_WideSaveRegsR4R11LR</a>.</p>

</div>
</div>

### emitARMWinCFISaveSP() {#ad5ad2ae6ed7aeea271d21de265110d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinCFISaveSP (unsigned Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/win64eh/#a6147069c8d9fb51bcbc2ec9ff447a21ea73e5f2ff29af4a2c90c8711b8a6780e4">llvm::Win64EH::UOP_SaveSP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitARMWinUnwindCode() {#a81b77364c8aa77b4f1f006f9ce7a4c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::emitARMWinUnwindCode (unsigned UnwindCode, int Reg, int Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentEpilog {#adc4e5cff88f7011bbcf5303414c0543f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::CurrentEpilog = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>

</div>
</div>

### InEpilogCFI {#aaac86e91aaecdc60e2c17b6df2f60ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::InEpilogCFI = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armwincoffstreamer-cpp">ARMWinCOFFStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
