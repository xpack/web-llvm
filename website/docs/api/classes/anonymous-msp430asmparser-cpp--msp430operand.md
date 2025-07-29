---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-msp430asmparser-cpp-/msp430operand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MSP430Operand` Class

<p>A parsed <a href="/web-llvm/docs/api/namespaces/llvm/msp430">MSP430</a> assembly operand. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MSP430AsmParser.cpp}::MSP430Operand { ... }
</div>

## Base class

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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a> <a href="#abc6c3cf9b294b11649a1f4b350fc0bb5">Base</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#a85c794d0dc12de97846026c475659b8b">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c96fc6096b84022ae9d9262373f4612">MSP430Operand</a> (StringRef Tok, SMLoc const &amp;S)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956f44b555ad70bc07d2b1e3ad56141d">MSP430Operand</a> (KindTy Kind, MCRegister Reg, SMLoc const &amp;S, SMLoc const &amp;E)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7969387aaa6549fe6877633078d2b91">MSP430Operand</a> (MCExpr const *Imm, SMLoc const &amp;S, SMLoc const &amp;E)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e46b149d4ac8eb72be4d083f028d73b">MSP430Operand</a> (MCRegister Reg, MCExpr const *Expr, SMLoc const &amp;S, SMLoc const &amp;E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c6549504302b3b1bd7ef56e56b1379">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2ddbddfcf39f25f8909b8a9a16312f">addExprOperand</a> (MCInst &amp;Inst, const MCExpr *Expr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad795b1ef17d0c2d436c386a9190c3710">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f292c019d2b087fc36a88099ea71a4">addMemOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f2fc6eab167edce38a6b62a69b97ae">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#a66f2fc6eab167edce38a6b62a69b97ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af427044ee45bf41e2ab7456ff69b0e19">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#af427044ee45bf41e2ab7456ff69b0e19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c129b1f688487a0f274f5c9c08a3167">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#a8c129b1f688487a0f274f5c9c08a3167">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40ced6917be348be5a0b582cea68e977">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#a40ced6917be348be5a0b582cea68e977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60848820c69b1c04c74cfff54545dc76">isIndReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4049e2cfac33820a9f22ddbe969027f5">isPostIndReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae28c2379bdc634e961e57b8affc65bd7">isCGImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f26382512e4f971038add4d56d57ae">getToken</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e1efd5e49a3a027d181a6bef950673">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65596fd9854984ef18515540cca6760">setReg</a> (MCRegister RegNo)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fae598d21560ec42ea1929dde7280ff">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Get the location of the first token of this operand. <a href="#a0fae598d21560ec42ea1929dde7280ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae846fa93b92d96bcea2228becf59ee6a">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Get the location of the last token of this operand. <a href="#ae846fa93b92d96bcea2228becf59ee6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8009d79470031a382a5f6f977a443cb">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#af8009d79470031a382a5f6f977a443cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f2927cb9a47e00d5ed1ed9d14a82cb1">Imm</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc6594a09528f334ec3afd11195ec50">Tok</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Memory</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a005cbcd159587f267451a9d0ba760002">Mem</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{MSP430AsmParser.cpp}::MSP430Operand::KindTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f22e7321754cec8a990a691030477e3">Kind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{MSP430AsmParser.cpp}<a href="#a4c96fc6096b84022ae9d9262373f4612">::MSP430Operand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2758076656c6e09dd1324f614a2942d1"></a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41db5e4ba6a85006ed2117cc698a9fbf">Start</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c52ef1135c334e32bf3563e868afa7">End</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand">MSP430Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7211b20a8d88bf8e7bb69694ff203fe8">CreateToken</a> (StringRef Str, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand">MSP430Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9df297a79752e4d68504167db3da7e">CreateReg</a> (MCRegister Reg, SMLoc S, SMLoc E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand">MSP430Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86e875f604b25232a8ea7daf5464000">CreateImm</a> (const MCExpr *Val, SMLoc S, SMLoc E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand">MSP430Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a025b8228f376cbfd2d8b04d1da9e6991">CreateMem</a> (MCRegister Reg, const MCExpr *Val, SMLoc S, SMLoc E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand">MSP430Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5266be8744e34e83902948c164a7d01">CreateIndReg</a> (MCRegister Reg, SMLoc S, SMLoc E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand">MSP430Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad68b41db92173137bffc7c332731c01b">CreatePostIndReg</a> (MCRegister Reg, SMLoc S, SMLoc E)</td>
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

<p>A parsed <a href="/web-llvm/docs/api/namespaces/llvm/msp430">MSP430</a> assembly operand.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Base {#abc6c3cf9b294b11649a1f4b350fc0bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef MCParsedAsmOperand anonymous{MSP430AsmParser.cpp}::MSP430Operand::Base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### KindTy {#a85c794d0dc12de97846026c475659b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MSP430AsmParser.cpp}::MSP430Operand::KindTy </td>
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
<td class="doxyEnumItemName">k_Imm<a id="a85c794d0dc12de97846026c475659b8bab146d1f93ff5290f4007c8f46b2dc330"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_Reg<a id="a85c794d0dc12de97846026c475659b8ba08ea31e49e56835478df67dd16501757"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_Tok<a id="a85c794d0dc12de97846026c475659b8bacad4eb90f1aa5ed3f4cf3782144c7b22"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_Mem<a id="a85c794d0dc12de97846026c475659b8badbca0b8889e49d84e83d4bde6fb94ce3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_IndReg<a id="a85c794d0dc12de97846026c475659b8baf5a5c5d8ed7abd2b6940d3b55c20a568"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_PostIndReg<a id="a85c794d0dc12de97846026c475659b8ba67b99d8904d750d51a99d179fe27e60a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MSP430Operand() {#a4c96fc6096b84022ae9d9262373f4612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MSP430AsmParser.cpp}::MSP430Operand::MSP430Operand (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Tok, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; S)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Reference <a href="#acfc6594a09528f334ec3afd11195ec50">Tok</a>.</p>

</div>
</div>

### MSP430Operand() {#a956f44b555ad70bc07d2b1e3ad56141d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MSP430AsmParser.cpp}::MSP430Operand::MSP430Operand (KindTy Kind, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; E)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Reference <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a>.</p>

</div>
</div>

### MSP430Operand() {#ae7969387aaa6549fe6877633078d2b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MSP430AsmParser.cpp}::MSP430Operand::MSP430Operand (<a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Imm, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; E)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Reference <a href="#a2f2927cb9a47e00d5ed1ed9d14a82cb1">Imm</a>.</p>

</div>
</div>

### MSP430Operand() {#a4e46b149d4ac8eb72be4d083f028d73b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MSP430AsmParser.cpp}::MSP430Operand::MSP430Operand (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; E)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="#a005cbcd159587f267451a9d0ba760002">Mem</a> and <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addExprOperand() {#a4b2ddbddfcf39f25f8909b8a9a16312f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MSP430AsmParser.cpp}::MSP430Operand::addExprOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#ad795b1ef17d0c2d436c386a9190c3710">addImmOperands</a> and <a href="#af6f292c019d2b087fc36a88099ea71a4">addMemOperands</a>.</p>

</div>
</div>

### addImmOperands() {#ad795b1ef17d0c2d436c386a9190c3710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MSP430AsmParser.cpp}::MSP430Operand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="#a4b2ddbddfcf39f25f8909b8a9a16312f">addExprOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2f2927cb9a47e00d5ed1ed9d14a82cb1">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMemOperands() {#af6f292c019d2b087fc36a88099ea71a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MSP430AsmParser.cpp}::MSP430Operand::addMemOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="#a4b2ddbddfcf39f25f8909b8a9a16312f">addExprOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a005cbcd159587f267451a9d0ba760002">Mem</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#a52c6549504302b3b1bd7ef56e56b1379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MSP430AsmParser.cpp}::MSP430Operand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a>.</p>

</div>
</div>

### getEndLoc() {#ae846fa93b92d96bcea2228becf59ee6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{MSP430AsmParser.cpp}::MSP430Operand::getEndLoc ()</td>
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

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### getReg() {#a14e1efd5e49a3a027d181a6bef950673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{MSP430AsmParser.cpp}::MSP430Operand::getReg ()</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a>.</p>

</div>
</div>

### getStartLoc() {#a0fae598d21560ec42ea1929dde7280ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{MSP430AsmParser.cpp}::MSP430Operand::getStartLoc ()</td>
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

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### getToken() {#a74f26382512e4f971038add4d56d57ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MSP430AsmParser.cpp}::MSP430Operand::getToken ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#acfc6594a09528f334ec3afd11195ec50">Tok</a>.</p>

</div>
</div>

### isCGImm() {#ae28c2379bdc634e961e57b8affc65bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MSP430AsmParser.cpp}::MSP430Operand::isCGImm ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Reference <a href="#a2f2927cb9a47e00d5ed1ed9d14a82cb1">Imm</a>.</p>

</div>
</div>

### isImm() {#af427044ee45bf41e2ab7456ff69b0e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MSP430AsmParser.cpp}::MSP430Operand::isImm ()</td>
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

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### isIndReg() {#a60848820c69b1c04c74cfff54545dc76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MSP430AsmParser.cpp}::MSP430Operand::isIndReg ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### isMem() {#a40ced6917be348be5a0b582cea68e977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MSP430AsmParser.cpp}::MSP430Operand::isMem ()</td>
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

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### isPostIndReg() {#a4049e2cfac33820a9f22ddbe969027f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MSP430AsmParser.cpp}::MSP430Operand::isPostIndReg ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### isReg() {#a66f2fc6eab167edce38a6b62a69b97ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MSP430AsmParser.cpp}::MSP430Operand::isReg ()</td>
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

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### isToken() {#a8c129b1f688487a0f274f5c9c08a3167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MSP430AsmParser.cpp}::MSP430Operand::isToken ()</td>
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

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### print() {#af8009d79470031a382a5f6f977a443cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MSP430AsmParser.cpp}::MSP430Operand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="#a2f2927cb9a47e00d5ed1ed9d14a82cb1">Imm</a>, <a href="#a005cbcd159587f267451a9d0ba760002">Mem</a>, <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a> and <a href="#acfc6594a09528f334ec3afd11195ec50">Tok</a>.</p>

</div>
</div>

### setReg() {#ad65596fd9854984ef18515540cca6760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MSP430AsmParser.cpp}::MSP430Operand::setReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNo)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Imm {#a2f2927cb9a47e00d5ed1ed9d14a82cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* anonymous{MSP430AsmParser.cpp}::MSP430Operand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ad795b1ef17d0c2d436c386a9190c3710">addImmOperands</a>, <a href="#ae28c2379bdc634e961e57b8affc65bd7">isCGImm</a>, <a href="#ae7969387aaa6549fe6877633078d2b91">MSP430Operand</a> and <a href="#af8009d79470031a382a5f6f977a443cb">print</a>.</p>

</div>
</div>

### Mem {#a005cbcd159587f267451a9d0ba760002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Memory anonymous{MSP430AsmParser.cpp}::MSP430Operand::Mem</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#af6f292c019d2b087fc36a88099ea71a4">addMemOperands</a>, <a href="#a4e46b149d4ac8eb72be4d083f028d73b">MSP430Operand</a> and <a href="#af8009d79470031a382a5f6f977a443cb">print</a>.</p>

</div>
</div>

### Reg {#a1f2021881eb98234adac4bd0d92148df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{MSP430AsmParser.cpp}::MSP430Operand::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a52c6549504302b3b1bd7ef56e56b1379">addRegOperands</a>, <a href="#af5266be8744e34e83902948c164a7d01">CreateIndReg</a>, <a href="#a025b8228f376cbfd2d8b04d1da9e6991">CreateMem</a>, <a href="#ad68b41db92173137bffc7c332731c01b">CreatePostIndReg</a>, <a href="#a1e9df297a79752e4d68504167db3da7e">CreateReg</a>, <a href="#a14e1efd5e49a3a027d181a6bef950673">getReg</a>, <a href="#a956f44b555ad70bc07d2b1e3ad56141d">MSP430Operand</a>, <a href="#a4e46b149d4ac8eb72be4d083f028d73b">MSP430Operand</a>, <a href="#af8009d79470031a382a5f6f977a443cb">print</a> and <a href="#ad65596fd9854984ef18515540cca6760">setReg</a>.</p>

</div>
</div>

### Tok {#acfc6594a09528f334ec3afd11195ec50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MSP430AsmParser.cpp}::MSP430Operand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a74f26382512e4f971038add4d56d57ae">getToken</a>, <a href="#a4c96fc6096b84022ae9d9262373f4612">MSP430Operand</a> and <a href="#af8009d79470031a382a5f6f977a443cb">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a2758076656c6e09dd1324f614a2942d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{MSP430AsmParser.cpp}::MSP430Operand anonymous{MSP430AsmParser.cpp}::MSP430Operand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### End {#a85c52ef1135c334e32bf3563e868afa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{MSP430AsmParser.cpp}::MSP430Operand::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### Kind {#a1f22e7321754cec8a990a691030477e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MSP430AsmParser.cpp}::MSP430Operand::KindTy anonymous{MSP430AsmParser.cpp}::MSP430Operand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### Start {#a41db5e4ba6a85006ed2117cc698a9fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{MSP430AsmParser.cpp}::MSP430Operand::Start</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CreateImm() {#ae86e875f604b25232a8ea7daf5464000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MSP430Operand &gt; anonymous{MSP430AsmParser.cpp}::MSP430Operand::CreateImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

### CreateIndReg() {#af5266be8744e34e83902948c164a7d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MSP430Operand &gt; anonymous{MSP430AsmParser.cpp}::MSP430Operand::CreateIndReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Reference <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a>.</p>

</div>
</div>

### CreateMem() {#a025b8228f376cbfd2d8b04d1da9e6991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MSP430Operand &gt; anonymous{MSP430AsmParser.cpp}::MSP430Operand::CreateMem (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Reference <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a>.</p>

</div>
</div>

### CreatePostIndReg() {#ad68b41db92173137bffc7c332731c01b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MSP430Operand &gt; anonymous{MSP430AsmParser.cpp}::MSP430Operand::CreatePostIndReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Reference <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a>.</p>

</div>
</div>

### CreateReg() {#a1e9df297a79752e4d68504167db3da7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MSP430Operand &gt; anonymous{MSP430AsmParser.cpp}::MSP430Operand::CreateReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>


<p>Reference <a href="#a1f2021881eb98234adac4bd0d92148df">Reg</a>.</p>

</div>
</div>

### CreateToken() {#a7211b20a8d88bf8e7bb69694ff203fe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MSP430Operand &gt; anonymous{MSP430AsmParser.cpp}::MSP430Operand::CreateToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp">MSP430AsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
