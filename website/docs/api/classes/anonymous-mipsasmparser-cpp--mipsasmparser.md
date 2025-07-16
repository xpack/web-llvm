---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsAsmParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MipsAsmParser.cpp}::MipsAsmParser { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> - Generic interface to target specific assembly parsers. <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">MacroExpanderResultTy { <a href="#ab602d70fc3f7760c1129476262284ef5">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MipsMatchResultTy { <a href="#a1cc23ec2b0500b7a65f0dff434439842">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96cded7294d54537fbb8eb5a6148448a">MipsAsmParser</a> (const MCSubtargetInfo &amp;sti, MCAsmParser &amp;parser, const MCInstrInfo &amp;MII, const MCTargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac964e5af40a6a2ef3f9c66ff99a9bff6">hasEightFccRegisters</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if all of $fcc0 - $fcc7 exist for the current ISA. <a href="#ac964e5af40a6a2ef3f9c66ff99a9bff6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add247e0ffe13bb3be96149a87f76fdd0">isGP64bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c574cee37d4dc862ab265d3d868f48">isFP64bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d5112681065033b21957cce5c39a006">isJalrRelocAvailable</a> (const MCExpr *JalExpr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8210c883374ef37931a98f5a6f29cdaf">getABI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53f77370590649e45c899803f28c7ca">isABI_N32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e45cf8ca147de3b0754dace689b95d8">isABI_N64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f649f8fc75e6d81af975b11e185aa2">isABI_O32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b9eda08cdf4302cefdd29142fd7ad9">isABI_FPXX</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0e0ccb7e6acd30896a906f736c43b5">useOddSPReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e85cf47ca6b1d8ddda59b00a7ae36ba">inMicroMipsMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e047192437014aae53ea1890032247">hasMips1</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc794873c49297ff96574e00f1b5663e">hasMips2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33358b01657551e9897c46ae22ac769">hasMips3</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae249c0d4e2f933c6813d7240d4cac74a">hasMips4</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1b6f33c50c7c62eb22755e58db6767">hasMips5</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3ae5f55aa381e1a6f736b94a6e677c">hasMips32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad589304ee63280c264c3c98caf1c539f">hasMips64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01dcbaf97b1b2705589d8236031a79e3">hasMips32r2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8730ce5a088eda1c3140256bd6a03c9e">hasMips64r2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ce16773cf8c7f0c98f7fbaa3d5d317">hasMips32r3</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1f4d7b73354121e3aad92f0d67f92b">hasMips64r3</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593aedccc3a26cec8905b51b632bf4b9">hasMips32r5</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6610f1f33c28ac40df021889e30637">hasMips64r5</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87a9d84e6a95a2a8dec24cc9fbf9782">hasMips32r6</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab4e6172794538d72918f061a2f0c5b">hasMips64r6</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c021c9f4635df0665d125048b47e7e">hasDSP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5a07b97ad289fdde26ae19668bdb70">hasDSPR2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6f2aa184e5830270965e716a6b4bab2">hasDSPR3</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc6713921dceca3b4e9f3786489f79f">hasMSA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb0529e17a17d8f4a2213203d014915">hasCnMips</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affbd145c3b36fef1fd4b257af1d518c3">hasCnMipsP</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa143403928e1083cfdc597cb6fce3586">inPicMode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107301eb02adf57c8691e0657b691a0b">inMips16Mode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0663cdef0df07f884fd131f854895fc0">useTraps</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60fab57f12760fb6292bd6a0772ecae0">useSoftFloat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e8f2965e69274bfd3721377a2c5a73">hasMT</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787bb66fa41d02867509747713c2bc5b">hasCRC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0bed1f160b0b40a74d80ce644a3fcb0">hasVirt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334ef162a9c4e3edf76f888bea0da7c3">hasGINV</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5c0612448c5ac2b161b8519f8d07ef">hasForbiddenSlot</a> (const MCInstrDesc &amp;MCID) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb21a485fa2fd2134dc9b42138f978c">SafeInForbiddenSlot</a> (const MCInstrDesc &amp;MCID) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb49acf71f4529ada133ab101343bf36">onEndOfFile</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae30aebdceb6d90a602e7f4df5ee13829">warnIfRegIndexIsAT</a> (unsigned RegIndex, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Warn if RegIndex is the same as the current AT. <a href="#ae30aebdceb6d90a602e7f4df5ee13829">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae122d4f2b68d15529a89d7ac74a316cb">warnIfNoMacro</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e638c0bc60a5cc583fec2a57f29e56d">isLittle</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d8b8865a2b71781082b9ea2da3b5a5">createTargetUnaryExpr</a> (const MCExpr *E, AsmToken::TokenKind OperatorToken, MCContext &amp;Ctx) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50aebe296a5374cbaae3b62e835c034b">areEqualRegs</a> (const MCParsedAsmOperand &amp;Op1, const MCParsedAsmOperand &amp;Op2) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether two operands are registers and are equal. <a href="#a50aebe296a5374cbaae3b62e835c034b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer">MipsTargetStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec8c6f7327237fb73d88758a0734ae2d">getTargetStreamer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab24464a6370e0a570dc0234e7cbc719c">printWarningWithFixIt</a> (const Twine &amp;Msg, const Twine &amp;FixMsg, SMRange Range, bool ShowColors=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6179f9c290f368178cee3497d0e046a5">ConvertXWPOperands</a> (MCInst &amp;Inst, const OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7f29dc7ec6b88215d52a57bd18af92d">checkEarlyTargetMatchPredicate</a> (MCInst &amp;Inst, const OperandVector &amp;Operands) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Validate the instruction match against any complex target predicates before rendering any operands to it. <a href="#ac7f29dc7ec6b88215d52a57bd18af92d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecdad75bf6b2335ce65fee5181175f3f">checkTargetMatchPredicate</a> (MCInst &amp;Inst) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkTargetMatchPredicate - Validate the instruction match against any complex target predicates not expressible via match classes. <a href="#aecdad75bf6b2335ce65fee5181175f3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7ce11f80d66cb8929283c9ce394b29">matchAndEmitInstruction</a> (SMLoc IDLoc, unsigned &amp;Opcode, OperandVector &amp;Operands, MCStreamer &amp;Out, uint64_t &amp;ErrorInfo, bool MatchingInlineAsm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recognize a series of operands of a parsed instruction as an actual MCInst and emit it to the specified MCStreamer. <a href="#a9b7ce11f80d66cb8929283c9ce394b29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f9242c0c9f87ff75fcac3b41575c95">parseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse a register as used in CFI directives. <a href="#a36f9242c0c9f87ff75fcac3b41575c95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ce1e3216973844f0d7a6225dfca14e">tryParseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryParseRegister - parse one register if possible <a href="#a41ce1e3216973844f0d7a6225dfca14e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2632f17531ad3348eb64b2dd59a793c">parseParenSuffix</a> (StringRef Name, OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sometimes (i.e. <a href="#ac2632f17531ad3348eb64b2dd59a793c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae123684b16e02da8ee5bcccc1bb355e1">parseBracketSuffix</a> (StringRef Name, OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sometimes (i.e. <a href="#ae123684b16e02da8ee5bcccc1bb355e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa074f81f8252a05df84b602c18680ba8">mnemonicIsValid</a> (StringRef Mnemonic, unsigned VariantID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077824f58c9e845e84f0f2cf050a943c">parseInstruction</a> (ParseInstructionInfo &amp;Info, StringRef Name, SMLoc NameLoc, OperandVector &amp;Operands) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse one assembly instruction. <a href="#a077824f58c9e845e84f0f2cf050a943c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927c6d2fc5a8123e0ff253ea54a37734">ParseDirective</a> (AsmToken DirectiveID) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirective - Parse a target specific assembler directive This method is deprecated, use 'parseDirective' instead. <a href="#a927c6d2fc5a8123e0ff253ea54a37734">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3f5155a9fdec8988eee087419fb0a6">parseMemOperand</a> (OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b2caa3c30c2b189ae737e9fd52cc5fb">matchAnyRegisterNameWithoutDollar</a> (OperandVector &amp;Operands, StringRef Identifier, SMLoc S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847a0eb482ef2389b8bdb350a9b0c60f">matchAnyRegisterWithoutDollar</a> (OperandVector &amp;Operands, const AsmToken &amp;Token, SMLoc S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86bc6d294617025ffcba39706bbff635">matchAnyRegisterWithoutDollar</a> (OperandVector &amp;Operands, SMLoc S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e458a48b209a63923e6d2ba02be9cfb">parseAnyRegister</a> (OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a5011bdb951ba8f695ed702f248452e">parseImm</a> (OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95fb3130367d4e5fbedd59513e1dc991">parseJumpTarget</a> (OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f1e8637d1708545d998dc6ceb2c4584">parseInvNum</a> (OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e68e57ed9af34672256bed0a4a0d176">parseRegisterList</a> (OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ba30d5df0749190fe7ef82a39c1740">searchSymbolAlias</a> (OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade1a046fe264c33e5926c6433dc8b746">parseOperand</a> (OperandVector &amp;, StringRef Mnemonic)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MacroExpanderResultTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b37d14640640310c45c8cede887b49">tryExpandInstruction</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f17f2686cb575dbf6e3c2022773bdc6">expandJalWithRegs</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b21a8419273a3a5600c4b3126a45cf5">loadImmediate</a> (int64_t ImmValue, unsigned DstReg, unsigned SrcReg, bool Is32BitImm, bool IsAddress, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load (or add) an immediate into a register. <a href="#a2b21a8419273a3a5600c4b3126a45cf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa816aab0035b466d1621be3f3b292e16">loadAndAddSymbolAddress</a> (const MCExpr *SymExpr, unsigned DstReg, unsigned SrcReg, bool Is32BitSym, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9f61bd31717a61786919901b458cf8">emitPartialAddress</a> (MipsTargetStreamer &amp;TOut, SMLoc IDLoc, MCSymbol *Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc9209695915d81cc104ecbf431e79dd">expandLoadImm</a> (MCInst &amp;Inst, bool Is32BitImm, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac687ae0a5d8985d622f06aa42ed7a939">expandLoadSingleImmToGPR</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc7df799800be32455558edace17546">expandLoadSingleImmToFPR</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc37471876aa6bd87f4573b711fedaee">expandLoadDoubleImmToGPR</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf1ccd16277e15e9dee9b2d8f970fc8">expandLoadDoubleImmToFPR</a> (MCInst &amp;Inst, bool Is64FPU, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12be6e2aff70dbe01be1722b79346323">expandLoadAddress</a> (unsigned DstReg, unsigned BaseReg, const MCOperand &amp;Offset, bool Is32BitAddress, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93e8f03eff7217371cbb7013467a8e2">expandUncondBranchMMPseudo</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af77686356c3280d6cb00497d20382268">expandMem16Inst</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI, bool IsLoad)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ee40372c359cb125289a6caf7110d70">expandMem9Inst</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI, bool IsLoad)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f3366c1bdff2add30093d3957bbfbec">expandLoadStoreMultiple</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac709887d9f1150ed15a7c55944f3ab6a">expandAliasImmediate</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a5e1913312d6eeadb442f84e9cffd3">expandBranchImm</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a271dc198238249a46e695518c54745dd">expandCondBranches</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae734efcb068c37a99bd54de7e46d9d34">expandDivRem</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI, const bool IsMips64, const bool Signed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9926785ed5d084be598befc6263736">expandTrunc</a> (MCInst &amp;Inst, bool IsDouble, bool Is64FPU, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5200f8b225e93e2165e42e43c7eb39">expandUlh</a> (MCInst &amp;Inst, bool Signed, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2892fc0f5917479be3b5d2df8fa384">expandUsh</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3314f3ab8a8f0baa2ebc400d1f17faf7">expandUxw</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae343fb3878d35108b1dc8e9018d9b40c">expandSge</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a9480f6d103f98e20a690d2718a07f">expandSgeImm</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91d596658f39fa9403cde2fe2e2d3251">expandSgtImm</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e7a0fc3d086351cc241bd22ade17fd">expandSle</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a06e9e31468cdf62076ee57ea3c0113">expandSleImm</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d6f2007bebdd5e1e8f109aa1fae0a0">expandRotation</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a807fa0c7a13fdf571e614256fc4a8c6a">expandRotationImm</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb942c2e0ffc8dcc669c10d35a54dd2b">expandDRotation</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dfeeea5790378755b29b6216d87037c">expandDRotationImm</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d1015d7e0eb35457fcbce71f6b73d7f">expandAbs</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909b12611b69bbffeae8f3b177e1ca40">expandMulImm</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af649e1521a1ae8013745e2108994652e">expandMulO</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a36fe676cf2be2a02dc9db3ddf03c2">expandMulOU</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f7c48d9abba71693d124f6b4b38b0fb">expandDMULMacro</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b5434071ad1adc0fe6e52ad5454f7a3">expandLoadStoreDMacro</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI, bool IsLoad)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a4d117f5e2a4c5b975d7cfff3c2ae86">expandStoreDM1Macro</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38d466f7516f32be395c24aa5c68cd3">expandSeq</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980aa9fa92ee8ec3ca59f30f12a2d189">expandSeqI</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40eda94f90a8599a631838682f52f9b2">expandSne</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b3259390aef9b10637cc90bd36a69f2">expandSneI</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf531c43959d1d3d5d42834086392d51">expandMXTRAlias</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand an alias of 'mftr' or 'mttr' into the full instruction, by producing an mftr or mttr with the correctly mapped gpr register, u, sel and h bits. <a href="#adf531c43959d1d3d5d42834086392d51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec71f32fe86f92c20bdd792c2f61266">expandSaaAddr</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0bfd96034bc491d3394e3997c9c106">reportParseError</a> (const Twine &amp;ErrorMsg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae428f3920c26fb06d248ddba230cc0cd">reportParseError</a> (SMLoc Loc, const Twine &amp;ErrorMsg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18044571d5e7d324b9c913246a8567cd">parseMemOffset</a> (const MCExpr *&amp;Res, bool isParenExpr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ab616dc3e3d1cb9a278f78b78e42f7">parseSetMips0Directive</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f6ea5e72a31b24678d87af4c96f552">parseSetArchDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34cdf2fb2689296d9ad082ccc701618">parseSetFeature</a> (uint64_t Feature)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6eae0029cc894b1e4481f5a099433f">isPicAndNotNxxAbi</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c8a9d68ccbd9cca8f9baa767b0719e6">parseDirectiveCpAdd</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5b2663de90f158d66d4ebd8ac6e563">parseDirectiveCpLoad</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac94192edbe3e311ac2aee4aa4218d55b">parseDirectiveCpLocal</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a782e23141551905c3306b8f6f3e330df">parseDirectiveCpRestore</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a187e407e9f580a72b388b16a530bf1ef">parseDirectiveCPSetup</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a2120b9f55ba9758805117e8f9e793">parseDirectiveCPReturn</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb69465a9e78660bbf8dd805e001bfd1">parseDirectiveNaN</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb0a48bd0b5ffbb804411ad77be002b2">parseDirectiveSet</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0fb0bbbad912849e5669f90811c3f5b">parseDirectiveOption</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a7a7935b88cf566d4a8cf4345860c5e">parseInsnDirective</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseInsnDirective ::= .insn <a href="#a4a7a7935b88cf566d4a8cf4345860c5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79efeb36093fdd82e27d9679909cee84">parseRSectionDirective</a> (StringRef Section)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseRSectionDirective ::= .rdata <a href="#a79efeb36093fdd82e27d9679909cee84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b4967aadd0a776cd192d8416495d9c">parseSSectionDirective</a> (StringRef Section, unsigned Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseSSectionDirective ::= .sbss ::= .sdata <a href="#a45b4967aadd0a776cd192d8416495d9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e3e8bdbec41d52a2617ebbfa26f104">parseSetAtDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42768c0c11572cbf6489fa90e9b766e3">parseSetNoAtDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a800743c47bdb61dd32de9ac0f5fcc">parseSetMacroDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a61f6a742fe819653f27a8a2d2b68ca">parseSetNoMacroDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b5a1c12a951d092ae177677355093a">parseSetMsaDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7649e9b3a8f03b3b513e8b534bef2b48">parseSetNoMsaDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3cabb232c6fe93d86e9ad24db7a516d">parseSetNoDspDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a225a37abc608b3db0afd3f501191a">parseSetNoMips3DDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124cd8624102bbafc19b391f87f3e591">parseSetReorderDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9403606d5d4a1f0ee90d292d4452ea1d">parseSetNoReorderDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3dbaab23d42c5a75f9dd3762ef092a">parseSetMips16Directive</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58fe47bc833d49bfcfcf00b0475f6b2a">parseSetNoMips16Directive</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ff48b0ac1245470be8d69f876805cf">parseSetFpDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fada66382f9d8442f42e9edef060250">parseSetOddSPRegDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cd498157701e08bbb25a7140e8ad82f">parseSetNoOddSPRegDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b558fcbb772ac18b4c92115ef524bc">parseSetPopDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e41c9decf0f396063dffb54b9c348c7">parseSetPushDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fafbf62257a9d3db9d5222f3eb57da8">parseSetSoftFloatDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a129337e909b576f426e6632cead3be16">parseSetHardFloatDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8abc1bdaea4bfaa8ee7dc22911615f">parseSetMtDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66917d68435b8f7328b4d910fed59365">parseSetNoMtDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690aab6011276e8102150a8fae1680dc">parseSetNoCRCDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6998d4cba0966938f2ae9784728f47bb">parseSetNoVirtDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10df9679d46d858984228cf77c006387">parseSetNoGINVDirective</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1202893f3ad90cf0314829897773d4df">parseSetAssignment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283c780ef6d5ae515f4f31691f87bd82">parseDirectiveGpWord</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveGpWord ::= .gpword local_sym <a href="#a283c780ef6d5ae515f4f31691f87bd82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a4026475dec860a397124ee828306b">parseDirectiveGpDWord</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveGpDWord ::= .gpdword local_sym <a href="#a36a4026475dec860a397124ee828306b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61ed969bb0c5e1c87f7a2fd55a80b2a8">parseDirectiveDtpRelWord</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveDtpRelWord ::= .dtprelword tls_sym <a href="#a61ed969bb0c5e1c87f7a2fd55a80b2a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b61b13e9e0152ae84934c36a7fceaaf">parseDirectiveDtpRelDWord</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveDtpRelDWord ::= .dtpreldword tls_sym <a href="#a2b61b13e9e0152ae84934c36a7fceaaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb9163f10ae58f4fbc06797a59a8e5ad">parseDirectiveTpRelWord</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveTpRelWord ::= .tprelword tls_sym <a href="#aeb9163f10ae58f4fbc06797a59a8e5ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a933d199e8dc55baf54fd79b3c905d68f">parseDirectiveTpRelDWord</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveTpRelDWord ::= .tpreldword tls_sym <a href="#a933d199e8dc55baf54fd79b3c905d68f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d18db6320cd4996efaf7f8023302a38">parseDirectiveModule</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveModule ::= .module oddspreg ::= .module nooddspreg ::= .module fp=value ::= .module softfloat ::= .module hardfloat ::= .module mt ::= .module crc ::= .module nocrc ::= .module virt ::= .module novirt ::= .module ginv ::= .module noginv <a href="#a8d18db6320cd4996efaf7f8023302a38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b39632eba3fd0da113e20239a1a61d">parseDirectiveModuleFP</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveModuleFP ::= =32 ::= =xx ::= =64 <a href="#a28b39632eba3fd0da113e20239a1a61d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2835de3e04e5cf236dd51664f443bca7">parseFpABIValue</a> (MipsABIFlagsSection::FpABIKind &amp;FpABI, StringRef Directive)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c5f86fb915e0ff7c615ac11698e9ba">parseInternalDirectiveReallowModule</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987bf9566130ea81a35aeebeab83b4bb">eatComma</a> (StringRef ErrorStr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a56643fb6abee5fee26725113200c8b">matchCPURegisterName</a> (StringRef Symbol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2b26225805cb9e7c8a05e613062951e">matchHWRegsRegisterName</a> (StringRef Symbol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4c0ae4b50a00f1a0bea9cb74f36e7bd">matchFPURegisterName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec5b4525d2dfa79802cfc7428a7a11d">matchFCCRegisterName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265f34b23da0927f9dfb4b61a6f4b734">matchACRegisterName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa4913c5b3a6a7fb3e08f140459eecb">matchMSA128RegisterName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60d6b0d40c9bb56b26a144598e6ca9c">matchMSA128CtrlRegisterName</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a044894054ade826eaf00a9f061d49693">getReg</a> (int RC, int RegNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac69606a72faa6fd9396f81466f8919">getATReg</a> (SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the internal register number for the current AT. <a href="#a2ac69606a72faa6fd9396f81466f8919">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa097b951858a3b2df4bd712482d245b5">canUseATReg</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a0a116d8357670ba75a1ce0958759b">processInstruction</a> (MCInst &amp;Inst, SMLoc IDLoc, MCStreamer &amp;Out, const MCSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a812b76c8a744159214eb59a320e71673">validateMSAIndex</a> (int Val, int RegKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad732510c581158cbb7ebbb8bd0a5eb9a">selectArch</a> (StringRef ArchFeature)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e638c898a10b5abcebc918b5c6ae88a">setFeatureBits</a> (uint64_t Feature, StringRef FeatureString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c5a14255f397ffc1a84f1ad2995d49">clearFeatureBits</a> (uint64_t Feature, StringRef FeatureString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f783070645835799f29ab322c2b62a">setModuleFeatureBits</a> (uint64_t Feature, StringRef FeatureString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abce32b8da8200e7ba5fe9b77e1dc7677">clearModuleFeatureBits</a> (uint64_t Feature, StringRef FeatureString)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo">MipsABIInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d46cc26a1352a40ecf2b74b446ac2a2">ABI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsassembleroptions">MipsAssemblerOptions</a> &gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a748bcbbe1da0340bc6a61e0f8a067197">AssemblerOptions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72697300adb432a2861ca52e02c37015">CurrentFn</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe0320d4066b0db98f4520795c2c8f68">IsLittleEndian</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93d90480ea5a2c30560e6200577049d">IsPicEnabled</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b520780336cdb335541dcc71049a2a">IsCpRestoreSet</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a755008f391b4778d02df40aa77d813c7">CurForbiddenSlotAttr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03659a3443b146d6d359c54c06a002cd">CpRestoreOffset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31d5b0c72a63d693347f59a447e7cb6">GPReg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec16d9c9d499fb09d7d4502904824e18">CpSaveLocation</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a7dcd9e979dacec662fc1be078f8a40">CpSaveLocationIsRegister</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, then CpSaveLocation is a register, otherwise it's an offset. <a href="#a0a7dcd9e979dacec662fc1be078f8a40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc654be0b70b5cc77422ca7f33bc4cb">RegisterSets</a></td>
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


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### MacroExpanderResultTy {#ab602d70fc3f7760c1129476262284ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MipsAsmParser.cpp}::MipsAsmParser::MacroExpanderResultTy </td>
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
<td class="doxyEnumItemName">MER_NotAMacro<a id="ab602d70fc3f7760c1129476262284ef5a38d05c85f944295487adcb06a73e085c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MER_Success<a id="ab602d70fc3f7760c1129476262284ef5aa4104e0b3cbdaa32a3645b4e18d83ade"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MER_Fail<a id="ab602d70fc3f7760c1129476262284ef5a99e268f98808cf42579dc334f842f905"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### MipsMatchResultTy {#a1cc23ec2b0500b7a65f0dff434439842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MipsAsmParser.cpp}::MipsAsmParser::MipsMatchResultTy </td>
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
<td class="doxyEnumItemName">Match_RequiresDifferentSrcAndDst<a id="a1cc23ec2b0500b7a65f0dff434439842a8c6f89987c5c40be819a0ed56b354fa1"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_TARGET_MATCH_RESULT_TY)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_RequiresDifferentOperands<a id="a1cc23ec2b0500b7a65f0dff434439842ae445212ead627fa359e884f87e132a13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_RequiresNoZeroRegister<a id="a1cc23ec2b0500b7a65f0dff434439842a2930fa07ef4d79687c49cad0479b0080"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_RequiresSameSrcAndDst<a id="a1cc23ec2b0500b7a65f0dff434439842a664aa6ca404e7fd08a04d29eb90f3b57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_NoFCCRegisterForCurrentISA<a id="a1cc23ec2b0500b7a65f0dff434439842ae3ab58384212038c52ba9a960d8af5f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_NonZeroOperandForSync<a id="a1cc23ec2b0500b7a65f0dff434439842a6626abf70519c894ba2922857c494d9e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_NonZeroOperandForMTCX<a id="a1cc23ec2b0500b7a65f0dff434439842adb7242a8318ac0b1f510b16f64138d3e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_RequiresPosSizeRange0_32<a id="a1cc23ec2b0500b7a65f0dff434439842a1cbe94fcccc17763c7b59e10b432e26b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_RequiresPosSizeRange33_64<a id="a1cc23ec2b0500b7a65f0dff434439842a420cd517d7f713ee29f64da2cf2f2054"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_RequiresPosSizeUImm6<a id="a1cc23ec2b0500b7a65f0dff434439842afc1f39191c4c6f57322ac96ddc0947e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MipsAsmParser() {#a96cded7294d54537fbb8eb5a6148448a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MipsAsmParser.cpp}::MipsAsmParser::MipsAsmParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; sti, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; parser, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#abd600bd726e3f0dc6745757b8ff99322">llvm::MCAsmParser::addAliasForDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a725fe8674a09b1579039321d641118e4">computeTargetABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c346c56fb9021d994675d1710d2d551">llvm::getCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1ef6ef4ff039e873e9f66e21e3e55e26">llvm::MCSubtargetInfo::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a77a335167c72ea8bc771501825f81696">llvm::MCAsmParserExtension::Initialize</a>, <a href="#a7e85cf47ca6b1d8ddda59b00a7ae36ba">inMicroMipsMode</a>, <a href="#a16f649f8fc75e6d81af975b11e185aa2">isABI_O32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a45678567c4d2b54e70800daa41897207">llvm::Triple::isLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a32cd9ae9007321c391a62dd4bd69d268">llvm::MCTargetAsmParser::MCTargetAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a86c4103ccd50c7d1f8df88d71ccfef5e">llvm::MCTargetAsmParser::MII</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9bc309121dfab6b0c03a026eec7b2ab7">llvm::MCTargetAsmParser::setAvailableFeatures</a> and <a href="#a0e0e0ccb7e6acd30896a906f736c43b5">useOddSPReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### areEqualRegs() {#a50aebe296a5374cbaae3b62e835c034b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::areEqualRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a> &amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a> &amp; Op2)</td>
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

