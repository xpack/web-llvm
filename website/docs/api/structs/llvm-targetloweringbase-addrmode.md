---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetloweringbase/addrmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AddrMode` Struct Reference

<p>This represents an addressing mode of: BaseGV + BaseOffs + BaseReg + Scale*ScaleReg + ScalableOffset*vscale If BaseGV is null, there is no BaseGV. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TargetLoweringBase::AddrMode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2478465e9b443e243e992d22f2e5db9">AddrMode</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d775e3fd8ebcd0941d1e12cbfccda3d">BaseGV</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a115ffe6d615735fbe8b1bf31877565ba">BaseOffs</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8868c35de6c36dc0d57e84f256c4ffde">HasBaseReg</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea7d02f0e4b0c1d37d6986ec9f7f5c0">Scale</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5d77356a7fa4c176fd2835f8fb00cb">ScalableOffset</a> = 0</td>
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

## Description {#details}

<p>This represents an addressing mode of: BaseGV + BaseOffs + BaseReg + Scale*ScaleReg + ScalableOffset*vscale If BaseGV is null, there is no BaseGV.</p>


<p>If BaseOffs is zero, there is no base offset. If HasBaseReg is false, there is no base register. If Scale is zero, there is no ScaleReg. Scale of 1 indicates a reg with no scale. If ScalableOffset is zero, there is no scalable offset.</p>


<p>Definition at line 2816 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AddrMode() {#ad2478465e9b443e243e992d22f2e5db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLoweringBase::AddrMode::AddrMode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BaseGV {#a2d775e3fd8ebcd0941d1e12cbfccda3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue* llvm::TargetLoweringBase::AddrMode::BaseGV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a0899ff53f18fd319b08cd613b140f969">llvm::AArch64TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6bab4676a9047479dd222ae4d6e9dff0">llvm::ARMTTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a7caed3bceadafb0aaa8416b84ddb9c87">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4c06fd8823711b9a3a748faaeea2c40c">llvm::X86TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae854a8e8c09efe0960eaae718304b77d">llvm::AArch64TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a14ba388c0893657958340f94a164faa9">llvm::ARMTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a78e02356de3219cd3bc8f36d924f7d40">llvm::AVRTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aea9d34adacdbb687e929238b3c197152">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a2f0eada972883c6e2ad49334be57b141">llvm::HexagonTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a97827ae16535ba63871ef5a031909264">llvm::LoongArchTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ab1fbe8bf005228a2fea5deb173b08e47">llvm::NVPTXTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a7747bd26b2eea5f7c32012e5dcdbd61a">llvm::PPCTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a493000ba3c662fc283ecccf2392e4393">llvm::RISCVTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a6d3e878a08fe1d62c3aad96a158d1a94">llvm::SITargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a6e0cffce6bc5c85b42dbf14f60534a1e">llvm::SystemZTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afa3aef362a1dcff57193d4e6a54f7044">llvm::TargetLoweringBase::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad1a79970217e7be886648d06d5fded3c">llvm::X86TargetLowering::isLegalAddressingMode</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a46c27b50bb571224cf575e6334ca9cf1">llvm::XCoreTargetLowering::isLegalAddressingMode</a>.</p>

</div>
</div>

### BaseOffs {#a115ffe6d615735fbe8b1bf31877565ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::TargetLoweringBase::AddrMode::BaseOffs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a0899ff53f18fd319b08cd613b140f969">llvm::AArch64TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6bab4676a9047479dd222ae4d6e9dff0">llvm::ARMTTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a7caed3bceadafb0aaa8416b84ddb9c87">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4c06fd8823711b9a3a748faaeea2c40c">llvm::X86TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae854a8e8c09efe0960eaae718304b77d">llvm::AArch64TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a14ba388c0893657958340f94a164faa9">llvm::ARMTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a78e02356de3219cd3bc8f36d924f7d40">llvm::AVRTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aea9d34adacdbb687e929238b3c197152">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a2f0eada972883c6e2ad49334be57b141">llvm::HexagonTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a97827ae16535ba63871ef5a031909264">llvm::LoongArchTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ab1fbe8bf005228a2fea5deb173b08e47">llvm::NVPTXTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a7747bd26b2eea5f7c32012e5dcdbd61a">llvm::PPCTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a493000ba3c662fc283ecccf2392e4393">llvm::RISCVTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a6d3e878a08fe1d62c3aad96a158d1a94">llvm::SITargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a6e0cffce6bc5c85b42dbf14f60534a1e">llvm::SystemZTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afa3aef362a1dcff57193d4e6a54f7044">llvm::TargetLoweringBase::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad1a79970217e7be886648d06d5fded3c">llvm::X86TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a46c27b50bb571224cf575e6334ca9cf1">llvm::XCoreTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a94fdd48878bedb4f53de2f18efcf640f">llvm::SITargetLowering::isLegalFlatAddressingMode</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3acff99aeccfa086e7fbef44df8c0ce1">llvm::CombinerHelper::matchPtrAddImmedChain</a>.</p>

</div>
</div>

### HasBaseReg {#a8868c35de6c36dc0d57e84f256c4ffde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetLoweringBase::AddrMode::HasBaseReg = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a0899ff53f18fd319b08cd613b140f969">llvm::AArch64TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6bab4676a9047479dd222ae4d6e9dff0">llvm::ARMTTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a7caed3bceadafb0aaa8416b84ddb9c87">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4c06fd8823711b9a3a748faaeea2c40c">llvm::X86TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae854a8e8c09efe0960eaae718304b77d">llvm::AArch64TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a14ba388c0893657958340f94a164faa9">llvm::ARMTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a78e02356de3219cd3bc8f36d924f7d40">llvm::AVRTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aea9d34adacdbb687e929238b3c197152">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a97827ae16535ba63871ef5a031909264">llvm::LoongArchTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ab1fbe8bf005228a2fea5deb173b08e47">llvm::NVPTXTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a7747bd26b2eea5f7c32012e5dcdbd61a">llvm::PPCTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a493000ba3c662fc283ecccf2392e4393">llvm::RISCVTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a6d3e878a08fe1d62c3aad96a158d1a94">llvm::SITargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afa3aef362a1dcff57193d4e6a54f7044">llvm::TargetLoweringBase::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad1a79970217e7be886648d06d5fded3c">llvm::X86TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a46c27b50bb571224cf575e6334ca9cf1">llvm::XCoreTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a221b01b74bd3f7ddd1779947901f5eec">llvm::ARMTargetLowering::isLegalT1ScaledAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a1b478e338eb3e2c6ab20ac7462896c58">llvm::ARMTargetLowering::isLegalT2ScaledAddressingMode</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3acff99aeccfa086e7fbef44df8c0ce1">llvm::CombinerHelper::matchPtrAddImmedChain</a>.</p>

</div>
</div>

### ScalableOffset {#aac5d77356a7fa4c176fd2835f8fb00cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::TargetLoweringBase::AddrMode::ScalableOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a0899ff53f18fd319b08cd613b140f969">llvm::AArch64TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6bab4676a9047479dd222ae4d6e9dff0">llvm::ARMTTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a7caed3bceadafb0aaa8416b84ddb9c87">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4c06fd8823711b9a3a748faaeea2c40c">llvm::X86TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae854a8e8c09efe0960eaae718304b77d">llvm::AArch64TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aea9d34adacdbb687e929238b3c197152">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a493000ba3c662fc283ecccf2392e4393">llvm::RISCVTargetLowering::isLegalAddressingMode</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afa3aef362a1dcff57193d4e6a54f7044">llvm::TargetLoweringBase::isLegalAddressingMode</a>.</p>

</div>
</div>

### Scale {#a8ea7d02f0e4b0c1d37d6986ec9f7f5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::TargetLoweringBase::AddrMode::Scale = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a0899ff53f18fd319b08cd613b140f969">llvm::AArch64TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6bab4676a9047479dd222ae4d6e9dff0">llvm::ARMTTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a7caed3bceadafb0aaa8416b84ddb9c87">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4c06fd8823711b9a3a748faaeea2c40c">llvm::X86TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae854a8e8c09efe0960eaae718304b77d">llvm::AArch64TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/arctargetlowering/#aa92aa97d7c1a7783e53b9a3baac05b03">llvm::ARCTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a14ba388c0893657958340f94a164faa9">llvm::ARMTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a78e02356de3219cd3bc8f36d924f7d40">llvm::AVRTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aea9d34adacdbb687e929238b3c197152">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a2f0eada972883c6e2ad49334be57b141">llvm::HexagonTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a97827ae16535ba63871ef5a031909264">llvm::LoongArchTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ab1fbe8bf005228a2fea5deb173b08e47">llvm::NVPTXTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a7747bd26b2eea5f7c32012e5dcdbd61a">llvm::PPCTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a493000ba3c662fc283ecccf2392e4393">llvm::RISCVTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a6d3e878a08fe1d62c3aad96a158d1a94">llvm::SITargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a6e0cffce6bc5c85b42dbf14f60534a1e">llvm::SystemZTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afa3aef362a1dcff57193d4e6a54f7044">llvm::TargetLoweringBase::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad1a79970217e7be886648d06d5fded3c">llvm::X86TargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a46c27b50bb571224cf575e6334ca9cf1">llvm::XCoreTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a94fdd48878bedb4f53de2f18efcf640f">llvm::SITargetLowering::isLegalFlatAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a221b01b74bd3f7ddd1779947901f5eec">llvm::ARMTargetLowering::isLegalT1ScaledAddressingMode</a> and <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a1b478e338eb3e2c6ab20ac7462896c58">llvm::ARMTargetLowering::isLegalT2ScaledAddressingMode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
