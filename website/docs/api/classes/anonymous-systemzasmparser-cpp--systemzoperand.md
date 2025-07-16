---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-systemzasmparser-cpp-/systemzoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SystemZOperand` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SystemZAsmParser.cpp}::SystemZOperand { ... }
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandKind { <a href="#aca0d2bb5fbabe1e27cbc7b6a511e7a8a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eff68bd981e6b74408ec95e09ecbd21">SystemZOperand</a> (OperandKind Kind, SMLoc StartLoc, SMLoc EndLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad619790865459ede153ed9b7341dab3b">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#ad619790865459ede153ed9b7341dab3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b0a545f1c0558209646663c9f7f4b23">getToken</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac929ff26209cdfe20d5d75d88622a2a6">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#ac929ff26209cdfe20d5d75d88622a2a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b442bca1ebfe1c728e90ef3a64cf5dd">isReg</a> (RegisterKind RegKind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f7cad4b1df6ce3b538bae4d9d22626">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f7cb9fd304ca662234161f95976aeb">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#aa0f7cb9fd304ca662234161f95976aeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95da200525ff35bb62a3770a1e9b7916">isImm</a> (int64_t MinValue, int64_t MaxValue) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc34143d09dd0971c2e635a8e5d05062">getImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90f8707f3ab8975b86e07e33268c37e0">isImmTLS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ImmTLSOp</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf401d05934124362984d723bfcf2b6">getImmTLS</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52e6a76d995e9aaa52f6dcfcd068d83c">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#a52e6a76d995e9aaa52f6dcfcd068d83c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597a56aabd8bda5735088779308cc79e">isMem</a> (MemoryKind MemKind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20569bb40fcb991f4a30df3fcd81938">isMem</a> (MemoryKind MemKind, RegisterKind RegKind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1c52add2a9bc91d8a84d64c67f5df8">isMemDisp12</a> (MemoryKind MemKind, RegisterKind RegKind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ed4fa8ef298479d8627315c701a1a0a">isMemDisp20</a> (MemoryKind MemKind, RegisterKind RegKind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d45b266a620c0a7de7829e35f4e4548">isMemDisp12Len4</a> (RegisterKind RegKind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe72daae8d87d18f0b2dbcbdf06227d">isMemDisp12Len8</a> (RegisterKind RegKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MemOp &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6723611a80a78a70eeeb7fa781e7f797">getMem</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269ecf7239298db8293b556a989cc204">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Get the location of the first token of this operand. <a href="#a269ecf7239298db8293b556a989cc204">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9cab4ecf34839a10ba40ed16b59769d">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Get the location of the last token of this operand. <a href="#ac9cab4ecf34839a10ba40ed16b59769d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c3ca8914109586f1de6da390582f232">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#a9c3ca8914109586f1de6da390582f232">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab64f8a3497de0ff3c86ccedc5301db1b">getLocRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLocRange - Get the range between the first and last token of this operand. <a href="#ab64f8a3497de0ff3c86ccedc5301db1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5e94fab8baba89e96b19929550f2a21">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4b72b68c6fc2ddcfa070f61861e620d">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b9382a69efae30312157561c9935e47">addBDAddrOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf2793ad54a2663ea0dedbaaa2b29cd8">addBDXAddrOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c2fe3c329a0af3333996cd5f459941">addBDLAddrOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94365cb7b08e65f8c3939b8c6403137c">addBDRAddrOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af776389f8f4e4c37da30a66ff260f9f6">addBDVAddrOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5adb948f0e1acffb765fb3d36b58635f">addLXAAddrOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c05e49d03c9042135ec827804a0a9e4">addImmTLSOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b878cd98af868fcdadc94c9aa220d61">isGR32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370502caa01b985a9bb645268b2ba9a5">isGRH32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6aaa1d948c6089eb2cf809a497d53a">isGRX32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98681787bb59be7a983b65ae6c44fb38">isGR64</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a031110e5d94f00fa5d6239e8f6fb8dae">isGR128</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b8159ab6d09402d643d63f9927c5e8">isADDR32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf7edb8a5901ab5ffa0cb5b6622785b">isADDR64</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1e592436131b00bb180acf5183c2378">isADDR128</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8dff833867e3509565dcc7d6b4cb3b">isFP32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34e94d15fd6f7842290b2a7a16b0fb18">isFP64</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d17f013f564103ab8efe285dd61dfb2">isFP128</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7f7eab11791fc5b122ea2526b2f4e2e">isVR32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d3eb61d9ad447ddbde6297b2f4b789">isVR64</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26eacb1aa0fafa30abd3a5bacf517f3a">isVF128</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8512e3642408d1cde75268a05ffa1f">isVR128</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f47a9c9abe9710c69244ce3c2db9970">isAR32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8c51e33dab5decdddbb04b370e741ad">isCR64</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ea1066c3f3f6b30e2ab53b39054ec3">isAnyReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69bbae9a6665c012fe7b60d9e4502a0">isBDAddr32Disp12</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0383e44be5cfd2bac03b9a1824ddbb80">isBDAddr32Disp20</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53545db6405c50c1014689c425eb5621">isBDAddr64Disp12</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07ceb2828bb8998e66885745d3296eea">isBDAddr64Disp20</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac75e52d7796e50d93186e2b87a09e9">isBDXAddr64Disp12</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dacbda60bf27b49ed7c015bf8509b40">isBDXAddr64Disp20</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab94d54c211c5a276930215a470b4edd">isBDLAddr64Disp12Len4</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0761f9b4ffe799f9eabe32250a205db8">isBDLAddr64Disp12Len8</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab75f2fefede3f401fa42473d900e0ff0">isBDRAddr64Disp12</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75a0ea9a47735071d58d32dbc27cc83">isBDVAddr64Disp12</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd822adf3f7e0927fc0a81f9e4818b6">isLXAAddr64Disp20</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad12fccbe8d5ede1598deb9ded83cce70">isU1Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a9f26d0a1bccde30486a3924d3b671e">isU2Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475cc20a06283d7ee2ce7f21ac8a21a5">isU3Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412c5fddd850e5f1ecdbf5264f007415">isU4Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ae0d524a296f5a3901f762a8419332">isU8Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423f8aa0726e8d472ed64b404b623561">isS8Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf89a656cafe3f758650095b6a5a1aeb">isU12Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad799cf8502d62f862c5e6ec7747e07c4">isU16Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2c248605ba77f19a9a643f33dea04a">isS16Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c634554a01c0722a4af89e637f688b">isU32Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac213ff697b1131d6d24cfcc7573330b3">isS32Imm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb2b12317fcbcbd4e1202887ad0852d">isU48Imm</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf7998f77dc94d50c5710c9f635b5a0">addExpr</a> (MCInst &amp;Inst, const MCExpr *Expr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">TokenOp</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f944da1625e6bf6b0f5940ba5d2a4a2">Token</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">RegOp</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a356e18f07e6aca6280d7945772fea11f">Reg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d61f2cee2d1807e35166f00efebc9e">Imm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ImmTLSOp</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9865b1dcc1e2c855fbfced54fd4522">ImmTLS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">MemOp</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">OperandKind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a578d1d05d0b9c86a3be10d7f468dc1">Kind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8756e53694fa6c836d35e8de86d555b7">StartLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4850d0a3ac6ca349facc4a143ea4e287">EndLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{SystemZAsmParser.cpp}<a href="#a6eff68bd981e6b74408ec95e09ecbd21">::SystemZOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98e8d8598ec5057808ca2287d102305"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand">SystemZOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e30ea5b42e8b5e143944612afbcb83e">createInvalid</a> (SMLoc StartLoc, SMLoc EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand">SystemZOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a42fd3c53367b38232356ef0a504dd4">createToken</a> (StringRef Str, SMLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand">SystemZOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d2e13cf9dcf7cebd5fa2fa40666943e">createReg</a> (RegisterKind Kind, unsigned Num, SMLoc StartLoc, SMLoc EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand">SystemZOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa414830b56fea225ca06502b12d50ba">createImm</a> (const MCExpr *Expr, SMLoc StartLoc, SMLoc EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand">SystemZOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaf2a54c5e09bd42f5487467bf720183">createMem</a> (MemoryKind MemKind, RegisterKind RegKind, unsigned Base, const MCExpr *Disp, unsigned Index, const MCExpr *LengthImm, unsigned LengthReg, SMLoc StartLoc, SMLoc EndLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand">SystemZOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a163fe09e841314e24f5005eb27b677be">createImmTLS</a> (const MCExpr *Imm, const MCExpr *Sym, SMLoc StartLoc, SMLoc EndLoc)</td>
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


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### OperandKind {#aca0d2bb5fbabe1e27cbc7b6a511e7a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{SystemZAsmParser.cpp}::SystemZOperand::OperandKind </td>
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
<td class="doxyEnumItemName">KindInvalid<a id="aca0d2bb5fbabe1e27cbc7b6a511e7a8aa08ebb5eb02cf3f8dfd07830f0f459acd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KindToken<a id="aca0d2bb5fbabe1e27cbc7b6a511e7a8aaae8f6ac1c202d08de9d8615a8e43017e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KindReg<a id="aca0d2bb5fbabe1e27cbc7b6a511e7a8aa3b09975e3a46992785094bdaf766cf25"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KindImm<a id="aca0d2bb5fbabe1e27cbc7b6a511e7a8aaabb4034e21c3334f31509c82a0341240"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KindImmTLS<a id="aca0d2bb5fbabe1e27cbc7b6a511e7a8aab05ff6f050e48de758c878cb0368ffce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KindMem<a id="aca0d2bb5fbabe1e27cbc7b6a511e7a8aa1a160c6fc4bcdfa643e67e6bc1caeb27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SystemZOperand() {#a6eff68bd981e6b74408ec95e09ecbd21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SystemZAsmParser.cpp}::SystemZOperand::SystemZOperand (OperandKind Kind, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBDAddrOperands() {#a9b9382a69efae30312157561c9935e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDAddrOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad08dbd42896a9d8a5e639b82463ca282">anonymous{SystemZAsmParser.cpp}::BDMem</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a>, <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addBDLAddrOperands() {#ac0c2fe3c329a0af3333996cd5f459941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDLAddrOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a7aece02c19a6695e171c271c8498d47d">anonymous{SystemZAsmParser.cpp}::BDLMem</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a>, <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addBDRAddrOperands() {#a94365cb7b08e65f8c3939b8c6403137c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDRAddrOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad8fecadb6cd4db1b3e5d879b179edc4a">anonymous{SystemZAsmParser.cpp}::BDRMem</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a>, <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addBDVAddrOperands() {#af776389f8f4e4c37da30a66ff260f9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDVAddrOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9aff880170e6e607744224e05bc1201fd2">anonymous{SystemZAsmParser.cpp}::BDVMem</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a>, <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addBDXAddrOperands() {#abf2793ad54a2663ea0dedbaaa2b29cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDXAddrOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a3b4bf8b62c9fa7d0fb50f231f0e0c992">anonymous{SystemZAsmParser.cpp}::BDXMem</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a>, <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmOperands() {#ad4b72b68c6fc2ddcfa070f61861e620d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afc34143d09dd0971c2e635a8e5d05062">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmTLSOperands() {#a3c05e49d03c9042135ec827804a0a9e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addImmTLSOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afd9865b1dcc1e2c855fbfced54fd4522">ImmTLS</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addLXAAddrOperands() {#a5adb948f0e1acffb765fb3d36b58635f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addLXAAddrOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a9ee56e068f483e37ef3fc3fdbefb19db">anonymous{SystemZAsmParser.cpp}::LXAMem</a>, <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#ac5e94fab8baba89e96b19929550f2a21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getEndLoc() {#ac9cab4ecf34839a10ba40ed16b59769d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{SystemZAsmParser.cpp}::SystemZOperand::getEndLoc ()</td>
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

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### getImm() {#afc34143d09dd0971c2e635a8e5d05062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{SystemZAsmParser.cpp}::SystemZOperand::getImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1d61f2cee2d1807e35166f00efebc9e">Imm</a>.</p>


<p>Referenced by <a href="#ad4b72b68c6fc2ddcfa070f61861e620d">addImmOperands</a> and <a href="#a9c3ca8914109586f1de6da390582f232">print</a>.</p>

</div>
</div>

### getImmTLS() {#afcf401d05934124362984d723bfcf2b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ImmTLSOp anonymous{SystemZAsmParser.cpp}::SystemZOperand::getImmTLS ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#afd9865b1dcc1e2c855fbfced54fd4522">ImmTLS</a>.</p>


<p>Referenced by <a href="#a9c3ca8914109586f1de6da390582f232">print</a>.</p>

</div>
</div>

### getLocRange() {#ab64f8a3497de0ff3c86ccedc5301db1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange anonymous{SystemZAsmParser.cpp}::SystemZOperand::getLocRange ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLocRange - Get the range between the first and last token of this operand.</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a0b228c0975660d76b206b2f9220b3cc3">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::matchAndEmitInstruction</a>.</p>

</div>
</div>

### getMem() {#a6723611a80a78a70eeeb7fa781e7f797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemOp &amp; anonymous{SystemZAsmParser.cpp}::SystemZOperand::getMem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a>.</p>


<p>Referenced by <a href="#a9c3ca8914109586f1de6da390582f232">print</a>.</p>

</div>
</div>

### getReg() {#aa5f7cad4b1df6ce3b538bae4d9d22626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{SystemZAsmParser.cpp}::SystemZOperand::getReg ()</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a356e18f07e6aca6280d7945772fea11f">Reg</a>.</p>


<p>Referenced by <a href="#a9c3ca8914109586f1de6da390582f232">print</a>.</p>

</div>
</div>

### getStartLoc() {#a269ecf7239298db8293b556a989cc204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{SystemZAsmParser.cpp}::SystemZOperand::getStartLoc ()</td>
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

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a0b228c0975660d76b206b2f9220b3cc3">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::matchAndEmitInstruction</a>.</p>

</div>
</div>

### getToken() {#a4b0a545f1c0558209646663c9f7f4b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{SystemZAsmParser.cpp}::SystemZOperand::getToken ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a8f944da1625e6bf6b0f5940ba5d2a4a2">Token</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a0b228c0975660d76b206b2f9220b3cc3">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::matchAndEmitInstruction</a> and <a href="#a9c3ca8914109586f1de6da390582f232">print</a>.</p>

</div>
</div>

### isADDR128() {#ae1e592436131b00bb180acf5183c2378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isADDR128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### isADDR32() {#a53b8159ab6d09402d643d63f9927c5e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isADDR32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87a2625030067ecd3b50022f92e08b446e2">anonymous{SystemZAsmParser.cpp}::GR32Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isADDR64() {#a5bf7edb8a5901ab5ffa0cb5b6622785b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isADDR64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isAnyReg() {#a08ea1066c3f3f6b30e2ab53b39054ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isAnyReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isAR32() {#a1f47a9c9abe9710c69244ce3c2db9970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isAR32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abaa29668e19bea393f3577552035b0ab">anonymous{SystemZAsmParser.cpp}::AR32Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isBDAddr32Disp12() {#aa69bbae9a6665c012fe7b60d9e4502a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDAddr32Disp12 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad08dbd42896a9d8a5e639b82463ca282">anonymous{SystemZAsmParser.cpp}::BDMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87a2625030067ecd3b50022f92e08b446e2">anonymous{SystemZAsmParser.cpp}::GR32Reg</a> and <a href="#a2e1c52add2a9bc91d8a84d64c67f5df8">isMemDisp12</a>.</p>

</div>
</div>

### isBDAddr32Disp20() {#a0383e44be5cfd2bac03b9a1824ddbb80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDAddr32Disp20 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad08dbd42896a9d8a5e639b82463ca282">anonymous{SystemZAsmParser.cpp}::BDMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87a2625030067ecd3b50022f92e08b446e2">anonymous{SystemZAsmParser.cpp}::GR32Reg</a> and <a href="#a4ed4fa8ef298479d8627315c701a1a0a">isMemDisp20</a>.</p>

</div>
</div>

### isBDAddr64Disp12() {#a53545db6405c50c1014689c425eb5621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDAddr64Disp12 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad08dbd42896a9d8a5e639b82463ca282">anonymous{SystemZAsmParser.cpp}::BDMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="#a2e1c52add2a9bc91d8a84d64c67f5df8">isMemDisp12</a>.</p>

</div>
</div>

### isBDAddr64Disp20() {#a07ceb2828bb8998e66885745d3296eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDAddr64Disp20 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad08dbd42896a9d8a5e639b82463ca282">anonymous{SystemZAsmParser.cpp}::BDMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="#a4ed4fa8ef298479d8627315c701a1a0a">isMemDisp20</a>.</p>

</div>
</div>

### isBDLAddr64Disp12Len4() {#aab94d54c211c5a276930215a470b4edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDLAddr64Disp12Len4 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="#a8d45b266a620c0a7de7829e35f4e4548">isMemDisp12Len4</a>.</p>

</div>
</div>

### isBDLAddr64Disp12Len8() {#a0761f9b4ffe799f9eabe32250a205db8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDLAddr64Disp12Len8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="#a6fe72daae8d87d18f0b2dbcbdf06227d">isMemDisp12Len8</a>.</p>

</div>
</div>

### isBDRAddr64Disp12() {#ab75f2fefede3f401fa42473d900e0ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDRAddr64Disp12 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad8fecadb6cd4db1b3e5d879b179edc4a">anonymous{SystemZAsmParser.cpp}::BDRMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="#a2e1c52add2a9bc91d8a84d64c67f5df8">isMemDisp12</a>.</p>

</div>
</div>

### isBDVAddr64Disp12() {#ac75a0ea9a47735071d58d32dbc27cc83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDVAddr64Disp12 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9aff880170e6e607744224e05bc1201fd2">anonymous{SystemZAsmParser.cpp}::BDVMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="#a2e1c52add2a9bc91d8a84d64c67f5df8">isMemDisp12</a>.</p>

</div>
</div>

### isBDXAddr64Disp12() {#a5ac75e52d7796e50d93186e2b87a09e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDXAddr64Disp12 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a3b4bf8b62c9fa7d0fb50f231f0e0c992">anonymous{SystemZAsmParser.cpp}::BDXMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="#a2e1c52add2a9bc91d8a84d64c67f5df8">isMemDisp12</a>.</p>

</div>
</div>

### isBDXAddr64Disp20() {#a1dacbda60bf27b49ed7c015bf8509b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isBDXAddr64Disp20 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a3b4bf8b62c9fa7d0fb50f231f0e0c992">anonymous{SystemZAsmParser.cpp}::BDXMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="#a4ed4fa8ef298479d8627315c701a1a0a">isMemDisp20</a>.</p>

</div>
</div>

### isCR64() {#aa8c51e33dab5decdddbb04b370e741ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isCR64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87ac663155d4f902d877cb26c9d28687060">anonymous{SystemZAsmParser.cpp}::CR64Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isFP128() {#a8d17f013f564103ab8efe285dd61dfb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isFP128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87ad454000be78d8700119c060327219483">anonymous{SystemZAsmParser.cpp}::FP128Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isFP32() {#acd8dff833867e3509565dcc7d6b4cb3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isFP32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87a42c41f183eb08e1c80b0835e28c775b7">anonymous{SystemZAsmParser.cpp}::FP32Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isFP64() {#a34e94d15fd6f7842290b2a7a16b0fb18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isFP64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87a55926458c31866d584b8bbc56a198c61">anonymous{SystemZAsmParser.cpp}::FP64Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isGR128() {#a031110e5d94f00fa5d6239e8f6fb8dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isGR128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87a0df628529dc62b33b763c64aa2bb16f1">anonymous{SystemZAsmParser.cpp}::GR128Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isGR32() {#a2b878cd98af868fcdadc94c9aa220d61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isGR32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87a2625030067ecd3b50022f92e08b446e2">anonymous{SystemZAsmParser.cpp}::GR32Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isGR64() {#a98681787bb59be7a983b65ae6c44fb38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isGR64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isGRH32() {#a370502caa01b985a9bb645268b2ba9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isGRH32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87a68d79b81526978dbe0712315893f5bfd">anonymous{SystemZAsmParser.cpp}::GRH32Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isGRX32() {#acf6aaa1d948c6089eb2cf809a497d53a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isGRX32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### isImm() {#aa0f7cb9fd304ca662234161f95976aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isImm ()</td>
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

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### isImm() {#a95da200525ff35bb62a3770a1e9b7916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isImm (int64_t MinValue, int64_t MaxValue)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="#ad1d61f2cee2d1807e35166f00efebc9e">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp/#a1dec4aea5f6ca0f9360bdf9cdbd839f1">inRange</a>.</p>

</div>
</div>

### isImmTLS() {#a90f8707f3ab8975b86e07e33268c37e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isImmTLS ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### isLXAAddr64Disp20() {#a9cd822adf3f7e0927fc0a81f9e4818b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isLXAAddr64Disp20 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87abf02d733ad4a0c94bfd5989725abe1b2">anonymous{SystemZAsmParser.cpp}::GR64Reg</a>, <a href="#a4ed4fa8ef298479d8627315c701a1a0a">isMemDisp20</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a9ee56e068f483e37ef3fc3fdbefb19db">anonymous{SystemZAsmParser.cpp}::LXAMem</a>.</p>

</div>
</div>

### isMem() {#a52e6a76d995e9aaa52f6dcfcd068d83c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isMem ()</td>
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

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### isMem() {#a597a56aabd8bda5735088779308cc79e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isMem (<a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9">MemoryKind</a> MemKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad08dbd42896a9d8a5e639b82463ca282">anonymous{SystemZAsmParser.cpp}::BDMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a3b4bf8b62c9fa7d0fb50f231f0e0c992">anonymous{SystemZAsmParser.cpp}::BDXMem</a> and <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a>.</p>

</div>
</div>

### isMem() {#af20569bb40fcb991f4a30df3fcd81938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isMem (<a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9">MemoryKind</a> MemKind, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87">RegisterKind</a> RegKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a> and <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a>.</p>

</div>
</div>

### isMemDisp12() {#a2e1c52add2a9bc91d8a84d64c67f5df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isMemDisp12 (<a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9">MemoryKind</a> MemKind, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87">RegisterKind</a> RegKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp/#a1dec4aea5f6ca0f9360bdf9cdbd839f1">inRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a> and <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a>.</p>


<p>Referenced by <a href="#aa69bbae9a6665c012fe7b60d9e4502a0">isBDAddr32Disp12</a>, <a href="#a53545db6405c50c1014689c425eb5621">isBDAddr64Disp12</a>, <a href="#ab75f2fefede3f401fa42473d900e0ff0">isBDRAddr64Disp12</a>, <a href="#ac75a0ea9a47735071d58d32dbc27cc83">isBDVAddr64Disp12</a>, <a href="#a5ac75e52d7796e50d93186e2b87a09e9">isBDXAddr64Disp12</a>, <a href="#a8d45b266a620c0a7de7829e35f4e4548">isMemDisp12Len4</a> and <a href="#a6fe72daae8d87d18f0b2dbcbdf06227d">isMemDisp12Len8</a>.</p>

</div>
</div>

### isMemDisp12Len4() {#a8d45b266a620c0a7de7829e35f4e4548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isMemDisp12Len4 (<a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87">RegisterKind</a> RegKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a7aece02c19a6695e171c271c8498d47d">anonymous{SystemZAsmParser.cpp}::BDLMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp/#a1dec4aea5f6ca0f9360bdf9cdbd839f1">inRange</a>, <a href="#a2e1c52add2a9bc91d8a84d64c67f5df8">isMemDisp12</a> and <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a>.</p>


<p>Referenced by <a href="#aab94d54c211c5a276930215a470b4edd">isBDLAddr64Disp12Len4</a>.</p>

</div>
</div>

### isMemDisp12Len8() {#a6fe72daae8d87d18f0b2dbcbdf06227d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isMemDisp12Len8 (<a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87">RegisterKind</a> RegKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a7aece02c19a6695e171c271c8498d47d">anonymous{SystemZAsmParser.cpp}::BDLMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp/#a1dec4aea5f6ca0f9360bdf9cdbd839f1">inRange</a>, <a href="#a2e1c52add2a9bc91d8a84d64c67f5df8">isMemDisp12</a> and <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a>.</p>


<p>Referenced by <a href="#a0761f9b4ffe799f9eabe32250a205db8">isBDLAddr64Disp12Len8</a>.</p>

</div>
</div>

### isMemDisp20() {#a4ed4fa8ef298479d8627315c701a1a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isMemDisp20 (<a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9">MemoryKind</a> MemKind, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87">RegisterKind</a> RegKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp/#a1dec4aea5f6ca0f9360bdf9cdbd839f1">inRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb2e33eb1a7368945a838c85438b040">llvm::isMem</a> and <a href="#aa55d5658b55564d56df2d27862bbf78a">Mem</a>.</p>


<p>Referenced by <a href="#a0383e44be5cfd2bac03b9a1824ddbb80">isBDAddr32Disp20</a>, <a href="#a07ceb2828bb8998e66885745d3296eea">isBDAddr64Disp20</a>, <a href="#a1dacbda60bf27b49ed7c015bf8509b40">isBDXAddr64Disp20</a> and <a href="#a9cd822adf3f7e0927fc0a81f9e4818b6">isLXAAddr64Disp20</a>.</p>

</div>
</div>

### isReg() {#ac929ff26209cdfe20d5d75d88622a2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isReg ()</td>
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

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### isReg() {#a2b442bca1ebfe1c728e90ef3a64cf5dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isReg (<a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87">RegisterKind</a> RegKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="#a356e18f07e6aca6280d7945772fea11f">Reg</a>.</p>

</div>
</div>

### isS16Imm() {#abb2c248605ba77f19a9a643f33dea04a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isS16Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isS32Imm() {#ac213ff697b1131d6d24cfcc7573330b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isS32Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isS8Imm() {#a423f8aa0726e8d472ed64b404b623561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isS8Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isToken() {#ad619790865459ede153ed9b7341dab3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isToken ()</td>
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

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### isU12Imm() {#adf89a656cafe3f758650095b6a5a1aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU12Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isU16Imm() {#ad799cf8502d62f862c5e6ec7747e07c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU16Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isU1Imm() {#ad12fccbe8d5ede1598deb9ded83cce70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU1Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isU2Imm() {#a6a9f26d0a1bccde30486a3924d3b671e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU2Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isU32Imm() {#a17c634554a01c0722a4af89e637f688b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU32Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isU3Imm() {#a475cc20a06283d7ee2ce7f21ac8a21a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU3Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isU48Imm() {#acfb2b12317fcbcbd4e1202887ad0852d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU48Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isU4Imm() {#a412c5fddd850e5f1ecdbf5264f007415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU4Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isU8Imm() {#af7ae0d524a296f5a3901f762a8419332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isU8Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isVF128() {#a26eacb1aa0fafa30abd3a5bacf517f3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isVF128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### isVR128() {#a4a8512e3642408d1cde75268a05ffa1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isVR128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87a52a1e6e3eef7bb0bfc8e9ede59dc1b8c">anonymous{SystemZAsmParser.cpp}::VR128Reg</a>.</p>

</div>
</div>

### isVR32() {#ab7f7eab11791fc5b122ea2526b2f4e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isVR32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87af1474e020d6244f493ff4662c6609abb">anonymous{SystemZAsmParser.cpp}::VR32Reg</a>.</p>

</div>
</div>

### isVR64() {#af4d3eb61d9ad447ddbde6297b2f4b789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SystemZAsmParser.cpp}::SystemZOperand::isVR64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87aa93dd08bdc52499b9788d2984833f971">anonymous{SystemZAsmParser.cpp}::VR64Reg</a>.</p>

</div>
</div>

### print() {#a9c3ca8914109586f1de6da390582f232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>print - Print a debug representation of the operand to the given stream.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a7aece02c19a6695e171c271c8498d47d">anonymous{SystemZAsmParser.cpp}::BDLMem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad8fecadb6cd4db1b3e5d879b179edc4a">anonymous{SystemZAsmParser.cpp}::BDRMem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#afc34143d09dd0971c2e635a8e5d05062">getImm</a>, <a href="#afcf401d05934124362984d723bfcf2b6">getImmTLS</a>, <a href="#a6723611a80a78a70eeeb7fa781e7f797">getMem</a>, <a href="#aa5f7cad4b1df6ce3b538bae4d9d22626">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzgnuinstprinter/#af4ada4aaf8d8e055ea1487353f62f49f">llvm::SystemZGNUInstPrinter::getRegisterName</a>, <a href="#a4b0a545f1c0558209646663c9f7f4b23">getToken</a>, <a href="#ad1d61f2cee2d1807e35166f00efebc9e">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp/#af327403a272fee7aacf8d6cd5f01f331">printMCExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addExpr() {#a8cf7998f77dc94d50c5710c9f635b5a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SystemZAsmParser.cpp}::SystemZOperand::addExpr (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Imm {#ad1d61f2cee2d1807e35166f00efebc9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* anonymous{SystemZAsmParser.cpp}::SystemZOperand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a163fe09e841314e24f5005eb27b677be">createImmTLS</a>, <a href="#afc34143d09dd0971c2e635a8e5d05062">getImm</a>, <a href="#a95da200525ff35bb62a3770a1e9b7916">isImm</a> and <a href="#a9c3ca8914109586f1de6da390582f232">print</a>.</p>

</div>
</div>

### ImmTLS {#afd9865b1dcc1e2c855fbfced54fd4522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmTLSOp anonymous{SystemZAsmParser.cpp}::SystemZOperand::ImmTLS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a3c05e49d03c9042135ec827804a0a9e4">addImmTLSOperands</a> and <a href="#afcf401d05934124362984d723bfcf2b6">getImmTLS</a>.</p>

</div>
</div>

### Mem {#aa55d5658b55564d56df2d27862bbf78a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemOp anonymous{SystemZAsmParser.cpp}::SystemZOperand::Mem</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a9b9382a69efae30312157561c9935e47">addBDAddrOperands</a>, <a href="#ac0c2fe3c329a0af3333996cd5f459941">addBDLAddrOperands</a>, <a href="#a94365cb7b08e65f8c3939b8c6403137c">addBDRAddrOperands</a>, <a href="#af776389f8f4e4c37da30a66ff260f9f6">addBDVAddrOperands</a>, <a href="#abf2793ad54a2663ea0dedbaaa2b29cd8">addBDXAddrOperands</a>, <a href="#a5adb948f0e1acffb765fb3d36b58635f">addLXAAddrOperands</a>, <a href="#a6723611a80a78a70eeeb7fa781e7f797">getMem</a>, <a href="#a597a56aabd8bda5735088779308cc79e">isMem</a>, <a href="#af20569bb40fcb991f4a30df3fcd81938">isMem</a>, <a href="#a2e1c52add2a9bc91d8a84d64c67f5df8">isMemDisp12</a>, <a href="#a8d45b266a620c0a7de7829e35f4e4548">isMemDisp12Len4</a>, <a href="#a6fe72daae8d87d18f0b2dbcbdf06227d">isMemDisp12Len8</a> and <a href="#a4ed4fa8ef298479d8627315c701a1a0a">isMemDisp20</a>.</p>

</div>
</div>

### Reg {#a356e18f07e6aca6280d7945772fea11f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegOp anonymous{SystemZAsmParser.cpp}::SystemZOperand::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#aa5f7cad4b1df6ce3b538bae4d9d22626">getReg</a> and <a href="#a2b442bca1ebfe1c728e90ef3a64cf5dd">isReg</a>.</p>

</div>
</div>

### Token {#a8f944da1625e6bf6b0f5940ba5d2a4a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenOp anonymous{SystemZAsmParser.cpp}::SystemZOperand::Token</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4b0a545f1c0558209646663c9f7f4b23">getToken</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#ab98e8d8598ec5057808ca2287d102305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{SystemZAsmParser.cpp}::SystemZOperand anonymous{SystemZAsmParser.cpp}::SystemZOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### EndLoc {#a4850d0a3ac6ca349facc4a143ea4e287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{SystemZAsmParser.cpp}::SystemZOperand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### Kind {#a3a578d1d05d0b9c86a3be10d7f468dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OperandKind anonymous{SystemZAsmParser.cpp}::SystemZOperand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### StartLoc {#a8756e53694fa6c836d35e8de86d555b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{SystemZAsmParser.cpp}::SystemZOperand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createImm() {#afa414830b56fea225ca06502b12d50ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SystemZOperand &gt; anonymous{SystemZAsmParser.cpp}::SystemZOperand::createImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### createImmTLS() {#a163fe09e841314e24f5005eb27b677be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SystemZOperand &gt; anonymous{SystemZAsmParser.cpp}::SystemZOperand::createImmTLS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Sym, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad1d61f2cee2d1807e35166f00efebc9e">Imm</a>.</p>

</div>
</div>

### createInvalid() {#a9e30ea5b42e8b5e143944612afbcb83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SystemZOperand &gt; anonymous{SystemZAsmParser.cpp}::SystemZOperand::createInvalid (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### createMem() {#afaf2a54c5e09bd42f5487467bf720183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SystemZOperand &gt; anonymous{SystemZAsmParser.cpp}::SystemZOperand::createMem (<a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9">MemoryKind</a> MemKind, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87">RegisterKind</a> RegKind, unsigned Base, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Disp, unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * LengthImm, unsigned LengthReg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9a7aece02c19a6695e171c271c8498d47d">anonymous{SystemZAsmParser.cpp}::BDLMem</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a967870493eab9a69c2b84f198a7c49e9ad8fecadb6cd4db1b3e5d879b179edc4a">anonymous{SystemZAsmParser.cpp}::BDRMem</a>.</p>

</div>
</div>

### createReg() {#a6d2e13cf9dcf7cebd5fa2fa40666943e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SystemZOperand &gt; anonymous{SystemZAsmParser.cpp}::SystemZOperand::createReg (<a href="/web-llvm/docs/api/namespaces/anonymous-systemzasmparser-cpp-/#a325e04fadeaf2a228ada957f88773d87">RegisterKind</a> Kind, unsigned Num, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>

</div>
</div>

### createToken() {#a6a42fd3c53367b38232356ef0a504dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; SystemZOperand &gt; anonymous{SystemZAsmParser.cpp}::SystemZOperand::createToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#ad79a6d97b50d37cfcc0ba24dfc387b10">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp">SystemZAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
