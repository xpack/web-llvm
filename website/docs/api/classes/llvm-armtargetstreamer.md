---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armtargetstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMTargetStreamer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ARMTargetStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific streamer interface. <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armtargetasmstreamer">ARMTargetAsmStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armtargetelfstreamer">ARMTargetELFStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer">ARMTargetWinCOFFStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f600d55ab2c40ef824e52fc51c7940">ARMTargetStreamer</a> (MCStreamer &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1655ccaf8d05c56295292107ab293bfc">~ARMTargetStreamer</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cabf2bb78bfc2e766cbb05c3eeef424">emitFnStart</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247d5a2deb0fce93c25015a673c97e20">emitFnEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac934dd0c337b6250ac4c7201bf98121f">emitCantUnwind</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720a1619127865deb96960381cd5378c">emitPersonality</a> (const MCSymbol *Personality)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a339fdc70a5fe821f34cbaa4c0d11a8e7">emitPersonalityIndex</a> (unsigned Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83149cad598845c0936408bc21646c06">emitHandlerData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eef07d52435d62777b2ee9f2bb6d8fa">emitSetFP</a> (MCRegister FpReg, MCRegister SpReg, int64_t Offset=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b24c1310884ed826e2a20069b0396f8">emitMovSP</a> (MCRegister Reg, int64_t Offset=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0214f3bda1c223d51e536308f3c36ff">emitPad</a> (int64_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd5251753290a740360018c30bb7827">emitRegSave</a> (const SmallVectorImpl&lt; MCRegister &gt; &amp;RegList, bool isVector)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a087ea52d8224d56676b4d9d4991e5433">emitUnwindRaw</a> (int64_t StackOffset, const SmallVectorImpl&lt; uint8_t &gt; &amp;Opcodes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6867d10b2f78a4b0a1ddc30cb152170f">switchVendor</a> (StringRef Vendor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae22e6e88e18778afaff210613d77f426">emitAttribute</a> (unsigned Attribute, unsigned Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415c480e96a50b4f87c0cd7194fa5cc7">emitTextAttribute</a> (unsigned Attribute, StringRef String)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eeb7cee648baa71718622ae5a1a34a4">emitIntTextAttribute</a> (unsigned Attribute, unsigned IntValue, StringRef StringValue="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac57eb560abdf514d313690de66cceb4a">emitFPU</a> (ARM::FPUKind FPU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7f67e3f87641d78037c61630263bb9b">emitArch</a> (ARM::ArchKind Arch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab4bb4eb059fffc1127b9deb65122bf">emitArchExtension</a> (uint64_t ArchExt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7245dfb3e78f51e165602c9e3dbf8a6f">emitObjectArch</a> (ARM::ArchKind Arch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b7b6be8c77b055cf79259a4af7ff0c">emitTargetAttributes</a> (const MCSubtargetInfo &amp;STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the build attributes that only depend on the hardware that we expect. <a href="#a17b7b6be8c77b055cf79259a4af7ff0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23be80c54dc3188ec583ba0f28ff997b">finishAttributeSection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35fb67d88bdb317b8d0ed132e9403414">emitInst</a> (uint32_t Inst, char Suffix='\0')</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22985dc7b9d850ab4256c46a8e34870f">annotateTLSDescriptorSequence</a> (const MCSymbolRefExpr *SRE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac7bd541c1116d9b31b663b64f6bd3f8">emitThumbSet</a> (MCSymbol *Symbol, const MCExpr *Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe2d27d9a2926aa9036a2424e924242">emitConstantPools</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425a2a6a58a8289dc30694c76ae6536d">emitARMWinCFIAllocStack</a> (unsigned Size, bool Wide)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54bfa2e01028f5b6ac0bd2bad34a30a8">emitARMWinCFISaveRegMask</a> (unsigned Mask, bool Wide)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30635e5a0a508c1770d7bbacf1516320">emitARMWinCFISaveSP</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0f91d28881ca3d363b264a01501687d">emitARMWinCFISaveFRegs</a> (unsigned First, unsigned Last)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a397ecab3815400c2b77bbf5d972f131d">emitARMWinCFISaveLR</a> (unsigned Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656d09c0dd8cc4a716187bb9dcf3d01a">emitARMWinCFIPrologEnd</a> (bool Fragment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6235ded9ed2a075be365e55cbf650f0">emitARMWinCFINop</a> (bool Wide)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8a12f4266c57ffd0327cef8e121097">emitARMWinCFIEpilogStart</a> (unsigned Condition)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d779bcdd91c2c13bb69f8118737ec4">emitARMWinCFIEpilogEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51a1c5a8bda3c41dc5ef0058ce59aa50">emitARMWinCFICustom</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e1cb197db87a8dc1af4596efc680373">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset any state between object emissions, i.e. <a href="#a1e1cb197db87a8dc1af4596efc680373">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73892053d64aff715825c4e09d464f4a">addConstantPoolEntry</a> (const MCExpr *, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback used to implement the ldr= pseudo. <a href="#a73892053d64aff715825c4e09d464f4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0fe64e72b37b9e3271e6841ed006b67">emitCurrentConstantPool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback used to implement the .ltorg directive. <a href="#ae0fe64e72b37b9e3271e6841ed006b67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/assemblerconstantpools">AssemblerConstantPools</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab041eeb4ad0ffc9d51e31638feaf800f">ConstantPools</a></td>
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


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMTargetStreamer() {#a25f600d55ab2c40ef824e52fc51c7940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMTargetStreamer::ARMTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#acfff4f9a518231ee043200a694fcbafa">llvm::MCTargetStreamer::MCTargetStreamer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armtargetasmstreamer/#a96b4bfb064959ee08937b92ccf339193">anonymous{ARMELFStreamer.cpp}::ARMTargetAsmStreamer::ARMTargetAsmStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armtargetelfstreamer/#a8b4aa3019b467a5ea6a0db81cbe071ce">anonymous{ARMELFStreamer.cpp}::ARMTargetELFStreamer::ARMTargetELFStreamer</a> and <a href="/web-llvm/docs/api/classes/anonymous-armwincoffstreamer-cpp-/armtargetwincoffstreamer/#a5f5e47cdb6b79545371ed6176cd82911">anonymous{ARMWinCOFFStreamer.cpp}::ARMTargetWinCOFFStreamer::ARMTargetWinCOFFStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ARMTargetStreamer() {#a1655ccaf8d05c56295292107ab293bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMTargetStreamer::~ARMTargetStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addConstantPoolEntry() {#a73892053d64aff715825c4e09d464f4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * ARMTargetStreamer::addConstantPoolEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback used to implement the ldr= pseudo.</p>


<p>Add a new entry to the constant pool for the current section and return an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> that can be used to refer to the constant pool location.</p>


<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>

</div>
</div>

### annotateTLSDescriptorSequence() {#a22985dc7b9d850ab4256c46a8e34870f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::annotateTLSDescriptorSequence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * SRE)</td>
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



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitArch() {#af7f67e3f87641d78037c61630263bb9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitArch (<a href="/web-llvm/docs/api/namespaces/llvm/arm/#a251fc5156cdf171e44a7a4463609fe8a">ARM::ArchKind</a> Arch)</td>
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



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitArchExtension() {#a3ab4bb4eb059fffc1127b9deb65122bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitArchExtension (uint64_t ArchExt)</td>
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



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="#a17b7b6be8c77b055cf79259a4af7ff0c">emitTargetAttributes</a>.</p>

</div>
</div>

### emitARMWinCFIAllocStack() {#a425a2a6a58a8289dc30694c76ae6536d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFIAllocStack (unsigned Size, bool Wide)</td>
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



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitARMWinCFICustom() {#a51a1c5a8bda3c41dc5ef0058ce59aa50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFICustom (unsigned Opcode)</td>
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



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitARMWinCFIEpilogEnd() {#a63d779bcdd91c2c13bb69f8118737ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFIEpilogEnd ()</td>
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



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitARMWinCFIEpilogStart() {#ade8a12f4266c57ffd0327cef8e121097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFIEpilogStart (unsigned Condition)</td>
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



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitARMWinCFINop() {#ae6235ded9ed2a075be365e55cbf650f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFINop (bool Wide)</td>
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



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitARMWinCFIPrologEnd() {#a656d09c0dd8cc4a716187bb9dcf3d01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFIPrologEnd (bool Fragment)</td>
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



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitARMWinCFISaveFRegs() {#ad0f91d28881ca3d363b264a01501687d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFISaveFRegs (unsigned First, unsigned Last)</td>
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



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitARMWinCFISaveLR() {#a397ecab3815400c2b77bbf5d972f131d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFISaveLR (unsigned Offset)</td>
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



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitARMWinCFISaveRegMask() {#a54bfa2e01028f5b6ac0bd2bad34a30a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFISaveRegMask (unsigned Mask, bool Wide)</td>
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



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitARMWinCFISaveSP() {#a30635e5a0a508c1770d7bbacf1516320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitARMWinCFISaveSP (unsigned Reg)</td>
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



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitAttribute() {#ae22e6e88e18778afaff210613d77f426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitAttribute (unsigned Attribute, unsigned Value)</td>
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



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a9f2d9f34828769634981f82c4977d930">llvm::ARMAsmPrinter::emitEndOfAsmFile</a> and <a href="#a17b7b6be8c77b055cf79259a4af7ff0c">emitTargetAttributes</a>.</p>

</div>
</div>

### emitCantUnwind() {#ac934dd0c337b6250ac4c7201bf98121f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitCantUnwind ()</td>
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



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armexception/#aabdec7bf5c7d63c648b278d130aca3c2">llvm::ARMException::endFunction</a>.</p>

</div>
</div>

### emitConstantPools() {#aebe2d27d9a2926aa9036a2424e924242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitConstantPools ()</td>
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



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>

</div>
</div>

### emitCurrentConstantPool() {#ae0fe64e72b37b9e3271e6841ed006b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitCurrentConstantPool ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback used to implement the .ltorg directive.</p>


<p>Emit contents of constant pool for the current section.</p>


<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>

</div>
</div>

### emitFnEnd() {#a247d5a2deb0fce93c25015a673c97e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitFnEnd ()</td>
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



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armexception/#aabdec7bf5c7d63c648b278d130aca3c2">llvm::ARMException::endFunction</a>.</p>

</div>
</div>

### emitFnStart() {#a6cabf2bb78bfc2e766cbb05c3eeef424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitFnStart ()</td>
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



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armexception/#ad22476d7463665ca4c25d7fde2824398">llvm::ARMException::beginFunction</a>.</p>

</div>
</div>

### emitFPU() {#ac57eb560abdf514d313690de66cceb4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitFPU (<a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7ec47cecec400dff032e3b34a3630129">ARM::FPUKind</a> FPU)</td>
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



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="#a17b7b6be8c77b055cf79259a4af7ff0c">emitTargetAttributes</a>.</p>

</div>
</div>

### emitHandlerData() {#a83149cad598845c0936408bc21646c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitHandlerData ()</td>
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



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armexception/#aabdec7bf5c7d63c648b278d130aca3c2">llvm::ARMException::endFunction</a>.</p>

</div>
</div>

### emitInst() {#a35fb67d88bdb317b8d0ed132e9403414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitInst (uint32_t Inst, char Suffix='\0')</td>
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



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af94e84eca402017c9ce57b7b4c4104e3">llvm::MCStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#aae0550266742eb14bea527b1e6f6300a">llvm::MCTargetStreamer::getStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a135c23c5281985d2eb038733b46a11b6">llvm::MCAsmInfo::isLittleEndian</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### emitIntTextAttribute() {#a9eeb7cee648baa71718622ae5a1a34a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitIntTextAttribute (unsigned Attribute, unsigned IntValue, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StringValue="")</td>
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



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitMovSP() {#a2b24c1310884ed826e2a20069b0396f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitMovSP (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, int64_t Offset=0)</td>
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



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitObjectArch() {#a7245dfb3e78f51e165602c9e3dbf8a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitObjectArch (<a href="/web-llvm/docs/api/namespaces/llvm/arm/#a251fc5156cdf171e44a7a4463609fe8a">ARM::ArchKind</a> Arch)</td>
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



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitPad() {#ae0214f3bda1c223d51e536308f3c36ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitPad (int64_t Offset)</td>
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



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitPersonality() {#a720a1619127865deb96960381cd5378c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitPersonality (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Personality)</td>
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



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armexception/#aabdec7bf5c7d63c648b278d130aca3c2">llvm::ARMException::endFunction</a>.</p>

</div>
</div>

### emitPersonalityIndex() {#a339fdc70a5fe821f34cbaa4c0d11a8e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitPersonalityIndex (unsigned Index)</td>
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



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitRegSave() {#a5dd5251753290a740360018c30bb7827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitRegSave (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &gt; &amp; RegList, bool isVector)</td>
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



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitSetFP() {#a1eef07d52435d62777b2ee9f2bb6d8fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitSetFP (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> FpReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SpReg, int64_t Offset=0)</td>
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



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitTargetAttributes() {#a17b7b6be8c77b055cf79259a4af7ff0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitTargetAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the build attributes that only depend on the hardware that we expect.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6ac1e2a90ed1ea61e5a9c94403450ffcf0">llvm::ARMBuildAttrs::ABI_HardFP_use</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6a80cebeb60c235348741536710cd9d899">llvm::ARMBuildAttrs::Advanced_SIMD_arch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae0cf1eb000ae6051e4582b5ed5035b53a3ae3f73491a4bb1f066fb9c088c817a4">llvm::ARM::AEK_DSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae0cf1eb000ae6051e4582b5ed5035b53a5f1f438b9f21a7398c0a3cb309de236b">llvm::ARM::AEK_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae0cf1eb000ae6051e4582b5ed5035b53a702b3dbbbb0644da5761177f22603798">llvm::ARM::AEK_HWDIVARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae0cf1eb000ae6051e4582b5ed5035b53a140c0bf1b5db93ee5f2d3e9c8925645c">llvm::ARM::AEK_HWDIVTHUMB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae0cf1eb000ae6051e4582b5ed5035b53a305d16015304a00ca3762781644539cc">llvm::ARM::AEK_SIMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10dabb5d7c315c1217100b7c29cf19d64ca7">llvm::ARMBuildAttrs::AllowBTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da7aa7c494b5c5945a0528dd569525b5f9">llvm::ARMBuildAttrs::AllowDIVExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10daa5cedd7d339a70606b857fc2c498e0fb">llvm::ARMBuildAttrs::Allowed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10daeeb461f37b62346d689cdae6447b87f9">llvm::ARMBuildAttrs::AllowHPFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da94b7e68702888dee4af6bbb4b9abce3b">llvm::ARMBuildAttrs::AllowMP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da96679293f4823264d6d5c5da8adfda30">llvm::ARMBuildAttrs::AllowMVEInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da1f9a10e7d17b4b0ba4b1f61ad757adb1">llvm::ARMBuildAttrs::AllowMVEIntegerAndFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da043049fbf433d3cb7d96ae4f4d51d23b">llvm::ARMBuildAttrs::AllowNeonARMv8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da4ca3c026c11f6705d2dffb25b814909c">llvm::ARMBuildAttrs::AllowNeonARMv8_1a</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10daf4a50dec80a0d2ac905327c48a289c4a">llvm::ARMBuildAttrs::AllowPAC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10daa0ebd5a6f13bc2b521c53c4c79ecc5ce">llvm::ARMBuildAttrs::AllowThumb32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da061b8e858a32e88e3ae5ae77d491d64c">llvm::ARMBuildAttrs::AllowThumbDerived</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da222232593de0262f234323874d198d21">llvm::ARMBuildAttrs::AllowTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da1043823aeb4de304dbc3eb4e4bae13c4">llvm::ARMBuildAttrs::AllowTZVirtualization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da8edb37eae51094e2edd43e941de79a85">llvm::ARMBuildAttrs::AllowVirtualization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a5af12287edb52a422e35d2d962d8675ea4055efd7b4a72be9ddaaaaee12014983">llvm::ARMBuildAttrs::ApplicationProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6a32c829f47c3280a9c081198fc927f3c2">llvm::ARMBuildAttrs::ARM_ISA_use</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6a95179de49813a1def4a7bf42db5ef7b1">llvm::ARMBuildAttrs::BTI_extension</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6a0279c11a681fcdb5d127fe510b794dae">llvm::ARMBuildAttrs::CPU_arch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6adc480a9854461c31275e13b17a431956">llvm::ARMBuildAttrs::CPU_arch_profile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6ae72f5987483e0286f0225c32b27e4441">llvm::ARMBuildAttrs::CPU_name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6a2c3301699af6d702cd84e3e67bd8fd38">llvm::ARMBuildAttrs::CPU_unaligned_access</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6a9d2b627f8f8a450a467befb8eee43f8d">llvm::ARMBuildAttrs::DIV_use</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6ac41e338bd0ebad18ef47c0ef3dd35ddc">llvm::ARMBuildAttrs::DSP_extension</a>, <a href="#a3ab4bb4eb059fffc1127b9deb65122bf">emitArchExtension</a>, <a href="#ae22e6e88e18778afaff210613d77f426">emitAttribute</a>, <a href="#ac57eb560abdf514d313690de66cceb4a">emitFPU</a>, <a href="#a415c480e96a50b4f87c0cd7194fa5cc7">emitTextAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6a46d720d15e2beb148b6dc0cbaaf323a8">llvm::ARMBuildAttrs::FP_HP_extension</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp/#aaf6e4a38fe1be7aab9c4e702d9dbb396">getArchForCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10dad73ca706d2ba8083b257c8aa589ebf2b">llvm::ARMBuildAttrs::HardFPSinglePrecision</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp/#a482a1a87ca8a29083e5c88eac796ed62">isV8M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a5af12287edb52a422e35d2d962d8675eadd3aa668a94bc1798b0f619d2745e51a">llvm::ARMBuildAttrs::MicroControllerProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6aa83f5b2511c84a5080ea185a6f315f05">llvm::ARMBuildAttrs::MPextension_use</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6a7b8e76f3d836b46eb71f9d78074a8513">llvm::ARMBuildAttrs::MVE_arch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a1df37811cd3e1ed487bf9db640daa10da64723843712f68698dfe9f085d6bd630">llvm::ARMBuildAttrs::Not_Allowed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6ae4ba9f321f9347ac72e200b6c0537ace">llvm::ARMBuildAttrs::PAC_extension</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a5af12287edb52a422e35d2d962d8675eaf8af73196e31a66825ea7db1fd3e49e8">llvm::ARMBuildAttrs::RealTimeProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="#a6867d10b2f78a4b0a1ddc30cb152170f">switchVendor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6add6bd85d9bcdd64df76ff3ce8ff59282">llvm::ARMBuildAttrs::THUMB_ISA_use</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6a3a1243e2ca97bc9f4e4e197693c145d3">llvm::ARMBuildAttrs::Virtualization_use</a>.</p>

</div>
</div>

### emitTextAttribute() {#a415c480e96a50b4f87c0cd7194fa5cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitTextAttribute (unsigned Attribute, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
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



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="#a17b7b6be8c77b055cf79259a4af7ff0c">emitTargetAttributes</a>.</p>

</div>
</div>

### emitThumbSet() {#aac7bd541c1116d9b31b663b64f6bd3f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitThumbSet (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### emitUnwindRaw() {#a087ea52d8224d56676b4d9d4991e5433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::emitUnwindRaw (int64_t StackOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; Opcodes)</td>
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



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### finishAttributeSection() {#a23be80c54dc3188ec583ba0f28ff997b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::finishAttributeSection ()</td>
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



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a9f2d9f34828769634981f82c4977d930">llvm::ARMAsmPrinter::emitEndOfAsmFile</a>.</p>

</div>
</div>

### reset() {#a1e1cb197db87a8dc1af4596efc680373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::reset ()</td>
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

<p>Reset any state between object emissions, i.e.</p>


<p>the equivalent of <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a>'s reset method.</p>


<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>

</div>
</div>

### switchVendor() {#a6867d10b2f78a4b0a1ddc30cb152170f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMTargetStreamer::switchVendor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Vendor)</td>
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



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Referenced by <a href="#a17b7b6be8c77b055cf79259a4af7ff0c">emitTargetAttributes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ConstantPools {#ab041eeb4ad0ffc9d51e31638feaf800f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AssemblerConstantPools&gt; llvm::ARMTargetStreamer::ConstantPools</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">MCStreamer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
