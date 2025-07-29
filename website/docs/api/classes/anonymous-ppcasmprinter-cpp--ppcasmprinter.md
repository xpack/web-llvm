---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCAsmPrinter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is intended to be used as a driving class for all asm writers. <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter">PPCAIXAsmPrinter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter">PPCLinuxAsmPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter">PPCLinuxAsmPrinter</a> - PowerPC assembly printer, customized for Linux. <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">TOCEntryType { <a href="#a89afc4ac7f190ecd3a3477233cbc7a2c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ff58b45ac27585d64b06c4c511203af">PPCAsmPrinter</a> (TargetMachine &amp;TM, std::unique_ptr&lt; MCStreamer &gt; Streamer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286c4fcfc2468b0c24b7c8a244431680">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a286c4fcfc2468b0c24b7c8a244431680">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c898bad0c4231a321821ddc71384cf3">lookUpOrCreateTOCEntry</a> (const MCSymbol *Sym, TOCEntryType Type, MCSymbolRefExpr::VariantKind Kind=MCSymbolRefExpr::VariantKind::VK_None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lookUpOrCreateTOCEntry – Given a symbol, look up whether a TOC entry exists for it. <a href="#a1c898bad0c4231a321821ddc71384cf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8db7e061867921fb14fc196998f467c7">doInitialization</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up the AsmPrinter when we are working on a new module. <a href="#a8db7e061867921fb14fc196998f467c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dce3e9284d907db3457ebbfc74909f7">emitInstruction</a> (const MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitInstruction – Print out a single PowerPC MI in Darwin syntax to the current output stream. <a href="#a8dce3e9284d907db3457ebbfc74909f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad00203b7ccef5249a4dda62efbd1be07">printOperand</a> (const MachineInstr *MI, unsigned OpNo, raw_ostream &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is for PrintAsmOperand and PrintAsmMemoryOperand, invoked by EmitMSInlineAsmStr and EmitGCCInlineAsmStr only. <a href="#ad00203b7ccef5249a4dda62efbd1be07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f8e1481cddfd9f6c8b70c75f7450db">PrintSymbolOperand</a> (const MachineOperand &amp;MO, raw_ostream &amp;O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the MachineOperand as a symbol. <a href="#ab6f8e1481cddfd9f6c8b70c75f7450db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bbac805be0153c6ba2c002e08a77388">PrintAsmOperand</a> (const MachineInstr *MI, unsigned OpNo, const char *ExtraCode, raw_ostream &amp;O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PrintAsmOperand - Print out an operand for an inline asm expression. <a href="#a0bbac805be0153c6ba2c002e08a77388">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a758959d103a6db4daf1f07ea906cd657">PrintAsmMemoryOperand</a> (const MachineInstr *MI, unsigned OpNo, const char *ExtraCode, raw_ostream &amp;O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant as an address. <a href="#a758959d103a6db4daf1f07ea906cd657">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace062181b0166f4afdd510884a411583">LowerSTACKMAP</a> (StackMaps &amp;SM, const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf266e359a05a56bd9533dff30b3e12">LowerPATCHPOINT</a> (StackMaps &amp;SM, const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5eda02c50a11f3dde025afe0675b6e">EmitTlsCall</a> (const MachineInstr *MI, MCSymbolRefExpr::VariantKind VK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitTlsCall – Given a GETtls[ld]ADDR[32] instruction, print a call to __tls_get_addr to the current output stream. <a href="#a0c5eda02c50a11f3dde025afe0675b6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acec704ab147b53f347bf1020f050665d">EmitAIXTlsCallHelper</a> (const MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7810a05a90e7fc6d13fa85c0242ab5f">getAdjustedFasterLocalExpr</a> (const MachineOperand &amp;MO, int64_t Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18157b59b68837aae0f41a1018bf4525">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the specified function out to the OutStreamer. <a href="#a18157b59b68837aae0f41a1018bf4525">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a9f5abc8bc96c0f6aad7e8a2ef5e343">TOC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d680022bd0368819b4d6f511765a13">Subtarget</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade0e59f0d0a86894dadff63d7933b42d">TLSVarsToAddressMapping</a></td>
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


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### TOCEntryType {#a89afc4ac7f190ecd3a3477233cbc7a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::TOCEntryType </td>
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
<td class="doxyEnumItemName">TOCType_ConstantPool<a id="a89afc4ac7f190ecd3a3477233cbc7a2ca792ef2313c4a3378f0ea146d9abe878d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCType_GlobalExternal<a id="a89afc4ac7f190ecd3a3477233cbc7a2ca2a5d76c7eaf994877948e3dc41f64c3e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCType_GlobalInternal<a id="a89afc4ac7f190ecd3a3477233cbc7a2ca7b78f44952a2d0a9275b685f7cf525cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCType_JumpTable<a id="a89afc4ac7f190ecd3a3477233cbc7a2cacbe41b167510b5ced82d9bd880e82374"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCType_ThreadLocal<a id="a89afc4ac7f190ecd3a3477233cbc7a2caf34586b531d8ae3acdee8f3ecfecd31f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCType_BlockAddress<a id="a89afc4ac7f190ecd3a3477233cbc7a2ca9348392012e03cf7fa9719a3a61e3b4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOCType_EHBlock<a id="a89afc4ac7f190ecd3a3477233cbc7a2ca5fb9658e0fc09a8c6650c16138d1c299"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PPCAsmPrinter() {#a6ff58b45ac27585d64b06c4c511203af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::PPCAsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; Streamer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#afcfe4636c15aaef711e33ecc8638f9b4">llvm::AsmPrinter::AsmPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a7891bd7ab167fc01fb3523e7f1057755">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::PPCAIXAsmPrinter</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a8c814a47b8f04900dc9efa78d9f76a3b">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::PPCLinuxAsmPrinter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doInitialization() {#a8db7e061867921fb14fc196998f467c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Set up the AsmPrinter when we are working on a new module.</p>


<p>If your pass overrides this, it must make sure to explicitly call this implementation.</p>


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7cd6d58462a0ebf3fa2c3d1423b0e2c6">llvm::AsmPrinter::doInitialization</a> and <a href="#a2a9f5abc8bc96c0f6aad7e8a2ef5e343">TOC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>.</p>

</div>
</div>

### EmitAIXTlsCallHelper() {#acec704ab147b53f347bf1020f050665d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCAsmPrinter::EmitAIXTlsCallHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#abfcac3a9ee111cfe8a6df190086ca997">createMCSymbolForTlsGetAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b02eda9bb97934fbcc3d7f29219b931">llvm::AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="#ae2d680022bd0368819b4d6f511765a13">Subtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="#a8dce3e9284d907db3457ebbfc74909f7">emitInstruction</a> and <a href="#a0c5eda02c50a11f3dde025afe0675b6e">EmitTlsCall</a>.</p>

</div>
</div>

### emitInstruction() {#a8dce3e9284d907db3457ebbfc74909f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCAsmPrinter::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>EmitInstruction – Print out a single PowerPC MI in Darwin syntax to the current output stream.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#ad824e6c64e2015a9fbaba9a4c9d0a7b9">llvm::MCInstBuilder::addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#ac6bfc040ddca811a88a95e1f6d6b3747">llvm::MCInstBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a2b9700052102985a61c9cf62b71d68f0">llvm::MCInstBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a4f49f04c5de0799837b4c349c1db8ce2">llvm::PPCMCExpr::createHa</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a4cc67dcfb3533e94b42341e10b8ffe76">llvm::PPCMCExpr::createLo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#acec704ab147b53f347bf1020f050665d">EmitAIXTlsCallHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a11dc1e48c7d0e0da77a6d6d377fd391b">llvm::AsmPrinter::emitNops</a>, <a href="#a0c5eda02c50a11f3dde025afe0675b6e">EmitTlsCall</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b02eda9bb97934fbcc3d7f29219b931">llvm::AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ae7810a05a90e7fc6d13fa85c0242ab5f">getAdjustedFasterLocalExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#aa85a26f5f6b24110a2388e4726cdd282">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa5d2c67dadc073dac78224224ee89350">llvm::GlobalValue::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a5191842b97cefc259bf0689f9565310b">getMCSymbolForTOCPseudoMO</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a47f5c74e1b14ba4a61db057400644acc">llvm::Value::getPointerAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a17b4520610e0151c3ea791c6adf27d07">getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aebe7e48735a59049062e384e810c108a">llvm::AsmPrinter::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a731bb8307207186d81b2a7353f21f199">getTOCEntryTypeForMO</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0d18aef18dd1ef1e35f038d830fed316">llvm::GlobalVariable::hasAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a3cae4242c478d473bfa1af350f126545">llvm::TLSModel::InitialExec</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#abed9003622087a5bbddb7c19b6d02ce6">llvm::MachineOperand::isBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a5b401e780c5eed0aca1cfbf44d36a545">llvm::MachineOperand::isCPI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8eb9bf17230a1c4329e26935f44d72eb">llvm::MachineOperand::isJTI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab2fdacf803a7a00c831b1e3c068a5ce8">llvm::AsmPrinter::isPositionIndependent</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ad50f5d7186d7a17abb53860320a2a5b1">llvm::AsmPrinter::isVerbose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a110e377ad85dc311cb9bce1e32bea8aa">llvm::TLSModel::LocalDynamic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120ae13ef3bbe423ce80086f0a684fd25753">llvm::TLSModel::LocalExec</a>, <a href="#a1c898bad0c4231a321821ddc71384cf3">lookUpOrCreateTOCEntry</a>, <a href="#a3cf266e359a05a56bd9533dff30b3e12">LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75665dd8dc7cd6ec1cb1f06a34ebb042">llvm::LowerPPCMachineInstrToMCInst</a>, <a href="#ace062181b0166f4afdd510884a411583">LowerSTACKMAP</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a47692fd7344d1adc2916ad4cc31d26c8">llvm::AsmPrinter::MAI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffaf045b588ae476aff3ea48b77c042f7b1">llvm::PPCII::MO_GOT_TLSGD_PCREL_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffa467b829ca0e160907522584b98b618a0">llvm::PPCII::MO_GOT_TPREL_PCREL_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffae65924f7be0d235dfb37b97894d631b6">llvm::PPCII::MO_TLSGD_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffa6003030015cbe98f30d697c9c8a155bf">llvm::PPCII::MO_TLSGDM_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffa77f81a23f8ce498f9ef4bbc5433c116b">llvm::PPCII::MO_TLSLD_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffa1dcd064e63645a232083e4de59b09110">llvm::PPCII::MO_TLSLDM_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffac09dc26b3c7ea75dfd6da305042926cb">llvm::PPCII::MO_TPREL_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffa4590d1594bf15001842f0bc03068dc7e">llvm::PPCII::MO_TPREL_PCREL_FLAG</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#afd1501c49c84f3addfd108c2484f5674">PB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd6925150e1774fabfaff17efd3f9b9e">llvm::SignExtend32</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adfcde4e021a2e59edfa21733753ef8f9">llvm::AsmPrinter::SM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>, <a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6ba930654495acf7b77bcf00f2c65c32347">llvm::PICLevel::SmallPIC</a>, <a href="#ae2d680022bd0368819b4d6f511765a13">Subtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>, <a href="#a2a9f5abc8bc96c0f6aad7e8a2ef5e343">TOC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a29f2a3fe672b7936fde6f04eb0284c74">llvm::MCSymbolRefExpr::VK_DTPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a45ef9ce5642cace4f318f108b42e11e6">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a5f3745b2d55b8cb0de42cb6c62fe0ca9">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSGDM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a6c66e7ad14399948694612a5891021c3">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSIE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985af0042f0eb9fb8dba8f49e4bedf5e9e10">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSLD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985afd7d09055e7b976b23804658655b5184">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSLE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a02e865dbaa6698cd599a034b55630829">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSML</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a557068c0a5af8551cfeeebacb4e7b50d">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab8a6b1fa79f3b913402f58157014df7c">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab73442f1c191fde93198b4568cda1dfc">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8df42e2c96f1fc53644f6a6c8353f57c">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSGD_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a7fe6746f350536c8fe0392b0a6670769">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSGD_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ad2369968761f661db6468af845d997f9">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSLD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a11579e28bc40de8894dd92e9dabb677e">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSLD_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a9e1d9b07e91fad292c9fd673ca12e142">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSLD_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4cd5875553111c54d66aa7254d99af01">llvm::MCSymbolRefExpr::VK_PPC_GOT_TPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a10816ac7561fb1d788b69d59c4153236">llvm::MCSymbolRefExpr::VK_PPC_GOT_TPREL_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aed3c47b613307c1c3bb2e123285a324c">llvm::MCSymbolRefExpr::VK_PPC_GOT_TPREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8b7bdf367ac57c04cfe5fc65738f8746">llvm::MCSymbolRefExpr::VK_PPC_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2e024b4ca6a06e62e43f54816758e59e">llvm::MCSymbolRefExpr::VK_PPC_L</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2de16a7019f22064bed686092ccc8697">llvm::MCSymbolRefExpr::VK_PPC_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a14ae083881358216647922cedc7ae4ea">llvm::MCSymbolRefExpr::VK_PPC_LOCAL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a614a4f4a72a1a5fbf6b309990dbf9643">llvm::MCSymbolRefExpr::VK_PPC_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a55f8ba42b33462144024cc7a07194631">llvm::MCSymbolRefExpr::VK_PPC_TLSLD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa4b8b58379694eb9c24793904e2b2089">llvm::MCSymbolRefExpr::VK_PPC_TOC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a86b94af00057681fc558d5ade49f77f9">llvm::MCSymbolRefExpr::VK_PPC_TOC_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a9ea61bcfe12d2dbd766d06581e5abe79">llvm::MCSymbolRefExpr::VK_PPC_TOC_LO</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a357bed48651388b3b7882ed32f085ec1">llvm::MCSymbolRefExpr::VK_PPC_U</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a8a08ac1d3e9758e48d542db8b3fc10ce">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a4123a254ab36bc97c087331e6cb38665">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### EmitTlsCall() {#a0c5eda02c50a11f3dde025afe0675b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCAsmPrinter::EmitTlsCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a> VK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitTlsCall – Given a GETtls[ld]ADDR[32] instruction, print a call to __tls_get_addr to the current output stream.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#ad824e6c64e2015a9fbaba9a4c9d0a7b9">llvm::MCInstBuilder::addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6ba4b47a7c017bdb1e3748f3cd8f78c2899">llvm::PICLevel::BigPIC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="#acec704ab147b53f347bf1020f050665d">EmitAIXTlsCallHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b02eda9bb97934fbcc3d7f29219b931">llvm::AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab2fdacf803a7a00c831b1e3c068a5ce8">llvm::AsmPrinter::isPositionIndependent</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffaf045b588ae476aff3ea48b77c042f7b1">llvm::PPCII::MO_GOT_TLSGD_PCREL_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffad1af346db81472a462b7f04fa9498ab4">llvm::PPCII::MO_GOT_TLSLD_PCREL_FLAG</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="#ae2d680022bd0368819b4d6f511765a13">Subtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985afaacbcfe095c753443e87af4aad33014">llvm::MCSymbolRefExpr::VK_PPC_NOTOC</a>.</p>


<p>Referenced by <a href="#a8dce3e9284d907db3457ebbfc74909f7">emitInstruction</a>.</p>

</div>
</div>

### getAdjustedFasterLocalExpr() {#ae7810a05a90e7fc6d13fa85c0242ab5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * PPCAsmPrinter::getAdjustedFasterLocalExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6b66f492cbea5f4b4f434d7178477116">llvm::GlobalValue::isDeclarationForLinker</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a110e377ad85dc311cb9bce1e32bea8aa">llvm::TLSModel::LocalDynamic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120ae13ef3bbe423ce80086f0a684fd25753">llvm::TLSModel::LocalExec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="#ade0e59f0d0a86894dadff63d7933b42d">TLSVarsToAddressMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985af0042f0eb9fb8dba8f49e4bedf5e9e10">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSLD</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985afd7d09055e7b976b23804658655b5184">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSLE</a>.</p>


<p>Referenced by <a href="#a8dce3e9284d907db3457ebbfc74909f7">emitInstruction</a>.</p>

</div>
</div>

### getPassName() {#a286c4fcfc2468b0c24b7c8a244431680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>

</div>
</div>

### lookUpOrCreateTOCEntry() {#a1c898bad0c4231a321821ddc71384cf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * PPCAsmPrinter::lookUpOrCreateTOCEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="#a89afc4ac7f190ecd3a3477233cbc7a2c">TOCEntryType</a> Type, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a> Kind=MCSymbolRefExpr::VariantKind::VK_None)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>lookUpOrCreateTOCEntry – Given a symbol, look up whether a TOC entry exists for it.</p>


<p>If not, create one. Then return a symbol that references the TOC entry.</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a0f285c285e7aa2ac700f0895ec14c377">collectTOCStats</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa92c1e2c33abf7fb64f544b67f234df6">llvm::AsmPrinter::createTempSymbol</a> and <a href="#a2a9f5abc8bc96c0f6aad7e8a2ef5e343">TOC</a>.</p>


<p>Referenced by <a href="#a8dce3e9284d907db3457ebbfc74909f7">emitInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#aa72747d7d3b33e66672520f5a3e93462">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitTTypeReference</a>.</p>

</div>
</div>

### LowerPATCHPOINT() {#a3cf266e359a05a56bd9533dff30b3e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCAsmPrinter::LowerPATCHPOINT (<a href="/web-llvm/docs/api/classes/llvm/stackmaps">StackMaps</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b02eda9bb97934fbcc3d7f29219b931">llvm::AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#ad86c02ad0c56344cf19e482d1924c9f6">llvm::PatchPointOpers::getCallTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a4ecfe362fe15df202b5605e5378eca1b">llvm::PatchPointOpers::getNextScratchIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#aa319bb1da5a106c84bfa9a1fdca084bc">llvm::PatchPointOpers::getNumPatchBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adfcde4e021a2e59edfa21733753ef8f9">llvm::AsmPrinter::SM</a> and <a href="#ae2d680022bd0368819b4d6f511765a13">Subtarget</a>.</p>


<p>Referenced by <a href="#a8dce3e9284d907db3457ebbfc74909f7">emitInstruction</a>.</p>

</div>
</div>

### LowerSTACKMAP() {#ace062181b0166f4afdd510884a411583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCAsmPrinter::LowerSTACKMAP (<a href="/web-llvm/docs/api/classes/llvm/stackmaps">StackMaps</a> &amp; SM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b02eda9bb97934fbcc3d7f29219b931">llvm::AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#adfcde4e021a2e59edfa21733753ef8f9">llvm::AsmPrinter::SM</a>.</p>


<p>Referenced by <a href="#a8dce3e9284d907db3457ebbfc74909f7">emitInstruction</a>.</p>

</div>
</div>

### PrintAsmMemoryOperand() {#a758959d103a6db4daf1f07ea906cd657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmPrinter::PrintAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ExtraCode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant as an address.</p>


<p>Targets should override this to format as appropriate. This method can return true if the operand is erroneous.</p>


<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae4a28f2ce2647934f469d4bb2144612a">llvm::AsmPrinter::getDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ad00203b7ccef5249a4dda62efbd1be07">printOperand</a>.</p>

</div>
</div>

### PrintAsmOperand() {#a0bbac805be0153c6ba2c002e08a77388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCAsmPrinter::PrintAsmOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ExtraCode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>PrintAsmOperand - Print out an operand for an inline asm expression.</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a84277ab72a3b3a1e5efaf81dd2b85a18">llvm::PPCInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#acc7a469d7d5e4183e2b84d15072786cf">llvm::PPC::isVFRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a5436d12d95e36064db97636d22f20988">llvm::PPC::isVRRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af865b91965a6c4e1082d1510228db5b5">llvm::AsmPrinter::PrintAsmOperand</a>, <a href="#ad00203b7ccef5249a4dda62efbd1be07">printOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a2ddf0f8e0c9ad93a6c3a893df96ef599">llvm::PPC::stripRegisterPrefix</a>.</p>

</div>
</div>

### printOperand() {#ad00203b7ccef5249a4dda62efbd1be07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCAsmPrinter::printOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function is for PrintAsmOperand and PrintAsmMemoryOperand, invoked by EmitMSInlineAsmStr and EmitGCCInlineAsmStr only.</p>


<p>The <span class="doxyComputerOutput">MI</span> would be INLINEASM ONLY.</p>


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a94f5b10f666acf5a0cddd5ac8302d0b8">llvm::MachineOperand::getBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae285dffa957552fa3fe1d34e1bcb7963">llvm::AsmPrinter::GetBlockAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae4a28f2ce2647934f469d4bb2144612a">llvm::AsmPrinter::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a848e97da70c9a3e915855fc0cdaf19a8">llvm::AsmPrinter::getFunctionNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a84277ab72a3b3a1e5efaf81dd2b85a18">llvm::PPCInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1cc134bd22a318835dc929323da70ea4">llvm::MachineBasicBlock::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab313591ae4ea1e3a4ab59121a7dc2a2b">llvm::MachineOperand::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a47692fd7344d1adc2916ad4cc31d26c8">llvm::AsmPrinter::MAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">llvm::MachineOperand::MO_BlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">llvm::MachineOperand::MO_ConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">llvm::MachineOperand::MO_MachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>, <a href="#ab6f8e1481cddfd9f6c8b70c75f7450db">PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a2ddf0f8e0c9ad93a6c3a893df96ef599">llvm::PPC::stripRegisterPrefix</a>.</p>


<p>Referenced by <a href="#a758959d103a6db4daf1f07ea906cd657">PrintAsmMemoryOperand</a> and <a href="#a0bbac805be0153c6ba2c002e08a77388">PrintAsmOperand</a>.</p>

</div>
</div>

### PrintSymbolOperand() {#ab6f8e1481cddfd9f6c8b70c75f7450db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCAsmPrinter::PrintSymbolOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print the MachineOperand as a symbol.</p>


<p>Targets with complex handling of symbol references should override the base implementation.</p>


<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a47692fd7344d1adc2916ad4cc31d26c8">llvm::AsmPrinter::MAI</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9267c5a5f78e26424afb66b404d44d8b">llvm::AsmPrinter::printOffset</a>.</p>


<p>Referenced by <a href="#ad00203b7ccef5249a4dda62efbd1be07">printOperand</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a18157b59b68837aae0f41a1018bf4525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Emit the specified function out to the OutStreamer.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25e51557ff442df4d50f2ad5d1f55743">llvm::AsmPrinter::emitXRayTable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#abdebe99024a5c0aac2587659ba60a581">llvm::AsmPrinter::runOnMachineFunction</a> and <a href="#ae2d680022bd0368819b4d6f511765a13">Subtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Subtarget {#ae2d680022bd0368819b4d6f511765a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCSubtarget* anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::Subtarget = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="#acec704ab147b53f347bf1020f050665d">EmitAIXTlsCallHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#aa667597fe6ef3ceceb450890b00fefad">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitEndOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a4f7d295492d6b2992bc084b59a00557c">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitFunctionBodyEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a0e3f4587b93083fdc01e3ec8f66b3701">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitFunctionBodyStart</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#ac456206c08bdce2e1a11cf14b316bc9a">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a8a08ac1d3e9758e48d542db8b3fc10ce">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitInstruction</a>, <a href="#a8dce3e9284d907db3457ebbfc74909f7">emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a4123a254ab36bc97c087331e6cb38665">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitInstruction</a>, <a href="#a0c5eda02c50a11f3dde025afe0675b6e">EmitTlsCall</a>, <a href="#a3cf266e359a05a56bd9533dff30b3e12">LowerPATCHPOINT</a>, <a href="#a18157b59b68837aae0f41a1018bf4525">runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af0df6b7695918476493cd9b95a4c1f62">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::SetupMachineFunction</a>.</p>

</div>
</div>

### TLSVarsToAddressMapping {#ade0e59f0d0a86894dadff63d7933b42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;const GlobalValue *, uint64_t&gt; anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::TLSVarsToAddressMapping</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a> and <a href="#ae7810a05a90e7fc6d13fa85c0242ab5f">getAdjustedFasterLocalExpr</a>.</p>

</div>
</div>

### TOC {#a2a9f5abc8bc96c0f6aad7e8a2ef5e343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;std::pair&lt;const MCSymbol *, MCSymbolRefExpr::VariantKind&gt;, MCSymbol *&gt; anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::TOC</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a>.</p>


<p>Referenced by <a href="#a8db7e061867921fb14fc196998f467c7">doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#aa667597fe6ef3ceceb450890b00fefad">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitEndOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#ac8c4251bf69ea6c9c941658a83bc9ec4">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitEndOfAsmFile</a>, <a href="#a8dce3e9284d907db3457ebbfc74909f7">emitInstruction</a> and <a href="#a1c898bad0c4231a321821ddc71384cf3">lookUpOrCreateTOCEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp">PPCAsmPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