<p>Returns whether two operands are registers and are equal.</p>


<p>This is used by the tied-operands checks in the AsmMatcher. This method can be overridden to allow e.g. a sub- or super-register as the tied operand.</p>


<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a78471ca3b825294a4e6015500d7a6630">llvm::MCParsedAsmOperand::getReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a3212ab0fba4f46a46382c297dd7ee5f7">llvm::MCParsedAsmOperand::isReg</a>.</p>

</div>
</div>

### createTargetUnaryExpr() {#a79d8b8865a2b71781082b9ea2da3b5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{MipsAsmParser.cpp}::MipsAsmParser::createTargetUnaryExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * E, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> OperatorToken, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#a0087423de073ff81b2249bdea54eab40">llvm::MipsMCExpr::create</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a257902481821ba5b40f837390279b03a">llvm::MipsMCExpr::MEK_CALL_HI16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a649881b3e57f4661dd4c80bee4a4b90a">llvm::MipsMCExpr::MEK_CALL_LO16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a89d1a8e66789c4eae95877553dbc1565">llvm::MipsMCExpr::MEK_DTPREL_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a9d0a302a9152729f52460e636c7fb44e">llvm::MipsMCExpr::MEK_DTPREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a386aafa447bee675e328e88e9470957e">llvm::MipsMCExpr::MEK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a0453b77229668594037b194c19c8e8ab">llvm::MipsMCExpr::MEK_GOT_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a0ae33921dce666ee7adef46268bf9f2f">llvm::MipsMCExpr::MEK_GOT_DISP</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a0a7f1b614b8ffd488e6089fbe10a316f">llvm::MipsMCExpr::MEK_GOT_HI16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70af6e3d6f3b62ea7d5e97a5e8ff6ccf054">llvm::MipsMCExpr::MEK_GOT_LO16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70ab986b26f0ebeb0499f36b0d82fe639d7">llvm::MipsMCExpr::MEK_GOT_OFST</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70adcc3e0803f2bff3ce95d8ff86fb0f550">llvm::MipsMCExpr::MEK_GOT_PAGE</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a79bd0912db4f9ad29c7e7e172a5c805d">llvm::MipsMCExpr::MEK_GOTTPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a24a451c9dcd6dc7d1ea999a25d59eaa6">llvm::MipsMCExpr::MEK_GPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a8ac2bfc0d79177cf5b86d149b0c5e9d4">llvm::MipsMCExpr::MEK_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70ad184d95272d90612c94695f1d1f42fcf">llvm::MipsMCExpr::MEK_HIGHER</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70aeb7b57e94a471eb90a2905c65b60ce47">llvm::MipsMCExpr::MEK_HIGHEST</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70aa2690d1ded3eb1d272f24462311161e8">llvm::MipsMCExpr::MEK_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a3640c09e70edd6796e72ed1e1989fa2d">llvm::MipsMCExpr::MEK_NEG</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70adc7eb8cb308edcc2b568b4a737a6174c">llvm::MipsMCExpr::MEK_PCREL_HI16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70ac16da9fec94c6aaee788e43d1788bfea">llvm::MipsMCExpr::MEK_PCREL_LO16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70abe74e919e6de05ae1af1093c96928e29">llvm::MipsMCExpr::MEK_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a89674453ca1f94bb72d4e9dca3e1e771">llvm::MipsMCExpr::MEK_TLSLDM</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a855ac563dd866b584fe34b8d58eb4546">llvm::MipsMCExpr::MEK_TPREL_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a8c4e3452b4ab8d6f1b9bdb42ecd075f6">llvm::MipsMCExpr::MEK_TPREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a00c4e8d8fb246b6b7aeed5c7b53ee299">llvm::AsmToken::PercentCall16</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a707c1a6ff33be3833fa784e55c72d356">llvm::AsmToken::PercentCall_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a074f871580c44c082aa24aaafd8a238a">llvm::AsmToken::PercentCall_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a267b3c56c189ca7b2c22f3f5a29647fe">llvm::AsmToken::PercentDtprel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aa8b764c71f0045677baab76623a52bcd">llvm::AsmToken::PercentDtprel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a00774b22629d30aaa48e1c2bd537028b">llvm::AsmToken::PercentGot</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039af1f8ea5e121b4bc15a5df42c055bd6d7">llvm::AsmToken::PercentGot_Disp</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ab0762694eece06d0f7a3a2079a4a4fc8">llvm::AsmToken::PercentGot_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0c1d09e9bf3105cc4a9f0fdbd353573e">llvm::AsmToken::PercentGot_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad1e2f5b48c997464f7959fc57dffc5f8">llvm::AsmToken::PercentGot_Ofst</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a92f6b21bb33e8fed87795f60509087b9">llvm::AsmToken::PercentGot_Page</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a0605e7b15189ad4dbaf2de310d8d71d6">llvm::AsmToken::PercentGottprel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039aceac274aaa62864ab0b60654281e237a">llvm::AsmToken::PercentGp_Rel</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a07aadc6194c34b01c1dbc32579382c1e">llvm::AsmToken::PercentHi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a1889a8a107d7a02053f669a752290d2d">llvm::AsmToken::PercentHigher</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ab00380bcbfc11a24a06d6ff70619f9fa">llvm::AsmToken::PercentHighest</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ad3c8fae162d44bb21f7f39c853e85eca">llvm::AsmToken::PercentLo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039afe3b827d1ceee6cf5aaf0bb61cc1e77f">llvm::AsmToken::PercentNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a28be2810a4857bb3b0aad6844d80176e">llvm::AsmToken::PercentPcrel_Hi</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a7aa2c1d1de0fe4ef4d1d2275632aa6a1">llvm::AsmToken::PercentPcrel_Lo</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8f666b660d975090f718938ee00fe9fc">llvm::AsmToken::PercentTlsgd</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a91a7f91ec2b3a0618572a821556591cf">llvm::AsmToken::PercentTlsldm</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a8df6f192abb2cb6a173a7a2aa91bd8a2">llvm::AsmToken::PercentTprel_Hi</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a63518ba1849d2eb240372e55b9a04436">llvm::AsmToken::PercentTprel_Lo</a>.</p>

