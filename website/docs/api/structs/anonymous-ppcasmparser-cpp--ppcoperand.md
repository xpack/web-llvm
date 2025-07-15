---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-ppcasmparser-cpp-/ppcoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PPCOperand` Struct Reference

<p><a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> - Instances of this class represent a parsed PowerPC machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{PPCAsmParser.cpp}::PPCOperand { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1be76281c13e0cef6e6a12dcb5a4f20">PPCOperand</a> (KindTy K)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a> (const PPCOperand &amp;o)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d82efaa49cc17052a265dde23146e36">operator delete</a> (void *p)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2212381a63a9401192ca4cd2e0848d57">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Get the location of the first token of this operand. <a href="#a2212381a63a9401192ca4cd2e0848d57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae096c59c5a80ed11a3f32924cee86aa4">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Get the location of the last token of this operand. <a href="#ae096c59c5a80ed11a3f32924cee86aa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8f09afbbbd490d3dea1581bb6822f1a">getLocRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLocRange - Get the range between the first and last token of this operand. <a href="#ae8f09afbbbd490d3dea1581bb6822f1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6480a22ac6ebd233e909aaaaf62b07c7">isPPC64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isPPC64 - True if this operand is for an instruction in 64-bit mode. <a href="#a6480a22ac6ebd233e909aaaaf62b07c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914c12de5acc75d734ef554d1b4ee24a">isMemOpBase</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMemOpBase - True if this operand is the base of a memory operand. <a href="#a914c12de5acc75d734ef554d1b4ee24a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb1034deebd58e871c3492e943d266ae">getImmS16Context</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a771af6229c9ebe45f90a0a4a9fae5ca9">getImmU16Context</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10ee31543b73261c04cda2defa75de5">getExpr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6192ac623dde968e730b9fa3c0bb1cb">getExprCRVal</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaefa9109db2aed80c122b9e1f8d560ea">getTLSReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3493a3463a7b84d4c1ed90351b0255cf">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca22bd498258dd09d43340c64f85425">getRegNum</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a692b3490ec9d6143561aa09bb5171f24">getFpReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc37ea8cfbc538c93441d960be37101">getVSReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd47908f21bc243be854f13fd2696be0">getACCReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c2e82336cade5bd080afad399904b2b">getDMRROWReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8fb4cf52ee38e36ecc1eab57c15cd9">getDMRROWpReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11d782ee7e0deedd06746f2c86e8d34">getDMRReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ef0e8519b1c606d1417b6ec8cdb8699">getDMRpReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96d434c457c8c5fea171cd4efea30c3">getVSRpEvenReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31394c25c9ca05d1190f57f9eb70cd0">getG8pReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a420139fede0b33009661079f322f4cd7">getCCReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd4cd7b3f3f4c18acd2628544ffc4992">getCRBit</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbbf9811e42d91f85362752c7ddd11cb">getCRBitMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a455ced885ddd5aefe302a90a58c68cb2">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#a455ced885ddd5aefe302a90a58c68cb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b696a091eb94c73cf6bdd5a16f93161">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#a8b696a091eb94c73cf6bdd5a16f93161">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f7e780fcd1fca846da3453e80b9956b">isU1Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b3d4e189a0ebf4181ec540574b21f10">isU2Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad9f1ba12f4e58e4bc5bab488d189949">isU3Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2930e8de3d14ec58fedfac120a8e02">isU4Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857b7ac2b20fc1e6bb5d99084f53da21">isU5Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c9bf1a794738d85346b7604c546fa35">isS5Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc7e147bc2b88d8cb5a65c57953444c6">isU6Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f4028a12c599b4c539b8579a62f547">isU6ImmX2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a701430ad4879a7023430e35263b9b3e5">isU7Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a377edbc4aee80a8abe8d2016c3f6b821">isU7ImmX4</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997aee7bc438bbe5faa941e56d91580e">isU8Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add31352045a5b5e0247a9aaa6c490499">isU8ImmX8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d5f836ffdb5137ec44a9bb9531afbae">isU10Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a231f7258845b174145f4d49bbf504e05">isU12Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62aa807f340ba4f274f6b0dfe4e8edaf">isU16Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dfdb5e0fcd33e4038caf0703ad56a81">isS16Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1258a10dba8cca7134d342632f6f395">isS16ImmX4</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04fbcfd67eb7f189c743ead1f088375b">isS16ImmX16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b58203dceb224394d68960ff55d1865">isS17Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdbfe738015fe099912f6d24fb9c733c">isHashImmX8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c7e807b8fc8cb08c52a62a89416609f">isS34ImmX16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb6cb9de0fa635a83d33e1b0af34f75">isS34Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bf08bbc56e651bb431a913bb734e116">isTLSReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4de939ce83874ff932546d8d24d9a39e">isDirectBr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad567b66d66e2323125ca82fa2b0f9108">isCondBr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf6f7c15b9c6422776e19d882ac078d">isImmZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb9f6db146551815f7788069c268a70">isRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22fce5a901cab04aa9681d1684c74d37">isACCRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f84e1223953fa166b5a060e7bdaa00">isDMRROWRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee51047a4aa81dc5a6a34c4d1afc2bf5">isDMRROWpRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac40460073342cc0a79bedd462a290ccd">isDMRRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912c40d665c2b1565fdef84b6dd79446">isDMRpRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48151a184723b552d9412bcb78ee95f0">isVSRpEvenRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5380af69ce06d80a1d4b43a7b2867d2b">isVSRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af742da66f9d94de298a7eb84616cff18">isCCRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e56d29ba6ed0224bea08c9ff5caee25">isCRBitNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad424624defbddac75756d98d6a6b71d4">isEvenRegNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2e2413edff2117a52f84bc36ebf51e3">isCRBitMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e12157eb12d9afce2e53d46fc102e4">isATBitsAsHint</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3808574b283c9d38f502dabf1682d3a5">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#a3808574b283c9d38f502dabf1682d3a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af932177edee5402a8b769fe68a7eae3f">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#af932177edee5402a8b769fe68a7eae3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf3bf9bfc5c81b76395bcce75480146">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d7068f5331beed20c505ac25bf75e6">addRegGPRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fcff4b5ab16b5126b53e6221f72e4fe">addRegGPRCNoR0Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8399dd3de3aaf78884b2133c214ec5d">addRegG8RCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a926e9234ebdc634051a8cc4a884dab">addRegG8RCNoX0Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f7c8642744e66352d3f0484f6b9f291">addRegG8pRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a520869629199796c869900cd4531fb96">addRegGxRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb6dfb246e08cada6c1ee959fa370b5">addRegGxRCNoR0Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae660622f18164d2564fc611c31e5dfe6">addRegF4RCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46e8f65e73a8c1ec486feacbd11b8598">addRegF8RCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfbd9f9bd8886de9cc1ce69aa19cecce">addRegFpRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0746159c32e7ac0c99ed85d5ee328103">addRegVFRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06b4630ea0969c8091479fa22a5a5bc">addRegVRRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae738609c642f9c748c350ac993771f5a">addRegVSRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae671f24372f1086564183e87fa417d64">addRegVSFRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084aa0e18d26956a3e8c10627318e6d6">addRegVSSRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8a5f120ec6a5723f1f2cfea052f096e">addRegSPE4RCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed33a86160f649e381a5e36d2ac0025">addRegSPERCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12210c238d328df79afbb1bf5b8d330f">addRegACCRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b9fc1453025fe740abd2314b1edce41">addRegDMRROWRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ff3b4938bbefa984a374310ba12b8e">addRegDMRROWpRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af033d8ccbf4172c8b4e289ddc6b645f7">addRegDMRRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a179ed03cc48e9a5569d66a7f44576942">addRegDMRpRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1fb4b2250fe4553fafb1966344239be">addRegWACCRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95631286ee78d31fa6a320bdd65adf1a">addRegWACC_HIRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a994642f0fa42d7b1ec9557c989e816e5">addRegVSRpRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a148f711934b9ce4ad92cedcc83542771">addRegVSRpEvenRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f272922c818ce3d068c8da3b088e51">addRegCRBITRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a261bc82cf89578d4cad2017373d2000d">addRegCRRCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5416ccbb01a0d1a87c306aa8f9229cc7">addCRBitMaskOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a713d7daafa349daa3ed89e1cf32844ba">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc4166605fc07257d0de56a87f4b3f0d">addS16ImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f8f8640a87306d856954ff636e3c54">addU16ImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e11d80124a79d601e7d34d463ff119">addBranchTargetOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ff241ea58ce22b2fb48a3fbb7f1085">addTLSRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d3c212ecbec16b2898f24ff0b7d0ca5">getToken</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20157fd0e76f33a15a770adf3790a7ff">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#a20157fd0e76f33a15a770adf3790a7ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26206c8c7721a537c5645f13ee6315f7">isExtImm</a> (bool Signed, unsigned Multiple) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{PPCAsmParser.cpp}<a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8">::PPCOperand::KindTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68b535568a91966aa77b76522e3cc0ce">StartLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac012c990b558984dc92d3b247ffa52b7">EndLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a3018fe530c9dfd18d2dfd18f7b3fb">Tok</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4cc89859c1adb2b4012f3ad7118d52e">Expr</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abddf336f0120b6831b1ba59dcc7cd634">TLSReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{PPCAsmParser.cpp}<a href="#af1be76281c13e0cef6e6a12dcb5a4f20">::PPCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6526407a6b80ee4d2c10714ae08f9e36"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade80d23dae3697bbc7e8c429da708dc3">CreateToken</a> (StringRef Str, SMLoc S, bool IsPPC64)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4116a0530b455559f9a6472ab5ea9ea">CreateTokenWithStringCopy</a> (StringRef Str, SMLoc S, bool IsPPC64)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eeecc72015c256728aafacf157f8af1">CreateImm</a> (int64_t Val, SMLoc S, SMLoc E, bool IsPPC64, bool IsMemOpBase=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af62b42fd31f3597b479e46c299c0b7e4">CreateExpr</a> (const MCExpr *Val, SMLoc S, SMLoc E, bool IsPPC64)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45965995484c74a694ac62c4ace838a5">CreateTLSReg</a> (const MCSymbolRefExpr *Sym, SMLoc S, SMLoc E, bool IsPPC64)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe47a7edc64d1a798629c7610f110a18">CreateContextImm</a> (int64_t Val, SMLoc S, SMLoc E, bool IsPPC64)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21aef0218253cc55d4f082c34327d40">CreateFromMCExpr</a> (const MCExpr *Val, SMLoc S, SMLoc E, bool IsPPC64)</td>
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

<p><a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> - Instances of this class represent a parsed PowerPC machine instruction.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### KindTy {#afaa2f6edfd12b232a9ff1fab1ef0fba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{PPCAsmParser.cpp}::PPCOperand::KindTy </td>
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
<td class="doxyEnumItemName">Token<a id="afaa2f6edfd12b232a9ff1fab1ef0fba8aaf48d38972ba0f8d5b65f8df03110403"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Immediate<a id="afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ContextImmediate<a id="afaa2f6edfd12b232a9ff1fab1ef0fba8aed8df6b976d72b6f68a15d5a93b3d2f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Expression<a id="afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TLSRegister<a id="afaa2f6edfd12b232a9ff1fab1ef0fba8a1c6f17770c851308ee7cb87d34e6ddb7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PPCOperand() {#af1be76281c13e0cef6e6a12dcb5a4f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCAsmParser.cpp}::PPCOperand::PPCOperand (<a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8">KindTy</a> K)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Reference <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#ad4116a0530b455559f9a6472ab5ea9ea">CreateTokenWithStringCopy</a>, <a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a185e7e0c07e5d9a0faa11b0ab5f40b97">validateMemOp</a>.</p>

</div>
</div>

### PPCOperand() {#ac03530ad5518aada38f4fb6fd29e7c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCAsmParser.cpp}::PPCOperand::PPCOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand">PPCOperand</a> &amp; o)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aed8df6b976d72b6f68a15d5a93b3d2f9">ContextImmediate</a>, <a href="#ac012c990b558984dc92d3b247ffa52b7">EndLoc</a>, <a href="#ab4cc89859c1adb2b4012f3ad7118d52e">Expr</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a>, <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a116eebce8e7768c60749aa19af77f817">llvm::MCParsedAsmOperand::MCParsedAsmOperand</a>, <a href="#af1be76281c13e0cef6e6a12dcb5a4f20">PPCOperand</a>, <a href="#a68b535568a91966aa77b76522e3cc0ce">StartLoc</a>, <a href="#abddf336f0120b6831b1ba59dcc7cd634">TLSReg</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a1c6f17770c851308ee7cb87d34e6ddb7">TLSRegister</a>, <a href="#a69a3018fe530c9dfd18d2dfd18f7b3fb">Tok</a> and <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aaf48d38972ba0f8d5b65f8df03110403">Token</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#a3d82efaa49cc17052a265dde23146e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::operator delete (void * p)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBranchTargetOperands() {#ae4e11d80124a79d601e7d34d463ff119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addBranchTargetOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#af10ee31543b73261c04cda2defa75de5">getExpr</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addCRBitMaskOperands() {#a5416ccbb01a0d1a87c306aa8f9229cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addCRBitMaskOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#afbbf9811e42d91f85362752c7ddd11cb">getCRBitMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmOperands() {#a713d7daafa349daa3ed89e1cf32844ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#af10ee31543b73261c04cda2defa75de5">getExpr</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegACCRCOperands() {#a12210c238d328df79afbb1bf5b8d330f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegACCRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#afd47908f21bc243be854f13fd2696be0">getACCReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegCRBITRCOperands() {#ac9f272922c818ce3d068c8da3b088e51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegCRBITRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#abd4cd7b3f3f4c18acd2628544ffc4992">getCRBit</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegCRRCOperands() {#a261bc82cf89578d4cad2017373d2000d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegCRRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a420139fede0b33009661079f322f4cd7">getCCReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegDMRpRCOperands() {#a179ed03cc48e9a5569d66a7f44576942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRpRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a9ef0e8519b1c606d1417b6ec8cdb8699">getDMRpReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegDMRRCOperands() {#af033d8ccbf4172c8b4e289ddc6b645f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#af11d782ee7e0deedd06746f2c86e8d34">getDMRReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegDMRROWpRCOperands() {#ad5ff3b4938bbefa984a374310ba12b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRROWpRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#afb8fb4cf52ee38e36ecc1eab57c15cd9">getDMRROWpReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegDMRROWRCOperands() {#a6b9fc1453025fe740abd2314b1edce41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRROWRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a2c2e82336cade5bd080afad399904b2b">getDMRROWReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegF4RCOperands() {#ae660622f18164d2564fc611c31e5dfe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegF4RCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegF8RCOperands() {#a46e8f65e73a8c1ec486feacbd11b8598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegF8RCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegFpRCOperands() {#adfbd9f9bd8886de9cc1ce69aa19cecce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegFpRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a692b3490ec9d6143561aa09bb5171f24">getFpReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegG8pRCOperands() {#a4f7c8642744e66352d3f0484f6b9f291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegG8pRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#ac31394c25c9ca05d1190f57f9eb70cd0">getG8pReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegG8RCNoX0Operands() {#a6a926e9234ebdc634051a8cc4a884dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegG8RCNoX0Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a2fb6dfb246e08cada6c1ee959fa370b5">addRegGxRCNoR0Operands</a>.</p>

</div>
</div>

### addRegG8RCOperands() {#ad8399dd3de3aaf78884b2133c214ec5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegG8RCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a520869629199796c869900cd4531fb96">addRegGxRCOperands</a>.</p>

</div>
</div>

### addRegGPRCNoR0Operands() {#a9fcff4b5ab16b5126b53e6221f72e4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGPRCNoR0Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a2fb6dfb246e08cada6c1ee959fa370b5">addRegGxRCNoR0Operands</a>.</p>

</div>
</div>

### addRegGPRCOperands() {#ab6d7068f5331beed20c505ac25bf75e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGPRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a520869629199796c869900cd4531fb96">addRegGxRCOperands</a>.</p>

</div>
</div>

### addRegGxRCNoR0Operands() {#a2fb6dfb246e08cada6c1ee959fa370b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGxRCNoR0Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a6a926e9234ebdc634051a8cc4a884dab">addRegG8RCNoX0Operands</a>, <a href="#a9fcff4b5ab16b5126b53e6221f72e4fe">addRegGPRCNoR0Operands</a>, <a href="#a6480a22ac6ebd233e909aaaaf62b07c7">isPPC64</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegGxRCOperands() {#a520869629199796c869900cd4531fb96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGxRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#ad8399dd3de3aaf78884b2133c214ec5d">addRegG8RCOperands</a>, <a href="#ab6d7068f5331beed20c505ac25bf75e6">addRegGPRCOperands</a>, <a href="#a6480a22ac6ebd233e909aaaaf62b07c7">isPPC64</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#a7bf3bf9bfc5c81b76395bcce75480146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegSPE4RCOperands() {#ae8a5f120ec6a5723f1f2cfea052f096e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegSPE4RCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegSPERCOperands() {#a7ed33a86160f649e381a5e36d2ac0025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegSPERCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegVFRCOperands() {#a0746159c32e7ac0c99ed85d5ee328103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVFRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegVRRCOperands() {#ad06b4630ea0969c8091479fa22a5a5bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVRRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a0d533b6fd9e806ef90040a6524d9be1b">getRegNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegVSFRCOperands() {#ae671f24372f1086564183e87fa417d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSFRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a1cc37ea8cfbc538c93441d960be37101">getVSReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegVSRCOperands() {#ae738609c642f9c748c350ac993771f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a1cc37ea8cfbc538c93441d960be37101">getVSReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegVSRpEvenRCOperands() {#a148f711934b9ce4ad92cedcc83542771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSRpEvenRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#ac96d434c457c8c5fea171cd4efea30c3">getVSRpEvenReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegVSRpRCOperands() {#a994642f0fa42d7b1ec9557c989e816e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSRpRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#ac96d434c457c8c5fea171cd4efea30c3">getVSRpEvenReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegVSSRCOperands() {#a084aa0e18d26956a3e8c10627318e6d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSSRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a1cc37ea8cfbc538c93441d960be37101">getVSReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegWACC\_HIRCOperands() {#a95631286ee78d31fa6a320bdd65adf1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegWACC_HIRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#afd47908f21bc243be854f13fd2696be0">getACCReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegWACCRCOperands() {#ad1fb4b2250fe4553fafb1966344239be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addRegWACCRCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#afd47908f21bc243be854f13fd2696be0">getACCReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addS16ImmOperands() {#abc4166605fc07257d0de56a87f4b3f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addS16ImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aed8df6b976d72b6f68a15d5a93b3d2f9">ContextImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#af10ee31543b73261c04cda2defa75de5">getExpr</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#adb1034deebd58e871c3492e943d266ae">getImmS16Context</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addTLSRegOperands() {#ab4ff241ea58ce22b2fb48a3fbb7f1085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addTLSRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="#aaefa9109db2aed80c122b9e1f8d560ea">getTLSReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addU16ImmOperands() {#a25f8f8640a87306d856954ff636e3c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCAsmParser.cpp}::PPCOperand::addU16ImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aed8df6b976d72b6f68a15d5a93b3d2f9">ContextImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#af10ee31543b73261c04cda2defa75de5">getExpr</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#a771af6229c9ebe45f90a0a4a9fae5ca9">getImmU16Context</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getACCReg() {#afd47908f21bc243be854f13fd2696be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getACCReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#a22fce5a901cab04aa9681d1684c74d37">isACCRegNumber</a>.</p>


<p>Referenced by <a href="#a12210c238d328df79afbb1bf5b8d330f">addRegACCRCOperands</a>, <a href="#a95631286ee78d31fa6a320bdd65adf1a">addRegWACC_HIRCOperands</a> and <a href="#ad1fb4b2250fe4553fafb1966344239be">addRegWACCRCOperands</a>.</p>

</div>
</div>

### getCCReg() {#a420139fede0b33009661079f322f4cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getCCReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab4cc89859c1adb2b4012f3ad7118d52e">Expr</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="#af742da66f9d94de298a7eb84616cff18">isCCRegNumber</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#a261bc82cf89578d4cad2017373d2000d">addRegCRRCOperands</a>.</p>

</div>
</div>

### getCRBit() {#abd4cd7b3f3f4c18acd2628544ffc4992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getCRBit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab4cc89859c1adb2b4012f3ad7118d52e">Expr</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="#a3e56d29ba6ed0224bea08c9ff5caee25">isCRBitNumber</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#ac9f272922c818ce3d068c8da3b088e51">addRegCRBITRCOperands</a>.</p>

</div>
</div>

### getCRBitMask() {#afbbf9811e42d91f85362752c7ddd11cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getCRBitMask ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#af2e2413edff2117a52f84bc36ebf51e3">isCRBitMask</a>.</p>


<p>Referenced by <a href="#a5416ccbb01a0d1a87c306aa8f9229cc7">addCRBitMaskOperands</a>.</p>

</div>
</div>

### getDMRpReg() {#a9ef0e8519b1c606d1417b6ec8cdb8699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getDMRpReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#a912c40d665c2b1565fdef84b6dd79446">isDMRpRegNumber</a>.</p>


<p>Referenced by <a href="#a179ed03cc48e9a5569d66a7f44576942">addRegDMRpRCOperands</a>.</p>

</div>
</div>

### getDMRReg() {#af11d782ee7e0deedd06746f2c86e8d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getDMRReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#ac40460073342cc0a79bedd462a290ccd">isDMRRegNumber</a>.</p>


<p>Referenced by <a href="#af033d8ccbf4172c8b4e289ddc6b645f7">addRegDMRRCOperands</a>.</p>

</div>
</div>

### getDMRROWpReg() {#afb8fb4cf52ee38e36ecc1eab57c15cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getDMRROWpReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#aee51047a4aa81dc5a6a34c4d1afc2bf5">isDMRROWpRegNumber</a>.</p>


<p>Referenced by <a href="#ad5ff3b4938bbefa984a374310ba12b8e">addRegDMRROWpRCOperands</a>.</p>

</div>
</div>

### getDMRROWReg() {#a2c2e82336cade5bd080afad399904b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getDMRROWReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#a51f84e1223953fa166b5a060e7bdaa00">isDMRROWRegNumber</a>.</p>


<p>Referenced by <a href="#a6b9fc1453025fe740abd2314b1edce41">addRegDMRROWRCOperands</a>.</p>

</div>
</div>

### getEndLoc() {#ae096c59c5a80ed11a3f32924cee86aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{PPCAsmParser.cpp}::PPCOperand::getEndLoc ()</td>
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

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Reference <a href="#ac012c990b558984dc92d3b247ffa52b7">EndLoc</a>.</p>

</div>
</div>

### getExpr() {#af10ee31543b73261c04cda2defa75de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{PPCAsmParser.cpp}::PPCOperand::getExpr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab4cc89859c1adb2b4012f3ad7118d52e">Expr</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#ae4e11d80124a79d601e7d34d463ff119">addBranchTargetOperands</a>, <a href="#a713d7daafa349daa3ed89e1cf32844ba">addImmOperands</a>, <a href="#abc4166605fc07257d0de56a87f4b3f0d">addS16ImmOperands</a>, <a href="#a25f8f8640a87306d856954ff636e3c54">addU16ImmOperands</a> and <a href="#a20157fd0e76f33a15a770adf3790a7ff">print</a>.</p>

</div>
</div>

### getExprCRVal() {#aa6192ac623dde968e730b9fa3c0bb1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{PPCAsmParser.cpp}::PPCOperand::getExprCRVal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab4cc89859c1adb2b4012f3ad7118d52e">Expr</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#af742da66f9d94de298a7eb84616cff18">isCCRegNumber</a> and <a href="#a3e56d29ba6ed0224bea08c9ff5caee25">isCRBitNumber</a>.</p>

</div>
</div>

### getFpReg() {#a692b3490ec9d6143561aa09bb5171f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getFpReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#ad424624defbddac75756d98d6a6b71d4">isEvenRegNumber</a>.</p>


<p>Referenced by <a href="#adfbd9f9bd8886de9cc1ce69aa19cecce">addRegFpRCOperands</a>.</p>

</div>
</div>

### getG8pReg() {#ac31394c25c9ca05d1190f57f9eb70cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getG8pReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#ad424624defbddac75756d98d6a6b71d4">isEvenRegNumber</a>.</p>


<p>Referenced by <a href="#a4f7c8642744e66352d3f0484f6b9f291">addRegG8pRCOperands</a>.</p>

</div>
</div>

### getImm() {#a383385f08edecc84e33ca9d00e5ec56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{PPCAsmParser.cpp}::PPCOperand::getImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#ae4e11d80124a79d601e7d34d463ff119">addBranchTargetOperands</a>, <a href="#a713d7daafa349daa3ed89e1cf32844ba">addImmOperands</a>, <a href="#abc4166605fc07257d0de56a87f4b3f0d">addS16ImmOperands</a>, <a href="#a25f8f8640a87306d856954ff636e3c54">addU16ImmOperands</a>, <a href="#a22fce5a901cab04aa9681d1684c74d37">isACCRegNumber</a>, <a href="#af742da66f9d94de298a7eb84616cff18">isCCRegNumber</a>, <a href="#ad567b66d66e2323125ca82fa2b0f9108">isCondBr</a>, <a href="#af2e2413edff2117a52f84bc36ebf51e3">isCRBitMask</a>, <a href="#a3e56d29ba6ed0224bea08c9ff5caee25">isCRBitNumber</a>, <a href="#a4de939ce83874ff932546d8d24d9a39e">isDirectBr</a>, <a href="#a912c40d665c2b1565fdef84b6dd79446">isDMRpRegNumber</a>, <a href="#ac40460073342cc0a79bedd462a290ccd">isDMRRegNumber</a>, <a href="#aee51047a4aa81dc5a6a34c4d1afc2bf5">isDMRROWpRegNumber</a>, <a href="#a51f84e1223953fa166b5a060e7bdaa00">isDMRROWRegNumber</a>, <a href="#ad424624defbddac75756d98d6a6b71d4">isEvenRegNumber</a>, <a href="#afdbfe738015fe099912f6d24fb9c733c">isHashImmX8</a>, <a href="#aedf6f7c15b9c6422776e19d882ac078d">isImmZero</a>, <a href="#abeb9f6db146551815f7788069c268a70">isRegNumber</a>, <a href="#acbb6cb9de0fa635a83d33e1b0af34f75">isS34Imm</a>, <a href="#a5c7e807b8fc8cb08c52a62a89416609f">isS34ImmX16</a>, <a href="#a2c9bf1a794738d85346b7604c546fa35">isS5Imm</a>, <a href="#a5d5f836ffdb5137ec44a9bb9531afbae">isU10Imm</a>, <a href="#a231f7258845b174145f4d49bbf504e05">isU12Imm</a>, <a href="#a5f7e780fcd1fca846da3453e80b9956b">isU1Imm</a>, <a href="#a9b3d4e189a0ebf4181ec540574b21f10">isU2Imm</a>, <a href="#aad9f1ba12f4e58e4bc5bab488d189949">isU3Imm</a>, <a href="#a2e2930e8de3d14ec58fedfac120a8e02">isU4Imm</a>, <a href="#a857b7ac2b20fc1e6bb5d99084f53da21">isU5Imm</a>, <a href="#afc7e147bc2b88d8cb5a65c57953444c6">isU6Imm</a>, <a href="#a64f4028a12c599b4c539b8579a62f547">isU6ImmX2</a>, <a href="#a701430ad4879a7023430e35263b9b3e5">isU7Imm</a>, <a href="#a377edbc4aee80a8abe8d2016c3f6b821">isU7ImmX4</a>, <a href="#a997aee7bc438bbe5faa941e56d91580e">isU8Imm</a>, <a href="#add31352045a5b5e0247a9aaa6c490499">isU8ImmX8</a>, <a href="#a5380af69ce06d80a1d4b43a7b2867d2b">isVSRegNumber</a>, <a href="#a48151a184723b552d9412bcb78ee95f0">isVSRpEvenRegNumber</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a7a8526125b46eeca9eb066fedddefa6f">anonymous{PPCAsmParser.cpp}::PPCAsmParser::parseInstruction</a> and <a href="#a20157fd0e76f33a15a770adf3790a7ff">print</a>.</p>

</div>
</div>

### getImmS16Context() {#adb1034deebd58e871c3492e943d266ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{PPCAsmParser.cpp}::PPCOperand::getImmS16Context ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aed8df6b976d72b6f68a15d5a93b3d2f9">ContextImmediate</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#abc4166605fc07257d0de56a87f4b3f0d">addS16ImmOperands</a>.</p>

</div>
</div>

### getImmU16Context() {#a771af6229c9ebe45f90a0a4a9fae5ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{PPCAsmParser.cpp}::PPCOperand::getImmU16Context ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aed8df6b976d72b6f68a15d5a93b3d2f9">ContextImmediate</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#a25f8f8640a87306d856954ff636e3c54">addU16ImmOperands</a>.</p>

</div>
</div>

### getLocRange() {#ae8f09afbbbd490d3dea1581bb6822f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange anonymous{PPCAsmParser.cpp}::PPCOperand::getLocRange ()</td>
</tr>
</table>
</td>
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

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#ac012c990b558984dc92d3b247ffa52b7">EndLoc</a> and <a href="#a68b535568a91966aa77b76522e3cc0ce">StartLoc</a>.</p>

</div>
</div>

### getReg() {#a3493a3463a7b84d4c1ed90351b0255cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{PPCAsmParser.cpp}::PPCOperand::getReg ()</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getRegNum() {#aeca22bd498258dd09d43340c64f85425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getRegNum ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#abeb9f6db146551815f7788069c268a70">isRegNumber</a>.</p>

</div>
</div>

### getStartLoc() {#a2212381a63a9401192ca4cd2e0848d57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{PPCAsmParser.cpp}::PPCOperand::getStartLoc ()</td>
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

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Reference <a href="#a68b535568a91966aa77b76522e3cc0ce">StartLoc</a>.</p>

</div>
</div>

### getTLSReg() {#aaefa9109db2aed80c122b9e1f8d560ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{PPCAsmParser.cpp}::PPCOperand::getTLSReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>, <a href="#abddf336f0120b6831b1ba59dcc7cd634">TLSReg</a> and <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a1c6f17770c851308ee7cb87d34e6ddb7">TLSRegister</a>.</p>


<p>Referenced by <a href="#ab4ff241ea58ce22b2fb48a3fbb7f1085">addTLSRegOperands</a> and <a href="#a20157fd0e76f33a15a770adf3790a7ff">print</a>.</p>

</div>
</div>

### getToken() {#a7d3c212ecbec16b2898f24ff0b7d0ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{PPCAsmParser.cpp}::PPCOperand::getToken ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>, <a href="#a69a3018fe530c9dfd18d2dfd18f7b3fb">Tok</a> and <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aaf48d38972ba0f8d5b65f8df03110403">Token</a>.</p>


<p>Referenced by <a href="#a20157fd0e76f33a15a770adf3790a7ff">print</a>.</p>

</div>
</div>

### getVSReg() {#a1cc37ea8cfbc538c93441d960be37101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getVSReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#a5380af69ce06d80a1d4b43a7b2867d2b">isVSRegNumber</a>.</p>


<p>Referenced by <a href="#ae671f24372f1086564183e87fa417d64">addRegVSFRCOperands</a>, <a href="#ae738609c642f9c748c350ac993771f5a">addRegVSRCOperands</a> and <a href="#a084aa0e18d26956a3e8c10627318e6d6">addRegVSSRCOperands</a>.</p>

</div>
</div>

### getVSRpEvenReg() {#ac96d434c457c8c5fea171cd4efea30c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCAsmParser.cpp}::PPCOperand::getVSRpEvenReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a> and <a href="#a48151a184723b552d9412bcb78ee95f0">isVSRpEvenRegNumber</a>.</p>


<p>Referenced by <a href="#a148f711934b9ce4ad92cedcc83542771">addRegVSRpEvenRCOperands</a> and <a href="#a994642f0fa42d7b1ec9557c989e816e5">addRegVSRpRCOperands</a>.</p>

</div>
</div>

### isACCRegNumber() {#a22fce5a901cab04aa9681d1684c74d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isACCRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#afd47908f21bc243be854f13fd2696be0">getACCReg</a>.</p>

</div>
</div>

### isATBitsAsHint() {#a90e12157eb12d9afce2e53d46fc102e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isATBitsAsHint ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### isCCRegNumber() {#af742da66f9d94de298a7eb84616cff18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isCCRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a>, <a href="#aa6192ac623dde968e730b9fa3c0bb1cb">getExprCRVal</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#a420139fede0b33009661079f322f4cd7">getCCReg</a>.</p>

</div>
</div>

### isCondBr() {#ad567b66d66e2323125ca82fa2b0f9108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isCondBr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isCRBitMask() {#af2e2413edff2117a52f84bc36ebf51e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isCRBitMask ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#afbbf9811e42d91f85362752c7ddd11cb">getCRBitMask</a>.</p>

</div>
</div>

### isCRBitNumber() {#a3e56d29ba6ed0224bea08c9ff5caee25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isCRBitNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a>, <a href="#aa6192ac623dde968e730b9fa3c0bb1cb">getExprCRVal</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#abd4cd7b3f3f4c18acd2628544ffc4992">getCRBit</a>.</p>

</div>
</div>

### isDirectBr() {#a4de939ce83874ff932546d8d24d9a39e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isDirectBr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isDMRpRegNumber() {#a912c40d665c2b1565fdef84b6dd79446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isDMRpRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#a9ef0e8519b1c606d1417b6ec8cdb8699">getDMRpReg</a>.</p>

</div>
</div>

### isDMRRegNumber() {#ac40460073342cc0a79bedd462a290ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isDMRRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#af11d782ee7e0deedd06746f2c86e8d34">getDMRReg</a>.</p>

</div>
</div>

### isDMRROWpRegNumber() {#aee51047a4aa81dc5a6a34c4d1afc2bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isDMRROWpRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#afb8fb4cf52ee38e36ecc1eab57c15cd9">getDMRROWpReg</a>.</p>

</div>
</div>

### isDMRROWRegNumber() {#a51f84e1223953fa166b5a060e7bdaa00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isDMRROWRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#a2c2e82336cade5bd080afad399904b2b">getDMRROWReg</a>.</p>

</div>
</div>

### isEvenRegNumber() {#ad424624defbddac75756d98d6a6b71d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isEvenRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a> and <a href="#abeb9f6db146551815f7788069c268a70">isRegNumber</a>.</p>


<p>Referenced by <a href="#a692b3490ec9d6143561aa09bb5171f24">getFpReg</a> and <a href="#ac31394c25c9ca05d1190f57f9eb70cd0">getG8pReg</a>.</p>

</div>
</div>

### isHashImmX8() {#afdbfe738015fe099912f6d24fb9c733c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isHashImmX8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isImm() {#a8b696a091eb94c73cf6bdd5a16f93161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isImm ()</td>
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

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isImmZero() {#aedf6f7c15b9c6422776e19d882ac078d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isImmZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isMem() {#a3808574b283c9d38f502dabf1682d3a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isMem ()</td>
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

<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### isMemOpBase() {#a914c12de5acc75d734ef554d1b4ee24a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isMemOpBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isMemOpBase - True if this operand is the base of a memory operand.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a9cae142752dfe139534b5eb738ee9e5d">Imm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isPPC64() {#a6480a22ac6ebd233e909aaaaf62b07c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isPPC64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isPPC64 - True if this operand is for an instruction in 64-bit mode.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Reference <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a>.</p>


<p>Referenced by <a href="#a2fb6dfb246e08cada6c1ee959fa370b5">addRegGxRCNoR0Operands</a>, <a href="#a520869629199796c869900cd4531fb96">addRegGxRCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a0e9209ef161dfa2b45ab9f122f2ada34">anonymous{PPCAsmParser.cpp}::PPCAsmParser::ParseDirective</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a7a8526125b46eeca9eb066fedddefa6f">anonymous{PPCAsmParser.cpp}::PPCAsmParser::parseInstruction</a>.</p>

</div>
</div>

### isReg() {#af932177edee5402a8b769fe68a7eae3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isReg ()</td>
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

<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### isRegNumber() {#abeb9f6db146551815f7788069c268a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#aeca22bd498258dd09d43340c64f85425">getRegNum</a> and <a href="#ad424624defbddac75756d98d6a6b71d4">isEvenRegNumber</a>.</p>

</div>
</div>

### isS16Imm() {#a0dfdb5e0fcd33e4038caf0703ad56a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isS16Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### isS16ImmX16() {#a04fbcfd67eb7f189c743ead1f088375b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isS16ImmX16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### isS16ImmX4() {#aa1258a10dba8cca7134d342632f6f395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isS16ImmX4 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### isS17Imm() {#a3b58203dceb224394d68960ff55d1865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isS17Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### isS34Imm() {#acbb6cb9de0fa635a83d33e1b0af34f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isS34Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isS34ImmX16() {#a5c7e807b8fc8cb08c52a62a89416609f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isS34ImmX16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isS5Imm() {#a2c9bf1a794738d85346b7604c546fa35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isS5Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isTLSReg() {#a9bf08bbc56e651bb431a913bb734e116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isTLSReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a> and <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a1c6f17770c851308ee7cb87d34e6ddb7">TLSRegister</a>.</p>

</div>
</div>

### isToken() {#a455ced885ddd5aefe302a90a58c68cb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isToken ()</td>
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

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a> and <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aaf48d38972ba0f8d5b65f8df03110403">Token</a>.</p>

</div>
</div>

### isU10Imm() {#a5d5f836ffdb5137ec44a9bb9531afbae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU10Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU12Imm() {#a231f7258845b174145f4d49bbf504e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU12Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU16Imm() {#a62aa807f340ba4f274f6b0dfe4e8edaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU16Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### isU1Imm() {#a5f7e780fcd1fca846da3453e80b9956b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU1Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a7a8526125b46eeca9eb066fedddefa6f">anonymous{PPCAsmParser.cpp}::PPCAsmParser::parseInstruction</a>.</p>

</div>
</div>

### isU2Imm() {#a9b3d4e189a0ebf4181ec540574b21f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU2Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU3Imm() {#aad9f1ba12f4e58e4bc5bab488d189949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU3Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU4Imm() {#a2e2930e8de3d14ec58fedfac120a8e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU4Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU5Imm() {#a857b7ac2b20fc1e6bb5d99084f53da21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU5Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU6Imm() {#afc7e147bc2b88d8cb5a65c57953444c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU6Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU6ImmX2() {#a64f4028a12c599b4c539b8579a62f547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU6ImmX2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU7Imm() {#a701430ad4879a7023430e35263b9b3e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU7Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU7ImmX4() {#a377edbc4aee80a8abe8d2016c3f6b821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU7ImmX4 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU8Imm() {#a997aee7bc438bbe5faa941e56d91580e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU8Imm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isU8ImmX8() {#add31352045a5b5e0247a9aaa6c490499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isU8ImmX8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>

</div>
</div>

### isVSRegNumber() {#a5380af69ce06d80a1d4b43a7b2867d2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isVSRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#a1cc37ea8cfbc538c93441d960be37101">getVSReg</a>.</p>

</div>
</div>

### isVSRpEvenRegNumber() {#a48151a184723b552d9412bcb78ee95f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isVSRpEvenRegNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>.</p>


<p>Referenced by <a href="#ac96d434c457c8c5fea171cd4efea30c3">getVSRpEvenReg</a>.</p>

</div>
</div>

### print() {#a20157fd0e76f33a15a770adf3790a7ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aed8df6b976d72b6f68a15d5a93b3d2f9">ContextImmediate</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a>, <a href="#af10ee31543b73261c04cda2defa75de5">getExpr</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#aaefa9109db2aed80c122b9e1f8d560ea">getTLSReg</a>, <a href="#a7d3c212ecbec16b2898f24ff0b7d0ca5">getToken</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a>, <a href="#ae5b523f052735b5f4f6cd772c692e62b">Kind</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a1c6f17770c851308ee7cb87d34e6ddb7">TLSRegister</a> and <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aaf48d38972ba0f8d5b65f8df03110403">Token</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isExtImm() {#a26206c8c7721a537c5645f13ee6315f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::isExtImm (bool Signed, unsigned Multiple)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a6526407a6b80ee4d2c10714ae08f9e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{PPCAsmParser.cpp}::PPCOperand anonymous{PPCAsmParser.cpp}::PPCOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>

</div>
</div>

### EndLoc {#ac012c990b558984dc92d3b247ffa52b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{PPCAsmParser.cpp}::PPCOperand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ae096c59c5a80ed11a3f32924cee86aa4">getEndLoc</a>, <a href="#ae8f09afbbbd490d3dea1581bb6822f1a">getLocRange</a> and <a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a>.</p>

</div>
</div>

### Expr {#ab4cc89859c1adb2b4012f3ad7118d52e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ExprOp anonymous{PPCAsmParser.cpp}::PPCOperand::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a420139fede0b33009661079f322f4cd7">getCCReg</a>, <a href="#abd4cd7b3f3f4c18acd2628544ffc4992">getCRBit</a>, <a href="#af10ee31543b73261c04cda2defa75de5">getExpr</a>, <a href="#aa6192ac623dde968e730b9fa3c0bb1cb">getExprCRVal</a> and <a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a>.</p>

</div>
</div>

### Imm {#a9cae142752dfe139534b5eb738ee9e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ImmOp anonymous{PPCAsmParser.cpp}::PPCOperand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#afd47908f21bc243be854f13fd2696be0">getACCReg</a>, <a href="#a420139fede0b33009661079f322f4cd7">getCCReg</a>, <a href="#abd4cd7b3f3f4c18acd2628544ffc4992">getCRBit</a>, <a href="#afbbf9811e42d91f85362752c7ddd11cb">getCRBitMask</a>, <a href="#a9ef0e8519b1c606d1417b6ec8cdb8699">getDMRpReg</a>, <a href="#af11d782ee7e0deedd06746f2c86e8d34">getDMRReg</a>, <a href="#afb8fb4cf52ee38e36ecc1eab57c15cd9">getDMRROWpReg</a>, <a href="#a2c2e82336cade5bd080afad399904b2b">getDMRROWReg</a>, <a href="#a692b3490ec9d6143561aa09bb5171f24">getFpReg</a>, <a href="#ac31394c25c9ca05d1190f57f9eb70cd0">getG8pReg</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#adb1034deebd58e871c3492e943d266ae">getImmS16Context</a>, <a href="#a771af6229c9ebe45f90a0a4a9fae5ca9">getImmU16Context</a>, <a href="#aeca22bd498258dd09d43340c64f85425">getRegNum</a>, <a href="#a1cc37ea8cfbc538c93441d960be37101">getVSReg</a>, <a href="#ac96d434c457c8c5fea171cd4efea30c3">getVSRpEvenReg</a>, <a href="#a914c12de5acc75d734ef554d1b4ee24a">isMemOpBase</a> and <a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a>.</p>

</div>
</div>

### IsPPC64 {#acc599d567fbb545ae845c5993d575051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCAsmParser.cpp}::PPCOperand::IsPPC64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#afe47a7edc64d1a798629c7610f110a18">CreateContextImm</a>, <a href="#af62b42fd31f3597b479e46c299c0b7e4">CreateExpr</a>, <a href="#ab21aef0218253cc55d4f082c34327d40">CreateFromMCExpr</a>, <a href="#a0eeecc72015c256728aafacf157f8af1">CreateImm</a>, <a href="#a45965995484c74a694ac62c4ace838a5">CreateTLSReg</a>, <a href="#ade80d23dae3697bbc7e8c429da708dc3">CreateToken</a>, <a href="#ad4116a0530b455559f9a6472ab5ea9ea">CreateTokenWithStringCopy</a>, <a href="#a4de939ce83874ff932546d8d24d9a39e">isDirectBr</a>, <a href="#a6480a22ac6ebd233e909aaaaf62b07c7">isPPC64</a> and <a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a>.</p>

</div>
</div>

### Kind {#ae5b523f052735b5f4f6cd772c692e62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{PPCAsmParser.cpp}::PPCOperand::KindTy anonymous{PPCAsmParser.cpp}::PPCOperand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ae4e11d80124a79d601e7d34d463ff119">addBranchTargetOperands</a>, <a href="#a713d7daafa349daa3ed89e1cf32844ba">addImmOperands</a>, <a href="#abc4166605fc07257d0de56a87f4b3f0d">addS16ImmOperands</a>, <a href="#a25f8f8640a87306d856954ff636e3c54">addU16ImmOperands</a>, <a href="#a420139fede0b33009661079f322f4cd7">getCCReg</a>, <a href="#abd4cd7b3f3f4c18acd2628544ffc4992">getCRBit</a>, <a href="#af10ee31543b73261c04cda2defa75de5">getExpr</a>, <a href="#aa6192ac623dde968e730b9fa3c0bb1cb">getExprCRVal</a>, <a href="#a383385f08edecc84e33ca9d00e5ec56d">getImm</a>, <a href="#adb1034deebd58e871c3492e943d266ae">getImmS16Context</a>, <a href="#a771af6229c9ebe45f90a0a4a9fae5ca9">getImmU16Context</a>, <a href="#aaefa9109db2aed80c122b9e1f8d560ea">getTLSReg</a>, <a href="#a7d3c212ecbec16b2898f24ff0b7d0ca5">getToken</a>, <a href="#a22fce5a901cab04aa9681d1684c74d37">isACCRegNumber</a>, <a href="#af742da66f9d94de298a7eb84616cff18">isCCRegNumber</a>, <a href="#ad567b66d66e2323125ca82fa2b0f9108">isCondBr</a>, <a href="#af2e2413edff2117a52f84bc36ebf51e3">isCRBitMask</a>, <a href="#a3e56d29ba6ed0224bea08c9ff5caee25">isCRBitNumber</a>, <a href="#a4de939ce83874ff932546d8d24d9a39e">isDirectBr</a>, <a href="#a912c40d665c2b1565fdef84b6dd79446">isDMRpRegNumber</a>, <a href="#ac40460073342cc0a79bedd462a290ccd">isDMRRegNumber</a>, <a href="#aee51047a4aa81dc5a6a34c4d1afc2bf5">isDMRROWpRegNumber</a>, <a href="#a51f84e1223953fa166b5a060e7bdaa00">isDMRROWRegNumber</a>, <a href="#afdbfe738015fe099912f6d24fb9c733c">isHashImmX8</a>, <a href="#a8b696a091eb94c73cf6bdd5a16f93161">isImm</a>, <a href="#aedf6f7c15b9c6422776e19d882ac078d">isImmZero</a>, <a href="#a914c12de5acc75d734ef554d1b4ee24a">isMemOpBase</a>, <a href="#abeb9f6db146551815f7788069c268a70">isRegNumber</a>, <a href="#acbb6cb9de0fa635a83d33e1b0af34f75">isS34Imm</a>, <a href="#a5c7e807b8fc8cb08c52a62a89416609f">isS34ImmX16</a>, <a href="#a2c9bf1a794738d85346b7604c546fa35">isS5Imm</a>, <a href="#a9bf08bbc56e651bb431a913bb734e116">isTLSReg</a>, <a href="#a455ced885ddd5aefe302a90a58c68cb2">isToken</a>, <a href="#a5d5f836ffdb5137ec44a9bb9531afbae">isU10Imm</a>, <a href="#a231f7258845b174145f4d49bbf504e05">isU12Imm</a>, <a href="#a5f7e780fcd1fca846da3453e80b9956b">isU1Imm</a>, <a href="#a9b3d4e189a0ebf4181ec540574b21f10">isU2Imm</a>, <a href="#aad9f1ba12f4e58e4bc5bab488d189949">isU3Imm</a>, <a href="#a2e2930e8de3d14ec58fedfac120a8e02">isU4Imm</a>, <a href="#a857b7ac2b20fc1e6bb5d99084f53da21">isU5Imm</a>, <a href="#afc7e147bc2b88d8cb5a65c57953444c6">isU6Imm</a>, <a href="#a64f4028a12c599b4c539b8579a62f547">isU6ImmX2</a>, <a href="#a701430ad4879a7023430e35263b9b3e5">isU7Imm</a>, <a href="#a377edbc4aee80a8abe8d2016c3f6b821">isU7ImmX4</a>, <a href="#a997aee7bc438bbe5faa941e56d91580e">isU8Imm</a>, <a href="#add31352045a5b5e0247a9aaa6c490499">isU8ImmX8</a>, <a href="#a5380af69ce06d80a1d4b43a7b2867d2b">isVSRegNumber</a>, <a href="#a48151a184723b552d9412bcb78ee95f0">isVSRpEvenRegNumber</a>, <a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a>, <a href="#af1be76281c13e0cef6e6a12dcb5a4f20">PPCOperand</a> and <a href="#a20157fd0e76f33a15a770adf3790a7ff">print</a>.</p>

</div>
</div>

### StartLoc {#a68b535568a91966aa77b76522e3cc0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{PPCAsmParser.cpp}::PPCOperand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ae8f09afbbbd490d3dea1581bb6822f1a">getLocRange</a>, <a href="#a2212381a63a9401192ca4cd2e0848d57">getStartLoc</a> and <a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a>.</p>

</div>
</div>

### TLSReg {#abddf336f0120b6831b1ba59dcc7cd634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct TLSRegOp anonymous{PPCAsmParser.cpp}::PPCOperand::TLSReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#aaefa9109db2aed80c122b9e1f8d560ea">getTLSReg</a> and <a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a>.</p>

</div>
</div>

### Tok {#a69a3018fe530c9dfd18d2dfd18f7b3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct TokOp anonymous{PPCAsmParser.cpp}::PPCOperand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a7d3c212ecbec16b2898f24ff0b7d0ca5">getToken</a> and <a href="#ac03530ad5518aada38f4fb6fd29e7c90">PPCOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CreateContextImm() {#afe47a7edc64d1a798629c7610f110a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PPCOperand &gt; anonymous{PPCAsmParser.cpp}::PPCOperand::CreateContextImm (int64_t Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, bool IsPPC64)</td>
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



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aed8df6b976d72b6f68a15d5a93b3d2f9">ContextImmediate</a> and <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a>.</p>


<p>Referenced by <a href="#ab21aef0218253cc55d4f082c34327d40">CreateFromMCExpr</a>.</p>

</div>
</div>

### CreateExpr() {#af62b42fd31f3597b479e46c299c0b7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PPCOperand &gt; anonymous{PPCAsmParser.cpp}::PPCOperand::CreateExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, bool IsPPC64)</td>
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



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a3d4443a5f4df398bcde06fae90a11c04">EvaluateCRExpr</a>, <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a9d866c8bff40984f5af8ce295ce81cf4">Expression</a> and <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a>.</p>


<p>Referenced by <a href="#ab21aef0218253cc55d4f082c34327d40">CreateFromMCExpr</a>.</p>

</div>
</div>

### CreateFromMCExpr() {#ab21aef0218253cc55d4f082c34327d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PPCOperand &gt; anonymous{PPCAsmParser.cpp}::PPCOperand::CreateFromMCExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, bool IsPPC64)</td>
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



<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afe47a7edc64d1a798629c7610f110a18">CreateContextImm</a>, <a href="#af62b42fd31f3597b479e46c299c0b7e4">CreateExpr</a>, <a href="#a0eeecc72015c256728aafacf157f8af1">CreateImm</a>, <a href="#a45965995484c74a694ac62c4ace838a5">CreateTLSReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a1ebb65d3581b26c6d9be3d4ff95d8648">llvm::MCSymbolRefExpr::VK_PPC_TLS</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a3af1b5ef4b41faa6d2e73935860fa3c0">llvm::MCSymbolRefExpr::VK_PPC_TLS_PCREL</a>.</p>

</div>
</div>

### CreateImm() {#a0eeecc72015c256728aafacf157f8af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PPCOperand &gt; anonymous{PPCAsmParser.cpp}::PPCOperand::CreateImm (int64_t Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, bool IsPPC64, bool IsMemOpBase=false)</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a61032ce754b7f4646d6e71462970261b">Immediate</a> and <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a>.</p>


<p>Referenced by <a href="#ab21aef0218253cc55d4f082c34327d40">CreateFromMCExpr</a>.</p>

</div>
</div>

### CreateTLSReg() {#a45965995484c74a694ac62c4ace838a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PPCOperand &gt; anonymous{PPCAsmParser.cpp}::PPCOperand::CreateTLSReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * Sym, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, bool IsPPC64)</td>
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



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a> and <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8a1c6f17770c851308ee7cb87d34e6ddb7">TLSRegister</a>.</p>


<p>Referenced by <a href="#ab21aef0218253cc55d4f082c34327d40">CreateFromMCExpr</a>.</p>

</div>
</div>

### CreateToken() {#ade80d23dae3697bbc7e8c429da708dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PPCOperand &gt; anonymous{PPCAsmParser.cpp}::PPCOperand::CreateToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, bool IsPPC64)</td>
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



<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a> and <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aaf48d38972ba0f8d5b65f8df03110403">Token</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a7a8526125b46eeca9eb066fedddefa6f">anonymous{PPCAsmParser.cpp}::PPCAsmParser::parseInstruction</a>.</p>

</div>
</div>

### CreateTokenWithStringCopy() {#ad4116a0530b455559f9a6472ab5ea9ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PPCOperand &gt; anonymous{PPCAsmParser.cpp}::PPCOperand::CreateTokenWithStringCopy (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, bool IsPPC64)</td>
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



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a>.</p>


<p>References <a href="#acc599d567fbb545ae845c5993d575051">IsPPC64</a>, <a href="#af1be76281c13e0cef6e6a12dcb5a4f20">PPCOperand</a> and <a href="#afaa2f6edfd12b232a9ff1fab1ef0fba8aaf48d38972ba0f8d5b65f8df03110403">Token</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a7a8526125b46eeca9eb066fedddefa6f">anonymous{PPCAsmParser.cpp}::PPCAsmParser::parseInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp">PPCAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
