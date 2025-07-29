---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrinstprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AVRInstPrinter` Class

<p>Prints <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> instructions to a textual stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRInstPrinter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">Target/AVR/MCTargetDesc/AVRInstPrinter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an instance of a target assembly language printer that converts an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to valid target assembly syntax. <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a282bdeaa0bf79bd9eee45e43def355ce">AVRInstPrinter</a> (const MCAsmInfo &amp;MAI, const MCInstrInfo &amp;MII, const MCRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17adee37669068124e468fdc414437a7">printInst</a> (const MCInst *MI, uint64_t Address, StringRef Annot, const MCSubtargetInfo &amp;STI, raw_ostream &amp;O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to the specified <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#a17adee37669068124e468fdc414437a7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e7ca7f55247dc202af4a429a6bbd7a">printOperand</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05fea845d450085662934db70cda629">printPCRelImm</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is used to print an immediate value that ends up being encoded as a pc-relative value. <a href="#ab05fea845d450085662934db70cda629">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b4a725949e0a7c9f4921d4b9bd7e7b">printPCRelImm</a> (const MCInst *MI, uint64_t, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae848fb1ea11a6e88c934170025f51612">printMemri</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a94ca501ad7fb19d33f7a7bb70eafe">printMemspi</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa90251ecf3fb4f027b0db7dd862e7862">getMnemonic</a> (const MCInst &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pair containing the mnemonic for <span class="doxyComputerOutput">MI</span> and the number of bits left for further processing by printInstruction (generated by tablegen). <a href="#aa90251ecf3fb4f027b0db7dd862e7862">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbdb6244bbfce280d58ca23bc4aff543">printInstruction</a> (const MCInst *MI, uint64_t Address, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f2c7abaaa7c6ce55b52519725efadd">printAliasInstr</a> (const MCInst *MI, uint64_t Address, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a649c9ca260c7c619e670505816189fad">printCustomAliasOperand</a> (const MCInst *MI, uint64_t Address, unsigned OpIdx, unsigned PrintMethodIdx, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764e6f89eb04f23437c3d27b55f448f5">getPrettyRegisterName</a> (MCRegister Reg, MCRegisterInfo const &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ce213f5ed83234bb7d31e79d46fe18a">getRegisterName</a> (MCRegister Reg, unsigned AltIdx=AVR::NoRegAltName)</td>
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

<p>Prints <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> instructions to a textual stream.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AVRInstPrinter() {#a282bdeaa0bf79bd9eee45e43def355ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRInstPrinter::AVRInstPrinter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aacb2bfbafa57a37e627bf1334d349bc6">llvm::MCInstPrinter::MAI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#af0525fc87f3e2054109908599d21098d">llvm::MCInstPrinter::MCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a41acdb280262403252bc72f6d3f23f7a">llvm::MCInstPrinter::MII</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aaaeadf26b0e3ae38625c5469231bbce6">llvm::MCInstPrinter::MRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printInst() {#a17adee37669068124e468fdc414437a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRInstPrinter::printInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Annot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print the specified <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to the specified <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>


<p><span class="doxyComputerOutput">Address</span> the address of current instruction on most targets, used to print a PC relative immediate as the target address. On targets where a PC relative immediate is relative to the next instruction and the length of a <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> is difficult to measure (e.g. x86), this is the address of the next instruction. If Address is 0, the immediate will be printed.</p>


<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-cpp">AVRInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aab90c946a08959c165433b2c125895ea">llvm::MCInstPrinter::printAnnotation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getMnemonic() {#aa90251ecf3fb4f027b0db7dd862e7862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const char *, uint64_t &gt; llvm::AVRInstPrinter::getMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
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

<p>Returns a pair containing the mnemonic for <span class="doxyComputerOutput">MI</span> and the number of bits left for further processing by printInstruction (generated by tablegen).</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>.</p>

</div>
</div>

### printAliasInstr() {#a34f2c7abaaa7c6ce55b52519725efadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRInstPrinter::printAliasInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>.</p>

</div>
</div>

### printCustomAliasOperand() {#a649c9ca260c7c619e670505816189fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRInstPrinter::printCustomAliasOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, unsigned OpIdx, unsigned PrintMethodIdx, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>.</p>

</div>
</div>

### printInstruction() {#afbdb6244bbfce280d58ca23bc4aff543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRInstPrinter::printInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>.</p>

</div>
</div>

### printMemri() {#ae848fb1ea11a6e88c934170025f51612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRInstPrinter::printMemri (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-cpp">AVRInstPrinter.cpp</a>.</p>

</div>
</div>

### printMemspi() {#a86a94ca501ad7fb19d33f7a7bb70eafe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRInstPrinter::printMemspi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>.</p>

</div>
</div>

### printOperand() {#ad8e7ca7f55247dc202af4a429a6bbd7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRInstPrinter::printOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-cpp">AVRInstPrinter.cpp</a>.</p>

</div>
</div>

### printPCRelImm() {#ab05fea845d450085662934db70cda629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRInstPrinter::printPCRelImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is used to print an immediate value that ends up being encoded as a pc-relative value.</p>

<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-cpp">AVRInstPrinter.cpp</a>.</p>

</div>
</div>

### printPCRelImm() {#a28b4a725949e0a7c9f4921d4b9bd7e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRInstPrinter::printPCRelImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getPrettyRegisterName() {#a764e6f89eb04f23437c3d27b55f448f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AVRInstPrinter::getPrettyRegisterName (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MRI)</td>
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



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-cpp">AVRInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aaaeadf26b0e3ae38625c5469231bbce6">llvm::MCInstPrinter::MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#abb1c33c814741adb78a9ff7f10ff3552">llvm::AVRAsmPrinter::PrintAsmOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a7ddd6d21450d4f2269de2ab98fc8db6b">llvm::AVRAsmPrinter::printOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getRegisterName() {#a4ce213f5ed83234bb7d31e79d46fe18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AVRInstPrinter::getRegisterName (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, unsigned AltIdx=AVR::NoRegAltName)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-cpp">AVRInstPrinter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrinstprinter-h">AVRInstPrinter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
