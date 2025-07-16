---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cskyasmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CSKYAsmBackend` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::CSKYAsmBackend { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">Target/CSKY/MCTargetDesc/CSKYAsmBackend.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505a926c67574c37de8ec2752859f204">CSKYAsmBackend</a> (const MCSubtargetInfo &amp;STI, const MCTargetOptions &amp;OP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2a47a4ecaea065cf01c2533c6d5cd35">getNumFixupKinds</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of target specific fixup kinds. <a href="#ae2a47a4ecaea065cf01c2533c6d5cd35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9770a1a9fb4e41322c32fe546c3145d6">applyFixup</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, MutableArrayRef&lt; char &gt; Data, uint64_t Value, bool IsResolved, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate. <a href="#a9770a1a9fb4e41322c32fe546c3145d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2151211fadfde00e75af25b5f98270c1">getFixupKindInfo</a> (MCFixupKind Kind) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get information on a fixup kind. <a href="#a2151211fadfde00e75af25b5f98270c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad13795ffc171e5e2cfd4ad867dbab3">fixupNeedsRelaxation</a> (const MCFixup &amp;Fixup, uint64_t Value) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple predicate for targets where !Resolved implies requiring relaxation. <a href="#a4ad13795ffc171e5e2cfd4ad867dbab3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade0613efda90a350f47392d0b721b1f8">relaxInstruction</a> (MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Relax the instruction in the given fragment to the next wider instruction. <a href="#ade0613efda90a350f47392d0b721b1f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4315216f104f0f7963b4ba8e6f85d01d">mayNeedRelaxation</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction may need relaxation. <a href="#a4315216f104f0f7963b4ba8e6f85d01d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae536aee2760cede7e1b8532bf821759e">fixupNeedsRelaxationAdvanced</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, bool Resolved, uint64_t Value, const MCRelaxableFragment *DF, const bool WasForced) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific predicate for whether a given fixup requires the associated instruction to be relaxed. <a href="#ae536aee2760cede7e1b8532bf821759e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c0b495532ba9e071763edc19516f31">writeNopData</a> (raw_ostream &amp;OS, uint64_t Count, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write an (optimal) nop sequence of Count bytes to the given output. <a href="#af8c0b495532ba9e071763edc19516f31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8d2ec2c857eeaca14a0ef9376e7403">shouldForceRelocation</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, const uint64_t Value, const MCSubtargetInfo *STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook to check if a relocation is needed for some target specific reason. <a href="#a9b8d2ec2c857eeaca14a0ef9376e7403">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter">MCObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef809c1ec44be2c4a7567c3e31e4a028">createObjectTargetWriter</a> () const override</td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CSKYAsmBackend() {#a505a926c67574c37de8ec2752859f204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CSKYAsmBackend::CSKYAsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; OP)</td>
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



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a3dd30d6980185ef34e42333191453867">llvm::MCAsmBackend::MCAsmBackend</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyFixup() {#a9770a1a9fb4e41322c32fe546c3145d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYAsmBackend::applyFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Data, uint64_t Value, bool IsResolved, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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


<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ae03bfc95ecd6ac86582ade86cd2711f1">adjustFixupValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#a2151211fadfde00e75af25b5f98270c1">getFixupKindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### createObjectTargetWriter() {#aef809c1ec44be2c4a7567c3e31e4a028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MCObjectTargetWriter &gt; CSKYAsmBackend::createObjectTargetWriter ()</td>
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



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a37fabad629f21b28c2c1822508713eaa">llvm::createCSKYELFObjectWriter</a>.</p>

</div>
</div>

### fixupNeedsRelaxation() {#a4ad13795ffc171e5e2cfd4ad867dbab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYAsmBackend::fixupNeedsRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, uint64_t Value)</td>
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

<p>Simple predicate for targets where !Resolved implies requiring relaxation.</p>

<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>.</p>

</div>
</div>

### fixupNeedsRelaxationAdvanced() {#ae536aee2760cede7e1b8532bf821759e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYAsmBackend::fixupNeedsRelaxationAdvanced (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool Resolved, uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> * DF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool WasForced)</td>
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

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a36c5d2cff2efb3e83227a9dca61accc1">llvm::CSKY::fixup_csky_pcrel_imm10_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a536ed49406b71ec231209116d1459a92">llvm::CSKY::fixup_csky_pcrel_imm16_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa11a4036cb9536c4ed8991e3fb2d126c">llvm::CSKY::fixup_csky_pcrel_imm26_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a4c2d802607ee153939c71f832414931c">llvm::CSKY::fixup_csky_pcrel_uimm7_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getFixupKindInfo() {#a2151211fadfde00e75af25b5f98270c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCFixupKindInfo &amp; CSKYAsmBackend::getFixupKindInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a6d70355097ca3e247e1aedf88d6288d1">llvm::CSKY::fixup_csky_addr32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2ad1bf76d360185c7b047a69ac3ca47a31">llvm::CSKY::fixup_csky_addr_hi16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2af2da376d6904e5f37e2f389dc295810d">llvm::CSKY::fixup_csky_addr_lo16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2afdb8ccea389463c5c685e028b9f94726">llvm::CSKY::fixup_csky_doffset_imm18</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a5302f6fa84a724caf5ad8cdf6569d8c7">llvm::CSKY::fixup_csky_doffset_imm18_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a854b6d429bc64a8468194537a6f06e5f">llvm::CSKY::fixup_csky_doffset_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a5caa470fa9668e45540e67044ff14315">llvm::CSKY::fixup_csky_got32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2ac16105e6ed5d02c6d9664e008c649525">llvm::CSKY::fixup_csky_got_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a7189eb87f08082cd8e53fef4f48b83f1">llvm::CSKY::fixup_csky_gotoff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a40093f3fe6bca907433c06cb5256cd15">llvm::CSKY::fixup_csky_gotpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a36c5d2cff2efb3e83227a9dca61accc1">llvm::CSKY::fixup_csky_pcrel_imm10_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a536ed49406b71ec231209116d1459a92">llvm::CSKY::fixup_csky_pcrel_imm16_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a8548ad738cfd027c7759b8c2e0396c49">llvm::CSKY::fixup_csky_pcrel_imm18_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa11a4036cb9536c4ed8991e3fb2d126c">llvm::CSKY::fixup_csky_pcrel_imm26_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a8ebf6cafce7b2282b6db2e6b568518f5">llvm::CSKY::fixup_csky_pcrel_uimm16_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a4c2d802607ee153939c71f832414931c">llvm::CSKY::fixup_csky_pcrel_uimm7_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2ac3502715f5dd21573ae7085cdb2a7c3e">llvm::CSKY::fixup_csky_pcrel_uimm8_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa6060b29f15a989d994dd28029d887b7">llvm::CSKY::fixup_csky_plt32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa0247adcbb9af641dc8871d528adc437">llvm::CSKY::fixup_csky_plt_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da4736f387c937299570b8ac87f9d9dd08">llvm::MCFixupKindInfo::FKF_IsAlignedDownTo32Bits</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="#ae2a47a4ecaea065cf01c2533c6d5cd35">getNumFixupKinds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a3fc5992d99d9696f12829ca9d7531a87">llvm::CSKY::NumTargetFixupKinds</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>.</p>


<p>Referenced by <a href="#a9770a1a9fb4e41322c32fe546c3145d6">applyFixup</a>.</p>

</div>
</div>

### getNumFixupKinds() {#ae2a47a4ecaea065cf01c2533c6d5cd35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::CSKYAsmBackend::getNumFixupKinds ()</td>
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

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a3fc5992d99d9696f12829ca9d7531a87">llvm::CSKY::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#a2151211fadfde00e75af25b5f98270c1">getFixupKindInfo</a>.</p>

</div>
</div>

### mayNeedRelaxation() {#a4315216f104f0f7963b4ba8e6f85d01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYAsmBackend::mayNeedRelaxation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>.</p>

</div>
</div>

### relaxInstruction() {#ade0613efda90a350f47392d0b721b1f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYAsmBackend::relaxInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ab8aa6b74c6bb82576347afb756807f20">llvm::MCInst::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>

</div>
</div>

### shouldForceRelocation() {#a9b8d2ec2c857eeaca14a0ef9376e7403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYAsmBackend::shouldForceRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2afdb8ccea389463c5c685e028b9f94726">llvm::CSKY::fixup_csky_doffset_imm18</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a5302f6fa84a724caf5ad8cdf6569d8c7">llvm::CSKY::fixup_csky_doffset_imm18_scale2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a854b6d429bc64a8468194537a6f06e5f">llvm::CSKY::fixup_csky_doffset_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a5caa470fa9668e45540e67044ff14315">llvm::CSKY::fixup_csky_got32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2ac16105e6ed5d02c6d9664e008c649525">llvm::CSKY::fixup_csky_got_imm18_scale4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a7189eb87f08082cd8e53fef4f48b83f1">llvm::CSKY::fixup_csky_gotoff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2a40093f3fe6bca907433c06cb5256cd15">llvm::CSKY::fixup_csky_gotpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa6060b29f15a989d994dd28029d887b7">llvm::CSKY::fixup_csky_plt32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae6b0dde9ada1e7ffffed2d85168a70a2aa0247adcbb9af641dc8871d528adc437">llvm::CSKY::fixup_csky_plt_imm18_scale4</a>.</p>

</div>
</div>

### writeNopData() {#af8c0b495532ba9e071763edc19516f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSKYAsmBackend::writeNopData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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


<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a>, definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a06288f4d38e1d74fc7a1d10056d88373">llvm::raw_ostream::write_zeros</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-cpp">CSKYAsmBackend.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskyasmbackend-h">CSKYAsmBackend.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
