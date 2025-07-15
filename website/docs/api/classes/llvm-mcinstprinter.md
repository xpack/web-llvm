---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcinstprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCInstPrinter` Class Reference

<p>This is an instance of a target assembly language printer that converts an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to valid target assembly syntax. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCInstPrinter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">llvm/MC/MCInstPrinter.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilinstprinter">DXILInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter">AArch64InstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter">AMDGPUInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arcinstprinter">ARCInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arminstprinter">ARMInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/avrinstprinter">AVRInstPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prints <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> instructions to a textual stream. <a href="/web-llvm/docs/api/classes/llvm/avrinstprinter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter">BPFInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter">CSKYInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter">HexagonInstPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prints bundles as a newline separated list of individual instructions Duplexes are separated by a vertical tab \v character A trailing line includes bundle properties such as endloop0/1. <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter">LanaiInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loongarchinstprinter">LoongArchInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/m68kinstprinter">M68kInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msp430instprinter">MSP430InstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipsinstprinter">MipsInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter">NVPTXInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter">PPCInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/r600instprinter">R600InstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter">RISCVInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter">SPIRVInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter">SparcInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon">SystemZInstPrinterCommon</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/veinstprinter">VEInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter">WebAssemblyInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon">X86InstPrinterCommon</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xcoreinstprinter">XCoreInstPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xtensainstprinter">XtensaInstPrinter</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Markup { <a href="#a4e0302b2f7a78c8741bc07ca7655b859">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0525fc87f3e2054109908599d21098d">MCInstPrinter</a> (const MCAsmInfo &amp;mai, const MCInstrInfo &amp;mii, const MCRegisterInfo &amp;mri)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55e82de41ab06366834cbef13e46ac6d">~MCInstPrinter</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a363576a336d10dec34bf190017ffc68f">applyTargetSpecificCLOption</a> (StringRef Opt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Customize the printer according to a command line option. <a href="#a363576a336d10dec34bf190017ffc68f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3216205cbe92e7720a22058cf2d57676">setCommentStream</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify a stream to emit comments to. <a href="#a3216205cbe92e7720a22058cf2d57676">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3e4ca8fe0215000850b46704e98a95d">getMnemonic</a> (const MCInst &amp;MI) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pair containing the mnemonic for <span class="doxyComputerOutput">MI</span> and the number of bits left for further processing by printInstruction (generated by tablegen). <a href="#ad3e4ca8fe0215000850b46704e98a95d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac297f3bc74269d7fe98eaf7300cba9fa">printInst</a> (const MCInst *MI, uint64_t Address, StringRef Annot, const MCSubtargetInfo &amp;STI, raw_ostream &amp;OS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to the specified <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#ac297f3bc74269d7fe98eaf7300cba9fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c484cd2ea7bf71dad8fd6d223864bb">getOpcodeName</a> (unsigned Opcode) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of the specified opcode enum (e.g. <a href="#a62c484cd2ea7bf71dad8fd6d223864bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ad5f0b1236badc25e0613d3b962997">printRegName</a> (raw_ostream &amp;OS, MCRegister Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the assembler register name. <a href="#ad0ad5f0b1236badc25e0613d3b962997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29057263eeedcc271ae4ec3dfd2353d">getUseMarkup</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93ea46134ac48f273fb38c88c4edde07">setUseMarkup</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2724fcd7769447ccd8459f7fe617a911">getUseColor</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa0680085158cfb0c14163a07ce9515">setUseColor</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/withmarkup">WithMarkup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c158b4d63bb4b8cc91e6cfb0150341">markup</a> (raw_ostream &amp;OS, Markup M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4957778d98023b01a166bc52820cbd4b">getPrintImmHex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5315ee213d2bb70bfb0d581369c8bd47">setPrintImmHex</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae555ad59948ec618ceb8f19d50bd1601">setPrintHexStyle</a> (HexStyle::Style Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0389bf1c38ceac3d1bac5801f726c50b">setPrintBranchImmAsAddress</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e30b2456b2073db0e92ddc5a9d8191">setSymbolizeOperands</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a5ab1597f769f3c0016aaa98f00e27a">setMCInstrAnalysis</a> (const MCInstrAnalysis *Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/format-object">format_object</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab13fc5e3f3dc12bc75fe3d764b832812">formatImm</a> (int64_t Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to print immediates in decimal or hex. <a href="#ab13fc5e3f3dc12bc75fe3d764b832812">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/format-object">format_object</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa062041642a7343958a53aa65564147e">formatDec</a> (int64_t Value) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility functions to print decimal/hexadecimal values. <a href="#aa062041642a7343958a53aa65564147e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/format-object">format_object</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a152eff13caf242abc99d47f5a197a4d9">formatHex</a> (int64_t Value) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/format-object">format_object</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae984d0ef2a117d681fee8e563786c9b8">formatHex</a> (uint64_t Value) const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab90c946a08959c165433b2c125895ea">printAnnotation</a> (raw_ostream &amp;OS, StringRef Annot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function for printing annotations. <a href="#aab90c946a08959c165433b2c125895ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9677047c398a916ab4a5a6fabeb36e7">matchAliasPatterns</a> (const MCInst *MI, const MCSubtargetInfo *STI, const AliasMatchingData &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for matching MCInsts to alias patterns when printing instructions. <a href="#ae9677047c398a916ab4a5a6fabeb36e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f767b1fc960c3a7528055069b0ae97">CommentStream</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A stream that comments can be emitted to if desired. <a href="#a43f767b1fc960c3a7528055069b0ae97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb2bfbafa57a37e627bf1334d349bc6">MAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41acdb280262403252bc72f6d3f23f7a">MII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaeadf26b0e3ae38625c5469231bbce6">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea22be8e7b7e6922680a8369bcf7e3b7">MIA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a1fa89c14ac7b72829c033469ec1fbd">UseMarkup</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we are printing marked up assembly. <a href="#a0a1fa89c14ac7b72829c033469ec1fbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98b5a4fbd0a43ca838ff5cbaef3f2d4">UseColor</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we are printing colored assembly. <a href="#ab98b5a4fbd0a43ca838ff5cbaef3f2d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb00adba3dbd7afd9ee2b432c2edffbb">PrintAliases</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we prefer aliases (e.g. nop) to raw mnemonics. <a href="#afb00adba3dbd7afd9ee2b432c2edffbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23492d33eb76ba85db3600115fed651b">PrintImmHex</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we are printing immediates as hex. <a href="#a23492d33eb76ba85db3600115fed651b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/hexstyle/#a2ff7bb0072f1202f7b06bb426d6ecda0">HexStyle::Style</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9e5aa3371a52ac7283a2c8aa217b73b">PrintHexStyle</a> = <a href="/web-llvm/docs/api/namespaces/llvm/hexstyle/#a2ff7bb0072f1202f7b06bb426d6ecda0aa6e66dd1bf3e5335ef80add25879696d">HexStyle::C</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Which style to use for printing hexadecimal values. <a href="#af9e5aa3371a52ac7283a2c8aa217b73b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acef595ffd1764f8c06f5347db94ee756">PrintBranchImmAsAddress</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, a branch immediate (e.g. <a href="#acef595ffd1764f8c06f5347db94ee756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5151f8e39f6265b5528efed4b516bae7">SymbolizeOperands</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, symbolize branch target and memory reference operands. <a href="#a5151f8e39f6265b5528efed4b516bae7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a1d5efc43dd5669473ac2fe47d5aaf965">raw_ostream::Colors</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715c5d502c8de89fcfdf281ce964d6fe">ColorStack</a> {<a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a1d5efc43dd5669473ac2fe47d5aaf965ab5859d8721cfdc0312b2838b9c985bc1">raw_ostream::Colors::RESET</a>}</td>
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

<p>This is an instance of a target assembly language printer that converts an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to valid target assembly syntax.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Markup {#a4e0302b2f7a78c8741bc07ca7655b859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::MCInstPrinter::Markup </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Immediate<a id="a4e0302b2f7a78c8741bc07ca7655b859a43f6615bbb2c40a5306ff804094420b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="a4e0302b2f7a78c8741bc07ca7655b859a0ba7583639a274c434bbe6ef797115a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Target<a id="a4e0302b2f7a78c8741bc07ca7655b859ac41a31890959544c6523af684561abe5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Memory<a id="a4e0302b2f7a78c8741bc07ca7655b859a4789f23283b3a61f858b641a1bef19a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCInstPrinter() {#af0525fc87f3e2054109908599d21098d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCInstPrinter::MCInstPrinter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; mai, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; mii, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; mri)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>References <a href="#aacb2bfbafa57a37e627bf1334d349bc6">MAI</a>, <a href="#a41acdb280262403252bc72f6d3f23f7a">MII</a> and <a href="#aaaeadf26b0e3ae38625c5469231bbce6">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a25564f331cc6af413258bc158e2f6362">llvm::AArch64InstPrinter::AArch64InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a397ac42c3fc31d8e4417f88a2b35cbc3">llvm::AMDGPUInstPrinter::AMDGPUInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstprinter/#ac6a77c6da8a3bcaffee929785559e587">llvm::ARCInstPrinter::ARCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1d8cbdde05449044b55edeee26798755">llvm::ARMInstPrinter::ARMInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstprinter/#a282bdeaa0bf79bd9eee45e43def355ce">llvm::AVRInstPrinter::AVRInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#adb499bc66580ac40d8c65985d089d6d6">llvm::BPFInstPrinter::BPFInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#af93fcbdf85c3ef5143f88d5efff3bb3d">llvm::CSKYInstPrinter::CSKYInstPrinter</a>, <a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilinstprinter/#a624c93ec59ea0010d96268f38d5a8c7f">anonymous{DirectXMCTargetDesc.cpp}::DXILInstPrinter::DXILInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aee2ab1ee25125b8000a0f73032193e62">llvm::HexagonInstPrinter::HexagonInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#af1711f06e734af794401bf8309d6d108">llvm::LanaiInstPrinter::LanaiInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstprinter/#a7cba96f6c7391513eb03cb4ba308fbf4">llvm::LoongArchInstPrinter::LoongArchInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstprinter/#a1ef2b97460ddb35e458be7e89d8738ea">llvm::M68kInstPrinter::M68kInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstprinter/#a8043a81c90184759a74875bbe3c5d786">llvm::MipsInstPrinter::MipsInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instprinter/#a20821c61885abfa98d1d2428e6c1b822">llvm::MSP430InstPrinter::MSP430InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#add610a318df0bfbeaa50f84cc18da163">llvm::NVPTXInstPrinter::NVPTXInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a064d49758b20b2021f604ad36025e6dc">llvm::PPCInstPrinter::PPCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instprinter/#aa3cb58bc9e02a5ff0d1bb3cbf1c1dbe2">llvm::R600InstPrinter::R600InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ac349c338d1fbab2ed4ff45696879345f">llvm::RISCVInstPrinter::RISCVInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter/#aabbbc72f3731b783b678898bbeeb586e">llvm::SparcInstPrinter::SparcInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a2cbf8de32b8c738c9dca78428dfd133c">llvm::SystemZInstPrinterCommon::SystemZInstPrinterCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstprinter/#a14c25fdcd169bc57542f6d578ff54576">llvm::VEInstPrinter::VEInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#adbaa9608f865bf505ae05f19f510142a">llvm::WebAssemblyInstPrinter::WebAssemblyInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/withmarkup/#a7b81786db9cbd784cdcd4f76bd42faee">llvm::MCInstPrinter::WithMarkup::WithMarkup</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstprinter/#a67610c0d5b63f39c60d4a797c151d11b">llvm::XCoreInstPrinter::XCoreInstPrinter</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensainstprinter/#ab242fc996d13d86bde98459d6cede9aa">llvm::XtensaInstPrinter::XtensaInstPrinter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCInstPrinter() {#a55e82de41ab06366834cbef13e46ac6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstPrinter::~MCInstPrinter ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyTargetSpecificCLOption() {#a363576a336d10dec34bf190017ffc68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCInstPrinter::applyTargetSpecificCLOption (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Opt)</td>
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

<p>Customize the printer according to a command line option.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the option is recognized and applied.</p></dd>
</dl>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>

</div>
</div>

### formatDec() {#aa062041642a7343958a53aa65564147e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">format_object&lt; int64_t &gt; MCInstPrinter::formatDec (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utility functions to print decimal/hexadecimal values.</p>

<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>.</p>


<p>Referenced by <a href="#ab13fc5e3f3dc12bc75fe3d764b832812">formatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a2a7190d0f25b0630d12ca99ad0086b2b">llvm::AMDGPUInstPrinter::printEndpgm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a911ef2be2a24eeb524fd5954a6dff449">llvm::AArch64InstPrinter::printImmSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a0124206da659398599dfb682b6a610cb">llvm::AMDGPUInstPrinter::printSwizzle</a>.</p>

</div>
</div>

### formatHex() {#a152eff13caf242abc99d47f5a197a4d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">format_object&lt; int64_t &gt; MCInstPrinter::formatHex (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexstyle/#a2ff7bb0072f1202f7b06bb426d6ecda0aee14e37b71e28e68ace5e2f6b67042a9">llvm::HexStyle::Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexstyle/#a2ff7bb0072f1202f7b06bb426d6ecda0aa6e66dd1bf3e5335ef80add25879696d">llvm::HexStyle::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp/#a3a84d311db99342342801bebaddc8fd4">needsLeadingZero</a> and <a href="#af9e5aa3371a52ac7283a2c8aa217b73b">PrintHexStyle</a>.</p>


<p>Referenced by <a href="#ab13fc5e3f3dc12bc75fe3d764b832812">formatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#abb152646dc9741817f3ed67493d97ab2">llvm::PPCInstPrinter::printAbsBranchOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a146902cc0e36f3575c2d37719a736fa8">llvm::AArch64InstPrinter::printAdrAdrpLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a046c010a1d8cd5af5616392918c2ab82">llvm::AArch64InstPrinter::printAlignedLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#ac38ede18b7d7e2f613e49545a40c154e">llvm::PPCInstPrinter::printBranchOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ad68b53f833debb000d3141302ac9705f">llvm::RISCVInstPrinter::printBranchOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#ab5f670329da0b2f68a30d42d277033fc">llvm::CSKYInstPrinter::printConstpool</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a934eba438d143e98b9da1e01b91726f3">llvm::CSKYInstPrinter::printCSKYSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a6895016d90c30dc6d1997e420a181f0e">llvm::AMDGPUInstPrinter::printDepCtr</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#a228980581aefb2e57c28d339ff630daa">llvm::NVPTXInstPrinter::printHexu32imm</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a6d700a1da8b98eb35fb0ee4595471c99">llvm::LanaiInstPrinter::printHi16AndImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#aa4b2736d7f1931de837abeb415ab0976">llvm::LanaiInstPrinter::printHi16ImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a911ef2be2a24eeb524fd5954a6dff449">llvm::AArch64InstPrinter::printImmSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#aa4a1e038e705c568fc64c1ed907532d7">llvm::LanaiInstPrinter::printLo16AndImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a4ce0520be1b2212530d4852d7e1036b5">llvm::LanaiInstPrinter::printMemImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a0ba7b11a4b0a5f97e3ed516b5d82ab1b">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a2512f7ec6f3ac947fb398d135929fe60">llvm::CSKYInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#ab6dece7a876e0eec58519cc3c33ecba6">llvm::LanaiInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a20c39b7993054629cfb4f77926f0f51c">llvm::X86InstPrinterCommon::printPCRelImm</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#af71092aeb107ea7f054fac85a28ba146">llvm::AArch64InstPrinter::printSVELogicalImm</a>.</p>

</div>
</div>

### formatHex() {#ae984d0ef2a117d681fee8e563786c9b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">format_object&lt; uint64_t &gt; MCInstPrinter::formatHex (uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexstyle/#a2ff7bb0072f1202f7b06bb426d6ecda0aee14e37b71e28e68ace5e2f6b67042a9">llvm::HexStyle::Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexstyle/#a2ff7bb0072f1202f7b06bb426d6ecda0aa6e66dd1bf3e5335ef80add25879696d">llvm::HexStyle::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp/#a3a84d311db99342342801bebaddc8fd4">needsLeadingZero</a> and <a href="#af9e5aa3371a52ac7283a2c8aa217b73b">PrintHexStyle</a>.</p>

</div>
</div>

### formatImm() {#ab13fc5e3f3dc12bc75fe3d764b832812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">format_object&lt; int64_t &gt; llvm::MCInstPrinter::formatImm (int64_t Value)</td>
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

<p>Utility function to print immediates in decimal or hex.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>References <a href="#aa062041642a7343958a53aa65564147e">formatDec</a>, <a href="#a152eff13caf242abc99d47f5a197a4d9">formatHex</a> and <a href="#a23492d33eb76ba85db3600115fed651b">PrintImmHex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af03a90b8cd1b7df88a120d1e87993dec">llvm::ARMInstPrinter::printAddrModeImm12Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a8f28c9e40efb457286cf0bac91a9f987">llvm::AArch64InstPrinter::printAddSubImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a046c010a1d8cd5af5616392918c2ab82">llvm::AArch64InstPrinter::printAlignedLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a0572b63082c110b3a4b2a2b9c8d31d0f">llvm::AArch64InstPrinter::printAMIndexedWB</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ad68b53f833debb000d3141302ac9705f">llvm::RISCVInstPrinter::printBranchOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#a07b2f49008fa1aee47028452e3609212">llvm::BPFInstPrinter::printBrTargetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a7cb007e8951999f6e302446fc2789754">llvm::AArch64InstPrinter::printBTIHintOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a321c1863f0f95dd6d0908504f4bc4b2b">llvm::RISCVInstPrinter::printCSRSystemRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a032220cf9055d0c2171f09806b2250bf">llvm::AArch64InstPrinter::printImm</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#a8ab9dbe63d2b01ab39359cfb5bd5319e">llvm::BPFInstPrinter::printImm64Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#adf3c1940dd03ebf286a0311bd556ccf9">llvm::AArch64InstPrinter::printImm8OptLsl</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a605f81e4f3e978f3185c55119252aaf0">llvm::ARMInstPrinter::printImmPlusOneOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab33bdf5eb88f0d16d50681f65f217a69">llvm::AArch64InstPrinter::printImmRangeScale</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a82e386d940e4aa23f93b42a961e2c1a7">llvm::AArch64InstPrinter::printImmScale</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a75d3a2429c144498e74b899dbb33506e">llvm::X86ATTInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a066020a10f4b28e5fd81783c3fa5b1de">llvm::X86IntelInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#acbf2e86fc2f834cd174befe788226f89">llvm::BPFInstPrinter::printMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab7d33433deb752463cdbaa7a587eb969">llvm::X86ATTInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#af25f10e8eea4608eddac083e4117e41e">llvm::X86IntelInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a0ba7b11a4b0a5f97e3ed516b5d82ab1b">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a14a78c5a53b12d5137e5e5e3af8d4390">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#ace0292b8a0ab3255644b2acf607d6439">llvm::BPFInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#a74044d477e5ae4d2a331370db9bf8576">llvm::HexagonInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#aee685621f62068066a69335b0d3c0e20">llvm::NVPTXInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#aa3bc43f980c1b1c92a3e059d7656e1fb">llvm::RISCVInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a27c4a87f88c20ac4710c4e092dadb6fb">llvm::SPIRVInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a71c593e9a81209bbab000361729a3a56">llvm::X86ATTInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#abf71b07ec943c7c93490dc9f4ab105f1">llvm::X86IntelInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a20c39b7993054629cfb4f77926f0f51c">llvm::X86InstPrinterCommon::printPCRelImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a6dac4e979d4dbda85519ef1362309b8a">llvm::AArch64InstPrinter::printPHintOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a1574059a04c27b4f6566b7d4054afc33">llvm::AArch64InstPrinter::printPrefetchOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a33734af4dfb32357ecfae0ba9e219ab9">llvm::AArch64InstPrinter::printPSBHintOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a649e3ac07d737cdd0e85b27ad84b82d8">llvm::AArch64InstPrinter::printRangePrefetchAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a5988d3e81357c76416249bb6f13deded">llvm::AArch64InstPrinter::printRPRFMOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a85e08980d5a5de4514bb034b567cabf2">llvm::AArch64InstPrinter::printSImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ac41795a4e1926f0a0173c8f985e92eef">llvm::AArch64InstPrinter::printSVEPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a2cdc4ea363a73fc772d36d9fb5911adb">llvm::AArch64InstPrinter::printSystemPStateField</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a00207d77e26f99de17095b10b6374f3b">llvm::ARMInstPrinter::printT2AddrModeImm0_1020s4Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af181e7c7bbb781086e7b9a9da4d828f5">llvm::ARMInstPrinter::printThumbAddrModeImm5SOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a4480dd8734b70a12632d73053873d011">llvm::ARMInstPrinter::printThumbLdrLabelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#adc3221baf568e47bcb7b3a01b378cfbf">llvm::ARMInstPrinter::printThumbS4ImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#abb247fb381ee428adcc845962a5ec78c">llvm::ARMInstPrinter::printThumbSRImm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#af447e80e370c0025f51d603359e6d0f5">llvm::X86ATTInstPrinter::printU8Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a4a5b9d6ff6dfe2ebc2b052c68156829d">llvm::X86IntelInstPrinter::printU8Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a1ebaad303ddd83b5203b3548e43c06d1">llvm::AArch64InstPrinter::printUImm12Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ab41df3f24906d7ac103c09ccc17a58ec">llvm::RISCVInstPrinter::printVTypeI</a>.</p>

</div>
</div>

### getMnemonic() {#ad3e4ca8fe0215000850b46704e98a95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::pair&lt; const char *, uint64_t &gt; llvm::MCInstPrinter::getMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pair containing the mnemonic for <span class="doxyComputerOutput">MI</span> and the number of bits left for further processing by printInstruction (generated by tablegen).</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getOpcodeName() {#a62c484cd2ea7bf71dad8fd6d223864bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MCInstPrinter::getOpcodeName (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the name of the specified opcode enum (e.g.</p>


<p>getOpcodeName - Return the name of the specified opcode enum (e.g.</p>


<p>"MOV32ri") or empty if we can't resolve it.</p>


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>Reference <a href="#a41acdb280262403252bc72f6d3f23f7a">MII</a>.</p>

</div>
</div>

### getPrintImmHex() {#a4957778d98023b01a166bc52820cbd4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstPrinter::getPrintImmHex ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#a23492d33eb76ba85db3600115fed651b">PrintImmHex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a911ef2be2a24eeb524fd5954a6dff449">llvm::AArch64InstPrinter::printImmSVE</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>.</p>

</div>
</div>

### getUseColor() {#a2724fcd7769447ccd8459f7fe617a911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstPrinter::getUseColor ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#ab98b5a4fbd0a43ca838ff5cbaef3f2d4">UseColor</a>.</p>


<p>Referenced by <a href="#a00c158b4d63bb4b8cc91e6cfb0150341">markup</a>.</p>

</div>
</div>

### getUseMarkup() {#ac29057263eeedcc271ae4ec3dfd2353d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstPrinter::getUseMarkup ()</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#a0a1fa89c14ac7b72829c033469ec1fbd">UseMarkup</a>.</p>


<p>Referenced by <a href="#a00c158b4d63bb4b8cc91e6cfb0150341">markup</a> and <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a0ba7b11a4b0a5f97e3ed516b5d82ab1b">llvm::ARMInstPrinter::printOperand</a>.</p>

</div>
</div>

### markup() {#a00c158b4d63bb4b8cc91e6cfb0150341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstPrinter::WithMarkup MCInstPrinter::markup (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="#a4e0302b2f7a78c8741bc07ca7655b859">Markup</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>References <a href="#a2724fcd7769447ccd8459f7fe617a911">getUseColor</a> and <a href="#ac29057263eeedcc271ae4ec3dfd2353d">getUseMarkup</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ac5739a68abf105b4fee5ae4ed66b83c2">llvm::ARMInstPrinter::printAddrMode2OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a27ad0652b6099f891ab3329efe1ece6f">llvm::ARMInstPrinter::printAddrMode3OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#afdc2a24a421c911f502c96f9822ca0de">llvm::ARMInstPrinter::printAddrMode5FP16Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a5ce1d55f5ea53662c66eec4d08b34ea1">llvm::ARMInstPrinter::printAddrMode5Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ad24ada064f2ce683e24da38479d0cd40">llvm::ARMInstPrinter::printAddrMode6Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a12758349533cc0bfa0fe29af6dfae950">llvm::ARMInstPrinter::printAddrMode7Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af03a90b8cd1b7df88a120d1e87993dec">llvm::ARMInstPrinter::printAddrModeImm12Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a4b5beafa5bc7ad72ede3c7523405929c">llvm::ARMInstPrinter::printAddrModeTBB</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af4bbbe1e2e2c4ab428f0c64b8e7f2b85">llvm::ARMInstPrinter::printAddrModeTBH</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a8f28c9e40efb457286cf0bac91a9f987">llvm::AArch64InstPrinter::printAddSubImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a146902cc0e36f3575c2d37719a736fa8">llvm::AArch64InstPrinter::printAdrAdrpLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aed2da08c30700cc19a7bd01eaf6b3f40">llvm::ARMInstPrinter::printAdrLabelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a046c010a1d8cd5af5616392918c2ab82">llvm::AArch64InstPrinter::printAlignedLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1e026f7100c90a0382ba7c7290cefaa8">llvm::ARMInstPrinter::printAM2PreOrOffsetIndexOp</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af16346148e47bd920deff1ae577e52fc">llvm::ARMInstPrinter::printAM3PreOrOffsetIndexOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a0572b63082c110b3a4b2a2b9c8d31d0f">llvm::AArch64InstPrinter::printAMIndexedWB</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a7f89beec12829953872f4f813d8fbb5d">llvm::AArch64InstPrinter::printArithExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a2a541f27b19d9ccf89e9200500f98c1d">llvm::AArch64InstPrinter::printBarriernXSOption</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#af459165965e978f1f992b7cdf6d230f0">llvm::AArch64InstPrinter::printBarrierOption</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a760d31d471929fb5632301c778fc4169">llvm::ARMInstPrinter::printBitfieldInvMaskImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ad68b53f833debb000d3141302ac9705f">llvm::RISCVInstPrinter::printBranchOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a7cb007e8951999f6e302446fc2789754">llvm::AArch64InstPrinter::printBTIHintOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a96e0b63477002e6e283a7c6e51bdabb4">llvm::AArch64InstPrinter::printComplexRotationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a321c1863f0f95dd6d0908504f4bc4b2b">llvm::RISCVInstPrinter::printCSRSystemRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#afca8e1c634ec0bf5ce9c1f15863f80c6">llvm::X86ATTInstPrinter::printDstIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#adbd383ca44ab0c856157a6b7e8cea87e">llvm::X86IntelInstPrinter::printDstIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#af21fef5229d19a1eb6a38a8587829b38">llvm::AArch64InstPrinter::printExactFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1d7464b29c6dd600dfdcae7b3a1f5d73">llvm::ARMInstPrinter::printFBits16</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a7d2bd1a695994b76edf3ef8f90e1eb1e">llvm::ARMInstPrinter::printFBits32</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a761e8a0a85cb668fdc8a026441fac635">llvm::AArch64InstPrinter::printFPImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aa012d06e92b0a7a5310d8639fc198096">llvm::ARMInstPrinter::printFPImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a930e8675c9ef99ced183aea742952d8a">llvm::RISCVInstPrinter::printFPImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a032220cf9055d0c2171f09806b2250bf">llvm::AArch64InstPrinter::printImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#adf3c1940dd03ebf286a0311bd556ccf9">llvm::AArch64InstPrinter::printImm8OptLsl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ae7404397b7b8599e273f338f7b0730d4">llvm::AArch64InstPrinter::printImmHex</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a605f81e4f3e978f3185c55119252aaf0">llvm::ARMInstPrinter::printImmPlusOneOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a82e386d940e4aa23f93b42a961e2c1a7">llvm::AArch64InstPrinter::printImmScale</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a911ef2be2a24eeb524fd5954a6dff449">llvm::AArch64InstPrinter::printImmSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64appleinstprinter/#a0af3a1b2f3995f8f8dfa849a6cb2f0a5">llvm::AArch64AppleInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a97d0066eae87ce228a58774409c88425">llvm::ARMInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab86bea1cb49f64b7eb22195b6653e317">llvm::AArch64InstPrinter::printLogicalImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a767125d6b773e1457126e182a553f35d">llvm::AArch64InstPrinter::printMemExtendImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a75d3a2429c144498e74b899dbb33506e">llvm::X86ATTInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a066020a10f4b28e5fd81783c3fa5b1de">llvm::X86IntelInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab7d33433deb752463cdbaa7a587eb969">llvm::X86ATTInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#af25f10e8eea4608eddac083e4117e41e">llvm::X86IntelInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#abc5aa54b2e18ae6a32233d406f5e004d">llvm::ARMInstPrinter::printModImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a3cad68cdc642615cc733a25472dce3f5">llvm::ARMInstPrinter::printMveAddrModeRQOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a14a78c5a53b12d5137e5e5e3af8d4390">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#aee685621f62068066a69335b0d3c0e20">llvm::NVPTXInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#aa3bc43f980c1b1c92a3e059d7656e1fb">llvm::RISCVInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a60c14b6310b40e44fed1f341556c55ac">llvm::SystemZInstPrinterCommon::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a71c593e9a81209bbab000361729a3a56">llvm::X86ATTInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#abf71b07ec943c7c93490dc9f4ab105f1">llvm::X86IntelInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a20c39b7993054629cfb4f77926f0f51c">llvm::X86InstPrinterCommon::printPCRelImm</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#aba7a5e60523b2a3eb825f0ee302ae6fc">llvm::SystemZInstPrinterCommon::printPCRelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a6dac4e979d4dbda85519ef1362309b8a">llvm::AArch64InstPrinter::printPHintOp</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a0be5d588e9fe970c8c635596bfbc3b71">llvm::ARMInstPrinter::printPKHASRShiftImm</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ab8decb50f88e325cbe1aabd937719f71">llvm::ARMInstPrinter::printPKHLSLShiftImm</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a5479df62fe36346eb1455d6d8caa4f93">llvm::ARMInstPrinter::printPostIdxImm8Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a77912110733b7a8e37d0b7f6febece3d">llvm::ARMInstPrinter::printPostIdxImm8s4Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ac94de400799b4c99639b0895f5f401cd">llvm::AArch64InstPrinter::printPostIncOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a1574059a04c27b4f6566b7d4054afc33">llvm::AArch64InstPrinter::printPrefetchOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a33734af4dfb32357ecfae0ba9e219ab9">llvm::AArch64InstPrinter::printPSBHintOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#aa0bbfadb3263a307cbd6663184fa04bb">llvm::AArch64InstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ad5e6e3a15dc8b7a484317f7ba99ab170">llvm::AArch64InstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a7cb99a3e5ff7ee74943bd6ff584cb997">llvm::ARMInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstprinter/#a4b850cbcb67aa7a498a57cb99d850609">llvm::MipsInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#aa945d70974561557f6b99e33430892cc">llvm::RISCVInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ac59222883330e9cdcebf2c39dc9d6d7d">llvm::X86ATTInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a1b7206eebaedc6e86456963982f0c559">llvm::X86IntelInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a81efcd8f3f43f3d722b01d713c7b1c35">llvm::ARMInstPrinter::printRotImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a2ce2becffb8924f6a1d76eb62e2c3902">llvm::AArch64InstPrinter::printShifter</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aae52b826a0f416709e59324ffff18b60">llvm::ARMInstPrinter::printShiftImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a489e944ed336ebeb25656c01848e48fa">llvm::AArch64InstPrinter::printSIMDType10Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a85e08980d5a5de4514bb034b567cabf2">llvm::AArch64InstPrinter::printSImm</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a332da3e8113c5366a77cd9273788cb88">llvm::SystemZInstPrinterCommon::printSImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a39e74a473e64ff067645b5ecf62f8f48">llvm::X86ATTInstPrinter::printSrcIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#aae867cd8d466a2caadce0091ae119c64">llvm::X86IntelInstPrinter::printSrcIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ad10e372bdad63fb7b26aef3ea2e33fc9">llvm::RISCVInstPrinter::printStackAdj</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a3d6a40e590c9628a4622ba38046b01a5">llvm::X86ATTInstPrinter::printSTiRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#af71092aeb107ea7f054fac85a28ba146">llvm::AArch64InstPrinter::printSVELogicalImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ac41795a4e1926f0a0173c8f985e92eef">llvm::AArch64InstPrinter::printSVEPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a00207d77e26f99de17095b10b6374f3b">llvm::ARMInstPrinter::printT2AddrModeImm0_1020s4Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aa218ebbedccda344468600864f879dc6">llvm::ARMInstPrinter::printT2AddrModeImm8OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a2eab063ac2c7a90d992fcad57a541994">llvm::ARMInstPrinter::printT2AddrModeImm8Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a6c099d2050d7e56a522aaee0fe5420ee">llvm::ARMInstPrinter::printT2AddrModeImm8s4OffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ab2e9628e70fe2fef1984adaf73772f0e">llvm::ARMInstPrinter::printT2AddrModeImm8s4Operand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aae087d0df6f0c28ffa9ed6db015b14ba">llvm::ARMInstPrinter::printT2AddrModeSoRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af181e7c7bbb781086e7b9a9da4d828f5">llvm::ARMInstPrinter::printThumbAddrModeImm5SOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aaa2e8abbd7147f87614a5d81d0a9c62c">llvm::ARMInstPrinter::printThumbAddrModeRROperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a4480dd8734b70a12632d73053873d011">llvm::ARMInstPrinter::printThumbLdrLabelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#adc3221baf568e47bcb7b3a01b378cfbf">llvm::ARMInstPrinter::printThumbS4ImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#abb247fb381ee428adcc845962a5ec78c">llvm::ARMInstPrinter::printThumbSRImm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#af447e80e370c0025f51d603359e6d0f5">llvm::X86ATTInstPrinter::printU8Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a4a5b9d6ff6dfe2ebc2b052c68156829d">llvm::X86IntelInstPrinter::printU8Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a1ebaad303ddd83b5203b3548e43c06d1">llvm::AArch64InstPrinter::printUImm12Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a05c6b3aa6140926f41b12c7e14c12a43">llvm::SystemZInstPrinterCommon::printUImmOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#ae905b708b2b1677ea7ce953ed987cf23">llvm::ARMInstPrinter::printVMOVModImmOperand</a>.</p>

</div>
</div>

### printInst() {#ac297f3bc74269d7fe98eaf7300cba9fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCInstPrinter::printInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Annot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the specified <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to the specified <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>


<p><span class="doxyComputerOutput">Address</span> the address of current instruction on most targets, used to print a PC relative immediate as the target address. On targets where a PC relative immediate is relative to the next instruction and the length of a <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> is difficult to measure (e.g. x86), this is the address of the next instruction. If Address is 0, the immediate will be printed.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetasmstreamer/#ad17bf01008144e718fa39ffa0ef84733">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetAsmStreamer::prettyPrintAsm</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#a50530e571361f88c35f9f32b52577f91">llvm::MCTargetStreamer::prettyPrintAsm</a>.</p>

</div>
</div>

### printRegName() {#ad0ad5f0b1236badc25e0613d3b962997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCInstPrinter::printRegName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Print the assembler register name.</p>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a52148b72ea5562b0ec318da1b42314a3">llvm::X86InstPrinterCommon::printTILEPair</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a5f7ea952a6f77a70e64f2803c0824c44">llvm::X86InstPrinterCommon::printVKPair</a>.</p>

</div>
</div>

### setCommentStream() {#a3216205cbe92e7720a22058cf2d57676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInstPrinter::setCommentStream (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Specify a stream to emit comments to.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#a43f767b1fc960c3a7528055069b0ae97">CommentStream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### setMCInstrAnalysis() {#a0a5ab1597f769f3c0016aaa98f00e27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInstPrinter::setMCInstrAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a> * Value)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#aea22be8e7b7e6922680a8369bcf7e3b7">MIA</a>.</p>

</div>
</div>

### setPrintBranchImmAsAddress() {#a0389bf1c38ceac3d1bac5801f726c50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInstPrinter::setPrintBranchImmAsAddress (bool Value)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#acef595ffd1764f8c06f5347db94ee756">PrintBranchImmAsAddress</a>.</p>

</div>
</div>

### setPrintHexStyle() {#ae555ad59948ec618ceb8f19d50bd1601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInstPrinter::setPrintHexStyle (<a href="/web-llvm/docs/api/namespaces/llvm/hexstyle/#a2ff7bb0072f1202f7b06bb426d6ecda0">HexStyle::Style</a> Value)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#af9e5aa3371a52ac7283a2c8aa217b73b">PrintHexStyle</a>.</p>

</div>
</div>

### setPrintImmHex() {#a5315ee213d2bb70bfb0d581369c8bd47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInstPrinter::setPrintImmHex (bool Value)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#a23492d33eb76ba85db3600115fed651b">PrintImmHex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad1c77f840dadc1ffb03432c9e688e4c6">llvm::logicalview::LVBinaryReader::loadGenericTargetInfo</a>.</p>

</div>
</div>

### setSymbolizeOperands() {#a49e30b2456b2073db0e92ddc5a9d8191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInstPrinter::setSymbolizeOperands (bool Value)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#a5151f8e39f6265b5528efed4b516bae7">SymbolizeOperands</a>.</p>

</div>
</div>

### setUseColor() {#a3aa0680085158cfb0c14163a07ce9515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInstPrinter::setUseColor (bool Value)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#ab98b5a4fbd0a43ca838ff5cbaef3f2d4">UseColor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a>.</p>

</div>
</div>

### setUseMarkup() {#a93ea46134ac48f273fb38c88c4edde07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCInstPrinter::setUseMarkup (bool Value)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Reference <a href="#a0a1fa89c14ac7b72829c033469ec1fbd">UseMarkup</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### matchAliasPatterns() {#ae9677047c398a916ab4a5a6fabeb36e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * MCInstPrinter::matchAliasPatterns (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aliasmatchingdata">AliasMatchingData</a> &amp; M)</td>
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

<p>Helper for matching MCInsts to alias patterns when printing instructions.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp/#aad70fb95e1855cf69dfefcf98e2d5e8b">matchAliasCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#aaaeadf26b0e3ae38625c5469231bbce6">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>

</div>
</div>

### printAnnotation() {#aab90c946a08959c165433b2c125895ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCInstPrinter::printAnnotation (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Annot)</td>
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

<p>Utility function for printing annotations.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a>.</p>


<p>References <a href="#a43f767b1fc960c3a7528055069b0ae97">CommentStream</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#aacb2bfbafa57a37e627bf1334d349bc6">MAI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64appleinstprinter/#a0af3a1b2f3995f8f8dfa849a6cb2f0a5">llvm::AArch64AppleInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#aa35cac4eccfa6cf751d2389d1bb969fc">llvm::AMDGPUInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstprinter/#a408e7ba3edd7f4ef0bdc6ee5999b1667">llvm::ARCInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a97d0066eae87ce228a58774409c88425">llvm::ARMInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstprinter/#a17adee37669068124e468fdc414437a7">llvm::AVRInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#aab4b975dde6d877eaafcbdee9bfd78ea">llvm::BPFInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a15fb262046aed9fd07026656600c2187">llvm::CSKYInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a798be7ce342102ee46d3e6bfa12abf56">llvm::LanaiInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstprinter/#a2a9fa4d5c4f3319f2d80d5a7f257c886">llvm::LoongArchInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstprinter/#a60f3d9ba6ae89122cad2c9e32f3ba55c">llvm::M68kInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstprinter/#a68a4bd6bf466ad6ca9d76acefb598023">llvm::MipsInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instprinter/#a4b9395b6a61d77caa70fb582b6cf651a">llvm::MSP430InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#ad8b1b771eb418dde21dc5f500a78b3d1">llvm::NVPTXInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a6cd305cb01305d4c101633f77bf6e4bc">llvm::PPCInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instprinter/#ac3edd96bf7aeb895c06dcf467cf1b06f">llvm::R600InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a889daf2539fe759734a84d036429f3bc">llvm::RISCVInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter/#a15077d2f8790410dd346ecefb9dc750e">llvm::SparcInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a538b1435d732f0d2620cea4849af80aa">llvm::SPIRVInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzgnuinstprinter/#a2d02d8ed72899b45a00c99ed2826d55b">llvm::SystemZGNUInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhlasminstprinter/#a8e762c0500c96d4684914b4c326e3fe8">llvm::SystemZHLASMInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstprinter/#abfd0ba3cc44ada35e6bbf8a9725ac518">llvm::VEInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#a7d7a0c71edec56b48ee2f53ccb92c58e">llvm::WebAssemblyInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ac2345780b2997c9882b808140bce11fa">llvm::X86ATTInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#ae9718621d043eee9b485afd90cd062b6">llvm::X86IntelInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstprinter/#acdec566fe6048a0230f51f82c4a7f88f">llvm::XCoreInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstprinter/#a0aa86a498b3f4382b0440dad553486a5">llvm::XtensaInstPrinter::printInst</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a649e3ac07d737cdd0e85b27ad84b82d8">llvm::AArch64InstPrinter::printRangePrefetchAlias</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ColorStack {#a715c5d502c8de89fcfdf281ce964d6fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;raw_ostream::Colors, 4&gt; llvm::MCInstPrinter::ColorStack {<a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a1d5efc43dd5669473ac2fe47d5aaf965ab5859d8721cfdc0312b2838b9c985bc1">raw_ostream::Colors::RESET</a>}</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>

</div>
</div>

### CommentStream {#a43f767b1fc960c3a7528055069b0ae97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream* llvm::MCInstPrinter::CommentStream = nullptr</td>
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

<p>A stream that comments can be emitted to if desired.</p>


<p>Each comment must end with a newline. This will be null if verbose assembly emission is disabled.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a8f28c9e40efb457286cf0bac91a9f987">llvm::AArch64InstPrinter::printAddSubImm</a>, <a href="#aab90c946a08959c165433b2c125895ea">printAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a911ef2be2a24eeb524fd5954a6dff449">llvm::AArch64InstPrinter::printImmSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#a7d7a0c71edec56b48ee2f53ccb92c58e">llvm::WebAssemblyInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ac2345780b2997c9882b808140bce11fa">llvm::X86ATTInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#ae9718621d043eee9b485afd90cd062b6">llvm::X86IntelInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a0ba7b11a4b0a5f97e3ed516b5d82ab1b">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a71c593e9a81209bbab000361729a3a56">llvm::X86ATTInstPrinter::printOperand</a> and <a href="#a3216205cbe92e7720a22058cf2d57676">setCommentStream</a>.</p>

</div>
</div>

### MAI {#aacb2bfbafa57a37e627bf1334d349bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo&amp; llvm::MCInstPrinter::MAI</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64appleinstprinter/#a2ef9160ac2bb99fa3a3cefe2b5d35f55">llvm::AArch64AppleInstPrinter::AArch64AppleInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a25564f331cc6af413258bc158e2f6362">llvm::AArch64InstPrinter::AArch64InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a397ac42c3fc31d8e4417f88a2b35cbc3">llvm::AMDGPUInstPrinter::AMDGPUInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstprinter/#ac6a77c6da8a3bcaffee929785559e587">llvm::ARCInstPrinter::ARCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1d8cbdde05449044b55edeee26798755">llvm::ARMInstPrinter::ARMInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstprinter/#a282bdeaa0bf79bd9eee45e43def355ce">llvm::AVRInstPrinter::AVRInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#adb499bc66580ac40d8c65985d089d6d6">llvm::BPFInstPrinter::BPFInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#af93fcbdf85c3ef5143f88d5efff3bb3d">llvm::CSKYInstPrinter::CSKYInstPrinter</a>, <a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilinstprinter/#a624c93ec59ea0010d96268f38d5a8c7f">anonymous{DirectXMCTargetDesc.cpp}::DXILInstPrinter::DXILInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#a465da4c4c97df14ca7f6cb45235236c5">llvm::HexagonInstPrinter::getMAI</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzgnuinstprinter/#af4ada4aaf8d8e055ea1487353f62f49f">llvm::SystemZGNUInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhlasminstprinter/#a097cfc2f2cf32716decb074e2cd68bed">llvm::SystemZHLASMInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aee2ab1ee25125b8000a0f73032193e62">llvm::HexagonInstPrinter::HexagonInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#af1711f06e734af794401bf8309d6d108">llvm::LanaiInstPrinter::LanaiInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstprinter/#a7cba96f6c7391513eb03cb4ba308fbf4">llvm::LoongArchInstPrinter::LoongArchInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstprinter/#a1ef2b97460ddb35e458be7e89d8738ea">llvm::M68kInstPrinter::M68kInstPrinter</a>, <a href="#af0525fc87f3e2054109908599d21098d">MCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstprinter/#a8043a81c90184759a74875bbe3c5d786">llvm::MipsInstPrinter::MipsInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instprinter/#a20821c61885abfa98d1d2428e6c1b822">llvm::MSP430InstPrinter::MSP430InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#add610a318df0bfbeaa50f84cc18da163">llvm::NVPTXInstPrinter::NVPTXInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a064d49758b20b2021f604ad36025e6dc">llvm::PPCInstPrinter::PPCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#ad4b08e8c79d635454e9a610088a9a68e">llvm::SystemZInstPrinterCommon::printAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a8f28c9e40efb457286cf0bac91a9f987">llvm::AArch64InstPrinter::printAddSubImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a146902cc0e36f3575c2d37719a736fa8">llvm::AArch64InstPrinter::printAdrAdrpLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#aed2da08c30700cc19a7bd01eaf6b3f40">llvm::ARMInstPrinter::printAdrLabelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a046c010a1d8cd5af5616392918c2ab82">llvm::AArch64InstPrinter::printAlignedLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a0572b63082c110b3a4b2a2b9c8d31d0f">llvm::AArch64InstPrinter::printAMIndexedWB</a>, <a href="#aab90c946a08959c165433b2c125895ea">printAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#ab23dffcc8f344a96400be2b5e9aff13f">llvm::SystemZInstPrinterCommon::printBDAddrOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a5e4656b9a299733e5c48c1064bd018eb">llvm::SystemZInstPrinterCommon::printBDLAddrOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#ae19b3cfc089f875fa8e03986936de3c6">llvm::SystemZInstPrinterCommon::printBDRAddrOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a25db403e16e89d7e9da94f00c6d80c70">llvm::SystemZInstPrinterCommon::printBDVAddrOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a1ad481403c012763f777c67c6394f07a">llvm::SystemZInstPrinterCommon::printBDXAddrOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#ab5f670329da0b2f68a30d42d277033fc">llvm::CSKYInstPrinter::printConstpool</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a488900b8c4238199da9f7f1f70e035ad">llvm::CSKYInstPrinter::printDataSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a84f6f60161c89280faa55085b4cf5b67">llvm::SystemZInstPrinterCommon::printFormattedRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a6d700a1da8b98eb35fb0ee4595471c99">llvm::LanaiInstPrinter::printHi16AndImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#aa4b2736d7f1931de837abeb415ab0976">llvm::LanaiInstPrinter::printHi16ImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a6cd305cb01305d4c101633f77bf6e4bc">llvm::PPCInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instprinter/#a7ae6d7ad35a919a88fc5a9daa781e1a3">llvm::R600InstPrinter::printLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#aa4a1e038e705c568fc64c1ed907532d7">llvm::LanaiInstPrinter::printLo16AndImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a8c23ba9c65c5c8674d96004c5ed796c6">llvm::SystemZInstPrinterCommon::printLXAAddrOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a4ce0520be1b2212530d4852d7e1036b5">llvm::LanaiInstPrinter::printMemImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a75d3a2429c144498e74b899dbb33506e">llvm::X86ATTInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a066020a10f4b28e5fd81783c3fa5b1de">llvm::X86IntelInstPrinter::printMemOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab7d33433deb752463cdbaa7a587eb969">llvm::X86ATTInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#af25f10e8eea4608eddac083e4117e41e">llvm::X86IntelInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a64951e8d7bcbf195d938d8a46b10f296">llvm::LanaiInstPrinter::printMemRiOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a7175783d7bc00499ba7c333ffe2698f9">llvm::LanaiInstPrinter::printMemSplsOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a80be2f780a4e9aa7a80781980e2944a3">llvm::AArch64InstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a14a78c5a53b12d5137e5e5e3af8d4390">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a2512f7ec6f3ac947fb398d135929fe60">llvm::CSKYInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#ab6dece7a876e0eec58519cc3c33ecba6">llvm::LanaiInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#aee685621f62068066a69335b0d3c0e20">llvm::NVPTXInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a5f2fd1af8259132b7f1d061dc1446077">llvm::PPCInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instprinter/#a572fc6c9209a834b1de293468ccc6691">llvm::R600InstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#aa3bc43f980c1b1c92a3e059d7656e1fb">llvm::RISCVInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter/#a1fbde6ef1b980af08ff6d9de6cdc1f7b">llvm::SparcInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#aa253a64ab9acbb178d594bfacd73d2da">llvm::SystemZInstPrinterCommon::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a60c14b6310b40e44fed1f341556c55ac">llvm::SystemZInstPrinterCommon::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstprinter/#a568643b76a6a9fb21ee23f7394de92fe">llvm::VEInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#aa43bb54e111c5b87edb58a368175a352">llvm::WebAssemblyInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a71c593e9a81209bbab000361729a3a56">llvm::X86ATTInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#abf71b07ec943c7c93490dc9f4ab105f1">llvm::X86IntelInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a20c39b7993054629cfb4f77926f0f51c">llvm::X86InstPrinterCommon::printPCRelImm</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#aba7a5e60523b2a3eb825f0ee302ae6fc">llvm::SystemZInstPrinterCommon::printPCRelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a7ae1b284807c7eaed159d4da9201bc4f">llvm::SystemZInstPrinterCommon::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a4480dd8734b70a12632d73053873d011">llvm::ARMInstPrinter::printThumbLdrLabelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#ada3d2a129f8e8076337a902e8077adcf">llvm::PPCInstPrinter::printTLSCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a4a5b9d6ff6dfe2ebc2b052c68156829d">llvm::X86IntelInstPrinter::printU8Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a1ebaad303ddd83b5203b3548e43c06d1">llvm::AArch64InstPrinter::printUImm12Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instprinter/#aa3cb58bc9e02a5ff0d1bb3cbf1c1dbe2">llvm::R600InstPrinter::R600InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ac349c338d1fbab2ed4ff45696879345f">llvm::RISCVInstPrinter::RISCVInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter/#aabbbc72f3731b783b678898bbeeb586e">llvm::SparcInstPrinter::SparcInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzgnuinstprinter/#aad48d1622d271c8d38455f6f9e3d221c">llvm::SystemZGNUInstPrinter::SystemZGNUInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhlasminstprinter/#a282e8ecd6309b1cf639e416252b9e004">llvm::SystemZHLASMInstPrinter::SystemZHLASMInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a2cbf8de32b8c738c9dca78428dfd133c">llvm::SystemZInstPrinterCommon::SystemZInstPrinterCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstprinter/#a14c25fdcd169bc57542f6d578ff54576">llvm::VEInstPrinter::VEInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#adbaa9608f865bf505ae05f19f510142a">llvm::WebAssemblyInstPrinter::WebAssemblyInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab0eab1043ec13eef281ed50af6d26ad1">llvm::X86ATTInstPrinter::X86ATTInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#acbeb180e9a279e317e3283cd9a5148b6">llvm::X86IntelInstPrinter::X86IntelInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstprinter/#a67610c0d5b63f39c60d4a797c151d11b">llvm::XCoreInstPrinter::XCoreInstPrinter</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensainstprinter/#ab242fc996d13d86bde98459d6cede9aa">llvm::XtensaInstPrinter::XtensaInstPrinter</a>.</p>

</div>
</div>

### MIA {#aea22be8e7b7e6922680a8369bcf7e3b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrAnalysis* llvm::MCInstPrinter::MIA = nullptr</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab7d33433deb752463cdbaa7a587eb969">llvm::X86ATTInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#af25f10e8eea4608eddac083e4117e41e">llvm::X86IntelInstPrinter::printMemReference</a> and <a href="#a0a5ab1597f769f3c0016aaa98f00e27a">setMCInstrAnalysis</a>.</p>

</div>
</div>

### MII {#a41acdb280262403252bc72f6d3f23f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrInfo&amp; llvm::MCInstPrinter::MII</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64appleinstprinter/#a2ef9160ac2bb99fa3a3cefe2b5d35f55">llvm::AArch64AppleInstPrinter::AArch64AppleInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a25564f331cc6af413258bc158e2f6362">llvm::AArch64InstPrinter::AArch64InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a397ac42c3fc31d8e4417f88a2b35cbc3">llvm::AMDGPUInstPrinter::AMDGPUInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstprinter/#ac6a77c6da8a3bcaffee929785559e587">llvm::ARCInstPrinter::ARCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1d8cbdde05449044b55edeee26798755">llvm::ARMInstPrinter::ARMInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstprinter/#a282bdeaa0bf79bd9eee45e43def355ce">llvm::AVRInstPrinter::AVRInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#adb499bc66580ac40d8c65985d089d6d6">llvm::BPFInstPrinter::BPFInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#af93fcbdf85c3ef5143f88d5efff3bb3d">llvm::CSKYInstPrinter::CSKYInstPrinter</a>, <a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilinstprinter/#a624c93ec59ea0010d96268f38d5a8c7f">anonymous{DirectXMCTargetDesc.cpp}::DXILInstPrinter::DXILInstPrinter</a>, <a href="#a62c484cd2ea7bf71dad8fd6d223864bb">getOpcodeName</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#af1711f06e734af794401bf8309d6d108">llvm::LanaiInstPrinter::LanaiInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstprinter/#a7cba96f6c7391513eb03cb4ba308fbf4">llvm::LoongArchInstPrinter::LoongArchInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstprinter/#a1ef2b97460ddb35e458be7e89d8738ea">llvm::M68kInstPrinter::M68kInstPrinter</a>, <a href="#af0525fc87f3e2054109908599d21098d">MCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstprinter/#a8043a81c90184759a74875bbe3c5d786">llvm::MipsInstPrinter::MipsInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instprinter/#a20821c61885abfa98d1d2428e6c1b822">llvm::MSP430InstPrinter::MSP430InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#add610a318df0bfbeaa50f84cc18da163">llvm::NVPTXInstPrinter::NVPTXInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a064d49758b20b2021f604ad36025e6dc">llvm::PPCInstPrinter::PPCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a538b1435d732f0d2620cea4849af80aa">llvm::SPIRVInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#a7d7a0c71edec56b48ee2f53ccb92c58e">llvm::WebAssemblyInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ac2345780b2997c9882b808140bce11fa">llvm::X86ATTInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#ae9718621d043eee9b485afd90cd062b6">llvm::X86IntelInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a9e01cbc62f1eb3379712051ded643013">llvm::X86InstPrinterCommon::printInstFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#ab9572d51415fe9448360292077d55435">llvm::SPIRVInstPrinter::printOpDecorate</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a0ba7b11a4b0a5f97e3ed516b5d82ab1b">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a2512f7ec6f3ac947fb398d135929fe60">llvm::CSKYInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a5f2fd1af8259132b7f1d061dc1446077">llvm::PPCInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#aa43bb54e111c5b87edb58a368175a352">llvm::WebAssemblyInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a5ae494d9fb7b6ef87715f462677938b9">llvm::SPIRVInstPrinter::printOpExtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a95c5146c0c6b3cca75af04e9494ffed9">llvm::X86ATTInstPrinter::printVecCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#a173bb9d9d14eaa55322a702f85808a43">llvm::X86IntelInstPrinter::printVecCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instprinter/#aa3cb58bc9e02a5ff0d1bb3cbf1c1dbe2">llvm::R600InstPrinter::R600InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ac349c338d1fbab2ed4ff45696879345f">llvm::RISCVInstPrinter::RISCVInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter/#aabbbc72f3731b783b678898bbeeb586e">llvm::SparcInstPrinter::SparcInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzgnuinstprinter/#aad48d1622d271c8d38455f6f9e3d221c">llvm::SystemZGNUInstPrinter::SystemZGNUInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhlasminstprinter/#a282e8ecd6309b1cf639e416252b9e004">llvm::SystemZHLASMInstPrinter::SystemZHLASMInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a2cbf8de32b8c738c9dca78428dfd133c">llvm::SystemZInstPrinterCommon::SystemZInstPrinterCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstprinter/#a14c25fdcd169bc57542f6d578ff54576">llvm::VEInstPrinter::VEInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#adbaa9608f865bf505ae05f19f510142a">llvm::WebAssemblyInstPrinter::WebAssemblyInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab0eab1043ec13eef281ed50af6d26ad1">llvm::X86ATTInstPrinter::X86ATTInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#acbeb180e9a279e317e3283cd9a5148b6">llvm::X86IntelInstPrinter::X86IntelInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstprinter/#a67610c0d5b63f39c60d4a797c151d11b">llvm::XCoreInstPrinter::XCoreInstPrinter</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensainstprinter/#ab242fc996d13d86bde98459d6cede9aa">llvm::XtensaInstPrinter::XtensaInstPrinter</a>.</p>

</div>
</div>

### MRI {#aaaeadf26b0e3ae38625c5469231bbce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo&amp; llvm::MCInstPrinter::MRI</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64appleinstprinter/#a2ef9160ac2bb99fa3a3cefe2b5d35f55">llvm::AArch64AppleInstPrinter::AArch64AppleInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a25564f331cc6af413258bc158e2f6362">llvm::AArch64InstPrinter::AArch64InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a397ac42c3fc31d8e4417f88a2b35cbc3">llvm::AMDGPUInstPrinter::AMDGPUInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstprinter/#ac6a77c6da8a3bcaffee929785559e587">llvm::ARCInstPrinter::ARCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1d8cbdde05449044b55edeee26798755">llvm::ARMInstPrinter::ARMInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstprinter/#a282bdeaa0bf79bd9eee45e43def355ce">llvm::AVRInstPrinter::AVRInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#adb499bc66580ac40d8c65985d089d6d6">llvm::BPFInstPrinter::BPFInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#af93fcbdf85c3ef5143f88d5efff3bb3d">llvm::CSKYInstPrinter::CSKYInstPrinter</a>, <a href="/web-llvm/docs/api/classes/anonymous-directxmctargetdesc-cpp-/dxilinstprinter/#a624c93ec59ea0010d96268f38d5a8c7f">anonymous{DirectXMCTargetDesc.cpp}::DXILInstPrinter::DXILInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstprinter/#a764e6f89eb04f23437c3d27b55f448f5">llvm::AVRInstPrinter::getPrettyRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a2d1579b3e66d752d5d8ecae54574c9c8">llvm::AMDGPUInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aee2ab1ee25125b8000a0f73032193e62">llvm::HexagonInstPrinter::HexagonInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#af1711f06e734af794401bf8309d6d108">llvm::LanaiInstPrinter::LanaiInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstprinter/#a7cba96f6c7391513eb03cb4ba308fbf4">llvm::LoongArchInstPrinter::LoongArchInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstprinter/#a1ef2b97460ddb35e458be7e89d8738ea">llvm::M68kInstPrinter::M68kInstPrinter</a>, <a href="#ae9677047c398a916ab4a5a6fabeb36e7">matchAliasPatterns</a>, <a href="#af0525fc87f3e2054109908599d21098d">MCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstprinter/#a8043a81c90184759a74875bbe3c5d786">llvm::MipsInstPrinter::MipsInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instprinter/#a20821c61885abfa98d1d2428e6c1b822">llvm::MSP430InstPrinter::MSP430InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#add610a318df0bfbeaa50f84cc18da163">llvm::NVPTXInstPrinter::NVPTXInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a064d49758b20b2021f604ad36025e6dc">llvm::PPCInstPrinter::PPCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a3c2a374b81cf111251b53fcb78582ccf">llvm::AArch64InstPrinter::printGPR64x8</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a6aea91057ff37bf4d641db81fdc3fa28">llvm::ARMInstPrinter::printGPRPairOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a6123d45e40ad2f8d535de67d6cb3b000">llvm::AArch64InstPrinter::printGPRSeqPairsClassOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a97d0066eae87ce228a58774409c88425">llvm::ARMInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a0458691bad5c02f5f7cd418c61775a08">llvm::ARMInstPrinter::printMVEVectorList</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a5f2fd1af8259132b7f1d061dc1446077">llvm::PPCInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a649e3ac07d737cdd0e85b27ad84b82d8">llvm::AArch64InstPrinter::printRangePrefetchAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1464b3517e7960c2e8ac10981946b9fb">llvm::ARMInstPrinter::printRegisterList</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstprinter/#a28eb6ce8fefa02f3982efabe39094b09">llvm::VEInstPrinter::printRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a8b42aa365301378d930039cef44b8d70">llvm::AMDGPUInstPrinter::printRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a5d6cefc91e6dcb85e959ccab7374bf97">llvm::AArch64InstPrinter::printVectorList</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a1c97be706043c998b45f5de701acdc11">llvm::ARMInstPrinter::printVectorListTwo</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a08111f1704baf5f9d793827db513d18f">llvm::ARMInstPrinter::printVectorListTwoAllLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a28d0adc1872b53812e1e24ecfb5c268c">llvm::ARMInstPrinter::printVectorListTwoSpaced</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a4760360f7f08e6a6cf66b13f948904cd">llvm::ARMInstPrinter::printVectorListTwoSpacedAllLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instprinter/#aa3cb58bc9e02a5ff0d1bb3cbf1c1dbe2">llvm::R600InstPrinter::R600InstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ac349c338d1fbab2ed4ff45696879345f">llvm::RISCVInstPrinter::RISCVInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter/#aabbbc72f3731b783b678898bbeeb586e">llvm::SparcInstPrinter::SparcInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzgnuinstprinter/#aad48d1622d271c8d38455f6f9e3d221c">llvm::SystemZGNUInstPrinter::SystemZGNUInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhlasminstprinter/#a282e8ecd6309b1cf639e416252b9e004">llvm::SystemZHLASMInstPrinter::SystemZHLASMInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a2cbf8de32b8c738c9dca78428dfd133c">llvm::SystemZInstPrinterCommon::SystemZInstPrinterCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstprinter/#a14c25fdcd169bc57542f6d578ff54576">llvm::VEInstPrinter::VEInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#adbaa9608f865bf505ae05f19f510142a">llvm::WebAssemblyInstPrinter::WebAssemblyInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab0eab1043ec13eef281ed50af6d26ad1">llvm::X86ATTInstPrinter::X86ATTInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#acbeb180e9a279e317e3283cd9a5148b6">llvm::X86IntelInstPrinter::X86IntelInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstprinter/#a67610c0d5b63f39c60d4a797c151d11b">llvm::XCoreInstPrinter::XCoreInstPrinter</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensainstprinter/#ab242fc996d13d86bde98459d6cede9aa">llvm::XtensaInstPrinter::XtensaInstPrinter</a>.</p>

</div>
</div>

### PrintAliases {#afb00adba3dbd7afd9ee2b432c2edffbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstPrinter::PrintAliases = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

<p>True if we prefer aliases (e.g. nop) to raw mnemonics.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a5887f158990cbe1ec54ac0e8afc1fa6b">llvm::AArch64InstPrinter::applyTargetSpecificCLOption</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a59cc4673fdcaa6a2dbd8fe5df66431a2">llvm::RISCVInstPrinter::applyTargetSpecificCLOption</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a8899a9d651df9e263ab389f5ed6ac5bb">llvm::RISCVInstPrinter::printFRMArg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ab4e79ecca1f6c9c8b0dcf317d32a4523">llvm::AArch64InstPrinter::printInst</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a889daf2539fe759734a84d036429f3bc">llvm::RISCVInstPrinter::printInst</a>.</p>

</div>
</div>

### PrintBranchImmAsAddress {#acef595ffd1764f8c06f5347db94ee756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstPrinter::PrintBranchImmAsAddress = false</td>
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

<p>If true, a branch immediate (e.g.</p>


<p>bl 4) will be printed as a hexadecimal address (e.g. bl 0x20004). This is useful for a stream disassembler (llvm-objdump -d).</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a146902cc0e36f3575c2d37719a736fa8">llvm::AArch64InstPrinter::printAdrAdrpLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a046c010a1d8cd5af5616392918c2ab82">llvm::AArch64InstPrinter::printAlignedLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#ac38ede18b7d7e2f613e49545a40c154e">llvm::PPCInstPrinter::printBranchOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#ad68b53f833debb000d3141302ac9705f">llvm::RISCVInstPrinter::printBranchOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#ab5f670329da0b2f68a30d42d277033fc">llvm::CSKYInstPrinter::printConstpool</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a934eba438d143e98b9da1e01b91726f3">llvm::CSKYInstPrinter::printCSKYSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a252fe2d0cd8a010c2d522d3dbaf3f207">llvm::CSKYInstPrinter::printFPRRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a0ba7b11a4b0a5f97e3ed516b5d82ab1b">llvm::ARMInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a2512f7ec6f3ac947fb398d135929fe60">llvm::CSKYInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a20c39b7993054629cfb4f77926f0f51c">llvm::X86InstPrinterCommon::printPCRelImm</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#af24f84362d7592d49f2a70c08bd410a1">llvm::CSKYInstPrinter::printRegName</a> and <a href="#a0389bf1c38ceac3d1bac5801f726c50b">setPrintBranchImmAsAddress</a>.</p>

</div>
</div>

### PrintHexStyle {#af9e5aa3371a52ac7283a2c8aa217b73b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexStyle::Style llvm::MCInstPrinter::PrintHexStyle = <a href="/web-llvm/docs/api/namespaces/llvm/hexstyle/#a2ff7bb0072f1202f7b06bb426d6ecda0aa6e66dd1bf3e5335ef80add25879696d">HexStyle::C</a></td>
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

<p>Which style to use for printing hexadecimal values.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="#a152eff13caf242abc99d47f5a197a4d9">formatHex</a>, <a href="#ae984d0ef2a117d681fee8e563786c9b8">formatHex</a> and <a href="#ae555ad59948ec618ceb8f19d50bd1601">setPrintHexStyle</a>.</p>

</div>
</div>

### PrintImmHex {#a23492d33eb76ba85db3600115fed651b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstPrinter::PrintImmHex = false</td>
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

<p>True if we are printing immediates as hex.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="#ab13fc5e3f3dc12bc75fe3d764b832812">formatImm</a>, <a href="#a4957778d98023b01a166bc52820cbd4b">getPrintImmHex</a> and <a href="#a5315ee213d2bb70bfb0d581369c8bd47">setPrintImmHex</a>.</p>

</div>
</div>

### SymbolizeOperands {#a5151f8e39f6265b5528efed4b516bae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstPrinter::SymbolizeOperands = false</td>
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

<p>If true, symbolize branch target and memory reference operands.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#ab7d33433deb752463cdbaa7a587eb969">llvm::X86ATTInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#af25f10e8eea4608eddac083e4117e41e">llvm::X86IntelInstPrinter::printMemReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a20c39b7993054629cfb4f77926f0f51c">llvm::X86InstPrinterCommon::printPCRelImm</a> and <a href="#a49e30b2456b2073db0e92ddc5a9d8191">setSymbolizeOperands</a>.</p>

</div>
</div>

### UseColor {#ab98b5a4fbd0a43ca838ff5cbaef3f2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstPrinter::UseColor = false</td>
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

<p>True if we are printing colored assembly.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="#a2724fcd7769447ccd8459f7fe617a911">getUseColor</a> and <a href="#a3aa0680085158cfb0c14163a07ce9515">setUseColor</a>.</p>

</div>
</div>

### UseMarkup {#a0a1fa89c14ac7b72829c033469ec1fbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCInstPrinter::UseMarkup = false</td>
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

<p>True if we are printing marked up assembly.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a>.</p>


<p>Referenced by <a href="#ac29057263eeedcc271ae4ec3dfd2353d">getUseMarkup</a> and <a href="#a93ea46134ac48f273fb38c88c4edde07">setUseMarkup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstprinter-h">MCInstPrinter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp">MCInstPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
