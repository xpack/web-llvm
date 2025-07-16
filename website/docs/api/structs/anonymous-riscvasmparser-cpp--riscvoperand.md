---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-riscvasmparser-cpp-/riscvoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RISCVOperand` Struct Reference

<p><a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> - Instances of this class represent a parsed machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{RISCVAsmParser.cpp}::RISCVOperand { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a> - This abstract class represents a source-level assembly instruction operand. <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#aa9202fc0701ef2e6259785f73081d8ae">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc72e7198ffd2124971f65d993f0ecf">RISCVOperand</a> (KindTy K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a> (const RISCVOperand &amp;o)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09729766c665aa84cb453c72112b562b">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#a09729766c665aa84cb453c72112b562b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f74b84e50bbdb46303e4f537ef46a95">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#a2f74b84e50bbdb46303e4f537ef46a95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e5be37a834e42f278fd02f4c1e49ae">isV0Reg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc38af9f8bf1904f5e95b7af5cc4b3c">isAnyReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7046735c047f11553ce3716cc90e2fc">isAnyRegC</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f45b5c592823a5ca093f3475569065">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#af5f45b5c592823a5ca093f3475569065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a969a8d61305379d126f02a5e5c0769e6">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#a969a8d61305379d126f02a5e5c0769e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaa68359051f29a1499f6715c7ca952b">isSystemRegister</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad204a1a19d9668609652c527d0403037">isRegReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8feadbc213297463f9dc650e00f763d">isRlist</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00e7f3cfa5c4ee1b300d621c786e5e0">isSpimm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86c3d46f4298d1d52cb1a72320d8fe6">isGPR</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acee60d11c2387d3b7b42d9ef5d31bdf1">isGPRPair</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a497847b31bb15c186b5613adec4846fd">isGPRF16</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc08f8bfe7e4a35ed1834acb44e4ee9b">isGPRF32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41fa64dc342c50433433d2a502fc82a">isGPRAsFPR</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd3d20ef6dd1e1d4130a13e05a580fee">isGPRAsFPR16</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace8fe8916afb3ef41e8dfda82c123440">isGPRAsFPR32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f90ca97b27f1d2539b50874f4c2981">isGPRPairAsFPR64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8502fc60d43c787f067cf0a3d3aed2e">isBareSymbol</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5042f1f9092dd0215e831229e55f8ebd">isCallSymbol</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5b91c95fad7d6be2b9fbab33610982">isPseudoJumpSymbol</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0a8adb97fa110f25f96b03c0ddc590">isTPRelAddSymbol</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfccb31cfbda65ecc1f98d308df407d2">isTLSDESCCallSymbol</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5acd6bf8266660157be23d9ca1e28af7">isCSRSystemRegister</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e51b20075aca7e72c747ebe4ce625b9">isVTypeImm</a> (unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ffcfa61f8429e10911f920e8aa16db">isVTypeI10</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077dff4c4b4290b14e1ba95976bae56d">isVTypeI11</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ebb39dac8dee5b668ccf6ad46893c35">isFenceArg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the operand is a valid for the fence instruction e.g. <a href="#a1ebb39dac8dee5b668ccf6ad46893c35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e04c381c74c4fee94660003f8822fb0">isFRMArg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the operand is a valid floating point rounding mode. <a href="#a8e04c381c74c4fee94660003f8822fb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168c93f6e1a2b274a3eb7057aa12d0e3">isFRMArgLegacy</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a111f6373dc343ca036d335dd93a235a6">isRTZArg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b07c2d3b33166b642509347647acee">isLoadFPImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the operand is a valid fli.s floating-point immediate. <a href="#a65b07c2d3b33166b642509347647acee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a791d6b93becfa0221371554c45053e">isImmXLenLI</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45cda9866fff2598a0fbf13fc2c21735">isImmXLenLI_Restricted</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea5baf20e0a1c77c77df4d599153e89">isUImmLog2XLen</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c60dd71c23660c5f1f1a94b7f53137f">isUImmLog2XLenNonZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f60201ed3b2c549f06fc69bb4e688be">isUImmLog2XLenHalf</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316d511c200bac1e4e0d18a1009d6cab">isUImm1</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c250b5d116f388a711ce211a640838">isUImm2</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08c1d77dbe7a9ab3a1bf0374fb38a15">isUImm3</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa82a6816f6ecd588b43f3f2576112c">isUImm4</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a514caca686644c2ad0d73f870a96d27f">isUImm5</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4fa244442c32b92368f06b00f4d0505">isUImm6</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c3daaef61115d7d51eed9d7fdbb2b36">isUImm7</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b7708ea704dc781ec8a1316a802ce25">isUImm8</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb05c3b557b8e1e0b46a9886b42f7d80">isUImm10</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454427509663610a20e658b289a2ba00">isUImm11</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf02e5ad5c0d88a3e0516f894ff9d947">isUImm16</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e90af5538eb25666bf7d659bcf41ba5">isUImm20</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2e624f6eabe05032b1d7ef020ad6e6">isUImm32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48fca9aad0177b9539cb543a8ce683e7">isUImm48</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b7716db3ddc0347dda99d61e925d753">isUImm64</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae99db1ae2ce5a2b14538903fed4cffdc">isUImm5NonZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d8c7238cf9ac3ee71e1bff04885275c">isUImm5GT3</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a26a869a59be9ae11a98d9129fd331f">isUImm8GE32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c72952eddffc0cf8c0f301f9f75f9b">isRnumArg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d26cbdd8ca30a5d98afb728360f974c">isRnumArg_0_7</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ad881e8c2b8a510e90ae491602b8a7">isRnumArg_1_10</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d069740c7a0135792efbcfc07dfb574">isRnumArg_2_14</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc37984bc54744b905e01edc0b594beb">isSImm5</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad01a2bf5a8b48c76149ee03417626e12">isSImm6</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af949c7bbac35f257efa40174d553af">isSImm6NonZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfbb6e70817ddf44c690c812da1d300c">isCLUIImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311a899eaec9b7e7e0ecc3bcdb03bc92">isUImm2Lsb0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afecb01e5f389e34cb6ff2193d429b50b">isUImm5Lsb0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d5778b8d84d190f64085c330c49206">isUImm6Lsb0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accf08f0dc52b404b10f854884408cb43">isUImm7Lsb00</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2784f59f188a8c871a9f0b30c87c925">isUImm7Lsb000</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b303f3378e4f430ff52c7520317f7ed">isUImm8Lsb00</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b9f96bd235d2600a144430d35a2663">isUImm8Lsb000</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ede124eb449bccb57da5089795ead1">isSImm9Lsb0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b003806c09ef35d160cfdb9a2865ff5">isUImm9Lsb000</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40ce5b912f81fa907dc15a8fe418c50">isUImm10Lsb00NonZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af093f69b028595df33edd1202e0cbc52">isSImm12</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac919a38328c27eb6be9a981a93892a0b">isSImm12Lsb0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d77a04edcf0d4f6922b7588617bfdd">isSImm12Lsb00000</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f413b3dbb8145b1fbc25107f688f02a">isSImm13Lsb0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a881b29a20a1d8eb1ff76ee27c79ce4de">isSImm10Lsb0000NonZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafcf3c2bb5b0550a74203b0c15648681">isUImm20LUI</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7941ccc7f7bc6d6f518e1db11e581b9d">isUImm20AUIPC</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6ca848fcaf79620c6535ed2c92f1c7">isSImm21Lsb0JAL</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1505168c2edbb91f93e80adc33c2d604">isImmZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea18d9f8d1a819e45efc723be71dcb8">isSImm5Plus1</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe1704021f6026752f84192211fe503">isSImm26</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100c560a19a7ac5f1c4de5a92fb70f6a">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Gets location of the first token of this operand <a href="#a100c560a19a7ac5f1c4de5a92fb70f6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd210eb3e7dcd6d418f1642d9f9d8401">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Gets location of the last token of this operand <a href="#acd210eb3e7dcd6d418f1642d9f9d8401">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this operand is for an RV64 instruction. <a href="#ac8063e11349812b98b26251397f174af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e2290cbf87a82c3fa1825dd701b706">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad56a0381360ef39001884ebf5c9920b">getSysReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3105a33a236d9b9f471664f593b0d5da">getFPConst</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5807533b5f320ca7716b348fc210169c">getToken</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7696e2ed10c27a39a03144f36a21ddc4">getVType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscvfprndmode/#a9214a4f7f7322f485189dd3726776b76">RISCVFPRndMode::RoundingMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa66ed9ade9605bccd73d410447380456">getFRM</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa25790c6806f48a3be471a2e4228616a">getFence</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a8ec62f78c00b33f2cfe5c531366f9">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433c5deedfe24ee94256da5a3021aa19">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b37da283ebf9ecc9ef3b8468b9569d">addFPImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab805d2778c683124cc4241c4ae522e">addFenceArgOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5cd5faa882cb075d2cd166a3cd3222">addCSRSystemRegisterOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5515c4f1f3e9f0e04e83a787020af209">addVTypeIOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18328b40cba50468c5a380fb0d86eeb">addRlistOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7c494c84693e0715097e5d9bc23c31">addRegRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd3aa898829c8a5af0f9f8b6c0b369f">addSpimmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852817cd2a9f95112d0f01374ddc156f">addFRMArgOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{RISCVAsmParser.cpp}<a href="#aa9202fc0701ef2e6259785f73081d8ae">::RISCVOperand::KindTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ccbbcdb3901f28502979e9a0f0ab72">StartLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d5a78f43db087f0be5f959a8c7f07b2">EndLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13263d18f2fae75e479e3cfcc04951d">Tok</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/regop">RegOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/immop">ImmOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/fpimmop">FPImmOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e24bdd3d976ab7d7c8f91373f2a409">FPImm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83b10ce54e91c160fe427a9deb9ecb1">SysReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea97031fa9df60c20a21f9cc8bdfbaa">VType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf81c000ce9b2d98a4c581adf48ed648">FRM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb6b7d8aa5881b56351cfda55a945cf2">Fence</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dda8a2dae54cade391e067430b856e1">Rlist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec175f6124fde7360b4e4c5f54e7ab68">Spimm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b7409bbebe1ed20beb3ea7d78c2f37c">RegReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{RISCVAsmParser.cpp}<a href="#a9fc72e7198ffd2124971f65d993f0ecf">::RISCVOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af5f59b367bd03c3fb3c0f0adbe01c4"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a> (const MCExpr *Expr, int64_t &amp;Imm, RISCVMCExpr::VariantKind &amp;VK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a> (int64_t Imm, bool IsRV64Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e549ead0c31b1e6180ef2d52813a6dd">createToken</a> (StringRef Str, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1969d66edd578a4de9321c1acd08d7b9">createReg</a> (MCRegister Reg, SMLoc S, SMLoc E, bool IsGPRAsFPR=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86e438c1f518ace583bc6645628ccc32">createImm</a> (const MCExpr *Val, SMLoc S, SMLoc E, bool IsRV64)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82719125b54cd9a449e8bcde8c69f77f">createFPImm</a> (uint64_t Val, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb1440e5c9ed8cf3b8e6366e413d51c">createSysReg</a> (StringRef Str, SMLoc S, unsigned Encoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9187bd16dbf70135d4afc96c5f1d282e">createFRMArg</a> (RISCVFPRndMode::RoundingMode FRM, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7319b975a79be450e87e210ad5755374">createFenceArg</a> (unsigned Val, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a801d4f6598c5e9c7224e8df654e40003">createVType</a> (unsigned VTypeI, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a016456ae72f5c5044229196ffc301ebf">createRlist</a> (unsigned RlistEncode, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316f3c138ccbe02af7c5e13e1b711b87">createRegReg</a> (MCRegister Reg1, MCRegister Reg2, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a20a4ebf74cf0cd35abd08b6f53405">createSpimm</a> (unsigned Spimm, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6762c005d2c4f50e2ba59d9cdab146a5">addExpr</a> (MCInst &amp;Inst, const MCExpr *Expr, bool IsRV64Imm)</td>
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

<p><a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> - Instances of this class represent a parsed machine instruction.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### KindTy {#aa9202fc0701ef2e6259785f73081d8ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{RISCVAsmParser.cpp}::RISCVOperand::KindTy </td>
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
<td class="doxyEnumItemName">Token<a id="aa9202fc0701ef2e6259785f73081d8aea459a6f79ad9b13cbcb5f692d2cc7a94d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Immediate<a id="aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPImmediate<a id="aa9202fc0701ef2e6259785f73081d8aeae3d8da4503ba8c447d522a9194b008c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SystemRegister<a id="aa9202fc0701ef2e6259785f73081d8aea02a594430be99850ee772aa87474ffd6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VType<a id="aa9202fc0701ef2e6259785f73081d8aea40f97061ec443f48b610108eb6b10220"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRM<a id="aa9202fc0701ef2e6259785f73081d8aea83445ea5183d15511eeaa89336af0d91"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Fence<a id="aa9202fc0701ef2e6259785f73081d8aeafa1124a61230804809a9b5fc57932b40"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Rlist<a id="aa9202fc0701ef2e6259785f73081d8aea783428a7e222d726ca55e7aa6a232977"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Spimm<a id="aa9202fc0701ef2e6259785f73081d8aea96de0d3240f0de846f0d4d86ae41ec92"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegReg<a id="aa9202fc0701ef2e6259785f73081d8aea546839a5c4bcf9f9450967155f48de41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RISCVOperand() {#a9fc72e7198ffd2124971f65d993f0ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVAsmParser.cpp}::RISCVOperand::RISCVOperand (<a href="#aa9202fc0701ef2e6259785f73081d8ae">KindTy</a> K)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>


<p>Referenced by <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### RISCVOperand() {#afb5400c33634bafb22f22c263e55d9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVAsmParser.cpp}::RISCVOperand::RISCVOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand">RISCVOperand</a> &amp; o)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a4d5a78f43db087f0be5f959a8c7f07b2">EndLoc</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aeafa1124a61230804809a9b5fc57932b40">Fence</a>, <a href="#a77e24bdd3d976ab7d7c8f91373f2a409">FPImm</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aeae3d8da4503ba8c447d522a9194b008c9">FPImmediate</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea83445ea5183d15511eeaa89336af0d91">FRM</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1">Immediate</a>, <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a116eebce8e7768c60749aa19af77f817">llvm::MCParsedAsmOperand::MCParsedAsmOperand</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea546839a5c4bcf9f9450967155f48de41">RegReg</a>, <a href="#a9fc72e7198ffd2124971f65d993f0ecf">RISCVOperand</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea783428a7e222d726ca55e7aa6a232977">Rlist</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea96de0d3240f0de846f0d4d86ae41ec92">Spimm</a>, <a href="#ad8ccbbcdb3901f28502979e9a0f0ab72">StartLoc</a>, <a href="#ac83b10ce54e91c160fe427a9deb9ecb1">SysReg</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea02a594430be99850ee772aa87474ffd6">SystemRegister</a>, <a href="#af13263d18f2fae75e479e3cfcc04951d">Tok</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea459a6f79ad9b13cbcb5f692d2cc7a94d">Token</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea40f97061ec443f48b610108eb6b10220">VType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCSRSystemRegisterOperands() {#afd5cd5faa882cb075d2cd166a3cd3222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addCSRSystemRegisterOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ac83b10ce54e91c160fe427a9deb9ecb1">SysReg</a>.</p>

</div>
</div>

### addFenceArgOperands() {#aaab805d2778c683124cc4241c4ae522e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFenceArgOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#abb6b7d8aa5881b56351cfda55a945cf2">Fence</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addFPImmOperands() {#a72b37da283ebf9ecc9ef3b8468b9569d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFPImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a6762c005d2c4f50e2ba59d9cdab146a5">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a3105a33a236d9b9f471664f593b0d5da">getFPConst</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addFRMArgOperands() {#a852817cd2a9f95112d0f01374ddc156f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFRMArgOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#aa66ed9ade9605bccd73d410447380456">getFRM</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmOperands() {#a433c5deedfe24ee94256da5a3021aa19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a6762c005d2c4f50e2ba59d9cdab146a5">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#ab2a8ec62f78c00b33f2cfe5c531366f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegRegOperands() {#a1c7c494c84693e0715097e5d9bc23c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addRegRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a4b7409bbebe1ed20beb3ea7d78c2f37c">RegReg</a>.</p>

</div>
</div>

### addRlistOperands() {#af18328b40cba50468c5a380fb0d86eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addRlistOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a4dda8a2dae54cade391e067430b856e1">Rlist</a>.</p>

</div>
</div>

### addSpimmOperands() {#a2cd3aa898829c8a5af0f9f8b6c0b369f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addSpimmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#aec175f6124fde7360b4e4c5f54e7ab68">Spimm</a>.</p>

</div>
</div>

### addVTypeIOperands() {#a5515c4f1f3e9f0e04e83a787020af209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addVTypeIOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 1310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a7696e2ed10c27a39a03144f36a21ddc4">getVType</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1">Immediate</a>, <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### getEndLoc() {#acd210eb3e7dcd6d418f1642d9f9d8401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{RISCVAsmParser.cpp}::RISCVOperand::getEndLoc ()</td>
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

<p>getEndLoc - Gets location of the last token of this operand</p>

<p>Definition at line 1062 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#a4d5a78f43db087f0be5f959a8c7f07b2">EndLoc</a>.</p>

</div>
</div>

### getFence() {#aa25790c6806f48a3be471a2e4228616a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVAsmParser.cpp}::RISCVOperand::getFence ()</td>
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



<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aeafa1124a61230804809a9b5fc57932b40">Fence</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>


<p>Referenced by <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a>.</p>

</div>
</div>

### getFPConst() {#a3105a33a236d9b9f471664f593b0d5da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{RISCVAsmParser.cpp}::RISCVOperand::getFPConst ()</td>
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



<p>Definition at line 1084 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a77e24bdd3d976ab7d7c8f91373f2a409">FPImm</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aeae3d8da4503ba8c447d522a9194b008c9">FPImmediate</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>


<p>Referenced by <a href="#a72b37da283ebf9ecc9ef3b8468b9569d">addFPImmOperands</a> and <a href="#a65b07c2d3b33166b642509347647acee">isLoadFPImm</a>.</p>

</div>
</div>

### getFRM() {#aa66ed9ade9605bccd73d410447380456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVFPRndMode::RoundingMode anonymous{RISCVAsmParser.cpp}::RISCVOperand::getFRM ()</td>
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



<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea83445ea5183d15511eeaa89336af0d91">FRM</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>


<p>Referenced by <a href="#a852817cd2a9f95112d0f01374ddc156f">addFRMArgOperands</a> and <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a>.</p>

</div>
</div>

### getImm() {#a46c5cbdee2f5b53138baa9bb106305bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{RISCVAsmParser.cpp}::RISCVOperand::getImm ()</td>
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



<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1">Immediate</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>


<p>Referenced by <a href="#a72b37da283ebf9ecc9ef3b8468b9569d">addFPImmOperands</a>, <a href="#a433c5deedfe24ee94256da5a3021aa19">addImmOperands</a>, <a href="#a5515c4f1f3e9f0e04e83a787020af209">addVTypeIOperands</a>, <a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a>, <a href="#ac8502fc60d43c787f067cf0a3d3aed2e">isBareSymbol</a>, <a href="#a5042f1f9092dd0215e831229e55f8ebd">isCallSymbol</a>, <a href="#adfbb6e70817ddf44c690c812da1d300c">isCLUIImm</a>, <a href="#a9a791d6b93becfa0221371554c45053e">isImmXLenLI</a>, <a href="#a45cda9866fff2598a0fbf13fc2c21735">isImmXLenLI_Restricted</a>, <a href="#a1505168c2edbb91f93e80adc33c2d604">isImmZero</a>, <a href="#afd5b91c95fad7d6be2b9fbab33610982">isPseudoJumpSymbol</a>, <a href="#a33c72952eddffc0cf8c0f301f9f75f9b">isRnumArg</a>, <a href="#a6d26cbdd8ca30a5d98afb728360f974c">isRnumArg_0_7</a>, <a href="#ae0ad881e8c2b8a510e90ae491602b8a7">isRnumArg_1_10</a>, <a href="#a7d069740c7a0135792efbcfc07dfb574">isRnumArg_2_14</a>, <a href="#a881b29a20a1d8eb1ff76ee27c79ce4de">isSImm10Lsb0000NonZero</a>, <a href="#af093f69b028595df33edd1202e0cbc52">isSImm12</a>, <a href="#aa0d77a04edcf0d4f6922b7588617bfdd">isSImm12Lsb00000</a>, <a href="#adfe1704021f6026752f84192211fe503">isSImm26</a>, <a href="#afc37984bc54744b905e01edc0b594beb">isSImm5</a>, <a href="#abea18d9f8d1a819e45efc723be71dcb8">isSImm5Plus1</a>, <a href="#ad01a2bf5a8b48c76149ee03417626e12">isSImm6</a>, <a href="#a6af949c7bbac35f257efa40174d553af">isSImm6NonZero</a>, <a href="#acfccb31cfbda65ecc1f98d308df407d2">isTLSDESCCallSymbol</a>, <a href="#afc0a8adb97fa110f25f96b03c0ddc590">isTPRelAddSymbol</a>, <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>, <a href="#ad40ce5b912f81fa907dc15a8fe418c50">isUImm10Lsb00NonZero</a>, <a href="#a7941ccc7f7bc6d6f518e1db11e581b9d">isUImm20AUIPC</a>, <a href="#aafcf3c2bb5b0550a74203b0c15648681">isUImm20LUI</a>, <a href="#a311a899eaec9b7e7e0ecc3bcdb03bc92">isUImm2Lsb0</a>, <a href="#a9d8c7238cf9ac3ee71e1bff04885275c">isUImm5GT3</a>, <a href="#afecb01e5f389e34cb6ff2193d429b50b">isUImm5Lsb0</a>, <a href="#ae99db1ae2ce5a2b14538903fed4cffdc">isUImm5NonZero</a>, <a href="#ac2d5778b8d84d190f64085c330c49206">isUImm6Lsb0</a>, <a href="#accf08f0dc52b404b10f854884408cb43">isUImm7Lsb00</a>, <a href="#ac2784f59f188a8c871a9f0b30c87c925">isUImm7Lsb000</a>, <a href="#a2a26a869a59be9ae11a98d9129fd331f">isUImm8GE32</a>, <a href="#a2b303f3378e4f430ff52c7520317f7ed">isUImm8Lsb00</a>, <a href="#a27b9f96bd235d2600a144430d35a2663">isUImm8Lsb000</a>, <a href="#a8b003806c09ef35d160cfdb9a2865ff5">isUImm9Lsb000</a>, <a href="#a8ea5baf20e0a1c77c77df4d599153e89">isUImmLog2XLen</a>, <a href="#a6f60201ed3b2c549f06fc69bb4e688be">isUImmLog2XLenHalf</a>, <a href="#a6c60dd71c23660c5f1f1a94b7f53137f">isUImmLog2XLenNonZero</a>, <a href="#a6e51b20075aca7e72c747ebe4ce625b9">isVTypeImm</a> and <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a>.</p>

</div>
</div>

### getReg() {#ac3e2290cbf87a82c3fa1825dd701b706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{RISCVAsmParser.cpp}::RISCVOperand::getReg ()</td>
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



<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>

</div>
</div>

### getStartLoc() {#a100c560a19a7ac5f1c4de5a92fb70f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{RISCVAsmParser.cpp}::RISCVOperand::getStartLoc ()</td>
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

<p>getStartLoc - Gets location of the first token of this operand</p>

<p>Definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad8ccbbcdb3901f28502979e9a0f0ab72">StartLoc</a>.</p>

</div>
</div>

### getSysReg() {#aad56a0381360ef39001884ebf5c9920b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{RISCVAsmParser.cpp}::RISCVOperand::getSysReg ()</td>
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



<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#ac83b10ce54e91c160fe427a9deb9ecb1">SysReg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea02a594430be99850ee772aa87474ffd6">SystemRegister</a>.</p>


<p>Referenced by <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a>.</p>

</div>
</div>

### getToken() {#a5807533b5f320ca7716b348fc210169c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{RISCVAsmParser.cpp}::RISCVOperand::getToken ()</td>
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



<p>Definition at line 1089 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#af13263d18f2fae75e479e3cfcc04951d">Tok</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea459a6f79ad9b13cbcb5f692d2cc7a94d">Token</a>.</p>


<p>Referenced by <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a>.</p>

</div>
</div>

### getVType() {#a7696e2ed10c27a39a03144f36a21ddc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RISCVAsmParser.cpp}::RISCVOperand::getVType ()</td>
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



<p>Definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea40f97061ec443f48b610108eb6b10220">VType</a>.</p>


<p>Referenced by <a href="#a5515c4f1f3e9f0e04e83a787020af209">addVTypeIOperands</a> and <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a>.</p>

</div>
</div>

### isAnyReg() {#aefc38af9f8bf1904f5e95b7af5cc4b3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isAnyReg ()</td>
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



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>

</div>
</div>

### isAnyRegC() {#ad7046735c047f11553ce3716cc90e2fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isAnyRegC ()</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>

</div>
</div>

### isBareSimmNLsb0() {#a0f7cfaa1c472b36c995d6f95d9321e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isBareSimmNLsb0 ()</td>
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



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>


<p>Referenced by <a href="#ac919a38328c27eb6be9a981a93892a0b">isSImm12Lsb0</a>, <a href="#a5f413b3dbb8145b1fbc25107f688f02a">isSImm13Lsb0</a>, <a href="#abc6ca848fcaf79620c6535ed2c92f1c7">isSImm21Lsb0JAL</a> and <a href="#aa8ede124eb449bccb57da5089795ead1">isSImm9Lsb0</a>.</p>

</div>
</div>

### isBareSymbol() {#ac8502fc60d43c787f067cf0a3d3aed2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isBareSymbol ()</td>
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



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isCallSymbol() {#a5042f1f9092dd0215e831229e55f8ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isCallSymbol ()</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6aa4478c3f29a4ad6e0fe8e721c821c476">llvm::RISCVMCExpr::VK_RISCV_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a7f0a2ade0160be4082351dd594bfab25">llvm::RISCVMCExpr::VK_RISCV_CALL_PLT</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isCLUIImm() {#adfbb6e70817ddf44c690c812da1d300c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isCLUIImm ()</td>
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



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isCSRSystemRegister() {#a5acd6bf8266660157be23d9ca1e28af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isCSRSystemRegister ()</td>
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



<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#adaa68359051f29a1499f6715c7ca952b">isSystemRegister</a>.</p>

</div>
</div>

### isFenceArg() {#a1ebb39dac8dee5b668ccf6ad46893c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isFenceArg ()</td>
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

<p>Return true if the operand is a valid for the fence instruction e.g.</p>


<p>('iorw').</p>


<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#aa9202fc0701ef2e6259785f73081d8aeafa1124a61230804809a9b5fc57932b40">Fence</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>

</div>
</div>

### isFRMArg() {#a8e04c381c74c4fee94660003f8822fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isFRMArg ()</td>
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

<p>Return true if the operand is a valid floating point rounding mode.</p>

<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#aa9202fc0701ef2e6259785f73081d8aea83445ea5183d15511eeaa89336af0d91">FRM</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>


<p>Referenced by <a href="#a111f6373dc343ca036d335dd93a235a6">isRTZArg</a>.</p>

</div>
</div>

### isFRMArgLegacy() {#a168c93f6e1a2b274a3eb7057aa12d0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isFRMArgLegacy ()</td>
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



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#aa9202fc0701ef2e6259785f73081d8aea83445ea5183d15511eeaa89336af0d91">FRM</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>

</div>
</div>

### isGPR() {#ae86c3d46f4298d1d52cb1a72320d8fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isGPR ()</td>
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



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>


<p>Referenced by <a href="#ac41fa64dc342c50433433d2a502fc82a">isGPRAsFPR</a>.</p>

</div>
</div>

### isGPRAsFPR() {#ac41fa64dc342c50433433d2a502fc82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isGPRAsFPR ()</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#ae86c3d46f4298d1d52cb1a72320d8fe6">isGPR</a> and <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a>.</p>

</div>
</div>

### isGPRAsFPR16() {#abd3d20ef6dd1e1d4130a13e05a580fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isGPRAsFPR16 ()</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a497847b31bb15c186b5613adec4846fd">isGPRF16</a> and <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a>.</p>

</div>
</div>

### isGPRAsFPR32() {#ace8fe8916afb3ef41e8dfda82c123440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isGPRAsFPR32 ()</td>
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



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#adc08f8bfe7e4a35ed1834acb44e4ee9b">isGPRF32</a> and <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a>.</p>

</div>
</div>

### isGPRF16() {#a497847b31bb15c186b5613adec4846fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isGPRF16 ()</td>
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



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>


<p>Referenced by <a href="#abd3d20ef6dd1e1d4130a13e05a580fee">isGPRAsFPR16</a>.</p>

</div>
</div>

### isGPRF32() {#adc08f8bfe7e4a35ed1834acb44e4ee9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isGPRF32 ()</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>


<p>Referenced by <a href="#ace8fe8916afb3ef41e8dfda82c123440">isGPRAsFPR32</a>.</p>

</div>
</div>

### isGPRPair() {#acee60d11c2387d3b7b42d9ef5d31bdf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isGPRPair ()</td>
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



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>


<p>Referenced by <a href="#ad7f90ca97b27f1d2539b50874f4c2981">isGPRPairAsFPR64</a>.</p>

</div>
</div>

### isGPRPairAsFPR64() {#ad7f90ca97b27f1d2539b50874f4c2981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isGPRPairAsFPR64 ()</td>
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



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#acee60d11c2387d3b7b42d9ef5d31bdf1">isGPRPair</a> and <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a>.</p>

</div>
</div>

### isImm() {#af5f45b5c592823a5ca093f3475569065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isImm ()</td>
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

<p>isImm - Is this an immediate operand?</p>

<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1">Immediate</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>

</div>
</div>

### isImmXLenLI() {#a9a791d6b93becfa0221371554c45053e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isImmXLenLI ()</td>
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



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a89f3c31cf14a9542b52fd208ce5093ac">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::isSymbolDiff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a3c930f90b860b3ff02df7bd420c1f89e">llvm::RISCVMCExpr::VK_RISCV_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a4b697ccb4bf41db17dc4422189098f55">llvm::RISCVMCExpr::VK_RISCV_PCREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a563b259281b6f3e45a89bb1784036aec">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_ADD_LO</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a5e718279c4aba4b5032b0e4ae1435db7">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_LOAD_LO</a>.</p>

</div>
</div>

### isImmXLenLI\_Restricted() {#a45cda9866fff2598a0fbf13fc2c21735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isImmXLenLI_Restricted ()</td>
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



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isImmZero() {#a1505168c2edbb91f93e80adc33c2d604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isImmZero ()</td>
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



<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isLoadFPImm() {#a65b07c2d3b33166b642509347647acee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isLoadFPImm ()</td>
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

<p>Return true if the operand is a valid fli.s floating-point immediate.</p>

<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#aa9202fc0701ef2e6259785f73081d8aeae3d8da4503ba8c447d522a9194b008c9">FPImmediate</a>, <a href="#a3105a33a236d9b9f471664f593b0d5da">getFPConst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#a514caca686644c2ad0d73f870a96d27f">isUImm5</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>

</div>
</div>

### isMem() {#a969a8d61305379d126f02a5e5c0769e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isMem ()</td>
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

<p>isMem - Is this a memory operand?</p>

<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>

</div>
</div>

### isPseudoJumpSymbol() {#afd5b91c95fad7d6be2b9fbab33610982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isPseudoJumpSymbol ()</td>
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



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6aa4478c3f29a4ad6e0fe8e721c821c476">llvm::RISCVMCExpr::VK_RISCV_CALL</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isReg() {#a2f74b84e50bbdb46303e4f537ef46a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isReg ()</td>
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

<p>isReg - Is this a register operand?</p>

<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>

</div>
</div>

### isRegReg() {#ad204a1a19d9668609652c527d0403037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRegReg ()</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea546839a5c4bcf9f9450967155f48de41">RegReg</a>.</p>

</div>
</div>

### isRlist() {#ad8feadbc213297463f9dc650e00f763d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRlist ()</td>
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



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea783428a7e222d726ca55e7aa6a232977">Rlist</a>.</p>

</div>
</div>

### isRnumArg() {#a33c72952eddffc0cf8c0f301f9f75f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRnumArg ()</td>
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



<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isRnumArg\_0\_7() {#a6d26cbdd8ca30a5d98afb728360f974c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRnumArg_0_7 ()</td>
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



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isRnumArg\_1\_10() {#ae0ad881e8c2b8a510e90ae491602b8a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRnumArg_1_10 ()</td>
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



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isRnumArg\_2\_14() {#a7d069740c7a0135792efbcfc07dfb574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRnumArg_2_14 ()</td>
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



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isRTZArg() {#a111f6373dc343ca036d335dd93a235a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRTZArg ()</td>
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



<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#acf81c000ce9b2d98a4c581adf48ed648">FRM</a>, <a href="#a8e04c381c74c4fee94660003f8822fb0">isFRMArg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvfprndmode/#a9214a4f7f7322f485189dd3726776b76a5bdeddce1d5418fc8d89741d396541ad">llvm::RISCVFPRndMode::RTZ</a>.</p>

</div>
</div>

### isRV64Imm() {#ac8063e11349812b98b26251397f174af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isRV64Imm ()</td>
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

<p>True if this operand is for an RV64 instruction.</p>

<p>Definition at line 1064 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1">Immediate</a> and <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>.</p>


<p>Referenced by <a href="#a72b37da283ebf9ecc9ef3b8468b9569d">addFPImmOperands</a>, <a href="#a433c5deedfe24ee94256da5a3021aa19">addImmOperands</a>, <a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a>, <a href="#a9a791d6b93becfa0221371554c45053e">isImmXLenLI</a>, <a href="#a45cda9866fff2598a0fbf13fc2c21735">isImmXLenLI_Restricted</a>, <a href="#a881b29a20a1d8eb1ff76ee27c79ce4de">isSImm10Lsb0000NonZero</a>, <a href="#af093f69b028595df33edd1202e0cbc52">isSImm12</a>, <a href="#aa0d77a04edcf0d4f6922b7588617bfdd">isSImm12Lsb00000</a>, <a href="#adfe1704021f6026752f84192211fe503">isSImm26</a>, <a href="#afc37984bc54744b905e01edc0b594beb">isSImm5</a>, <a href="#abea18d9f8d1a819e45efc723be71dcb8">isSImm5Plus1</a>, <a href="#ad01a2bf5a8b48c76149ee03417626e12">isSImm6</a>, <a href="#a6af949c7bbac35f257efa40174d553af">isSImm6NonZero</a>, <a href="#a8ea5baf20e0a1c77c77df4d599153e89">isUImmLog2XLen</a>, <a href="#a6f60201ed3b2c549f06fc69bb4e688be">isUImmLog2XLenHalf</a> and <a href="#a6c60dd71c23660c5f1f1a94b7f53137f">isUImmLog2XLenNonZero</a>.</p>

</div>
</div>

### isSImm10Lsb0000NonZero() {#a881b29a20a1d8eb1ff76ee27c79ce4de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm10Lsb0000NonZero ()</td>
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



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isSImm12() {#af093f69b028595df33edd1202e0cbc52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm12 ()</td>
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



<p>Definition at line 940 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a3c930f90b860b3ff02df7bd420c1f89e">llvm::RISCVMCExpr::VK_RISCV_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a4b697ccb4bf41db17dc4422189098f55">llvm::RISCVMCExpr::VK_RISCV_PCREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a563b259281b6f3e45a89bb1784036aec">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_ADD_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a5e718279c4aba4b5032b0e4ae1435db7">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_LOAD_LO</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a1cfe2bb904199433c2ef567b6227db8c">llvm::RISCVMCExpr::VK_RISCV_TPREL_LO</a>.</p>

</div>
</div>

### isSImm12Lsb0() {#ac919a38328c27eb6be9a981a93892a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm12Lsb0 ()</td>
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



<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a>.</p>

</div>
</div>

### isSImm12Lsb00000() {#aa0d77a04edcf0d4f6922b7588617bfdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm12Lsb00000 ()</td>
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



<p>Definition at line 961 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isSImm13Lsb0() {#a5f413b3dbb8145b1fbc25107f688f02a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm13Lsb0 ()</td>
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



<p>Definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a>.</p>

</div>
</div>

### isSImm21Lsb0JAL() {#abc6ca848fcaf79620c6535ed2c92f1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm21Lsb0JAL ()</td>
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



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a>.</p>

</div>
</div>

### isSImm26() {#adfe1704021f6026752f84192211fe503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm26 ()</td>
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



<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isSImm5() {#afc37984bc54744b905e01edc0b594beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm5 ()</td>
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



<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isSImm5Plus1() {#abea18d9f8d1a819e45efc723be71dcb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm5Plus1 ()</td>
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



<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isSImm6() {#ad01a2bf5a8b48c76149ee03417626e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm6 ()</td>
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



<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isSImm6NonZero() {#a6af949c7bbac35f257efa40174d553af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm6NonZero ()</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isSImm9Lsb0() {#aa8ede124eb449bccb57da5089795ead1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSImm9Lsb0 ()</td>
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



<p>Definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a>.</p>

</div>
</div>

### isSpimm() {#ae00e7f3cfa5c4ee1b300d621c786e5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSpimm ()</td>
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



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea96de0d3240f0de846f0d4d86ae41ec92">Spimm</a>.</p>

</div>
</div>

### isSystemRegister() {#adaa68359051f29a1499f6715c7ca952b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isSystemRegister ()</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea02a594430be99850ee772aa87474ffd6">SystemRegister</a>.</p>


<p>Referenced by <a href="#a5acd6bf8266660157be23d9ca1e28af7">isCSRSystemRegister</a>.</p>

</div>
</div>

### isTLSDESCCallSymbol() {#acfccb31cfbda65ecc1f98d308df407d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isTLSDESCCallSymbol ()</td>
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



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6ae5770558120b3a15fc80a83e0532dc22">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_CALL</a>.</p>

</div>
</div>

### isToken() {#a09729766c665aa84cb453c72112b562b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isToken ()</td>
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

<p>isToken - Is this a token operand?</p>

<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea459a6f79ad9b13cbcb5f692d2cc7a94d">Token</a>.</p>

</div>
</div>

### isTPRelAddSymbol() {#afc0a8adb97fa110f25f96b03c0ddc590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isTPRelAddSymbol ()</td>
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



<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a9396ec898399370b727b35de80497248">llvm::RISCVMCExpr::VK_RISCV_TPREL_ADD</a>.</p>

</div>
</div>

### IsUImm() {#ad56527e41b356250baa3f977a0f23379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::IsUImm ()</td>
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



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>


<p>Referenced by <a href="#a316d511c200bac1e4e0d18a1009d6cab">isUImm1</a>, <a href="#afb05c3b557b8e1e0b46a9886b42f7d80">isUImm10</a>, <a href="#a454427509663610a20e658b289a2ba00">isUImm11</a>, <a href="#acf02e5ad5c0d88a3e0516f894ff9d947">isUImm16</a>, <a href="#af1c250b5d116f388a711ce211a640838">isUImm2</a>, <a href="#a0e90af5538eb25666bf7d659bcf41ba5">isUImm20</a>, <a href="#ad08c1d77dbe7a9ab3a1bf0374fb38a15">isUImm3</a>, <a href="#aaf2e624f6eabe05032b1d7ef020ad6e6">isUImm32</a>, <a href="#adfa82a6816f6ecd588b43f3f2576112c">isUImm4</a>, <a href="#a48fca9aad0177b9539cb543a8ce683e7">isUImm48</a>, <a href="#a514caca686644c2ad0d73f870a96d27f">isUImm5</a>, <a href="#aa4fa244442c32b92368f06b00f4d0505">isUImm6</a>, <a href="#a0b7716db3ddc0347dda99d61e925d753">isUImm64</a>, <a href="#a6c3daaef61115d7d51eed9d7fdbb2b36">isUImm7</a> and <a href="#a1b7708ea704dc781ec8a1316a802ce25">isUImm8</a>.</p>

</div>
</div>

### isUImm1() {#a316d511c200bac1e4e0d18a1009d6cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm1 ()</td>
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



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm10() {#afb05c3b557b8e1e0b46a9886b42f7d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm10 ()</td>
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



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm10Lsb00NonZero() {#ad40ce5b912f81fa907dc15a8fe418c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm10Lsb00NonZero ()</td>
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



<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm11() {#a454427509663610a20e658b289a2ba00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm11 ()</td>
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



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm16() {#acf02e5ad5c0d88a3e0516f894ff9d947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm16 ()</td>
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



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm2() {#af1c250b5d116f388a711ce211a640838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm2 ()</td>
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



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm20() {#a0e90af5538eb25666bf7d659bcf41ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm20 ()</td>
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



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm20AUIPC() {#a7941ccc7f7bc6d6f518e1db11e581b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm20AUIPC ()</td>
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



<p>Definition at line 1003 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6af53e7457e88370f76455f7cf9c525a8f">llvm::RISCVMCExpr::VK_RISCV_GOT_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a380387ebfe7e093c92941ec73b8a2557">llvm::RISCVMCExpr::VK_RISCV_PCREL_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a739b9795700df7ae19816f89508f1b49">llvm::RISCVMCExpr::VK_RISCV_TLS_GD_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a17c514839d8a0aca51f132e5dae74967">llvm::RISCVMCExpr::VK_RISCV_TLS_GOT_HI</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6aada38a4713e0b102bd6c05f34926f896">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_HI</a>.</p>

</div>
</div>

### isUImm20LUI() {#aafcf3c2bb5b0550a74203b0c15648681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm20LUI ()</td>
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



<p>Definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a402cdf1e65b003605c1db8647861c353">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::classifySymbolRef</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6ab5c3ca301e449ab85f42444601bba378">llvm::RISCVMCExpr::VK_RISCV_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a28a380cf34cda5c68bbe50aa22378bb1">llvm::RISCVMCExpr::VK_RISCV_TPREL_HI</a>.</p>

</div>
</div>

### isUImm2Lsb0() {#a311a899eaec9b7e7e0ecc3bcdb03bc92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm2Lsb0 ()</td>
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



<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm3() {#ad08c1d77dbe7a9ab3a1bf0374fb38a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm3 ()</td>
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



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm32() {#aaf2e624f6eabe05032b1d7ef020ad6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm32 ()</td>
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



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm4() {#adfa82a6816f6ecd588b43f3f2576112c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm4 ()</td>
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



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm48() {#a48fca9aad0177b9539cb543a8ce683e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm48 ()</td>
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



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm5() {#a514caca686644c2ad0d73f870a96d27f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm5 ()</td>
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



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>


<p>Referenced by <a href="#a65b07c2d3b33166b642509347647acee">isLoadFPImm</a>.</p>

</div>
</div>

### isUImm5GT3() {#a9d8c7238cf9ac3ee71e1bff04885275c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm5GT3 ()</td>
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



<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm5Lsb0() {#afecb01e5f389e34cb6ff2193d429b50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm5Lsb0 ()</td>
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



<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm5NonZero() {#ae99db1ae2ce5a2b14538903fed4cffdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm5NonZero ()</td>
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



<p>Definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm6() {#aa4fa244442c32b92368f06b00f4d0505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm6 ()</td>
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



<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm64() {#a0b7716db3ddc0347dda99d61e925d753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm64 ()</td>
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



<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm6Lsb0() {#ac2d5778b8d84d190f64085c330c49206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm6Lsb0 ()</td>
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



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm7() {#a6c3daaef61115d7d51eed9d7fdbb2b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm7 ()</td>
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



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm7Lsb00() {#accf08f0dc52b404b10f854884408cb43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm7Lsb00 ()</td>
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



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm7Lsb000() {#ac2784f59f188a8c871a9f0b30c87c925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm7Lsb000 ()</td>
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



<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm8() {#a1b7708ea704dc781ec8a1316a802ce25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm8 ()</td>
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



<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>.</p>

</div>
</div>

### isUImm8GE32() {#a2a26a869a59be9ae11a98d9129fd331f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm8GE32 ()</td>
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



<p>Definition at line 748 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm8Lsb00() {#a2b303f3378e4f430ff52c7520317f7ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm8Lsb00 ()</td>
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



<p>Definition at line 890 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm8Lsb000() {#a27b9f96bd235d2600a144430d35a2663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm8Lsb000 ()</td>
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



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImm9Lsb000() {#a8b003806c09ef35d160cfdb9a2865ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImm9Lsb000 ()</td>
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



<p>Definition at line 912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImmLog2XLen() {#a8ea5baf20e0a1c77c77df4d599153e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImmLog2XLen ()</td>
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



<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImmLog2XLenHalf() {#a6f60201ed3b2c549f06fc69bb4e688be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImmLog2XLenHalf ()</td>
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



<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isUImmLog2XLenNonZero() {#a6c60dd71c23660c5f1f1a94b7f53137f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isUImmLog2XLenNonZero ()</td>
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



<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>

</div>
</div>

### isV0Reg() {#a48e5be37a834e42f278fd02f4c1e49ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isV0Reg ()</td>
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



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>

</div>
</div>

### isVTypeI10() {#a48ffcfa61f8429e10911f920e8aa16db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isVTypeI10 ()</td>
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



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1">Immediate</a>, <a href="#a6e51b20075aca7e72c747ebe4ce625b9">isVTypeImm</a>, <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea40f97061ec443f48b610108eb6b10220">VType</a>.</p>

</div>
</div>

### isVTypeI11() {#a077dff4c4b4290b14e1ba95976bae56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isVTypeI11 ()</td>
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



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1">Immediate</a>, <a href="#a6e51b20075aca7e72c747ebe4ce625b9">isVTypeImm</a>, <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea40f97061ec443f48b610108eb6b10220">VType</a>.</p>

</div>
</div>

### isVTypeImm() {#a6e51b20075aca7e72c747ebe4ce625b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::isVTypeImm (unsigned N)</td>
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



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>


<p>Referenced by <a href="#a48ffcfa61f8429e10911f920e8aa16db">isVTypeI10</a> and <a href="#a077dff4c4b4290b14e1ba95976bae56d">isVTypeI11</a>.</p>

</div>
</div>

### print() {#a5c67f50a9eeeeebe54d2cb8393b3d956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>print - Print a debug representation of the operand to the given stream.</p>

<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#aa9202fc0701ef2e6259785f73081d8aeafa1124a61230804809a9b5fc57932b40">Fence</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aeae3d8da4503ba8c447d522a9194b008c9">FPImmediate</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea83445ea5183d15511eeaa89336af0d91">FRM</a>, <a href="#aa25790c6806f48a3be471a2e4228616a">getFence</a>, <a href="#aa66ed9ade9605bccd73d410447380456">getFRM</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a150fc71b3d1a82817f7626c912b01abe">llvm::RISCVInstPrinter::getRegisterName</a>, <a href="#aad56a0381360ef39001884ebf5c9920b">getSysReg</a>, <a href="#a5807533b5f320ca7716b348fc210169c">getToken</a>, <a href="#a7696e2ed10c27a39a03144f36a21ddc4">getVType</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1">Immediate</a>, <a href="#af16426cd7206ab5262eb7b8cb4d5928c">Kind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a9a4e8a70f59e180ae2284aebb60e42a3">llvm::RISCVZC::printRlist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#acab957b7266a5cb7bb0a69c3d1277397">llvm::RISCVVType::printVType</a>, <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea546839a5c4bcf9f9450967155f48de41">RegReg</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea783428a7e222d726ca55e7aa6a232977">Rlist</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea96de0d3240f0de846f0d4d86ae41ec92">Spimm</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea02a594430be99850ee772aa87474ffd6">SystemRegister</a>, <a href="#aa9202fc0701ef2e6259785f73081d8aea459a6f79ad9b13cbcb5f692d2cc7a94d">Token</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea40f97061ec443f48b610108eb6b10220">VType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a4af5f59b367bd03c3fb3c0f0adbe01c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{RISCVAsmParser.cpp}::RISCVOperand anonymous{RISCVAsmParser.cpp}::RISCVOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>

</div>
</div>

### EndLoc {#a4d5a78f43db087f0be5f959a8c7f07b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{RISCVAsmParser.cpp}::RISCVOperand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#acd210eb3e7dcd6d418f1642d9f9d8401">getEndLoc</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### Fence {#abb6b7d8aa5881b56351cfda55a945cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct FenceOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::Fence</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#aaab805d2778c683124cc4241c4ae522e">addFenceArgOperands</a>, <a href="#aa25790c6806f48a3be471a2e4228616a">getFence</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### FPImm {#a77e24bdd3d976ab7d7c8f91373f2a409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPImmOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::FPImm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a3105a33a236d9b9f471664f593b0d5da">getFPConst</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### FRM {#acf81c000ce9b2d98a4c581adf48ed648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct FRMOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::FRM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a9187bd16dbf70135d4afc96c5f1d282e">createFRMArg</a>, <a href="#aa66ed9ade9605bccd73d410447380456">getFRM</a>, <a href="#a111f6373dc343ca036d335dd93a235a6">isRTZArg</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### Imm {#a76b1a37f44cc47b52ce533d2bd3e05ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a6762c005d2c4f50e2ba59d9cdab146a5">addExpr</a>, <a href="#a72b37da283ebf9ecc9ef3b8468b9569d">addFPImmOperands</a>, <a href="#a5515c4f1f3e9f0e04e83a787020af209">addVTypeIOperands</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a>, <a href="#ac8502fc60d43c787f067cf0a3d3aed2e">isBareSymbol</a>, <a href="#a5042f1f9092dd0215e831229e55f8ebd">isCallSymbol</a>, <a href="#adfbb6e70817ddf44c690c812da1d300c">isCLUIImm</a>, <a href="#a9a791d6b93becfa0221371554c45053e">isImmXLenLI</a>, <a href="#a45cda9866fff2598a0fbf13fc2c21735">isImmXLenLI_Restricted</a>, <a href="#a1505168c2edbb91f93e80adc33c2d604">isImmZero</a>, <a href="#afd5b91c95fad7d6be2b9fbab33610982">isPseudoJumpSymbol</a>, <a href="#a33c72952eddffc0cf8c0f301f9f75f9b">isRnumArg</a>, <a href="#a6d26cbdd8ca30a5d98afb728360f974c">isRnumArg_0_7</a>, <a href="#ae0ad881e8c2b8a510e90ae491602b8a7">isRnumArg_1_10</a>, <a href="#a7d069740c7a0135792efbcfc07dfb574">isRnumArg_2_14</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="#a881b29a20a1d8eb1ff76ee27c79ce4de">isSImm10Lsb0000NonZero</a>, <a href="#af093f69b028595df33edd1202e0cbc52">isSImm12</a>, <a href="#aa0d77a04edcf0d4f6922b7588617bfdd">isSImm12Lsb00000</a>, <a href="#adfe1704021f6026752f84192211fe503">isSImm26</a>, <a href="#afc37984bc54744b905e01edc0b594beb">isSImm5</a>, <a href="#abea18d9f8d1a819e45efc723be71dcb8">isSImm5Plus1</a>, <a href="#ad01a2bf5a8b48c76149ee03417626e12">isSImm6</a>, <a href="#a6af949c7bbac35f257efa40174d553af">isSImm6NonZero</a>, <a href="#acfccb31cfbda65ecc1f98d308df407d2">isTLSDESCCallSymbol</a>, <a href="#afc0a8adb97fa110f25f96b03c0ddc590">isTPRelAddSymbol</a>, <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>, <a href="#ad40ce5b912f81fa907dc15a8fe418c50">isUImm10Lsb00NonZero</a>, <a href="#a7941ccc7f7bc6d6f518e1db11e581b9d">isUImm20AUIPC</a>, <a href="#aafcf3c2bb5b0550a74203b0c15648681">isUImm20LUI</a>, <a href="#a311a899eaec9b7e7e0ecc3bcdb03bc92">isUImm2Lsb0</a>, <a href="#a9d8c7238cf9ac3ee71e1bff04885275c">isUImm5GT3</a>, <a href="#afecb01e5f389e34cb6ff2193d429b50b">isUImm5Lsb0</a>, <a href="#ae99db1ae2ce5a2b14538903fed4cffdc">isUImm5NonZero</a>, <a href="#ac2d5778b8d84d190f64085c330c49206">isUImm6Lsb0</a>, <a href="#accf08f0dc52b404b10f854884408cb43">isUImm7Lsb00</a>, <a href="#ac2784f59f188a8c871a9f0b30c87c925">isUImm7Lsb000</a>, <a href="#a2a26a869a59be9ae11a98d9129fd331f">isUImm8GE32</a>, <a href="#a2b303f3378e4f430ff52c7520317f7ed">isUImm8Lsb00</a>, <a href="#a27b9f96bd235d2600a144430d35a2663">isUImm8Lsb000</a>, <a href="#a8b003806c09ef35d160cfdb9a2865ff5">isUImm9Lsb000</a>, <a href="#a8ea5baf20e0a1c77c77df4d599153e89">isUImmLog2XLen</a>, <a href="#a6f60201ed3b2c549f06fc69bb4e688be">isUImmLog2XLenHalf</a>, <a href="#a6c60dd71c23660c5f1f1a94b7f53137f">isUImmLog2XLenNonZero</a>, <a href="#a6e51b20075aca7e72c747ebe4ce625b9">isVTypeImm</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### Kind {#af16426cd7206ab5262eb7b8cb4d5928c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{RISCVAsmParser.cpp}::RISCVOperand::KindTy anonymous{RISCVAsmParser.cpp}::RISCVOperand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a5515c4f1f3e9f0e04e83a787020af209">addVTypeIOperands</a>, <a href="#aa25790c6806f48a3be471a2e4228616a">getFence</a>, <a href="#a3105a33a236d9b9f471664f593b0d5da">getFPConst</a>, <a href="#aa66ed9ade9605bccd73d410447380456">getFRM</a>, <a href="#a46c5cbdee2f5b53138baa9bb106305bf">getImm</a>, <a href="#ac3e2290cbf87a82c3fa1825dd701b706">getReg</a>, <a href="#aad56a0381360ef39001884ebf5c9920b">getSysReg</a>, <a href="#a5807533b5f320ca7716b348fc210169c">getToken</a>, <a href="#a7696e2ed10c27a39a03144f36a21ddc4">getVType</a>, <a href="#aefc38af9f8bf1904f5e95b7af5cc4b3c">isAnyReg</a>, <a href="#ad7046735c047f11553ce3716cc90e2fc">isAnyRegC</a>, <a href="#a1ebb39dac8dee5b668ccf6ad46893c35">isFenceArg</a>, <a href="#a8e04c381c74c4fee94660003f8822fb0">isFRMArg</a>, <a href="#a168c93f6e1a2b274a3eb7057aa12d0e3">isFRMArgLegacy</a>, <a href="#ae86c3d46f4298d1d52cb1a72320d8fe6">isGPR</a>, <a href="#a497847b31bb15c186b5613adec4846fd">isGPRF16</a>, <a href="#adc08f8bfe7e4a35ed1834acb44e4ee9b">isGPRF32</a>, <a href="#acee60d11c2387d3b7b42d9ef5d31bdf1">isGPRPair</a>, <a href="#af5f45b5c592823a5ca093f3475569065">isImm</a>, <a href="#a65b07c2d3b33166b642509347647acee">isLoadFPImm</a>, <a href="#a2f74b84e50bbdb46303e4f537ef46a95">isReg</a>, <a href="#ad204a1a19d9668609652c527d0403037">isRegReg</a>, <a href="#ad8feadbc213297463f9dc650e00f763d">isRlist</a>, <a href="#ac8063e11349812b98b26251397f174af">isRV64Imm</a>, <a href="#ae00e7f3cfa5c4ee1b300d621c786e5e0">isSpimm</a>, <a href="#adaa68359051f29a1499f6715c7ca952b">isSystemRegister</a>, <a href="#a09729766c665aa84cb453c72112b562b">isToken</a>, <a href="#a48e5be37a834e42f278fd02f4c1e49ae">isV0Reg</a>, <a href="#a48ffcfa61f8429e10911f920e8aa16db">isVTypeI10</a>, <a href="#a077dff4c4b4290b14e1ba95976bae56d">isVTypeI11</a>, <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a>, <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a> and <a href="#a9fc72e7198ffd2124971f65d993f0ecf">RISCVOperand</a>.</p>

</div>
</div>

### Reg {#af33eddc1fccc314212795d2c3f02eab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a1969d66edd578a4de9321c1acd08d7b9">createReg</a>, <a href="#ac3e2290cbf87a82c3fa1825dd701b706">getReg</a>, <a href="#aefc38af9f8bf1904f5e95b7af5cc4b3c">isAnyReg</a>, <a href="#ad7046735c047f11553ce3716cc90e2fc">isAnyRegC</a>, <a href="#ae86c3d46f4298d1d52cb1a72320d8fe6">isGPR</a>, <a href="#ac41fa64dc342c50433433d2a502fc82a">isGPRAsFPR</a>, <a href="#abd3d20ef6dd1e1d4130a13e05a580fee">isGPRAsFPR16</a>, <a href="#ace8fe8916afb3ef41e8dfda82c123440">isGPRAsFPR32</a>, <a href="#a497847b31bb15c186b5613adec4846fd">isGPRF16</a>, <a href="#adc08f8bfe7e4a35ed1834acb44e4ee9b">isGPRF32</a>, <a href="#acee60d11c2387d3b7b42d9ef5d31bdf1">isGPRPair</a>, <a href="#ad7f90ca97b27f1d2539b50874f4c2981">isGPRPairAsFPR64</a>, <a href="#a48e5be37a834e42f278fd02f4c1e49ae">isV0Reg</a>, <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### RegReg {#a4b7409bbebe1ed20beb3ea7d78c2f37c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct RegRegOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::RegReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a1c7c494c84693e0715097e5d9bc23c31">addRegRegOperands</a>, <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### Rlist {#a4dda8a2dae54cade391e067430b856e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct RlistOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::Rlist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#af18328b40cba50468c5a380fb0d86eeb">addRlistOperands</a>, <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### Spimm {#aec175f6124fde7360b4e4c5f54e7ab68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct SpimmOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::Spimm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2cd3aa898829c8a5af0f9f8b6c0b369f">addSpimmOperands</a>, <a href="#ac8a20a4ebf74cf0cd35abd08b6f53405">createSpimm</a>, <a href="#a5c67f50a9eeeeebe54d2cb8393b3d956">print</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### StartLoc {#ad8ccbbcdb3901f28502979e9a0f0ab72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{RISCVAsmParser.cpp}::RISCVOperand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a100c560a19a7ac5f1c4de5a92fb70f6a">getStartLoc</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### SysReg {#ac83b10ce54e91c160fe427a9deb9ecb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct SysRegOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::SysReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#afd5cd5faa882cb075d2cd166a3cd3222">addCSRSystemRegisterOperands</a>, <a href="#aad56a0381360ef39001884ebf5c9920b">getSysReg</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### Tok {#af13263d18f2fae75e479e3cfcc04951d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{RISCVAsmParser.cpp}::RISCVOperand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a5807533b5f320ca7716b348fc210169c">getToken</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

### VType {#a5ea97031fa9df60c20a21f9cc8bdfbaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct VTypeOp anonymous{RISCVAsmParser.cpp}::RISCVOperand::VType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a7696e2ed10c27a39a03144f36a21ddc4">getVType</a> and <a href="#afb5400c33634bafb22f22c263e55d9fe">RISCVOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### addExpr() {#a6762c005d2c4f50e2ba59d9cdab146a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVAsmParser.cpp}::RISCVOperand::addExpr (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, bool IsRV64Imm)</td>
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



<p>Definition at line 1261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a9c7fddc2abc6f895aa8b9785ce983cc5">evaluateConstantImm</a>, <a href="#a0b748307979d2ca9eeee5560269e585a">fixImmediateForRV32</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>


<p>Referenced by <a href="#a72b37da283ebf9ecc9ef3b8468b9569d">addFPImmOperands</a> and <a href="#a433c5deedfe24ee94256da5a3021aa19">addImmOperands</a>.</p>

</div>
</div>

### createFenceArg() {#a7319b975a79be450e87e210ad5755374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createFenceArg (unsigned Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 1220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa9202fc0701ef2e6259785f73081d8aeafa1124a61230804809a9b5fc57932b40">Fence</a>.</p>

</div>
</div>

### createFPImm() {#a82719125b54cd9a449e8bcde8c69f77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createFPImm (uint64_t Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 1192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa9202fc0701ef2e6259785f73081d8aeae3d8da4503ba8c447d522a9194b008c9">FPImmediate</a>.</p>

</div>
</div>

### createFRMArg() {#a9187bd16dbf70135d4afc96c5f1d282e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createFRMArg (<a href="/web-llvm/docs/api/namespaces/llvm/riscvfprndmode/#a9214a4f7f7322f485189dd3726776b76">RISCVFPRndMode::RoundingMode</a> FRM, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 1212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#acf81c000ce9b2d98a4c581adf48ed648">FRM</a>.</p>

</div>
</div>

### createImm() {#a86e438c1f518ace583bc6645628ccc32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, bool IsRV64)</td>
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



<p>Definition at line 1182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa9202fc0701ef2e6259785f73081d8aea43f6615bbb2c40a5306ff804094420b1">Immediate</a>.</p>

</div>
</div>

### createReg() {#a1969d66edd578a4de9321c1acd08d7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, bool IsGPRAsFPR=false)</td>
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



<p>Definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#af33eddc1fccc314212795d2c3f02eab4">Reg</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea0ba7583639a274c434bbe6ef797115a4">Register</a>.</p>

</div>
</div>

### createRegReg() {#a316f3c138ccbe02af7c5e13e1b711b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createRegReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg1, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg2, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 1244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a> and <a href="#aa9202fc0701ef2e6259785f73081d8aea546839a5c4bcf9f9450967155f48de41">RegReg</a>.</p>

</div>
</div>

### createRlist() {#a016456ae72f5c5044229196ffc301ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createRlist (unsigned RlistEncode, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 1236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa9202fc0701ef2e6259785f73081d8aea783428a7e222d726ca55e7aa6a232977">Rlist</a>.</p>

</div>
</div>

### createSpimm() {#ac8a20a4ebf74cf0cd35abd08b6f53405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createSpimm (unsigned Spimm, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#aec175f6124fde7360b4e4c5f54e7ab68">Spimm</a>.</p>

</div>
</div>

### createSysReg() {#abfb1440e5c9ed8cf3b8e6366e413d51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createSysReg (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, unsigned Encoding)</td>
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



<p>Definition at line 1200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa9202fc0701ef2e6259785f73081d8aea02a594430be99850ee772aa87474ffd6">SystemRegister</a>.</p>

</div>
</div>

### createToken() {#a2e549ead0c31b1e6180ef2d52813a6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa9202fc0701ef2e6259785f73081d8aea459a6f79ad9b13cbcb5f692d2cc7a94d">Token</a>.</p>

</div>
</div>

### createVType() {#a801d4f6598c5e9c7224e8df654e40003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RISCVOperand &gt; anonymous{RISCVAsmParser.cpp}::RISCVOperand::createVType (unsigned VTypeI, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 1228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa9202fc0701ef2e6259785f73081d8aea40f97061ec443f48b610108eb6b10220">VType</a>.</p>

</div>
</div>

### evaluateConstantImm() {#a9c7fddc2abc6f895aa8b9785ce983cc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVAsmParser.cpp}::RISCVOperand::evaluateConstantImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, int64_t &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6">RISCVMCExpr::VariantKind</a> &amp; VK)</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>.</p>


<p>Referenced by <a href="#a6762c005d2c4f50e2ba59d9cdab146a5">addExpr</a>, <a href="#a5515c4f1f3e9f0e04e83a787020af209">addVTypeIOperands</a>, <a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a>, <a href="#ac8502fc60d43c787f067cf0a3d3aed2e">isBareSymbol</a>, <a href="#a5042f1f9092dd0215e831229e55f8ebd">isCallSymbol</a>, <a href="#adfbb6e70817ddf44c690c812da1d300c">isCLUIImm</a>, <a href="#a9a791d6b93becfa0221371554c45053e">isImmXLenLI</a>, <a href="#a45cda9866fff2598a0fbf13fc2c21735">isImmXLenLI_Restricted</a>, <a href="#a1505168c2edbb91f93e80adc33c2d604">isImmZero</a>, <a href="#afd5b91c95fad7d6be2b9fbab33610982">isPseudoJumpSymbol</a>, <a href="#a33c72952eddffc0cf8c0f301f9f75f9b">isRnumArg</a>, <a href="#a6d26cbdd8ca30a5d98afb728360f974c">isRnumArg_0_7</a>, <a href="#ae0ad881e8c2b8a510e90ae491602b8a7">isRnumArg_1_10</a>, <a href="#a7d069740c7a0135792efbcfc07dfb574">isRnumArg_2_14</a>, <a href="#a881b29a20a1d8eb1ff76ee27c79ce4de">isSImm10Lsb0000NonZero</a>, <a href="#af093f69b028595df33edd1202e0cbc52">isSImm12</a>, <a href="#aa0d77a04edcf0d4f6922b7588617bfdd">isSImm12Lsb00000</a>, <a href="#adfe1704021f6026752f84192211fe503">isSImm26</a>, <a href="#afc37984bc54744b905e01edc0b594beb">isSImm5</a>, <a href="#abea18d9f8d1a819e45efc723be71dcb8">isSImm5Plus1</a>, <a href="#ad01a2bf5a8b48c76149ee03417626e12">isSImm6</a>, <a href="#a6af949c7bbac35f257efa40174d553af">isSImm6NonZero</a>, <a href="#acfccb31cfbda65ecc1f98d308df407d2">isTLSDESCCallSymbol</a>, <a href="#afc0a8adb97fa110f25f96b03c0ddc590">isTPRelAddSymbol</a>, <a href="#ad56527e41b356250baa3f977a0f23379">IsUImm</a>, <a href="#ad40ce5b912f81fa907dc15a8fe418c50">isUImm10Lsb00NonZero</a>, <a href="#a7941ccc7f7bc6d6f518e1db11e581b9d">isUImm20AUIPC</a>, <a href="#aafcf3c2bb5b0550a74203b0c15648681">isUImm20LUI</a>, <a href="#a311a899eaec9b7e7e0ecc3bcdb03bc92">isUImm2Lsb0</a>, <a href="#a9d8c7238cf9ac3ee71e1bff04885275c">isUImm5GT3</a>, <a href="#afecb01e5f389e34cb6ff2193d429b50b">isUImm5Lsb0</a>, <a href="#ae99db1ae2ce5a2b14538903fed4cffdc">isUImm5NonZero</a>, <a href="#ac2d5778b8d84d190f64085c330c49206">isUImm6Lsb0</a>, <a href="#accf08f0dc52b404b10f854884408cb43">isUImm7Lsb00</a>, <a href="#ac2784f59f188a8c871a9f0b30c87c925">isUImm7Lsb000</a>, <a href="#a2a26a869a59be9ae11a98d9129fd331f">isUImm8GE32</a>, <a href="#a2b303f3378e4f430ff52c7520317f7ed">isUImm8Lsb00</a>, <a href="#a27b9f96bd235d2600a144430d35a2663">isUImm8Lsb000</a>, <a href="#a8b003806c09ef35d160cfdb9a2865ff5">isUImm9Lsb000</a>, <a href="#a8ea5baf20e0a1c77c77df4d599153e89">isUImmLog2XLen</a>, <a href="#a6f60201ed3b2c549f06fc69bb4e688be">isUImmLog2XLenHalf</a>, <a href="#a6c60dd71c23660c5f1f1a94b7f53137f">isUImmLog2XLenNonZero</a> and <a href="#a6e51b20075aca7e72c747ebe4ce625b9">isVTypeImm</a>.</p>

</div>
</div>

### fixImmediateForRV32() {#a0b748307979d2ca9eeee5560269e585a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{RISCVAsmParser.cpp}::RISCVOperand::fixImmediateForRV32 (int64_t Imm, bool IsRV64Imm)</td>
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



<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a>.</p>


<p>References <a href="#a76b1a37f44cc47b52ce533d2bd3e05ef">Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="#a6762c005d2c4f50e2ba59d9cdab146a5">addExpr</a>, <a href="#a0f7cfaa1c472b36c995d6f95d9321e0a">isBareSimmNLsb0</a>, <a href="#a881b29a20a1d8eb1ff76ee27c79ce4de">isSImm10Lsb0000NonZero</a>, <a href="#af093f69b028595df33edd1202e0cbc52">isSImm12</a>, <a href="#aa0d77a04edcf0d4f6922b7588617bfdd">isSImm12Lsb00000</a>, <a href="#adfe1704021f6026752f84192211fe503">isSImm26</a>, <a href="#afc37984bc54744b905e01edc0b594beb">isSImm5</a>, <a href="#abea18d9f8d1a819e45efc723be71dcb8">isSImm5Plus1</a>, <a href="#ad01a2bf5a8b48c76149ee03417626e12">isSImm6</a> and <a href="#a6af949c7bbac35f257efa40174d553af">isSImm6NonZero</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp">RISCVAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
