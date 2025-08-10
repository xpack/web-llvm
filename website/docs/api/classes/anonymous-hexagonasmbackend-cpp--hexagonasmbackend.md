---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HexagonAsmBackend` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b432a75e4c8499722355b663f221326">HexagonAsmBackend</a> (const Target &amp;T, const Triple &amp;TT, uint8_t OSABI, StringRef CPU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ec10dc2c03306d6af8dca3fcdf7bed">createObjectTargetWriter</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f15b18cabd44b81a747ab2801302ebe">setExtender</a> (MCContext &amp;Context) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e028c8da3f6987e96b0a6ecd17e8683">takeExtender</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b07f04cec36431247582b5012ed8de">getNumFixupKinds</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of target specific fixup kinds. <a href="#a11b07f04cec36431247582b5012ed8de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaee0ad4212de302179900df9f6acaf0">getFixupKindInfo</a> (MCFixupKind Kind) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get information on a fixup kind. <a href="#adaee0ad4212de302179900df9f6acaf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac398fae75ecf58a6927e06f0a6206bf6">shouldForceRelocation</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, const uint64_t, const MCSubtargetInfo *STI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook to check if a relocation is needed for some target specific reason. <a href="#ac398fae75ecf58a6927e06f0a6206bf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b3e808d3a4c48865a0b8cb59487f7d">HandleFixupError</a> (const int bits, const int align_bits, const int64_t FixupValue, const char *fixupStr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb84e0118cb55bac7f2f1b46ccc6ff3d">applyFixup</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, MutableArrayRef&lt; char &gt; Data, uint64_t FixupValue, bool IsResolved, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ApplyFixup - Apply the. <a href="#acb84e0118cb55bac7f2f1b46ccc6ff3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135855aba8ee58019db788042c0d9a54">isInstRelaxable</a> (MCInst const &amp;HMI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9758e55140e8285d5e686cab77ba6b2">mayNeedRelaxation</a> (MCInst const &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MayNeedRelaxation - Check whether the given instruction may need relaxation. <a href="#af9758e55140e8285d5e686cab77ba6b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabc01e9899fccd76ffd3a0c7da023fb5">fixupNeedsRelaxationAdvanced</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, bool Resolved, uint64_t Value, const MCRelaxableFragment *DF, const bool WasForced) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fixupNeedsRelaxation - <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific predicate for whether a given fixup requires the associated instruction to be relaxed. <a href="#aabc01e9899fccd76ffd3a0c7da023fb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22c9938ad82cf97ee6cc8cf00d265cc">relaxInstruction</a> (MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Relax the instruction in the given fragment to the next wider instruction. <a href="#af22c9938ad82cf97ee6cc8cf00d265cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c00c27f8d0dd1c66b06b38458748a29">writeNopData</a> (raw_ostream &amp;OS, uint64_t Count, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write an (optimal) nop sequence of Count bytes to the given output. <a href="#a4c00c27f8d0dd1c66b06b38458748a29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f3e864193e615bb8e8bda2cca24ff3">finishLayout</a> (MCAssembler const &amp;Asm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Give backend an opportunity to finish layout after relaxation. <a href="#a11f3e864193e615bb8e8bda2cca24ff3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8636a3687f62d42e4e67e3d8a1f6eef9">ReplaceInstruction</a> (MCCodeEmitter &amp;E, MCRelaxableFragment &amp;RF, MCInst &amp;HMB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ba151035e79ada9153eb537586175e">OSABI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dfcaff782a94b971f3c53f10076f703">CPU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fa866f2973f39ea5855815a09f47aa7">relaxedCnt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1572d446770d97ce9bedf563f3f55f22">MCII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9530c1304d9fcd957157bd1ba0aaaca3">RelaxTarget</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af933c6eec221db16836f0e3b153b5b00">Extender</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a217a206982028ff5c8888a91b457059c">MaxPacketSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a837c9361b583e084829da4271f799d84">getFixupKindNumBytes</a> (unsigned Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getFixupKindNumBytes - The number of bytes the fixup may change. <a href="#a837c9361b583e084829da4271f799d84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aece1d67f05090d0ad648b88294aeb586">adjustFixupValue</a> (MCFixupKind Kind, uint64_t Value)</td>
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


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonAsmBackend() {#a2b432a75e4c8499722355b663f221326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::HexagonAsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, uint8_t OSABI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a249ee518076ddd95d8bdae34bd403a39">createMCInstrInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a3dd30d6980185ef34e42333191453867">llvm::MCAsmBackend::MCAsmBackend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a72eaee9433568ed277e40ed923f7bb50">llvm::createHexagonAsmBackend</a>, <a href="#a7f15b18cabd44b81a747ab2801302ebe">setExtender</a> and <a href="#a7e028c8da3f6987e96b0a6ecd17e8683">takeExtender</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyFixup() {#acb84e0118cb55bac7f2f1b46ccc6ff3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::applyFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Data, uint64_t FixupValue, bool IsResolved, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>ApplyFixup - Apply the.</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for given</li>
<li>Fixup into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate.</li>
</ul>

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ae03bfc95ecd6ac86582ade86cd2711f1">adjustFixupValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa0a49adb0d61b7f58450fa61d489c9de5">llvm::Hexagon::fixup_Hexagon_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3892bebaed52b6bb7704fb4705bfd3ea">llvm::Hexagon::fixup_Hexagon_B13_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5742fbb01e95827aa1d4fed0e8bf49db">llvm::Hexagon::fixup_Hexagon_B13_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8e7f405b8420c4b38d640cd008c0f1b5">llvm::Hexagon::fixup_Hexagon_B15_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadba6b69224d9575e3845b5a1d5fbf437">llvm::Hexagon::fixup_Hexagon_B15_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9d43956f2ba0ad2b6a14b6f15d8a9d1b">llvm::Hexagon::fixup_Hexagon_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadfd8c0fda1dc285ceabeb34ddcd3a226">llvm::Hexagon::fixup_Hexagon_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa659fb706c1401f9541effc64fa54ba68">llvm::Hexagon::fixup_Hexagon_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faec512985edaee90285f046598a99c063">llvm::Hexagon::fixup_Hexagon_B7_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa2fc452a2d9e80df1f68ec27693e9632c">llvm::Hexagon::fixup_Hexagon_B7_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8433e062504192a5113a2e9d08e911e2">llvm::Hexagon::fixup_Hexagon_B9_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf7ad305a417f6572f3ecc7d3d73179ca">llvm::Hexagon::fixup_Hexagon_B9_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="#adaee0ad4212de302179900df9f6acaf0">getFixupKindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp/#ac372fb24df18ed69d99fb8658ec0e7a7">getFixupKindNumBytes</a>, <a href="#a09b3e808d3a4c48865a0b8cb59487f7d">HandleFixupError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad80b46c754cc7216244a866ec9b1cb0">llvm::isIntN</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a37b5dd8a8b82f2818e0f4ea9699d8ae5">llvm::raw_ostream::write_hex</a>.</p>

</div>
</div>

### createObjectTargetWriter() {#a22ec10dc2c03306d6af8dca3fcdf7bed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MCObjectTargetWriter &gt; anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::createObjectTargetWriter ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a5b7e8838b0e52c94c10f13deed0a9c02">llvm::createHexagonELFObjectWriter</a>.</p>

</div>
</div>

### finishLayout() {#a11f3e864193e615bb8e8bda2cca24ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::finishLayout (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Asm)</td>
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

<p>Give backend an opportunity to finish layout after relaxation.</p>

<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a246da06f2e49f678663ae6e21bedffb3">llvm::HexagonMCInstrInfo::bundleSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcchecker/#a51fa2302a4a13602a1942ab9cd7588ff">llvm::HexagonMCChecker::check</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae86bea5bf6fe3c0a2a9f09f5fdc4a310">llvm::MCOperand::createInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68a1f3544ccfba8bd153218f9aff934ae23">llvm::MCFragment::FT_Align</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#aebf48160a3995325c6d2465080bcab68abe5194c45ead6aefe6b0882dcb6f2104">llvm::MCFragment::FT_Relaxable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment/#a970b0dade67a110b2d700dda628054c6">llvm::MCRelaxableFragment::getInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a2c97dba695c5b5fa2bcc39c47c3b0762">llvm::MCEncodedFragment::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e62b46a3eb52ccf356ac99f8ebb3c06">llvm::HexagonMCShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### fixupNeedsRelaxationAdvanced() {#aabc01e9899fccd76ffd3a0c7da023fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::fixupNeedsRelaxationAdvanced (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool Resolved, uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> * DF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool WasForced)</td>
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

<p>fixupNeedsRelaxation - <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific predicate for whether a given fixup requires the associated instruction to be relaxed.</p>

<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a246da06f2e49f678663ae6e21bedffb3">llvm::HexagonMCInstrInfo::bundleSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3892bebaed52b6bb7704fb4705bfd3ea">llvm::Hexagon::fixup_Hexagon_B13_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8e7f405b8420c4b38d640cd008c0f1b5">llvm::Hexagon::fixup_Hexagon_B15_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9d43956f2ba0ad2b6a14b6f15d8a9d1b">llvm::Hexagon::fixup_Hexagon_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faec512985edaee90285f046598a99c063">llvm::Hexagon::fixup_Hexagon_B7_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8433e062504192a5113a2e9d08e911e2">llvm::Hexagon::fixup_Hexagon_B9_PCREL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8b3161e980be30851bf3f346ca0550ce">HEXAGON_INSTR_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#adda8e3193ca3d31e415a2e4ac6089d50">llvm::HexagonMCInstrInfo::instruction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a69d33e060c5b0bbfe0f8a2cbeb71f598">llvm::HexagonMCInstrInfo::isBundle</a>, <a href="#a135855aba8ee58019db788042c0d9a54">isInstRelaxable</a> and <a href="#a7f15b18cabd44b81a747ab2801302ebe">setExtender</a>.</p>

</div>
</div>

### getFixupKindInfo() {#adaee0ad4212de302179900df9f6acaf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCFixupKindInfo &amp; anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::getFixupKindInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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

<p>Get information on a fixup kind.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="#a11b07f04cec36431247582b5012ed8de">getNumFixupKinds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa6ae0c38cd8fb6d8505e1d6008bd48f50">llvm::Hexagon::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#acb84e0118cb55bac7f2f1b46ccc6ff3d">applyFixup</a>.</p>

</div>
</div>

### getNumFixupKinds() {#a11b07f04cec36431247582b5012ed8de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::getNumFixupKinds ()</td>
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

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa6ae0c38cd8fb6d8505e1d6008bd48f50">llvm::Hexagon::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#adaee0ad4212de302179900df9f6acaf0">getFixupKindInfo</a>.</p>

</div>
</div>

### HandleFixupError() {#a09b3e808d3a4c48865a0b8cb59487f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::HandleFixupError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int bits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int align_bits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int64_t FixupValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * fixupStr)</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#acb84e0118cb55bac7f2f1b46ccc6ff3d">applyFixup</a>.</p>

</div>
</div>

### isInstRelaxable() {#a135855aba8ee58019db788042c0d9a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::isInstRelaxable (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; HMI)</td>
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



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5d6d2c647044122707e6ebc1f62f7c67">llvm::HexagonMCInstrInfo::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5115f4f0f0213e99431e82c167be0b98">llvm::HexagonMCInstrInfo::getExtendableOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a94f0ca29631596dfaa69418dd1dd6cbd">llvm::HexagonMCInstrInfo::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a8c525c01df0d371a390190574d22bccc">llvm::HexagonMCInstrInfo::isExtendable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5ad0644e32da21f9b472af7cdcd6a9d4">llvm::HexagonMCInstrInfo::mustNotExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ad720fe766d40e8defad0b11e39ed72cf">llvm::HexagonII::TypeCJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a26ca54cbeaf9cd797a07ae0c316b73b0">llvm::HexagonII::TypeCR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a9ef44633e8b88d5296c9251b1c9dcb88">llvm::HexagonII::TypeJ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807ac169e59f59e13ba605133af333a9f62f">llvm::HexagonII::TypeNCJ</a>.</p>


<p>Referenced by <a href="#aabc01e9899fccd76ffd3a0c7da023fb5">fixupNeedsRelaxationAdvanced</a>.</p>

</div>
</div>

### mayNeedRelaxation() {#af9758e55140e8285d5e686cab77ba6b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::mayNeedRelaxation (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>MayNeedRelaxation - Check whether the given instruction may need relaxation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inst</td>
<td class="doxyParamItemDescription"><p>- The instruction to test.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>

</div>
</div>

### relaxInstruction() {#af22c9938ad82cf97ee6cc8cf00d265cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a607343a05725b53e0d5bd85a4a44586e">llvm::HexagonMCInstrInfo::bundleInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a246da06f2e49f678663ae6e21bedffb3">llvm::HexagonMCInstrInfo::bundleSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae86bea5bf6fe3c0a2a9f09f5fdc4a310">llvm::MCOperand::createInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#afef5615be55fa8a93b6a92b8c787aad0">llvm::HexagonMCInstrInfo::deriveExtender</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aea78a68d4baf2fd4614a3be3a14dd548">llvm::HexagonMCInstrInfo::getExtendableOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8f76c0f5e34856920717e06ebc5f4dc3">HEXAGON_PACKET_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a69d33e060c5b0bbfe0f8a2cbeb71f598">llvm::HexagonMCInstrInfo::isBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a> and <a href="#a7e028c8da3f6987e96b0a6ecd17e8683">takeExtender</a>.</p>

</div>
</div>

### setExtender() {#a7f15b18cabd44b81a747ab2801302ebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::setExtender (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>Reference <a href="#a2b432a75e4c8499722355b663f221326">HexagonAsmBackend</a>.</p>


<p>Referenced by <a href="#aabc01e9899fccd76ffd3a0c7da023fb5">fixupNeedsRelaxationAdvanced</a>.</p>

</div>
</div>

### shouldForceRelocation() {#ac398fae75ecf58a6927e06f0a6206bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::shouldForceRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Hook to check if a relocation is needed for some target specific reason.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp/#aa57c66831334dfff51354be452ebbe21">DisableFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad99ecf031674f184411b22dc55e59659">llvm::Hexagon::fixup_Hexagon_10_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fab6c0d1722606ba0c87cf23facac8cf9a">llvm::Hexagon::fixup_Hexagon_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa4a4308781cf42caa5826013ce7196fa5">llvm::Hexagon::fixup_Hexagon_12_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa983047fe1d9d76db3ea8ada08e1a1761">llvm::Hexagon::fixup_Hexagon_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1238f42b1826506b29adb8d7e79b6881">llvm::Hexagon::fixup_Hexagon_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf45ac0138cce02b717e60b43ac920e06">llvm::Hexagon::fixup_Hexagon_23_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa105e484db4846fe2f4433677246b78e3">llvm::Hexagon::fixup_Hexagon_27_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa0a49adb0d61b7f58450fa61d489c9de5">llvm::Hexagon::fixup_Hexagon_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8d74109744840889ca2b701dfcdac096">llvm::Hexagon::fixup_Hexagon_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa58d886d876663e910bb42d4711cd3a47">llvm::Hexagon::fixup_Hexagon_32_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa94c391478d4495def35b608d8d49aecd">llvm::Hexagon::fixup_Hexagon_6_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa75669d3838a8248efdcecdf57ea4eaee">llvm::Hexagon::fixup_Hexagon_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa88a5681b1be1d10a65270e11a9680a51">llvm::Hexagon::fixup_Hexagon_7_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4facd53bc898ef0ddc41efd51d392581b89">llvm::Hexagon::fixup_Hexagon_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1752309db082a3eaf850e6478cb6e2ac">llvm::Hexagon::fixup_Hexagon_8_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fac2aefbd0a7d3415735342e0b3dd7607d">llvm::Hexagon::fixup_Hexagon_9_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3892bebaed52b6bb7704fb4705bfd3ea">llvm::Hexagon::fixup_Hexagon_B13_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5742fbb01e95827aa1d4fed0e8bf49db">llvm::Hexagon::fixup_Hexagon_B13_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8e7f405b8420c4b38d640cd008c0f1b5">llvm::Hexagon::fixup_Hexagon_B15_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadba6b69224d9575e3845b5a1d5fbf437">llvm::Hexagon::fixup_Hexagon_B15_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9d43956f2ba0ad2b6a14b6f15d8a9d1b">llvm::Hexagon::fixup_Hexagon_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadfd8c0fda1dc285ceabeb34ddcd3a226">llvm::Hexagon::fixup_Hexagon_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa659fb706c1401f9541effc64fa54ba68">llvm::Hexagon::fixup_Hexagon_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faec512985edaee90285f046598a99c063">llvm::Hexagon::fixup_Hexagon_B7_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa2fc452a2d9e80df1f68ec27693e9632c">llvm::Hexagon::fixup_Hexagon_B7_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8433e062504192a5113a2e9d08e911e2">llvm::Hexagon::fixup_Hexagon_B9_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf7ad305a417f6572f3ecc7d3d73179ca">llvm::Hexagon::fixup_Hexagon_B9_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1e3c630a7c5b5dc7c5329435a6b41a97">llvm::Hexagon::fixup_Hexagon_COPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3e900a9a202bbab42a492fa01de22593">llvm::Hexagon::fixup_Hexagon_DTPMOD_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa824c46bf71f91ca5c47d28f611512b25">llvm::Hexagon::fixup_Hexagon_DTPREL_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa7380060dd15e7fae6a660465c0c0215a">llvm::Hexagon::fixup_Hexagon_DTPREL_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad98d188763eb82743804f9487e2aa1e7">llvm::Hexagon::fixup_Hexagon_DTPREL_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa877c2ee214a59923396a49df10525171">llvm::Hexagon::fixup_Hexagon_DTPREL_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa703bfe0936ee91755b39ec64dceed58b">llvm::Hexagon::fixup_Hexagon_DTPREL_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3ad50b0feaad604ba6c3e1bb12d5d53e">llvm::Hexagon::fixup_Hexagon_DTPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8a0fc945427de25d74ac06fbfec27455">llvm::Hexagon::fixup_Hexagon_DTPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa69dd3f3b5eee56c84b9d3d753f9f3696">llvm::Hexagon::fixup_Hexagon_GD_GOT_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5bddf1f4c7df22f46a83d1ffeec2d9dc">llvm::Hexagon::fixup_Hexagon_GD_GOT_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa698984f6e98ef90a74f4ffb1110c8e83">llvm::Hexagon::fixup_Hexagon_GD_GOT_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa95aa368cc3aa0efc85295e5e0fda662e">llvm::Hexagon::fixup_Hexagon_GD_GOT_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa46bb2621d89288ade28fc1ef2bcd0d7d">llvm::Hexagon::fixup_Hexagon_GD_GOT_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa0bd2f6d5a9ddac2ae30d825a7c9c0aff">llvm::Hexagon::fixup_Hexagon_GD_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa71ffeb67d2bb37d7ca90058c88c87d7a">llvm::Hexagon::fixup_Hexagon_GD_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9a689f3ed64b9083dc9b5b9d8cfaaf68">llvm::Hexagon::fixup_Hexagon_GD_PLT_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa95bb47d6433e0d1496f52a00247731dd">llvm::Hexagon::fixup_Hexagon_GD_PLT_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa72100ecf8c35b05ed173bdb24b6cd01e">llvm::Hexagon::fixup_Hexagon_GD_PLT_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa27b6bfa00bdafea93c099b82427a4825">llvm::Hexagon::fixup_Hexagon_GLOB_DAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad2f0d42bcf2a8b8d8cc55870ea4f968a">llvm::Hexagon::fixup_Hexagon_GOT_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa10325a6488d2667fde692f8168f36536">llvm::Hexagon::fixup_Hexagon_GOT_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5b53b6d46a35711771f21d6988e00bc6">llvm::Hexagon::fixup_Hexagon_GOT_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1650494cb02ba11cae46812eab294dd4">llvm::Hexagon::fixup_Hexagon_GOT_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fac97b8f66ee281a6286efcebc4697e7ed">llvm::Hexagon::fixup_Hexagon_GOT_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa0bd79ef1d1a6a62fb91a9f28447b1e3c">llvm::Hexagon::fixup_Hexagon_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa6983463228ac808d9fdb72f996efd344">llvm::Hexagon::fixup_Hexagon_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad4fc2083e1517b0cf6dfd085231fbd89">llvm::Hexagon::fixup_Hexagon_GOTREL_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fafa196a1c11f392e0d0778479cbdcb390">llvm::Hexagon::fixup_Hexagon_GOTREL_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa886678bbd3b53e49c1e613b69345eb82">llvm::Hexagon::fixup_Hexagon_GOTREL_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf1153ccc22742ec0464cb1b9927eecc9">llvm::Hexagon::fixup_Hexagon_GOTREL_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa58f925e6ea2b9418e5f060c7a20db09e">llvm::Hexagon::fixup_Hexagon_GOTREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fabfc9bbd4439da18ba02014c0034ab906">llvm::Hexagon::fixup_Hexagon_GOTREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9138381af1cca4c3b1b6d704b99a1264">llvm::Hexagon::fixup_Hexagon_GPREL16_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8772f6b3894ea2528dd63a9b18d486c0">llvm::Hexagon::fixup_Hexagon_GPREL16_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa86787739672c42f914e9cff84b54fd08">llvm::Hexagon::fixup_Hexagon_GPREL16_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa09ee45819d307cd444ef760ba4b4a839">llvm::Hexagon::fixup_Hexagon_GPREL16_3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9ac1d082837fe4e072372d5479ecd945">llvm::Hexagon::fixup_Hexagon_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa79ef6386750168ee03339b4d203ec396">llvm::Hexagon::fixup_Hexagon_HL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa47a387a1776b251aaf360a6dce6c506a">llvm::Hexagon::fixup_Hexagon_IE_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa762facc50089208c6007d89f6935c99b">llvm::Hexagon::fixup_Hexagon_IE_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa96cfce497d5a8ffbc24e234b6b5b65dd">llvm::Hexagon::fixup_Hexagon_IE_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fae0bfea17caa1f1375f045bc52c812870">llvm::Hexagon::fixup_Hexagon_IE_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fae412b909dd6c896523c05e3d7f1315d9">llvm::Hexagon::fixup_Hexagon_IE_GOT_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fab8ade61a33bbfaa4d5a25268acc2b601">llvm::Hexagon::fixup_Hexagon_IE_GOT_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1437ba334dcf5bdf60eed35e439eeccd">llvm::Hexagon::fixup_Hexagon_IE_GOT_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9ad1ee188faef46ac49cd93b07a0e805">llvm::Hexagon::fixup_Hexagon_IE_GOT_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa59c78c64a975df3e44624569e8142127">llvm::Hexagon::fixup_Hexagon_IE_GOT_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fac7156b443277048d58471fe1abd746e9">llvm::Hexagon::fixup_Hexagon_IE_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3eee608f87c662e714399c4da1bcdfe0">llvm::Hexagon::fixup_Hexagon_IE_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa640f88cd125f9b795bf9ea5637c1af80">llvm::Hexagon::fixup_Hexagon_IE_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf702bce95b626ec4b9882426369264e4">llvm::Hexagon::fixup_Hexagon_IE_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa170d14cf0c7d0e241f21dde3baf09d24">llvm::Hexagon::fixup_Hexagon_JMP_SLOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad2c0c2014c24cb796bfcbeebd7bc8a02">llvm::Hexagon::fixup_Hexagon_LD_GOT_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8f23abef486b6e149287dd187f4a1774">llvm::Hexagon::fixup_Hexagon_LD_GOT_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8e2d48cfc26356af4a52ab9738e813de">llvm::Hexagon::fixup_Hexagon_LD_GOT_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fae835cb5b9d766d2a38aa6dc318ead74c">llvm::Hexagon::fixup_Hexagon_LD_GOT_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faab1514b556208cf0151233da6d70a0c1">llvm::Hexagon::fixup_Hexagon_LD_GOT_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa46d5b5f65f0c34f1df0dc1d127bb267b">llvm::Hexagon::fixup_Hexagon_LD_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fab96a52b0f2dd5f94298e3a0c2b292498">llvm::Hexagon::fixup_Hexagon_LD_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1d78e3d110cd9b108eae5c7dfe20b9c3">llvm::Hexagon::fixup_Hexagon_LD_PLT_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa43847e6cd11cfe076051a9997931709a">llvm::Hexagon::fixup_Hexagon_LD_PLT_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa07f492a937c5572b112d66da7966073c">llvm::Hexagon::fixup_Hexagon_LD_PLT_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa62fc0b99badda962b2f1bcdd1367ff13">llvm::Hexagon::fixup_Hexagon_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5de78d76e447c09d64aff72960145cd2">llvm::Hexagon::fixup_Hexagon_PLT_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa85cc680592aabe5903faee5dbe52a293">llvm::Hexagon::fixup_Hexagon_RELATIVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fabb0a4c45ae086959ca277bb07406f6ee">llvm::Hexagon::fixup_Hexagon_TPREL_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa404621dd8b91539d09de1373561a5443">llvm::Hexagon::fixup_Hexagon_TPREL_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa2a2067c1eb00e35133f5d83164e77267">llvm::Hexagon::fixup_Hexagon_TPREL_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa51750857d8c467426b78cf2b3335ba92">llvm::Hexagon::fixup_Hexagon_TPREL_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa27a221e1c9b48f060c699ffef2bc3784">llvm::Hexagon::fixup_Hexagon_TPREL_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faa5df11702270e9d9efea4564ee46ebeb">llvm::Hexagon::fixup_Hexagon_TPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faa504ba238a35d3921438a7cc482d33ad">llvm::Hexagon::fixup_Hexagon_TPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### takeExtender() {#a7e028c8da3f6987e96b0a6ecd17e8683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst * anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::takeExtender ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a2b432a75e4c8499722355b663f221326">HexagonAsmBackend</a>.</p>


<p>Referenced by <a href="#af22c9938ad82cf97ee6cc8cf00d265cc">relaxInstruction</a>.</p>

</div>
</div>

### writeNopData() {#a4c00c27f8d0dd1c66b06b38458748a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::writeNopData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Write an (optimal) nop sequence of Count bytes to the given output.</p>


<p>If the target cannot generate such a sequence, it should return an error.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True on success.</p></dd>
</dl>


<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a8b3161e980be30851bf3f346ca0550ce">HEXAGON_INSTR_SIZE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ReplaceInstruction() {#a8636a3687f62d42e4e67e3d8a1f6eef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::ReplaceInstruction (<a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &amp; E, <a href="/web-llvm/docs/api/classes/llvm/mcrelaxablefragment">MCRelaxableFragment</a> &amp; RF, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; HMB)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CPU {#a6dfcaff782a94b971f3c53f10076f703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::CPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>

</div>
</div>

### Extender {#af933c6eec221db16836f0e3b153b5b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst* anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::Extender</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>

</div>
</div>

### MaxPacketSize {#a217a206982028ff5c8888a91b457059c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::MaxPacketSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>

</div>
</div>

### MCII {#a1572d446770d97ce9bedf563f3f55f22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCInstrInfo&gt; anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::MCII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>

</div>
</div>

### OSABI {#a06ba151035e79ada9153eb537586175e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::OSABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>

</div>
</div>

### relaxedCnt {#a3fa866f2973f39ea5855815a09f47aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::relaxedCnt</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>

</div>
</div>

### RelaxTarget {#a9530c1304d9fcd957157bd1ba0aaaca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCInst *&gt; anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::RelaxTarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### adjustFixupValue() {#aece1d67f05090d0ad648b88294aeb586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::adjustFixupValue (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind, uint64_t Value)</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3892bebaed52b6bb7704fb4705bfd3ea">llvm::Hexagon::fixup_Hexagon_B13_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5742fbb01e95827aa1d4fed0e8bf49db">llvm::Hexagon::fixup_Hexagon_B13_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8e7f405b8420c4b38d640cd008c0f1b5">llvm::Hexagon::fixup_Hexagon_B15_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadba6b69224d9575e3845b5a1d5fbf437">llvm::Hexagon::fixup_Hexagon_B15_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9d43956f2ba0ad2b6a14b6f15d8a9d1b">llvm::Hexagon::fixup_Hexagon_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadfd8c0fda1dc285ceabeb34ddcd3a226">llvm::Hexagon::fixup_Hexagon_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa659fb706c1401f9541effc64fa54ba68">llvm::Hexagon::fixup_Hexagon_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faec512985edaee90285f046598a99c063">llvm::Hexagon::fixup_Hexagon_B7_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa2fc452a2d9e80df1f68ec27693e9632c">llvm::Hexagon::fixup_Hexagon_B7_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8433e062504192a5113a2e9d08e911e2">llvm::Hexagon::fixup_Hexagon_B9_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf7ad305a417f6572f3ecc7d3d73179ca">llvm::Hexagon::fixup_Hexagon_B9_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa72100ecf8c35b05ed173bdb24b6cd01e">llvm::Hexagon::fixup_Hexagon_GD_PLT_B32_PCREL_X</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa07f492a937c5572b112d66da7966073c">llvm::Hexagon::fixup_Hexagon_LD_PLT_B32_PCREL_X</a>.</p>

</div>
</div>

### getFixupKindNumBytes() {#a837c9361b583e084829da4271f799d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::getFixupKindNumBytes (unsigned Kind)</td>
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

<p>getFixupKindNumBytes - The number of bytes the fixup may change.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa0a49adb0d61b7f58450fa61d489c9de5">llvm::Hexagon::fixup_Hexagon_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3892bebaed52b6bb7704fb4705bfd3ea">llvm::Hexagon::fixup_Hexagon_B13_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5742fbb01e95827aa1d4fed0e8bf49db">llvm::Hexagon::fixup_Hexagon_B13_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8e7f405b8420c4b38d640cd008c0f1b5">llvm::Hexagon::fixup_Hexagon_B15_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadba6b69224d9575e3845b5a1d5fbf437">llvm::Hexagon::fixup_Hexagon_B15_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9d43956f2ba0ad2b6a14b6f15d8a9d1b">llvm::Hexagon::fixup_Hexagon_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadfd8c0fda1dc285ceabeb34ddcd3a226">llvm::Hexagon::fixup_Hexagon_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa659fb706c1401f9541effc64fa54ba68">llvm::Hexagon::fixup_Hexagon_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faec512985edaee90285f046598a99c063">llvm::Hexagon::fixup_Hexagon_B7_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa2fc452a2d9e80df1f68ec27693e9632c">llvm::Hexagon::fixup_Hexagon_B7_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8433e062504192a5113a2e9d08e911e2">llvm::Hexagon::fixup_Hexagon_B9_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf7ad305a417f6572f3ecc7d3d73179ca">llvm::Hexagon::fixup_Hexagon_B9_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa72100ecf8c35b05ed173bdb24b6cd01e">llvm::Hexagon::fixup_Hexagon_GD_PLT_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa07f492a937c5572b112d66da7966073c">llvm::Hexagon::fixup_Hexagon_LD_PLT_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonasmbackend-cpp">HexagonAsmBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