</div>
</div>

### getABI() {#a8210c883374ef37931a98f5a6f29cdaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsABIInfo &amp; anonymous{MipsAsmParser.cpp}::MipsAsmParser::getABI ()</td>
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



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### hasCnMips() {#a1bb0529e17a17d8f4a2213203d014915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasCnMips ()</td>
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



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasCnMipsP() {#affbd145c3b36fef1fd4b257af1d518c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasCnMipsP ()</td>
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



<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasCRC() {#a787bb66fa41d02867509747713c2bc5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasCRC ()</td>
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



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasDSP() {#a25c021c9f4635df0665d125048b47e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasDSP ()</td>
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



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasDSPR2() {#aac5a07b97ad289fdde26ae19668bdb70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasDSPR2 ()</td>
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



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasDSPR3() {#ae6f2aa184e5830270965e716a6b4bab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasDSPR3 ()</td>
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



<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasEightFccRegisters() {#ac964e5af40a6a2ef3f9c66ff99a9bff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasEightFccRegisters ()</td>
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

<p>True if all of $fcc0 - $fcc7 exist for the current ISA.</p>

<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>References <a href="#a1e3ae5f55aa381e1a6f736b94a6e677c">hasMips32</a> and <a href="#ae249c0d4e2f933c6813d7240d4cac74a">hasMips4</a>.</p>

</div>
</div>

### hasForbiddenSlot() {#a0c5c0612448c5ac2b161b8519f8d07ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasForbiddenSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; MCID)</td>
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



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#aa15730b4ade780fcc4cc70b956af313eaa073124a362de1f2a0c6ff15a51da563">llvm::MipsII::HasForbiddenSlot</a> and <a href="#a7e85cf47ca6b1d8ddda59b00a7ae36ba">inMicroMipsMode</a>.</p>

</div>
</div>

### hasGINV() {#a334ef162a9c4e3edf76f888bea0da7c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasGINV ()</td>
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



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips1() {#a35e047192437014aae53ea1890032247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips1 ()</td>
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



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips2() {#abc794873c49297ff96574e00f1b5663e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips2 ()</td>
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



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips3() {#ab33358b01657551e9897c46ae22ac769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips3 ()</td>
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



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips32() {#a1e3ae5f55aa381e1a6f736b94a6e677c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips32 ()</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>


<p>Referenced by <a href="#ac964e5af40a6a2ef3f9c66ff99a9bff6">hasEightFccRegisters</a>.</p>

</div>
</div>

### hasMips32r2() {#a01dcbaf97b1b2705589d8236031a79e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips32r2 ()</td>
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



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips32r3() {#a19ce16773cf8c7f0c98f7fbaa3d5d317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips32r3 ()</td>
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



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips32r5() {#a593aedccc3a26cec8905b51b632bf4b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips32r5 ()</td>
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



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips32r6() {#aa87a9d84e6a95a2a8dec24cc9fbf9782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips32r6 ()</td>
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



<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips4() {#ae249c0d4e2f933c6813d7240d4cac74a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips4 ()</td>
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



<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>


<p>Referenced by <a href="#ac964e5af40a6a2ef3f9c66ff99a9bff6">hasEightFccRegisters</a>.</p>

</div>
</div>

### hasMips5() {#a2d1b6f33c50c7c62eb22755e58db6767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips5 ()</td>
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



<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips64() {#ad589304ee63280c264c3c98caf1c539f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips64 ()</td>
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



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips64r2() {#a8730ce5a088eda1c3140256bd6a03c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips64r2 ()</td>
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



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips64r3() {#afa1f4d7b73354121e3aad92f0d67f92b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips64r3 ()</td>
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



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips64r5() {#a5f6610f1f33c28ac40df021889e30637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips64r5 ()</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMips64r6() {#a3ab4e6172794538d72918f061a2f0c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMips64r6 ()</td>
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



<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMSA() {#a3dc6713921dceca3b4e9f3786489f79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMSA ()</td>
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



<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasMT() {#ac2e8f2965e69274bfd3721377a2c5a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasMT ()</td>
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



<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### hasVirt() {#ad0bed1f160b0b40a74d80ce644a3fcb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::hasVirt ()</td>
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



<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### inMicroMipsMode() {#a7e85cf47ca6b1d8ddda59b00a7ae36ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::inMicroMipsMode ()</td>
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



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>


<p>Referenced by <a href="#a0c5c0612448c5ac2b161b8519f8d07ef">hasForbiddenSlot</a> and <a href="#a96cded7294d54537fbb8eb5a6148448a">MipsAsmParser</a>.</p>

</div>
</div>

### inMips16Mode() {#a107301eb02adf57c8691e0657b691a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::inMips16Mode ()</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### inPicMode() {#aa143403928e1083cfdc597cb6fce3586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::inPicMode ()</td>
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



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### isABI\_FPXX() {#aa6b9eda08cdf4302cefdd29142fd7ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::isABI_FPXX ()</td>
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



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### isABI\_N32() {#ac53f77370590649e45c899803f28c7ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::isABI_N32 ()</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### isABI\_N64() {#a2e45cf8ca147de3b0754dace689b95d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::isABI_N64 ()</td>
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



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### isABI\_O32() {#a16f649f8fc75e6d81af975b11e185aa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::isABI_O32 ()</td>
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



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a96cded7294d54537fbb8eb5a6148448a">MipsAsmParser</a>.</p>

</div>
</div>

### isFP64bit() {#a56c574cee37d4dc862ab265d3d868f48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::isFP64bit ()</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### isGP64bit() {#add247e0ffe13bb3be96149a87f76fdd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::isGP64bit ()</td>
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



<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### isJalrRelocAvailable() {#a1d5112681065033b21957cce5c39a006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::isJalrRelocAvailable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * JalExpr)</td>
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



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a9578328a1d072a99ad4322f34e52fa12">EmitJalrReloc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a>.</p>

</div>
</div>

### isLittle() {#a7e638c0bc60a5cc583fec2a57f29e56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::isLittle ()</td>
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



<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### onEndOfFile() {#adb49acf71f4529ada133ab101343bf36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAsmParser::onEndOfFile ()</td>
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



<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a09ac655a921f536b820733476056c75e">llvm::MipsTargetStreamer::emitDirectiveSetReorder</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a68f176e080c458432506637ce9976533">llvm::MipsTargetStreamer::emitEmptyDelaySlot</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aff6afefbe685c9940c3e082c7f576df6">llvm::MCTargetAsmParser::STI</a>.</p>

</div>
</div>

### SafeInForbiddenSlot() {#a7cb21a485fa2fd2134dc9b42138f978c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::SafeInForbiddenSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; MCID)</td>
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



<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/mipsii/#aa15730b4ade780fcc4cc70b956af313ea1bc5a446bd5b475f853dbb9642e070b9">llvm::MipsII::IsCTI</a>.</p>

</div>
</div>

### useOddSPReg() {#a0e0e0ccb7e6acd30896a906f736c43b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::useOddSPReg ()</td>
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



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>


<p>Referenced by <a href="#a96cded7294d54537fbb8eb5a6148448a">MipsAsmParser</a>.</p>

</div>
</div>

### useSoftFloat() {#a60fab57f12760fb6292bd6a0772ecae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::useSoftFloat ()</td>
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



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### useTraps() {#a0663cdef0df07f884fd131f854895fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::useTraps ()</td>
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



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>.</p>

</div>
</div>

### warnIfNoMacro() {#ae122d4f2b68d15529a89d7ac74a316cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAsmParser::warnIfNoMacro (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

### warnIfRegIndexIsAT() {#ae30aebdceb6d90a602e7f4df5ee13829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAsmParser::warnIfRegIndexIsAT (unsigned RegIndex, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Warn if RegIndex is the same as the current AT.</p>

<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canUseATReg() {#aa097b951858a3b2df4bd712482d245b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::canUseATReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### checkEarlyTargetMatchPredicate() {#ac7f29dc7ec6b88215d52a57bd18af92d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsAsmParser::checkEarlyTargetMatchPredicate (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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

<p>Validate the instruction match against any complex target predicates before rendering any operands to it.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### checkTargetMatchPredicate() {#aecdad75bf6b2335ce65fee5181175f3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsAsmParser::checkTargetMatchPredicate (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
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

<p>checkTargetMatchPredicate - Validate the instruction match against any complex target predicates not expressible via match classes.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### clearFeatureBits() {#a07c5a14255f397ffc1a84f1ad2995d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MipsAsmParser.cpp}::MipsAsmParser::clearFeatureBits (uint64_t Feature, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FeatureString)</td>
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



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### clearModuleFeatureBits() {#abce32b8da8200e7ba5fe9b77e1dc7677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MipsAsmParser.cpp}::MipsAsmParser::clearModuleFeatureBits (uint64_t Feature, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FeatureString)</td>
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



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### ConvertXWPOperands() {#a6179f9c290f368178cee3497d0e046a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAsmParser::ConvertXWPOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### eatComma() {#a987bf9566130ea81a35aeebeab83b4bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::eatComma (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ErrorStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### emitPartialAddress() {#a0c9f61bd31717a61786919901b458cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::emitPartialAddress (<a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer">MipsTargetStreamer</a> &amp; TOut, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandAbs() {#a6d1015d7e0eb35457fcbce71f6b73d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandAbs (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandAliasImmediate() {#ac709887d9f1150ed15a7c55944f3ab6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandAliasImmediate (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandBranchImm() {#ab9a5e1913312d6eeadb442f84e9cffd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandBranchImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandCondBranches() {#a271dc198238249a46e695518c54745dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandCondBranches (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandDivRem() {#ae734efcb068c37a99bd54de7e46d9d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandDivRem (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool IsMips64, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool Signed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandDMULMacro() {#a6f7c48d9abba71693d124f6b4b38b0fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandDMULMacro (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandDRotation() {#aeb942c2e0ffc8dcc669c10d35a54dd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandDRotation (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandDRotationImm() {#a8dfeeea5790378755b29b6216d87037c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandDRotationImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandJalWithRegs() {#a7f17f2686cb575dbf6e3c2022773bdc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandJalWithRegs (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandLoadAddress() {#a12be6e2aff70dbe01be1722b79346323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandLoadAddress (unsigned DstReg, unsigned BaseReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Offset, bool Is32BitAddress, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandLoadDoubleImmToFPR() {#aaaf1ccd16277e15e9dee9b2d8f970fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandLoadDoubleImmToFPR (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, bool Is64FPU, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandLoadDoubleImmToGPR() {#adc37471876aa6bd87f4573b711fedaee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandLoadDoubleImmToGPR (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandLoadImm() {#abc9209695915d81cc104ecbf431e79dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandLoadImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, bool Is32BitImm, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandLoadSingleImmToFPR() {#a5fc7df799800be32455558edace17546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandLoadSingleImmToFPR (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandLoadSingleImmToGPR() {#ac687ae0a5d8985d622f06aa42ed7a939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandLoadSingleImmToGPR (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandLoadStoreDMacro() {#a3b5434071ad1adc0fe6e52ad5454f7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandLoadStoreDMacro (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, bool IsLoad)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandLoadStoreMultiple() {#a2f3366c1bdff2add30093d3957bbfbec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandLoadStoreMultiple (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandMem16Inst() {#af77686356c3280d6cb00497d20382268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAsmParser::expandMem16Inst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, bool IsLoad)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandMem9Inst() {#a0ee40372c359cb125289a6caf7110d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAsmParser::expandMem9Inst (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, bool IsLoad)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandMulImm() {#a909b12611b69bbffeae8f3b177e1ca40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandMulImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandMulO() {#af649e1521a1ae8013745e2108994652e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandMulO (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandMulOU() {#aa7a36fe676cf2be2a02dc9db3ddf03c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandMulOU (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandMXTRAlias() {#adf531c43959d1d3d5d42834086392d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandMXTRAlias (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand an alias of 'mftr' or 'mttr' into the full instruction, by producing an mftr or mttr with the correctly mapped gpr register, u, sel and h bits.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandRotation() {#a44d6f2007bebdd5e1e8f109aa1fae0a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandRotation (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandRotationImm() {#a807fa0c7a13fdf571e614256fc4a8c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandRotationImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSaaAddr() {#a3ec71f32fe86f92c20bdd792c2f61266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSaaAddr (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSeq() {#af38d466f7516f32be395c24aa5c68cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSeq (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSeqI() {#a980aa9fa92ee8ec3ca59f30f12a2d189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSeqI (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSge() {#ae343fb3878d35108b1dc8e9018d9b40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSge (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSgeImm() {#ab2a9480f6d103f98e20a690d2718a07f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSgeImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSgtImm() {#a91d596658f39fa9403cde2fe2e2d3251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSgtImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSle() {#a35e7a0fc3d086351cc241bd22ade17fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSle (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSleImm() {#a9a06e9e31468cdf62076ee57ea3c0113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSleImm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSne() {#a40eda94f90a8599a631838682f52f9b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSne (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandSneI() {#a2b3259390aef9b10637cc90bd36a69f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandSneI (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandStoreDM1Macro() {#a4a4d117f5e2a4c5b975d7cfff3c2ae86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandStoreDM1Macro (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandTrunc() {#afa9926785ed5d084be598befc6263736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandTrunc (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, bool IsDouble, bool Is64FPU, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandUlh() {#a7e5200f8b225e93e2165e42e43c7eb39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandUlh (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, bool Signed, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandUncondBranchMMPseudo() {#af93e8f03eff7217371cbb7013467a8e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandUncondBranchMMPseudo (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandUsh() {#abb2892fc0f5917479be3b5d2df8fa384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandUsh (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### expandUxw() {#a3314f3ab8a8f0baa2ebc400d1f17faf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::expandUxw (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### getATReg() {#a2ac69606a72faa6fd9396f81466f8919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsAsmParser::getATReg (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the internal register number for the current AT.</p>


<p>Also checks if the current AT is unavailable (set to $0) and gives an error if it is. This should be used in pseudo-instruction expansions which need AT.</p>


<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### getReg() {#a044894054ade826eaf00a9f061d49693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsAsmParser::getReg (int RC, int RegNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### getTargetStreamer() {#aec8c6f7327237fb73d88758a0734ae2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsTargetStreamer &amp; anonymous{MipsAsmParser.cpp}::MipsAsmParser::getTargetStreamer ()</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### isPicAndNotNxxAbi() {#a9a6eae0029cc894b1e4481f5a099433f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::isPicAndNotNxxAbi ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### loadAndAddSymbolAddress() {#aa816aab0035b466d1621be3f3b292e16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::loadAndAddSymbolAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * SymExpr, unsigned DstReg, unsigned SrcReg, bool Is32BitSym, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### loadImmediate() {#a2b21a8419273a3a5600c4b3126a45cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::loadImmediate (int64_t ImmValue, unsigned DstReg, unsigned SrcReg, bool Is32BitImm, bool IsAddress, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Load (or add) an immediate into a register.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ImmValue</td>
<td class="doxyParamItemDescription"><p>The immediate to load.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DstReg</td>
<td class="doxyParamItemDescription"><p>The register that will hold the immediate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcReg</td>
<td class="doxyParamItemDescription"><p>A register to add to the immediate or Mips::NoRegister for a simple initialization.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Is32BitImm</td>
<td class="doxyParamItemDescription"><p>Is ImmValue 32-bit or 64-bit?</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsAddress</td>
<td class="doxyParamItemDescription"><p>True if the immediate represents an address. False if it is an integer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IDLoc</td>
<td class="doxyParamItemDescription"><p>Location of the immediate in the source file.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchACRegisterName() {#a265f34b23da0927f9dfb4b61a6f4b734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MipsAsmParser::matchACRegisterName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchAndEmitInstruction() {#a9b7ce11f80d66cb8929283c9ce394b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::matchAndEmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, unsigned &amp; Opcode, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, uint64_t &amp; ErrorInfo, bool MatchingInlineAsm)</td>
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

<p>Recognize a series of operands of a parsed instruction as an actual MCInst and emit it to the specified MCStreamer.</p>


<p>This returns false on success and returns true on failure to match.</p>


<p>On failure, the target parser is responsible for emitting a diagnostic explaining the match failure.</p>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchAnyRegisterNameWithoutDollar() {#a1b2caa3c30c2b189ae737e9fd52cc5fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MipsAsmParser::matchAnyRegisterNameWithoutDollar (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Identifier, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchAnyRegisterWithoutDollar() {#a847a0eb482ef2389b8bdb350a9b0c60f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MipsAsmParser::matchAnyRegisterWithoutDollar (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> &amp; Token, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchAnyRegisterWithoutDollar() {#a86bc6d294617025ffcba39706bbff635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MipsAsmParser::matchAnyRegisterWithoutDollar (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchCPURegisterName() {#a8a56643fb6abee5fee26725113200c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MipsAsmParser::matchCPURegisterName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchFCCRegisterName() {#aeec5b4525d2dfa79802cfc7428a7a11d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MipsAsmParser::matchFCCRegisterName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchFPURegisterName() {#ac4c0ae4b50a00f1a0bea9cb74f36e7bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MipsAsmParser::matchFPURegisterName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchHWRegsRegisterName() {#ac2b26225805cb9e7c8a05e613062951e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MipsAsmParser::matchHWRegsRegisterName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchMSA128CtrlRegisterName() {#ae60d6b0d40c9bb56b26a144598e6ca9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MipsAsmParser::matchMSA128CtrlRegisterName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### matchMSA128RegisterName() {#aefa4913c5b3a6a7fb3e08f140459eecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MipsAsmParser::matchMSA128RegisterName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### mnemonicIsValid() {#aa074f81f8252a05df84b602c18680ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::mnemonicIsValid (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemonic, unsigned VariantID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseAnyRegister() {#a8e458a48b209a63923e6d2ba02be9cfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MipsAsmParser::parseAnyRegister (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseBracketSuffix() {#ae123684b16e02da8ee5bcccc1bb355e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseBracketSuffix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sometimes (i.e.</p>


<p>in MSA) the operand may be followed immediately by either one of these. ::= '[', register, ']' ::= '[', integer, ']' handle it before we iterate so we don't get tripped up by the lack of a comma.</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirective() {#a927c6d2fc5a8123e0ff253ea54a37734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::ParseDirective (<a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> DirectiveID)</td>
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

<p>ParseDirective - Parse a target specific assembler directive This method is deprecated, use 'parseDirective' instead.</p>


<p>The parser is positioned following the directive name. The target specific directive parser should parse the entire directive doing or recording any target specific work, or return true and do nothing if the directive is not target specific. If the directive is specific for the target, the entire line is parsed up to and including the end-of-statement token and false is returned.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DirectiveID</td>
<td class="doxyParamItemDescription"><p>- the identifier token of the directive.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCpAdd() {#a8c8a9d68ccbd9cca8f9baa767b0719e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveCpAdd (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCpLoad() {#aed5b2663de90f158d66d4ebd8ac6e563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveCpLoad (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCpLocal() {#ac94192edbe3e311ac2aee4aa4218d55b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveCpLocal (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCpRestore() {#a782e23141551905c3306b8f6f3e330df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveCpRestore (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCPReturn() {#ab9a2120b9f55ba9758805117e8f9e793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveCPReturn ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveCPSetup() {#a187e407e9f580a72b388b16a530bf1ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveCPSetup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveDtpRelDWord() {#a2b61b13e9e0152ae84934c36a7fceaaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveDtpRelDWord ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveDtpRelDWord ::= .dtpreldword tls_sym</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveDtpRelWord() {#a61ed969bb0c5e1c87f7a2fd55a80b2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveDtpRelWord ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveDtpRelWord ::= .dtprelword tls_sym</p>

<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveGpDWord() {#a36a4026475dec860a397124ee828306b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveGpDWord ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveGpDWord ::= .gpdword local_sym</p>

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveGpWord() {#a283c780ef6d5ae515f4f31691f87bd82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveGpWord ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveGpWord ::= .gpword local_sym</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveModule() {#a8d18db6320cd4996efaf7f8023302a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveModule ::= .module oddspreg ::= .module nooddspreg ::= .module fp=value ::= .module softfloat ::= .module hardfloat ::= .module mt ::= .module crc ::= .module nocrc ::= .module virt ::= .module novirt ::= .module ginv ::= .module noginv</p>

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveModuleFP() {#a28b39632eba3fd0da113e20239a1a61d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveModuleFP ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveModuleFP ::= =32 ::= =xx ::= =64</p>

<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveNaN() {#adb69465a9e78660bbf8dd805e001bfd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveNaN ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveOption() {#af0fb0bbbad912849e5669f90811c3f5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveOption ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSet() {#afb0a48bd0b5ffbb804411ad77be002b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveTpRelDWord() {#a933d199e8dc55baf54fd79b3c905d68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveTpRelDWord ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveTpRelDWord ::= .tpreldword tls_sym</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveTpRelWord() {#aeb9163f10ae58f4fbc06797a59a8e5ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseDirectiveTpRelWord ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveTpRelWord ::= .tprelword tls_sym</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseFpABIValue() {#a2835de3e04e5cf236dd51664f443bca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseFpABIValue (<a href="/web-llvm/docs/api/structs/llvm/mipsabiflagssection/#abace76eb927d4f67287e6fe14b80b427">MipsABIFlagsSection::FpABIKind</a> &amp; FpABI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseImm() {#a1a5011bdb951ba8f695ed702f248452e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus anonymous{MipsAsmParser.cpp}::MipsAsmParser::parseImm (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseInsnDirective() {#a4a7a7935b88cf566d4a8cf4345860c5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseInsnDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseInsnDirective ::= .insn</p>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseInstruction() {#a077824f58c9e845e84f0f2cf050a943c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseInstruction (<a href="/web-llvm/docs/api/structs/llvm/parseinstructioninfo">ParseInstructionInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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

<p>Parse one assembly instruction.</p>


<p>The parser is positioned following the instruction name. The target specific instruction parser should parse the entire instruction and construct the appropriate MCInst, or emit an error. On success, the entire line should be parsed up to and including the end-of-statement token. On failure, the parser is not required to read to the end of the line.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The instruction name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLoc</td>
<td class="doxyParamItemDescription"><p>- The source location of the name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Operands</td>
<td class="doxyParamItemDescription"><p>[out] - The list of parsed operands, this returns ownership of them to the caller.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on failure.</p></dd>
</dl>


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseInternalDirectiveReallowModule() {#af1c5f86fb915e0ff7c615ac11698e9ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseInternalDirectiveReallowModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseInvNum() {#a8f1e8637d1708545d998dc6ceb2c4584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MipsAsmParser::parseInvNum (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseJumpTarget() {#a95fb3130367d4e5fbedd59513e1dc991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MipsAsmParser::parseJumpTarget (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseMemOffset() {#a18044571d5e7d324b9c913246a8567cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseMemOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, bool isParenExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseMemOperand() {#a6e3f5155a9fdec8988eee087419fb0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MipsAsmParser::parseMemOperand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseOperand() {#ade1a046fe264c33e5926c6433dc8b746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseOperand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Mnemonic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseParenSuffix() {#ac2632f17531ad3348eb64b2dd59a793c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseParenSuffix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sometimes (i.e.</p>


<p>load/stores) the operand may be followed immediately by either this. ::= '(', register, ')' handle it before we iterate so we don't get tripped up by the lack of a comma.</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseRegister() {#a36f9242c0c9f87ff75fcac3b41575c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>Parse a register as used in CFI directives.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseRegisterList() {#a2e68e57ed9af34672256bed0a4a0d176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MipsAsmParser::parseRegisterList (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseRSectionDirective() {#a79efeb36093fdd82e27d9679909cee84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseRSectionDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseRSectionDirective ::= .rdata</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetArchDirective() {#aa0f6ea5e72a31b24678d87af4c96f552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetArchDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetAssignment() {#a1202893f3ad90cf0314829897773d4df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetAssignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetAtDirective() {#a70e3e8bdbec41d52a2617ebbfa26f104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetAtDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetFeature() {#aa34cdf2fb2689296d9ad082ccc701618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetFeature (uint64_t Feature)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetFpDirective() {#a79ff48b0ac1245470be8d69f876805cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetFpDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetHardFloatDirective() {#a129337e909b576f426e6632cead3be16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetHardFloatDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetMacroDirective() {#a17a800743c47bdb61dd32de9ac0f5fcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetMacroDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetMips0Directive() {#ac6ab616dc3e3d1cb9a278f78b78e42f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetMips0Directive ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetMips16Directive() {#a1b3dbaab23d42c5a75f9dd3762ef092a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetMips16Directive ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetMsaDirective() {#af3b5a1c12a951d092ae177677355093a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetMsaDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetMtDirective() {#a0c8abc1bdaea4bfaa8ee7dc22911615f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetMtDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoAtDirective() {#a42768c0c11572cbf6489fa90e9b766e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoAtDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoCRCDirective() {#a690aab6011276e8102150a8fae1680dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoCRCDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoDspDirective() {#ad3cabb232c6fe93d86e9ad24db7a516d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoDspDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoGINVDirective() {#a10df9679d46d858984228cf77c006387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoGINVDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoMacroDirective() {#a1a61f6a742fe819653f27a8a2d2b68ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoMacroDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoMips16Directive() {#a58fe47bc833d49bfcfcf00b0475f6b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoMips16Directive ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoMips3DDirective() {#a41a225a37abc608b3db0afd3f501191a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoMips3DDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoMsaDirective() {#a7649e9b3a8f03b3b513e8b534bef2b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoMsaDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoMtDirective() {#a66917d68435b8f7328b4d910fed59365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoMtDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoOddSPRegDirective() {#a8cd498157701e08bbb25a7140e8ad82f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoOddSPRegDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoReorderDirective() {#a9403606d5d4a1f0ee90d292d4452ea1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoReorderDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetNoVirtDirective() {#a6998d4cba0966938f2ae9784728f47bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetNoVirtDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetOddSPRegDirective() {#a9fada66382f9d8442f42e9edef060250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetOddSPRegDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetPopDirective() {#a53b558fcbb772ac18b4c92115ef524bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetPopDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetPushDirective() {#a6e41c9decf0f396063dffb54b9c348c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetPushDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetReorderDirective() {#a124cd8624102bbafc19b391f87f3e591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetReorderDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSetSoftFloatDirective() {#a1fafbf62257a9d3db9d5222f3eb57da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSetSoftFloatDirective ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### parseSSectionDirective() {#a45b4967aadd0a776cd192d8416495d9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::parseSSectionDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, unsigned Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseSSectionDirective ::= .sbss ::= .sdata</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### printWarningWithFixIt() {#ab24464a6370e0a570dc0234e7cbc719c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsAsmParser::printWarningWithFixIt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; FixMsg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range, bool ShowColors=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### processInstruction() {#a12a0a116d8357670ba75a1ce0958759b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::processInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### reportParseError() {#a9a0bfd96034bc491d3394e3997c9c106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::reportParseError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrorMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### reportParseError() {#ae428f3920c26fb06d248ddba230cc0cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::reportParseError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrorMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### searchSymbolAlias() {#ac6ba30d5df0749190fe7ef82a39c1740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsAsmParser::searchSymbolAlias (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### selectArch() {#ad732510c581158cbb7ebbb8bd0a5eb9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MipsAsmParser.cpp}::MipsAsmParser::selectArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchFeature)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### setFeatureBits() {#a5e638c898a10b5abcebc918b5c6ae88a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MipsAsmParser.cpp}::MipsAsmParser::setFeatureBits (uint64_t Feature, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FeatureString)</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### setModuleFeatureBits() {#a28f783070645835799f29ab322c2b62a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MipsAsmParser.cpp}::MipsAsmParser::setModuleFeatureBits (uint64_t Feature, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FeatureString)</td>
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



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### tryExpandInstruction() {#ab6b37d14640640310c45c8cede887b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsAsmParser::MacroExpanderResultTy MipsAsmParser::tryExpandInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### tryParseRegister() {#a41ce1e3216973844f0d7a6225dfca14e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus MipsAsmParser::tryParseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>tryParseRegister - parse one register if possible</p>


<p>Check whether a register specification can be parsed at the current location, without failing the entire parse if it can't. Must not consume tokens if the parse fails.</p>


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### validateMSAIndex() {#a812b76c8a744159214eb59a320e71673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::validateMSAIndex (int Val, int RegKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ABI {#a0d46cc26a1352a40ecf2b74b446ac2a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsABIInfo anonymous{MipsAsmParser.cpp}::MipsAsmParser::ABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### AssemblerOptions {#a748bcbbe1da0340bc6a61e0f8a067197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;MipsAssemblerOptions&gt;, 2&gt; anonymous{MipsAsmParser.cpp}::MipsAsmParser::AssemblerOptions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### CpRestoreOffset {#a03659a3443b146d6d359c54c06a002cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{MipsAsmParser.cpp}::MipsAsmParser::CpRestoreOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### CpSaveLocation {#aec16d9c9d499fb09d7d4502904824e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MipsAsmParser.cpp}::MipsAsmParser::CpSaveLocation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### CpSaveLocationIsRegister {#a0a7dcd9e979dacec662fc1be078f8a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::CpSaveLocationIsRegister</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, then CpSaveLocation is a register, otherwise it's an offset.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### CurForbiddenSlotAttr {#a755008f391b4778d02df40aa77d813c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::CurForbiddenSlotAttr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### CurrentFn {#a72697300adb432a2861ca52e02c37015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* anonymous{MipsAsmParser.cpp}::MipsAsmParser::CurrentFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### GPReg {#ae31d5b0c72a63d693347f59a447e7cb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MipsAsmParser.cpp}::MipsAsmParser::GPReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### IsCpRestoreSet {#ab8b520780336cdb335541dcc71049a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::IsCpRestoreSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### IsLittleEndian {#afe0320d4066b0db98f4520795c2c8f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::IsLittleEndian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### IsPicEnabled {#af93d90480ea5a2c30560e6200577049d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsAsmParser.cpp}::MipsAsmParser::IsPicEnabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

### RegisterSets {#a5fc654be0b70b5cc77422ca7f33bc4cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;AsmToken&gt; anonymous{MipsAsmParser.cpp}::MipsAsmParser::RegisterSets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp">MipsAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
