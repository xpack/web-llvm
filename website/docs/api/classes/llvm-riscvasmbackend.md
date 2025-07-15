---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/riscvasmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RISCVAsmBackend` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RISCVAsmBackend { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">Target/RISCV/MCTargetDesc/RISCVAsmBackend.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic interface to target specific assembler backends. <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f98d19f3eacb689ad7ccf9cb4518a9a">RISCVAsmBackend</a> (const MCSubtargetInfo &amp;STI, uint8_t OSABI, bool Is64Bit, const MCTargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf78bd76d7b93bbb8a462e1bb7c0741">~RISCVAsmBackend</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357ab41636878b2e45fd6e637c74e189">setForceRelocs</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df2a46541fffb2b35320ae71b7fe26c">shouldInsertExtraNopBytesForCodeAlign</a> (const MCAlignFragment &amp;AF, unsigned &amp;Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook to check if extra nop bytes must be inserted for alignment directive. <a href="#a6df2a46541fffb2b35320ae71b7fe26c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f78db3a67945349cd7bcee045f65b1b">shouldInsertFixupForCodeAlign</a> (MCAssembler &amp;Asm, MCAlignFragment &amp;AF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook which indicates if the target requires a fixup to be generated when handling an align directive in an executable section. <a href="#a9f78db3a67945349cd7bcee045f65b1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5461102b304d92530e9a6e3afcd47b30">evaluateTargetFixup</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCFragment *DF, const MCValue &amp;Target, const MCSubtargetInfo *STI, uint64_t &amp;Value, bool &amp;WasForced) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4b22b2ab12c7d26784790f13aeb273">handleAddSubRelocations</a> (const MCAssembler &amp;Asm, const MCFragment &amp;F, const MCFixup &amp;Fixup, const MCValue &amp;Target, uint64_t &amp;FixedValue) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e40738fcf4d771be936969f54b2d1a">applyFixup</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, MutableArrayRef&lt; char &gt; Data, uint64_t Value, bool IsResolved, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate. <a href="#a29e40738fcf4d771be936969f54b2d1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter">MCObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114d0788f4ba31c3ce5b5e02c476f07e">createObjectTargetWriter</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a95c754e0453aefe81ebad98e4ff895">shouldForceRelocation</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, const uint64_t Value, const MCSubtargetInfo *STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook to check if a relocation is needed for some target specific reason. <a href="#a6a95c754e0453aefe81ebad98e4ff895">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67f770e0c7076b7fc767f1aee60edcd3">fixupNeedsRelaxationAdvanced</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, bool Resolved, uint64_t Value, const MCRelaxableFragment *DF, const bool WasForced) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific predicate for whether a given fixup requires the associated instruction to be relaxed. <a href="#a67f770e0c7076b7fc767f1aee60edcd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb6ee79095712ce921a73cdb0fccf79d">getNumFixupKinds</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of target specific fixup kinds. <a href="#adb6ee79095712ce921a73cdb0fccf79d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93cdb06931a3c3ccef44a634cb837c2">getFixupKind</a> (StringRef Name) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a relocation name used in .reloc to a fixup kind. <a href="#af93cdb06931a3c3ccef44a634cb837c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b88cc963afa1ea60002eaab16939eb">getFixupKindInfo</a> (MCFixupKind Kind) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get information on a fixup kind. <a href="#a54b88cc963afa1ea60002eaab16939eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c222afc583edb916fd251f05f41d0c8">mayNeedRelaxation</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction may need relaxation. <a href="#a7c222afc583edb916fd251f05f41d0c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ece2411bd9ad97c1fd869d77c1b461b">getRelaxedOpcode</a> (unsigned Op) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a358ac79e04af2c8c34fa5084fa46cfee">relaxInstruction</a> (MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Relax the instruction in the given fragment to the next wider instruction. <a href="#a358ac79e04af2c8c34fa5084fa46cfee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056a7266fa88806c3f88ab217fac6e4e">relaxDwarfLineAddr</a> (const MCAssembler &amp;Asm, MCDwarfLineAddrFragment &amp;DF, bool &amp;WasRelaxed) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a172850f33ba1afc4850ad347040d02a7">relaxDwarfCFA</a> (const MCAssembler &amp;Asm, MCDwarfCallFrameFragment &amp;DF, bool &amp;WasRelaxed) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b10511c4a52fc282850610c648ba455">relaxLEB128</a> (const MCAssembler &amp;Asm, MCLEBFragment &amp;LF, int64_t &amp;Value) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e4421566f19358913fa09d91a089989">writeNopData</a> (raw_ostream &amp;OS, uint64_t Count, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write an (optimal) nop sequence of Count bytes to the given output. <a href="#a7e4421566f19358913fa09d91a089989">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5097291f2c0513b2f9733a85116b3e15">getTargetOptions</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f9c6db272eb3985f9d17714696c508f">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a717fd7ea9423b4d0b496534ff09a0e63">OSABI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7cec70f9d86e508ff1bafa13f83d604">Is64Bit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acff0e660657f81c58cab980bd727eb59">ForceRelocs</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0fcb8e67f1332a628c135729380cbbd">TargetOptions</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVAsmBackend() {#a4f98d19f3eacb689ad7ccf9cb4518a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RISCVAsmBackend::RISCVAsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, uint8_t OSABI, bool Is64Bit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a3dd30d6980185ef34e42333191453867">llvm::MCAsmBackend::MCAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvfeatures/#a33bd43741ac5adb4b9a36f946b927cda">llvm::RISCVFeatures::validate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RISCVAsmBackend() {#adbf78bd76d7b93bbb8a462e1bb7c0741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RISCVAsmBackend::~RISCVAsmBackend ()</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyFixup() {#a29e40738fcf4d771be936969f54b2d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVAsmBackend::applyFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Data, uint64_t Value, bool IsResolved, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Apply the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate.</p>


<p>Errors (such as an out of range fixup value) should be reported via <span class="doxyComputerOutput">Ctx</span>. The <span class="doxyComputerOutput">STI</span> is present only for fragments of type <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdatafragment">MCDataFragment</a> with hasInstructions() == true.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ae03bfc95ecd6ac86582ade86cd2711f1">adjustFixupValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#a54b88cc963afa1ea60002eaab16939eb">getFixupKindInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### createObjectTargetWriter() {#a114d0788f4ba31c3ce5b5e02c476f07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MCObjectTargetWriter &gt; RISCVAsmBackend::createObjectTargetWriter ()</td>
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



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a01e1a55856fda89f1e35320e199981f0">llvm::createRISCVELFObjectWriter</a>.</p>

</div>
</div>

### evaluateTargetFixup() {#a5461102b304d92530e9a6e3afcd47b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::evaluateTargetFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * DF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, uint64_t &amp; Value, bool &amp; WasForced)</td>
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



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad37e08bb2772b97fd5c82cc64b92b8c9">llvm::RISCV::fixup_riscv_pcrel_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a25f04a3aac7dcd8105cd6199add50589">llvm::RISCV::fixup_riscv_pcrel_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a352fb7bc558f75c5d77993daf797ea1c">llvm::RISCV::fixup_riscv_pcrel_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ac480fe24e2a9fc38e09382467a80c8e5">llvm::RISCV::fixup_riscv_tlsdesc_hi20</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#ae357568bfa7baaa244f16208924f4637">llvm::MCSymbolELF::getBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#a6d15eb9e5fcc1aefad18f4f9f7dcbc66">llvm::MCFixup::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a2c716684711cb83467c2138bc4e84454">llvm::MCSymbolELF::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#a1766447693abfb2e612a4d394f8b4cd0">llvm::MCFixup::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa462dae167e31cac32e97bb0c77ab071">llvm::MCSymbol::isUndefined</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a6a95c754e0453aefe81ebad98e4ff895">shouldForceRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a7269ceaea4bf3dbd15caa427598cbcb9">llvm::ELF::STT_GNU_IFUNC</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### fixupNeedsRelaxationAdvanced() {#a67f770e0c7076b7fc767f1aee60edcd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::fixupNeedsRelaxationAdvanced (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool Resolved, uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> * DF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool WasForced)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific predicate for whether a given fixup requires the associated instruction to be relaxed.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad266f94de8002bb828840b8f22972ea8">llvm::RISCV::fixup_riscv_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad0ebbd5ab44960cdc83796e80006aaaa">llvm::RISCV::fixup_riscv_rvc_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a9f4ce31fb99c4613c6f173ce268f9725">llvm::RISCV::fixup_riscv_rvc_jump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp/#a85cbc0c468227bf768eebe0a12b1525c">RelaxBranches</a>.</p>

</div>
</div>

### getFixupKind() {#af93cdb06931a3c3ccef44a634cb837c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MCFixupKind &gt; RISCVAsmBackend::getFixupKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Map a relocation name used in .reloc to a fixup kind.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>.</p>

</div>
</div>

### getFixupKindInfo() {#a54b88cc963afa1ea60002eaab16939eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCFixupKindInfo &amp; RISCVAsmBackend::getFixupKindInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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

<p>Get information on a fixup kind.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da21d215ec80c4375e0df4cf9843b2706c">llvm::MCFixupKindInfo::FKF_IsTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="#adb6ee79095712ce921a73cdb0fccf79d">getNumFixupKinds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a8a051219a274fe1213d1b7c3512d3a31">llvm::RISCV::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#a29e40738fcf4d771be936969f54b2d1a">applyFixup</a>.</p>

</div>
</div>

### getNumFixupKinds() {#adb6ee79095712ce921a73cdb0fccf79d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RISCVAsmBackend::getNumFixupKinds ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of target specific fixup kinds.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a8a051219a274fe1213d1b7c3512d3a31">llvm::RISCV::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#a54b88cc963afa1ea60002eaab16939eb">getFixupKindInfo</a>.</p>

</div>
</div>

### getRelaxedOpcode() {#a9ece2411bd9ad97c1fd869d77c1b461b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVAsmBackend::getRelaxedOpcode (unsigned Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>Referenced by <a href="#a7c222afc583edb916fd251f05f41d0c8">mayNeedRelaxation</a> and <a href="#a358ac79e04af2c8c34fa5084fa46cfee">relaxInstruction</a>.</p>

</div>
</div>

### getTargetOptions() {#a5097291f2c0513b2f9733a85116b3e15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCTargetOptions &amp; llvm::RISCVAsmBackend::getTargetOptions ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>

</div>
</div>

### handleAddSubRelocations() {#a9f4b22b2ab12c7d26784790f13aeb273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::handleAddSubRelocations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, uint64_t &amp; FixedValue)</td>
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



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ad273f7fe2962a053becd88767fee3b0d">llvm::FK_Data_leb128</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### mayNeedRelaxation() {#a7c222afc583edb916fd251f05f41d0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::mayNeedRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction may need relaxation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inst</td>
<td class="doxyParamItemDescription"><p>- The instruction to test.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">STI</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> in effect when the instruction was encoded.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a> and <a href="#a9ece2411bd9ad97c1fd869d77c1b461b">getRelaxedOpcode</a>.</p>

</div>
</div>

### relaxDwarfCFA() {#a172850f33ba1afc4850ad347040d02a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::relaxDwarfCFA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfcallframefragment">MCDwarfCallFrameFragment</a> &amp; DF, bool &amp; WasRelaxed)</td>
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



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a9756a579fc66a3fbcc6d3e82866a289f">llvm::MCExpr::evaluateKnownAbsolute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

### relaxDwarfLineAddr() {#a056a7266fa88806c3f88ab217fac6e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::relaxDwarfLineAddr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddrfragment">MCDwarfLineAddrFragment</a> &amp; DF, bool &amp; WasRelaxed)</td>
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



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a9756a579fc66a3fbcc6d3e82866a289f">llvm::MCExpr::evaluateKnownAbsolute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a071993fe404ae3387526e7a104b0f38c">llvm::MCBinaryExpr::getLHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a267d99907b13ad949383af25d7fe3dce">llvm::RISCV::getRelocPairForSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a201920f46caa494d398931ef46788de2">llvm::MCBinaryExpr::getRHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a06288f4d38e1d74fc7a1d10056d88373">llvm::raw_ostream::write_zeros</a>.</p>

</div>
</div>

### relaxInstruction() {#a358ac79e04af2c8c34fa5084fa46cfee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVAsmBackend::relaxInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Relax the instruction in the given fragment to the next wider instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Inst</td>
<td class="doxyParamItemDescription"><p>The instruction to relax, which is also the relaxed instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">STI</td>
<td class="doxyParamItemDescription"><p>the subtarget information for the associated instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="#a9ece2411bd9ad97c1fd869d77c1b461b">getRelaxedOpcode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvrvc/#a74d57723c5d24eea18d6ad20f8bca1da">llvm::RISCVRVC::uncompress</a>.</p>

</div>
</div>

### relaxLEB128() {#a0b10511c4a52fc282850610c648ba455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, bool &gt; RISCVAsmBackend::relaxLEB128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/mclebfragment">MCLEBFragment</a> &amp; LF, int64_t &amp; Value)</td>
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



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a9756a579fc66a3fbcc6d3e82866a289f">llvm::MCExpr::evaluateKnownAbsolute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ad273f7fe2962a053becd88767fee3b0d">llvm::FK_Data_leb128</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragmentwithfixups/#a8a0daac469ed602d68174c8efae89b22">llvm::MCEncodedFragmentWithFixups&lt; ContentsSize, FixupsSize &gt;::getFixups</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#afc4237f50d652cdefff412b2c780c369">llvm::MCExpr::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mclebfragment/#a49b19ceb2d2197e696806b38855c2641">llvm::MCLEBFragment::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mclebfragment/#a24e57b36b177dab1e77af0931f661d76">llvm::MCLEBFragment::isSigned</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp/#af76701b8fc911801230dde550cce7c33">ULEB128Reloc</a>.</p>

</div>
</div>

### setForceRelocs() {#a357ab41636878b2e45fd6e637c74e189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RISCVAsmBackend::setForceRelocs ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>

</div>
</div>

### shouldForceRelocation() {#a6a95c754e0453aefe81ebad98e4ff895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::shouldForceRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Hook to check if a relocation is needed for some target specific reason.</p>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a4ff796b91dfd8a1d885eed8bf90d7cf7">llvm::RISCV::fixup_riscv_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a1dcfb88aadd66136c03e2620a6ff91dd">llvm::RISCV::fixup_riscv_tls_gd_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a13b9024d713be1b06a31431a40316038">llvm::RISCV::fixup_riscv_tls_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ac480fe24e2a9fc38e09382467a80c8e5">llvm::RISCV::fixup_riscv_tlsdesc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ad273f7fe2962a053becd88767fee3b0d">llvm::FK_Data_leb128</a>.</p>


<p>Referenced by <a href="#a5461102b304d92530e9a6e3afcd47b30">evaluateTargetFixup</a>.</p>

</div>
</div>

### shouldInsertExtraNopBytesForCodeAlign() {#a6df2a46541fffb2b35320ae71b7fe26c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::shouldInsertExtraNopBytesForCodeAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment">MCAlignFragment</a> &amp; AF, unsigned &amp; Size)</td>
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

<p>Hook to check if extra nop bytes must be inserted for alignment directive.</p>


<p>For some targets this may be necessary in order to support linker relaxation. The number of bytes to insert are returned in Size.</p>


<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment/#a5169ecb5ee59e190bdbf4d08f2e4fc8f">llvm::MCAlignFragment::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment/#ab891d26919538bc5b770905a54e2d495">llvm::MCAlignFragment::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a9f78db3a67945349cd7bcee045f65b1b">shouldInsertFixupForCodeAlign</a>.</p>

</div>
</div>

### shouldInsertFixupForCodeAlign() {#a9f78db3a67945349cd7bcee045f65b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::shouldInsertFixupForCodeAlign (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment">MCAlignFragment</a> &amp; AF)</td>
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

<p>Hook which indicates if the target requires a fixup to be generated when handling an align directive in an executable section.</p>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a63305955ac569a08596601f41364158c">llvm::RISCV::fixup_riscv_align</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9749211eb432ffc5b2bbef35eed9e429">llvm::MCValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mcalignfragment/#ab891d26919538bc5b770905a54e2d495">llvm::MCAlignFragment::getSubtargetInfo</a> and <a href="#a6df2a46541fffb2b35320ae71b7fe26c">shouldInsertExtraNopBytesForCodeAlign</a>.</p>

</div>
</div>

### writeNopData() {#a7e4421566f19358913fa09d91a089989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVAsmBackend::writeNopData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Write an (optimal) nop sequence of Count bytes to the given output.</p>


<p>If the target cannot generate such a sequence, it should return an error.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True on success.</p></dd>
</dl>


<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ForceRelocs {#acff0e660657f81c58cab980bd727eb59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVAsmBackend::ForceRelocs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>

</div>
</div>

### Is64Bit {#af7cec70f9d86e508ff1bafa13f83d604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RISCVAsmBackend::Is64Bit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>

</div>
</div>

### OSABI {#a717fd7ea9423b4d0b496534ff09a0e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::RISCVAsmBackend::OSABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>

</div>
</div>

### STI {#a7f9c6db272eb3985f9d17714696c508f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo&amp; llvm::RISCVAsmBackend::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>

</div>
</div>

### TargetOptions {#ac0fcb8e67f1332a628c135729380cbbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCTargetOptions&amp; llvm::RISCVAsmBackend::TargetOptions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-cpp">RISCVAsmBackend.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvasmbackend-h">RISCVAsmBackend.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
