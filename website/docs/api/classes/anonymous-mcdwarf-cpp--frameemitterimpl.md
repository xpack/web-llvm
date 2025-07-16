---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FrameEmitterImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MCDwarf.cpp}::FrameEmitterImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd7a78d5ed414219a63412f4812e0f0">FrameEmitterImpl</a> (bool IsEH, MCObjectStreamer &amp;Streamer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53a38280a7cf030655d4ad153dcf8cc1">EmitCompactUnwind</a> (const MCDwarfFrameInfo &amp;frame)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the unwind information in a compact way. <a href="#a53a38280a7cf030655d4ad153dcf8cc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06884c9e11f3d8bb503abfb8dc03586b">EmitCIE</a> (const MCDwarfFrameInfo &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9503972de494ac87e3025a25bbbbb6">EmitFDE</a> (const MCSymbol &amp;cieStart, const MCDwarfFrameInfo &amp;frame, bool LastInSection, const MCSymbol &amp;SectionStart)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3faa8e5c64af2110e902fed6c4dce689">emitCFIInstructions</a> (ArrayRef&lt; MCCFIInstruction &gt; Instrs, MCSymbol *BaseLabel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit frame instructions to describe the layout of the frame. <a href="#a3faa8e5c64af2110e902fed6c4dce689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a483ddfcbeaea69d0917549e79f76e7fe">emitCFIInstruction</a> (const MCCFIInstruction &amp;Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94e023a5cbce33e212bc7821ed433a29">CFAOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fb04b46559bb785aff5b7fb05231a2f">InitialCFAOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332c588124ab34d7fa272310a9ffebdb">IsEH</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01915bad0e230284f532acc45afe1ae6">Streamer</a></td>
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


<p>Definition at line 1328 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FrameEmitterImpl() {#abbd7a78d5ed414219a63412f4812e0f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MCDwarf.cpp}::FrameEmitterImpl::FrameEmitterImpl (bool IsEH, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> &amp; Streamer)</td>
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



<p>Definition at line 1335 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitCFIInstruction() {#a483ddfcbeaea69d0917549e79f76e7fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FrameEmitterImpl::emitCFIInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a> &amp; Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1346 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ab521cbeeba5f775524447eec5b221d56">getDataAlignmentFactor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecaea7047186e58e6304947fbe2b12963ca">llvm::MCCFIInstruction::OpAdjustCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecacbbd41f459c6cea155b66a7ba10f1058">llvm::MCCFIInstruction::OpDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca5822faf65b27795cd48bd44712d48927">llvm::MCCFIInstruction::OpDefCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca238c64d5f2c2fea57085c0238948b04f">llvm::MCCFIInstruction::OpDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecaf15acea66ebc677cba2af933cc86c953">llvm::MCCFIInstruction::OpEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca3f760b48a6b6d7dbd15f414986c12dc9">llvm::MCCFIInstruction::OpGnuArgsSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecad8166a4b87f2c30cb19a0d8095736fd6">llvm::MCCFIInstruction::OpLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca41d79805b057315fb8e3593987b4fe6d">llvm::MCCFIInstruction::OpLLVMDefAspaceCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecaa66d4b16f63e1a1f48ab0a412e105d84">llvm::MCCFIInstruction::OpNegateRAState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca66624166e3d049539c5275c2a92993bc">llvm::MCCFIInstruction::OpNegateRAStateWithPC</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca74ec33979cec7221719caa137b50da3f">llvm::MCCFIInstruction::OpOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca47154c1d7af6be5e653ad8d1647efef1">llvm::MCCFIInstruction::OpRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca829be22c6230d5b270c57913ab767d66">llvm::MCCFIInstruction::OpRelOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca9725887cea764021d6f8d670f28f1ae5">llvm::MCCFIInstruction::OpRememberState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecab1624e2be4e6b5b590bcc4743241c0a8">llvm::MCCFIInstruction::OpRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca52e7e859e3f36138023caadf8991d04b">llvm::MCCFIInstruction::OpRestoreState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecab85cb8f2dc33b315db03abc258d2d7d0">llvm::MCCFIInstruction::OpSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca3d6a7342ab1bccb9ac138911f12e2eb4">llvm::MCCFIInstruction::OpUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca9bc8a1d177bcfde894a63285618df9c9">llvm::MCCFIInstruction::OpValOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca3316e063e766219c3a12d004d2d10afd">llvm::MCCFIInstruction::OpWindowSave</a>.</p>


<p>Referenced by <a href="#a3faa8e5c64af2110e902fed6c4dce689">emitCFIInstructions</a>.</p>

</div>
</div>

### emitCFIInstructions() {#a3faa8e5c64af2110e902fed6c4dce689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FrameEmitterImpl::emitCFIInstructions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a> &gt; Instrs, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * BaseLabel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit frame instructions to describe the layout of the frame.</p>

<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Reference <a href="#a483ddfcbeaea69d0917549e79f76e7fe">emitCFIInstruction</a>.</p>


<p>Referenced by <a href="#a06884c9e11f3d8bb503abfb8dc03586b">EmitCIE</a> and <a href="#a3d9503972de494ac87e3025a25bbbbb6">EmitFDE</a>.</p>

</div>
</div>

### EmitCIE() {#a06884c9e11f3d8bb503abfb8dc03586b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol &amp; FrameEmitterImpl::EmitCIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1341 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a2d5ea8ed8f8ff79c7b1844d329b22ebe">llvm::dwarf::DW64_CIE_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0a2cfb047bef74739998077d46fb6ccb">llvm::dwarf::DW_CIE_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4adc3aedef0caeccf6d845a430da6d3f8d">llvm::dwarf::DW_LENGTH_DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a479c805988e7c9a81faae52757503066">emitAbsValue</a>, <a href="#a3faa8e5c64af2110e902fed6c4dce689">emitCFIInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#aabfe51a98519272e0f4ee5e0fdcb90b0">emitEncodingByte</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#aa5b673bb0b1684ee529dc9fcafd6167b">EmitPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a845dfa10e848411e52b9dbba304cb887">getCIEVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#affd5fd4fc8ca1b0f483c51543e58108d">llvm::MCAsmInfo::getCodePointerSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ab521cbeeba5f775524447eec5b221d56">getDataAlignmentFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae871de84d03670534d73ae7448b6b6d9">llvm::MCContext::getDwarfFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a99c58fcbed2434b9535b866015cd0259">llvm::MCContext::getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a9b753f5b5ed5d2d28462e83e7c5e923b">llvm::MCObjectFileInfo::getFDEEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a3c2da6516abf838b5ed237b05fc9ae57">llvm::MCAsmInfo::getInitialFrameState</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a2c92e93d2452cf0ad4bc91c46685425b">llvm::MCAsmInfo::getMinInstAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7eff7fcbe27aa063e7dced4042ca3416">llvm::MCContext::getRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae482cc4ee4cf4d5b4bfe6e1dde4f1ed8">getSizeForEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0b741aef91502fa04c0f5265a58ba45c">llvm::dwarf::getUnitLengthFieldByteSize</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a433d11c67a32132351c98de2b8065284">llvm::MCDwarfFrameInfo::IsBKeyFrame</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad80999a465c92131481073b2fce9d5ed">llvm::MCDwarfFrameInfo::IsMTETaggedFrame</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a8711bbf8d91d469855854590ab674e15">llvm::MCDwarfFrameInfo::IsSignalFrame</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a1ddd4c949a45e7d0f88d8661584d6798">llvm::MCDwarfFrameInfo::IsSimple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#aedbfd737ebf204c167470729f2ec0042">llvm::MCDwarfFrameInfo::Lsda</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad8d9360321fbcbdb17515c2d227f75fa">llvm::MCDwarfFrameInfo::LsdaEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a3c371b9d29a2da49e836e29ac73b359b">llvm::MCDwarfFrameInfo::Personality</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a932960bf69710f1094b4e6d8fc5d627c">llvm::MCDwarfFrameInfo::PersonalityEncoding</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ac75bed23a3d4eac190a5e9f4c1c7abc0">llvm::MCDwarfFrameInfo::RAReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adb9ddd77a3cbc6e719b2ff77e0a2efcf">RAReg</a>.</p>

</div>
</div>

### EmitCompactUnwind() {#a53a38280a7cf030655d4ad153dcf8cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FrameEmitterImpl::EmitCompactUnwind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &amp; frame)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the unwind information in a compact way.</p>

<p>Definition at line 1339 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#aca389e403a6d34682ba72a9120c3f83c">llvm::MCDwarfFrameInfo::Begin</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#aba0776b50178c515003db66042e730e6">llvm::MCDwarfFrameInfo::CompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab8bb265a153372d87860f6a33d858f3e">llvm::dwarf::DW_EH_PE_absptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abfafdba601fd5cab55113f2cdb96c033">llvm::dwarf::DW_EH_PE_udata4</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a479c805988e7c9a81faae52757503066">emitAbsValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a4a28a7bafd6aef6062f253778813f217">llvm::MCDwarfFrameInfo::End</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a5eb24afad571f2444e56298ef8c2693f">llvm::MCObjectFileInfo::getCompactUnwindDwarfEHFrameOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a9b753f5b5ed5d2d28462e83e7c5e923b">llvm::MCObjectFileInfo::getFDEEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae482cc4ee4cf4d5b4bfe6e1dde4f1ed8">getSizeForEncoding</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#aedbfd737ebf204c167470729f2ec0042">llvm::MCDwarfFrameInfo::Lsda</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad8d9360321fbcbdb17515c2d227f75fa">llvm::MCDwarfFrameInfo::LsdaEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a3c371b9d29a2da49e836e29ac73b359b">llvm::MCDwarfFrameInfo::Personality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### EmitFDE() {#a3d9503972de494ac87e3025a25bbbbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FrameEmitterImpl::EmitFDE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; cieStart, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> &amp; frame, bool LastInSection, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; SectionStart)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1342 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#aca389e403a6d34682ba72a9120c3f83c">llvm::MCDwarfFrameInfo::Begin</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a917f23f8bbeb0cb04446cf1dfa039787">llvm::MCAsmInfo::doesDwarfUseRelocationsAcrossSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab8bb265a153372d87860f6a33d858f3e">llvm::dwarf::DW_EH_PE_absptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4adc3aedef0caeccf6d845a430da6d3f8d">llvm::dwarf::DW_LENGTH_DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a479c805988e7c9a81faae52757503066">emitAbsValue</a>, <a href="#a3faa8e5c64af2110e902fed6c4dce689">emitCFIInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a07c0db5089a287c91b8197cad7f2eeda">emitFDESymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a4a28a7bafd6aef6062f253778813f217">llvm::MCDwarfFrameInfo::End</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#affd5fd4fc8ca1b0f483c51543e58108d">llvm::MCAsmInfo::getCodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae871de84d03670534d73ae7448b6b6d9">llvm::MCContext::getDwarfFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a9b753f5b5ed5d2d28462e83e7c5e923b">llvm::MCObjectFileInfo::getFDEEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae482cc4ee4cf4d5b4bfe6e1dde4f1ed8">getSizeForEncoding</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#aedbfd737ebf204c167470729f2ec0042">llvm::MCDwarfFrameInfo::Lsda</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad8d9360321fbcbdb17515c2d227f75fa">llvm::MCDwarfFrameInfo::LsdaEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a831093d85c75c64067ee4ecd1e811860">makeEndMinusStartExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a7712b3a2d11d7c25f0378d814255b253">llvm::MCAsmInfo::needsDwarfSectionOffsetDirective</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CFAOffset {#a94e023a5cbce33e212bc7821ed433a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{MCDwarf.cpp}::FrameEmitterImpl::CFAOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1329 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>

</div>
</div>

### InitialCFAOffset {#a9fb04b46559bb785aff5b7fb05231a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{MCDwarf.cpp}::FrameEmitterImpl::InitialCFAOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>

</div>
</div>

### IsEH {#a332c588124ab34d7fa272310a9ffebdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCDwarf.cpp}::FrameEmitterImpl::IsEH</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1331 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>

</div>
</div>

### Streamer {#a01915bad0e230284f532acc45afe1ae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCObjectStreamer&amp; anonymous{MCDwarf.cpp}::FrameEmitterImpl::Streamer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1332 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
