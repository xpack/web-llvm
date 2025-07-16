---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `WebAssemblyOperand` Struct Reference

<p><a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand">WebAssemblyOperand</a> - Instances of this class represent the operands in a parsed Wasm machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#a514ae09aabfe5228ce2da14cc7deee6d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ef9eb97030d89c30ef0e119b77493b">WebAssemblyOperand</a> (SMLoc Start, SMLoc End, TokOp T)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10331f5f11a0820e143f264f219abb60">WebAssemblyOperand</a> (SMLoc Start, SMLoc End, IntOp I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79bb0087b45e534fd21f2737b7630cc5">WebAssemblyOperand</a> (SMLoc Start, SMLoc End, FltOp F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15b5347772744464650c8298ff218a05">WebAssemblyOperand</a> (SMLoc Start, SMLoc End, SymOp S)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ff2abedbc46a52544d7536dc6c4200">WebAssemblyOperand</a> (SMLoc Start, SMLoc End, BrLOp B)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bd353a0b1fc4914971dd2b835dbb0c">WebAssemblyOperand</a> (SMLoc Start, SMLoc End, CaLOp C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7161af619720b2e924b6ee6b74df82bf">~WebAssemblyOperand</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d8d92b5c02423eeb1be46843dbea7a">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#a57d8d92b5c02423eeb1be46843dbea7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca517b72e2452f383b379119de73449">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#a6ca517b72e2452f383b379119de73449">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69da41a89dd5c734e825b03fb66f6483">isFPImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a2f0f314083cd035762ab5798cac7c">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#ad6a2f0f314083cd035762ab5798cac7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10510da890870caeb8fabfacca361a57">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#a10510da890870caeb8fabfacca361a57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea73ed70bdc7865b84380fbcdc7f69b">isBrList</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70102ed41316ae23e907410a5305a6a4">isCatchList</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21410a037e267b2c6b46fd4c8fbcb8b0">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7090305f9998619ef1341e0610c0ad43">getToken</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdaa341b7a8359420c16ea5e712bd06f">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Get the location of the first token of this operand. <a href="#afdaa341b7a8359420c16ea5e712bd06f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addca181060e92b1523dbb78b0f4ebd82">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Get the location of the last token of this operand. <a href="#addca181060e92b1523dbb78b0f4ebd82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a87536ccf220359cf152936a7bdcb0c">addRegOperands</a> (MCInst &amp;, unsigned) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1843f39a0d50d963f92c5f1fe30b633e">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897c9e930c31d4b65408c09c73d6a417">addFPImmf32Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcb95d1f0d9f65bf8d7fb3e60601c57">addFPImmf64Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8896b0d3d3c22e3b36197de128dd7fd6">addBrListOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20abe1ede172e9ba62511e7892a43051">addCatchListOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d7f1477e16e4c0bbc4950af5e7a958">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#a82d7f1477e16e4c0bbc4950af5e7a958">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{WebAssemblyAsmParser.cpp}<a href="#a514ae09aabfe5228ce2da14cc7deee6d">::WebAssemblyOperand::KindTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a530617d1eb02beea0911de865ac257a4">StartLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3b9d12cff86d47f8035c707d0f0118d">EndLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a443a426ff5152d394556181d8c89dd03">Tok</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194e5ceda0deed4b388b81a233463b89">Int</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fbdb6bcba5026cca0cae320cb9b4088">Flt</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975c5ba34b2dbeaf5dfeac01e7524f97">Sym</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b9be4c450b1ebe36cea878f63afd594">BrL</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77426c5ad774fd208d3e417b7d1ad42e">CaL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{WebAssemblyAsmParser.cpp}<a href="#a22ef9eb97030d89c30ef0e119b77493b">::WebAssemblyOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca648594c15025103b03d65861c52fa"></a></td>
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

<p><a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand">WebAssemblyOperand</a> - Instances of this class represent the operands in a parsed Wasm machine instruction.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### KindTy {#a514ae09aabfe5228ce2da14cc7deee6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::KindTy </td>
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
<td class="doxyEnumItemName">Token<a id="a514ae09aabfe5228ce2da14cc7deee6da93b5488901707d43b16652c260b3ca07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Integer<a id="a514ae09aabfe5228ce2da14cc7deee6dad9e10b5e087a0911780dddc5d29b5499"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Float<a id="a514ae09aabfe5228ce2da14cc7deee6da815b08a0b66a6c0140053fda826b218c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Symbol<a id="a514ae09aabfe5228ce2da14cc7deee6da7596cdf670b3170a7dc7e68c7524209d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BrList<a id="a514ae09aabfe5228ce2da14cc7deee6da5b375c4c7c4fa1a1b497e97f0f0fdcdd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CatchList<a id="a514ae09aabfe5228ce2da14cc7deee6dad2b98f8dc8ab025686213d07393f5512"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### WebAssemblyOperand() {#a22ef9eb97030d89c30ef0e119b77493b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::WebAssemblyOperand (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/tokop">TokOp</a> T)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#ac3b9d12cff86d47f8035c707d0f0118d">EndLoc</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a>, <a href="#a530617d1eb02beea0911de865ac257a4">StartLoc</a>, <a href="#a443a426ff5152d394556181d8c89dd03">Tok</a> and <a href="#a514ae09aabfe5228ce2da14cc7deee6da93b5488901707d43b16652c260b3ca07">Token</a>.</p>

</div>
</div>

### WebAssemblyOperand() {#a10331f5f11a0820e143f264f219abb60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::WebAssemblyOperand (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/intop">IntOp</a> I)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#ac3b9d12cff86d47f8035c707d0f0118d">EndLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a194e5ceda0deed4b388b81a233463b89">Int</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6dad9e10b5e087a0911780dddc5d29b5499">Integer</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a> and <a href="#a530617d1eb02beea0911de865ac257a4">StartLoc</a>.</p>

</div>
</div>

### WebAssemblyOperand() {#a79bb0087b45e534fd21f2737b7630cc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::WebAssemblyOperand (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/fltop">FltOp</a> F)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#ac3b9d12cff86d47f8035c707d0f0118d">EndLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6da815b08a0b66a6c0140053fda826b218c">Float</a>, <a href="#a3fbdb6bcba5026cca0cae320cb9b4088">Flt</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a> and <a href="#a530617d1eb02beea0911de865ac257a4">StartLoc</a>.</p>

</div>
</div>

### WebAssemblyOperand() {#a15b5347772744464650c8298ff218a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::WebAssemblyOperand (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/symop">SymOp</a> S)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#ac3b9d12cff86d47f8035c707d0f0118d">EndLoc</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a>, <a href="#a530617d1eb02beea0911de865ac257a4">StartLoc</a>, <a href="#a975c5ba34b2dbeaf5dfeac01e7524f97">Sym</a> and <a href="#a514ae09aabfe5228ce2da14cc7deee6da7596cdf670b3170a7dc7e68c7524209d">Symbol</a>.</p>

</div>
</div>

### WebAssemblyOperand() {#a84ff2abedbc46a52544d7536dc6c4200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::WebAssemblyOperand (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/brlop">BrLOp</a> B)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a6b9be4c450b1ebe36cea878f63afd594">BrL</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6da5b375c4c7c4fa1a1b497e97f0f0fdcdd">BrList</a>, <a href="#ac3b9d12cff86d47f8035c707d0f0118d">EndLoc</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a> and <a href="#a530617d1eb02beea0911de865ac257a4">StartLoc</a>.</p>

</div>
</div>

### WebAssemblyOperand() {#ae2bd353a0b1fc4914971dd2b835dbb0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::WebAssemblyOperand (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/calop">CaLOp</a> C)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a77426c5ad774fd208d3e417b7d1ad42e">CaL</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6dad2b98f8dc8ab025686213d07393f5512">CatchList</a>, <a href="#ac3b9d12cff86d47f8035c707d0f0118d">EndLoc</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a> and <a href="#a530617d1eb02beea0911de865ac257a4">StartLoc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WebAssemblyOperand() {#a7161af619720b2e924b6ee6b74df82bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::~WebAssemblyOperand ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#a6b9be4c450b1ebe36cea878f63afd594">BrL</a>, <a href="#a77426c5ad774fd208d3e417b7d1ad42e">CaL</a>, <a href="#a2ea73ed70bdc7865b84380fbcdc7f69b">isBrList</a> and <a href="#a70102ed41316ae23e907410a5305a6a4">isCatchList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBrListOperands() {#a8896b0d3d3c22e3b36197de128dd7fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addBrListOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6b9be4c450b1ebe36cea878f63afd594">BrL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a2ea73ed70bdc7865b84380fbcdc7f69b">isBrList</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addCatchListOperands() {#a20abe1ede172e9ba62511e7892a43051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addCatchListOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a77426c5ad774fd208d3e417b7d1ad42e">CaL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a70102ed41316ae23e907410a5305a6a4">isCatchList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a375966ac0e4dd9dfc317d2834f5e0f4ba3ca3ba67f4bcede39109b409811d8d83">llvm::wasm::WASM_OPCODE_CATCH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a375966ac0e4dd9dfc317d2834f5e0f4ba55e4b9989bc5f2f792e7d1b25048271b">llvm::wasm::WASM_OPCODE_CATCH_REF</a>.</p>

</div>
</div>

### addFPImmf32Operands() {#a897c9e930c31d4b65408c09c73d6a417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addFPImmf32Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a28d125e6f6bba87ccb0032ddceeb6c47">llvm::MCOperand::createSFPImm</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6da815b08a0b66a6c0140053fda826b218c">Float</a>, <a href="#a3fbdb6bcba5026cca0cae320cb9b4088">Flt</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addFPImmf64Operands() {#a3bcb95d1f0d9f65bf8d7fb3e60601c57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addFPImmf64Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ad813d2ab5c4ffc7d5f6172735b44ca1a">llvm::MCOperand::createDFPImm</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6da815b08a0b66a6c0140053fda826b218c">Float</a>, <a href="#a3fbdb6bcba5026cca0cae320cb9b4088">Flt</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmOperands() {#a1843f39a0d50d963f92c5f1fe30b633e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a194e5ceda0deed4b388b81a233463b89">Int</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6dad9e10b5e087a0911780dddc5d29b5499">Integer</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a975c5ba34b2dbeaf5dfeac01e7524f97">Sym</a> and <a href="#a514ae09aabfe5228ce2da14cc7deee6da7596cdf670b3170a7dc7e68c7524209d">Symbol</a>.</p>

</div>
</div>

### addRegOperands() {#a3a87536ccf220359cf152936a7bdcb0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp;, unsigned)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getEndLoc() {#addca181060e92b1523dbb78b0f4ebd82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::getEndLoc ()</td>
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

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Reference <a href="#ac3b9d12cff86d47f8035c707d0f0118d">EndLoc</a>.</p>

</div>
</div>

### getReg() {#a21410a037e267b2c6b46fd4c8fbcb8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::getReg ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getStartLoc() {#afdaa341b7a8359420c16ea5e712bd06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::getStartLoc ()</td>
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

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Reference <a href="#a530617d1eb02beea0911de865ac257a4">StartLoc</a>.</p>

</div>
</div>

### getToken() {#a7090305f9998619ef1341e0610c0ad43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::getToken ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a57d8d92b5c02423eeb1be46843dbea7a">isToken</a> and <a href="#a443a426ff5152d394556181d8c89dd03">Tok</a>.</p>

</div>
</div>

### isBrList() {#a2ea73ed70bdc7865b84380fbcdc7f69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::isBrList ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#a514ae09aabfe5228ce2da14cc7deee6da5b375c4c7c4fa1a1b497e97f0f0fdcdd">BrList</a> and <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a>.</p>


<p>Referenced by <a href="#a8896b0d3d3c22e3b36197de128dd7fd6">addBrListOperands</a> and <a href="#a7161af619720b2e924b6ee6b74df82bf">~WebAssemblyOperand</a>.</p>

</div>
</div>

### isCatchList() {#a70102ed41316ae23e907410a5305a6a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::isCatchList ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#a514ae09aabfe5228ce2da14cc7deee6dad2b98f8dc8ab025686213d07393f5512">CatchList</a> and <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a>.</p>


<p>Referenced by <a href="#a20abe1ede172e9ba62511e7892a43051">addCatchListOperands</a> and <a href="#a7161af619720b2e924b6ee6b74df82bf">~WebAssemblyOperand</a>.</p>

</div>
</div>

### isFPImm() {#a69da41a89dd5c734e825b03fb66f6483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::isFPImm ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#a514ae09aabfe5228ce2da14cc7deee6da815b08a0b66a6c0140053fda826b218c">Float</a> and <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a>.</p>

</div>
</div>

### isImm() {#a6ca517b72e2452f383b379119de73449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::isImm ()</td>
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

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#a514ae09aabfe5228ce2da14cc7deee6dad9e10b5e087a0911780dddc5d29b5499">Integer</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a> and <a href="#a514ae09aabfe5228ce2da14cc7deee6da7596cdf670b3170a7dc7e68c7524209d">Symbol</a>.</p>

</div>
</div>

### isMem() {#ad6a2f0f314083cd035762ab5798cac7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::isMem ()</td>
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

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>

</div>
</div>

### isReg() {#a10510da890870caeb8fabfacca361a57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::isReg ()</td>
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

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>

</div>
</div>

### isToken() {#a57d8d92b5c02423eeb1be46843dbea7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::isToken ()</td>
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

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a> and <a href="#a514ae09aabfe5228ce2da14cc7deee6da93b5488901707d43b16652c260b3ca07">Token</a>.</p>


<p>Referenced by <a href="#a7090305f9998619ef1341e0610c0ad43">getToken</a>.</p>

</div>
</div>

### print() {#a82d7f1477e16e4c0bbc4950af5e7a958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>References <a href="#a6b9be4c450b1ebe36cea878f63afd594">BrL</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6da5b375c4c7c4fa1a1b497e97f0f0fdcdd">BrList</a>, <a href="#a77426c5ad774fd208d3e417b7d1ad42e">CaL</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6dad2b98f8dc8ab025686213d07393f5512">CatchList</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6da815b08a0b66a6c0140053fda826b218c">Float</a>, <a href="#a3fbdb6bcba5026cca0cae320cb9b4088">Flt</a>, <a href="#a194e5ceda0deed4b388b81a233463b89">Int</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6dad9e10b5e087a0911780dddc5d29b5499">Integer</a>, <a href="#a224a0ccf7728c66d3a484cd996aa591b">Kind</a>, <a href="#a975c5ba34b2dbeaf5dfeac01e7524f97">Sym</a>, <a href="#a514ae09aabfe5228ce2da14cc7deee6da7596cdf670b3170a7dc7e68c7524209d">Symbol</a>, <a href="#a443a426ff5152d394556181d8c89dd03">Tok</a> and <a href="#a514ae09aabfe5228ce2da14cc7deee6da93b5488901707d43b16652c260b3ca07">Token</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#abca648594c15025103b03d65861c52fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>

</div>
</div>

### BrL {#a6b9be4c450b1ebe36cea878f63afd594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct BrLOp anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::BrL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a8896b0d3d3c22e3b36197de128dd7fd6">addBrListOperands</a>, <a href="#a82d7f1477e16e4c0bbc4950af5e7a958">print</a>, <a href="#a84ff2abedbc46a52544d7536dc6c4200">WebAssemblyOperand</a> and <a href="#a7161af619720b2e924b6ee6b74df82bf">~WebAssemblyOperand</a>.</p>

</div>
</div>

### CaL {#a77426c5ad774fd208d3e417b7d1ad42e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct CaLOp anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::CaL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a20abe1ede172e9ba62511e7892a43051">addCatchListOperands</a>, <a href="#a82d7f1477e16e4c0bbc4950af5e7a958">print</a>, <a href="#ae2bd353a0b1fc4914971dd2b835dbb0c">WebAssemblyOperand</a> and <a href="#a7161af619720b2e924b6ee6b74df82bf">~WebAssemblyOperand</a>.</p>

</div>
</div>

### EndLoc {#ac3b9d12cff86d47f8035c707d0f0118d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#addca181060e92b1523dbb78b0f4ebd82">getEndLoc</a>, <a href="#a84ff2abedbc46a52544d7536dc6c4200">WebAssemblyOperand</a>, <a href="#ae2bd353a0b1fc4914971dd2b835dbb0c">WebAssemblyOperand</a>, <a href="#a79bb0087b45e534fd21f2737b7630cc5">WebAssemblyOperand</a>, <a href="#a10331f5f11a0820e143f264f219abb60">WebAssemblyOperand</a>, <a href="#a15b5347772744464650c8298ff218a05">WebAssemblyOperand</a> and <a href="#a22ef9eb97030d89c30ef0e119b77493b">WebAssemblyOperand</a>.</p>

</div>
</div>

### Flt {#a3fbdb6bcba5026cca0cae320cb9b4088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct FltOp anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::Flt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a897c9e930c31d4b65408c09c73d6a417">addFPImmf32Operands</a>, <a href="#a3bcb95d1f0d9f65bf8d7fb3e60601c57">addFPImmf64Operands</a>, <a href="#a82d7f1477e16e4c0bbc4950af5e7a958">print</a> and <a href="#a79bb0087b45e534fd21f2737b7630cc5">WebAssemblyOperand</a>.</p>

</div>
</div>

### Int {#a194e5ceda0deed4b388b81a233463b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct IntOp anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::Int</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a1843f39a0d50d963f92c5f1fe30b633e">addImmOperands</a>, <a href="#a82d7f1477e16e4c0bbc4950af5e7a958">print</a> and <a href="#a10331f5f11a0820e143f264f219abb60">WebAssemblyOperand</a>.</p>

</div>
</div>

### Kind {#a224a0ccf7728c66d3a484cd996aa591b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::KindTy anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a897c9e930c31d4b65408c09c73d6a417">addFPImmf32Operands</a>, <a href="#a3bcb95d1f0d9f65bf8d7fb3e60601c57">addFPImmf64Operands</a>, <a href="#a1843f39a0d50d963f92c5f1fe30b633e">addImmOperands</a>, <a href="#a2ea73ed70bdc7865b84380fbcdc7f69b">isBrList</a>, <a href="#a70102ed41316ae23e907410a5305a6a4">isCatchList</a>, <a href="#a69da41a89dd5c734e825b03fb66f6483">isFPImm</a>, <a href="#a6ca517b72e2452f383b379119de73449">isImm</a>, <a href="#a57d8d92b5c02423eeb1be46843dbea7a">isToken</a>, <a href="#a82d7f1477e16e4c0bbc4950af5e7a958">print</a>, <a href="#a84ff2abedbc46a52544d7536dc6c4200">WebAssemblyOperand</a>, <a href="#ae2bd353a0b1fc4914971dd2b835dbb0c">WebAssemblyOperand</a>, <a href="#a79bb0087b45e534fd21f2737b7630cc5">WebAssemblyOperand</a>, <a href="#a10331f5f11a0820e143f264f219abb60">WebAssemblyOperand</a>, <a href="#a15b5347772744464650c8298ff218a05">WebAssemblyOperand</a> and <a href="#a22ef9eb97030d89c30ef0e119b77493b">WebAssemblyOperand</a>.</p>

</div>
</div>

### StartLoc {#a530617d1eb02beea0911de865ac257a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#afdaa341b7a8359420c16ea5e712bd06f">getStartLoc</a>, <a href="#a84ff2abedbc46a52544d7536dc6c4200">WebAssemblyOperand</a>, <a href="#ae2bd353a0b1fc4914971dd2b835dbb0c">WebAssemblyOperand</a>, <a href="#a79bb0087b45e534fd21f2737b7630cc5">WebAssemblyOperand</a>, <a href="#a10331f5f11a0820e143f264f219abb60">WebAssemblyOperand</a>, <a href="#a15b5347772744464650c8298ff218a05">WebAssemblyOperand</a> and <a href="#a22ef9eb97030d89c30ef0e119b77493b">WebAssemblyOperand</a>.</p>

</div>
</div>

### Sym {#a975c5ba34b2dbeaf5dfeac01e7524f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct SymOp anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::Sym</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a1843f39a0d50d963f92c5f1fe30b633e">addImmOperands</a>, <a href="#a82d7f1477e16e4c0bbc4950af5e7a958">print</a> and <a href="#a15b5347772744464650c8298ff218a05">WebAssemblyOperand</a>.</p>

</div>
</div>

### Tok {#a443a426ff5152d394556181d8c89dd03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct TokOp anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a7090305f9998619ef1341e0610c0ad43">getToken</a>, <a href="#a82d7f1477e16e4c0bbc4950af5e7a958">print</a> and <a href="#a22ef9eb97030d89c30ef0e119b77493b">WebAssemblyOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp">WebAssemblyAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
