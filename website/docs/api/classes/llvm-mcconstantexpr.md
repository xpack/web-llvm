---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcconstantexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCConstantExpr` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCConstantExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for the full range of assembler expressions which are needed for parsing. <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb36a7f2a4d5526555ccde63e436c65">MCConstantExpr</a> (int64_t Value, bool PrintInHex, unsigned SizeInBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3e6697a2e3a3c788d319b9cc1cb3749">Value</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ffc3c2b42f106ac63cc782667bfdbc">classof</a> (const MCExpr *E)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bb86ea091b25c28b8c295f5638609d8">encodeSubclassData</a> (bool PrintInHex, unsigned SizeInBytes)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1aeaa12b290784669b012ea6be48228">SizeInBytesBits</a> = 8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a89955415ebc7269c3950e9ebd26c60">SizeInBytesMask</a> = (1 &lt;&lt; SizeInBytesBits) - 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af604b9d4a3a383e5a9a936fcd4ae8228">PrintInHexBit</a> = 1 &lt;&lt; SizeInBytesBits</td>
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

## Construction Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr">MCConstantExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9bdc4c9c65ea1ff077fbbb6407d7b2a">create</a> (int64_t Value, MCContext &amp;Ctx, bool PrintInHex=false, unsigned SizeInBytes=0)</td>
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

## Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89859d5c7657c00986cd1f33cbcdb8ad">getValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a723344f63b9a579c118f9fdf8f7d6cac">getSizeInBytes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515212db43234f10b2a1a10bb66a9db9">useHexFormat</a> () const</td>
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


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### MCConstantExpr() {#a0eb36a7f2a4d5526555ccde63e436c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCConstantExpr::MCConstantExpr (int64_t Value, bool PrintInHex, unsigned SizeInBytes)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Value {#ad3e6697a2e3a3c788d319b9cc1cb3749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MCConstantExpr::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a34ffc3c2b42f106ac63cc782667bfdbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCConstantExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d">llvm::MCExpr::Constant</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a7c94b145b6ade90726e2bab678ddc708">llvm::MCExpr::MCExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### encodeSubclassData() {#a4bb86ea091b25c28b8c295f5638609d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCConstantExpr::encodeSubclassData (bool PrintInHex, unsigned SizeInBytes)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### PrintInHexBit {#af604b9d4a3a383e5a9a936fcd4ae8228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCConstantExpr::PrintInHexBit = 1 &lt;&lt; SizeInBytesBits</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

### SizeInBytesBits {#ab1aeaa12b290784669b012ea6be48228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCConstantExpr::SizeInBytesBits = 8</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

### SizeInBytesMask {#a1a89955415ebc7269c3950e9ebd26c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::MCConstantExpr::SizeInBytesMask = (1 &lt;&lt; SizeInBytesBits) - 1</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Construction

### create {#af9bdc4c9c65ea1ff077fbbb6407d7b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCConstantExpr * MCConstantExpr::create (int64_t Value, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, bool PrintInHex=false, unsigned SizeInBytes=0)</td>
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



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a10e72ca32e8206bcc1a9ec642a797e44">llvm::HexagonMCInstrInfo::addConstant</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a4664c509547eec1f1063959c2159a6b3">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addSignedImmOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a6f793a0798fab60a5fd44654d33dbf21">adjustDuplex</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a74dc10b4ec4a74b8a4379ea8f6edb221">llvm::AMDGPU::MCKernelDescriptor::bits_get</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#a9e9129ae20b8f08b24f78bd53bb0c11e">llvm::AMDGPU::MCKernelDescriptor::bits_set</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#ae18928643ad012c59561c9e50dc452fa">computeAccumOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a99e0974cd15aab665b6eba448cd94a5f">llvm::AMDGPUMCExpr::createExtraSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#a528b669c7627f74c541a4800020df024">llvm::AMDGPUMCExpr::createOccupancy</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a64b42038a61a3c4b1880eea5331cdb44">llvm::AMDGPUDisassembler::decodeVersionImm</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a99ca9bd4a32a51a2f03d00ad2f09b572">llvm::AMDGPUTargetELFStreamer::emitAMDGPULDS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#abf468fdf1fecb6e06d29a8cbfaa808bb">llvm::AMDGPUTargetAsmStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#aac2390b5c807bff61a3eaa2ce2430543">llvm::AMDGPUTargetELFStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a082d0b0afa7b05bf751feabbc3550f2b">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitArrayBound</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a1b7e117c34782423f4cab2396b42b059">llvm::MCWinCOFFStreamer::emitCOFFImgRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a6dbbe16f1a57144b250b2b3ba1243e93">llvm::MCWinCOFFStreamer::emitCOFFSecRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a29a3c5dc6082aabd411724f33011f795">llvm::MCELFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#abc85cf8fcb99aada0bb615989928b516">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLineStartLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#af0cbac92300c3074e6bb81d58e92a86b">llvm::WebAssemblyAsmPrinter::emitEndOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a43decaae146363e80c3ba5b685016bb5">llvm::CodeViewContext::emitFileChecksums</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af6a6f6142b6fd138cdc9e08217577c4d">llvm::MCStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a953d00375e745bab150d06ba9ced5802">llvm::AsmPrinter::emitFrameAlloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a0e3f4587b93083fdc01e3ec8f66b3701">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitFunctionBodyStart</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#ab7906bdf774a35b56cb2e908d012472c">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a25956df5af6db1ef928aa17999d28727">llvm::SystemZAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a11156cb1f872cbe35d40c6f36a21d56f">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a02ddab75d51b8f46e8e2327dbb0e367b">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitIntValueInHex</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a9e376ffce522c2c85b62c86d18867336">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitIntValueInHexWithPadding</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a11d81bc488e34bd6e757c2831ecc5e42">llvm::ARMAsmPrinter::emitJumpTableAddrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a7b744276265a7587d11961d5cbf82dd0">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a27e1e6e35a8e68da67d5090a6e9f4c0d">llvm::ARMAsmPrinter::emitJumpTableTBInst</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet/#a766a8f22f00b2895f373b0328840e760">llvm::AMDGPU::AMDGPUMCKernelCodeT::EmitKernelCodeT</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2380b3abc7ab19ec1af9883a5f7bbd67">llvm::AsmPrinter::emitLabelPlusOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a2aca46ca706a8a857dc668e015740e53">llvm::XtensaAsmPrinter::emitMachineConstantPoolEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a6d60dc7f70a5ab7a44c79f6bba354c0f">llvm::TargetLoweringObjectFileELF::emitPersonalityValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#adae657ab9991540e975726434ee1f053">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#ac7b652d5871240542b523c9d9fd950b5">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#acd56f0ff4ca0b0bb54682c0e195c7589">llvm::AVRAsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1208c7bbb9786b85087c70ba698fd54f">llvm::X86AsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a70e3e2288f783c384791e314b8e20231">EmitSymbolRefWithOfs</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a0c5eda02c50a11f3dde025afe0675b6e">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::EmitTlsCall</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25e51557ff442df4d50f2ad5d1f55743">llvm::AsmPrinter::emitXRayTable</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kmccodeemitter-cpp-/m68kmccodeemitter/#ae9def4fef17a8e66265e30f687158adf">anonymous{M68kMCCodeEmitter.cpp}::M68kMCCodeEmitter::encodePCRelImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#ac6740cbf8bbdd52574f85db63500cd25">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#afa2b2e58e0859c0608b6f10a8ad1c79f">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a595765b8c36eef76cb8f2a6dfd10c277">llvm::AMDGPUTargetELFStreamer::finish</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae7810a05a90e7fc6d13fa85c0242ab5f">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::getAdjustedFasterLocalExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a1a53bd2f56709e4b8ec00e8ae0447e4f">llvm::MipsMCCodeEmitter::getBranchTarget21OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#add4d66dd8382e6b4fe7fa789844f1e27">llvm::MipsMCCodeEmitter::getBranchTarget21OpValueMM</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a9332e7f86488ac03e792fde668bac68e">llvm::MipsMCCodeEmitter::getBranchTarget26OpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a93c2d268f594d31d146df08d1c0e007e">llvm::MipsMCCodeEmitter::getBranchTarget26OpValueMM</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a6b63701360781e817473a4818ce94912">llvm::MipsMCCodeEmitter::getBranchTargetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#aa1dfb38c5dc5e51389464d20e369678f">llvm::MipsMCCodeEmitter::getBranchTargetOpValue1SImm16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a07ecbb2c17eb03d8c4755dc5cfd88a5a">llvm::MipsMCCodeEmitter::getBranchTargetOpValueLsl2MMR6</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#a6928f0f796b63f34abf586618d0ebba7">llvm::MipsMCCodeEmitter::getBranchTargetOpValueMMR6</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a4c73e82c5082e2f77d5647e1034eb81d">llvm::SIProgramInfo::getComputePGMRSrc1</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a318d26ac513db990b9466b1ce9380032">llvm::SIProgramInfo::getComputePGMRSrc2</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#a4824f185b09fa4322916df3508816b22">llvm::MipsTargetObjectFile::getDebugThreadLocalSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#ae427ea6c3fad2449f851240892963b14">llvm::AMDGPU::MCKernelDescriptor::getDefaultAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/x86-64mcasminfodarwin/#a2718196f3a76adab2b39bcdff3f3cb44">llvm::X86_64MCAsmInfoDarwin::getExprForPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a496a589a4ca89aafae1db05782b62cde">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::getExprOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#a847e5bb4507e49e9af8582df2cb12f50">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::getImmOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#ab479db6c0dce9d07c70ea70016ed99ff">llvm::AArch64_ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#a62d13f21f5dde00137a248d95cf8acd6">llvm::ARMElfTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#affc824acbbe220a54656c5519b408c4b">llvm::RISCVELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64elftargetobjectfile/#a7fade16e9dc1ebc9b6974b12857f5abe">llvm::X86_64ELFTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64machotargetobjectfile/#abe4296cf38fa7bebb355865172c0acac">llvm::X86_64MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#abe52a78f5c8a6b91ae15c4635ccf564e">llvm::SIProgramInfo::getPGMRSrc1</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a15f8b9a5641db8dcff762d1190a285dc">llvm::SIProgramInfo::getPGMRSrc2</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ab0816f42a174972f6c2b099e9f7b6bc6">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getSingleInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aaab77f3694a5bc3b29ffbc6ce87444ad">GetSubDivExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp/#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-64machotargetobjectfile/#a17558be02e5c14c099a7f347669a3132">llvm::X86_64MachoTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a64f1accd42a5eb6c0d80c800e63123b9">llvm::HexagonMCELFStreamer::HexagonMCEmitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/amdgpumckernelcodet/#a9dfce6025a9fbad86f7dd26156f36912">llvm::AMDGPU::AMDGPUMCKernelCodeT::initDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpumcinstlower-h-/#aed8f360a779835ad5c5e36181744af3d">anonymous{AMDGPUMCInstLower.h}::lowerAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac2b1c517d194a6bdd00f66bce97f52c3">llvm::AsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a55d9cc47f7041c1afad87f88ec5c7636">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::lowerConstantPtrAuth</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a55859f4a9f64b42f225c2f6c63212be5">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#a9bdd6ed65ae27d68d065f712e0d281de">llvm::LanaiMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ab8310eee0e086d64c49733dd9da4171b">llvm::M68kMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a8520755e983a50f3c24f91e0f8e06d03">llvm::MSP430MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a153a3f96b2710ef9d924d8168a93482b">llvm::XtensaAsmPrinter::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#a5edb97651738551635eb05cc3f9fa77c">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#acb4de1517ebc1f8095f87eef68f290f7">llvm::AVRMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a48efbf9c526eceb30f721ea086dc98fd">llvm::AArch64MCInstLower::lowerSymbolOperandCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ae4b8638e074c6af2301cd209d3d2021c">llvm::AArch64MCInstLower::lowerSymbolOperandMachO</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ad484999912240f5615d60831473902cd">makeStartPlusIntExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#af999327aaf208e1dcb5c3c60d6c2452c">MaskShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8749a42239506716ab09647dd0b31795">llvm::AMDGPU::maskShiftGet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f3ff39c7ddc47c851a92a89a6c68e3d">llvm::AMDGPU::maskShiftSet</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#a1a1853bf4db9f8b2acf588859ee22f76">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveSubsection</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#ac7fc5af218d2f17280c5b443dbe20838">anonymous{AsmParser.cpp}::AsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46e587fd477a44bb0b3c9e3689ff2f92">anonymous{MasmParser.cpp}::MasmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a89eeee4c3ec5d281810e8ac7572ddee4">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ae72726562d2c74f257bb14d331c90300">llvm::SIProgramInfo::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a931125c9821366d0a4f14a4f8e423f95">llvm::AMDGPUAsmPrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a7e075cc11fc81de8e280e3cdf8560ef3">ScaleVectorOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a44fe092bd112e2eb16c1cba213922aca">llvm::AMDGPUPALMetadata::setRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a21aceafe085b9a14a9864954b9fdb14b">llvm::MCContext::setSymbolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a9f78db3a67945349cd7bcee045f65b1b">llvm::RISCVAsmBackend::shouldInsertFixupForCodeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a246c8dfd4ca957b7da4d52cb7805650c">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseAdjImm0_63</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors

### getSizeInBytes {#a723344f63b9a579c118f9fdf8f7d6cac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCConstantExpr::getSizeInBytes ()</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ad7a73c5ca50f673d05234b59a93bfa29">llvm::MCExpr::getSubclassData</a>.</p>

</div>
</div>

### getValue {#a89859d5c7657c00986cd1f33cbcdb8ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MCConstantExpr::getValue ()</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab44f4b2113b7a3876bd7e61758319c6f">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addAdrpLabelOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aab7d7b59c23bda548073770ccaaa1f54">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBranchTarget14Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aa1448a1c0dc861047a4abeab5dfa3d57">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBranchTarget26Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#acd4ed46a8bba14b6e611e0e34a5e02cc">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addComplexRotationEvenOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a0e16e22e5918c7110f0f7658b61f53e8">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addComplexRotationOddOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ad09ecb52e79c8bef77dea3fa313c9a31">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmScaledOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ae997d5e3fd8015241b318c4b0da0c194">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLogicalImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a94b3cbab03d77b6119bf4ffb8dc5b21d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPAuthPCRelLabel16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a418048be5c0be53d70dec5000e5d4a7b">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPCRelLabel19Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#acbecf14320c5f3c8b0156ccc7a9ee39b">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPCRelLabel9Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a275d93f01f3c0461c602869aa89a1fad">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSIMDImmType10Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aade413b77f569da1d358d025182ced99">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addUImm12OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a3cc87770d7b78bdaebb4b74db9dfd78f">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addUImm6Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a2c00c11ef810b9f4ca1781a341de60d3">llvm::CodeViewContext::encodeInlineLineTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a6502fd15601fbefa6de9a3c3f2a15a0d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isBranchTarget</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#ab6b0c7909cd1c59c0450d9d1a8493bc9">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isBrImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#ae57fbd0e584ec2382b9940e01e19d768">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isCondCode</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a7a980e5bb4840109e1822c062cbfafa7">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isHiImm16And</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#acb23248dfc6a00019f3f78d74a2b45b1">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isImm10</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a0f6c1755e5ae566a87d87508d3cee9dc">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImmInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4a18544038561f8c08b8ea6d6da02784">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImmScaled</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a3aaf84fd1fc76bb95d588ff92b53c672">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isImmShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a9d689d56ccbeb5bad8afd84d615d31b7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isLogicalImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#ade0aa7301c37915069aa87297225d180">anonymous{LanaiAsmParser.cpp}::LanaiOperand::isLoImm16And</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4f7622e49d7747dc8b2b9ee2f586a4c9">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isPAuthPCRelLabel16Operand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aa1892421b1a924f86a66c28974d47c7d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSIMDImmType10</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a82e2a376717221b4993b1fc95415bde9">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isUImm12Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a36d0b74dbf90ea3967907f05a88b06a2">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isUImm6</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a3836dbcbb0e7b8207e5b1f40a85269af">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParsePrefetch</a>.</p>

</div>
</div>

### useHexFormat {#a515212db43234f10b2a1a10bb66a9db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCConstantExpr::useHexFormat ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ad7a73c5ca50f673d05234b59a93bfa29">llvm::MCExpr::getSubclassData</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">MCExpr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp">MCExpr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
