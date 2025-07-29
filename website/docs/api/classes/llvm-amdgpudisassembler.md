---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpudisassembler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPUDisassembler` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUDisassembler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">Target/AMDGPU/Disassembler/AMDGPUDisassembler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Superclass for all disassemblers. <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OpWidthTy { <a href="#ab8355dd4c437a99c65c3d9f3b6f5101a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852783bf1f53ae8e8e22a3042759f90b">AMDGPUDisassembler</a> (const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx, MCInstrInfo const *MCII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94d3b563775fcf320d994bcd8aa646ce">~AMDGPUDisassembler</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3391e8d688dabff24f81458e8867e450">setABIVersion</a> (unsigned Version) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ELF-specific, set the ABI version from the object header. <a href="#a3391e8d688dabff24f81458e8867e450">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a> (MCInst &amp;MI, uint64_t &amp;Size, ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address, raw_ostream &amp;CS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the disassembly of a single instruction. <a href="#ad9305ad45a7db970a0a198791bea136a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d28a91d7aca8ef06fa3e2533047f0b">getRegClassName</a> (unsigned RegClassID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a> (unsigned int RegId) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10982f41862673ec4aa270b0eef58a7b">createRegOperand</a> (unsigned RegClassID, unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af564aa8a41fb212e8dfc8856ef35c871">createSRegOperand</a> (unsigned SRegClassID, unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a7e8470c4be479dbcf6ac32a977b8b3">createVGPR16Operand</a> (unsigned RegIdx, bool IsHi) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b147cf1557182f62cf46de5ea9b5061">errOperand</a> (unsigned V, const Twine &amp;ErrMsg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename InsnType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae4a6148a52bc05698e9890ee276e6b1">tryDecodeInst</a> (const uint8_t *Table, MCInst &amp;MI, InsnType Inst, uint64_t Address, raw_ostream &amp;Comments) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename InsnType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8d70063859b434ed950708dc5d2434b">tryDecodeInst</a> (const uint8_t *Table1, const uint8_t *Table2, MCInst &amp;MI, InsnType Inst, uint64_t Address, raw_ostream &amp;Comments) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec69108aa44466b2b0dfdd41a76aab1">onSymbolStart</a> (SymbolInfoTy &amp;Symbol, uint64_t &amp;Size, ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to perform separate target specific disassembly for a particular symbol. <a href="#afec69108aa44466b2b0dfdd41a76aab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66aa742680260d77ebab20536c828c17">decodeKernelDescriptor</a> (StringRef KdName, ArrayRef&lt; uint8_t &gt; Bytes, uint64_t KdAddress) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec298d8a742a9519e6dc0903f822f2b">decodeKernelDescriptorDirective</a> (DataExtractor::Cursor &amp;Cursor, ArrayRef&lt; uint8_t &gt; Bytes, raw_string_ostream &amp;KdStream) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a717ebce0af699c0b264313d0cb21e2">decodeCOMPUTE_PGM_RSRC1</a> (uint32_t FourByteBuffer, raw_string_ostream &amp;KdStream) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode as directives that handle COMPUTE_PGM_RSRC1. <a href="#a1a717ebce0af699c0b264313d0cb21e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341ce9a65b287f8033788c0bb12d8fa3">decodeCOMPUTE_PGM_RSRC2</a> (uint32_t FourByteBuffer, raw_string_ostream &amp;KdStream) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode as directives that handle COMPUTE_PGM_RSRC2. <a href="#a341ce9a65b287f8033788c0bb12d8fa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de6bde5116ff125fb02491b47586333">decodeCOMPUTE_PGM_RSRC3</a> (uint32_t FourByteBuffer, raw_string_ostream &amp;KdStream) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode as directives that handle COMPUTE_PGM_RSRC3. <a href="#a7de6bde5116ff125fb02491b47586333">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcaab7e1e2ab1a6575d41a5e3fe99db">convertEXPInst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951e9da312d0c74b6988e59280910007">convertVINTERPInst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ebec5cbc0a8238828d0527a06568f1">convertFMAanyK</a> (MCInst &amp;MI, int ImmLitIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2160759492c85b0f23cc8e5d9538f6">convertSDWAInst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb4b1dd5155bf0f31e8d74cdd8ccc6c">convertMAIInst</a> (MCInst &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>f8f6f4 instructions have different pseudos depending on the used formats. <a href="#acdb4b1dd5155bf0f31e8d74cdd8ccc6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5924dbd31504014961bf4324546da2cc">convertDPP8Inst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5f0e6bc47c72961a9a05d307d6400f1">convertMIMGInst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688f4832464547c17012a58790863c53">convertVOP3DPPInst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2662661417cf1a8f0b242b84853829f">convertVOP3PDPPInst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2021d83fb89da51586187868e0ba649d">convertVOPCDPPInst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a074a4f039b95fd6ecd9a199e3db42097">convertVOPC64DPPInst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4974310fb906d87e0b82ea333101d33c">convertMacDPPInst</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dc51b29f05105e3ce97ba5b40087dcb">convertTrue16OpSel</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a49c0ccc7c9aa0fe2692b60975f8ba3">getVgprClassId</a> (const OpWidthTy Width) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc52c96e46c682e3e109f4a3ddef37b">getAgprClassId</a> (const OpWidthTy Width) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1c21284d55eedc91c4a3969626b6f1a">getSgprClassId</a> (const OpWidthTy Width) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adae4bf9c24a1f20e4ad36d42620f6e7a">getTtmpClassId</a> (const OpWidthTy Width) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc1d16f7c74d8204bf3ab1f4d5c0998">decodeMandatoryLiteralConstant</a> (unsigned Imm) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c8699483ef63f1164acdd8a35f49066">decodeLiteralConstant</a> (bool ExtendFP64) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f8e99199a1dc95b1fd2a144aa79a6c">decodeSrcOp</a> (const OpWidthTy Width, unsigned Val, bool MandatoryLiteral=false, unsigned ImmWidth=0, AMDGPU::OperandSemantics Sema=AMDGPU::OperandSemantics::INT) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a> (const OpWidthTy Width, unsigned Val, bool MandatoryLiteral=false, unsigned ImmWidth=0, AMDGPU::OperandSemantics Sema=AMDGPU::OperandSemantics::INT) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ae2e98f9553b452f8c2b5107a8cb16a">decodeVOPDDstYOp</a> (MCInst &amp;Inst, unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865ae0d33ec9cd2b21d7b55470ac58d0">decodeSpecialReg32</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168a8034e9e01207fb71a39bde063d7f">decodeSpecialReg64</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318ce4a6802b51ada47c71f8692132ab">decodeSpecialReg96Plus</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a> (const OpWidthTy Width, unsigned Val, unsigned ImmWidth, AMDGPU::OperandSemantics Sema) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdccfd26f12d23c635188ff714e99c8d">decodeSDWASrc16</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f73e787f141094d0aa638db8653ec8">decodeSDWASrc32</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9481f68151f53dba0f1e3416819e6e26">decodeSDWAVopcDst</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfa93abf00f463c320ff9b5fb940583">decodeBoolReg</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682a5e3b08aa66c35ff6853e832695c3">decodeSplitBarrier</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8610c5c7c16e772286ed071dd699c9">decodeDpp8FI</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b42038a61a3c4b1880eea5331cdb44">decodeVersionImm</a> (unsigned Imm) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae852f28eb2685d5dc30c78308011af7f">getTTmpIdx</a> (unsigned Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b498d343f513db217828dd650ae22c">getMCII</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7297f920e9ff94394d81719b75080ecb">isVI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c9f9be5e439d07443ad92852b18f06">isGFX9</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2163e267c5265155b8e5ac1f9306fdc">isGFX90A</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c6ec88b07c8f5dcfecacabe3007ecf">isGFX9Plus</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee62e9882c0b90536eaa08027bbfef7">isGFX10</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515f1867e36cdffa566f9faa967bf2ad">isGFX10Plus</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347423b9fcc60e76ff31a10a90bd5840">isGFX11</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5cd2cf12e0610bc99b7c894f677b2f8">isGFX11Plus</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e19f604d742a99d805737f3d21ff62">isGFX12</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a606a1a89df2407a17f844127bca7e">isGFX12Plus</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bbaf8f762d31654b6a7580783122f5">hasArchitectedFlatScratch</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b52b6c12bfcdcdede7a84beba3bbe10">hasKernargPreload</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae75794f911e166bcea94523957bdec07">isMacDPP</a> (MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa51102a50cd2ee003b77179625bb13e0">createConstantSymbolExpr</a> (StringRef Id, int64_t Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  &gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753d2143002854b389075e7b60f089de">MCII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad7a4636eb976abde114ff31593c4c2">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f2a96e256ad9c2abdd042c074ed084e">MAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8ab274ee961e63788a84896cd986bf">TargetMaxInstBytes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5a61f7256cb5fec8c5825d33bd57e7">Bytes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab778cfb57f56fd98820c8dde6bb47aa6">Literal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192e72a9b3153ee16e3a14ffcea4535a">Literal64</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b92d8479c9b4aa37d18845dbd5e2eff">HasLiteral</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c2d9dff8203615f9430e71e87de459">EnableWavefrontSize32</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f7c537ff5fc08a730344fd7a2f120e">CodeObjectVersion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5825ce4e0f1ff040a30e4cb8ee9c6960">UCVersionW64Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5b9538afcf03c5ef6f621520c3298a7">UCVersionW32Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52396a2d490a8bc2dee7c15fb81766ee">UCVersionMDPExpr</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55ea9f3ceb384181fdfd06df56cdd31">decodeIntImmed</a> (unsigned Imm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e463b2ce57bfddac123b8ae44feba93">decodeFPImmed</a> (unsigned ImmWidth, unsigned Imm, AMDGPU::OperandSemantics Sema)</td>
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


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### OpWidthTy {#ab8355dd4c437a99c65c3d9f3b6f5101a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPUDisassembler::OpWidthTy </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW32<a id="ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW64<a id="ab8355dd4c437a99c65c3d9f3b6f5101aaf4b2e7b624bfcb0b2c7116e43d97783a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW96<a id="ab8355dd4c437a99c65c3d9f3b6f5101aa7a8a59cea7f5905c9fe60d781a6d58ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW128<a id="ab8355dd4c437a99c65c3d9f3b6f5101aa8ffffdcc951d4a57f5aa6bac5c04e33f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW160<a id="ab8355dd4c437a99c65c3d9f3b6f5101aaf97d2901faed385ee707b87157401cfe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW192<a id="ab8355dd4c437a99c65c3d9f3b6f5101aa01b1c271e4cb0b36b504a011e8287283"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW256<a id="ab8355dd4c437a99c65c3d9f3b6f5101aabf21748608d2e79fe40afabedc73acec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW288<a id="ab8355dd4c437a99c65c3d9f3b6f5101aab323e458551a652e29905a8646970ec1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW320<a id="ab8355dd4c437a99c65c3d9f3b6f5101aacadff24cd85017f3815ad31e0d6ab424"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW352<a id="ab8355dd4c437a99c65c3d9f3b6f5101aab0077d8f0741fa97a665bb6edeb4f8ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW384<a id="ab8355dd4c437a99c65c3d9f3b6f5101aa280444282f753f38ca2c05b21ab6bd86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW512<a id="ab8355dd4c437a99c65c3d9f3b6f5101aa6f8b46bc6ca016b690e5fb7f8c4b3c52"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW1024<a id="ab8355dd4c437a99c65c3d9f3b6f5101aab94d3d679afc6c4f940d701c33cecee1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW16<a id="ab8355dd4c437a99c65c3d9f3b6f5101aaac71e10a2d389621d890aa986f9d0466"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPWV216<a id="ab8355dd4c437a99c65c3d9f3b6f5101aa157c08e03e0d0d3224f8e7fa03fc5f77"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPWV232<a id="ab8355dd4c437a99c65c3d9f3b6f5101aac41f58b414787f98d86d828f36250681"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW_LAST_<a id="ab8355dd4c437a99c65c3d9f3b6f5101aaaaa93b70a3d0d8ced191087633da35c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPW_FIRST_<a id="ab8355dd4c437a99c65c3d9f3b6f5101aa412d714f8ebb1d095d58e852d85f3efa"></a></td>
<td class="doxyEnumItemDescription"> (= OPW32)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AMDGPUDisassembler() {#a852783bf1f53ae8e8e22a3042759f90b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUDisassembler::AMDGPUDisassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * MCII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ucversion/#a826e7eb7566b6093e87bf78f186b96a2">llvm::AMDGPU::UCVersion::getGFXVersions</a>, <a href="#a515f1867e36cdffa566f9faa967bf2ad">isGFX10Plus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a07639073d0bfe2f90b94ced7f2944596">llvm::MCDisassembler::MCDisassembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AMDGPUDisassembler() {#a94d3b563775fcf320d994bcd8aa646ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPUDisassembler::~AMDGPUDisassembler ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertDPP8Inst() {#a5924dbd31504014961bf4324546da2cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertDPP8Inst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1012 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a0670115d0e8597ec2618045c1076d811">collectVOPModifiers</a>, <a href="#a6dc51b29f05105e3ce97ba5b40087dcb">convertTrue16OpSel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertEXPInst() {#a0fcaab7e1e2ab1a6575d41a5e3fe99db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertEXPInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertFMAanyK() {#a70ebec5cbc0a8238828d0527a06568f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertFMAanyK (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, int ImmLitIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/encvalues/#a8827d0769d5975ce9edb64c48d3a6614a64505b53beb145f22a5e090a5f7fc97a">llvm::AMDGPU::EncValues::LITERAL_CONST</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aff389f984e981455b4107b4708a77e5b">llvm::AMDGPU::OPERAND_REG_IMM_FP16_DEFERRED</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5af8ac73c62f6f1da6175d32824633a064">llvm::AMDGPU::OPERAND_REG_IMM_FP32_DEFERRED</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertMacDPPInst() {#a4974310fb906d87e0b82ea333101d33c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertMacDPPInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1005 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertMAIInst() {#acdb4b1dd5155bf0f31e8d74cdd8ccc6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertMAIInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>f8f6f4 instructions have different pseudos depending on the used formats.</p>


<p>In the disassembler table, we only have the variants with the largest register classes which assume using an fp8/bf8 format for both operands. The actual register class depends on the format in blgp and cbsz operands. Adjust the register classes depending on the used format.</p>


<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aff9a81d3a94f8d3b4530e6430d5c772c">adjustMFMA_F8F6F4OpRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af566f32b2d730ac9d98b434e754335f7">llvm::AMDGPU::getMFMA_F8F6F4_WithFormatArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mfma-f8f6f4-info/#af277cb1c27a021edb8643360537b3294">llvm::AMDGPU::MFMA_F8F6F4_Info::NumRegsSrcA</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mfma-f8f6f4-info/#a38bb9bb3804fe3b58aec80cd339573ff">llvm::AMDGPU::MFMA_F8F6F4_Info::NumRegsSrcB</a> and <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mfma-f8f6f4-info/#a3e72d32e10f86d40f3c435ed3707a7bc">llvm::AMDGPU::MFMA_F8F6F4_Info::Opcode</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertMIMGInst() {#ae5f0e6bc47c72961a9a05d307d6400f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertMIMGInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1062 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mimgbaseopcodeinfo/#ac4143c4d0308ab58f78f0e5fc74902e4">llvm::AMDGPU::MIMGBaseOpcodeInfo::A16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a9fafc367cabbdce17ed971f70373c7c9">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mimgbaseopcodeinfo/#ae568e3885ff86491cfec37106f83d1c7">llvm::AMDGPU::MIMGBaseOpcodeInfo::BVH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca1fb3a3c9d73c11f77861315b283e3fde">llvm::SIInstrFlags::Gather4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9af58a5d20f2215a00b675f34db92771">llvm::AMDGPU::getAddrSizeMIMGOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae1884e3318cb1f8a4465b1b4bd4d9827">llvm::AMDGPU::getMIMGBaseOpcodeInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7967181b077a4a08f5baf9950e30660d">llvm::AMDGPU::getMIMGDimInfoByEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0b5b29d1275f84b9e530fd2419cc03ac">llvm::AMDGPU::getMIMGInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a176f799037e98f7743008924c4b72266">llvm::AMDGPU::getMIMGOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9adcf3cabdbd72a34b34f13f2826314b">llvm::AMDGPU::hasG16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3856884676648fe8f7af93f6c5e60e1f">llvm::AMDGPU::hasPackedD16</a>, <a href="#a515f1867e36cdffa566f9faa967bf2ad">isGFX10Plus</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0666b703f5fe8ee884171492fb6a685a">llvm::SIInstrFlags::MIMG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca68afea1b16331758f09fc0d8c229b86f">llvm::SIInstrFlags::VSAMPLE</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertSDWAInst() {#a9a2160759492c85b0f23cc8e5d9538f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertSDWAInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertTrue16OpSel() {#a6dc51b29f05105e3ce97ba5b40087dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertTrue16OpSel (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass/#ad183dc79953e350b769b1dcfda4f0f1c">llvm::MCRegisterClass::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a8e2f726558b97b38629c9fa9f8691612">llvm::SISrcMods::DST_OP_SEL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass/#ac33acd2efcc170ca04a2229d8c365629">llvm::MCRegisterClass::getRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sisrcmods/#a4d4c7f0ccdd236a97a1583b77f8fd442a3b095994a942145ccaaed4f175c7172a">llvm::SISrcMods::OP_SEL_0</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hwencoding/#a7591861bd58475c68c3d9c2d3578daaca965397959a0d6089e58be5b01f6cf095">llvm::AMDGPU::HWEncoding::REG_IDX_MASK</a>.</p>


<p>Referenced by <a href="#a5924dbd31504014961bf4324546da2cc">convertDPP8Inst</a>, <a href="#a951e9da312d0c74b6988e59280910007">convertVINTERPInst</a>, <a href="#a688f4832464547c17012a58790863c53">convertVOP3DPPInst</a>, <a href="#a074a4f039b95fd6ecd9a199e3db42097">convertVOPC64DPPInst</a> and <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertVINTERPInst() {#a951e9da312d0c74b6988e59280910007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertVINTERPInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a6dc51b29f05105e3ce97ba5b40087dcb">convertTrue16OpSel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertVOP3DPPInst() {#a688f4832464547c17012a58790863c53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertVOP3DPPInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a0670115d0e8597ec2618045c1076d811">collectVOPModifiers</a>, <a href="#a6dc51b29f05105e3ce97ba5b40087dcb">convertTrue16OpSel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertVOP3PDPPInst() {#af2662661417cf1a8f0b242b84853829f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertVOP3PDPPInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a0670115d0e8597ec2618045c1076d811">collectVOPModifiers</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertVOPC64DPPInst() {#a074a4f039b95fd6ecd9a199e3db42097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertVOPC64DPPInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a0670115d0e8597ec2618045c1076d811">collectVOPModifiers</a>, <a href="#a6dc51b29f05105e3ce97ba5b40087dcb">convertTrue16OpSel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/structs/vopmodifiers/#ac99f5b33e7000c0fc1807242045a7c06">VOPModifiers::OpSel</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### convertVOPCDPPInst() {#a2021d83fb89da51586187868e0ba649d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::convertVOPCDPPInst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### createRegOperand() {#a13ac39db7a12e1ee120630d7aa17bae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::createRegOperand (unsigned int RegId)</td>
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



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a12457438c2b018b673e22e0253e466c4">llvm::AMDGPU::getMCReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a9a2160759492c85b0f23cc8e5d9538f6">convertSDWAInst</a>, <a href="#a10982f41862673ec4aa270b0eef58a7b">createRegOperand</a>, <a href="#af564aa8a41fb212e8dfc8856ef35c871">createSRegOperand</a>, <a href="#a5a7e8470c4be479dbcf6ac32a977b8b3">createVGPR16Operand</a>, <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a>, <a href="#a9481f68151f53dba0f1e3416819e6e26">decodeSDWAVopcDst</a>, <a href="#a865ae0d33ec9cd2b21d7b55470ac58d0">decodeSpecialReg32</a>, <a href="#a168a8034e9e01207fb71a39bde063d7f">decodeSpecialReg64</a>, <a href="#a318ce4a6802b51ada47c71f8692132ab">decodeSpecialReg96Plus</a>, <a href="#a84f8e99199a1dc95b1fd2a144aa79a6c">decodeSrcOp</a>, <a href="#a4ae2e98f9553b452f8c2b5107a8cb16a">decodeVOPDDstYOp</a> and <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### createRegOperand() {#a10982f41862673ec4aa270b0eef58a7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::createRegOperand (unsigned RegClassID, unsigned Val)</td>
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



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="#a5b147cf1557182f62cf46de5ea9b5061">errOperand</a> and <a href="#a16d28a91d7aca8ef06fa3e2533047f0b">getRegClassName</a>.</p>

</div>
</div>

### createSRegOperand() {#af564aa8a41fb212e8dfc8856ef35c871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::createSRegOperand (unsigned SRegClassID, unsigned Val)</td>
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



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a68057d4a784ee78eca6f35d84936df6c">llvm::MCDisassembler::CommentStream</a>, <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="#a16d28a91d7aca8ef06fa3e2533047f0b">getRegClassName</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a>, <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a> and <a href="#a9481f68151f53dba0f1e3416819e6e26">decodeSDWAVopcDst</a>.</p>

</div>
</div>

### createVGPR16Operand() {#a5a7e8470c4be479dbcf6ac32a977b8b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::createVGPR16Operand (unsigned RegIdx, bool IsHi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>.</p>

</div>
</div>

### decodeBoolReg() {#a4cfa93abf00f463c320ff9b5fb940583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeBoolReg (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a84f8e99199a1dc95b1fd2a144aa79a6c">decodeSrcOp</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf4b2e7b624bfcb0b2c7116e43d97783a">OPW64</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>

</div>
</div>

### decodeCOMPUTE\_PGM\_RSRC1() {#a1a717ebce0af699c0b264313d0cb21e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC1 (uint32_t FourByteBuffer, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> &amp; KdStream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode as directives that handle COMPUTE_PGM_RSRC1.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FourByteBuffer</td>
<td class="doxyParamItemDescription"><p>- Bytes holding contents of COMPUTE_PGM_RSRC1.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KdStream</td>
<td class="doxyParamItemDescription"><p>- Stream to write the disassembled directives to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 2046 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aa33da5c37d93576ec4aacb9ce7672368">CHECK_RESERVED_BITS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a00cbaf3dc4f08d1784589594dfe6149d">CHECK_RESERVED_BITS_DESC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#afa52988bf1e093da5f3499a666cf0a63">CHECK_RESERVED_BITS_DESC_MSG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#ac67c208c1ef5d548e50e8d2efb76fc2c">CHECK_RESERVED_BITS_MSG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#adbe651d6dbda0f8eacf67b705a8d3b13">GET_FIELD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a4f89565a53fec2d53160be82c292202e">llvm::AMDGPU::IsaInfo::getSGPREncodingGranule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a00ddec6f625f5fdc41b2ee64b272b5b9">llvm::AMDGPU::IsaInfo::getVGPREncodingGranule</a>, <a href="#ad1bbaf8f762d31654b6a7580783122f5">hasArchitectedFlatScratch</a>, <a href="#a515f1867e36cdffa566f9faa967bf2ad">isGFX10Plus</a>, <a href="#aa2a606a1a89df2407a17f844127bca7e">isGFX12Plus</a>, <a href="#a40c6ec88b07c8f5dcfecacabe3007ecf">isGFX9Plus</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a7b14fc850e8e58263a51cd89e7d6c838">PRINT_DIRECTIVE</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a1ec298d8a742a9519e6dc0903f822f2b">decodeKernelDescriptorDirective</a>.</p>

</div>
</div>

### decodeCOMPUTE\_PGM\_RSRC2() {#a341ce9a65b287f8033788c0bb12d8fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC2 (uint32_t FourByteBuffer, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> &amp; KdStream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode as directives that handle COMPUTE_PGM_RSRC2.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FourByteBuffer</td>
<td class="doxyParamItemDescription"><p>- Bytes holding contents of COMPUTE_PGM_RSRC2.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KdStream</td>
<td class="doxyParamItemDescription"><p>- Stream to write the disassembled directives to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 2154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aa33da5c37d93576ec4aacb9ce7672368">CHECK_RESERVED_BITS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a00cbaf3dc4f08d1784589594dfe6149d">CHECK_RESERVED_BITS_DESC</a>, <a href="#ad1bbaf8f762d31654b6a7580783122f5">hasArchitectedFlatScratch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a7b14fc850e8e58263a51cd89e7d6c838">PRINT_DIRECTIVE</a>.</p>


<p>Referenced by <a href="#a1ec298d8a742a9519e6dc0903f822f2b">decodeKernelDescriptorDirective</a>.</p>

</div>
</div>

### decodeCOMPUTE\_PGM\_RSRC3() {#a7de6bde5116ff125fb02491b47586333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; AMDGPUDisassembler::decodeCOMPUTE_PGM_RSRC3 (uint32_t FourByteBuffer, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> &amp; KdStream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode as directives that handle COMPUTE_PGM_RSRC3.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FourByteBuffer</td>
<td class="doxyParamItemDescription"><p>- Bytes holding contents of COMPUTE_PGM_RSRC3.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KdStream</td>
<td class="doxyParamItemDescription"><p>- Stream to write the disassembled directives to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 2202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#afa52988bf1e093da5f3499a666cf0a63">CHECK_RESERVED_BITS_DESC_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#adbe651d6dbda0f8eacf67b705a8d3b13">GET_FIELD</a>, <a href="#a515f1867e36cdffa566f9faa967bf2ad">isGFX10Plus</a>, <a href="#a347423b9fcc60e76ff31a10a90bd5840">isGFX11</a>, <a href="#af5cd2cf12e0610bc99b7c894f677b2f8">isGFX11Plus</a>, <a href="#aa2a606a1a89df2407a17f844127bca7e">isGFX12Plus</a>, <a href="#ae2163e267c5265155b8e5ac1f9306fdc">isGFX90A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a7b14fc850e8e58263a51cd89e7d6c838">PRINT_DIRECTIVE</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a44e38092dcf380740d2ead9690ae9bfc">PRINT_PSEUDO_DIRECTIVE_COMMENT</a>.</p>


<p>Referenced by <a href="#a1ec298d8a742a9519e6dc0903f822f2b">decodeKernelDescriptorDirective</a>.</p>

</div>
</div>

### decodeDpp8FI() {#a3f8610c5c7c16e772286ed071dd699c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeDpp8FI (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1907 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/dpp/#aa19c007b0d0fdcbf3db8462eeb72c059a86bc62297264c5c421f06a54985349a1">llvm::AMDGPU::DPP::DPP8_FI_0</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/dpp/#aa19c007b0d0fdcbf3db8462eeb72c059a470b8d8ac84510a78711e68988cb0d6b">llvm::AMDGPU::DPP::DPP8_FI_1</a>.</p>

</div>
</div>

### decodeKernelDescriptor() {#a66aa742680260d77ebab20536c828c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; AMDGPUDisassembler::decodeKernelDescriptor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> KdName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t KdAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 2467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a286f2813b785a6b1d7f9c688580c2dc4">AMDHSA_BITS_GET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a1ec298d8a742a9519e6dc0903f822f2b">decodeKernelDescriptorDirective</a>, <a href="#a515f1867e36cdffa566f9faa967bf2ad">isGFX10Plus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044ea037c5c9c1788405600fbd6c5ef7a1824">llvm::amdhsa::KERNEL_CODE_PROPERTIES_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#af10ce40e426fd2ff3b12ff8158da378d">llvm::support::endian::read16</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>


<p>Referenced by <a href="#afec69108aa44466b2b0dfdd41a76aab1">onSymbolStart</a>.</p>

</div>
</div>

### decodeKernelDescriptorDirective() {#a1ec298d8a742a9519e6dc0903f822f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; AMDGPUDisassembler::decodeKernelDescriptorDirective (<a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">DataExtractor::Cursor</a> &amp; Cursor, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> &amp; KdStream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 2315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a30475b065bebd7bc81d1112d9067d772abd2438b14a6a1a27fae653284aaa3cb4">llvm::AMDGPU::AMDHSA_COV5</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044ea8e1b04b78a7883b48863d2efe00d0ef1">llvm::amdhsa::COMPUTE_PGM_RSRC1_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044ea9836d1311b13f6354879bb75a4b4ad79">llvm::amdhsa::COMPUTE_PGM_RSRC2_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044ea3c5076dfb4b5c82782e6fd3f6a593ef2">llvm::amdhsa::COMPUTE_PGM_RSRC3_OFFSET</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aff86ab78c9551cfaa6fd58da22f49dc5">createReservedKDBitsError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aef7ddc0af2349fa45789289f716de36a">createReservedKDBytesError</a>, <a href="#a1a717ebce0af699c0b264313d0cb21e2">decodeCOMPUTE_PGM_RSRC1</a>, <a href="#a341ce9a65b287f8033788c0bb12d8fa3">decodeCOMPUTE_PGM_RSRC2</a>, <a href="#a7de6bde5116ff125fb02491b47586333">decodeCOMPUTE_PGM_RSRC3</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ade9e119455709c0d46a34464ebdbf179">llvm::DataExtractor::getBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a98923ce73981e5171ef246bdcc6fde60">llvm::DataExtractor::getU16</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a0eb55ea3f585f9c8a2619fe7250e56f4">llvm::DataExtractor::getU32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044ea2e074167b1983e588a8c0ba5325bfa97">llvm::amdhsa::GROUP_SEGMENT_FIXED_SIZE_OFFSET</a>, <a href="#ad1bbaf8f762d31654b6a7580783122f5">hasArchitectedFlatScratch</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a515f1867e36cdffa566f9faa967bf2ad">isGFX10Plus</a>, <a href="#ab9c9f9be5e439d07443ad92852b18f06">isGFX9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044eaf3e966f0fae82fa3dd5976a868292add">llvm::amdhsa::KERNARG_PRELOAD_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044eaf308f21ac7a45fcb649c83753e8255e9">llvm::amdhsa::KERNARG_SIZE_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044ea5c9a71aaaf3601b70f680fc756c4cc0f">llvm::amdhsa::KERNEL_CODE_ENTRY_BYTE_OFFSET_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044ea037c5c9c1788405600fbd6c5ef7a1824">llvm::amdhsa::KERNEL_CODE_PROPERTIES_OFFSET</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a7b14fc850e8e58263a51cd89e7d6c838">PRINT_DIRECTIVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044eac9f74838f2b410f00aafce9e75bdd8c1">llvm::amdhsa::PRIVATE_SEGMENT_FIXED_SIZE_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044eab15959445e2b2b3ad662f5617bb8dd20">llvm::amdhsa::RESERVED0_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044ea30240d80e085b09ee5946f541c54765e">llvm::amdhsa::RESERVED1_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdhsa/#a76c20677aff67ef610b0aec8cf21044ead3c5d91b7337c6b9da367cd983189fdb">llvm::amdhsa::RESERVED3_OFFSET</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#aa4c4043f99a1a5b283741ef4c7cf2464">llvm::DataExtractor::skip</a> and <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a22c134bb6de5493faf9c7076ef4dfcac">llvm::DataExtractor::Cursor::tell</a>.</p>


<p>Referenced by <a href="#a66aa742680260d77ebab20536c828c17">decodeKernelDescriptor</a>.</p>

</div>
</div>

### decodeLiteralConstant() {#a8c8699483ef63f1164acdd8a35f49066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeLiteralConstant (bool ExtendFP64)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aaff8a7b712c8ea0bb1275e621119e498">eatBytes</a> and <a href="#a5b147cf1557182f62cf46de5ea9b5061">errOperand</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a>.</p>

</div>
</div>

### decodeMandatoryLiteralConstant() {#a7bc1d16f7c74d8204bf3ab1f4d5c0998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeMandatoryLiteralConstant (unsigned Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a5b147cf1557182f62cf46de5ea9b5061">errOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af277efe76de2cd454da028d38646f2b5">llvm::AMDGPU::hasVOPD</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>

</div>
</div>

### decodeNonVGPRSrcOp() {#a7d7fece3c5c1c1d977334eb948baecfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeNonVGPRSrcOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8355dd4c437a99c65c3d9f3b6f5101a">OpWidthTy</a> Width, unsigned Val, bool MandatoryLiteral=false, unsigned ImmWidth=0, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272">AMDGPU::OperandSemantics</a> Sema=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a14af872950285c8905100828bc849349">AMDGPU::OperandSemantics::INT</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1672 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#af564aa8a41fb212e8dfc8856ef35c871">createSRegOperand</a>, <a href="#a7e463b2ce57bfddac123b8ae44feba93">decodeFPImmed</a>, <a href="#ab55ea9f3ceb384181fdfd06df56cdd31">decodeIntImmed</a>, <a href="#a8c8699483ef63f1164acdd8a35f49066">decodeLiteralConstant</a>, <a href="#a865ae0d33ec9cd2b21d7b55470ac58d0">decodeSpecialReg32</a>, <a href="#a168a8034e9e01207fb71a39bde063d7f">decodeSpecialReg64</a>, <a href="#a318ce4a6802b51ada47c71f8692132ab">decodeSpecialReg96Plus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a1c2050e48d2c5ccd761ea8003597de90">llvm::AMDGPU::FP64</a>, <a href="#ab1c21284d55eedc91c4a3969626b6f1a">getSgprClassId</a>, <a href="#adae4bf9c24a1f20e4ad36d42620f6e7a">getTtmpClassId</a>, <a href="#ae852f28eb2685d5dc30c78308011af7f">getTTmpIdx</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa8ffffdcc951d4a57f5aa6bac5c04e33f">OPW128</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaac71e10a2d389621d890aa986f9d0466">OPW16</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aabf21748608d2e79fe40afabedc73acec">OPW256</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa6f8b46bc6ca016b690e5fb7f8c4b3c52">OPW512</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf4b2e7b624bfcb0b2c7116e43d97783a">OPW64</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa7a8a59cea7f5905c9fe60d781a6d58ea">OPW96</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa157c08e03e0d0d3224f8e7fa03fc5f77">OPWV216</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aac41f58b414787f98d86d828f36250681">OPWV232</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aac8b18da22658e7589a0286322114803">SGPR_MAX</a>.</p>


<p>Referenced by <a href="#a84f8e99199a1dc95b1fd2a144aa79a6c">decodeSrcOp</a>.</p>

</div>
</div>

### decodeSDWASrc() {#a654a634c301c3ad83782795b18260031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeSDWASrc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8355dd4c437a99c65c3d9f3b6f5101a">OpWidthTy</a> Width, unsigned Val, unsigned ImmWidth, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272">AMDGPU::OperandSemantics</a> Sema)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="#af564aa8a41fb212e8dfc8856ef35c871">createSRegOperand</a>, <a href="#a7e463b2ce57bfddac123b8ae44feba93">decodeFPImmed</a>, <a href="#ab55ea9f3ceb384181fdfd06df56cdd31">decodeIntImmed</a>, <a href="#a865ae0d33ec9cd2b21d7b55470ac58d0">decodeSpecialReg32</a>, <a href="#ab1c21284d55eedc91c4a3969626b6f1a">getSgprClassId</a>, <a href="#adae4bf9c24a1f20e4ad36d42620f6e7a">getTtmpClassId</a>, <a href="#a2a49c0ccc7c9aa0fe2692b60975f8ba3">getVgprClassId</a>, <a href="#a515f1867e36cdffa566f9faa967bf2ad">isGFX10Plus</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#afdccfd26f12d23c635188ff714e99c8d">decodeSDWASrc16</a> and <a href="#a32f73e787f141094d0aa638db8653ec8">decodeSDWASrc32</a>.</p>

</div>
</div>

### decodeSDWASrc16() {#afdccfd26f12d23c635188ff714e99c8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeSDWASrc16 (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1864 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272aac30c0763322ae3938bebeecaff75de6">llvm::AMDGPU::FP16</a> and <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaac71e10a2d389621d890aa986f9d0466">OPW16</a>.</p>

</div>
</div>

### decodeSDWASrc32() {#a32f73e787f141094d0aa638db8653ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeSDWASrc32 (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a19126c4f8c4ab60581477e3ef8dd36f5">llvm::AMDGPU::FP32</a> and <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>.</p>

</div>
</div>

### decodeSDWAVopcDst() {#a9481f68151f53dba0f1e3416819e6e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeSDWAVopcDst (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1872 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="#af564aa8a41fb212e8dfc8856ef35c871">createSRegOperand</a>, <a href="#a865ae0d33ec9cd2b21d7b55470ac58d0">decodeSpecialReg32</a>, <a href="#a168a8034e9e01207fb71a39bde063d7f">decodeSpecialReg64</a>, <a href="#ab1c21284d55eedc91c4a3969626b6f1a">getSgprClassId</a>, <a href="#adae4bf9c24a1f20e4ad36d42620f6e7a">getTtmpClassId</a>, <a href="#ae852f28eb2685d5dc30c78308011af7f">getTTmpIdx</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf4b2e7b624bfcb0b2c7116e43d97783a">OPW64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aac8b18da22658e7589a0286322114803">SGPR_MAX</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>

</div>
</div>

### decodeSpecialReg32() {#a865ae0d33ec9cd2b21d7b55470ac58d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeSpecialReg32 (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="#a5b147cf1557182f62cf46de5ea9b5061">errOperand</a>, <a href="#af5cd2cf12e0610bc99b7c894f677b2f8">isGFX11Plus</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8aff98d3587ddb15f9e46ed88687f0f">llvm::M0</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a>, <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a> and <a href="#a9481f68151f53dba0f1e3416819e6e26">decodeSDWAVopcDst</a>.</p>

</div>
</div>

### decodeSpecialReg64() {#a168a8034e9e01207fb71a39bde063d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeSpecialReg64 (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1772 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="#a5b147cf1557182f62cf46de5ea9b5061">errOperand</a> and <a href="#af5cd2cf12e0610bc99b7c894f677b2f8">isGFX11Plus</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a> and <a href="#a9481f68151f53dba0f1e3416819e6e26">decodeSDWAVopcDst</a>.</p>

</div>
</div>

### decodeSpecialReg96Plus() {#a318ce4a6802b51ada47c71f8692132ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeSpecialReg96Plus (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1803 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="#a5b147cf1557182f62cf46de5ea9b5061">errOperand</a> and <a href="#af5cd2cf12e0610bc99b7c894f677b2f8">isGFX11Plus</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a>.</p>

</div>
</div>

### decodeSplitBarrier() {#a682a5e3b08aa66c35ff6853e832695c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeSplitBarrier (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1903 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="#a84f8e99199a1dc95b1fd2a144aa79a6c">decodeSrcOp</a> and <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>.</p>

</div>
</div>

### decodeSrcOp() {#a84f8e99199a1dc95b1fd2a144aa79a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeSrcOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8355dd4c437a99c65c3d9f3b6f5101a">OpWidthTy</a> Width, unsigned Val, bool MandatoryLiteral=false, unsigned ImmWidth=0, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272">AMDGPU::OperandSemantics</a> Sema=<a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272a14af872950285c8905100828bc849349">AMDGPU::OperandSemantics::INT</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1652 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a>, <a href="#a2bc52c96e46c682e3e109f4a3ddef37b">getAgprClassId</a> and <a href="#a2a49c0ccc7c9aa0fe2692b60975f8ba3">getVgprClassId</a>.</p>


<p>Referenced by <a href="#a4cfa93abf00f463c320ff9b5fb940583">decodeBoolReg</a> and <a href="#a682a5e3b08aa66c35ff6853e832695c3">decodeSplitBarrier</a>.</p>

</div>
</div>

### decodeVersionImm() {#a64b42038a61a3c4b1880eea5331cdb44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeVersionImm (unsigned Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1913 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a6b303b433f43b901194dbf17adfb562c">llvm::MCBinaryExpr::createOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a3faa10cafd0be721018fc1b9bc2c5488">llvm::MCDisassembler::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/ucversion/#a826e7eb7566b6093e87bf78f186b96a2">llvm::AMDGPU::UCVersion::getGFXVersions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

### decodeVOPDDstYOp() {#a4ae2e98f9553b452f8c2b5107a8cb16a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeVOPDDstYOp (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="#a2a49c0ccc7c9aa0fe2692b60975f8ba3">getVgprClassId</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a> and <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>.</p>

</div>
</div>

### errOperand() {#a5b147cf1557182f62cf46de5ea9b5061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::errOperand (unsigned V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrMsg)</td>
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



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a68057d4a784ee78eca6f35d84936df6c">llvm::MCDisassembler::CommentStream</a>.</p>


<p>Referenced by <a href="#a10982f41862673ec4aa270b0eef58a7b">createRegOperand</a>, <a href="#a8c8699483ef63f1164acdd8a35f49066">decodeLiteralConstant</a>, <a href="#a7bc1d16f7c74d8204bf3ab1f4d5c0998">decodeMandatoryLiteralConstant</a>, <a href="#a865ae0d33ec9cd2b21d7b55470ac58d0">decodeSpecialReg32</a>, <a href="#a168a8034e9e01207fb71a39bde063d7f">decodeSpecialReg64</a> and <a href="#a318ce4a6802b51ada47c71f8692132ab">decodeSpecialReg96Plus</a>.</p>

</div>
</div>

### getAgprClassId() {#a2bc52c96e46c682e3e109f4a3ddef37b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUDisassembler::getAgprClassId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8355dd4c437a99c65c3d9f3b6f5101a">OpWidthTy</a> Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab94d3d679afc6c4f940d701c33cecee1">OPW1024</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa8ffffdcc951d4a57f5aa6bac5c04e33f">OPW128</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaac71e10a2d389621d890aa986f9d0466">OPW16</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf97d2901faed385ee707b87157401cfe">OPW160</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aabf21748608d2e79fe40afabedc73acec">OPW256</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab323e458551a652e29905a8646970ec1">OPW288</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aacadff24cd85017f3815ad31e0d6ab424">OPW320</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab0077d8f0741fa97a665bb6edeb4f8ef">OPW352</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa280444282f753f38ca2c05b21ab6bd86">OPW384</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa6f8b46bc6ca016b690e5fb7f8c4b3c52">OPW512</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf4b2e7b624bfcb0b2c7116e43d97783a">OPW64</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa7a8a59cea7f5905c9fe60d781a6d58ea">OPW96</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa412d714f8ebb1d095d58e852d85f3efa">OPW_FIRST_</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaaaa93b70a3d0d8ced191087633da35c7">OPW_LAST_</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa157c08e03e0d0d3224f8e7fa03fc5f77">OPWV216</a> and <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aac41f58b414787f98d86d828f36250681">OPWV232</a>.</p>


<p>Referenced by <a href="#a84f8e99199a1dc95b1fd2a144aa79a6c">decodeSrcOp</a>.</p>

</div>
</div>

### getInstruction() {#ad9305ad45a7db970a0a198791bea136a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus AMDGPUDisassembler::getInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Instr, uint64_t &amp; Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CStream)</td>
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

<p>Returns the disassembly of a single instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Instr</td>
<td class="doxyParamItemDescription"><p>- An <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to populate with the contents of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- A value to populate with the size of the instruction, or the number of bytes consumed while attempting to decode an invalid instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Address</td>
<td class="doxyParamItemDescription"><p>- The address, in the memory space of region, of the first byte of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bytes</td>
<td class="doxyParamItemDescription"><p>- A reference to the actual bytes of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CStream</td>
<td class="doxyParamItemDescription"><p>- The stream to print comments and annotations on.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">MCDisassembler::Success</a> if the instruction is valid, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa9d693b8e530a7fa3457dece6f8951e6c">MCDisassembler::SoftFail</a> if the instruction was disassemblable but invalid, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">MCDisassembler::Fail</a> if the instruction was invalid.</p></dd>
</dl>


<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#a5924dbd31504014961bf4324546da2cc">convertDPP8Inst</a>, <a href="#a0fcaab7e1e2ab1a6575d41a5e3fe99db">convertEXPInst</a>, <a href="#a70ebec5cbc0a8238828d0527a06568f1">convertFMAanyK</a>, <a href="#a4974310fb906d87e0b82ea333101d33c">convertMacDPPInst</a>, <a href="#acdb4b1dd5155bf0f31e8d74cdd8ccc6c">convertMAIInst</a>, <a href="#ae5f0e6bc47c72961a9a05d307d6400f1">convertMIMGInst</a>, <a href="#a9a2160759492c85b0f23cc8e5d9538f6">convertSDWAInst</a>, <a href="#a6dc51b29f05105e3ce97ba5b40087dcb">convertTrue16OpSel</a>, <a href="#a951e9da312d0c74b6988e59280910007">convertVINTERPInst</a>, <a href="#a688f4832464547c17012a58790863c53">convertVOP3DPPInst</a>, <a href="#af2662661417cf1a8f0b242b84853829f">convertVOP3PDPPInst</a>, <a href="#a074a4f039b95fd6ecd9a199e3db42097">convertVOPC64DPPInst</a>, <a href="#a2021d83fb89da51586187868e0ba649d">convertVOPCDPPInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a13ac39db7a12e1ee120630d7aa17bae8">createRegOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca06434d3505958806f243119630f8c976">llvm::SIInstrFlags::DPP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca953a5ba3766c4aea8d9b8eeeba722679">llvm::SIInstrFlags::DS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a434621cd1f8f1c0240a47b65ba19ea9b">eat12Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a7d8ee6944c8121c49c2a8da4b1695fe7">eat16Bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aaff8a7b712c8ea0bb1275e621119e498">eatBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3f6b33151573e94a6ef7f14b809dbe70">llvm::SIInstrFlags::EXP</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab0e8527c8c81d2caa91d9b2bd1852574">llvm::SIInstrFlags::FLAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/cpol/#a7d79a4b341da8ac60b91c1f4b1ea42c4a54ef769ac24b3f9c29d7f0dc5433fecd">llvm::AMDGPU::CPol::GLC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac06f184d382ba9a26ef8deaea0b31cd8">llvm::AMDGPU::hasGDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a39c0a22d457ccc212829d0a052685264">insertNamedMCOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca046343a654627954ce26d0e7531e12f7">llvm::SIInstrFlags::IsAtomicRet</a>, <a href="#aeee62e9882c0b90536eaa08027bbfef7">isGFX10</a>, <a href="#a347423b9fcc60e76ff31a10a90bd5840">isGFX11</a>, <a href="#af5cd2cf12e0610bc99b7c894f677b2f8">isGFX11Plus</a>, <a href="#a18e19f604d742a99d805737f3d21ff62">isGFX12</a>, <a href="#ab9c9f9be5e439d07443ad92852b18f06">isGFX9</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#addb7ac73684b6266c9a9c177c602d603">llvm::AMDGPU::isMAC</a>, <a href="#ae75794f911e166bcea94523957bdec07">isMacDPP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaa0bc33f3818c02a577a8b209d98766cb">llvm::SIInstrFlags::IsMAI</a>, <a href="#a7297f920e9ff94394d81719b75080ecb">isVI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a55212d9e75092af1bf2bee56503b1609">llvm::AMDGPU::isVOPC64DPP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0666b703f5fe8ee884171492fb6a685a">llvm::SIInstrFlags::MIMG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4863f895381859543f89e4423126a73f">llvm::SIInstrFlags::MTBUF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca2fca87a5855f045ac7f07d8c2814e81f">llvm::SIInstrFlags::MUBUF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3cb08b10c27a453c57a2708e83859b47">llvm::SIInstrFlags::SDWA</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca30118e93ea743944a8fa1d846dcbaf37">llvm::SIInstrFlags::SMRD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca95d3d9b72a40bcb9f88738fd86094a62">llvm::SIInstrFlags::SOPK</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>, <a href="#aae4a6148a52bc05698e9890ee276e6b1">tryDecodeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecaffe2f0079ddf5f206b323cdecec1e655">llvm::SIInstrFlags::VIMAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca1440c15f5bea6a1ebb07324b7be433c3">llvm::SIInstrFlags::VINTERP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca78562688e8d67f7ffa892e4b92311a98">llvm::SIInstrFlags::VOP3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4b3bb80273571c42a8b35d5e952034c9">llvm::SIInstrFlags::VOP3P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca40767b966aa194931bb6ce67e3649de7">llvm::SIInstrFlags::VOPC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca68afea1b16331758f09fc0d8c229b86f">llvm::SIInstrFlags::VSAMPLE</a>.</p>

</div>
</div>

### getMCII() {#a01b498d343f513db217828dd650ae22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrInfo * llvm::AMDGPUDisassembler::getMCII ()</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>.</p>

</div>
</div>

### getRegClassName() {#a16d28a91d7aca8ef06fa3e2533047f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * AMDGPUDisassembler::getRegClassName (unsigned RegClassID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a3faa10cafd0be721018fc1b9bc2c5488">llvm::MCDisassembler::getContext</a>, <a href="#a16d28a91d7aca8ef06fa3e2533047f0b">getRegClassName</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7eff7fcbe27aa063e7dced4042ca3416">llvm::MCContext::getRegisterInfo</a>.</p>


<p>Referenced by <a href="#a10982f41862673ec4aa270b0eef58a7b">createRegOperand</a>, <a href="#af564aa8a41fb212e8dfc8856ef35c871">createSRegOperand</a> and <a href="#a16d28a91d7aca8ef06fa3e2533047f0b">getRegClassName</a>.</p>

</div>
</div>

### getSgprClassId() {#ab1c21284d55eedc91c4a3969626b6f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUDisassembler::getSgprClassId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8355dd4c437a99c65c3d9f3b6f5101a">OpWidthTy</a> Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa8ffffdcc951d4a57f5aa6bac5c04e33f">OPW128</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaac71e10a2d389621d890aa986f9d0466">OPW16</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf97d2901faed385ee707b87157401cfe">OPW160</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aabf21748608d2e79fe40afabedc73acec">OPW256</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab323e458551a652e29905a8646970ec1">OPW288</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aacadff24cd85017f3815ad31e0d6ab424">OPW320</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab0077d8f0741fa97a665bb6edeb4f8ef">OPW352</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa280444282f753f38ca2c05b21ab6bd86">OPW384</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa6f8b46bc6ca016b690e5fb7f8c4b3c52">OPW512</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf4b2e7b624bfcb0b2c7116e43d97783a">OPW64</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa7a8a59cea7f5905c9fe60d781a6d58ea">OPW96</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa412d714f8ebb1d095d58e852d85f3efa">OPW_FIRST_</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaaaa93b70a3d0d8ced191087633da35c7">OPW_LAST_</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa157c08e03e0d0d3224f8e7fa03fc5f77">OPWV216</a> and <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aac41f58b414787f98d86d828f36250681">OPWV232</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a>, <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a> and <a href="#a9481f68151f53dba0f1e3416819e6e26">decodeSDWAVopcDst</a>.</p>

</div>
</div>

### getTtmpClassId() {#adae4bf9c24a1f20e4ad36d42620f6e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUDisassembler::getTtmpClassId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8355dd4c437a99c65c3d9f3b6f5101a">OpWidthTy</a> Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa8ffffdcc951d4a57f5aa6bac5c04e33f">OPW128</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaac71e10a2d389621d890aa986f9d0466">OPW16</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aabf21748608d2e79fe40afabedc73acec">OPW256</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab323e458551a652e29905a8646970ec1">OPW288</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aacadff24cd85017f3815ad31e0d6ab424">OPW320</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab0077d8f0741fa97a665bb6edeb4f8ef">OPW352</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa280444282f753f38ca2c05b21ab6bd86">OPW384</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa6f8b46bc6ca016b690e5fb7f8c4b3c52">OPW512</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf4b2e7b624bfcb0b2c7116e43d97783a">OPW64</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa412d714f8ebb1d095d58e852d85f3efa">OPW_FIRST_</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaaaa93b70a3d0d8ced191087633da35c7">OPW_LAST_</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa157c08e03e0d0d3224f8e7fa03fc5f77">OPWV216</a> and <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aac41f58b414787f98d86d828f36250681">OPWV232</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a>, <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a> and <a href="#a9481f68151f53dba0f1e3416819e6e26">decodeSDWAVopcDst</a>.</p>

</div>
</div>

### getTTmpIdx() {#ae852f28eb2685d5dc30c78308011af7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int AMDGPUDisassembler::getTTmpIdx (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="#a40c6ec88b07c8f5dcfecacabe3007ecf">isGFX9Plus</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a> and <a href="#a9481f68151f53dba0f1e3416819e6e26">decodeSDWAVopcDst</a>.</p>

</div>
</div>

### getVgprClassId() {#a2a49c0ccc7c9aa0fe2692b60975f8ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUDisassembler::getVgprClassId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8355dd4c437a99c65c3d9f3b6f5101a">OpWidthTy</a> Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab94d3d679afc6c4f940d701c33cecee1">OPW1024</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa8ffffdcc951d4a57f5aa6bac5c04e33f">OPW128</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaac71e10a2d389621d890aa986f9d0466">OPW16</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf97d2901faed385ee707b87157401cfe">OPW160</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa01b1c271e4cb0b36b504a011e8287283">OPW192</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aabf21748608d2e79fe40afabedc73acec">OPW256</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab323e458551a652e29905a8646970ec1">OPW288</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa5960b4862125aa90147cba9dfb104f50">OPW32</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aacadff24cd85017f3815ad31e0d6ab424">OPW320</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aab0077d8f0741fa97a665bb6edeb4f8ef">OPW352</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa280444282f753f38ca2c05b21ab6bd86">OPW384</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa6f8b46bc6ca016b690e5fb7f8c4b3c52">OPW512</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaf4b2e7b624bfcb0b2c7116e43d97783a">OPW64</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa7a8a59cea7f5905c9fe60d781a6d58ea">OPW96</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa412d714f8ebb1d095d58e852d85f3efa">OPW_FIRST_</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aaaaa93b70a3d0d8ced191087633da35c7">OPW_LAST_</a>, <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aa157c08e03e0d0d3224f8e7fa03fc5f77">OPWV216</a> and <a href="#ab8355dd4c437a99c65c3d9f3b6f5101aac41f58b414787f98d86d828f36250681">OPWV232</a>.</p>


<p>Referenced by <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a>, <a href="#a84f8e99199a1dc95b1fd2a144aa79a6c">decodeSrcOp</a> and <a href="#a4ae2e98f9553b452f8c2b5107a8cb16a">decodeVOPDDstYOp</a>.</p>

</div>
</div>

### hasArchitectedFlatScratch() {#ad1bbaf8f762d31654b6a7580783122f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::hasArchitectedFlatScratch ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1982 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a1a717ebce0af699c0b264313d0cb21e2">decodeCOMPUTE_PGM_RSRC1</a>, <a href="#a341ce9a65b287f8033788c0bb12d8fa3">decodeCOMPUTE_PGM_RSRC2</a> and <a href="#a1ec298d8a742a9519e6dc0903f822f2b">decodeKernelDescriptorDirective</a>.</p>

</div>
</div>

### hasKernargPreload() {#a0b52b6c12bfcdcdede7a84beba3bbe10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::hasKernargPreload ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1986 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#adbe8b2394969d3cf98b70d46ce725354">llvm::AMDGPU::hasKernargPreload</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>

</div>
</div>

### isGFX10() {#aeee62e9882c0b90536eaa08027bbfef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isGFX10 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1960 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27e5626ce22d0cd09916837dc88b7efe">llvm::AMDGPU::isGFX10</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### isGFX10Plus() {#a515f1867e36cdffa566f9faa967bf2ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isGFX10Plus ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1962 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a852783bf1f53ae8e8e22a3042759f90b">AMDGPUDisassembler</a>, <a href="#ae5f0e6bc47c72961a9a05d307d6400f1">convertMIMGInst</a>, <a href="#a1a717ebce0af699c0b264313d0cb21e2">decodeCOMPUTE_PGM_RSRC1</a>, <a href="#a7de6bde5116ff125fb02491b47586333">decodeCOMPUTE_PGM_RSRC3</a>, <a href="#a66aa742680260d77ebab20536c828c17">decodeKernelDescriptor</a>, <a href="#a1ec298d8a742a9519e6dc0903f822f2b">decodeKernelDescriptorDirective</a> and <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a>.</p>

</div>
</div>

### isGFX11() {#a347423b9fcc60e76ff31a10a90bd5840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isGFX11 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1966 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a7de6bde5116ff125fb02491b47586333">decodeCOMPUTE_PGM_RSRC3</a> and <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### isGFX11Plus() {#af5cd2cf12e0610bc99b7c894f677b2f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isGFX11Plus ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1970 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a7de6bde5116ff125fb02491b47586333">decodeCOMPUTE_PGM_RSRC3</a>, <a href="#a865ae0d33ec9cd2b21d7b55470ac58d0">decodeSpecialReg32</a>, <a href="#a168a8034e9e01207fb71a39bde063d7f">decodeSpecialReg64</a>, <a href="#a318ce4a6802b51ada47c71f8692132ab">decodeSpecialReg96Plus</a> and <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### isGFX12() {#a18e19f604d742a99d805737f3d21ff62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isGFX12 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1974 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### isGFX12Plus() {#aa2a606a1a89df2407a17f844127bca7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isGFX12Plus ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1978 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a318d59d6a50364a460b64bb7ad1f17d0">llvm::AMDGPU::isGFX12Plus</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a1a717ebce0af699c0b264313d0cb21e2">decodeCOMPUTE_PGM_RSRC1</a> and <a href="#a7de6bde5116ff125fb02491b47586333">decodeCOMPUTE_PGM_RSRC3</a>.</p>

</div>
</div>

### isGFX9() {#ab9c9f9be5e439d07443ad92852b18f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isGFX9 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1952 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a626413fe751b97e13812bb7b635e6dd5">llvm::AMDGPU::isGFX9</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a1ec298d8a742a9519e6dc0903f822f2b">decodeKernelDescriptorDirective</a> and <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### isGFX90A() {#ae2163e267c5265155b8e5ac1f9306fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isGFX90A ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1954 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a7de6bde5116ff125fb02491b47586333">decodeCOMPUTE_PGM_RSRC3</a>.</p>

</div>
</div>

### isGFX9Plus() {#a40c6ec88b07c8f5dcfecacabe3007ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isGFX9Plus ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1958 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac251a1b5841022f34ff2791b1ce3b690">llvm::AMDGPU::isGFX9Plus</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a1a717ebce0af699c0b264313d0cb21e2">decodeCOMPUTE_PGM_RSRC1</a> and <a href="#ae852f28eb2685d5dc30c78308011af7f">getTTmpIdx</a>.</p>

</div>
</div>

### isMacDPP() {#ae75794f911e166bcea94523957bdec07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isMacDPP (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8f27aa11689bf9b12f6fb0e436e367c7">llvm::AMDGPU::hasNamedOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### isVI() {#a7297f920e9ff94394d81719b75080ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUDisassembler::isVI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1948 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a>.</p>

</div>
</div>

### onSymbolStart() {#afec69108aa44466b2b0dfdd41a76aab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; AMDGPUDisassembler::onSymbolStart (<a href="/web-llvm/docs/api/structs/llvm/symbolinfoty">SymbolInfoTy</a> &amp; Symbol, uint64_t &amp; Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address)</td>
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

<p>Used to perform separate target specific disassembly for a particular symbol.</p>


<p>May parse any prelude that precedes instructions after the start of a symbol, or the entire symbol. This is used for example by <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> to decode preludes.</p>


<p>Base implementation returns false. So all targets by default decline to treat symbols separately.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The number of bytes consumed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Address</td>
<td class="doxyParamItemDescription"><p>- The address, in the memory space of region, of the first byte of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bytes</td>
<td class="doxyParamItemDescription"><p>- A reference to the actual bytes at the symbol location.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>- True if this symbol triggered some target specific disassembly for this symbol. Size must be set with the number of bytes consumed.</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/error">Error</a> if this symbol triggered some target specific disassembly for this symbol, but an error was found with it. Size must be set with the number of bytes consumed.</li>
<li>False if the target doesn't want to handle the symbol separately. The value of Size is ignored in this case, and Err must not be set.</li>
</ul>
</dd>
</dl>


<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 2507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a66aa742680260d77ebab20536c828c17">decodeKernelDescriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a78554ab6218f194944dae873f7bb1563">llvm::ELF::STT_AMDGPU_HSA_KERNEL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a9803bad2cfdce7601000ee3f6b979d9b">llvm::ELF::STT_OBJECT</a>.</p>

</div>
</div>

### setABIVersion() {#a3391e8d688dabff24f81458e8867e450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUDisassembler::setABIVersion (unsigned Version)</td>
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

<p>ELF-specific, set the ABI version from the object header.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f9a0bcc6ecfeef7109258c6a8012978">llvm::AMDGPU::getAMDHSACodeObjectVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

### tryDecodeInst() {#aae4a6148a52bc05698e9890ee276e6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename InsnType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus llvm::AMDGPUDisassembler::tryDecodeInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Table, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, InsnType Inst, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Comments)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a68057d4a784ee78eca6f35d84936df6c">llvm::MCDisassembler::CommentStream</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>


<p>Referenced by <a href="#ad9305ad45a7db970a0a198791bea136a">getInstruction</a> and <a href="#ac8d70063859b434ed950708dc5d2434b">tryDecodeInst</a>.</p>

</div>
</div>

### tryDecodeInst() {#ac8d70063859b434ed950708dc5d2434b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename InsnType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus llvm::AMDGPUDisassembler::tryDecodeInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Table1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * Table2, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, InsnType Inst, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Comments)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#aae4a6148a52bc05698e9890ee276e6b1">tryDecodeInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createConstantSymbolExpr() {#aa51102a50cd2ee003b77179625bb13e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * AMDGPUDisassembler::createConstantSymbolExpr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id, int64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 2534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bytes {#a4b5a61f7256cb5fec8c5825d33bd57e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::AMDGPUDisassembler::Bytes</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### CodeObjectVersion {#ae4f7c537ff5fc08a730344fd7a2f120e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPUDisassembler::CodeObjectVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### EnableWavefrontSize32 {#a22c2d9dff8203615f9430e71e87de459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::AMDGPUDisassembler::EnableWavefrontSize32</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### HasLiteral {#a8b92d8479c9b4aa37d18845dbd5e2eff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUDisassembler::HasLiteral</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### Literal {#ab778cfb57f56fd98820c8dde6bb47aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::AMDGPUDisassembler::Literal</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### Literal64 {#a192e72a9b3153ee16e3a14ffcea4535a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AMDGPUDisassembler::Literal64</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### MAI {#a4f2a96e256ad9c2abdd042c074ed084e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo&amp; llvm::AMDGPUDisassembler::MAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### MCII {#a753d2143002854b389075e7b60f089de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCInstrInfo const&gt; const llvm::AMDGPUDisassembler::MCII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### MRI {#a7ad7a4636eb976abde114ff31593c4c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo&amp; llvm::AMDGPUDisassembler::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### TargetMaxInstBytes {#a0e8ab274ee961e63788a84896cd986bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::AMDGPUDisassembler::TargetMaxInstBytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### UCVersionMDPExpr {#a52396a2d490a8bc2dee7c15fb81766ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AMDGPUDisassembler::UCVersionMDPExpr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### UCVersionW32Expr {#aa5b9538afcf03c5ef6f621520c3298a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AMDGPUDisassembler::UCVersionW32Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### UCVersionW64Expr {#a5825ce4e0f1ff040a30e4cb8ee9c6960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::AMDGPUDisassembler::UCVersionW64Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decodeFPImmed() {#a7e463b2ce57bfddac123b8ae44feba93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeFPImmed (unsigned ImmWidth, unsigned Imm, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab41bbc27a953d3ed08c9d36c7b9ae272">AMDGPU::OperandSemantics</a> Sema)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a51cb222cd0ee12f7f7eb5c1aba1f1803">getInlineImmVal16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a96eff11e4ce91e92cfaa3e59f7600100">getInlineImmVal32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#aadb457499c6b9db87a068c5ae53ba32e">getInlineImmVal64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/encvalues/#a8827d0769d5975ce9edb64c48d3a6614a09d6b2004f2670f60b9963073f98226e">llvm::AMDGPU::EncValues::INLINE_FLOATING_C_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/encvalues/#a8827d0769d5975ce9edb64c48d3a6614a4e3fe67db06671a26db7cfaefb3d5322">llvm::AMDGPU::EncValues::INLINE_FLOATING_C_MIN</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a> and <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a>.</p>

</div>
</div>

### decodeIntImmed() {#ab55ea9f3ceb384181fdfd06df56cdd31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand AMDGPUDisassembler::decodeIntImmed (unsigned Imm)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 1408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>.</p>


<p>Referenced by <a href="#a7d7fece3c5c1c1d977334eb948baecfe">decodeNonVGPRSrcOp</a> and <a href="#a654a634c301c3ad83782795b18260031">decodeSDWASrc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
