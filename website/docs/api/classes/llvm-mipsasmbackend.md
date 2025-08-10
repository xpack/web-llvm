---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipsasmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MipsAsmBackend` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MipsAsmBackend { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">Target/Mips/MCTargetDesc/MipsAsmBackend.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipsasmbackend-cpp-/windowsmipsasmbackend">WindowsMipsAsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59409ae1b28d0e3412726c09a781762">MipsAsmBackend</a> (const Target &amp;T, const MCRegisterInfo &amp;MRI, const Triple &amp;TT, StringRef CPU, bool N32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter">MCObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87e8bd2ed5a73bacfcead9d8f9e9938">createObjectTargetWriter</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa68834049f70b768351aa29223d33a44">applyFixup</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, MutableArrayRef&lt; char &gt; Data, uint64_t Value, bool IsResolved, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ApplyFixup - Apply the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate. <a href="#aa68834049f70b768351aa29223d33a44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0c25f61de4486fee1e2cc6c09a4e1a">getFixupKind</a> (StringRef Name) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a relocation name used in .reloc to a fixup kind. <a href="#aae0c25f61de4486fee1e2cc6c09a4e1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2382d2ff9fb9c8a86a9157c82c9562f">getFixupKindInfo</a> (MCFixupKind Kind) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get information on a fixup kind. <a href="#ac2382d2ff9fb9c8a86a9157c82c9562f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bc32a7b51baf6b409dfb6aa37af65a0">getNumFixupKinds</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of target specific fixup kinds. <a href="#a5bc32a7b51baf6b409dfb6aa37af65a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88b2f08af754834c45de4e5017a11a19">writeNopData</a> (raw_ostream &amp;OS, uint64_t Count, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WriteNopData - Write an (optimal) nop sequence of Count bytes to the given output. <a href="#a88b2f08af754834c45de4e5017a11a19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e28438af4a885993c78ad8b77a4f40">shouldForceRelocation</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, const uint64_t Value, const MCSubtargetInfo *STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook to check if a relocation is needed for some target specific reason. <a href="#a60e28438af4a885993c78ad8b77a4f40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae949976eadf2a8e0861c129b0ca395fd">isMicroMips</a> (const MCSymbol *Sym) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a given symbol has been flagged with MICROMIPS flag. <a href="#ae949976eadf2a8e0861c129b0ca395fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbbe3c280ff9ef671b7d85a8b417a141">TheTriple</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a344d0986506990a23f260c47dc0ea88a">IsN32</a></td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsAsmBackend() {#af59409ae1b28d0e3412726c09a781762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MipsAsmBackend::MipsAsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, bool N32)</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a3dd30d6980185ef34e42333191453867">llvm::MCAsmBackend::MCAsmBackend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mipsasmbackend-cpp-/windowsmipsasmbackend/#ac877b7c8c76cb0abe7b96c05632ba135">anonymous{MipsAsmBackend.cpp}::WindowsMipsAsmBackend::WindowsMipsAsmBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyFixup() {#aa68834049f70b768351aa29223d33a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAsmBackend::applyFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Data, uint64_t Value, bool IsResolved, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>ApplyFixup - Apply the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate.</p>

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ae03bfc95ecd6ac86582ade86cd2711f1">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp/#a53c193f242d181baee037b917d83e3e2">calculateMMLEIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8297df7f9768b5bb575ab89d20b30ff3">llvm::Mips::fixup_MICROMIPS_PC10_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a493c08ff4c7daaa4e981326660778a1e">llvm::Mips::fixup_Mips_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5abf0d35311026f6e95d49eab0a5aa189d">llvm::Mips::fixup_Mips_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="#ac2382d2ff9fb9c8a86a9157c82c9562f">getFixupKindInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp/#aab6f63e5ba54f992d97d598a1298d38d">needsMMLEByteOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#acfcb94e2996dda3707eaa1eb1cb79f80">llvm::MCFixupKindInfo::TargetSize</a>.</p>

</div>
</div>

### createObjectTargetWriter() {#ae87e8bd2ed5a73bacfcead9d8f9e9938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MCObjectTargetWriter &gt; MipsAsmBackend::createObjectTargetWriter ()</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1915b2daceaa58dcae373f37116bcb48">llvm::createMipsELFObjectWriter</a>.</p>

</div>
</div>

### getFixupKind() {#aae0c25f61de4486fee1e2cc6c09a4e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MCFixupKind &gt; MipsAsmBackend::getFixupKind (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a515f8848142f500447c79f9529d20ce2">llvm::Mips::fixup_MICROMIPS_CALL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a51060e5d732b3b086038dc48f6ec3064">llvm::Mips::fixup_MICROMIPS_GOT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a91fa94291c3d1c568f5e2a3bc10ce94f">llvm::Mips::fixup_MICROMIPS_GOT_DISP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a5d681ebbbf7ccd4ecdf20992c6dcfce9">llvm::Mips::fixup_MICROMIPS_GOT_OFST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a12dd04a6f3222eb075bb7bbb7a877686">llvm::Mips::fixup_MICROMIPS_GOT_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5addc624c0c979e72440d037f862ddc8e3">llvm::Mips::fixup_MICROMIPS_GOTTPREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a649fdfac2fb6a04791d3a857fb7128c8">llvm::Mips::fixup_MICROMIPS_JALR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a6dcd134b90027fe09258de1b1acbe96f">llvm::Mips::fixup_MICROMIPS_TLS_DTPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ae8210f9b20325f1f373ba65d6c450834">llvm::Mips::fixup_MICROMIPS_TLS_DTPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8490753dcd2baed10ed9499d0af3c910">llvm::Mips::fixup_MICROMIPS_TLS_GD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a53b0c2d53b83db98a608596e490aaceb">llvm::Mips::fixup_MICROMIPS_TLS_LDM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a331d4409d1e73993aec8660ec95c9927">llvm::Mips::fixup_MICROMIPS_TLS_TPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a005bba69839f43aea295fd4b9b04b468">llvm::Mips::fixup_MICROMIPS_TLS_TPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a60c41d65c5b85e60845d0b5d9a5e2cad">llvm::Mips::fixup_Mips_CALL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5aa1da7ac91e24d477f5f1456ea78867ef">llvm::Mips::fixup_Mips_CALL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ab88a975afcf636548981251ccbe94308">llvm::Mips::fixup_Mips_CALL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0d08270c90f999bfc66bbac0d6bde120">llvm::Mips::fixup_Mips_DTPREL_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a9db2f1c56b099bee5e6e9b38ce74d44d">llvm::Mips::fixup_Mips_DTPREL_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5adb3fcfd2186ba8a2d087e1dd6aa81835">llvm::Mips::fixup_Mips_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a78e19d4edaf2ec86f2b8c0bad7e880db">llvm::Mips::fixup_Mips_GOT_DISP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a50816e1bb1c03b9f9e78fc51cda22812">llvm::Mips::fixup_Mips_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ae862242d904102cd8ae48b5e4617e5a0">llvm::Mips::fixup_Mips_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5aa9c59af1b95c717f8dbb3d368c137033">llvm::Mips::fixup_Mips_GOT_OFST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a6c25bcd83d096682c436213d1c449908">llvm::Mips::fixup_Mips_GOT_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a06928a5f5009c5df8048e4fbdac5f741">llvm::Mips::fixup_Mips_GOTTPREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5af4abf81a504e1e70891390ee5739bedb">llvm::Mips::fixup_Mips_JALR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0c08af5309247c17e74b8a371bacc619">llvm::Mips::fixup_Mips_TLSGD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a336dcdb17a6f36a1a33945ef20d8cf2f">llvm::Mips::fixup_Mips_TLSLDM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a7ab045ce0b118beba9895b611eb42ff2">llvm::Mips::fixup_Mips_TPREL_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a523f4b256997b5dcc3e870e4d89e5eef">llvm::Mips::fixup_Mips_TPREL_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad60ec34cc0289efdb2530fc622949f83">llvm::MCAsmBackend::getFixupKind</a>.</p>

</div>
</div>

### getFixupKindInfo() {#ac2382d2ff9fb9c8a86a9157c82c9562f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCFixupKindInfo &amp; MipsAsmBackend::getFixupKindInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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

<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="#a5bc32a7b51baf6b409dfb6aa37af65a0">getNumFixupKinds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5af8af0a48db5c06aebad80777d737d56f">llvm::Mips::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#aa68834049f70b768351aa29223d33a44">applyFixup</a>.</p>

</div>
</div>

### getNumFixupKinds() {#a5bc32a7b51baf6b409dfb6aa37af65a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MipsAsmBackend::getNumFixupKinds ()</td>
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

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5af8af0a48db5c06aebad80777d737d56f">llvm::Mips::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#ac2382d2ff9fb9c8a86a9157c82c9562f">getFixupKindInfo</a>.</p>

</div>
</div>

### isMicroMips() {#ae949976eadf2a8e0861c129b0ca395fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmBackend::isMicroMips (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether a given symbol has been flagged with MICROMIPS flag.</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a29b00051aee706fc5bbc604742a66f55a920f3ac6d4e61d6e58a5377436c31587">llvm::ELF::STO_MIPS_MICROMIPS</a>.</p>

</div>
</div>

### shouldForceRelocation() {#a60e28438af4a885993c78ad8b77a4f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmBackend::shouldForceRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a515f8848142f500447c79f9529d20ce2">llvm::Mips::fixup_MICROMIPS_CALL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a51060e5d732b3b086038dc48f6ec3064">llvm::Mips::fixup_MICROMIPS_GOT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a91fa94291c3d1c568f5e2a3bc10ce94f">llvm::Mips::fixup_MICROMIPS_GOT_DISP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a5d681ebbbf7ccd4ecdf20992c6dcfce9">llvm::Mips::fixup_MICROMIPS_GOT_OFST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a12dd04a6f3222eb075bb7bbb7a877686">llvm::Mips::fixup_MICROMIPS_GOT_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5addc624c0c979e72440d037f862ddc8e3">llvm::Mips::fixup_MICROMIPS_GOTTPREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a649fdfac2fb6a04791d3a857fb7128c8">llvm::Mips::fixup_MICROMIPS_JALR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a6dcd134b90027fe09258de1b1acbe96f">llvm::Mips::fixup_MICROMIPS_TLS_DTPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ae8210f9b20325f1f373ba65d6c450834">llvm::Mips::fixup_MICROMIPS_TLS_DTPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8490753dcd2baed10ed9499d0af3c910">llvm::Mips::fixup_MICROMIPS_TLS_GD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a53b0c2d53b83db98a608596e490aaceb">llvm::Mips::fixup_MICROMIPS_TLS_LDM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a331d4409d1e73993aec8660ec95c9927">llvm::Mips::fixup_MICROMIPS_TLS_TPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a005bba69839f43aea295fd4b9b04b468">llvm::Mips::fixup_MICROMIPS_TLS_TPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a60c41d65c5b85e60845d0b5d9a5e2cad">llvm::Mips::fixup_Mips_CALL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5aa1da7ac91e24d477f5f1456ea78867ef">llvm::Mips::fixup_Mips_CALL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ab88a975afcf636548981251ccbe94308">llvm::Mips::fixup_Mips_CALL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0d08270c90f999bfc66bbac0d6bde120">llvm::Mips::fixup_Mips_DTPREL_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a9db2f1c56b099bee5e6e9b38ce74d44d">llvm::Mips::fixup_Mips_DTPREL_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5adb3fcfd2186ba8a2d087e1dd6aa81835">llvm::Mips::fixup_Mips_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a78e19d4edaf2ec86f2b8c0bad7e880db">llvm::Mips::fixup_Mips_GOT_DISP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a50816e1bb1c03b9f9e78fc51cda22812">llvm::Mips::fixup_Mips_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ae862242d904102cd8ae48b5e4617e5a0">llvm::Mips::fixup_Mips_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5aa9c59af1b95c717f8dbb3d368c137033">llvm::Mips::fixup_Mips_GOT_OFST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a6c25bcd83d096682c436213d1c449908">llvm::Mips::fixup_Mips_GOT_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a06928a5f5009c5df8048e4fbdac5f741">llvm::Mips::fixup_Mips_GOTTPREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5af4abf81a504e1e70891390ee5739bedb">llvm::Mips::fixup_Mips_JALR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0c08af5309247c17e74b8a371bacc619">llvm::Mips::fixup_Mips_TLSGD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a336dcdb17a6f36a1a33945ef20d8cf2f">llvm::Mips::fixup_Mips_TLSLDM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a7ab045ce0b118beba9895b611eb42ff2">llvm::Mips::fixup_Mips_TPREL_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a523f4b256997b5dcc3e870e4d89e5eef">llvm::Mips::fixup_Mips_TPREL_LO</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3d3a355228d2f64fa312abbd7abfbf">llvm::FixupKind</a>.</p>

</div>
</div>

### writeNopData() {#a88b2f08af754834c45de4e5017a11a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmBackend::writeNopData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>WriteNopData - Write an (optimal) nop sequence of Count bytes to the given output.</p>


<p>If the target cannot generate such a sequence, it should return an error.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True on success.</p></dd>
</dl>


<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a06288f4d38e1d74fc7a1d10056d88373">llvm::raw_ostream::write_zeros</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsN32 {#a344d0986506990a23f260c47dc0ea88a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsAsmBackend::IsN32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>.</p>

</div>
</div>

### TheTriple {#abbbe3c280ff9ef671b7d85a8b417a141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::MipsAsmBackend::TheTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-cpp">MipsAsmBackend.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsasmbackend-h">MipsAsmBackend.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
