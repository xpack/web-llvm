---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/unwindopcodeassembler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UnwindOpcodeAssembler` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::UnwindOpcodeAssembler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">Target/ARM/MCTargetDesc/ARMUnwindOpAsm.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cbc33e72f7717cad6605161dfa8ffa2">UnwindOpcodeAssembler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ef9e820b750c101003978da4aaf66ae">Reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the unwind opcode assembler. <a href="#a9ef9e820b750c101003978da4aaf66ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7097755198a26d87ceca07a753983baf">setPersonality</a> (const MCSymbol *Per)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the personality. <a href="#a7097755198a26d87ceca07a753983baf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58246f7f59a6e6eac2f10a03464707a9">EmitRegSave</a> (uint32_t RegSave)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit unwind opcodes for .save directives. <a href="#a58246f7f59a6e6eac2f10a03464707a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1741b5416a0fd627aa23c0eb0d7c7b">EmitVFPRegSave</a> (uint32_t VFPRegSave)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit unwind opcodes for .vsave directives. <a href="#a3d1741b5416a0fd627aa23c0eb0d7c7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1564384a9331059dce31b7164158bc97">EmitSetSP</a> (uint16_t Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit unwind opcodes to copy address from source register to $sp. <a href="#a1564384a9331059dce31b7164158bc97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7efb1fa1b6df24d22533caf41162d46b">EmitSPOffset</a> (int64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit unwind opcodes to add $sp with an offset. <a href="#a7efb1fa1b6df24d22533caf41162d46b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1cfb912a74d848789c9edb810753f17">EmitRaw</a> (const SmallVectorImpl&lt; uint8_t &gt; &amp;Opcodes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit unwind raw opcodes. <a href="#ab1cfb912a74d848789c9edb810753f17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab94eb68723fc4c7d5378c1fbac1c194b">Finalize</a> (unsigned &amp;PersonalityIndex, SmallVectorImpl&lt; uint8_t &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the unwind opcode sequence for emitBytes() <a href="#ab94eb68723fc4c7d5378c1fbac1c194b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bed19443b5e43c6e356f6620615877">EmitInt8</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe64120a5838ce7565dd5e5e0dfcd78">EmitInt16</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd9c87c1dbcf24c38e262b8265ab316">emitBytes</a> (const uint8_t *Opcode, size_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint8_t, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a752ed0501f694f14d7f1f3799b3af69c">Ops</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c55e50908f654bf736d3953a688d4c7">OpBegins</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a262145f00eec27a326c76e8b5bc0acb8">HasPersonality</a> = false</td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UnwindOpcodeAssembler() {#a4cbc33e72f7717cad6605161dfa8ffa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::UnwindOpcodeAssembler::UnwindOpcodeAssembler ()</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### EmitRaw() {#ab1cfb912a74d848789c9edb810753f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::UnwindOpcodeAssembler::EmitRaw (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; Opcodes)</td>
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

<p>Emit unwind raw opcodes.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### EmitRegSave() {#a58246f7f59a6e6eac2f10a03464707a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnwindOpcodeAssembler::EmitRegSave (uint32_t RegSave)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit unwind opcodes for .save directives.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaaefcc1e6af568599a852b5a634db6f75d">llvm::ARM::EHABI::UNWIND_OPCODE_POP_RA_AUTH_CODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaa9a03bf3866742ac1b888bee3b12b36f6">llvm::ARM::EHABI::UNWIND_OPCODE_POP_REG_MASK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaaf6b4129defb78ab1e27de68558cdad7e">llvm::ARM::EHABI::UNWIND_OPCODE_POP_REG_MASK_R4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaa0a91a90150205dd8f3e3f3e5d764e34c">llvm::ARM::EHABI::UNWIND_OPCODE_POP_REG_RANGE_R4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaae8ab15ac55a28dc3b1954b3159a9cd61">llvm::ARM::EHABI::UNWIND_OPCODE_POP_REG_RANGE_R4_R14</a>.</p>

</div>
</div>

### EmitSetSP() {#a1564384a9331059dce31b7164158bc97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnwindOpcodeAssembler::EmitSetSP (uint16_t Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit unwind opcodes to copy address from source register to $sp.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaafb874bc6779295f8e3e6b4cecfd406bf">llvm::ARM::EHABI::UNWIND_OPCODE_SET_VSP</a>.</p>

</div>
</div>

### EmitSPOffset() {#a7efb1fa1b6df24d22533caf41162d46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnwindOpcodeAssembler::EmitSPOffset (int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit unwind opcodes to add $sp with an offset.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaa88017af7551328f81fac3ba62cd12258">llvm::ARM::EHABI::UNWIND_OPCODE_DEC_VSP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaaa5fb6fa61b25402c5a11953776e94069">llvm::ARM::EHABI::UNWIND_OPCODE_INC_VSP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaac7fec19e4c3252adc0fe1c56e7517633">llvm::ARM::EHABI::UNWIND_OPCODE_INC_VSP_ULEB128</a>.</p>

</div>
</div>

### EmitVFPRegSave() {#a3d1741b5416a0fd627aa23c0eb0d7c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnwindOpcodeAssembler::EmitVFPRegSave (uint32_t VFPRegSave)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit unwind opcodes for .vsave directives.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a37c1fdede126353d80c3753dfe06f3c7">llvm::bit_width</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d92de57590536d2f254fe5e903e3372">llvm::countl_one</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaaf3a1f5132396873d78fb4e5810ad2f82">llvm::ARM::EHABI::UNWIND_OPCODE_POP_VFP_REG_RANGE_FSTMFDD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a391979058f7394854c8e99446129c5aaa943f3a70dcab5069c2f70c1745031102">llvm::ARM::EHABI::UNWIND_OPCODE_POP_VFP_REG_RANGE_FSTMFDD_D16</a>.</p>

</div>
</div>

### Finalize() {#ab94eb68723fc4c7d5378c1fbac1c194b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnwindOpcodeAssembler::Finalize (unsigned &amp; PersonalityIndex, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the unwind opcode sequence for emitBytes()</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a7b99cf0c7d83797700266fe3d55872e7a74f0546618adde7fd3715e03c8af0d09">llvm::ARM::EHABI::AEABI_UNWIND_CPP_PR0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a7b99cf0c7d83797700266fe3d55872e7a091a1026c8394033f84acddfe2ad596d">llvm::ARM::EHABI::AEABI_UNWIND_CPP_PR1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/ehabi/#a7b99cf0c7d83797700266fe3d55872e7a95314429fa79c010af353b0a2c8f75d6">llvm::ARM::EHABI::NUM_PERSONALITY_INDEX</a> and <a href="#a9ef9e820b750c101003978da4aaf66ae">Reset</a>.</p>

</div>
</div>

### Reset() {#a9ef9e820b750c101003978da4aaf66ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::UnwindOpcodeAssembler::Reset ()</td>
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

<p>Reset the unwind opcode assembler.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>


<p>Referenced by <a href="#ab94eb68723fc4c7d5378c1fbac1c194b">Finalize</a>.</p>

</div>
</div>

### setPersonality() {#a7097755198a26d87ceca07a753983baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::UnwindOpcodeAssembler::setPersonality (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Per)</td>
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

<p>Set the personality.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitBytes() {#a2fd9c87c1dbcf24c38e262b8265ab316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::UnwindOpcodeAssembler::emitBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Opcode, size_t Size)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>

</div>
</div>

### EmitInt16() {#adfe64120a5838ce7565dd5e5e0dfcd78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::UnwindOpcodeAssembler::EmitInt16 (unsigned Opcode)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>

</div>
</div>

### EmitInt8() {#ad1bed19443b5e43c6e356f6620615877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::UnwindOpcodeAssembler::EmitInt8 (unsigned Opcode)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasPersonality {#a262145f00eec27a326c76e8b5bc0acb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::UnwindOpcodeAssembler::HasPersonality = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>

</div>
</div>

### OpBegins {#a7c55e50908f654bf736d3953a688d4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 8&gt; llvm::UnwindOpcodeAssembler::OpBegins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>

</div>
</div>

### Ops {#a752ed0501f694f14d7f1f3799b3af69c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint8_t, 32&gt; llvm::UnwindOpcodeAssembler::Ops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-cpp">ARMUnwindOpAsm.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armunwindopasm-h">ARMUnwindOpAsm.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
