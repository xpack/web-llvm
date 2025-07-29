---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-cskyasmparser-cpp-/cskyoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CSKYOperand` Struct

<p>Instances of this class represent a parsed machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{CSKYAsmParser.cpp}::CSKYOperand { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#a0fe109a97f1922d132a1dfdc52675b2f">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88892b58e78c13c97a82708d90d1b921">CSKYOperand</a> (KindTy K)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a> (const CSKYOperand &amp;o)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a251be8cb301dfe4feeb7c767cbc635b3">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#a251be8cb301dfe4feeb7c767cbc635b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9b8dec485b89adcdd448343390effc">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#a4e9b8dec485b89adcdd448343390effc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09793ba5bf1799c2844d6874a46719b9">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#a09793ba5bf1799c2844d6874a46719b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30539fea2253aa55aa1535edf7d4b6d2">isRegisterSeq</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636dd430d6ce22eaab127b74938fd49d">isRegisterList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69735d9460f81c6cab80fc9935aa43cd">isConstPoolOp</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04d4df7e90d08b2eabc917387ed5787b">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#a04d4df7e90d08b2eabc917387ed5787b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned num, unsigned shift = 0&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned num&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned num, unsigned shift = 0&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acdbc1487f391e78aa1b636227447099a">isSImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5760235fc53e6a6d90296001f10a27">isUImm1</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72dce4d8ff8e291219b30f37759a1f10">isUImm2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8679bbd6b778cca85e50697ead9eaff2">isUImm3</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22178c108295438aa12eea4972982fe1">isUImm4</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e87b9c31a4dfe49c9f33f7b19411a53">isUImm5</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2a75b9d63e952fcde5f3657fe12627d">isUImm6</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9bdb38aafda73ce8bdacb8a2f23e72">isUImm7</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5abcf11d32813821864d9e930627e68">isUImm8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca16f6ac9d7f22d7afe10c73be5a21d">isUImm12</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cff9c35cf1ac9cd0a55defed64b7798">isUImm16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d9012e70868641adb0cabbdf024382e">isUImm20</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b4b1f8a53801ae858fbeb81c04202e">isUImm24</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8847855febc99a582c22c9502752dd">isOImm3</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9b270b995abbff123e5c79f86cf9829">isOImm4</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6271e4be92f09f44747e9ce22e868d2">isOImm5</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08873f53446ab5dd2aee02737360b897">isOImm6</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a10d298d3ed343d7253be98d71e9db">isOImm8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d57e323aa8928d008390cfc0774a2ec">isOImm12</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc188e9a8d5bcca62b9e4753307c04e">isOImm16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a1385e17f646621e3a78f3741ea011">isSImm8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4f40b5142c3e4e0432b8bb304a7b935">isUImm5Shift1</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77523165d03f68032b922fe562d8b2d5">isUImm5Shift2</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507a09500e5796160245523152f00403">isUImm7Shift1</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed6a7d5f2a3126bad797147853a5ed85">isUImm7Shift2</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d9bb0c0111a2e0dde4c7dad5d4857e">isUImm7Shift3</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8868ad3a690cd244634c7f79af476feb">isUImm8Shift2</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93170b824e8cf8a7b7e511d2e81ef719">isUImm8Shift3</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c5db595dd3b8d866b068a24ee7d8783">isUImm8Shift8</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab69b2e5759ea42c3503e5168ed6f1f37">isUImm8Shift16</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a2cce84c7c464a2002b96dd7a0de44">isUImm8Shift24</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affcb13559ab137513ffd0f4219a03cb8">isUImm12Shift1</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea639d0b370c29060471e3f650d84a3d">isUImm12Shift2</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73dee159d511b6b729be34f1a46a8b4">isUImm16Shift8</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14fd60e621e201d571b93f4db2b30d09">isUImm16Shift16</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d4f99576a9d4d60eb9d5544040183f">isUImm24Shift8</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b674e59e4dabb31c06d53bc0b1b4e55">isSImm16Shift1</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb07869c134c15fbc0d6b48d827d0e7">isCSKYSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a0e595461e0016f6c307eb9302c598">isConstpool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f2458135443143a3f94c5a62d497a6f">isDataSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5519906431d13fc0c4cff7eb6ff8e809">isPSRFlag</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned MIN, unsigned MAX&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a097ad70c9670347503bca7f4c2d3d543">isRegSeqTemplate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bc484a2b4b4e2f052ebba4464a778cd">isRegSeq</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6f7c89fcad69c083db6708ed769142">isRegSeqV1</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5de267b6662af9925cc3541d67a6ec6d">isRegSeqV2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c17938b7a6213e6cdb04762c7c91a08">isRegList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a44db62cf1fc6e69f073dbf1e15c63">isExtImm6</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e3b98e29ed23647b30db5cd57ab98b">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets location of the first token of this operand. <a href="#a03e3b98e29ed23647b30db5cd57ab98b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa020b00e4347ac858117d192aafa9ad8">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets location of the last token of this operand. <a href="#aa020b00e4347ac858117d192aafa9ad8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82226e8082bf56eb3426cbc3eea25fda">getReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd47a756076d99f2f08295f610630ee">getRegSeq</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/reglistop">RegListOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a47dab517558178e2f94a6c413c486">getRegList</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680149bff79c86330b611b35156e302a">getImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795b1277e7e49407b1134db5db0422dc">getConstpoolOp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf78a1d51c3fdb8cf27c88c1ca771943">getToken</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfbeadbc6d68319d9559978a6d365e00">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#adfbeadbc6d68319d9559978a6d365e00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00891539f650560293f19ca17fa9160">addExpr</a> (MCInst &amp;Inst, const MCExpr *Expr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a326ed8ed376ee7d1fcd009912f1baadf">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5ea637c5c5977fe147cf7a93f076879">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4945c8a4072ad73e71889ff2d278625a">addConstpoolOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6301f276f11cc6a65a0fa29296aef93">addRegSeqOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ea4b3846e4d8daf60afad674bb0fb0">addRegListOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56950afb2b5f6d3c0f598b69e6c45ae8">isValidForTie</a> (const CSKYOperand &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{CSKYAsmParser.cpp}<a href="#a0fe109a97f1922d132a1dfdc52675b2f">::CSKYOperand::KindTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a178a552fa7eb0c50b588306819a033ab">StartLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d95afdd891e35f4a38639dc2cb0a4d8">EndLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b054fa05e2cb08f31495157b5aaff70">Tok</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/regop">RegOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eebdd79de2bf6787decb0bb6fc5bf59">Reg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/immop">ImmOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3fd7046f832525cda4acc8fc9e0aa08">Imm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/constpoolop">ConstpoolOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c4d96e4fb9435f729c687f6414a418">CPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/regseqop">RegSeqOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab18d807b225db0679487575c916f4722">RegSeq</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/reglistop">RegListOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c5d699778e1dadd461df2c9b44e8be1">RegList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{CSKYAsmParser.cpp}<a href="#a88892b58e78c13c97a82708d90d1b921">::CSKYOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a911af522a4aa66555a0a57c050710522"></a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b89384a7bd1cd36b086fb4c2b45e82">evaluateConstantImm</a> (const MCExpr *Expr, int64_t &amp;Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c0be9264bc2cf05ed0fccb82f4c1c7e">isLegalRegList</a> (unsigned from, unsigned to)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand">CSKYOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b77492d7449280048ddb0cccd3b972">createToken</a> (StringRef Str, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand">CSKYOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c81a9be6ecce267c7d22b9b9390416">createReg</a> (MCRegister RegNo, SMLoc S, SMLoc E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand">CSKYOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73648585f7b7fb9d014cfe008cadbed">createRegSeq</a> (MCRegister RegNoFrom, MCRegister RegNoTo, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand">CSKYOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87fe45f7faab0a040752d07ee871f124">createRegList</a> (const SmallVector&lt; MCRegister, 4 &gt; &amp;reglist, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand">CSKYOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada84f19885a95d7eb7218b96f28a8a40">createImm</a> (const MCExpr *Val, SMLoc S, SMLoc E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand">CSKYOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab931c884e85ca87c3ac707dfe2a17cd2">createConstpoolOp</a> (const MCExpr *Val, SMLoc S, SMLoc E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f848c9950190e2f6c61a3e9832eb5f7">getListValue</a> (unsigned ListFrom, unsigned ListTo)</td>
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

<p>Instances of this class represent a parsed machine instruction.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### KindTy {#a0fe109a97f1922d132a1dfdc52675b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{CSKYAsmParser.cpp}::CSKYOperand::KindTy </td>
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
<td class="doxyEnumItemName">Token<a id="a0fe109a97f1922d132a1dfdc52675b2fa37781a5be8694d18e72031f089ef91f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="a0fe109a97f1922d132a1dfdc52675b2fa1f1e2cb3df3cc93d854ed375c23bd9b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Immediate<a id="a0fe109a97f1922d132a1dfdc52675b2fae6cdfc311fbb7f9ee1b3b89ba3e549ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegisterSeq<a id="a0fe109a97f1922d132a1dfdc52675b2fa8a5271c4d20b8aab935f51381d0a9664"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPOP<a id="a0fe109a97f1922d132a1dfdc52675b2fa46acee502c8e0fb79a4f5766c6ed4dc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegisterList<a id="a0fe109a97f1922d132a1dfdc52675b2fa81026409322963abb764ee5663b75e6f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CSKYOperand() {#a88892b58e78c13c97a82708d90d1b921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CSKYAsmParser.cpp}::CSKYOperand::CSKYOperand (<a href="#a0fe109a97f1922d132a1dfdc52675b2f">KindTy</a> K)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a116eebce8e7768c60749aa19af77f817">llvm::MCParsedAsmOperand::MCParsedAsmOperand</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a> and <a href="#a56950afb2b5f6d3c0f598b69e6c45ae8">isValidForTie</a>.</p>

</div>
</div>

### CSKYOperand() {#a4ca99195c27268f9c7fc1cce995f92f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CSKYAsmParser.cpp}::CSKYOperand::CSKYOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand">CSKYOperand</a> &amp; o)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a25c4d96e4fb9435f729c687f6414a418">CPool</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa46acee502c8e0fb79a4f5766c6ed4dc9">CPOP</a>, <a href="#a88892b58e78c13c97a82708d90d1b921">CSKYOperand</a>, <a href="#a3d95afdd891e35f4a38639dc2cb0a4d8">EndLoc</a>, <a href="#aa3fd7046f832525cda4acc8fc9e0aa08">Imm</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fae6cdfc311fbb7f9ee1b3b89ba3e549ef">Immediate</a>, <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a116eebce8e7768c60749aa19af77f817">llvm::MCParsedAsmOperand::MCParsedAsmOperand</a>, <a href="#a1eebdd79de2bf6787decb0bb6fc5bf59">Reg</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa1f1e2cb3df3cc93d854ed375c23bd9b5">Register</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa81026409322963abb764ee5663b75e6f">RegisterList</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa8a5271c4d20b8aab935f51381d0a9664">RegisterSeq</a>, <a href="#a2c5d699778e1dadd461df2c9b44e8be1">RegList</a>, <a href="#ab18d807b225db0679487575c916f4722">RegSeq</a>, <a href="#a178a552fa7eb0c50b588306819a033ab">StartLoc</a>, <a href="#a5b054fa05e2cb08f31495157b5aaff70">Tok</a> and <a href="#a0fe109a97f1922d132a1dfdc52675b2fa37781a5be8694d18e72031f089ef91f1">Token</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addConstpoolOperands() {#a4945c8a4072ad73e71889ff2d278625a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CSKYAsmParser.cpp}::CSKYOperand::addConstpoolOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="#a795b1277e7e49407b1134db5db0422dc">getConstpoolOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addExpr() {#af00891539f650560293f19ca17fa9160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CSKYAsmParser.cpp}::CSKYOperand::addExpr (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#ae5ea637c5c5977fe147cf7a93f076879">addImmOperands</a>.</p>

</div>
</div>

### addImmOperands() {#ae5ea637c5c5977fe147cf7a93f076879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CSKYAsmParser.cpp}::CSKYOperand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#af00891539f650560293f19ca17fa9160">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a680149bff79c86330b611b35156e302a">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegListOperands() {#a87ea4b3846e4d8daf60afad674bb0fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CSKYAsmParser.cpp}::CSKYOperand::addRegListOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a0f848c9950190e2f6c61a3e9832eb5f7">getListValue</a>, <a href="#a63a47dab517558178e2f94a6c413c486">getRegList</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#a326ed8ed376ee7d1fcd009912f1baadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CSKYAsmParser.cpp}::CSKYOperand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegSeqOperands() {#af6301f276f11cc6a65a0fa29296aef93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CSKYAsmParser.cpp}::CSKYOperand::addRegSeqOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a2fd47a756076d99f2f08295f610630ee">getRegSeq</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getConstpoolOp() {#a795b1277e7e49407b1134db5db0422dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{CSKYAsmParser.cpp}::CSKYOperand::getConstpoolOp ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a25c4d96e4fb9435f729c687f6414a418">CPool</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa46acee502c8e0fb79a4f5766c6ed4dc9">CPOP</a> and <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>.</p>


<p>Referenced by <a href="#a4945c8a4072ad73e71889ff2d278625a">addConstpoolOperands</a> and <a href="#adfbeadbc6d68319d9559978a6d365e00">print</a>.</p>

</div>
</div>

### getEndLoc() {#aa020b00e4347ac858117d192aafa9ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{CSKYAsmParser.cpp}::CSKYOperand::getEndLoc ()</td>
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

<p>Gets location of the last token of this operand.</p>

<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a3d95afdd891e35f4a38639dc2cb0a4d8">EndLoc</a>.</p>

</div>
</div>

### getImm() {#a680149bff79c86330b611b35156e302a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{CSKYAsmParser.cpp}::CSKYOperand::getImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa3fd7046f832525cda4acc8fc9e0aa08">Imm</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fae6cdfc311fbb7f9ee1b3b89ba3e549ef">Immediate</a> and <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>.</p>


<p>Referenced by <a href="#ae5ea637c5c5977fe147cf7a93f076879">addImmOperands</a>, <a href="#a97a44db62cf1fc6e69f073dbf1e15c63">isExtImm6</a>, <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>, <a href="#a5519906431d13fc0c4cff7eb6ff8e809">isPSRFlag</a>, <a href="#acdbc1487f391e78aa1b636227447099a">isSImm</a>, <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a> and <a href="#adfbeadbc6d68319d9559978a6d365e00">print</a>.</p>

</div>
</div>

### getReg() {#a82226e8082bf56eb3426cbc3eea25fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{CSKYAsmParser.cpp}::CSKYOperand::getReg ()</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>, <a href="#a1eebdd79de2bf6787decb0bb6fc5bf59">Reg</a> and <a href="#a0fe109a97f1922d132a1dfdc52675b2fa1f1e2cb3df3cc93d854ed375c23bd9b5">Register</a>.</p>

</div>
</div>

### getRegList() {#a63a47dab517558178e2f94a6c413c486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegListOp anonymous{CSKYAsmParser.cpp}::CSKYOperand::getRegList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa81026409322963abb764ee5663b75e6f">RegisterList</a> and <a href="#a2c5d699778e1dadd461df2c9b44e8be1">RegList</a>.</p>


<p>Referenced by <a href="#a87ea4b3846e4d8daf60afad674bb0fb0">addRegListOperands</a>, <a href="#a5c17938b7a6213e6cdb04762c7c91a08">isRegList</a> and <a href="#adfbeadbc6d68319d9559978a6d365e00">print</a>.</p>

</div>
</div>

### getRegSeq() {#a2fd47a756076d99f2f08295f610630ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; MCRegister, MCRegister &gt; anonymous{CSKYAsmParser.cpp}::CSKYOperand::getRegSeq ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa8a5271c4d20b8aab935f51381d0a9664">RegisterSeq</a> and <a href="#ab18d807b225db0679487575c916f4722">RegSeq</a>.</p>


<p>Referenced by <a href="#af6301f276f11cc6a65a0fa29296aef93">addRegSeqOperands</a>, <a href="#a097ad70c9670347503bca7f4c2d3d543">isRegSeqTemplate</a> and <a href="#adfbeadbc6d68319d9559978a6d365e00">print</a>.</p>

</div>
</div>

### getStartLoc() {#a03e3b98e29ed23647b30db5cd57ab98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{CSKYAsmParser.cpp}::CSKYOperand::getStartLoc ()</td>
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

<p>Gets location of the first token of this operand.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a178a552fa7eb0c50b588306819a033ab">StartLoc</a>.</p>

</div>
</div>

### getToken() {#aaf78a1d51c3fdb8cf27c88c1ca771943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{CSKYAsmParser.cpp}::CSKYOperand::getToken ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>, <a href="#a5b054fa05e2cb08f31495157b5aaff70">Tok</a> and <a href="#a0fe109a97f1922d132a1dfdc52675b2fa37781a5be8694d18e72031f089ef91f1">Token</a>.</p>


<p>Referenced by <a href="#adfbeadbc6d68319d9559978a6d365e00">print</a>.</p>

</div>
</div>

### isConstpool() {#a95a0e595461e0016f6c307eb9302c598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isConstpool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a69735d9460f81c6cab80fc9935aa43cd">isConstPoolOp</a>.</p>

</div>
</div>

### isConstPoolOp() {#a69735d9460f81c6cab80fc9935aa43cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isConstPoolOp ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a0fe109a97f1922d132a1dfdc52675b2fa46acee502c8e0fb79a4f5766c6ed4dc9">CPOP</a> and <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>.</p>


<p>Referenced by <a href="#a95a0e595461e0016f6c307eb9302c598">isConstpool</a> and <a href="#a0f2458135443143a3f94c5a62d497a6f">isDataSymbol</a>.</p>

</div>
</div>

### isCSKYSymbol() {#a9cb07869c134c15fbc0d6b48d827d0e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isCSKYSymbol ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isDataSymbol() {#a0f2458135443143a3f94c5a62d497a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isDataSymbol ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a69735d9460f81c6cab80fc9935aa43cd">isConstPoolOp</a>.</p>

</div>
</div>

### isExtImm6() {#a97a44db62cf1fc6e69f073dbf1e15c63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isExtImm6 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#ab3b89384a7bd1cd36b086fb4c2b45e82">evaluateConstantImm</a>, <a href="#a680149bff79c86330b611b35156e302a">getImm</a>, <a href="#aa3fd7046f832525cda4acc8fc9e0aa08">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a>.</p>

</div>
</div>

### isImm() {#a09793ba5bf1799c2844d6874a46719b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isImm ()</td>
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

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a0fe109a97f1922d132a1dfdc52675b2fae6cdfc311fbb7f9ee1b3b89ba3e549ef">Immediate</a> and <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>.</p>

</div>
</div>

### isMem() {#a04d4df7e90d08b2eabc917387ed5787b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isMem ()</td>
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

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>

</div>
</div>

### isOImm() {#af8c034383cf8d9c5e91a4ed499c681a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned num&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isOImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#ab3b89384a7bd1cd36b086fb4c2b45e82">evaluateConstantImm</a>, <a href="#a680149bff79c86330b611b35156e302a">getImm</a>, <a href="#aa3fd7046f832525cda4acc8fc9e0aa08">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="#a9d57e323aa8928d008390cfc0774a2ec">isOImm12</a>, <a href="#a5fc188e9a8d5bcca62b9e4753307c04e">isOImm16</a>, <a href="#aac8847855febc99a582c22c9502752dd">isOImm3</a>, <a href="#aa9b270b995abbff123e5c79f86cf9829">isOImm4</a>, <a href="#ad6271e4be92f09f44747e9ce22e868d2">isOImm5</a>, <a href="#a08873f53446ab5dd2aee02737360b897">isOImm6</a> and <a href="#a77a10d298d3ed343d7253be98d71e9db">isOImm8</a>.</p>

</div>
</div>

### isOImm12() {#a9d57e323aa8928d008390cfc0774a2ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isOImm12 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>.</p>

</div>
</div>

### isOImm16() {#a5fc188e9a8d5bcca62b9e4753307c04e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isOImm16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>.</p>

</div>
</div>

### isOImm3() {#aac8847855febc99a582c22c9502752dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isOImm3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>.</p>

</div>
</div>

### isOImm4() {#aa9b270b995abbff123e5c79f86cf9829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isOImm4 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>.</p>

</div>
</div>

### isOImm5() {#ad6271e4be92f09f44747e9ce22e868d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isOImm5 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>.</p>

</div>
</div>

### isOImm6() {#a08873f53446ab5dd2aee02737360b897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isOImm6 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>.</p>

</div>
</div>

### isOImm8() {#a77a10d298d3ed343d7253be98d71e9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isOImm8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>.</p>

</div>
</div>

### isPSRFlag() {#a5519906431d13fc0c4cff7eb6ff8e809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isPSRFlag ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#ab3b89384a7bd1cd36b086fb4c2b45e82">evaluateConstantImm</a>, <a href="#a680149bff79c86330b611b35156e302a">getImm</a>, <a href="#aa3fd7046f832525cda4acc8fc9e0aa08">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isReg() {#a4e9b8dec485b89adcdd448343390effc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isReg ()</td>
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

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a> and <a href="#a0fe109a97f1922d132a1dfdc52675b2fa1f1e2cb3df3cc93d854ed375c23bd9b5">Register</a>.</p>

</div>
</div>

### isRegisterList() {#a636dd430d6ce22eaab127b74938fd49d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isRegisterList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a> and <a href="#a0fe109a97f1922d132a1dfdc52675b2fa81026409322963abb764ee5663b75e6f">RegisterList</a>.</p>


<p>Referenced by <a href="#a5c17938b7a6213e6cdb04762c7c91a08">isRegList</a>.</p>

</div>
</div>

### isRegisterSeq() {#a30539fea2253aa55aa1535edf7d4b6d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isRegisterSeq ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a> and <a href="#a0fe109a97f1922d132a1dfdc52675b2fa8a5271c4d20b8aab935f51381d0a9664">RegisterSeq</a>.</p>


<p>Referenced by <a href="#a097ad70c9670347503bca7f4c2d3d543">isRegSeqTemplate</a>.</p>

</div>
</div>

### isRegList() {#a5c17938b7a6213e6cdb04762c7c91a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isRegList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a63a47dab517558178e2f94a6c413c486">getRegList</a>, <a href="#a9c0be9264bc2cf05ed0fccb82f4c1c7e">isLegalRegList</a> and <a href="#a636dd430d6ce22eaab127b74938fd49d">isRegisterList</a>.</p>

</div>
</div>

### isRegSeq() {#a3bc484a2b4b4e2f052ebba4464a778cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isRegSeq ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a097ad70c9670347503bca7f4c2d3d543">isRegSeqTemplate</a>.</p>

</div>
</div>

### isRegSeqTemplate() {#a097ad70c9670347503bca7f4c2d3d543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned MIN, unsigned MAX&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isRegSeqTemplate ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a2fd47a756076d99f2f08295f610630ee">getRegSeq</a> and <a href="#a30539fea2253aa55aa1535edf7d4b6d2">isRegisterSeq</a>.</p>


<p>Referenced by <a href="#a3bc484a2b4b4e2f052ebba4464a778cd">isRegSeq</a>, <a href="#a2a6f7c89fcad69c083db6708ed769142">isRegSeqV1</a> and <a href="#a5de267b6662af9925cc3541d67a6ec6d">isRegSeqV2</a>.</p>

</div>
</div>

### isRegSeqV1() {#a2a6f7c89fcad69c083db6708ed769142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isRegSeqV1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a097ad70c9670347503bca7f4c2d3d543">isRegSeqTemplate</a>.</p>

</div>
</div>

### isRegSeqV2() {#a5de267b6662af9925cc3541d67a6ec6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isRegSeqV2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a097ad70c9670347503bca7f4c2d3d543">isRegSeqTemplate</a>.</p>

</div>
</div>

### isSImm() {#acdbc1487f391e78aa1b636227447099a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned num, unsigned shift = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isSImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#ab3b89384a7bd1cd36b086fb4c2b45e82">evaluateConstantImm</a>, <a href="#a680149bff79c86330b611b35156e302a">getImm</a>, <a href="#aa3fd7046f832525cda4acc8fc9e0aa08">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a>.</p>


<p>Referenced by <a href="#a6b674e59e4dabb31c06d53bc0b1b4e55">isSImm16Shift1</a> and <a href="#a30a1385e17f646621e3a78f3741ea011">isSImm8</a>.</p>

</div>
</div>

### isSImm16Shift1() {#a6b674e59e4dabb31c06d53bc0b1b4e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isSImm16Shift1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#acdbc1487f391e78aa1b636227447099a">isSImm</a>.</p>

</div>
</div>

### isSImm8() {#a30a1385e17f646621e3a78f3741ea011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isSImm8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#acdbc1487f391e78aa1b636227447099a">isSImm</a>.</p>

</div>
</div>

### isToken() {#a251be8cb301dfe4feeb7c767cbc635b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isToken ()</td>
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

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a> and <a href="#a0fe109a97f1922d132a1dfdc52675b2fa37781a5be8694d18e72031f089ef91f1">Token</a>.</p>

</div>
</div>

### isUImm() {#ad532c64ed131cfe08745e960e4c51746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned num, unsigned shift = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#ab3b89384a7bd1cd36b086fb4c2b45e82">evaluateConstantImm</a>, <a href="#a680149bff79c86330b611b35156e302a">getImm</a>, <a href="#aa3fd7046f832525cda4acc8fc9e0aa08">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a>.</p>


<p>Referenced by <a href="#a7c5760235fc53e6a6d90296001f10a27">isUImm1</a>, <a href="#a6ca16f6ac9d7f22d7afe10c73be5a21d">isUImm12</a>, <a href="#affcb13559ab137513ffd0f4219a03cb8">isUImm12Shift1</a>, <a href="#aea639d0b370c29060471e3f650d84a3d">isUImm12Shift2</a>, <a href="#a7cff9c35cf1ac9cd0a55defed64b7798">isUImm16</a>, <a href="#a14fd60e621e201d571b93f4db2b30d09">isUImm16Shift16</a>, <a href="#ae73dee159d511b6b729be34f1a46a8b4">isUImm16Shift8</a>, <a href="#a72dce4d8ff8e291219b30f37759a1f10">isUImm2</a>, <a href="#a6d9012e70868641adb0cabbdf024382e">isUImm20</a>, <a href="#a50b4b1f8a53801ae858fbeb81c04202e">isUImm24</a>, <a href="#ab4d4f99576a9d4d60eb9d5544040183f">isUImm24Shift8</a>, <a href="#a8679bbd6b778cca85e50697ead9eaff2">isUImm3</a>, <a href="#a22178c108295438aa12eea4972982fe1">isUImm4</a>, <a href="#a4e87b9c31a4dfe49c9f33f7b19411a53">isUImm5</a>, <a href="#ab4f40b5142c3e4e0432b8bb304a7b935">isUImm5Shift1</a>, <a href="#a77523165d03f68032b922fe562d8b2d5">isUImm5Shift2</a>, <a href="#af2a75b9d63e952fcde5f3657fe12627d">isUImm6</a>, <a href="#a9c9bdb38aafda73ce8bdacb8a2f23e72">isUImm7</a>, <a href="#a507a09500e5796160245523152f00403">isUImm7Shift1</a>, <a href="#aed6a7d5f2a3126bad797147853a5ed85">isUImm7Shift2</a>, <a href="#a49d9bb0c0111a2e0dde4c7dad5d4857e">isUImm7Shift3</a>, <a href="#ac5abcf11d32813821864d9e930627e68">isUImm8</a>, <a href="#ab69b2e5759ea42c3503e5168ed6f1f37">isUImm8Shift16</a>, <a href="#a8868ad3a690cd244634c7f79af476feb">isUImm8Shift2</a>, <a href="#ad5a2cce84c7c464a2002b96dd7a0de44">isUImm8Shift24</a>, <a href="#a93170b824e8cf8a7b7e511d2e81ef719">isUImm8Shift3</a> and <a href="#a3c5db595dd3b8d866b068a24ee7d8783">isUImm8Shift8</a>.</p>

</div>
</div>

### isUImm1() {#a7c5760235fc53e6a6d90296001f10a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm12() {#a6ca16f6ac9d7f22d7afe10c73be5a21d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm12 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm12Shift1() {#affcb13559ab137513ffd0f4219a03cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm12Shift1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm12Shift2() {#aea639d0b370c29060471e3f650d84a3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm12Shift2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm16() {#a7cff9c35cf1ac9cd0a55defed64b7798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm16Shift16() {#a14fd60e621e201d571b93f4db2b30d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm16Shift16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm16Shift8() {#ae73dee159d511b6b729be34f1a46a8b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm16Shift8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm2() {#a72dce4d8ff8e291219b30f37759a1f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm20() {#a6d9012e70868641adb0cabbdf024382e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm20 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm24() {#a50b4b1f8a53801ae858fbeb81c04202e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm24 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm24Shift8() {#ab4d4f99576a9d4d60eb9d5544040183f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm24Shift8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm3() {#a8679bbd6b778cca85e50697ead9eaff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm4() {#a22178c108295438aa12eea4972982fe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm4 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm5() {#a4e87b9c31a4dfe49c9f33f7b19411a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm5 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm5Shift1() {#ab4f40b5142c3e4e0432b8bb304a7b935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm5Shift1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm5Shift2() {#a77523165d03f68032b922fe562d8b2d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm5Shift2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm6() {#af2a75b9d63e952fcde5f3657fe12627d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm6 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm7() {#a9c9bdb38aafda73ce8bdacb8a2f23e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm7 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm7Shift1() {#a507a09500e5796160245523152f00403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm7Shift1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm7Shift2() {#aed6a7d5f2a3126bad797147853a5ed85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm7Shift2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm7Shift3() {#a49d9bb0c0111a2e0dde4c7dad5d4857e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm7Shift3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm8() {#ac5abcf11d32813821864d9e930627e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm8Shift16() {#ab69b2e5759ea42c3503e5168ed6f1f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm8Shift16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm8Shift2() {#a8868ad3a690cd244634c7f79af476feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm8Shift2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm8Shift24() {#ad5a2cce84c7c464a2002b96dd7a0de44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm8Shift24 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm8Shift3() {#a93170b824e8cf8a7b7e511d2e81ef719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm8Shift3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isUImm8Shift8() {#a3c5db595dd3b8d866b068a24ee7d8783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isUImm8Shift8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### isValidForTie() {#a56950afb2b5f6d3c0f598b69e6c45ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isValidForTie (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand">CSKYOperand</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a88892b58e78c13c97a82708d90d1b921">CSKYOperand</a>, <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a1eebdd79de2bf6787decb0bb6fc5bf59">Reg</a> and <a href="#a0fe109a97f1922d132a1dfdc52675b2fa1f1e2cb3df3cc93d854ed375c23bd9b5">Register</a>.</p>

</div>
</div>

### print() {#adfbeadbc6d68319d9559978a6d365e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CSKYAsmParser.cpp}::CSKYOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="#a0fe109a97f1922d132a1dfdc52675b2fa46acee502c8e0fb79a4f5766c6ed4dc9">CPOP</a>, <a href="#a795b1277e7e49407b1134db5db0422dc">getConstpoolOp</a>, <a href="#a680149bff79c86330b611b35156e302a">getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a3af25075605c9967bf441494fef34864">llvm::CSKYInstPrinter::getRegisterName</a>, <a href="#a63a47dab517558178e2f94a6c413c486">getRegList</a>, <a href="#a2fd47a756076d99f2f08295f610630ee">getRegSeq</a>, <a href="#aaf78a1d51c3fdb8cf27c88c1ca771943">getToken</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fae6cdfc311fbb7f9ee1b3b89ba3e549ef">Immediate</a>, <a href="#a73f3e0ed88e216fcc435b7c9e882f747">Kind</a>, <a href="#a1eebdd79de2bf6787decb0bb6fc5bf59">Reg</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa1f1e2cb3df3cc93d854ed375c23bd9b5">Register</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa81026409322963abb764ee5663b75e6f">RegisterList</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa8a5271c4d20b8aab935f51381d0a9664">RegisterSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a> and <a href="#a0fe109a97f1922d132a1dfdc52675b2fa37781a5be8694d18e72031f089ef91f1">Token</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a911af522a4aa66555a0a57c050710522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{CSKYAsmParser.cpp}::CSKYOperand anonymous{CSKYAsmParser.cpp}::CSKYOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>

</div>
</div>

### CPool {#a25c4d96e4fb9435f729c687f6414a418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstpoolOp anonymous{CSKYAsmParser.cpp}::CSKYOperand::CPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a> and <a href="#a795b1277e7e49407b1134db5db0422dc">getConstpoolOp</a>.</p>

</div>
</div>

### EndLoc {#a3d95afdd891e35f4a38639dc2cb0a4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{CSKYAsmParser.cpp}::CSKYOperand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a> and <a href="#aa020b00e4347ac858117d192aafa9ad8">getEndLoc</a>.</p>

</div>
</div>

### Imm {#aa3fd7046f832525cda4acc8fc9e0aa08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmOp anonymous{CSKYAsmParser.cpp}::CSKYOperand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a>, <a href="#ab3b89384a7bd1cd36b086fb4c2b45e82">evaluateConstantImm</a>, <a href="#a680149bff79c86330b611b35156e302a">getImm</a>, <a href="#a97a44db62cf1fc6e69f073dbf1e15c63">isExtImm6</a>, <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>, <a href="#a5519906431d13fc0c4cff7eb6ff8e809">isPSRFlag</a>, <a href="#acdbc1487f391e78aa1b636227447099a">isSImm</a> and <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### Kind {#a73f3e0ed88e216fcc435b7c9e882f747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{CSKYAsmParser.cpp}::CSKYOperand::KindTy anonymous{CSKYAsmParser.cpp}::CSKYOperand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a>, <a href="#a88892b58e78c13c97a82708d90d1b921">CSKYOperand</a>, <a href="#a795b1277e7e49407b1134db5db0422dc">getConstpoolOp</a>, <a href="#a680149bff79c86330b611b35156e302a">getImm</a>, <a href="#a82226e8082bf56eb3426cbc3eea25fda">getReg</a>, <a href="#a63a47dab517558178e2f94a6c413c486">getRegList</a>, <a href="#a2fd47a756076d99f2f08295f610630ee">getRegSeq</a>, <a href="#aaf78a1d51c3fdb8cf27c88c1ca771943">getToken</a>, <a href="#a69735d9460f81c6cab80fc9935aa43cd">isConstPoolOp</a>, <a href="#a09793ba5bf1799c2844d6874a46719b9">isImm</a>, <a href="#a4e9b8dec485b89adcdd448343390effc">isReg</a>, <a href="#a636dd430d6ce22eaab127b74938fd49d">isRegisterList</a>, <a href="#a30539fea2253aa55aa1535edf7d4b6d2">isRegisterSeq</a>, <a href="#a251be8cb301dfe4feeb7c767cbc635b3">isToken</a>, <a href="#a56950afb2b5f6d3c0f598b69e6c45ae8">isValidForTie</a> and <a href="#adfbeadbc6d68319d9559978a6d365e00">print</a>.</p>

</div>
</div>

### Reg {#a1eebdd79de2bf6787decb0bb6fc5bf59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegOp anonymous{CSKYAsmParser.cpp}::CSKYOperand::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a>, <a href="#a82226e8082bf56eb3426cbc3eea25fda">getReg</a>, <a href="#a56950afb2b5f6d3c0f598b69e6c45ae8">isValidForTie</a> and <a href="#adfbeadbc6d68319d9559978a6d365e00">print</a>.</p>

</div>
</div>

### RegList {#a2c5d699778e1dadd461df2c9b44e8be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegListOp anonymous{CSKYAsmParser.cpp}::CSKYOperand::RegList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a> and <a href="#a63a47dab517558178e2f94a6c413c486">getRegList</a>.</p>

</div>
</div>

### RegSeq {#ab18d807b225db0679487575c916f4722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegSeqOp anonymous{CSKYAsmParser.cpp}::CSKYOperand::RegSeq</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a> and <a href="#a2fd47a756076d99f2f08295f610630ee">getRegSeq</a>.</p>

</div>
</div>

### StartLoc {#a178a552fa7eb0c50b588306819a033ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{CSKYAsmParser.cpp}::CSKYOperand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a> and <a href="#a03e3b98e29ed23647b30db5cd57ab98b">getStartLoc</a>.</p>

</div>
</div>

### Tok {#a5b054fa05e2cb08f31495157b5aaff70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{CSKYAsmParser.cpp}::CSKYOperand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4ca99195c27268f9c7fc1cce995f92f6">CSKYOperand</a> and <a href="#aaf78a1d51c3fdb8cf27c88c1ca771943">getToken</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createConstpoolOp() {#ab931c884e85ca87c3ac707dfe2a17cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSKYOperand &gt; anonymous{CSKYAsmParser.cpp}::CSKYOperand::createConstpoolOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a0fe109a97f1922d132a1dfdc52675b2fa46acee502c8e0fb79a4f5766c6ed4dc9">CPOP</a>.</p>

</div>
</div>

### createImm() {#ada84f19885a95d7eb7218b96f28a8a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSKYOperand &gt; anonymous{CSKYAsmParser.cpp}::CSKYOperand::createImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a0fe109a97f1922d132a1dfdc52675b2fae6cdfc311fbb7f9ee1b3b89ba3e549ef">Immediate</a>.</p>

</div>
</div>

### createReg() {#aa3c81a9be6ecce267c7d22b9b9390416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSKYOperand &gt; anonymous{CSKYAsmParser.cpp}::CSKYOperand::createReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNo, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a0fe109a97f1922d132a1dfdc52675b2fa1f1e2cb3df3cc93d854ed375c23bd9b5">Register</a>.</p>

</div>
</div>

### createRegList() {#a87fe45f7faab0a040752d07ee871f124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSKYOperand &gt; anonymous{CSKYAsmParser.cpp}::CSKYOperand::createRegList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>, 4 &gt; &amp; reglist, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0fe109a97f1922d132a1dfdc52675b2fa81026409322963abb764ee5663b75e6f">RegisterList</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### createRegSeq() {#ad73648585f7b7fb9d014cfe008cadbed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSKYOperand &gt; anonymous{CSKYAsmParser.cpp}::CSKYOperand::createRegSeq (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNoFrom, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNoTo, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a0fe109a97f1922d132a1dfdc52675b2fa8a5271c4d20b8aab935f51381d0a9664">RegisterSeq</a>.</p>

</div>
</div>

### createToken() {#a85b77492d7449280048ddb0cccd3b972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSKYOperand &gt; anonymous{CSKYAsmParser.cpp}::CSKYOperand::createToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Reference <a href="#a0fe109a97f1922d132a1dfdc52675b2fa37781a5be8694d18e72031f089ef91f1">Token</a>.</p>

</div>
</div>

### evaluateConstantImm() {#ab3b89384a7bd1cd36b086fb4c2b45e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::evaluateConstantImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, int64_t &amp; Imm)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#aa3fd7046f832525cda4acc8fc9e0aa08">Imm</a>.</p>


<p>Referenced by <a href="#a97a44db62cf1fc6e69f073dbf1e15c63">isExtImm6</a>, <a href="#af8c034383cf8d9c5e91a4ed499c681a9">isOImm</a>, <a href="#a5519906431d13fc0c4cff7eb6ff8e809">isPSRFlag</a>, <a href="#acdbc1487f391e78aa1b636227447099a">isSImm</a> and <a href="#ad532c64ed131cfe08745e960e4c51746">isUImm</a>.</p>

</div>
</div>

### getListValue() {#a0f848c9950190e2f6c61a3e9832eb5f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{CSKYAsmParser.cpp}::CSKYOperand::getListValue (unsigned ListFrom, unsigned ListTo)</td>
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



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a87ea4b3846e4d8daf60afad674bb0fb0">addRegListOperands</a>.</p>

</div>
</div>

### isLegalRegList() {#a9c0be9264bc2cf05ed0fccb82f4c1c7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CSKYAsmParser.cpp}::CSKYOperand::isLegalRegList (unsigned from, unsigned to)</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a5c17938b7a6213e6cdb04762c7c91a08">isRegList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp">CSKYAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
