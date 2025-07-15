---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LanaiOperand` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{LanaiAsmParser.cpp}::LanaiOperand { ... }
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#aa8ff80a3592fd38f2712f96eb51ea144">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66aaea6b10c59bb990994e41e73d0cc9">LanaiOperand</a> (KindTy Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6f4c0a0a71ab332c6311fdf3cbbdd8">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Get the location of the first token of this operand. <a href="#abc6f4c0a0a71ab332c6311fdf3cbbdd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaedd09a65c8d8a7394b4e3c4144ccf34">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Get the location of the last token of this operand. <a href="#aaedd09a65c8d8a7394b4e3c4144ccf34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8df742095eda8b544c2c418d92821368">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a7cb8e8bdf283aa515d839190811d7">getToken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd8eb345a392a179f6ae817c52a6a47">getMemBaseReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ff5a61c7d69362c123a763e1abcc89">getMemOffsetReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac360a86c8897a5769f817b4b2117bca4">getMemOffset</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58b6d95c7e58e6c2924e02797d67705">getMemOp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e61c4da35f1fd0f5b707127d0deaf3">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#a65e61c4da35f1fd0f5b707127d0deaf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65adaddf2904bdfde259aff897c1a394">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#a65adaddf2904bdfde259aff897c1a394">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e81f8f7b848cfc189c45631f4470b0f">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#a3e81f8f7b848cfc189c45631f4470b0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626ece2116259c9429017015e3392d23">isMemImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617ae9ab779f94e2a2b45e449e08aee8">isMemRegImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96e9cf9b73f441b6ccf8446b3965de69">isMemRegReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9954ef99fcc113b4f4d1af1a76c7367">isMemSpls</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512faf94f3d9e5327ca9e170fb1d2863">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#a512faf94f3d9e5327ca9e170fb1d2863">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b0c7909cd1c59c0450d9d1a8493bc9">isBrImm</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec20268526405a50b6bb483af902f5a">isBrTarget</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4bb149e137d775e094dac3c27fa2a12">isCallTarget</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf98c08c7ee4d1244bbc1b9b89cd0ea">isHiImm16</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a980e5bb4840109e1822c062cbfafa7">isHiImm16And</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f72e54d11a94c9f7ed915863773bd69">isLoImm16</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b070244459f6f10638b5980da6759de">isLoImm16Signed</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade0aa7301c37915069aa87297225d180">isLoImm16And</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aaf84fd1fc76bb95d588ff92b53c672">isImmShift</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3debbf507853ab68544bd4ff00a54a33">isLoImm21</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb23248dfc6a00019f3f78d74a2b45b1">isImm10</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae57fbd0e584ec2382b9940e01e19d768">isCondCode</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852804acbee235af9428694e0e2a1fca">addExpr</a> (MCInst &amp;Inst, const MCExpr *Expr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a938a6ff26f09f87928908d016aa961d8">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a556559c7e8454cf761a7c221be5f9">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6242a454fd07471f8abb0de8c96948d1">addBrTargetOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1c4938e33ca93febed1f664840cbe0">addCallTargetOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeba174de27ec49a4b93d205a6cec2f2">addCondCodeOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cbefada336978d949d3aa114dbee948">addMemImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acacea0c596433796a7a9674ef7d6df1c">addMemRegImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bc907003ab69e65230cb39a00390735">addMemRegRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2d3ecd3f23934a5c6194502f9d758e">addMemSplsOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6d4d0389eb037b2ca67206191384ee">addImmShiftOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82890c84cee6bcbdb0175c3d99032dd">addImm10Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e06c5e6471e93005516ed8a140c72cb">addLoImm16Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9773bf588f5b30ff88274f1ee52e9c9b">addLoImm16AndOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df049e5840d649a327cba55d9ad3f8d">addHiImm16Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7b8b2f33404bae5609243536427d9b">addHiImm16AndOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b3ab698b20fe1832388bb62f71c213e">addLoImm21Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5538a23d0746dd37b532dbaade0fbe9f">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#a5538a23d0746dd37b532dbaade0fbe9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{LanaiAsmParser.cpp}<a href="#aa8ff80a3592fd38f2712f96eb51ea144">::LanaiOperand::KindTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9936c1b05850142b1cfbccdfd89faf4">Kind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ee3e85800b353b5c4adf8eb4e95000">StartLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a6b282353ede47cef740f02e0e4b27">EndLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9538df811284f3dc3d73e1208635e5c0">Tok</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70568198e71ea489ac0358df83295ecc">Reg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a8279225300238840d1471fcca15f59">Mem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{LanaiAsmParser.cpp}<a href="#a66aaea6b10c59bb990994e41e73d0cc9">::LanaiOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5f75e65cf4499bac6d5b797a9585404"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand">LanaiOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3cfef4622f389752d819004e3884b7">CreateToken</a> (StringRef Str, SMLoc Start)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand">LanaiOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c86dfc90c1c7a2870b31d1912365cc">createReg</a> (MCRegister Reg, SMLoc Start, SMLoc End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand">LanaiOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac8e5efcee7c675442d4b6e1c9c7cc4">createImm</a> (const MCExpr *Value, SMLoc Start, SMLoc End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand">LanaiOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51fd29f0c7b93190ced07ea70aa2ee4">MorphToMemImm</a> (std::unique_ptr&lt; LanaiOperand &gt; Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand">LanaiOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79a36528f23f14fb20be4d50b1aa8b55">MorphToMemRegReg</a> (MCRegister BaseReg, std::unique_ptr&lt; LanaiOperand &gt; Op, unsigned AluOp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand">LanaiOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d054df25bf91c180b93f642563943c">MorphToMemRegImm</a> (MCRegister BaseReg, std::unique_ptr&lt; LanaiOperand &gt; Op, unsigned AluOp)</td>
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


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### KindTy {#aa8ff80a3592fd38f2712f96eb51ea144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{LanaiAsmParser.cpp}::LanaiOperand::KindTy </td>
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
<td class="doxyEnumItemName">TOKEN<a id="aa8ff80a3592fd38f2712f96eb51ea144a36dac1f8c77839337a68f8cd0c653864"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REGISTER<a id="aa8ff80a3592fd38f2712f96eb51ea144a2749eb8ba67660dff3452bd18290db40"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMMEDIATE<a id="aa8ff80a3592fd38f2712f96eb51ea144a2a3bd4906d93cc674c70d3317ccb3152"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMORY_IMM<a id="aa8ff80a3592fd38f2712f96eb51ea144a5293f86b07afd549ecdea7e613e2c41a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMORY_REG_IMM<a id="aa8ff80a3592fd38f2712f96eb51ea144a89f3bca72298342d1b9bcb7c0c19600c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMORY_REG_REG<a id="aa8ff80a3592fd38f2712f96eb51ea144a1446ff028bd8d7e46b629547c41e0091"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LanaiOperand() {#a66aaea6b10c59bb990994e41e73d0cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LanaiAsmParser.cpp}::LanaiOperand::LanaiOperand (<a href="#aa8ff80a3592fd38f2712f96eb51ea144">KindTy</a> Kind)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Reference <a href="#af9936c1b05850142b1cfbccdfd89faf4">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#a14c5fa321a079e20b4a884fee7b7788a">IsMemoryAssignmentError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#afd44ea11a1de5d05327fb0ef9d20177f">IsRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#aa381725d28ae64fbe2941e262ad59353">MaybePredicatedInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBrTargetOperands() {#a6242a454fd07471f8abb0de8c96948d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addBrTargetOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a852804acbee235af9428694e0e2a1fca">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addCallTargetOperands() {#a2d1c4938e33ca93febed1f664840cbe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addCallTargetOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a852804acbee235af9428694e0e2a1fca">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addCondCodeOperands() {#abeba174de27ec49a4b93d205a6cec2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addCondCodeOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a852804acbee235af9428694e0e2a1fca">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addExpr() {#a852804acbee235af9428694e0e2a1fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addExpr (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a6242a454fd07471f8abb0de8c96948d1">addBrTargetOperands</a>, <a href="#a2d1c4938e33ca93febed1f664840cbe0">addCallTargetOperands</a>, <a href="#abeba174de27ec49a4b93d205a6cec2f2">addCondCodeOperands</a>, <a href="#ab82890c84cee6bcbdb0175c3d99032dd">addImm10Operands</a>, <a href="#a21a556559c7e8454cf761a7c221be5f9">addImmOperands</a>, <a href="#a2a6d4d0389eb037b2ca67206191384ee">addImmShiftOperands</a>, <a href="#a1cbefada336978d949d3aa114dbee948">addMemImmOperands</a> and <a href="#acacea0c596433796a7a9674ef7d6df1c">addMemRegImmOperands</a>.</p>

</div>
</div>

### addHiImm16AndOperands() {#a1d7b8b2f33404bae5609243536427d9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addHiImm16AndOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addHiImm16Operands() {#a1df049e5840d649a327cba55d9ad3f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addHiImm16Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a2b00558b059f7a2234361fe65e798333">llvm::LanaiMCExpr::getKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#ad9cc57639700272986d246093a5ad1c8ad6161e225a7527044494a229142ba329">llvm::LanaiMCExpr::VK_Lanai_ABS_HI</a>.</p>

</div>
</div>

### addImm10Operands() {#ab82890c84cee6bcbdb0175c3d99032dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addImm10Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a852804acbee235af9428694e0e2a1fca">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmOperands() {#a21a556559c7e8454cf761a7c221be5f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a852804acbee235af9428694e0e2a1fca">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmShiftOperands() {#a2a6d4d0389eb037b2ca67206191384ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addImmShiftOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a852804acbee235af9428694e0e2a1fca">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addLoImm16AndOperands() {#a9773bf588f5b30ff88274f1ee52e9c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm16AndOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addLoImm16Operands() {#a0e06c5e6471e93005516ed8a140c72cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm16Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a2b00558b059f7a2234361fe65e798333">llvm::LanaiMCExpr::getKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#ad9cc57639700272986d246093a5ad1c8a817d6b866eaba4761a3e1aaad6311b13">llvm::LanaiMCExpr::VK_Lanai_ABS_LO</a>.</p>

</div>
</div>

### addLoImm21Operands() {#a5b3ab698b20fe1832388bb62f71c213e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm21Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#a2b00558b059f7a2234361fe65e798333">llvm::LanaiMCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#ad860e326e495f296cdee70606908a6b1">llvm::MCSymbolRefExpr::getKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#ad9cc57639700272986d246093a5ad1c8a109977497b87b76b87fa10bd7bca40bc">llvm::LanaiMCExpr::VK_Lanai_None</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### addMemImmOperands() {#a1cbefada336978d949d3aa114dbee948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a852804acbee235af9428694e0e2a1fca">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac360a86c8897a5769f817b4b2117bca4">getMemOffset</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMemRegImmOperands() {#acacea0c596433796a7a9674ef7d6df1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemRegImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a852804acbee235af9428694e0e2a1fca">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a5dd8eb345a392a179f6ae817c52a6a47">getMemBaseReg</a>, <a href="#ac360a86c8897a5769f817b4b2117bca4">getMemOffset</a>, <a href="#ab58b6d95c7e58e6c2924e02797d67705">getMemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#adb2d3ecd3f23934a5c6194502f9d758e">addMemSplsOperands</a>.</p>

</div>
</div>

### addMemRegRegOperands() {#a3bc907003ab69e65230cb39a00390735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemRegRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a5dd8eb345a392a179f6ae817c52a6a47">getMemBaseReg</a>, <a href="#a43ff5a61c7d69362c123a763e1abcc89">getMemOffsetReg</a>, <a href="#ab58b6d95c7e58e6c2924e02797d67705">getMemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#adb2d3ecd3f23934a5c6194502f9d758e">addMemSplsOperands</a>.</p>

</div>
</div>

### addMemSplsOperands() {#adb2d3ecd3f23934a5c6194502f9d758e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemSplsOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#acacea0c596433796a7a9674ef7d6df1c">addMemRegImmOperands</a>, <a href="#a3bc907003ab69e65230cb39a00390735">addMemRegRegOperands</a>, <a href="#a617ae9ab779f94e2a2b45e449e08aee8">isMemRegImm</a>, <a href="#a96e9cf9b73f441b6ccf8446b3965de69">isMemRegReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#a938a6ff26f09f87928908d016aa961d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getEndLoc() {#aaedd09a65c8d8a7394b4e3c4144ccf34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{LanaiAsmParser.cpp}::LanaiOperand::getEndLoc ()</td>
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

<p>getEndLoc - Get the location of the last token of this operand.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Reference <a href="#a52a6b282353ede47cef740f02e0e4b27">EndLoc</a>.</p>

</div>
</div>

### getImm() {#a39f9673926289aecff3b7f94bdc3c0bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{LanaiAsmParser.cpp}::LanaiOperand::getImm ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>


<p>Referenced by <a href="#a6242a454fd07471f8abb0de8c96948d1">addBrTargetOperands</a>, <a href="#a2d1c4938e33ca93febed1f664840cbe0">addCallTargetOperands</a>, <a href="#abeba174de27ec49a4b93d205a6cec2f2">addCondCodeOperands</a>, <a href="#a1d7b8b2f33404bae5609243536427d9b">addHiImm16AndOperands</a>, <a href="#a1df049e5840d649a327cba55d9ad3f8d">addHiImm16Operands</a>, <a href="#ab82890c84cee6bcbdb0175c3d99032dd">addImm10Operands</a>, <a href="#a21a556559c7e8454cf761a7c221be5f9">addImmOperands</a>, <a href="#a2a6d4d0389eb037b2ca67206191384ee">addImmShiftOperands</a>, <a href="#a9773bf588f5b30ff88274f1ee52e9c9b">addLoImm16AndOperands</a>, <a href="#a0e06c5e6471e93005516ed8a140c72cb">addLoImm16Operands</a>, <a href="#a5b3ab698b20fe1832388bb62f71c213e">addLoImm21Operands</a> and <a href="#a5538a23d0746dd37b532dbaade0fbe9f">print</a>.</p>

</div>
</div>

### getMemBaseReg() {#a5dd8eb345a392a179f6ae817c52a6a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{LanaiAsmParser.cpp}::LanaiOperand::getMemBaseReg ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a> and <a href="#a2a8279225300238840d1471fcca15f59">Mem</a>.</p>


<p>Referenced by <a href="#acacea0c596433796a7a9674ef7d6df1c">addMemRegImmOperands</a>, <a href="#a3bc907003ab69e65230cb39a00390735">addMemRegRegOperands</a> and <a href="#a5538a23d0746dd37b532dbaade0fbe9f">print</a>.</p>

</div>
</div>

### getMemOffset() {#ac360a86c8897a5769f817b4b2117bca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{LanaiAsmParser.cpp}::LanaiOperand::getMemOffset ()</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a> and <a href="#a2a8279225300238840d1471fcca15f59">Mem</a>.</p>


<p>Referenced by <a href="#a1cbefada336978d949d3aa114dbee948">addMemImmOperands</a>, <a href="#acacea0c596433796a7a9674ef7d6df1c">addMemRegImmOperands</a> and <a href="#a5538a23d0746dd37b532dbaade0fbe9f">print</a>.</p>

</div>
</div>

### getMemOffsetReg() {#a43ff5a61c7d69362c123a763e1abcc89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{LanaiAsmParser.cpp}::LanaiOperand::getMemOffsetReg ()</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a> and <a href="#a2a8279225300238840d1471fcca15f59">Mem</a>.</p>


<p>Referenced by <a href="#a3bc907003ab69e65230cb39a00390735">addMemRegRegOperands</a> and <a href="#a5538a23d0746dd37b532dbaade0fbe9f">print</a>.</p>

</div>
</div>

### getMemOp() {#ab58b6d95c7e58e6c2924e02797d67705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LanaiAsmParser.cpp}::LanaiOperand::getMemOp ()</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a> and <a href="#a2a8279225300238840d1471fcca15f59">Mem</a>.</p>


<p>Referenced by <a href="#acacea0c596433796a7a9674ef7d6df1c">addMemRegImmOperands</a> and <a href="#a3bc907003ab69e65230cb39a00390735">addMemRegRegOperands</a>.</p>

</div>
</div>

### getReg() {#a8df742095eda8b544c2c418d92821368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{LanaiAsmParser.cpp}::LanaiOperand::getReg ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a> and <a href="#a70568198e71ea489ac0358df83295ecc">Reg</a>.</p>

</div>
</div>

### getStartLoc() {#abc6f4c0a0a71ab332c6311fdf3cbbdd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{LanaiAsmParser.cpp}::LanaiOperand::getStartLoc ()</td>
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

<p>getStartLoc - Get the location of the first token of this operand.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Reference <a href="#a26ee3e85800b353b5c4adf8eb4e95000">StartLoc</a>.</p>

</div>
</div>

### getToken() {#a63a7cb8e8bdf283aa515d839190811d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{LanaiAsmParser.cpp}::LanaiOperand::getToken ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a512faf94f3d9e5327ca9e170fb1d2863">isToken</a> and <a href="#a9538df811284f3dc3d73e1208635e5c0">Tok</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#aa381725d28ae64fbe2941e262ad59353">MaybePredicatedInst</a>.</p>

</div>
</div>

### isBrImm() {#ab6b0c7909cd1c59c0450d9d1a8493bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isBrImm ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a>.</p>


<p>Referenced by <a href="#a3ec20268526405a50b6bb483af902f5a">isBrTarget</a>.</p>

</div>
</div>

### isBrTarget() {#a3ec20268526405a50b6bb483af902f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isBrTarget ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#ab6b0c7909cd1c59c0450d9d1a8493bc9">isBrImm</a> and <a href="#a512faf94f3d9e5327ca9e170fb1d2863">isToken</a>.</p>

</div>
</div>

### isCallTarget() {#af4bb149e137d775e094dac3c27fa2a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isCallTarget ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="#a512faf94f3d9e5327ca9e170fb1d2863">isToken</a>.</p>

</div>
</div>

### isCondCode() {#ae57fbd0e584ec2382b9940e01e19d768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isCondCode ()</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63aa2b0af36cf77392c4cb0b9d17e06f2ef">llvm::LPCC::UNKNOWN</a>.</p>

</div>
</div>

### isHiImm16() {#aebf98c08c7ee4d1244bbc1b9b89cd0ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isHiImm16 ()</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#ad9cc57639700272986d246093a5ad1c8ad6161e225a7527044494a229142ba329">llvm::LanaiMCExpr::VK_Lanai_ABS_HI</a>.</p>

</div>
</div>

### isHiImm16And() {#a7a980e5bb4840109e1822c062cbfafa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isHiImm16And ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isImm() {#a65adaddf2904bdfde259aff897c1a394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isImm ()</td>
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

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#aa8ff80a3592fd38f2712f96eb51ea144a2a3bd4906d93cc674c70d3317ccb3152">IMMEDIATE</a> and <a href="#af9936c1b05850142b1cfbccdfd89faf4">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#a14c5fa321a079e20b4a884fee7b7788a">IsMemoryAssignmentError</a>.</p>

</div>
</div>

### isImm10() {#acb23248dfc6a00019f3f78d74a2b45b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isImm10 ()</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>.</p>

</div>
</div>

### isImmShift() {#a3aaf84fd1fc76bb95d588ff92b53c672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isImmShift ()</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isLoImm16() {#a6f72e54d11a94c9f7ed915863773bd69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isLoImm16 ()</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#ad9cc57639700272986d246093a5ad1c8a817d6b866eaba4761a3e1aaad6311b13">llvm::LanaiMCExpr::VK_Lanai_ABS_LO</a>.</p>

</div>
</div>

### isLoImm16And() {#ade0aa7301c37915069aa87297225d180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isLoImm16And ()</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isLoImm16Signed() {#a1b070244459f6f10638b5980da6759de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isLoImm16Signed ()</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#ad9cc57639700272986d246093a5ad1c8a817d6b866eaba4761a3e1aaad6311b13">llvm::LanaiMCExpr::VK_Lanai_ABS_LO</a>.</p>

</div>
</div>

### isLoImm21() {#a3debbf507853ab68544bd4ff00a54a33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isLoImm21 ()</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcexpr/#ad9cc57639700272986d246093a5ad1c8a109977497b87b76b87fa10bd7bca40bc">llvm::LanaiMCExpr::VK_Lanai_None</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### isMem() {#a3e81f8f7b848cfc189c45631f4470b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isMem ()</td>
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

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a626ece2116259c9429017015e3392d23">isMemImm</a>, <a href="#a617ae9ab779f94e2a2b45e449e08aee8">isMemRegImm</a> and <a href="#a96e9cf9b73f441b6ccf8446b3965de69">isMemRegReg</a>.</p>

</div>
</div>

### isMemImm() {#a626ece2116259c9429017015e3392d23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isMemImm ()</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#af9936c1b05850142b1cfbccdfd89faf4">Kind</a> and <a href="#aa8ff80a3592fd38f2712f96eb51ea144a5293f86b07afd549ecdea7e613e2c41a">MEMORY_IMM</a>.</p>


<p>Referenced by <a href="#a3e81f8f7b848cfc189c45631f4470b0f">isMem</a>.</p>

</div>
</div>

### isMemRegImm() {#a617ae9ab779f94e2a2b45e449e08aee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isMemRegImm ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#af9936c1b05850142b1cfbccdfd89faf4">Kind</a> and <a href="#aa8ff80a3592fd38f2712f96eb51ea144a89f3bca72298342d1b9bcb7c0c19600c">MEMORY_REG_IMM</a>.</p>


<p>Referenced by <a href="#adb2d3ecd3f23934a5c6194502f9d758e">addMemSplsOperands</a>, <a href="#a3e81f8f7b848cfc189c45631f4470b0f">isMem</a> and <a href="#af9954ef99fcc113b4f4d1af1a76c7367">isMemSpls</a>.</p>

</div>
</div>

### isMemRegReg() {#a96e9cf9b73f441b6ccf8446b3965de69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isMemRegReg ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#af9936c1b05850142b1cfbccdfd89faf4">Kind</a> and <a href="#aa8ff80a3592fd38f2712f96eb51ea144a1446ff028bd8d7e46b629547c41e0091">MEMORY_REG_REG</a>.</p>


<p>Referenced by <a href="#adb2d3ecd3f23934a5c6194502f9d758e">addMemSplsOperands</a>, <a href="#a3e81f8f7b848cfc189c45631f4470b0f">isMem</a> and <a href="#af9954ef99fcc113b4f4d1af1a76c7367">isMemSpls</a>.</p>

</div>
</div>

### isMemSpls() {#af9954ef99fcc113b4f4d1af1a76c7367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isMemSpls ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a617ae9ab779f94e2a2b45e449e08aee8">isMemRegImm</a> and <a href="#a96e9cf9b73f441b6ccf8446b3965de69">isMemRegReg</a>.</p>

</div>
</div>

### isReg() {#a65e61c4da35f1fd0f5b707127d0deaf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isReg ()</td>
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

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#af9936c1b05850142b1cfbccdfd89faf4">Kind</a> and <a href="#aa8ff80a3592fd38f2712f96eb51ea144a2749eb8ba67660dff3452bd18290db40">REGISTER</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#a14c5fa321a079e20b4a884fee7b7788a">IsMemoryAssignmentError</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#afd44ea11a1de5d05327fb0ef9d20177f">IsRegister</a>.</p>

</div>
</div>

### isToken() {#a512faf94f3d9e5327ca9e170fb1d2863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LanaiAsmParser.cpp}::LanaiOperand::isToken ()</td>
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

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#af9936c1b05850142b1cfbccdfd89faf4">Kind</a> and <a href="#aa8ff80a3592fd38f2712f96eb51ea144a36dac1f8c77839337a68f8cd0c653864">TOKEN</a>.</p>


<p>Referenced by <a href="#a63a7cb8e8bdf283aa515d839190811d7">getToken</a>, <a href="#a3ec20268526405a50b6bb483af902f5a">isBrTarget</a>, <a href="#af4bb149e137d775e094dac3c27fa2a12">isCallTarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#a14c5fa321a079e20b4a884fee7b7788a">IsMemoryAssignmentError</a>.</p>

</div>
</div>

### print() {#a5538a23d0746dd37b532dbaade0fbe9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LanaiAsmParser.cpp}::LanaiOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a>, <a href="#a5dd8eb345a392a179f6ae817c52a6a47">getMemBaseReg</a>, <a href="#ac360a86c8897a5769f817b4b2117bca4">getMemOffset</a>, <a href="#a43ff5a61c7d69362c123a763e1abcc89">getMemOffsetReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20237283e8b9e354abec8dc5ab16bd16">llvm::getToken</a>, <a href="#aa8ff80a3592fd38f2712f96eb51ea144a2a3bd4906d93cc674c70d3317ccb3152">IMMEDIATE</a>, <a href="#af9936c1b05850142b1cfbccdfd89faf4">Kind</a>, <a href="#aa8ff80a3592fd38f2712f96eb51ea144a5293f86b07afd549ecdea7e613e2c41a">MEMORY_IMM</a>, <a href="#aa8ff80a3592fd38f2712f96eb51ea144a89f3bca72298342d1b9bcb7c0c19600c">MEMORY_REG_IMM</a>, <a href="#aa8ff80a3592fd38f2712f96eb51ea144a1446ff028bd8d7e46b629547c41e0091">MEMORY_REG_REG</a>, <a href="#aa8ff80a3592fd38f2712f96eb51ea144a2749eb8ba67660dff3452bd18290db40">REGISTER</a> and <a href="#aa8ff80a3592fd38f2712f96eb51ea144a36dac1f8c77839337a68f8cd0c653864">TOKEN</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#ae5f75e65cf4499bac6d5b797a9585404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{LanaiAsmParser.cpp}::LanaiOperand anonymous{LanaiAsmParser.cpp}::LanaiOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>

</div>
</div>

### EndLoc {#a52a6b282353ede47cef740f02e0e4b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{LanaiAsmParser.cpp}::LanaiOperand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#aaedd09a65c8d8a7394b4e3c4144ccf34">getEndLoc</a>.</p>

</div>
</div>

### Imm {#a1c1e148b3f35f1940bad9af9e8b79614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ImmOp anonymous{LanaiAsmParser.cpp}::LanaiOperand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a39f9673926289aecff3b7f94bdc3c0bb">getImm</a>, <a href="#ab6b0c7909cd1c59c0450d9d1a8493bc9">isBrImm</a>, <a href="#ae57fbd0e584ec2382b9940e01e19d768">isCondCode</a>, <a href="#aebf98c08c7ee4d1244bbc1b9b89cd0ea">isHiImm16</a>, <a href="#a7a980e5bb4840109e1822c062cbfafa7">isHiImm16And</a>, <a href="#acb23248dfc6a00019f3f78d74a2b45b1">isImm10</a>, <a href="#a3aaf84fd1fc76bb95d588ff92b53c672">isImmShift</a>, <a href="#a6f72e54d11a94c9f7ed915863773bd69">isLoImm16</a>, <a href="#ade0aa7301c37915069aa87297225d180">isLoImm16And</a>, <a href="#a1b070244459f6f10638b5980da6759de">isLoImm16Signed</a>, <a href="#a3debbf507853ab68544bd4ff00a54a33">isLoImm21</a>, <a href="#ab51fd29f0c7b93190ced07ea70aa2ee4">MorphToMemImm</a> and <a href="#a82d054df25bf91c180b93f642563943c">MorphToMemRegImm</a>.</p>

</div>
</div>

### Kind {#af9936c1b05850142b1cfbccdfd89faf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{LanaiAsmParser.cpp}::LanaiOperand::KindTy anonymous{LanaiAsmParser.cpp}::LanaiOperand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a65adaddf2904bdfde259aff897c1a394">isImm</a>, <a href="#a626ece2116259c9429017015e3392d23">isMemImm</a>, <a href="#a617ae9ab779f94e2a2b45e449e08aee8">isMemRegImm</a>, <a href="#a96e9cf9b73f441b6ccf8446b3965de69">isMemRegReg</a>, <a href="#a65e61c4da35f1fd0f5b707127d0deaf3">isReg</a>, <a href="#a512faf94f3d9e5327ca9e170fb1d2863">isToken</a>, <a href="#a66aaea6b10c59bb990994e41e73d0cc9">LanaiOperand</a> and <a href="#a5538a23d0746dd37b532dbaade0fbe9f">print</a>.</p>

</div>
</div>

### Mem {#a2a8279225300238840d1471fcca15f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct MemOp anonymous{LanaiAsmParser.cpp}::LanaiOperand::Mem</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a5dd8eb345a392a179f6ae817c52a6a47">getMemBaseReg</a>, <a href="#ac360a86c8897a5769f817b4b2117bca4">getMemOffset</a>, <a href="#a43ff5a61c7d69362c123a763e1abcc89">getMemOffsetReg</a> and <a href="#ab58b6d95c7e58e6c2924e02797d67705">getMemOp</a>.</p>

</div>
</div>

### Reg {#a70568198e71ea489ac0358df83295ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct RegOp anonymous{LanaiAsmParser.cpp}::LanaiOperand::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a89c86dfc90c1c7a2870b31d1912365cc">createReg</a> and <a href="#a8df742095eda8b544c2c418d92821368">getReg</a>.</p>

</div>
</div>

### StartLoc {#a26ee3e85800b353b5c4adf8eb4e95000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{LanaiAsmParser.cpp}::LanaiOperand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#abc6f4c0a0a71ab332c6311fdf3cbbdd8">getStartLoc</a>.</p>

</div>
</div>

### Tok {#a9538df811284f3dc3d73e1208635e5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct Token anonymous{LanaiAsmParser.cpp}::LanaiOperand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a63a7cb8e8bdf283aa515d839190811d7">getToken</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createImm() {#abac8e5efcee7c675442d4b6e1c9c7cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LanaiOperand &gt; anonymous{LanaiAsmParser.cpp}::LanaiOperand::createImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End)</td>
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



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa8ff80a3592fd38f2712f96eb51ea144a2a3bd4906d93cc674c70d3317ccb3152">IMMEDIATE</a>.</p>

</div>
</div>

### createReg() {#a89c86dfc90c1c7a2870b31d1912365cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LanaiOperand &gt; anonymous{LanaiAsmParser.cpp}::LanaiOperand::createReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End)</td>
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



<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a70568198e71ea489ac0358df83295ecc">Reg</a> and <a href="#aa8ff80a3592fd38f2712f96eb51ea144a2749eb8ba67660dff3452bd18290db40">REGISTER</a>.</p>

</div>
</div>

### CreateToken() {#a9e3cfef4622f389752d819004e3884b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LanaiOperand &gt; anonymous{LanaiAsmParser.cpp}::LanaiOperand::CreateToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start)</td>
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



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa8ff80a3592fd38f2712f96eb51ea144a36dac1f8c77839337a68f8cd0c653864">TOKEN</a>.</p>

</div>
</div>

### MorphToMemImm() {#ab51fd29f0c7b93190ced07ea70aa2ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LanaiOperand &gt; anonymous{LanaiAsmParser.cpp}::LanaiOperand::MorphToMemImm (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand">LanaiOperand</a> &gt; Op)</td>
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



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lpac/#ab2e8fd263c886a713ccba7505c1b2ee0a25d8ba0c31384de6b8eaf87262199804">llvm::LPAC::ADD</a>, <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a> and <a href="#aa8ff80a3592fd38f2712f96eb51ea144a5293f86b07afd549ecdea7e613e2c41a">MEMORY_IMM</a>.</p>

</div>
</div>

### MorphToMemRegImm() {#a82d054df25bf91c180b93f642563943c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LanaiOperand &gt; anonymous{LanaiAsmParser.cpp}::LanaiOperand::MorphToMemRegImm (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> BaseReg, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand">LanaiOperand</a> &gt; Op, unsigned AluOp)</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>References <a href="#a1c1e148b3f35f1940bad9af9e8b79614">Imm</a> and <a href="#aa8ff80a3592fd38f2712f96eb51ea144a89f3bca72298342d1b9bcb7c0c19600c">MEMORY_REG_IMM</a>.</p>

</div>
</div>

### MorphToMemRegReg() {#a79a36528f23f14fb20be4d50b1aa8b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LanaiOperand &gt; anonymous{LanaiAsmParser.cpp}::LanaiOperand::MorphToMemRegReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> BaseReg, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand">LanaiOperand</a> &gt; Op, unsigned AluOp)</td>
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



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a>.</p>


<p>Reference <a href="#aa8ff80a3592fd38f2712f96eb51ea144a1446ff028bd8d7e46b629547c41e0091">MEMORY_REG_REG</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp">LanaiAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
