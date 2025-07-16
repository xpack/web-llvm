---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/x86attinstprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86ATTInstPrinter` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::X86ATTInstPrinter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">Target/X86/MCTargetDesc/X86ATTInstPrinter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0eab1043ec13eef281ed50af6d26ad1">X86ATTInstPrinter</a> (const MCAsmInfo &amp;MAI, const MCInstrInfo &amp;MII, const MCRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac59222883330e9cdcebf2c39dc9d6d7d">printRegName</a> (raw_ostream &amp;OS, MCRegister Reg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the assembler register name. <a href="#ac59222883330e9cdcebf2c39dc9d6d7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2345780b2997c9882b808140bce11fa">printInst</a> (const MCInst *MI, uint64_t Address, StringRef Annot, const MCSubtargetInfo &amp;STI, raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> to the specified <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#ac2345780b2997c9882b808140bce11fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c5146c0c6b3cca75af04e9494ffed9">printVecCompareInstr</a> (const MCInst *MI, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52013639bb1117bda85b6dbacf57e552">printAliasInstr</a> (const MCInst *MI, uint64_t Address, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1415c1a1f3a20f7d23e4f708fbda6a">printCustomAliasOperand</a> (const MCInst *MI, uint64_t Address, unsigned OpIdx, unsigned PrintMethodIdx, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b4ba41526e4e0091362fd791052fd9">getMnemonic</a> (const MCInst &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pair containing the mnemonic for <span class="doxyComputerOutput">MI</span> and the number of bits left for further processing by printInstruction (generated by tablegen). <a href="#a91b4ba41526e4e0091362fd791052fd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3365146d61c32b59efb93eb14cdc1e52">printInstruction</a> (const MCInst *MI, uint64_t Address, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71c593e9a81209bbab000361729a3a56">printOperand</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;OS) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a> (const MCInst *MI, unsigned Op, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d3a2429c144498e74b899dbb33506e">printMemOffset</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e74a473e64ff067645b5ecf62f8f48">printSrcIdx</a> (const MCInst *MI, unsigned Op, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afca8e1c634ec0bf5ce9c1f15863f80c6">printDstIdx</a> (const MCInst *MI, unsigned Op, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af447e80e370c0025f51d603359e6d0f5">printU8Imm</a> (const MCInst *MI, unsigned Op, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d6a40e590c9628a4622ba38046b01a5">printSTiRegOperand</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2bec3b01f50aa6cb5e45efbb6b6233">printbytemem</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced1614ef3538c93fb5f687dd799ac37">printwordmem</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e20022bba42c7f1aeae39a0eaf60dcd">printdwordmem</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d17c9ad99eaefc5cbe96e7c64ca4565">printqwordmem</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace07e6f8bc2061848d1462845c634fa6">printxmmwordmem</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2d4709b78f5f17721c846e117004d9c">printymmwordmem</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54a3b0dab2282abe65dade324dc140d">printzmmwordmem</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a556990fc31bfdadcb8bc534d65a52126">printtbytemem</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f6c21a6dd64d52be2c7c79fe3700ed">printSrcIdx8</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f1dc7d9235fe7adcde8db01c8aac9f">printSrcIdx16</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dbdb858b4a84ec98aa3da3863fdbb04">printSrcIdx32</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1502fbbf4229308815d6166449483dbc">printSrcIdx64</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418357d4eca8659540e469cf97b7dcd5">printDstIdx8</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd8e07a8802f61aca5c8dce970b68c6a">printDstIdx16</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6bdd753817bff0ba331063ce0707974">printDstIdx32</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b6a097879cf10980e5e1ed4b103247c">printDstIdx64</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e2dd7423046e42445c62d0a966c2cb">printMemOffs8</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa92be8a0ef224078337d653e4d8fa5">printMemOffs16</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96cf13c5ff76603c87daba760f1d0305">printMemOffs32</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af4de6c943bf66204e899e21d0a6c4c">printMemOffs64</a> (const MCInst *MI, unsigned OpNo, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5049609de0ca38a1c2469a30f0f4032f">HasCustomInstComment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124a43d72f8680a64fdd7132d29b1775">getRegisterName</a> (MCRegister Reg)</td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86ATTInstPrinter() {#ab0eab1043ec13eef281ed50af6d26ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::X86ATTInstPrinter::X86ATTInstPrinter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aacb2bfbafa57a37e627bf1334d349bc6">llvm::MCInstPrinter::MAI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a41acdb280262403252bc72f6d3f23f7a">llvm::MCInstPrinter::MII</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aaaeadf26b0e3ae38625c5469231bbce6">llvm::MCInstPrinter::MRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMnemonic() {#a91b4ba41526e4e0091362fd791052fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const char *, uint64_t &gt; llvm::X86ATTInstPrinter::getMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
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

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### printAliasInstr() {#a52013639bb1117bda85b6dbacf57e552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86ATTInstPrinter::printAliasInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ac2345780b2997c9882b808140bce11fa">printInst</a>.</p>

</div>
</div>

### printbytemem() {#aed2bec3b01f50aa6cb5e45efbb6b6233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printbytemem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a>.</p>

</div>
</div>

### printCustomAliasOperand() {#abb1415c1a1f3a20f7d23e4f708fbda6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printCustomAliasOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, unsigned OpIdx, unsigned PrintMethodIdx, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### printDstIdx() {#afca8e1c634ec0bf5ce9c1f15863f80c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86ATTInstPrinter::printDstIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a00c158b4d63bb4b8cc91e6cfb0150341">llvm::MCInstPrinter::markup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a4789f23283b3a61f858b641a1bef19a3">llvm::MCInstPrinter::Memory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a71c593e9a81209bbab000361729a3a56">printOperand</a>.</p>


<p>Referenced by <a href="#abd8e07a8802f61aca5c8dce970b68c6a">printDstIdx16</a>, <a href="#ab6bdd753817bff0ba331063ce0707974">printDstIdx32</a>, <a href="#a6b6a097879cf10980e5e1ed4b103247c">printDstIdx64</a> and <a href="#a418357d4eca8659540e469cf97b7dcd5">printDstIdx8</a>.</p>

</div>
</div>

### printDstIdx16() {#abd8e07a8802f61aca5c8dce970b68c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printDstIdx16 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#afca8e1c634ec0bf5ce9c1f15863f80c6">printDstIdx</a>.</p>

</div>
</div>

### printDstIdx32() {#ab6bdd753817bff0ba331063ce0707974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printDstIdx32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#afca8e1c634ec0bf5ce9c1f15863f80c6">printDstIdx</a>.</p>

</div>
</div>

### printDstIdx64() {#a6b6a097879cf10980e5e1ed4b103247c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printDstIdx64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#afca8e1c634ec0bf5ce9c1f15863f80c6">printDstIdx</a>.</p>

</div>
</div>

### printDstIdx8() {#a418357d4eca8659540e469cf97b7dcd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printDstIdx8 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#afca8e1c634ec0bf5ce9c1f15863f80c6">printDstIdx</a>.</p>

</div>
</div>

### printdwordmem() {#a5e20022bba42c7f1aeae39a0eaf60dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printdwordmem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a>.</p>


<p>Referenced by <a href="#a95c5146c0c6b3cca75af04e9494ffed9">printVecCompareInstr</a>.</p>

</div>
</div>

### printInst() {#ac2345780b2997c9882b808140bce11fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86ATTInstPrinter::printInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Annot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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


<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a43f767b1fc960c3a7528055069b0ae97">llvm::MCInstPrinter::CommentStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a41acdb280262403252bc72f6d3f23f7a">llvm::MCInstPrinter::MII</a>, <a href="#a52013639bb1117bda85b6dbacf57e552">printAliasInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aab90c946a08959c165433b2c125895ea">llvm::MCInstPrinter::printAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a9e01cbc62f1eb3379712051ded643013">llvm::X86InstPrinterCommon::printInstFlags</a>, <a href="#a3365146d61c32b59efb93eb14cdc1e52">printInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a20c39b7993054629cfb4f77926f0f51c">llvm::X86InstPrinterCommon::printPCRelImm</a> and <a href="#a95c5146c0c6b3cca75af04e9494ffed9">printVecCompareInstr</a>.</p>

</div>
</div>

### printInstruction() {#a3365146d61c32b59efb93eb14cdc1e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ac2345780b2997c9882b808140bce11fa">printInst</a>.</p>

</div>
</div>

### printMemOffs16() {#aeaa92be8a0ef224078337d653e4d8fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printMemOffs16 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a75d3a2429c144498e74b899dbb33506e">printMemOffset</a>.</p>

</div>
</div>

### printMemOffs32() {#a96cf13c5ff76603c87daba760f1d0305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printMemOffs32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a75d3a2429c144498e74b899dbb33506e">printMemOffset</a>.</p>

</div>
</div>

### printMemOffs64() {#a1af4de6c943bf66204e899e21d0a6c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printMemOffs64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a75d3a2429c144498e74b899dbb33506e">printMemOffset</a>.</p>

</div>
</div>

### printMemOffs8() {#a01e2dd7423046e42445c62d0a966c2cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printMemOffs8 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a75d3a2429c144498e74b899dbb33506e">printMemOffset</a>.</p>

</div>
</div>

### printMemOffset() {#a75d3a2429c144498e74b899dbb33506e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86ATTInstPrinter::printMemOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ab13fc5e3f3dc12bc75fe3d764b832812">llvm::MCInstPrinter::formatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aacb2bfbafa57a37e627bf1334d349bc6">llvm::MCInstPrinter::MAI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a00c158b4d63bb4b8cc91e6cfb0150341">llvm::MCInstPrinter::markup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a4789f23283b3a61f858b641a1bef19a3">llvm::MCInstPrinter::Memory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a292c9f3aa1e6836768480e9dd65b3f29">llvm::X86InstPrinterCommon::printOptionalSegReg</a>.</p>


<p>Referenced by <a href="#aeaa92be8a0ef224078337d653e4d8fa5">printMemOffs16</a>, <a href="#a96cf13c5ff76603c87daba760f1d0305">printMemOffs32</a>, <a href="#a1af4de6c943bf66204e899e21d0a6c4c">printMemOffs64</a> and <a href="#a01e2dd7423046e42445c62d0a966c2cb">printMemOffs8</a>.</p>

</div>
</div>

### printMemReference() {#ab7d33433deb752463cdbaa7a587eb969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86ATTInstPrinter::printMemReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84a319f0e99a1ac9396659683d2638d4f45">llvm::X86::AddrBaseReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84a93474770cf1401679ba37e1833632e58">llvm::X86::AddrDisp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84aba7ebe0e28a2c1c4c14343f549c01462">llvm::X86::AddrIndexReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84a353f20f0404222671129b3d31f7ffc7b">llvm::X86::AddrScaleAmt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84a8fed367c46e025e4269e9725a94391b6">llvm::X86::AddrSegmentReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ab13fc5e3f3dc12bc75fe3d764b832812">llvm::MCInstPrinter::formatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a43f6615bbb2c40a5306ff804094420b1">llvm::MCInstPrinter::Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aacb2bfbafa57a37e627bf1334d349bc6">llvm::MCInstPrinter::MAI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a00c158b4d63bb4b8cc91e6cfb0150341">llvm::MCInstPrinter::markup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a4789f23283b3a61f858b641a1bef19a3">llvm::MCInstPrinter::Memory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aea22be8e7b7e6922680a8369bcf7e3b7">llvm::MCInstPrinter::MIA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae3067756d9df7843be2d25cedab37da4">llvm::MCExpr::print</a>, <a href="#a71c593e9a81209bbab000361729a3a56">printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a292c9f3aa1e6836768480e9dd65b3f29">llvm::X86InstPrinterCommon::printOptionalSegReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a5151f8e39f6265b5528efed4b516bae7">llvm::MCInstPrinter::SymbolizeOperands</a>.</p>


<p>Referenced by <a href="#aed2bec3b01f50aa6cb5e45efbb6b6233">printbytemem</a>, <a href="#a5e20022bba42c7f1aeae39a0eaf60dcd">printdwordmem</a>, <a href="#a7d17c9ad99eaefc5cbe96e7c64ca4565">printqwordmem</a>, <a href="#a556990fc31bfdadcb8bc534d65a52126">printtbytemem</a>, <a href="#aced1614ef3538c93fb5f687dd799ac37">printwordmem</a>, <a href="#ace07e6f8bc2061848d1462845c634fa6">printxmmwordmem</a>, <a href="#aa2d4709b78f5f17721c846e117004d9c">printymmwordmem</a> and <a href="#af54a3b0dab2282abe65dade324dc140d">printzmmwordmem</a>.</p>

</div>
</div>

### printOperand() {#a71c593e9a81209bbab000361729a3a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86ATTInstPrinter::printOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a43f767b1fc960c3a7528055069b0ae97">llvm::MCInstPrinter::CommentStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ab13fc5e3f3dc12bc75fe3d764b832812">llvm::MCInstPrinter::formatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a43f6615bbb2c40a5306ff804094420b1">llvm::MCInstPrinter::Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#aacb2bfbafa57a37e627bf1334d349bc6">llvm::MCInstPrinter::MAI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a00c158b4d63bb4b8cc91e6cfb0150341">llvm::MCInstPrinter::markup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ac59222883330e9cdcebf2c39dc9d6d7d">printRegName</a>.</p>


<p>Referenced by <a href="#afca8e1c634ec0bf5ce9c1f15863f80c6">printDstIdx</a>, <a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a>, <a href="#a39e74a473e64ff067645b5ecf62f8f48">printSrcIdx</a>, <a href="#af447e80e370c0025f51d603359e6d0f5">printU8Imm</a> and <a href="#a95c5146c0c6b3cca75af04e9494ffed9">printVecCompareInstr</a>.</p>

</div>
</div>

### printqwordmem() {#a7d17c9ad99eaefc5cbe96e7c64ca4565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printqwordmem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a>.</p>


<p>Referenced by <a href="#a95c5146c0c6b3cca75af04e9494ffed9">printVecCompareInstr</a>.</p>

</div>
</div>

### printRegName() {#ac59222883330e9cdcebf2c39dc9d6d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86ATTInstPrinter::printRegName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="#a124a43d72f8680a64fdd7132d29b1775">getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a00c158b4d63bb4b8cc91e6cfb0150341">llvm::MCInstPrinter::markup</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a0ba7583639a274c434bbe6ef797115a4">llvm::MCInstPrinter::Register</a>.</p>


<p>Referenced by <a href="#a71c593e9a81209bbab000361729a3a56">printOperand</a> and <a href="#a3d6a40e590c9628a4622ba38046b01a5">printSTiRegOperand</a>.</p>

</div>
</div>

### printSrcIdx() {#a39e74a473e64ff067645b5ecf62f8f48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86ATTInstPrinter::printSrcIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a00c158b4d63bb4b8cc91e6cfb0150341">llvm::MCInstPrinter::markup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a4789f23283b3a61f858b641a1bef19a3">llvm::MCInstPrinter::Memory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a71c593e9a81209bbab000361729a3a56">printOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a292c9f3aa1e6836768480e9dd65b3f29">llvm::X86InstPrinterCommon::printOptionalSegReg</a>.</p>


<p>Referenced by <a href="#a68f1dc7d9235fe7adcde8db01c8aac9f">printSrcIdx16</a>, <a href="#a0dbdb858b4a84ec98aa3da3863fdbb04">printSrcIdx32</a>, <a href="#a1502fbbf4229308815d6166449483dbc">printSrcIdx64</a> and <a href="#a27f6c21a6dd64d52be2c7c79fe3700ed">printSrcIdx8</a>.</p>

</div>
</div>

### printSrcIdx16() {#a68f1dc7d9235fe7adcde8db01c8aac9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printSrcIdx16 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a39e74a473e64ff067645b5ecf62f8f48">printSrcIdx</a>.</p>

</div>
</div>

### printSrcIdx32() {#a0dbdb858b4a84ec98aa3da3863fdbb04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printSrcIdx32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a39e74a473e64ff067645b5ecf62f8f48">printSrcIdx</a>.</p>

</div>
</div>

### printSrcIdx64() {#a1502fbbf4229308815d6166449483dbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printSrcIdx64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a39e74a473e64ff067645b5ecf62f8f48">printSrcIdx</a>.</p>

</div>
</div>

### printSrcIdx8() {#a27f6c21a6dd64d52be2c7c79fe3700ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printSrcIdx8 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a39e74a473e64ff067645b5ecf62f8f48">printSrcIdx</a>.</p>

</div>
</div>

### printSTiRegOperand() {#a3d6a40e590c9628a4622ba38046b01a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86ATTInstPrinter::printSTiRegOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a00c158b4d63bb4b8cc91e6cfb0150341">llvm::MCInstPrinter::markup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac59222883330e9cdcebf2c39dc9d6d7d">printRegName</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a0ba7583639a274c434bbe6ef797115a4">llvm::MCInstPrinter::Register</a>.</p>

</div>
</div>

### printtbytemem() {#a556990fc31bfdadcb8bc534d65a52126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printtbytemem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a>.</p>

</div>
</div>

### printU8Imm() {#af447e80e370c0025f51d603359e6d0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86ATTInstPrinter::printU8Imm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ab13fc5e3f3dc12bc75fe3d764b832812">llvm::MCInstPrinter::formatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a4e0302b2f7a78c8741bc07ca7655b859a43f6615bbb2c40a5306ff804094420b1">llvm::MCInstPrinter::Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a00c158b4d63bb4b8cc91e6cfb0150341">llvm::MCInstPrinter::markup</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a71c593e9a81209bbab000361729a3a56">printOperand</a>.</p>

</div>
</div>

### printVecCompareInstr() {#a95c5146c0c6b3cca75af04e9494ffed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86ATTInstPrinter::printVecCompareInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea4a0b5ce031c6c73572f1006babe65b47">llvm::X86II::EVEX_B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabe6298d9ba729db7fa5c2149de1b21ed">llvm::X86II::EVEX_K</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea1b5f21917d273c19ffaa38e025d6b4af">llvm::X86II::EVEX_L2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3ae6529df02b311ddca2a678a0bfaf64">llvm::X86II::FormMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a41acdb280262403252bc72f6d3f23f7a">llvm::MCInstPrinter::MII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabeb3b7e6c5b8fde8b53c453b462f0aae">llvm::X86II::MRMSrcMem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea17bada293123ac2f889d0dece275027d">llvm::X86II::OpMapMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eafd3ef015d11de7b9cf6d25507774a0a9">llvm::X86II::OpPrefixMask</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a902794cd9596644cb58a3b0e1c2c83e5">llvm::X86InstPrinterCommon::printCMPMnemonic</a>, <a href="#a5e20022bba42c7f1aeae39a0eaf60dcd">printdwordmem</a>, <a href="#a71c593e9a81209bbab000361729a3a56">printOperand</a>, <a href="#a7d17c9ad99eaefc5cbe96e7c64ca4565">printqwordmem</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#aaa9b3bf5010285a0253e8a2983257bed">llvm::X86InstPrinterCommon::printVPCMPMnemonic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a30a73113a2c39001cdc62b6acff57543">llvm::X86InstPrinterCommon::printVPCOMMnemonic</a>, <a href="#aced1614ef3538c93fb5f687dd799ac37">printwordmem</a>, <a href="#ace07e6f8bc2061848d1462845c634fa6">printxmmwordmem</a>, <a href="#aa2d4709b78f5f17721c846e117004d9c">printymmwordmem</a>, <a href="#af54a3b0dab2282abe65dade324dc140d">printzmmwordmem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea12e1b321252ff4c31f9a6b563d8d18b7">llvm::X86II::REX_W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ead254d64df655ab661c3c3330610385af">llvm::X86II::TA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea05c399774dc40c2b03d5ab492e1006c6">llvm::X86II::VEX_L</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea5309cc29d36de4eb6d05bae85de58f78">llvm::X86II::XD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ead9268658d1be801bae20dba1f1378dcf">llvm::X86II::XS</a>.</p>


<p>Referenced by <a href="#ac2345780b2997c9882b808140bce11fa">printInst</a>.</p>

</div>
</div>

### printwordmem() {#aced1614ef3538c93fb5f687dd799ac37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printwordmem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a>.</p>


<p>Referenced by <a href="#a95c5146c0c6b3cca75af04e9494ffed9">printVecCompareInstr</a>.</p>

</div>
</div>

### printxmmwordmem() {#ace07e6f8bc2061848d1462845c634fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printxmmwordmem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a>.</p>


<p>Referenced by <a href="#a95c5146c0c6b3cca75af04e9494ffed9">printVecCompareInstr</a>.</p>

</div>
</div>

### printymmwordmem() {#aa2d4709b78f5f17721c846e117004d9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printymmwordmem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a>.</p>


<p>Referenced by <a href="#a95c5146c0c6b3cca75af04e9494ffed9">printVecCompareInstr</a>.</p>

</div>
</div>

### printzmmwordmem() {#af54a3b0dab2282abe65dade324dc140d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86ATTInstPrinter::printzmmwordmem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ab7d33433deb752463cdbaa7a587eb969">printMemReference</a>.</p>


<p>Referenced by <a href="#a95c5146c0c6b3cca75af04e9494ffed9">printVecCompareInstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasCustomInstComment {#a5049609de0ca38a1c2469a30f0f4032f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86ATTInstPrinter::HasCustomInstComment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getRegisterName() {#a124a43d72f8680a64fdd7132d29b1775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::X86ATTInstPrinter::getRegisterName (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp/#a894b4b25e2718aa162dc7675f5208912">getRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#aef7abd9e585da4743700d2c04b17ab77">getShuffleComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a185f9311cecc76ba862f1420c20db158">printAsmMRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a76421690e64ee4e01b59f44c74fa9c20">printAsmVRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86mcexpr/#ab19f09b74160b1ace474ec0660f6c325">llvm::X86MCExpr::printImpl</a> and <a href="#ac59222883330e9cdcebf2c39dc9d6d7d">printRegName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-cpp">X86ATTInstPrinter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">X86ATTInstPrinter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
