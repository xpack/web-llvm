---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HexagonDisassembler` Class

<p><a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> disassembler for all <a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> platforms. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonDisassembler.cpp}::HexagonDisassembler { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247d0faf64fb68b3e5ebc203adc6223f">HexagonDisassembler</a> (const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx, MCInstrInfo const *MCII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0816f42a174972f6c2b099e9f7b6bc6">getSingleInstruction</a> (MCInst &amp;Instr, MCInst &amp;MCB, ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address, raw_ostream &amp;CStream, bool &amp;Complete) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a963b35ab133a680b8e40743b1780d099">getInstruction</a> (MCInst &amp;Instr, uint64_t &amp;Size, ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address, raw_ostream &amp;CStream) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the disassembly of a single instruction. <a href="#a963b35ab133a680b8e40743b1780d099">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3698352988800e925904a78b2701c04">remapInstruction</a> (MCInst &amp;Instr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  &gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29f61978d19ce197dc2ff89cf4b3750">MCII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda36ec325e6f85df6877286392d544d">CurrentBundle</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34045a679c93f10aa18b84f8fc653a98">CurrentExtender</a></td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> disassembler for all <a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> platforms.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonDisassembler() {#a247d0faf64fb68b3e5ebc203adc6223f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::HexagonDisassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * MCII)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="#acda36ec325e6f85df6877286392d544d">CurrentBundle</a>, <a href="#a34045a679c93f10aa18b84f8fc653a98">CurrentExtender</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a07639073d0bfe2f90b94ced7f2944596">llvm::MCDisassembler::MCDisassembler</a>, <a href="#ac29f61978d19ce197dc2ff89cf4b3750">MCII</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a20a8e4705041b6319c008c1e981eee45">brtargetDecoder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a4a9f9bc1fdf428c5e7544a0424a8cc8f">createHexagonDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a2a753b4c73b07ef8f90dcada88f6ef4d">s32_0ImmDecoder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a42a94b0bc3b45d5b82f8cf8d26dc8449">unsignedImmDecoder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInstruction() {#a963b35ab133a680b8e40743b1780d099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus HexagonDisassembler::getInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Instr, uint64_t &amp; Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CStream)</td>
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
<td class="doxyParamItemDescription"><p>- An MCInst to populate with the contents of the instruction.</p></td>
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
<dd><p>- MCDisassembler::Success if the instruction is valid, MCDisassembler::SoftFail if the instruction was disassemblable but invalid, MCDisassembler::Fail if the instruction was invalid.</p></dd>
</dl>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcchecker/#a51fa2302a4a13602a1942ab9cd7588ff">llvm::HexagonMCChecker::check</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae86bea5bf6fe3c0a2a9f09f5fdc4a310">llvm::MCOperand::createInst</a>, <a href="#acda36ec325e6f85df6877286392d544d">CurrentBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#a42d7fe1ef88cc2906006661704af630f">llvm::Hexagon_MC::getArchSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a3faa10cafd0be721018fc1b9bc2c5488">llvm::MCDisassembler::getContext</a>, <a href="#ab0816f42a174972f6c2b099e9f7b6bc6">getSingleInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8b3161e980be30851bf3f346ca0550ce">HEXAGON_INSTR_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a033904b52204dcda98d7bfac83b6c679">HEXAGON_MAX_PACKET_SIZE</a>, <a href="#ac29f61978d19ce197dc2ff89cf4b3750">MCII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ad3698352988800e925904a78b2701c04">remapInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### getSingleInstruction() {#ab0816f42a174972f6c2b099e9f7b6bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus HexagonDisassembler::getSingleInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Instr, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CStream, bool &amp; Complete)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a6f793a0798fab60a5fd44654d33dbf21">adjustDuplex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a607343a05725b53e0d5bd85a4a44586e">llvm::HexagonMCInstrInfo::bundleInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a246da06f2e49f678663ae6e21bedffb3">llvm::HexagonMCInstrInfo::bundleSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae86bea5bf6fe3c0a2a9f09f5fdc4a310">llvm::MCOperand::createInst</a>, <a href="#acda36ec325e6f85df6877286392d544d">CurrentBundle</a>, <a href="#a34045a679c93f10aa18b84f8fc653a98">CurrentExtender</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a92a5e3cfec25537762fd0102dfeb23af">llvm::HexagonMCInstrInfo::extenderForIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a3faa10cafd0be721018fc1b9bc2c5488">llvm::MCDisassembler::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a44c5cbb3128220471c20639331ef9356">llvm::HexagonMCInstrInfo::getNewValueOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a96d1b18f6b327cd31760f1e6086ab7f8">llvm::HexagonMCInstrInfo::getNewValueOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aec6caa48fc271621aca9478a1c4a4268">llvm::HexagonMCInstrInfo::getNewValueOperand2</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#afa5e44937784daa4bb42a20a52ba5da3">llvm::HexagonMCInstrInfo::hasNewValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aa7bc69c19bc9f59a5e5c3161d034a71f">llvm::HexagonMCInstrInfo::hasNewValue2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8b3161e980be30851bf3f346ca0550ce">HEXAGON_INSTR_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#aeb96f895eb86ce028d6b45f80bbdba20afff861bd25343511b2bcdd1f7baed3a7">llvm::HexagonII::INST_PARSE_DUPLEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#aeb96f895eb86ce028d6b45f80bbdba20acc0a7f2184c7b9b7580796e31f5bcea0">llvm::HexagonII::INST_PARSE_LOOP_END</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#aeb96f895eb86ce028d6b45f80bbdba20ac5ea31d1f50c020d5d4af0a53fbd348e">llvm::HexagonII::INST_PARSE_MASK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#aeb96f895eb86ce028d6b45f80bbdba20a8eb40a3906fddc8fc297fd2647d5af84">llvm::HexagonII::INST_PARSE_PACKET_END</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a26ecf3daf01c489f01b5bf6953827080">llvm::HexagonMCInstrInfo::isDuplex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a8c525c01df0d371a390190574d22bccc">llvm::HexagonMCInstrInfo::isExtendable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#af57335bfd112468cfe89cb1bf7f205be">llvm::HexagonMCInstrInfo::isExtended</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a95c527167756007a3fb2ab49ec4b2c6d">llvm::HexagonMCInstrInfo::isImmext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a41c2639831016e233df65de1a6ec6bd3">llvm::HexagonMCInstrInfo::isNewValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a150c2ac48d241ceb656546c6c482c03a">llvm::HexagonMCInstrInfo::IsReverseVecRegPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a56307e938767b5cad81b457fa6b7f3bc">llvm::HexagonMCInstrInfo::IsVecRegPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ae72685c5f32e967a3708d52677f1226b">llvm::HexagonMCInstrInfo::isVector</a>, <a href="#ac29f61978d19ce197dc2ff89cf4b3750">MCII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvmoduleanalysis-cpp/#acaab1e2660e7055669741c9f485e26c5">OpIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a423fa247fcb4eadd2ba802397a79641b">llvm::HexagonMCInstrInfo::setInnerLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a0eae7cb5eae56054e1b89dfbe489a0f1">llvm::HexagonMCInstrInfo::setOuterLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a604722fe2776c0df4d275cff37a37d95">llvm::MCOperand::setReg</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>


<p>Referenced by <a href="#a963b35ab133a680b8e40743b1780d099">getInstruction</a>.</p>

</div>
</div>

### remapInstruction() {#ad3698352988800e925904a78b2701c04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonDisassembler::remapInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a607343a05725b53e0d5bd85a4a44586e">llvm::HexagonMCInstrInfo::bundleInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a963b35ab133a680b8e40743b1780d099">getInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurrentBundle {#acda36ec325e6f85df6877286392d544d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCInst *&gt; anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::CurrentBundle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Referenced by <a href="#a963b35ab133a680b8e40743b1780d099">getInstruction</a>, <a href="#ab0816f42a174972f6c2b099e9f7b6bc6">getSingleInstruction</a> and <a href="#a247d0faf64fb68b3e5ebc203adc6223f">HexagonDisassembler</a>.</p>

</div>
</div>

### CurrentExtender {#a34045a679c93f10aa18b84f8fc653a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst const* anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::CurrentExtender</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a2e0e4ab18e7fb56c7dbd46fe864243e6">anonymous{HexagonDisassembler.cpp}::fullValue</a>, <a href="#ab0816f42a174972f6c2b099e9f7b6bc6">getSingleInstruction</a> and <a href="#a247d0faf64fb68b3e5ebc203adc6223f">HexagonDisassembler</a>.</p>

</div>
</div>

### MCII {#ac29f61978d19ce197dc2ff89cf4b3750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCInstrInfo const&gt; const anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::MCII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-hexagondisassembler-cpp-/#a2e0e4ab18e7fb56c7dbd46fe864243e6">anonymous{HexagonDisassembler.cpp}::fullValue</a>, <a href="#a963b35ab133a680b8e40743b1780d099">getInstruction</a>, <a href="#ab0816f42a174972f6c2b099e9f7b6bc6">getSingleInstruction</a> and <a href="#a247d0faf64fb68b3e5ebc203adc6223f">HexagonDisassembler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
